---
stylesheet: https://cdnjs.cloudflare.com/ajax/libs/github-markdown-css/2.10.0/github-markdown.min.css
body_class: markdown-body
css: |-
  .page-break { page-break-after: always; }
  .markdown-body { font-size: 11px; font-family: monospace; }
  .markdown-body pre > code { white-space: pre-wrap; }
pdf_options:
  format: a4
  margin: 15mm 15mm 
---

# Arindam Das
(+91) 98316 57983 • dasarindam.mails@gmail.com • Baidyabati, India • [github.com/arindas](https://github.com/arindas)

## Description
Specializes in distributed systems, deep learning inference and AI SaaS at scale.

Generalist capable of architecting and implementing cloud-native software services, for any domain. I primarily have 
experience in medical imaging, real-time document processing and business inventory management.

## Technical Skills
- __Languages__: C, C++, Java, Python, Golang, Rust, Javascript, Typescript, SQL
- __Frameworks and Libraries__: Django, Tensorflow, Pytorch, React, Glommio
- __Tools__: Git, Vim, Neovim, Awk, Sed
- __DevOps__: Linux, Docker, Bash, Zsh, Github Actions, Gitlab CI, Terraform
- __Databases__: PostgreSQL, GCP Cloud Firestore, SQLite
- __Cloud__: AWS{S3, EC2, Lightsail}, Firebase, GCP{Instances, PubSub, Cloud Storage}, Azure{Instances}

## Soft Skills
Agile Software Development, Problem Solving, System Design, Technical Content Delivery

## Experience
<h3>MLOps Engineer, Medical Imaging AI Services, Claritas Healthtech (06/2020 - Present)</h3>

<b>Responsibilities<b>

- Provisioning infrastructure for researchers to train and experiment with deep learning models
- Developing distributed deep learning inference services and corresponding client web applications
- Deploying and maintaining said applications on the Google Cloud Platform

<b>Projects<b>

<h5>Propreitary file storage solution build on top of GCS</h5>
File storage solution built on top of Google Cloud Storage with additional support for bucket creation and user 
access authorization at the level of buckets. Implemented as a golang web service with the golang google-cloud-sdk,
along with a frontend React client application.

This solution enabled us to receive sensitive data from different medical institutions without providing access to our GCP infrastructure. 

<h5>Distributed deep learning inference</h5>
Distributed deep-learning based diagnosis on medical images for a variety of diseases. Implemented as an event-driven suite of 
microservices, in golang and python. We use golang for the web serving infrastructure and python for inference. The services talk 
to each other using Google Cloud PubSub. Additionaly there's a React Dashboard for visualizing medical images,
requesting diagnosis and viewing reports.

We were able to reduce turnaround time for a new disease prediction service deployment by 10x, along
with improved audit record keeping of all predicted reports.

<br/>

<h3>Solution Architect, DeepWrex Technologies (04/2018 - 06/2020)</h3>

<b>Responsibilities</b>
- Architect cloud based solutions for machine learning software services.
- Assist researchers in implementing deep learning research papers.
- Iterating from research PoC to production.

<b>Projects</b>
- A real-time named entity recognition system for medical reports. This was an in house, economic alternative to
AWS Medical Comprehend, which didn't exist at the time. This was implemented as a suite of C++ microservices, with
intermediate data storage on AWS S3. These services talked to each other with Kafka (using rdkafka)
- A scalable black and white image colourization system, deployed using "Pytorch Serve" and FastAPI on AWS. We 
implemented the instance aware image colourization paper.

<h3>Satellite Onboard Computer RTOS Research Student, KIITSAT (04/2018 - 05/2019)</h3>

- Developed a shell capable of spawning programs and organizing pipes
- Developed a minimal kernel for armv6 (on Raspberry Pi 3) with basic memory management and TTL based I/O Support
- Trained fellow team members on OS concepts

<!--
<h3>VR 3d Game Development Instructor, CampK12 (03/2020 - 06/2020)</h3>

<b>Responsibilities</b>
- Teaching K12 students about game development which entailed:
  - Problem solving skills
  - Basic Programming using Javascript
  - Trigonometry
  - _Patience and Perseverance_

Some projects that I taught to students can be found at https://github.com/arindas-campk12
-->

## Education
- <h3>B.Tech in Computer Science and Engineering</h3> 
  KIIT University, 06/2017 - 06/2021 • CGPA: 9.44 • SGPA 8th Semester: 9.69

## Open Source Projects
- [laminarmq](https://github.com/arindas/laminarmq): A scalable, distributed message queue powered by a segmented, partitioned, 
replicated and immutable log. It is a resource efficient alternative to Apache Kafka.


- [generational-lru](https://github.com/arindas/generational-lru): A generational arena based LRU Cache implementation
  in 100% safe rust. All allocations are based off a vector.


- [sangfroid](https://github.com/arindas/sangfroid): A load-balanced thread pool implemented in Rust using only the 
  standard library. Worker threads are managed with binary heap and are prioritized by the number of pending jobs.


- [quartz](https://github.com/arindas/quartz): A shared memory parallelized ray tracer using OpenMP.
  _Speciality:_ Non recursive. Traditionally ray tracers are tail recursive. Image formats supported: PPM


- [mac-on-linux-with-qemu](https://github.com/arindas/mac-on-linux-with-qemu): Runs MacOS on Linux with the QEMU
  KVM Hypervisor with some python utility scripts for downloading the disk images and shell scripts for starting QEMU.


- [riakv](https://github.com/arindas/riakv): An append-only key-value store, with checksum based record validation.
  It support both in-memory usage and persisting records to the disk.


- [elevate](https://github.com/arindas/elevate): Barebones zero dependency HTTP File upload server in Go.


- [bheap](https://github.com/arindas/bheap): A Rust generic binary max heap implementation. It allows dynamic 
  definition of the comparison function for the underlying domain at runtime.
