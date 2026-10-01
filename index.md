---
layout: cv
title: Gang Cheng's CV
---
# Gang Cheng 

<span class="accent">Red Hat Certified Architect</span>, <span class="accent">Infrastructure</span>/<span class="accent">DevSecOps</span>/<span class="accent">DevEx</span>/<span class="accent">Platform Engineer</span>

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat Profile</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">Linkedin page</a>
</div>

## Summary

Gang is a self-motivated person, and he believes that the mindset of <span class="accent">continuous learning</span> and the ability to <span class="accent">quickly adapt</span> to new technologies are core competencies for a professional IT engineer. Throughout his career, Gang has proactively built expertise in managing <span class="accent">modern infrastructure</span> and <span class="accent">platform engineering</span> through an ever-growing list of projects, certifications, workshops, conferences, courses, industry peers and through AI. His efforts and expertise were recognized when he received the honor of being awarded and titled as the <span class="accent">Red Hat Certified Professional of the Year 2024</span>(if you are curious of what it is, click Red Hat Bio on top for more info). 

In addition to his expertise in Red Hat, Gang has expanded his skills across <span class="accent">DevOps, Security, Cloud Native, and AIOps. He has worked in both small and large teams, taking on roles as <span class="accent">System Administrator</span>, <span class="accent">Infrastructure Engineer</span>,  <span class="accent">DevSecOps Engineer, and <span class="accent">Platform Engineer</span> — or a combination of them all, depending on project requirements. In the era of AI-driven engineering, Gang is also actively exploring how artificial intelligence can assist platform and infrastructure work. This includes <span class="accent">AI-assisted troubleshooting</span>, <span class="accent">automation</span>, infrastructure documentation, and improving <span class="accent">developer productivity</span> through intelligent tooling. Rather than viewing AI as a replacement for engineers, he sees it as a powerful collaborator that enhances <span class="accent">decision-making</span>, accelerates <span class="accent">problem-solving</span>, and helps engineers focus on higher-level <span class="accent">architectural thinking</span>.

No matter what title or environment, Gang adapts quickly to create value for the business through strong <span class="accent">communication</span> skills and a <span class="accent">collaborative mindset</span>.


## Employment

`2025-Now`  
***<font size="3">Senior Platform Engineer — Appear TV, Oslo</font>***

Appear TV is a leading global provider of video compression, media processing, and distribution technology, widely used by global broadcasters, telecom operators, and major live event organisations, including NBCUniversal, Discovery, NHL, Formula 1, and Riot Games.

At Appear, Gang's role combines <span class="accent">day-to-day platform engineering</span> with <span class="accent">project delivery</span>. Daily responsibilities include platform operations, developer and CI support, troubleshooting, component version updates, and infrastructure upgrades. Project work is planned and delivered through <span class="accent">sprint-based management</span>, covering improvements to Kubernetes infrastructure, GPU capabilities, automation, and platform security.

`project`
<strong style="color: #b22222;">Platform Engineering</strong>

<strong style="color: #000;">Key Responsibilities</strong>:

Built and maintained **bare-metal Kubernetes clusters** managed by Rancher, running on Flatcar (immutable OS), supporting internal R&D teams working with Rust, C++, Python, Yocto, and TypeScript.

Designed end-to-end **GitOps workflows** using GitLab + ArgoCD with Kustomize, enabling automated deployments, consistent environment management, and reduced operational overhead.

Automated infrastructure provisioning using **Terraform**, with GitLab pipelines triggering Terraform apply for predictable and auditable changes.

Integrated a **TrueNAS NFS backend** to provide persistent storage for stateful and stateless workloads, with centrally managed **PersistentVolumes (PVs)** and namespace-scoped **PersistentVolumeClaims (PVCs)**.

Managed and optimized internal platform components: **Harbor registry, PXE bootstrap node, VMware VM lifecycle, ExternalDNS, Bind9, MetalLB, Replicator, GitLab Runners**.

Supported developers with **CI jobs**, troubleshooting build and test failures, runner issues, and resource constraints to improve pipeline reliability and keep development workflows running smoothly.

Used the existing **Prometheus + Grafana** observability stack to monitor system health, investigate issues, and support platform operations through metrics, dashboards, and alerts.

Improved reliability of the development workflow, reduced deployment friction, and enhanced the entire software delivery lifecycle through automation and platform standardization.

Contributed to the project of building Appear Hub, a customer-facing delivery platform for firmware, documentation, and license distribution. Helped implement the solution on Azure using Container Apps for scalable backend services and Azure Front Door for global routing.

`project`
<strong style="color: #b22222;">NVIDIA GPU Cluster for Developer Workloads</strong>

Built and operated Kubernetes GPU capabilities with **GPU nodes in production use by developers**.

<strong style="color: #000;">Responsibilities</strong>：

Standardised GPU foundations using **NVIDIA GPU Operator**, establishing reusable cluster baselines and operational ownership.

Introduced **Time Slicing** and **MPS** to support GPU sharing and concurrent developer workloads.

Brought **GitLab Runner** GPU workloads into platform scheduling with defined policies for GPU pipelines.

Integrated GPU utilisation monitoring into the platform observability stack and applied access controls and policy guardrails using **Kyverno**.

Worked with R&D teams to align GPU resource allocation and platform operations with developer workload requirements.

<strong style="color: #000;">Value Created</strong>：

Provided shared, observable GPU infrastructure for production developer workloads, improving resource utilisation and consistency of GPU-backed CI execution.

`project`
<strong style="color: #b22222;">Self-Hosted LLM & Open WebUI Platform (MVP)</strong>

Built an MVP that demonstrated the feasibility of self-hosted LLM inference and an internal AI interface. The available GPUs supported prototype validation but lacked the capacity for the intended production workloads.

<strong style="color: #000;">Responsibilities</strong>：

Prototyped **vLLM** inference on Kubernetes and connected model endpoints to **Open WebUI** to test an internal AI access workflow.

Evaluated local models and hosted APIs, considering GPU capacity, model memory requirements, latency, concurrency, output quality, and cost.

Explored gateway routing, persistent storage, access controls, and usage visibility as part of the prototype architecture.

Worked with engineering stakeholders to explore potential uses such as log analysis, documentation, and code assistance and assess requirements for future adoption.

<strong style="color: #000;">Value Created</strong>：

Validated the local LLM serving approach and its integration with a user-facing AI interface, providing a technical basis for planning production AI infrastructure.

Identified hardware capacity requirements for production adoption. A budget proposal for infrastructure to host local LLMs has been submitted and is awaiting approval.

### **CISO Partnership Across Platform Security Projects**

Collaborated directly with the **CISO and security team** across vulnerability management, CI runner hardening, privileged workload risk mitigation, and platform security governance, supporting **ISO 27001 and external audit preparation**. Aligned CI/CD pipelines, Kubernetes cluster settings, and deployment workflows with security requirements and internal governance while balancing operational needs across the following projects.

Worked with a security engineer to develop reusable **Claude skills** that automate parts of risk assessment and, where appropriate, threat modelling for tools proposed for deployment to the cluster, supporting more consistent security reviews.

`project`
<strong style="color: #b22222;">Platform Vulnerability Management & CVE Remediation</strong>

Led a cross-team vulnerability management effort for a **production Kubernetes cluster hosting approximately 55 applications and platform tools**.

<strong style="color: #000;">Responsibilities</strong>：

Deployed and operated **Trivy Operator** for vulnerability visibility and Kubernetes security posture assessment, including **node and control-plane configuration checks**, detailed compliance reporting, and **Prometheus integration**.

Presented CVE reports in **Grafana** to support ongoing visibility and review. Reviewed findings with a security engineer, prioritising critical findings and coordinating developers to define remediation responsibilities and mitigation plans.

Owned hands-on remediation for platform-managed internal tools through patching and Helm chart upgrades. Helped application developers upgrade base images, rebuild container images, and revise Dockerfiles to address vulnerable components in their deployed applications.

Scanned updated container images before deployment and compared vulnerability reports before and after upgrades to check which issues were fixed. Investigated remaining critical findings to see whether fixes were available and assess the risk in our environment.

Established a repeatable process to identify, review, document, and address findings. Documented unresolved vulnerabilities and proposed risk acceptance for security approval with re-check dates; required security confirmation before suppressing false positives.

<strong style="color: #000;">Value Created</strong>：

Significantly reduced critical and high CVE findings across platform workloads through coordinated component upgrades and container image improvements, with remaining findings documented for security review.

Established an ongoing vulnerability management routine with shared responsibility between platform engineering, security, and development teams, supporting audit preparation and continued visibility into unresolved risks.

`project`
<strong style="color: #b22222;">CI Runner Restructuring & Platform Hardening</strong>

Restructured the cluster's CI runner infrastructure to improve execution efficiency and strengthen security across diverse engineering workloads.

<strong style="color: #000;">Responsibilities</strong>：

Reviewed runner requirements across **compilation, container builds, deployment jobs, Yocto release builds, video processing, video stream tests, and hardware testing**.

Reorganised runners around workload-specific resource requirements and bottlenecks spanning **CPU, GPU, memory, network, and disk I/O**, aligning CI job execution with suitable platform resources.

Removed **privileged execution** from most runners and restricted designated runners to authorised repositories, tightening access to runner capabilities and infrastructure resources.

Balanced platform hardening with the execution requirements of existing CI workloads, including jobs requiring specialised hardware and resource-intensive builds or tests.

<strong style="color: #000;">Value Created</strong>：

Improved the efficiency of existing CI workloads through better alignment between job requirements and runner resources.

Reduced exposure from privileged CI execution and strengthened repository-level control over runner access, establishing a more secure foundation for build, deployment, and testing workloads.

`project`
<strong style="color: #b22222;">Privileged Workload Risk Mitigation (Ongoing)</strong>

Driving an ongoing effort to mitigate privileged workload risks through complementary controls across runner hardening, runtime detection, node segregation, and audit logging.

<strong style="color: #000;">Responsibilities</strong>：

Using **Falco** for runtime detection of suspicious behaviour through stable, incubating, and custom rules.

Working on **node segregation** to separate privileged workloads from non-privileged workloads, alongside runner hardening to reduce unnecessary privileges.

Working on **Kubernetes API server audit logging** to improve visibility into API activity and support security investigations.

<strong style="color: #000;">Intended Value</strong>：

Reduce the potential impact of compromised workloads and improve detection and traceability of security-relevant activity while maintaining platform usability for engineering teams.

`project`
<strong style="color: #b22222;">Platform Security Governance</strong>

<strong style="color: #000;">Responsibilities</strong>：

Built and implemented **Kyverno Policy‑as‑Code** as the core platform security governance mechanism.

Led security governance reviews and implementation paths, aligning security controls with business requirements.

Reviewed platform baselines to identify key risks and vulnerabilities.

Designed and maintained **Validating** and **Mutation** policies, continuously iterating the policy library.

Delivered GitOps‑driven security policies for auditability, traceability and rollback.

Worked closely with the CISO and security architects to implement security and compliance controls across Kubernetes and DevOps environments, supporting IPO readiness and ISO 27001 certification.

Delivered platform‑level security hardening, including RBAC/IAM governance, network policies, secrets management, vulnerability remediation, image scanning, supply‑chain security (SBOM/signing), and audit logging.

<strong style="color: #000;">Value Created</strong>：

Established a platform‑level security governance system with auditable controls and compliance readiness.
Balanced security requirements with delivery efficiency by aligning policies to business needs.


`project`
<strong style="color: #b22222;">ClickTime & Visma Integration (Ongoing, Project Lead)</strong>

<strong style="color: #000;">Responsibilities</strong>：

Lead the ongoing internal integration project connecting **ClickTime** and **Visma** so time entries registered in ClickTime can be synchronised into Visma for payroll and reporting.

Worked with HR, Finance, project owners, and system stakeholders to understand the company's need to track flexitime and overtime by project and group, a level of detail not covered by Visma alone.

Helped stakeholders define and control requirements, translating broad business needs into practical integration scope, data flows, and validation scenarios.

Volunteered to build the integration even though software development is not the core responsibility of a platform engineer, using **Rust** and AI-assisted development with **Claude Code**.

Researched the **ClickTime** and **Visma** APIs to understand authentication, data models, endpoint behaviour, and how project, group, and time-entry data should map between the two systems.

Designed the integration as an internal middleware service with idempotency checks, duplicate prevention, retry handling, and auditable synchronisation.

Applied platform engineering practices including threat modelling, risk analysis, code testing, linting, Docker image packaging, Kubernetes deployment, and Argo CD setup.

Worked with a security engineer to perform security analysis and risk assessment for the integration, identifying what could go wrong across authentication, data mapping, access control, payroll-sensitive data handling, API failures, duplicate synchronisation, auditability, and operational ownership.

Translated the risk assessment into practical mitigations, including least-privilege API access, secret handling, validation checks, idempotency controls, retry and failure handling, logging, audit trails, and controlled rollout planning.

Kept the solution aligned with Norwegian payroll workflows while reducing dependency on expensive vendor-built customisation.

<strong style="color: #000;">Value Created</strong>：

Created a cost-saving internal alternative to a vendor-built ClickTime integration, enabling the company to track time at project and group level while still aligning with Visma and Norwegian payroll requirements.

Gained practical experience with a compact software development lifecycle, from stakeholder discovery and requirement shaping to API integration design, implementation, testing, and production planning.

The most important learning was not only writing code, but communicating with stakeholders: understanding their real needs, helping them define realistic requirements, and keeping the project scope under control.

Improved the project's production readiness by treating security and business risk as part of the design, not as a late-stage review activity.

`project`
<strong style="color: #b22222;">AI-Assisted Platform SRE Agent (MVP)</strong>

Built a **Python-based MVP** to explore AI-assisted troubleshooting and remediation for Kubernetes and VMware infrastructure.

Combined infrastructure checks with LLM-assisted analysis and a review interface, using policy guardrails and human approval for higher-risk actions.

Demonstrated potential to reduce repetitive operational work while retaining engineer oversight; the project remained a prototype.

`project`
<strong style="color: #b22222;">OpenShift Virtualization Migration MVP</strong>

<strong style="color: #000;">Responsibilities</strong>：

Led an MVP to evaluate moving selected workloads from **VMware vSphere** to **OpenShift Virtualization**, with the goal of understanding whether OpenShift VM could support future cost reduction and platform convergence.

Defined upfront mappings for **networking, storage, operating system dependencies, namespaces, and target landing zones** to reduce migration uncertainty and improve execution consistency.

Assessed workload suitability, performance characteristics, and operational constraints to determine which systems could be tested on OpenShift Virtualization and which should remain on VMware.

Tested migration scenarios in a non-production MVP context and documented rollout considerations, rollback needs, change-control requirements, and business impact for any future production adoption.

Applied a **platform engineering methodology** rather than a tool-only migration approach, focusing on standardisation, reusable patterns, automation, Infrastructure as Code, self-service guardrails, observability, and governance.

Worked across infrastructure and application stakeholders to balance downtime expectations, performance risk, compliance requirements, and delivery timelines.

<strong style="color: #000;">Value Created</strong>：

Created a pragmatic evaluation path for potential **cost reduction** and long-term **platform convergence**, using OpenShift as a possible foundation for both virtual machines and container workloads.

Reduced migration risk by defining mappings and trade-offs early, improving predictability around storage, networking, performance, and operational ownership.

Established reusable evaluation patterns and governance considerations that would make future workload onboarding faster, safer, and more auditable if the company decides to move toward production adoption.

`2022-2025`
***<font size= "3">Senior Infrastructure Engineer at Sopra Steria</font>***

Sopra Steria is one of Europe's major digital services and consulting companies, and in Norway is positioned as a leading consulting company within digitalisation, innovation, and sustainability, serving large private companies and public-sector organisations.

During his time at Sopra Steria, Gang delivered infrastructure, automation, DevOps, and platform services for enterprise and public-sector customers.

`selected work`
<strong style="color: #b22222;">Enterprise Linux, Virtualisation & Automation</strong>

Designed and implemented automated lifecycle management for **Red Hat Enterprise Linux on VMware**, covering standardised images, provisioning, patching, and operating system upgrades using **Ansible and Red Hat Satellite**.

Worked with application owners on RHEL upgrades and production readiness, including a standardised RHEL9 baseline and Active Directory integration. Collaborated on deploying **Ansible Automation Platform on OpenShift** to centralise automation workflows.

Standardised infrastructure and supported critical application deployment, configuration, and troubleshooting, reducing manual work and improving consistency and alignment with security requirements.

`selected work`
<strong style="color: #b22222;">Kubernetes, GitOps, Storage & Service Reliability</strong>

Independently designed and implemented a high-availability **Kubernetes** platform with **GitHub Actions Runner Controller**, migrating VM-based runners to scalable, isolated CI/CD execution. Worked with developers to troubleshoot and improve pipeline reliability.

Implemented initial **Argo CD** GitOps workflows with reusable Helm templates and access controls, enabling consistent self-service deployments for development teams.

Deployed an internal **MinIO** backend for versioned Terraform state management and integrated it with CI workflows, improving collaboration within customer hosting constraints.

Worked on infrastructure monitoring with **Prometheus and Grafana**, improving visibility, alerting, and troubleshooting across containers and virtual machines.

`2012-2022`
***<font size= "3">System Engineer at University of Oslo</font>***

At the University of Oslo, Gang worked as system engineer in managing and operating a local data center dedicated to delivering robust and reliable scientific computing infrastructure for researchers at the Centre for Molecular Medicine Norway (NCMM). His responsibilities spanned <span class="accent">core IT operations</span>, <span class="accent">distributed systems engineering</span>, and close <span class="accent">collaboration</span> with scientific researchers.

<strong style="color: #000;">Responsibilities</strong>

Server & Infrastructure Management: Installed, configured, and maintained compute systems for scientific workloads, including Linux-based compute nodes, distributed HPC servers, and NVIDIA GPU-accelerated machines. Built and operated foundational components of the university’s high-performance computing environment, ensuring system reliability, performance, and scalability across research workloads.

Windows Deployment and Administration: Automated provisioning and lifecycle management of Windows clients using PXE and SCCM (System Center Configuration Manager). Streamlined software distribution, security patching, and policy compliance for stable operation.

Network Operations: Worked with public university networks and an internal lab network for research equipment using <span class="accent">Cisco</span> switching and routing, including <span class="accent">VLANs</span>, <span class="accent">trunks</span>, <span class="accent">NAT</span>, <span class="accent">iptables</span>-based firewalling, internal <span class="accent">DNS</span> and <span class="accent">DHCP</span>, port assignments, and connectivity troubleshooting. Supported segmented internal infrastructure behind NAT via internal switching.

Scientific Software & Distributed Computing Environment: Installed and maintained complex scientific software stacks with unstable dependencies. Optimized computational environments for bioinformatics, molecular modeling, and large-scale data analysis, providing technical guidance for advanced distributed workloads.

Daily IT Operations: Performed daily responsibilities including user provisioning, access control, storage management, system monitoring (Nagios, Zabbix), and incident troubleshooting, minimizing downtime for critical research systems.

High-Performance Computing (HPC) Engineering & Parallel Workload Support: Contributed to the build-out and ongoing operation of the university’s HPC cluster, including configuration of distributed compute nodes with NVIDIA GPU nodes, shared storage, and Slurm scheduling services. Supported researchers in running parallel and GPU-accelerated jobs, optimized workload performance, and troubleshot issues across multi-node and high-throughput workflows.


## Certificate
**Certificate of Completion - AI Infrastructure and Operations Fundamentals**<br>
NVIDIA

**LFS255: Mastering Kubernetes Security with Kyverno**<br>
The Linux Foundation

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

<a href="https://www.nvidia.com/en-us/training/academy/course-detail/?id=course%3A15139853">NVIDIA Cumulus Linux Essentials</a>

<a href="https://www.nvidia.com/en-us/training/academy/course-detail/?id=course%3A15139833">NVIDIA Introduction to Networking</a>


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
<span class="accent">OpenShift</span>, <span class="accent">Kubernetes</span>, <span class="accent">Docker</span>, <span class="accent">Podman</span>, <span class="accent">GitHub Actions</span>, GitHub Actions Runner Controller(ARC), <span class="accent">Red Hat Linux</span>, Red Hat Satellite, <span class="accent">Red Hat Ansible</span>, Atlassian Bitbucket, Atlassian Confluence, Atlassian Jira, <span class="accent">Grafana</span>, <span class="accent">Prometheus</span>, Dell PowerEdge, <span class="accent">Cisco Switch</span>, Windows Server 2016, <span class="accent">Ansible</span>, <span class="accent">Terraform</span>, <span class="accent">Bash</span>, Perl, <span class="accent">Python</span>, Windows SCCM, Samba, <span class="accent">NFS</span>, FirewallD, Active Directory, <span class="accent">Networking</span>

## Exposure Skills
<span class="accent">AWS</span>, <span class="accent">MS Azure</span>, <span class="accent">OpenStack</span>, Vagrant

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
