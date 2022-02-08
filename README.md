**Arindam Das**
- (+91) 98316 57983
- Baidyabati, India
- [github.com/arindas](https://github.com/arindas)

## Description
Specializes in distributed systems, deep learning inference and AI SaaS at scale.

Generalist capable of architecting and implementing cloud native software services, for any domain. I primarily have 
experience in medical imaging, real time document processing and business inventory management.

## Technical Skills
C, C++, Java, Golang, Rust, Python, Django, Tensorflow, Pytorch, Javascript, React, SQL, Postgres, Git, Docker, DevOps, MLOps, Linux, AWS, GCP, Firebase

## Soft Skills
Agile Software Development, Technical Teaching

## Experience
- Full Stack Engineer, Medical Imaging AI Services, Claritas Healthtech Pte. Ltd. (06/2020 - Present)
  
  Responsibilities:
  - Developing distributed deep learning inference services and corresponding client web applications 
  - Deploying and maintaining said applications on the Google Cloud Platform
  
  Projects:
  - File storage solution built on top of Google Cloud Storage with additional support for bucket creation and user 
  access authorization at the level of buckets. Implemented as a golang webservice with the golang gooogle-cloud-sdk,
  along with a frontend React client application. Authentication: Firebase Auth. DB: Google Cloud Firestore.<br>
  This solution enabled us to receive sensitive data from different medical institutions without providing access to  
  our GCP infrastructure.
  - Distributed deep learning based diagnosis on medical images for a variety of diseases. Implemented as a suite of 
  microservices, in golang and python. We use golang for managing data and python for inference. The services talk 
  to each other using Google Cloud PubSub.<br>
  Authentication: Firebase Auth. DB: Google cloud firestore.<br>
  We were able to reduce turn around time for a new disease prediction service deployment by 10x, along
  with improved audit record keeping of all predicted reports.

<br>

- Solution Architect, DeepWrex Technologies (04/2018 - 06/2020)
  
  Responsibilities:
  - Architect cloud based solutions for machine learning software services.
  - Assist researchers in implementing deep learning research papers.
  - Iterating from research PoC to production.
  
  Projects:
  - A real time named entity recognition system for medical reports. This was an in house, economic alternative to
  AWS Medical Comprehend, which didn't exist at the time. This was implemented as suite of C++ microservices, with
  intermediate data storage on AWS S3. These services talked to each other with Kafka (using rdkafka)
  - A scalable black and white image colorization system, deployed using "Pytorch Serve" and FastAPI on AWS. We 
  implemented the instance aware image colorization paper.

<br>

- Satellite Onboard Computer RTOS Research Student, KIITSAT
  - Developed a shell capable of spawning programs and organizing pipes
  - Developed a minimal kernel for armv6 (on Raspberry Pi 3) with basic memory management and TTL based I/O Support
  - Trained fellow team members on OS concepts

<br>

- VR 3d Game Development Instructor, CampK12 (03/2020 - 06/2020)
  
  Responsibilities:
  - Teaching K12 students about game development which entailed:
    - Problem Solving skills
    - Basic Programming using Javascript
    - Trigonometry
    - _Patience and Perseverance_
  
  Some projects that I taught to students can be found at https://github.com/arindas-campk12

## Education
- B.Tech in Computer Science and Engineering<br> 
  KIIT University, 06/2017 - 06/2021<br>
  CGPA: 9.44<br>
  SGPA 8th Semester: 9.69<br>

- ISC, Higher Secondary<br>
  Don Bosco Bandel, 2005 - 2017<br>


## Side Projects
- [sangfroid](https://github.com/arindas/sangfroid): A load balanced thread pool implemented in Rust using only the 
  standard library. Worker threads are managed with binary heap and are prioritized by the number of pending jobs.


- [quartz](https://github.com/arindas/quartz): A shared memory parallelized ray tracer using OpenMP.
  _Speciality:_ Non recursive. Traditionally ray tracers are tail recursive. Image formats supported: PPM


- [mac-on-linux-with-qemu](https://github.com/arindas/mac-on-linux-with-qemu): Runs MacOS on Linux with the QEMU
  KVM Hypervisor with some python utility scripts for downloading the disk images and shell scripts for starting QEMU.


- [riakv](https://github.com/arindas/riakv): An append only key value store, with checksum based record validation.
  Originally inspired from the Rust In Action Book by Tim McNamara with enhancements for reading from in memory buffers,
  serializing and storing the index to disk, futher application of DRY principles and comphrehensive tests.

