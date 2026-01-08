Request:
```
A new submission has been made for the IBM z/OS and LinuxONE Open Source Development Programs Resource Request Form. Below is a copy of the submission:

First Name

John


Last Name

Fox


Email Address

jfx1985@outlool.com


Open Source Project Name

Z-Phosphor


Open Source Project Public Repo URL

https://gitlab.com/foxie1985/z-phosphor


Which of these use cases aligns with your needs?

Develop and test open source software


Other details about how you will be this resource

am developing Z-Phosphor, an open-source high-performance vector visualization engine for z/OS. The project creates a bridge between modern high-velocity data streams (Python/Edge-processed) and legacy mainframe presentation layers (GDDM/HLASM).

The Goal: To demonstrate that the IBM z17 is the only platform capable of serving as a centralized Command & Control (C2) interface for handling massive, life-critical datasets securely and reliably at unfathomable scales.

Current Use Cases:

Orbital Mechanics (HPC): I have adapted the engine to ingest Celestrak TLE data, performing real-time orbital propagation for 25,000+ satellites. Z-Phosphor renders this as a rotating 3D globe natively on 3270 hardware, demonstrating the platform's ability to handle complex spatial mathematics directly on the host.

Computer Vision Telemetry: I am prototyping a module that ingests metadata from edge AI sensors (LIDAR, bounding boxes). This allows the mainframe to act as a low-latency 'Vision Dashboard' for logistics. I specifically aim to explore how the Spyre AI Accelerator can optimize these inferencing workloads to reduce latency further.

Mass-Scale Medical IoT: I am using the engine to visualize high-frequency medical telemetry. By rendering thousands of concurrent patient vital signs as a live topology map, I am demonstrating how z/OS can serve as the secure backend for population-scale health monitoring where transaction reliability is critical.

Resource Need: Access to a genuine z/OS environment is critical to benchmark the throughput limits of the 3270 data stream against the Telum II Data Processing Unit (DPU). My engine pushes 20fps+ vector updates, creating a high-interrupt I/O load that emulators cannot replicate. I need to validate that the new DPU architecture can handle these massive visualization transactions without latency, justifying the z17's role in next-gen HPC sectors.


User profile page

https://gitlab.com/foxie1985


Country

Australia


Which operating system are you interested in doing development for?

z/OS


Describe any previous open source contributions

Creator and maintainer of Zpectrum (https://gitlab.com/foxie1985/zpectrum), an MIT-licensed open-source project that successfully demonstrated audio-reactive visualization on IBM Mainframes using Python and REXX.

I am now developing its successor, Z-Phosphor, which migrates that codebase to utilise HLASM and GDDM. This shift from interpreted scripting to native Assembler is designed to unlock the high-performance throughput required for the HPC and telemetry use cases described above. My work focuses on bridging modern Python data streams with legacy mainframe execution environments.


Please paste your public SSH key for system access.

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQC3JeQF0m0jmOovUZBqRwkLGpPwgmvGUZlme+FAAVROM/X9OvckXkq0a3epqmByguId/zYG8bgKEIN2nfOMcZ/rjawHMrO/wOW4PvKy4AbmbtjV4xZCPLcp3d4uKcoP4HJvRa+Jw4bxA/eESnYyKJPHMX01DMAi/GJsySDVV013OP30XDVhMFSm2bKDRa7AohzZI2K2AJVx5gP4MiECIpRkUIKnzise5T70hNJF4oRPq5fODNMSVC4xKchEoxZa8weG85BJATFvg4mRBxvn3aMr7tmXIma6VyjzqSo/+7n6g8bKjUN9+4zgzfkTh2XgmLY0rhgyTP+UFKLUR1mYKJUBo6Nr4WN9A2FD4OwB2YnduZTLObmdhqtxPaP1KAT6MpLA+2uqaDdFVP5Z0zn2GLIBtUeK53BbCLcNxmEBwzsLkhThbNlIUs4MoBV/vwGA2NvGp430pA86ytJF4OtsM8ljV/IyMjEHVDNZuJFwGAKL6nu1lNNE8Cl36RCRE5IuvrAedw0BrWiqug3oGzg5Y+W9jvvzhLB/1UW/LXmlq2d1FZMghMJaiFm3vl8V5o9ZnLQTUVNNQH/QoPDqKA/4EXTTUBBdMlHOnDH7A9F6NsTcS5O+BAsYFcX8VOBwoP9cqa9vE62SC7iv4xq+FlpeKJkiTLgDGM/PjCdupzAruHCFuw== z-phosphor-ibm-access
```

Request:
```
Hello,
A new submission has been made for the IBM z/OS and LinuxONE Open Source Development Programs Resource Request Form. Below is a copy of the submission:
First Name
Aaron

Last Name
Teo

Email Address
taronaeo@gmail.com

Open Source Project Name
Llama.cpp - open-source C/C++ inference engine for Large Language Models with minimal dependencies

Open Source Project Public Repo URL
https://github.com/ggml-org/llama.cpp

Which of these use cases aligns with your needs?
Develop and test open source software

Other details about how you will be this resource
While working at IBM Technologies (Singapore) previously during my internship, I had worked on the IBM zDNN accelerator for Llama.cpp and contributed it upstream. This contribution was met with praise from industry players looking to run LLM workloads on their IBM z17 mainframes, where a noticeable 134.32% performance increase using the IBM zDNN accelerator was seen.

I will be using this resource to continue the research and development (R&D) of the IBM zDNN backend for Llama.cpp and implement more support. Currently, the IBM zDNN backend for Llama.cpp supports only matrix multiplication at F32, F16, and BF16 data types, and I've had IBM customers such as Erik Janssen contact me on LinkedIn with interest in support for quantized models, which will be my next point of research, as there would be substantial gains with zDNN.

Apart from the quantized matrix multiplication research, I will also be looking into support for Flash Attention, Matrix Multiplication by ID (for MoE models) and general operations support for the zDNN backend, wherever zDNN can gain performance. And I will be making all these contributions available upstream.

As of now, I do not have access to an IBM z17 mainframe to test my code and conduct benchmarks, thus, the IBM zDNN backend for Llama.cpp is at a standstill with no further developments made since the initial contribution to upstream.

User profile page
https://github.com/ggml-org/llama.cpp/pulls?q=is%3Apr+author%3Ataronaeo+

Country
Singapore

Which operating system are you interested in doing development for?
Linux

Linux Distribution(s)
Ubuntu

Resources requested
IBM z17 Mainframe, 1 LPAR, minimally 2 IFLs (NOSMT), 64 GB memory, 160 GB storage, CPU Polarization set to horizontal (or if possible, set to vertical:high).
```

Request (Hibernate)**
TODO: Igor to reach out about IBM internal systems, could OSS use another database instead of db2
```
Hello,

A new submission has been made for the IBM z/OS and LinuxONE Open Source Development Programs Resource Request Form. Below is a copy of the submission:

First Name

Yoann


Last Name

Rodiere


Email Address

yoann@hibernate.org


Open Source Project Name

Hibernate


Open Source Project Public Repo URL

https://github.com/hibernate/hibernate-orm


Which of these use cases aligns with your needs?

Set up an open source CI/CD pipelineDevelop and test open source software


Other details about how you will be this resource

While the Hibernate project is open-source and owned by the Commonhaus Foundation (a Florida non-profit, see https://www.commonhaus.org/), most core contributors are IBM employees. I am, too, and can be reached at yrodiere@ibm.com.

As we were recently moved from Red Hat to IBM, many projects we and our coworkers work on are preparing for integration in (or as) IBM products.

In anticipation of this integration, and ahead of product work, we would like to start work *upstream*, in the open-source community -- as we always do.
The most obvious item on the agenda would be a better integration of Hibernate with "DB2 for Z". This requires access to an instance of DB2 for Z, which we do not have in our community infrastructure at the moment.

Note we do already have access to LinuxOne and regularly test our software on Linux + s390x. Our request is for a separate s390x instance *running z/OS* and preferably *with Semeru runtimes and DB2 pre-installed* (otherwise I'll try to figure out how to install them).

We would use this instance to run integration tests as part of our CI process. The goal would be to check that SQL generated by Hibernate ORM works as expected on DB2 for Z.
We would need the instance available either 24/7, or on specific schedule every day for a few hours.


Country

United States


Which operating system are you interested in doing development for?

z/OS


Describe any previous open source contributions

I am a core member of the Hibernate team, along with ~10 teammates also working at IBM.
We contribute daily to open-source projects, mainly Hibernate ones, but also Quarkus.
See:

* All top 8 contributors to Hibernate ORM: https://github.com/hibernate/hibernate-orm/graphs/contributors
* The #10 and #11 contributors to Quarkus: https://github.com/quarkusio/quarkus/graphs/contributors

The Hibernate project is a JPA implementation that powers persistence into relational databases in various popular Java platforms, from Spring to Quarkus to WildFly. It is the most popular JPA implementation and a very popular way to persist data in Java.

Hibernate is mostly relevant to IBM as:

1. A key component of existing Red Hat products: Red Hat build of Quarkus, Red Hat Enterprise Application Platform, Red Hat build of Keycloak.
2. A key component of the upcoming Quarkus offering at IBM.
3. A potential key component of future versions of Websphere/Liberty (still being discussed).
```


**Request:**
Conclusion: Rejected

```
Hello,
A new submission has been made for the IBM z/OS and LinuxONE Open Source Development Programs Resource Request Form. Below is a copy of the submission:
First Name
Nick
Last Name
Bolton
Email Address
nick@symless.com
Open Source Project Name
Deskflow
Open Source Project Public Repo URL
https://github.com/deskflow/deskflow
Which of these use cases aligns with your needs?
Develop and test open source softwareSet up an open source CI/CD pipeline
Other details about how you will be this resource
We are developing and maintaining Deskflow (née Synergy community edition), an open source C++ mouse and keyboard sharing tool, and want to extend support for IBM Z environments (z/OS and LinuxONE). Access to this development resource program will be used to build and test on big-endian systems. Developers use Deskflow to share a mouse and keyboard between IBM Z consoles and Linux dev systems. As well as improving productivity for IBM Z developers, as a famous repo ~20k stars, the fixes and documentation we contribute back to the community can be used as good examples for others who port and run open source tools on IBM Z. Users from our community requested that we add IBM Z to our CI.
User profile page
https://github.com/nbolton
Country
United Kingdom
Which operating system are you interested in doing development for?
z/OS
Describe any previous open source contributions
20 years contributing to open source through Synergy and now Deskflow.
```

**Request:**
Conclusion: Rejected
```
Hello,

A new submission has been made for the IBM z/OS and LinuxONE Open Source Development Programs Resource Request Form. Below is a copy of the submission:

First Name

Toshaan


Last Name

Bharvani


Email Address

toshaan@vantosh.com


Open Source Project Name

PowerZX


Open Source Project Public Repo URL

https://git.powerzx.org


Which of these use cases aligns with your needs?

Develop and test open source softwareSet up an open source CI/CD pipeline


Other details about how you will be this resource

PowerZX is an extension on z/OS that aims to provide open source packages for usage on x390x.
The idea is that we rebuild several packages in line with current PowerEL baseline versions and patches, as such we want to build an experience for developers and users to have similar experience with just the need to recompile and run.
While we do know that this is not going to be always possible, we do expect to have few changes/differnces between the baselines.
*** Please note that tihs is a new project that we are starting in line with other projects we will be building on, like PowerEL, currently there are no resources publicly available due to having limited testing capability ***
We do have PowerEL for IBM Power ppc64le and ppc64 (www.powerel.org), and will be staring an effort for IBM AIX and IBM i (still to be made public soon), with the same initial idea and logic, as wer do also have PowerEL for IBM Mainframe s390x, we think having this for z/OS would be relevant.


User profile page

https://git.powerzx.org


Country

Belgium


Which operating system are you interested in doing development for?

z/OS


Describe any previous open source contributions

3 LPAR
- Main Builder - z/OS 3.2 - 4 CP - 32GB RAM - 275GB disk
- Secondary Builder - z/OS 3.2 - 2 CP - 32GB RAM - 275GB disk
- Tester / QA - z/OS 3.2 - 1 CP - 16GB RAM - 125GB disk

```
