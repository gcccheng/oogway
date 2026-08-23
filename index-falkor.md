---
layout: cv
title: Gang Cheng's CV - Falkor Senior Platform Engineer
---
# Gang Cheng 

<span class="accent">Red Hat Certified Architect</span>, <span class="accent">Cloud-Native Platform Engineering</span>/<span class="accent">Kubernetes</span>/<span class="accent">Azure</span>/<span class="accent">AI Platform Operations</span>

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat Profile</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">Linkedin page</a>
</div>

## Summary

Gang is a <span class="accent">Senior Platform Engineer</span> and <span class="accent">Red Hat Certified Architect</span> with more than fourteen years of experience across Linux infrastructure, Kubernetes, OpenShift, automation, CI/CD, GitOps, observability, security governance, and cloud-native platform operations. His work is centered on building reliable internal platforms that improve developer productivity, operational efficiency, and delivery consistency. Red Hat recognized him as the <span class="accent">Red Hat Certified Professional of the Year 2024</span> for his continuous learning, and practical impact.

His recent work maps closely to Falkor's need for a senior engineer who can design, build, and operate a modern, AI-ready platform. At Appear, he operates production Kubernetes platforms, owns GitOps and automation workflows, builds observability and policy guardrails, and has delivered production GPU worker-node capabilities used by developers. He also built an internal AI/LLM MVP on top of the GPU platform and has practical exposure to maintaining Terraform-provisioned Azure backend resources for Appear Hub, including Azure Container Apps and Azure Front Door.

Gang combines hands-on engineering with cross-functional ownership. He has led platform architecture, technical roadmaps, security and risk reviews, stakeholder alignment, and mentoring for junior engineers. He is comfortable working across infrastructure, product, security, R&D, HR, Finance, and business stakeholders, translating broad requirements into maintainable platforms, automation, and operational practices.

For Falkor, Gang brings a strong fit across <span class="accent">Kubernetes</span>, <span class="accent">Azure exposure</span>, <span class="accent">Infrastructure as Code</span>, <span class="accent">Python/Bash/Rust automation</span>, <span class="accent">CI/CD and GitOps</span>, <span class="accent">observability</span>, <span class="accent">security-by-design</span>, and <span class="accent">AI/ML workload operations</span>.



## Employment

`2025-Now`  
***<font size="3">Senior Platform Engineer — Appear TV, Oslo</font>***

Appear TV is a leading global provider of video compression, media processing, and distribution technology, widely used by global broadcasters, telecom operators, and major live event organisations, including NBCUniversal, Discovery, NHL, Formula 1, and Riot Games.

At Appear, Gang works on building and maintaining modern internal platforms that support developer productivity, high-performance applications, and reliable product delivery. His work focuses on <span class="accent">Kubernetes</span>, <span class="accent">GitOps</span>, <span class="accent">observability</span>, <span class="accent">Infrastructure as Code</span>, <span class="accent">CI/CD automation</span>, <span class="accent">platform security</span>, and <span class="accent">AI-ready infrastructure</span>.

`project`
<strong style="color: #b22222;">Production GPU Platform for Development Workloads</strong>

<strong style="color: #000;">Responsibilities</strong>：

Designed, built, and operated production Kubernetes GPU worker-node capabilities for development workloads.

Owned the platform software baseline, including GPU driver lifecycle, GPU operator deployment, GPU-enabled Kubernetes node configuration, reusable cluster baselines, and operational documentation.

Introduced **Time Slicing** and **MPS** to enable fine-grained GPU sharing and multi-tenant concurrency across internal workloads.

Integrated **SR-IOV** and **Multus** for advanced pod networking, supporting workload isolation and more flexible network attachment patterns for data-intensive workloads.

Validated GPU workload readiness and infrastructure behavior before exposing the nodes for developer use.

Brought **GitLab Runner** GPU workloads into platform scheduling with defined policies for GPU pipelines.

Integrated observability into the platform stack, covering **GPU utilisation, workload behaviour, and operational health**.

Enforced access control and policy guardrails for GPU workloads via **Kyverno**.

Coordinated with R&D and platform teams to make GPU-backed development workloads available through a maintainable internal platform model.

<strong style="color: #000;">Value Created</strong>：

Delivered governable, observable, and rollback-safe production GPU infrastructure for development workloads.
Improved infrastructure utilisation and delivery efficiency through multi-tenant optimisation, shared scheduling, SR-IOV/Multus networking, and Kubernetes-native service delivery.

`project`
<strong style="color: #b22222;">AI Model Serving MVP</strong>

<strong style="color: #000;">Responsibilities</strong>：

Built a separate MVP to evaluate local LLM inference on Kubernetes as a possible backend for internal AI experimentation.

Used **vLLM** in GPU-enabled pods to test model serving patterns, endpoint behaviour, model loading, latency, concurrency, and operational stability.

Evaluated **Envoy Gateway** and **Envoy AI Gateway** as a possible traffic and AI routing layer for model endpoint exposure, request routing, policy enforcement, and future observability of inference traffic.

Integrated MVP model-serving components with Kubernetes-native storage and GitOps-driven cluster operations where persistent platform services were needed.

Connected the MVP serving layer with Open WebUI so selected internal users could evaluate self-hosted model endpoints through a familiar interface.

<strong style="color: #000;">Value Created</strong>：

Created a practical MVP path for controlled local machine learning model serving without presenting it as a production internal AI service.

Helped the team evaluate whether selected use cases could reduce dependency on external AI services and what governance, routing, observability, and operational ownership would be required.

`project`
<strong style="color: #b22222;">Internal Self-Hosted AI Platform MVP</strong>

Delivered an internal AI/LLM MVP to explore engineering use-cases such as log and telemetry analysis, documentation generation, incident explanation and code assistance.

<strong style="color: #000;">Responsibilities</strong>：

Acted as technical owner for the MVP, leading **platform architecture, capability layering and governance model**. Defined roadmap and delivery standards, ran architecture reviews, and coordinated cross‑team execution. Mentored junior engineers through task decomposition and peer reviews to improve delivery quality.

Designed the platform around **Open WebUI** as the user-facing interface, backed by locally served Kubernetes-based model endpoints from the AI model-serving MVP.

Evaluated multiple LLM backends and tools (hosted APIs and local inference) with a focus on **latency, concurrency characteristics, token cost and model behaviour**.

Designed a containerised MVP deployment model on Kubernetes, including access control, team isolation and integration with existing SSO / developer tooling.

Explored model‑selection strategies by comparing latency, output quality and token usage across different LLM providers (OpenAI, RequestyAI, local Llama variants), identifying which models were most suitable for specific request types.

Connected the user-facing AI MVP with the local inference backend to evaluate a hybrid AI strategy: external providers where appropriate, and self-hosted open-source models where data control, cost, or platform independence mattered more.

Implemented basic prompt governance, usage logging and cost visibility, laying groundwork for **responsible AI and auditability**.
Worked with several R&D teams to promote AI‑assisted engineering practices and capture feedback for future platform evolution (e.g. RAG, code search, knowledge base integration).

<strong style="color: #000;">Value Created</strong>：

Established the company’s first **unified internal AI MVP entry point and platform capability layer**, lowering the barrier for engineers to evaluate LLMs in daily work.

Shifted part of the AI exploration from ad‑hoc, individual experimentation toward **systematic, policy‑aware evaluation**.
Created a practical MVP foundation for future **AI Gateway‑style capabilities** such as multi‑tenant routing, cost/observability, local inference, and governance.

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

Implemented a Kubernetes security toolchain covering **Kyverno** for policy enforcement, **Trivy** for CVE scanning and NIS benchmark checks, and **Falco** for runtime security detection.

Led security governance reviews and implementation paths, aligning security controls with business requirements.

Reviewed platform baselines to identify key risks and vulnerabilities.

Designed and maintained **Validating** and **Mutation** policies, continuously iterating the policy library.

Delivered GitOps‑driven security policies for auditability, traceability and rollback.

Worked closely with the CISO and security architects to implement security and compliance controls across Kubernetes and DevOps environments, supporting ISO 27001 certification and ongoing platform governance.

Delivered platform‑level security hardening, including RBAC/IAM governance, network policies, secrets management, vulnerability remediation, image scanning, benchmark checks, runtime detection, supply‑chain security (SBOM/signing), and audit logging.

<strong style="color: #000;">Value Created</strong>：

Established a platform‑level security governance system with auditable policy controls, CVE visibility, benchmark evidence, runtime detection, and compliance readiness.
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
<strong style="color: #b22222;">Azure Backend Infrastructure Maintenance for Appear Hub</strong>

<strong style="color: #000;">Responsibilities</strong>：

Supported **Appear Hub**, a customer-facing delivery platform for firmware, documentation, and license distribution.

The backend Azure infrastructure was delivered by the platform team using **Terraform**, including Azure resources such as **Azure Container Apps** and **Azure Front Door**.

Participated in a limited capacity during the implementation phase, mainly by understanding the Terraform structure, resource layout, and operational responsibilities.

Took part in regular maintenance of the Terraform-provisioned Azure resources, helping keep infrastructure changes controlled, reviewable, and aligned with the team's platform standards.

<strong style="color: #000;">Value Created</strong>：

Gained practical exposure to maintaining Azure backend infrastructure in a customer-facing production context.

Helped support operational continuity for Terraform-managed Azure resources owned by the platform team.


`project`
<strong style="color: #b22222;">Production Ingress Controller Migration from NGINX to Traefik</strong>

<strong style="color: #000;">Responsibilities</strong>：

Led the migration planning for a production Kubernetes cluster moving from **NGINX Ingress Controller** to **Traefik**, because the existing NGINX-based setup was no longer a supported long-term option for the platform.

Analysed a complex ingress landscape with hundreds of Kubernetes Ingress resources, multiple application teams, production traffic exposure, **ExternalDNS**, **MetalLB**, DNS records, load balancer IP behaviour, TLS configuration, and rollback requirements.

Designed a staged migration plan covering inventory, compatibility checks, risk areas, test scenarios, communication, production sequencing, validation, and rollback.

Validated the migration approach first in a test cluster, using representative ingress patterns to identify behaviour differences and operational risks before touching production.

Adjusted the production plan based on test-cluster findings, including controller configuration, ingress annotations, DNS behaviour, service exposure, and cutover order.

Executed the production migration in a controlled way, verifying application reachability, DNS updates, load balancer behaviour, and ingress routing after each migration step.

<strong style="color: #000;">Value Created</strong>：

Reduced migration risk for a production platform by proving the approach in test first, adapting the plan based on real findings, and using staged production execution instead of a big-bang replacement.

Maintained service continuity across a complex ingress environment while moving the platform to a supported ingress controller foundation.


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
<strong style="color: #b22222;">Red Hat Enterprise Linux Lifecycle Modernisation</strong>

Description: Large Red Hat Enterprise Linux environments needed lifecycle modernisation across operating system upgrades, patching, provisioning, and future production baselines.

Contribution: Designed upgrade and preparation plans with application owners, automated RHEL7-to-RHEL8 upgrade workflows with Ansible, deployed and validated RHEL9, created a customised RHEL9 VMware image template, integrated the new operating system baseline with Windows AD, and implemented Ansible and Red Hat Satellite workflows for VM patching and provisioning on VMware.

<strong style="color: #000;">Value Created</strong>: Improved operating system lifecycle management, reduced manual upgrade, patching, and provisioning work, aligned systems with security and compliance requirements, and prepared a standardised RHEL9 baseline for future production use.


`project`
<strong style="color: #b22222;">Ansible Automation Platform on Openshift</strong>

Description: With an ever-increasing number of playbooks, inventories, and workflows, manually managing them is challenging. A central platform is required to orchestrate all the elements related to Ansible.

Contribution: Collaborated with teams on deploying the Ansible Automation Platform on Openshift.

<strong style="color: #000;">Value Created</strong>: Reduced manual tasks and errors while managing playbooks, inventories, and secrets, improved operational efficiency, and enhanced security

`2012-2022`
***<font size= "3">System Administrator → System Engineer → Senior Engineer at University of Oslo</font>***

At the University of Oslo, Gang grew from <span class="accent">System Administrator</span> to <span class="accent">System Engineer</span> and then <span class="accent">Senior Engineer</span>, taking on broader ownership as his responsibilities expanded. He managed and operated a local data center dedicated to scientific computing infrastructure for researchers at the Centre for Molecular Medicine Norway (NCMM). His responsibilities spanned <span class="accent">Linux systems</span>, <span class="accent">physical server operations</span>, <span class="accent">HPC support</span>, <span class="accent">NVIDIA GPU-accelerated machines</span>, distributed computing environments, and close collaboration with scientific researchers.

<strong style="color: #000;">Responsibilities</strong>

Server & Infrastructure Management: Installed, configured, and maintained physical and virtual compute systems for scientific workloads, including Linux-based compute nodes, distributed HPC servers, and NVIDIA GPU-accelerated machines. Built and operated foundational components of the university's high-performance computing environment, ensuring system reliability, performance, and scalability across research workloads.

Windows Deployment and Administration: Automated provisioning and lifecycle management of Windows clients using PXE and SCCM (System Center Configuration Manager). Streamlined software distribution, security patching, and policy compliance for stable operation.

Network Operations: Worked with public university networks and an internal lab network for research equipment using <span class="accent">Cisco</span> switching and routing, including <span class="accent">VLANs</span>, <span class="accent">trunks</span>, <span class="accent">NAT</span>, <span class="accent">iptables</span>-based firewalling, internal <span class="accent">DNS</span> and <span class="accent">DHCP</span>, port assignments, and connectivity troubleshooting. Supported segmented internal infrastructure behind NAT via internal switching.

Scientific Software & Distributed Computing Environment: Installed and maintained complex scientific software stacks with unstable dependencies for bioinformatics, molecular modeling, and large-scale data analysis. Supported researchers running compute-intensive and GPU-accelerated workloads by troubleshooting dependency, environment, performance, and job-execution issues.

Daily IT Operations: Performed daily responsibilities including user provisioning, access control, storage management, system monitoring (Nagios, Zabbix), and incident troubleshooting, minimizing downtime for critical research systems.

High-Performance Computing (HPC) Engineering & Parallel Workload Support: Contributed to the build-out and ongoing operation of the university's HPC cluster, including configuration of distributed compute nodes with NVIDIA GPU nodes, shared storage, and Slurm scheduling services. Supported researchers in running parallel and GPU-accelerated jobs, optimized workload performance, and troubleshot issues across multi-node and high-throughput workflows.


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
<span class="accent">Kubernetes</span>, <span class="accent">OpenShift</span>, <span class="accent">Azure Container Apps</span>, <span class="accent">Azure Front Door</span>, <span class="accent">Terraform</span>, <span class="accent">Argo CD</span>, <span class="accent">GitOps</span>, <span class="accent">Kustomize</span>, <span class="accent">Helm</span>, <span class="accent">GitLab CI/CD</span>, <span class="accent">GitHub Actions</span>, GitHub Actions Runner Controller(ARC), <span class="accent">Prometheus</span>, <span class="accent">Grafana</span>, <span class="accent">Azure Monitor exposure</span>, <span class="accent">Python</span>, <span class="accent">Bash</span>, <span class="accent">Rust</span>, <span class="accent">Ansible</span>, <span class="accent">Red Hat Ansible Automation Platform</span>, <span class="accent">Red Hat Linux</span>, Red Hat Satellite, <span class="accent">Docker</span>, <span class="accent">Podman</span>, <span class="accent">Kyverno</span>, <span class="accent">Harbor</span>, <span class="accent">Longhorn</span>, <span class="accent">Ceph</span>, <span class="accent">NFS</span>, <span class="accent">VMware vSphere</span>, <span class="accent">SR-IOV</span>, <span class="accent">Multus</span>, <span class="accent">Networking</span>, Active Directory, Windows SCCM

## Exposure Skills
<span class="accent">AWS</span>, <span class="accent">Microsoft Azure</span>, <span class="accent">Azure Red Hat OpenShift</span>, <span class="accent">OpenStack</span>, Vagrant

## Education
`2010-2012`
University of Oslo: Master in Network and System Administration
  
## Hobbies 
Blog writing, Skiing, and hiking
  
## Languages 
English: Full Professional Working Proficiency
  
Norwegian: Limited Professional Working Proficiency


  

<!-- ### Footer

Last updated: May 2013 -->
