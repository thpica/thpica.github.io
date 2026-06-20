# Thomas Picariello
**Staff Software Engineer** in Zurich, Switzerland  

![profile_picture](profile.png) | **Contact**
 | - thpica@gmail.com
 | - +41 77 973 65 35
 | - https://www.linkedin.com/in/thpica/
 | - https://github.com/thpica

## Profile
Staff Software Engineer with 10 years of experience designing and operating high-throughput distributed systems and multi-cloud infrastructure (GCP/AWS). Specialized in the AR/wearables space, with technical ownership spanning low-level C++ engine optimizations to global-scale Kubernetes orchestration. Proven history of leading cross-functional teams to deliver highly available, secure platforms from the ground up.

## Technical Skills

- **Core Programming Languages:** Go (Golang), C++ (Modern C++11/14/17), Python, TypeScript, JavaScript
- **Cloud & Orchestration Infrastructure:** Kubernetes (K8s), Google Cloud Platform (GCP), Amazon Web Services (AWS), Terraform, Istio Service Mesh
- **Data Engineering & Databases:** PostgreSQL, MongoDB, Elasticsearch, Data Lakes
- **Architectural Paradigms:** Distributed Systems, Multi-Cloud Architecture, Inter-Process Communication (IPC), Microservices, Split Rendering
- **Security & Identity Protocols:** OAuth2, OpenID Connect (OIDC), Keycloak, Zero-Trust Access Control

## Professional Experience

### Company: Magic Leap

**Total Tenure:** December 2017 – Present  
**Role:** Staff Software Engineer  
**Core Focus:** Developing specialized cloud and device-side software infrastructure for Augmented Reality (AR) wearable devices across three flagship initiatives.

#### Project: Android XR (Strategic Partnership with Google)

**Primary Tech Stack:** C++, OpenXR, Flatbuffers, Inter-Process Communication (IPC)  
**Description:** Contributed to Impress, an in-house C++ 3D game engine serving as a core building block for Android XR, Google Maps, Google Lens, and Google Search.  
**Accomplishments:** 
- Implemented automated security testing (Flatbuffers fuzzing) on critical Inter-Process Communication (IPC) API surfaces for split rendering systems. It identified multiple critical vulnerabilities in production systems.
- Led a cross-functional engineering team to integrate custom material support and a new OpenXR extension into the Impress Split Engine.

#### Project: ARCloud (On-Premise Digital Twin Platform)
**Primary Tech Stack:** Go (Golang), Kubernetes, GKE, EKS, Terraform, Istio, Keycloak, OAuth2/OIDC  
**Description:** Architected a multi-service Kubernetes platform handling identity management, access control, colocated device presence, and collaborative real-time digital twin data syncing (including spatial anchors, world meshes, and sparse maps).  
**Accomplishments:**
- Built a high-throughput batch job microservice handling large-scale sparse map merging and automated world mesh generation.
- Maintained highly available, shared Go (Golang) microservices across a multi-cloud stack featuring Google Kubernetes Engine (GKE) and Amazon Elastic Kubernetes Service (EKS) managed by Istio service mesh and deep observability tooling.
- Engineered and deployed secure identity infrastructure utilizing Keycloak (OAuth2/OIDC) to enforce access-control guarantees across distributed services.
- Managed end-to-end multi-cloud infrastructure deployments on GKE and EKS via Terraform.
- Spearheaded the development of a real-time collaborative C++ prototype enabling on-device spatial visualization of active digital twin synchronization.
- Mentored and guided junior-to-senior software engineers on technical design patterns, code quality, and cloud architecture.

#### Project: Datalab (Large-Scale Perception Data Platform)
**Primary Tech Stack:** Python, C++, Kubernetes (GKE), Custom K8s Controllers  
**Description:** Co-designed and operated multiple generations of an internal batch computing platform and dedicated data lake designed to train and evaluate computer vision and perception algorithms.  
**Accomplishments:**
- Drastically increased platform reliability, scale, and performance efficiency while scaling logging, infrastructure monitoring, and automated testing frameworks.
- Developed and maintained highly complex Python microservices utilizing custom Kubernetes controllers.
- Streamlined engineering iterations for all internal perception and machine learning teams by providing standardized pipelines for accurate evaluation metrics.
- Programmed a high-performance C++ codec used for low-latency recording and playback of raw sensor data on wearable devices.
- Owned critical platform services end-to-end on GKE, establishing Service Level Objectives (SLOs), directing multi-region capacity planning, and organizing internal incident response procedures.
- Enforced strict security compliance and data isolation parameters to safeguard Personally Identifiable Information (PII).

### Company: Localbini
**Tenure:** September 2015 – October 2017  
**Role:** Startup Chief Technology Officer (CTO)  
**Core Focus:** Directed the end-to-end technical strategy, architecture design, and execution of a global online marketplace platform for guided travel experiences, managing a multi-functional team of 10 professionals.  
**Accomplishments:** 
- Architected the complete software platform from the ground up, including backend services, web applications, mobile deployments (iOS/Android), and user experience/user interface (UX/UI) schemas.
- Successfully launched, deployed, and scaled the platform production applications.
- Created a highly collaborative, inclusive, and high-performing workplace environment across a multi-cultural engineering department.

## Education
**Bachelor of Science (BS) in Information Communication Systems**  
*Specialization:* Electrical Engineering and Embedded Computer Science  
*Format:* Tri-National degree completed across three countries and academic institutions:
- **Switzerland:** Fachhochschule Nordwestschweiz (FHNW), Brugg AG
- **Germany:** Hochschule Furtwangen (HFU), Furtwangen-im-Schwarzwald
- **France:** Université de Haute-Alsace (UHA), Mulhouse

## Languages
- **French:** Native Speaker
- **English:** Professional Working Proficiency (C1 Level)
- **German:** Professional Working Proficiency (C1 Level)

## Technical Side Projects
**High-Frequency Trading Data Processing Pipeline**
**GitHub Repository:** https://github.com/thpica/BidAskSpread  
**Context:** Independent academic collaboration with a Master of Science (MSc) student at the University of St. Gallen.  
**Impact:** Optimized an analytical data ingestion pipeline built to process terabytes of raw financial trading data. Replaced resource-intensive legacy Matlab scripts with an optimized, high-performance C++ implementation, reducing execution runtime requirements from months down to under a week on standard consumer hardware.

_Updated: June 2026_
