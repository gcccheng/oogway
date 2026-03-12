---
layout: cv
title: Gang Cheng's CV
---
# Gang Cheng 

Red Hat Certified Architect, Infrastructure/DevOps/DevEx/Platform Engineer

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat Bio</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">Linkedin page</a>
</div>

## Summary

Gang is a self-motivated person, and he believes that the mindset of continuous learning and the ability to quickly adapt to new technologies are core competencies for a professional IT engineer. Throughout his career, Gang has proactively built expertise in managing modern infrastructure and platform through an ever-growing list of projects, certifications, workshops, conferences, courses, industry peers and through AI. His efforts and expertise were recognized when he received the honor of being awarded and titled as the Red Hat Certified Professional of the Year 2024(if you are curious of what it is, click Red Hat Bio on top for more info). 

In addition to his expertise in Red Hat, Gang has expanded his skills across DevOps engineering, platform engineering, and site reliability engineering. He has worked in both small and large teams, taking on roles such as System Administrator, Infrastructure Engineer, DevOps Engineer, Developer Experience (DevEx) 
 Engineer, and Platform Engineer — or a combination of them all, depending on project requirements. In the era of AI-driven engineering, Gang is also actively exploring how artificial intelligence can assist platform and infrastructure work. This includes AI-assisted troubleshooting, automation generation, infrastructure documentation, and improving developer productivity through intelligent tooling. Rather than viewing AI as a replacement for engineers, he sees it as a powerful collaborator that enhances decision-making, accelerates problem-solving, and helps engineers focus on higher-level architectural thinking.

No matter what title or environment, Gang adapts quickly to create value for the business through strong communication skills and a collaborative mindset.


## Employment

`2025-Now`  
***<font size="3">Senior Platform Engineer — Appear TV, Oslo</font>***

At Appear, Gang works on building and maintaining a modern, scalable infrastructure powering developer productivity and high-performance applications. His work focuses on bare-metal Kubernetes, GitOps, observability, storage, CI/CD automation, and platform security.

`project`
**NVIDIA GPU Cluster & Model Serving Platform**

Responsibilities：

Designed and delivered **platformised NVIDIA GPU cluster capabilities**, defining GPU resource governance and service‑oriented delivery paths.
Standardised GPU foundations using **GPU Operator**, establishing reusable cluster baselines.
Introduced **Time Slicing** and **MPS** to enable fine‑grained GPU sharing and multi‑tenant concurrency.
Brought **GitLab Runner** GPU workloads into platform scheduling with defined policies for GPU pipelines.
Integrated GPU observability into the platform stack, covering **utilisation, inference latency, and throughput**.
Enforced access control and policy guardrails for GPU workloads via **Kyverno**.
Coordinated R&D and platform teams to operationalise model serving and inference workflows.

Value Created：

Delivered a governable, observable, and rollback‑safe GPU platform for reliable model serving.
Improved GPU utilisation and delivery efficiency through multi‑tenant optimisation and elastic scaling.

`project`
**Autonomous Platform SRE Agent (AI-Driven Operations MVP)**

Responsibilities：

Designed and built a modular autonomous SRE agent to reduce operational toil and automate repetitive platform engineering tasks, enabling a shift from reactive alerting to proactive remediation.
Architected a Python-based orchestrator framework with pluggable expert modules (Kubernetes, Vsphere, and supply-chain intelligence) to handle multi-domain infrastructure operations.
Implemented a “Brain + Tools” architecture, where the agent scans infrastructure APIs (Kubernetes and Vsphere), detects operational violations, and leverages LLM reasoning (GPT-4o) to analyse root causes and generate remediation strategies rather than simply reporting errors.
Built a Safety Engine & Policy Gatekeeper to constrain AI autonomy: the agent can automatically remediate low-risk issues (e.g., restarting stalled VMs or resolving policy violations), while high-risk changes require human approval.
Developed a Mission Control Dashboard using Flask and HTMX, providing visibility into the agent’s reasoning process and enabling engineers to review and approve remediation actions with one-click execution.
Solved the immutable pod remediation challenge by enabling semantic reasoning to identify and patch the parent controllers (Deployments/StatefulSets) instead of transient pods.
Integrated a software supply-chain intelligence module capable of scanning Terraform and Ansible repositories, analysing GitHub release notes, and performing semantic risk analysis before recommending dependency upgrades.

Value Created：

Reduced operational toil by automating classification and remediation of hundreds of infrastructure and security policy violations (e.g., Kyverno alerts and platform health checks).
Shifted maintenance left by transforming routine dependency updates into a structured review-and-approval workflow, accelerating platform upgrade cycles.
Demonstrated safe AI-assisted operations, enabling autonomous execution of L1-level SRE tasks while freeing senior engineers to focus on architecture and platform evolution.
Established a foundation for AI-augmented platform operations, lowering the barrier for engineers to leverage LLM capabilities while maintaining governance and operational safety.

`project`
**CISO Partnership & Platform Security Governance**

Responsibilities：

Built and implemented **Kyverno Policy‑as‑Code** as the core platform security governance mechanism.
Led security governance reviews and implementation paths, aligning security controls with business requirements.
Reviewed platform baselines to identify key risks and vulnerabilities.
Designed and maintained **Validating** and **Mutation** policies, continuously iterating the policy library.
Delivered GitOps‑driven security policies for auditability, traceability and rollback.
Worked closely with the CISO and security architects to implement security and compliance controls across Kubernetes and DevOps environments, supporting IPO readiness and ISO 27001 certification.
Delivered platform‑level security hardening, including RBAC/IAM governance, network policies, secrets management, vulnerability remediation, image scanning, supply‑chain security (SBOM/signing), and audit logging.

Value Created：

Established a platform‑level security governance system with auditable controls and compliance readiness.
Balanced security requirements with delivery efficiency by aligning policies to business needs.


`project`
**Internal Self-Hosted AI Platform**

Delivered an internal AI/LLM enablement platform to support engineering use-cases such as log and telemetry analysis, documentation generation, incident explanation and code assistance.

Responsibilities：

Acted as technical owner, leading **platform architecture, capability layering and governance model**.
Defined roadmap and delivery standards, ran architecture reviews, and coordinated cross‑team execution.
Mentored junior engineers through task decomposition and peer reviews to improve delivery quality.
Evaluated multiple LLM backends and tools (hosted APIs and local inference) with a focus on **latency, concurrency characteristics, token cost and model behaviour**.
Designed a containerised deployment model on Kubernetes, including access control, team isolation and integration with existing SSO / developer tooling.
Explored model‑selection strategies by comparing latency, output quality and token usage across different LLM providers (OpenAI, RequestyAI, local Llama variants), identifying which models were most suitable for specific request types.
Implemented basic prompt governance, usage logging and cost visibility, laying groundwork for **responsible AI and auditability**.
Worked with several R&D teams to promote AI‑assisted engineering practices and capture feedback for future platform evolution (e.g. RAG, code search, knowledge base integration).
  
Value Created：

Established the company’s first **unified internal AI entry point and platform capability layer**, significantly lowering the barrier for engineers to use LLMs in daily work.
Shifted AI usage from ad‑hoc, individual experimentation to **systematic, policy‑aware consumption**.
Created a practical foundation for future **AI Gateway‑style capabilities** such as multi‑tenant routing, cost/observability and governance.


`project`
**Platform Engineering**

Key Responsibilities:

Built and maintained **bare-metal Kubernetes clusters** managed by Rancher, running on Flatcar (immutable OS), supporting internal R&D teams working with Rust, C++, Python, Yocto, and TypeScript.

Designed end-to-end **GitOps workflows** using GitLab + ArgoCD with Kustomize, enabling automated deployments, consistent environment management, and reduced operational overhead.

Automated infrastructure provisioning using **Terraform**, with GitLab pipelines triggering Terraform apply for predictable and auditable changes.

Integrated **TrueNAS NFS backend** to support stateless workloads with decoupled persistent storage.

Managed and optimized internal platform components: **Harbor registry, PXE bootstrap node, VMware VM lifecycle, ExternalDNS, Bind9, MetalLB, Replicator, GitLab Runners**.

Built observability stack using **Prometheus + Grafana**, providing system health metrics, dashboards, and alerting.

Collaborated directly with the **CISO** to ensure that CI/CD pipelines, Kubernetes cluster settings, and deployment workflows comply with security requirements and internal governance.

Improved reliability of the development workflow, reduced deployment friction, and enhanced the entire software delivery lifecycle through automation and platform standardization.

Participated in the project of building Appear Hub, a customer-facing delivery platform for firmware, documentation, and license distribution. Implemented the solution on Azure using Container Apps for scalable backend services and Azure Front Door for global routing.


`2022-2025`
***<font size= "3">Senior Infrastructure Engineer at Sopra Steria</font>***

During past years, Gang has been worked as DevOps/infrastructure engineer and led/contributed to a variety of projects for customers, including:

`project`
**Building High Availability Kubernetes and Github Actions Runner Controller(ARC)(sole role)**

Description: The existing use of GitHub self-hosted runners on virtual machines (VMs) led to significant scalability issues, race conditions, and lack of workload isolation. As the number of CI/CD workflows grew, VM-based runners could no longer provide a flexible and manageable solution. To address this, a container orchestration platform was required to dynamically provision and scale runners on demand, ensuring standardized, isolated, and scalable infrastructure for GitHub Actions workflows.

Contribution: Took sole role in designing and implementing a high-availability Kubernetes cluster with GitHub Actions Runner Controller (ARC) to manage dynamic runner provisioning. Migrated CI/CD workflows from VM-based runners to Kubernetes, implemented automated scaling and isolation, and collaborated with developers to refactor pipelines. Established platform monitoring and ongoing maintenance processes.

Value Created: Delivered a secure, scalable, and automated CI/CD runner platform, reducing manual overhead and improving isolation, reliability, and developer productivity. Standardized the CI/CD pipeline infrastructure for consistency and scalability, while enabling on-demand scaling to meet workload peaks.


`project`
**Implementing Local S3-Compatible Backend for Terraform State Management using MinIO on Kubernetes(sole role)**

Description: Terraform state files were previously stored on local disks, causing issues like lack of version control and collaboration challenges. Public cloud storage (e.g., AWS S3) was not an option due to policy constraints.

Contribution: Designed and deployed a MinIO-based S3-compatible backend on an internal Kubernetes platform. Integrated it with GitHub Actions pipelines to enable secure and versioned Terraform state storage within the CI/CD workflow.

Value Created: Established a reliable, centralized, and versioned Terraform state backend, improving collaboration, auditability, and infrastructure stability—without relying on public cloud services.

`project`
**Implementing GitOps Deployment Workflow with Argo CD (Ongoing)(sole role)**

Description: With increasing demands from developers for faster and more flexible deployments, there was a growing need for a platform that allows developers to dynamically choose which environment to deploy their code to. The goal was to create an automated workflow where a code merge in GitHub would automatically trigger deployment of a new version in Kubernetes — enabling self-service, reducing manual operations, and aligning with modern DevOps practices.

Contribution: Designed and implemented GitOps workflows using Argo CD, connecting GitHub branches to Kubernetes namespaces for automated deployments. Built Helm-based reusable templates and structured repositories for dynamic environments, and implemented RBAC and project isolation for security. Worked with development teams to define deployment flows and ensure smooth integration.

Value Created: Established a flexible and automated deployment pipeline aligned with GitOps, enabling developers to deploy code seamlessly across environments. Improved deployment speed, consistency, and security, and reduced operational overhead by shifting to self-service workflows.

`project`
**Implementing Ceph Storage Integration for OpenShift**

Description: The client required a scalable and highly available storage backend to support stateful workloads running on OpenShift. I worked on deploying and integrating a Ceph-based storage solution to provide reliable Persistent Volume provisioning for the platform.

Contribution: Deployed and configured a Ceph cluster to serve as the storage backend for OpenShift, ensuring high availability and replication across nodes. Integrated Ceph with OpenShift via StorageClasses and dynamic PVC provisioning to support stateful applications. Performed validation of read/write performance, redundancy, and failure recovery scenarios. Documented operational procedures, including node replacement, OSD recovery, monitoring, and capacity planning.

Value Created: Dlivered a production-ready storage foundation for OpenShift workloads, enabling the platform to run databases, message queues, and other stateful services reliably. Improved resilience and reduced operational risk through automated failover and self-healing storage capabilities.


`project`
**Building Infrastructure Monitoring System(ongoing)(sole role)**

Description: With the increasing number of containers and virtual machines, it became critical to have a unified platform to monitor the entire infrastructure.

Contribution: Building Prometheus and Grafana on an existing Kubernetes platform to monitor both containers and VMs, integrating alerting and visualization.

Value Created: Provided real-time infrastructure visibility, automated alerting, and improved platform stability.
 
`project`
**Troubleshooting and Improving CI/CD Pipelines**

Description: The development team encountered various errors and instability when running pipelines on self-hosted runners.

Contribution: Troubleshot pipeline errors, optimized performance, improved reliability, and worked closely with developers to maintain organized workflows.

Value Created: Freed developers from troubleshooting, allowing them to focus on development and improving overall pipeline efficiency.

`project`
**Infrastructure Standardization and Automation(sole role)**

Description: The current infrastructure management was manual, inconsistent, and lacked standardization, leading to inefficiencies and errors across different environments.

Contribution: Standardized operating systems, simplified and automated VM provisioning and management process.

Value Created: Improve infrastructure consistency, reduce manual errors, enhance security, and significantly speed up deployment times through automation.


`project`
**Automating Upgrading RHEL7 to RHEL8**

Description: RHEL7 was approaching the end of support, so upgrading hundreds of RHEL7 was a high priority.

Contribution: Designed upgrading plan with application owners and automated upgrading job with Ansible.

Value Created: Ensure systems are aligned with security compliance standards.


`project`
**Ansible Automation Platform on Openshift**

Description: With an ever-increasing number of playbooks, inventories, and workflows, manually managing them is challenging. A central platform is required to orchestrate all the elements related to Ansible.

Contribution: Collaborated with teams on deploying the Ansible Automation Platform on Openshift.

Value Created: Reduced manual tasks and errors while managing playbooks, inventories, and secrets, improved operational efficiency, and enhanced security


`project`
**Deploying Red Hat 9 to Production Infrastructure**

Description: Need to test RHEL9 and make it ready for production use.

Contribution: Deployed Red Hat 9 using Ansible, created a customized Red Hat image template for VMware, and integrated the system with Windows AD.

Value Created: Enable seamless deployment, ensure system compatibility, and make new OS ready for production environment.


`project`
**Automating Patching of Red Hat VM**

Description: The manual patching process for a large-scale Red Hat environment was time-consuming and prone to errors, requiring a more efficient automated solution.

Contribution: Designed and implemented an Ansible-based workflow with Red Hat Satellite to automate patching.

Value Created: Streamlined patching, reduced errors, and improved system uptime and security across the infrastructure.

`project`
**Automating the Provisioning of Red Hat VM on VMWare Private Cloud Platform**

Description: The manual work of provisioning large-scale Red Hat VM was just impossible.

Contribution: Designed and implemented an Ansible-based workflow that automated the process of provisioning VM into the production environment.

Value Created: Streamlined installation, configuration, and management of VM.


`project`
**Deploying critical application to infrastructure(sole role)**

Description: A critical cloud-based application must be deployed, configured, and tested across the entire platform.
Contribution: Solo responsibility for installing, configuring, and troubleshooting applications.

Value Created: Ensure that the system is aligned with organization policies.

`project`
**Splunk Implementation**

Description: Implemented Splunk to monitor and analyze logs and metrics across infrastructure. The project involved centralized log collection, efficient indexing, and actionable insights to enhance system observability and operational efficiency.

Contribution: Deployed and configured Splunk Enterprise for centralized log aggregation and real-time monitoring. Developed custom dashboards for infrastructure health monitoring, including CPU usage, memory consumption, disk I/O, and application performance metrics.

Value Created: Enhanced system reliability and performance by proactively identifying incidents.


`2012-2022`
***<font size= "3">System Engineer at University of Oslo</font>***

At the University of Oslo, Gang worked as system engineer in managing and operating a local data center dedicated to delivering robust and reliable scientific computing infrastructure for researchers at the Centre for Molecular Medicine Norway (NCMM). His responsibilities spanned core IT operations, distributed systems engineering, and close collaboration with scientific researchers.

**Responsibilities**

- Server & Infrastructure Management: Installed, configured, and maintained compute systems for scientific workloads, including Linux-based compute nodes, distributed HPC servers, and NVIDIA GPU-accelerated machines. Built and operated foundational components of the university’s high-performance computing environment, ensuring system reliability, performance, and scalability across research workloads.
- Windows Deployment and Administration: Automated provisioning and lifecycle management of Windows clients using PXE and SCCM (System Center Configuration Manager). Streamlined software distribution, security patching, and policy compliance for stable operation.
- Network Operations: Administered public and private research networks using Cisco switches and routers, including NAT, VLAN segmentation, private dns domain and dhcp zone, firewall rules, port assignments, and connectivity troubleshooting to support secure, high-availability access to computing resources.
- Scientific Software & Distributed Computing Environment: Installed and maintained complex scientific software stacks with unstable dependencies. Optimized computational environments for bioinformatics, molecular modeling, and large-scale data analysis, providing technical guidance for advanced distributed workloads.
- Daily IT Operations: Performed daily responsibilities including user provisioning, access control, storage management, system monitoring (Nagios, Zabbix), and incident troubleshooting, minimizing downtime for critical research systems.
- High-Performance Computing (HPC) Engineering & Parallel Workload Support: Contributed to the build-out and ongoing operation of the university’s HPC cluster, including configuration of distributed compute nodes with NVIDIA GPU nodes, shared storage, and Slurm scheduling services. Supported researchers in running parallel and GPU-accelerated jobs, optimized workload performance, and troubleshot issues across multi-node and high-throughput workflows.


## Certificate
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng"> Red Hat Certified Professional of the Year 2024</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified Architect</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified Specialist in Containers</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified OpenShift Administrator</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified Specialist in Managing Automation with Ansible Automation Platform
</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified Specialist in Deployment and Systems Management</a>

<a href="https://rhtapps.redhat.com/verify?certId=210-181-160"> Red Hat Certified Engineer</a>

<a href="https://www.redhat.com/en/services/certification/rhcsa"> Red Hat 8 Certified System Administrator</a>

<a href="https://www.credly.com/earner/earned/badge/ec0cd8f2-d4d4-472b-b143-1a93702989dd"> Microsoft Certified: Azure Fundamentals</a>

<a href="https://www.redhat.com/en/services/certification/red-hat-certified-specialist-in-containers-and-kubernetes"> Red Hat Certified Specialist in Containers and Kubernetes</a>

## Events & Conference

<a href="https://cloud-native-day-oslo-2025.sessionize.com/schedule"> Cloud Native Day Oslo 2025 </a>

<a href="https://www.redhat.com/en/summit?sc_cid=7013a000003SgNoAAK&gad_source=1&gclid=Cj0KCQjwkN--BhDkARIsAD_mnIrWsK8FpcovhjhNkmFLjS6y1CHJ86KXi1ZhIma1cS59K3BK2zOzx9QaAp_EEALw_wcB&gclsrc=aw.ds"> Red Hat Summit - Red Hat Ansible Fest </a>

## Articles

<a href="https://medium.com/@gcccheng/lets-talk-about-troubleshooting-090ab6cbb95c"> Let´s talk about troubleshooting </a>

<a href="https://medium.com/@gcccheng/challenges-tips-and-rewards-working-as-a-consultant-in-norway-4b6ddce2ff3b"> Challenges, tips, and rewards: working as a consultant in Norway </a>

<a href="https://www.linkedin.com/pulse/cloud-native-day-oslo-reflections-highlights-gang-cheng-ripaf/?trackingId=rpGDQr2us8CpWZiuR3Sx%2FA%3D%3D"> Cloud Native Day Oslo — From DevOps to DevEx </a>

## Courses

<a href="https://www.coursera.org/learn/gcp-fundamentals"> Google Cloud Foundamentals </a>

<a href="https://www.nvidia.com/en-us/learn/certification/ai-infrastructure-operations-associate/"> Nvidia Academy: AI Infrastructure and Operations
 </a>

<a href="https://www.coursera.org/learn/genai-for-devops-practitioners"> GenAI for DevOps Practitioners </a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS162x+3T2019/home"> Linux Foundation: Introduction to DevOps and Site Reliability Engineering(Graded and Certified)</a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS151.x+2T2020/home"> Linux Foundation: Introduction to Cloud Infrastructure Technologies

 
<a href="https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/"> MicroSoft Azure Foundamentals </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5004NSA/index.html"> Intrusion detection and firewalls </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF4018NSA/index.html"> Enterprise Networking: Practices and Technologies </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5100NSA/index.html"> Research Methods and Data Analysis </a>

<a href="https://www.udemy.com/course/mastering-ansible/?gclid=Cj0KCQiAhMOMBhDhARIsAPVml-HCo3Nm7AYmD15j425Ld7FLtLZOYQ9vTev6CMsi5-DeO7ST9exGqw0aAuX3EALw_wcB&matchtype=e&utm_campaign=LongTail_la.EN_cc.ROW&utm_content=deal4584&utm_medium=udemyads&utm_source=adwords&utm_term=_._ag_80675493522_._ad_535700245675_._kw_ansible+course_._de_c_._dm__._pl__._ti_kwd-822946965094_._li_1010826_._pd__._"> Ansible For System Automation </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF1100/index-eng.html">Introduction to programming with scientific applications</a>

<a href="https://www.edx.org/course/fundamentals-of-containers-kubernetes-and-red-hat">Red Hat: Fundamentals of Containers, Kubernetes, and Red Hat OpenShift</a>

## Workshops
<a href="https://events.redhat.com/profile/form/index.cfm?PKformID=0x11991670001">Azure Red Hat OpenShift AI</a>

<a href="https://aws-experience.com/emea/north/e/ddd34/aws-immersion-day-generative-ai"> AWS RAG and Fine-tuned AI</a>
            
<a href="https://www.uio.no/english/services/it/research/hpc/fox/index.html"> Using the High Performance Computing cluster for Educloud Research users </a>
    
<a href="https://isovalent.com/isovalent-hands-on-workshop-oslo/"> Cilium Hands-On Workshop & Deep Dive Oslo </a>

Manage vm, virtul network, firewall on Azure
  
<a href="http://modules.sourceforge.net/">Using Environment Modules to initialize shell and modify shell environment</a>
  
Deploy AWS EC2 instance with terraform

Running containers with podman
  
<a href="https://www.ub.uio.no/english/courses-events/courses/other/Carpentry/211103_github"> Version Control with Git </a>

Cryptography and SSH remote logins 
  
<a href="https://www.ub.uio.no/english/courses-events/courses/other/coderefinery/Python%20for%20Scientific%20Computing%20%28internediate%29"> Python for Scientific Computing</a>

<a href="https://arnsteio.github.io/UH-IaaS-mini-workshop/"> Virtualized research architecture using openstack</a>
  
<a href="https://www.uio.no/tjenester/it/forskning/kompetansehuber/uio-ai-hub-node-project/it-resources/"> AI at UiO </a>

## Other Projects

Build multi-model Generative AI experiences on Azure Openshift

Provision VM using Terraform and Configuring CI/CD pipeline on Azure

Build Proxmox virtual infrastructure for complex IT system
  
Build Foreman+Ansible+Smart Proxy and provision hosts for large infrastructure
  
Integrate Linux to Windows Domain

Build modern inventory system with OCS inventory
  
Set up local directory service with OpenLDAP
  
<a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus"> Set up Windows Server Update Services for lab network </a>

<a href="https://guacamole.apache.org/">Using Apache Guacamole as free and open-source cross-platform Remote Desktop Gateway</a>
  
Intrusion detection and monitoring with Snort and Munin

## Experienced tech stacks
Kubernetes, Docker, Podman, GitHub Actions, GitHub Actions Runner Controller(ARC), Red Hat Linux, Red Hat Satellite, Red Hat Openshift, Red Hat Ansible,  Atlassian Bitbucket, Atlassian Confluence, Atlassian Jira, Grafana, Prometheus, Dell PowerEdge, Cisco SWitch, Windows Server 2016, Ansible, Terrafform, Bash, Perl, Python Windows SCCM, Samba, NFS, FirewallD, Active Directory, Networking

## Exposure Skills
AWS, MS Azure, Openstack, Vagrant

## Education
`2010-2012`
University of Oslo: Master in Network and System Administration
  
## Hobbies 
Blog writing, Skiing, and hiking
  
## Languages 
English: Full Professional Working Proficiency
  
Norwegian: Professional Working Proficiency


  

<!-- ### Footer

Last updated: May 2013 -->

