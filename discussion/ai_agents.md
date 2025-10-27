# AI Agents for z/OS Porting

## 1. OSS Porting Agent

**Goal:**  
Automate and simplify the process of porting open-source software (OSS) to z/OS.

**Description:**  
An AI-driven porting tool that integrates:

- [BobShell](#)
- [zopen MCP Server](https://github.com/zopencommunity/zopen-mcp-server)
- `AGENTS.md` context files

**Automated Tasks:**
- Identify project repository, build system, language, etc.
- Build the latest stable release
- Resolve build and test issues
- Create patches
- Create repositories
- Create CI/CD jobs
- Publish changes to repository
- Publish releases

This enables a fully automated porting workflow — from source discovery through build and verification.  
**Status:** In progress

---

## 2. Problem Analysis Agent

**Goal:**  
Accelerate problem determination and root-cause analysis.

**Description:**  
Combines a Problem Determination Analyzer with a z/OS RAG (Retrieval-Augmented Generation) approach.

**Key Features:**
- Stores historical patches and issue resolutions in a vector database
- Performs similarity searches to find related past issues
- Provides relevant solutions as context to the LLM
- Suggests or auto-generates potential fixes

**Repository:**  
Private repo — [zos-porting-rag](https://github.com/IgorTodorovskiIBM/zos-porting-rag)

**Enhancement:**  
Integrate into CI/CD pipelines to suggest fixes for common build or test failures.  
**Status:** In progress

---

## 3. Upstreaming Agent

**Goal:**  
Automate contribution of z/OS ports to upstream projects.

**Automated Tasks:**
- Identify upstream repository
- Build the latest development release
- Apply stable release patches
- Resolve build and test issues
- Create and submit pull requests or mailing list patches
- Summarize and submit changes
- Read and apply community feedback

---

## 4. Currency Agent

**Goal:**  
Keep zopen ports synchronized with upstream releases.

**Description:**  
Leverages “bump” to monitor new upstream releases.  
When updates fail, the agent triggers:
- The **Problem Analysis Agent** to investigate causes
- Automated rebuilds with AI patch suggestions
