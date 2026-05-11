---
layout: cv
title: Gang Cheng's CV
---
# Gang Cheng 

<span class="accent">Red Hat Certified Architect</span>, <span class="accent">Infrastructure</span>/<span class="accent">DevOps</span>/<span class="accent">DevEx</span>/<span class="accent">Platform Engineer</span>

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat Profile</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">Linkedin page</a>
</div>

## Summary

Gang is a self-motivated person, and he believes that the mindset of <span class="accent">continuous learning</span> and the ability to <span class="accent">quickly adapt</span> to new technologies are core competencies for a professional IT engineer. Throughout his career, Gang has proactively built expertise in managing <span class="accent">modern infrastructure</span> and <span class="accent">platform engineering</span> through an ever-growing list of projects, certifications, workshops, conferences, courses, industry peers and through AI. His efforts and expertise were recognized when he received the honor of being awarded and titled as the <span class="accent">Red Hat Certified Professional of the Year 2024</span>(if you are curious of what it is, click Red Hat Bio on top for more info). 

In addition to his expertise in <span class="accent">Red Hat</span>, Gang has expanded his skills across <span class="accent">DevOps engineering</span>, <span class="accent">platform engineering</span>, and <span class="accent">site reliability engineering</span>. He has worked in both small and large teams, taking on roles such as System Administrator, Infrastructure Engineer, DevOps Engineer, Developer Experience (DevEx) Engineer, and Platform Engineer — or a combination of them all, depending on project requirements. In the era of AI-driven engineering, Gang is also actively exploring how artificial intelligence can assist platform and infrastructure work. This includes <span class="accent">AI-assisted troubleshooting</span>, <span class="accent">automation</span>, infrastructure documentation, and improving <span class="accent">developer productivity</span> through intelligent tooling. Rather than viewing AI as a replacement for engineers, he sees it as a powerful collaborator that enhances <span class="accent">decision-making</span>, accelerates <span class="accent">problem-solving</span>, and helps engineers focus on higher-level <span class="accent">architectural thinking</span>.

No matter what title or environment, Gang adapts quickly to create value for the business through strong <span class="accent">communication</span> skills and a <span class="accent">collaborative mindset</span>.


## Employment

`2025-Now`  
***<font size="3">Senior Platform Engineer — Appear TV, Oslo</font>***

Appear TV is a leading global provider of video compression, media processing, and distribution technology, widely used by global broadcasters, telecom operators, and major live event organisations, including NBCUniversal, Discovery, NHL, Formula 1, and Riot Games.

At Appear, Gang works on building and maintaining a modern, scalable infrastructure powering developer productivity and high-performance applications. His work focuses on <span class="accent">bare-metal Kubernetes</span>, <span class="accent">GitOps</span>, <span class="accent">observability</span>, <span class="accent">storage</span>, <span class="accent">CI/CD automation</span>, and <span class="accent">platform security</span>.

`project`
<strong style="color: #b22222;">NVIDIA GPU Cluster & Machine Learning Model Serving Platform</strong>

<strong style="color: #000;">Responsibilities</strong>：

Designed and delivered **platformised NVIDIA GPU cluster capabilities**, defining GPU resource governance and service‑oriented delivery paths.

Standardised GPU foundations using **GPU Operator**, establishing reusable cluster baselines.

Introduced **Time Slicing** and **MPS** to enable fine‑grained GPU sharing and multi‑tenant concurrency.

Brought **GitLab Runner** GPU workloads into platform scheduling with defined policies for GPU pipelines.

Integrated GPU observability into the platform stack, covering **utilisation, inference latency, and throughput**.

Enforced access control and policy guardrails for GPU workloads via **Kyverno**.

Coordinated R&D and platform teams to operationalise GPU-backed machine learning model serving capabilities.

<strong style="color: #000;">Value Created</strong>：

Delivered a governable, observable, and rollback‑safe GPU platform for reliable machine learning model serving.
Improved GPU utilisation and delivery efficiency through multi‑tenant optimisation and elastic scaling.

`project`
<strong style="color: #b22222;">Autonomous Platform SRE Agent (AI-Driven Operations MVP)</strong>

<strong style="color: #000;">Responsibilities</strong>：

Designed and built a modular autonomous SRE agent to reduce operational toil and automate repetitive platform engineering tasks, enabling a shift from reactive alerting to proactive remediation.

Architected a Python-based orchestrator framework with pluggable expert modules (Kubernetes, Vsphere, and supply-chain intelligence) to handle multi-domain infrastructure operations.

Implemented a “Brain + Tools” architecture, where the agent scans infrastructure APIs (Kubernetes and Vsphere), detects operational violations, and leverages LLM reasoning (GPT-4o) to analyse root causes and generate remediation strategies rather than simply reporting errors.

Built a Safety Engine & Policy Gatekeeper to constrain AI autonomy: the agent can automatically remediate low-risk issues (e.g., restarting stalled VMs or resolving policy violations), while high-risk changes require human approval.

Developed a Mission Control Dashboard using Flask and HTMX, providing visibility into the agent’s reasoning process and enabling engineers to review and approve remediation actions with one-click execution.

Solved the immutable pod remediation challenge by enabling semantic reasoning to identify and patch the parent controllers (Deployments/StatefulSets) instead of transient pods.

Integrated a software supply-chain intelligence module capable of scanning Terraform and Ansible repositories, analysing GitHub release notes, and performing semantic risk analysis before recommending dependency upgrades.

<strong style="color: #000;">Value Created</strong>：

Demonstrated how operational toil could be reduced by automating classification and remediation of infrastructure and security policy violations (e.g., Kyverno alerts and platform health checks).

Shifted maintenance left by transforming routine dependency updates into a structured review-and-approval workflow, accelerating platform upgrade cycles.

Demonstrated safe AI-assisted operations by showing how L1-level SRE tasks could be automated under policy guardrails, allowing senior engineers to focus more on architecture and platform evolution.

Established a foundation for AI-augmented platform operations, lowering the barrier for engineers to leverage LLM capabilities while maintaining governance and operational safety.

`project`
<strong style="color: #b22222;">CISO Partnership & Platform Security Governance</strong>

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

Kept the solution aligned with Norwegian payroll workflows while reducing dependency on expensive vendor-built customisation.

<strong style="color: #000;">Value Created</strong>：

Created a cost-saving internal alternative to a vendor-built ClickTime integration, enabling the company to track time at project and group level while still aligning with Visma and Norwegian payroll requirements.

Gained practical experience with a compact software development lifecycle, from stakeholder discovery and requirement shaping to API integration design, implementation, testing, and production planning.

The most important learning was not only writing code, but communicating with stakeholders: understanding their real needs, helping them define realistic requirements, and keeping the project scope under control.


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


`project`
<strong style="color: #b22222;">Internal Self-Hosted AI Platform</strong>

Delivered an internal AI/LLM enablement platform to support engineering use-cases such as log and telemetry analysis, documentation generation, incident explanation and code assistance.

<strong style="color: #000;">Responsibilities</strong>：

Acted as technical owner, leading **platform architecture, capability layering and governance model**. Defined roadmap and delivery standards, ran architecture reviews, and coordinated cross‑team execution. Mentored junior engineers through task decomposition and peer reviews to improve delivery quality.

Evaluated multiple LLM backends and tools (hosted APIs and local inference) with a focus on **latency, concurrency characteristics, token cost and model behaviour**.

Designed a containerised deployment model on Kubernetes, including access control, team isolation and integration with existing SSO / developer tooling.

Explored model‑selection strategies by comparing latency, output quality and token usage across different LLM providers (OpenAI, RequestyAI, local Llama variants), identifying which models were most suitable for specific request types.

Implemented basic prompt governance, usage logging and cost visibility, laying groundwork for **responsible AI and auditability**.
Worked with several R&D teams to promote AI‑assisted engineering practices and capture feedback for future platform evolution (e.g. RAG, code search, knowledge base integration).
  
<strong style="color: #000;">Value Created</strong>：

Established the company’s first **unified internal AI entry point and platform capability layer**, significantly lowering the barrier for engineers to use LLMs in daily work.

Shifted AI usage from ad‑hoc, individual experimentation to **systematic, policy‑aware consumption**.
Created a practical foundation for future **AI Gateway‑style capabilities** such as multi‑tenant routing, cost/observability and governance.


`project`
<strong style="color: #b22222;">Platform Engineering</strong>

<strong style="color: #000;">Key Responsibilities</strong>:

Built and maintained **bare-metal Kubernetes clusters** managed by Rancher, running on Flatcar (immutable OS), supporting internal R&D teams working with Rust, C++, Python, Yocto, and TypeScript.

Designed end-to-end **GitOps workflows** using GitLab + ArgoCD with Kustomize, enabling automated deployments, consistent environment management, and reduced operational overhead.

Automated infrastructure provisioning using **Terraform**, with GitLab pipelines triggering Terraform apply for predictable and auditable changes.

Integrated **TrueNAS NFS backend** to support stateless workloads with decoupled persistent storage.

Managed and optimized internal platform components: **Harbor registry, PXE bootstrap node, VMware VM lifecycle, ExternalDNS, Bind9, MetalLB, Replicator, GitLab Runners**.

Built observability stack using **Prometheus + Grafana**, providing system health metrics, dashboards, and alerting.

Collaborated directly with the **CISO** to ensure that CI/CD pipelines, Kubernetes cluster settings, and deployment workflows comply with security requirements and internal governance.

Improved reliability of the development workflow, reduced deployment friction, and enhanced the entire software delivery lifecycle through automation and platform standardization.

Contributed to the project of building Appear Hub, a customer-facing delivery platform for firmware, documentation, and license distribution. Helped implement the solution on Azure using Container Apps for scalable backend services and Azure Front Door for global routing.


`2022-2025`
***<font size= "3">Senior Infrastructure Engineer at Sopra Steria</font>***

Sopra Steria is one of Europe's major digital services and consulting companies, and in Norway is positioned as a leading consulting company within digitalisation, innovation, and sustainability, serving large private companies and public-sector organisations.

During his time at Sopra Steria, Gang worked as a <span class="accent">DevOps</span>/<span class="accent">infrastructure engineer</span> and led/contributed to a variety of projects for customers, including:

`project`
<strong style="color: #b22222;">Building High Availability Kubernetes and Github Actions Runner Controller(ARC)(sole role)</strong>

Description: The existing use of GitHub self-hosted runners on virtual machines (VMs) led to significant scalability issues, race conditions, and lack of workload isolation. As the number of CI/CD workflows grew, VM-based runners could no longer provide a flexible and manageable solution. To address this, a container orchestration platform was required to dynamically provision and scale runners on demand, ensuring standardized, isolated, and scalable infrastructure for GitHub Actions workflows.

Contribution: Took sole role in designing and implementing a high-availability Kubernetes cluster with GitHub Actions Runner Controller (ARC) to manage dynamic runner provisioning. Migrated CI/CD workflows from VM-based runners to Kubernetes, implemented automated scaling and isolation, and collaborated with developers to refactor pipelines. Established platform monitoring and ongoing maintenance processes.

<strong style="color: #000;">Value Created</strong>: Delivered a secure, scalable, and automated CI/CD runner platform, reducing manual overhead and improving isolation, reliability, and developer productivity. Standardized the CI/CD pipeline infrastructure for consistency and scalability, while enabling on-demand scaling to meet workload peaks.


`project`
<strong style="color: #b22222;">Implementing Local S3-Compatible Backend for Terraform State Management using MinIO on Kubernetes(sole role)</strong>

Description: Terraform state files were previously stored on local disks, causing issues like lack of version control and collaboration challenges. Public cloud storage (e.g., AWS S3) was not an option due to policy constraints.

Contribution: Designed and deployed a MinIO-based S3-compatible backend on an internal Kubernetes platform. Integrated it with GitHub Actions pipelines to enable secure and versioned Terraform state storage within the CI/CD workflow.

<strong style="color: #000;">Value Created</strong>: Established a reliable, centralized, and versioned Terraform state backend, improving collaboration, auditability, and infrastructure stability—without relying on public cloud services.

`project`
<strong style="color: #b22222;">Implementing GitOps Deployment Workflow with Argo CD (Initial Implementation, Sole Platform Role)</strong>

Description: With increasing demands from developers for faster and more flexible deployments, there was a growing need for a platform that allows developers to dynamically choose which environment to deploy their code to. The goal was to create an automated workflow where a code merge in GitHub would automatically trigger deployment of a new version in Kubernetes — enabling self-service, reducing manual operations, and aligning with modern DevOps practices.

Contribution: Designed and implemented the initial GitOps workflows using Argo CD, connecting GitHub branches to Kubernetes namespaces for automated deployments. Built Helm-based reusable templates and structured repositories for dynamic environments, and implemented RBAC and project isolation for security. Coordinated with development teams to define deployment flows and ensure smooth integration.

<strong style="color: #000;">Value Created</strong>: Established a flexible and automated deployment pipeline aligned with GitOps, enabling developers to deploy code seamlessly across environments. Improved deployment speed, consistency, and security, and reduced operational overhead by shifting to self-service workflows.

`project`
<strong style="color: #b22222;">Implementing Ceph Storage Integration for OpenShift</strong>

Description: The client required a scalable and highly available storage backend to support stateful workloads running on OpenShift. I worked on deploying and integrating a Ceph-based storage solution to provide reliable Persistent Volume provisioning for the platform.

Contribution: Deployed and configured a Ceph cluster to serve as the storage backend for OpenShift, ensuring high availability and replication across nodes. Integrated Ceph with OpenShift via StorageClasses and dynamic PVC provisioning to support stateful applications. Performed validation of read/write performance, redundancy, and failure recovery scenarios. Documented operational procedures, including node replacement, OSD recovery, monitoring, and capacity planning.

<strong style="color: #000;">Value Created</strong>: Delivered a production-ready storage foundation for OpenShift workloads, enabling the platform to run databases, message queues, and other stateful services reliably. Improved resilience and reduced operational risk through automated failover and self-healing storage capabilities.


`project`
<strong style="color: #b22222;">Building Infrastructure Monitoring System(ongoing)(sole role)</strong>

Description: With the increasing number of containers and virtual machines, it became critical to have a unified platform to monitor the entire infrastructure.

Contribution: Building Prometheus and Grafana on an existing Kubernetes platform to monitor both containers and VMs, integrating alerting and visualization.

<strong style="color: #000;">Value Created</strong>: Provided real-time infrastructure visibility, automated alerting, and improved platform stability.
 
`project`
<strong style="color: #b22222;">Troubleshooting and Improving CI/CD Pipelines</strong>

Description: The development team encountered various errors and instability when running pipelines on self-hosted runners.

Contribution: Troubleshot pipeline errors, optimized performance, improved reliability, and worked closely with developers to maintain organized workflows.

<strong style="color: #000;">Value Created</strong>: Freed developers from troubleshooting, allowing them to focus on development and improving overall pipeline efficiency.

`project`
<strong style="color: #b22222;">Infrastructure Standardization and Automation(sole role)</strong>

Description: The current infrastructure management was manual, inconsistent, and lacked standardization, leading to inefficiencies and errors across different environments.

Contribution: Standardized operating systems, simplified and automated VM provisioning and management process.

<strong style="color: #000;">Value Created</strong>: Improve infrastructure consistency, reduce manual errors, enhance security, and significantly speed up deployment times through automation.


`project`
<strong style="color: #b22222;">Automating Upgrading RHEL7 to RHEL8</strong>

Description: RHEL7 was approaching the end of support, so upgrading hundreds of RHEL7 was a high priority.

Contribution: Designed upgrading plan with application owners and automated upgrading job with Ansible.

<strong style="color: #000;">Value Created</strong>: Ensure systems are aligned with security compliance standards.


`project`
<strong style="color: #b22222;">Ansible Automation Platform on Openshift</strong>

Description: With an ever-increasing number of playbooks, inventories, and workflows, manually managing them is challenging. A central platform is required to orchestrate all the elements related to Ansible.

Contribution: Collaborated with teams on deploying the Ansible Automation Platform on Openshift.

<strong style="color: #000;">Value Created</strong>: Reduced manual tasks and errors while managing playbooks, inventories, and secrets, improved operational efficiency, and enhanced security


`project`
<strong style="color: #b22222;">Preparing Red Hat 9 for Production Infrastructure</strong>

Description: Need to test RHEL9 and make it ready for production use.

Contribution: Deployed Red Hat 9 using Ansible, created a customized Red Hat image template for VMware, and integrated the system with Windows AD.

<strong style="color: #000;">Value Created</strong>: Enable seamless deployment, ensure system compatibility, and make new OS ready for production environment.


`project`
<strong style="color: #b22222;">Automating Patching of Red Hat VM</strong>

Description: The manual patching process for a large-scale Red Hat environment was time-consuming and prone to errors, requiring a more efficient automated solution.

Contribution: Designed and implemented an Ansible-based workflow with Red Hat Satellite to automate patching.

<strong style="color: #000;">Value Created</strong>: Streamlined patching, reduced errors, and improved system uptime and security across the infrastructure.

`project`
<strong style="color: #b22222;">Automating the Provisioning of Red Hat VM on VMWare Private Cloud Platform</strong>

Description: The manual work of provisioning large-scale Red Hat VM was just impossible.

Contribution: Designed and implemented an Ansible-based workflow that automated the process of provisioning VM into the production environment.

<strong style="color: #000;">Value Created</strong>: Streamlined installation, configuration, and management of VM.


`project`
<strong style="color: #b22222;">Deploying critical application to infrastructure(sole role)</strong>

Description: A critical cloud-based application must be deployed, configured, and tested across the entire platform.
Contribution: Solo responsibility for installing, configuring, and troubleshooting applications.

<strong style="color: #000;">Value Created</strong>: Ensure that the system is aligned with organization policies.

`project`
<strong style="color: #b22222;">Splunk Implementation</strong>

Description: Implemented Splunk to monitor and analyze logs and metrics across infrastructure. The project involved centralized log collection, efficient indexing, and actionable insights to enhance system observability and operational efficiency.

Contribution: Deployed and configured Splunk Enterprise for centralized log aggregation and real-time monitoring. Developed custom dashboards for infrastructure health monitoring, including CPU usage, memory consumption, disk I/O, and application performance metrics.

<strong style="color: #000;">Value Created</strong>: Enhanced system reliability and performance by proactively identifying incidents.


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
