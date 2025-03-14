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

Gang is a self-motivated person, and he believes that the mindset of continuous learning and the ability to quickly adapt to new technologies are core competencies for a professional IT engineer. Throughout his career, Gang has proactively built expertise in modern infrastructure, automation, and platform engineering through an ever-growing list of certifications, workshops, conferences and courses. His efforts and expertise were recognized when he received the honor of being awarded and titled as the Red Hat Certified Professional of the Year 2024(if you are curious of what it is, click Red Hat Bio on top for more info). 

In addition to his expertise in Red Hat, Gang has expanded his skills to a wide range of CD/CD, Cloud, platforms, and Site Reliability technologies. He has continuously shifted between roles such as System Administrator, Infrastructure Engineer, DevOps, Developer Experience (DevEx), and Platform Engineer(or more along with the change of industry) — demonstrating the ability to adapt and acquire new skills as required. 

With over a decade of hands-on experience in various IT infrastructure environments, Gang has built his knowledge through professional projects, continuous self-learning, and most importantly, peers from industry. He has successfully delivered solutions to customers, created value for stakeholders, and worked closely with developers and researchers. Gang's strong communication skills and collaborative mindset have enabled him to effectively contribute to cross-functional teams and drive impactful results.


## Employment
`2022-Now`
***<font size= "3">Senior Infrastructure Engineer at Sopra Steria</font>***

During past years, Gang has been worked as DevOps/infrastructure engineer and led/contributed to a variety of projects for customers, including:

**Building High Availability Kubernetes and Github Actions Runner Controller(ARC)**

Description: The existing use of GitHub self-hosted runners on virtual machines (VMs) led to significant scalability issues, race conditions, and lack of workload isolation. As the number of CI/CD workflows grew, VM-based runners could no longer provide a flexible and manageable solution. To address this, a container orchestration platform was required to dynamically provision and scale runners on demand, ensuring standardized, isolated, and scalable infrastructure for GitHub Actions workflows.

Contribution: Designed the architecture for a high-availability Kubernetes platform, enabling resilient and scalable hosting of self-hosted GitHub Actions Runners. Implemented GitHub Actions Runner Controller (ARC) on Kubernetes to manage dynamic provisioning and lifecycle of runners.Tested and validated Kubernetes cluster setup for high availability, including control plane redundancy, node failure resilience, and workload auto-scaling. Redesigned and migrated CI/CD workflows from static VM-based runners to dynamic container-based runners, ensuring compatibility and improved efficiency. Established automated scaling policies and custom GitHub Actions annotations to allocate runners per job needs, enhancing performance and isolation. Collaborated with developers to refactor pipeline steps for optimal use of containerized runners, improving CI/CD pipeline performance and developer experience. Took responsibility for ongoing maintenance, updates, and troubleshooting of the platform to ensure long-term stability and adaptability to evolving CI/CD needs.

Value Created: Improved isolation and security by running each GitHub Actions workflow in a separate container, eliminating cross-pipeline interference. Achieved on-demand scaling of runners, significantly reducing wait time for jobs and optimizing resource utilization. Enhanced reliability and resilience through high-availability Kubernetes cluster, minimizing downtime and failures. Reduced manual effort and operational complexity with fully automated runner provisioning and decommissioning, freeing up platform team capacity. Provided developers with a faster, more reliable CI/CD pipeline, improving overall software delivery speed and quality. Standardized the CI/CD runner infrastructure, enabling consistent, repeatable, and scalable DevOps workflows.

`project`
**Implementing GitOps Deployment Workflow with Argo CD (Ongoing)**

Description: With increasing demands from developers for faster and more flexible deployments, there was a growing need for a platform that allows developers to dynamically choose which environment to deploy their code to. The goal was to create an automated workflow where a code merge in GitHub would automatically trigger deployment of a new version in Kubernetes — enabling self-service, reducing manual operations, and aligning with modern DevOps practices.

Contribution to be made: Design and implement a GitOps-based deployment workflow using Argo CD to synchronize application manifests in GitHub with Kubernetes environments. Integrated GitHub repositories with Argo CD to ensure that merging to specific branches (e.g., dev, stage, prod) automatically triggers deployment to the corresponding Kubernetes namespaces. Set up ApplicationSets and Helm templates to allow dynamic and reusable deployment configurations across multiple environments. Collaborated with development teams to define GitOps repository structure, environment naming conventions, and workflows. Implemented RBAC and Argo CD project isolation to ensure secure and controlled deployment processes.

Value to be created: Imrove efficiency, flexibility, and consistency in application deployment through Git-based change management. Empower developers of self-service application deployment with clear separation of concerns between platform and development teams.


`project`
**Building Infrastructure Monitoring System(ongoing)**

Description: With increasing number of containers, virtual machines, it is become critial to have one platform that can monitor everything.

Contribution to be made: Build Prometheus and Grafana on existing Kubernetes platform to monitor both containers and virtual machines.

Value to be created: Visualized the status of infrastructure, automated the alerting and improved stability of platform

`project`


 
`project`
**Troubleshooting and Improving CI/CD Pipelines**

Description: The current developing team encounters various errors when running pipelines on self-hosted runners.

Contribution: Troubleshooting errors, optimiziing performance, improving reliability and maintaining workflow organized together with developing team .
Value Created: Release developers from troubleshooting errors so they can focus on developing.


`project`
**Infrastructure Standardization and Automation**

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
**Deploying critical application to infrastructure**

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

At the University of Oslo, Gang participated in managing a local data center to deliver a reliable scientific computing infrastructure to researchers at the Centre for Molecular Medicine Norway. His main tasks included:

Installing, configuring, and maintaining Dell/HP/Red Hat servers for a variety of services, including computing, virtualization, database, web, Samba, NFS, and inventory.

Deploying and managing Windows machines with SCCM.

Managing and maintaining 1 public network and 1 private lab network with Cisco devices.

Installing and maintaining complex scientific applications with increasing and unstable dependencies.

Performing daily admin work, including account management, storage management, security, monitoring, and problem troubleshooting.

Assisting researchers using the HPC system at the University of Oslo.

## Education
`2010-2012`
University of Oslo: Master in Network and System Administration
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


## Courses

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
  
Set up local directory service with OpenLDAP
  
<a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus"> Set up Windows Server Update Services for lab network </a>

<a href="https://guacamole.apache.org/">Using Apache Guacamole as free and open-source cross-platform Remote Desktop Gateway</a>
  
Intrusion detection and monitoring with Snort and Munin

## Experienced tech stacks
Kubernetes, Docker, Podman, GitHub Actions, GitHub Actions Runner Controller(ARC), Red Hat Linux, Red Hat Satellite, Red Hat Openshift, Red Hat Ansible,  Atlassian Bitbucket, Atlassian Confluence, Atlassian Jira, Grafana, Prometheus, Dell PowerEdge, Cisco SWitch, Windows Server 2016, Bash, Perl, Python Windows SCCM, Samba, NFS, FirewallD, Active Directory, Networking
## Exposure Skills
AWS, MS Azure, Openstack, Terraform, Vagrant
  
## Hobbies 
Blog writing, Skiing, and hiking
  
## Languages 
English: Full Professional Working Proficiency
  
Norwegian: Professional Working Proficiency


  

<!-- ### Footer

Last updated: May 2013 -->

