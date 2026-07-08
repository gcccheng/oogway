---
layout: cv
title: 程刚 的中文简历
---
# 程刚

<span class="accent">Red Hat 认证架构师</span>，<span class="accent">基础设施</span>/<span class="accent">DevOps</span>/<span class="accent">DevEx</span>/<span class="accent">平台工程师</span>

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 个人介绍</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn 页面</a>
</div>

## 个人简介

程刚 是一名自驱型工程师。他相信，<span class="accent">持续学习</span>的心态以及<span class="accent">快速适应</span>新技术的能力，是专业 IT 工程师的核心竞争力。在职业生涯中，程刚 通过不断参与项目、获取认证、参加工作坊和会议、学习课程、与行业同行交流以及使用 AI 工具，主动构建了在<span class="accent">现代基础设施</span>和<span class="accent">平台工程</span>方面的专业能力。他的努力和专业能力也得到了认可，并获得了 <span class="accent">Red Hat Certified Professional of the Year 2024</span> 的荣誉称号（如需了解该奖项，可点击页面顶部的 Red Hat 个人介绍链接）。

除了在 <span class="accent">Red Hat</span> 技术领域的专业经验，程刚 也持续扩展自己在 <span class="accent">DevOps 工程</span>、<span class="accent">平台工程</span>和<span class="accent">站点可靠性工程</span>方面的能力。他曾在小型和大型团队中工作，并根据项目需求承担过系统管理员、基础设施工程师、DevOps 工程师、开发者体验（DevEx）工程师和平台工程师等角色，或同时结合这些职责。在 AI 驱动工程的时代，程刚 也在积极探索人工智能如何辅助平台和基础设施工作，包括 <span class="accent">AI 辅助故障排查</span>、<span class="accent">自动化</span>、基础设施文档，以及通过智能工具提升<span class="accent">开发者生产力</span>。他并不把 AI 看作工程师的替代品，而是将其视为强大的协作者，可以增强<span class="accent">决策能力</span>、加速<span class="accent">问题解决</span>，并帮助工程师把更多精力放在更高层次的<span class="accent">架构思考</span>上。

无论职位名称或工作环境如何变化，程刚 都能快速适应，并通过良好的<span class="accent">沟通能力</span>和<span class="accent">协作意识</span>为业务创造价值。


## 工作经历

`2025-至今`  
***<font size="3">高级平台工程师 — Appear TV，奥斯陆</font>***

Appear TV 是全球领先的视频压缩、媒体处理和分发技术提供商，其技术被全球广播公司、电信运营商以及重大直播活动组织广泛使用，客户包括 NBCUniversal、Discovery、NHL、Formula 1 和 Riot Games。

在 Appear，程刚 负责构建和维护现代化、可扩展的基础设施，以支撑开发者生产力和高性能应用。他的工作重点包括 <span class="accent">裸金属 Kubernetes</span>、<span class="accent">GitOps</span>、<span class="accent">可观测性</span>、<span class="accent">存储</span>、<span class="accent">CI/CD 自动化</span>和<span class="accent">平台安全</span>。

`项目`
<strong style="color: #b22222;">NVIDIA GPU 集群与机器学习模型服务平台</strong>

<strong style="color: #000;">职责</strong>：

基于 NVIDIA GPU Operator 建立 Kubernetes GPU 平台标准，实现 GPU Driver、Container Toolkit、Device Plugin 及相关组件的自动化部署与生命周期管理，形成统一的 GPU 集群基线，降低 GPU 节点维护复杂度，提高平台一致性及可维护性。采用 Helm 与 GitOps 管理 GPU 平台组件，实现 GPU Operator、平台服务及基础设施的声明式部署，使 GPU 平台具备标准化交付、版本管理及快速回滚能力。

**GPU 资源管理**

基于 Kubernetes 建立统一 GPU 资源池，将 GPU 作为平台资源进行集中管理，为 AI 工作负载提供统一调度入口。引入 CUDA MPS 与 GPU Time Slicing，实现 GPU 共享能力，提高 GPU 利用率，支持多个推理服务及研发工作负载共享 GPU 资源。基于 Namespace、ResourceQuota、LimitRange 及 RBAC 建立 GPU 多租户资源管理机制，为不同研发团队提供统一 GPU 服务入口，并结合 Kyverno 对 GPU 工作负载实施安全策略、资源规范及访问控制。完成 NVIDIA MIG（Multi-Instance GPU）平台方案设计及 MVP 验证，评估 GPU 切分、多租户资源隔离及 GPU 利用率优化能力，并与 Time Slicing、CUDA MPS 等 GPU Sharing 技术进行对比分析。

**AI 工作负载平台**

以 vLLM 作为典型 GPU 工作负载，在 Kubernetes GPU 平台部署企业内部推理服务，验证 GPU 平台对 LLM 推理、GPU 调度、GPU 共享及模型生命周期管理的支撑能力。部署 Open WebUI，为内部研发团队提供统一 AI Portal，由 Kubernetes GPU 平台提供模型推理能力，形成完整的内部 AI 服务链路。选择并集成 Envoy Gateway 与 Envoy AI Gateway，统一管理模型服务入口，实现 AI 服务路由、模型端点管理、访问控制及未来 AI Gateway 能力扩展。持续评估和部署多个开源 LLM，重点关注 GPU 显存占用、模型加载时间、推理延迟、吞吐能力、GPU 利用率及平台稳定性，为 GPU 平台容量规划及资源管理提供依据。

**GPU 平台自动化**

将 GitLab Runner GPU Job 纳入 Kubernetes GPU 平台统一管理，实现 GPU CI/CD 工作负载调度，并建立 GPU Pipeline 使用规范。利用 Helm、GitOps 及 Kubernetes 原生能力，实现 GPU 平台组件、模型服务及 AI 工作负载自动化部署，提高平台一致性及交付效率。协调研发团队、平台团队及 AI 使用团队，将 GPU 工作负载从研发实验环境逐步沉淀为企业级平台服务，建立统一运维流程及平台责任边界。

**GPU 可观测性**

将 GPU 平台纳入企业统一监控体系，集成 DCGM Exporter、Prometheus、Grafana，实现 GPU 利用率、GPU Memory、GPU Temperature、Power Usage、ECC Error、GPU Pod 使用情况等指标监控。建立 GPU 平台 Dashboard，持续跟踪 GPU 利用率、推理吞吐量、模型响应延迟及 GPU 资源使用情况，为 GPU 容量规划及平台优化提供数据支撑。

**Kubernetes 平台能力**

集成 Kubernetes 原生分布式存储，为模型缓存、平台组件及 AI 工作负载提供持久化能力，同时保持平台与 GitOps 运维模式一致。 建立 Kubernetes 原生 AI Platform 运维体系，实现 GPU 平台、AI 服务及基础设施统一纳管，并保持平台组件标准化升级及生命周期管理。

<strong style="color: #000;">创造的价值</strong>：

构建企业统一 GPU AI Infrastructure Platform，为机器学习模型推理、AI 应用及 GPU 工作负载提供稳定、可治理、可观测的平台能力。

建立 Kubernetes 原生 GPU 平台标准，实现 GPU 生命周期管理、GPU 自动化部署及统一运维流程，提高平台一致性及可维护性。

通过 GPU 共享、多租户资源管理及 Kubernetes 原生平台能力，提高 GPU 利用率及 GPU 资源交付效率，降低研发团队使用 GPU 的门槛。

为企业内部自托管 AI 平台建立统一 GPU 后端基础设施，在部分业务场景中降低对外部 AI 服务的依赖，并为未来 GPU 集群、AI 推理平台及企业 AI 基础设施建设奠定平台基础。


`项目`
<strong style="color: #b22222;">内部自托管 AI 平台</strong>

交付了一个内部 AI/LLM 能力平台，支持工程场景中的日志和遥测分析、文档生成、事故解释和代码辅助。

<strong style="color: #000;">职责</strong>：

担任技术负责人，主导**平台架构、能力分层和治理模型**。定义路线图和交付标准，组织架构评审，并协调跨团队执行。通过任务拆解和同行评审指导初级工程师，提升交付质量。

围绕 **Open WebUI** 设计面向用户的入口，并由 NVIDIA GPU 推理平台中基于 Kubernetes 的本地模型端点提供后端能力。

评估多种 LLM 后端和工具（托管 API 与本地推理），重点关注**延迟、并发特征、token 成本和模型行为**。

设计 Kubernetes 上的容器化部署模型，包括访问控制、团队隔离以及与现有 SSO / 开发者工具链的集成。

通过比较不同 LLM 提供方（OpenAI、RequestyAI、本地 Llama 变体）在延迟、输出质量和 token 使用方面的表现，探索模型选择策略，并识别适合不同请求类型的模型。

将面向用户的 AI 平台与本地推理后端连接起来，支持混合 AI 策略：在适合的场景使用外部提供方，在数据控制、成本或平台独立性更重要的场景使用自托管开源模型。

实现基础提示词治理、使用日志和成本可见性，为**负责任 AI 和可审计性**打下基础。
与多个研发团队合作，推广 AI 辅助工程实践，并收集反馈用于未来平台演进，例如 RAG、代码搜索和知识库集成。

<strong style="color: #000;">创造的价值</strong>：

建立了公司第一个**统一的内部 AI 入口和平台能力层**，显著降低工程师在日常工作中使用 LLM 的门槛。

将 AI 使用方式从临时、个人化实验转向**系统化、具备策略意识的消费模式**。
为未来的 **AI Gateway 风格能力**建立实践基础，例如多租户路由、成本和可观测性、本地推理以及治理。

`项目`
<strong style="color: #b22222;">自主平台 SRE Agent（AI 驱动运维 MVP）</strong>

<strong style="color: #000;">职责</strong>：

设计并构建模块化自主 SRE Agent，用于减少运维重复劳动并自动化常见平台工程任务，推动从被动告警向主动修复转变。

设计基于 Python 的编排器框架，支持可插拔专家模块（Kubernetes、vSphere 和供应链情报），用于处理多领域基础设施运维。

实现 “Brain + Tools” 架构，Agent 扫描基础设施 API（Kubernetes 和 vSphere），检测运维违规，并利用 LLM 推理（GPT-4o）分析根因和生成修复策略，而不是简单报告错误。

构建 Safety Engine & Policy Gatekeeper 来约束 AI 自主性：Agent 可以自动修复低风险问题（例如重启卡住的虚拟机或解决策略违规），高风险变更则需要人工审批。

使用 Flask 和 HTMX 开发 Mission Control Dashboard，使工程师能够查看 Agent 的推理过程，并通过一键执行审查和批准修复动作。

通过语义推理识别并修补父控制器（Deployment/StatefulSet），而不是临时 Pod，从而解决不可变 Pod 的修复挑战。

集成软件供应链情报模块，能够扫描 Terraform 和 Ansible 仓库、分析 GitHub release notes，并在推荐依赖升级前执行语义风险分析。

<strong style="color: #000;">创造的价值</strong>：

展示了如何通过自动分类和修复基础设施与安全策略违规（例如 Kyverno 告警和平台健康检查）来减少运维重复劳动。

通过将常规依赖更新转化为结构化的审查和批准流程，将维护工作前移，并加速平台升级周期。

展示了在策略护栏下进行安全 AI 辅助运维的方式，说明 L1 级 SRE 任务可以被自动化，从而让资深工程师更专注于架构和平台演进。

为 AI 增强的平台运维建立基础，在保持治理和运维安全的同时，降低工程师使用 LLM 能力的门槛。

`项目`
<strong style="color: #b22222;">CISO 合作与平台安全治理</strong>

<strong style="color: #000;">职责</strong>：

构建并实施 **Kyverno Policy-as-Code**，作为平台安全治理的核心机制。

主导安全治理评审和实施路径，使安全控制与业务需求保持一致。

审查平台基线，识别关键风险和漏洞。

设计并维护 **Validating** 和 **Mutation** 策略，持续迭代策略库。

交付 GitOps 驱动的安全策略，确保可审计、可追溯和可回滚。

与 CISO 和安全架构师密切合作，在 Kubernetes 和 DevOps 环境中实施安全与合规控制，支持 IPO 准备和 ISO 27001 认证。

交付平台级安全加固，包括 RBAC/IAM 治理、网络策略、密钥管理、漏洞修复、镜像扫描、供应链安全（SBOM/签名）和审计日志。

<strong style="color: #000;">创造的价值</strong>：

建立了具备可审计控制和合规准备能力的平台级安全治理体系。
通过将策略与业务需求对齐，在安全要求和交付效率之间取得平衡。


`项目`
<strong style="color: #b22222;">ClickTime 与 Visma 集成（进行中，项目负责人）</strong>

<strong style="color: #000;">职责</strong>：

主导正在进行的内部集成项目，连接 **ClickTime** 与 **Visma**，使 ClickTime 中登记的工时可以同步到 Visma，用于工资和报表。

与 HR、财务、项目负责人和系统利益相关方合作，理解公司按项目和小组追踪弹性工时与加班时间的需求，而这一粒度并非仅靠 Visma 即可覆盖。

帮助利益相关方定义和控制需求，将宽泛的业务需求转化为可执行的集成范围、数据流和验证场景。

虽然软件开发并非平台工程师的核心职责，但主动承担集成开发工作，使用 **Rust** 和 **Claude Code** 进行 AI 辅助开发。

研究 **ClickTime** 和 **Visma** API，理解认证方式、数据模型、端点行为，以及项目、小组和工时数据在两个系统之间的映射方式。

将集成设计为内部中间件服务，具备幂等性检查、重复同步防护、重试处理和可审计同步能力。

应用平台工程实践，包括威胁建模、风险分析、代码测试、lint、Docker 镜像打包、Kubernetes 部署和 Argo CD 配置。

与安全工程师合作，对该集成进行安全分析和风险评估，识别认证、数据映射、访问控制、工资敏感数据处理、API 故障、重复同步、可审计性和运维责任等方面可能出现的问题。

将风险评估转化为实际缓解措施，包括最小权限 API 访问、密钥处理、验证检查、幂等控制、重试与失败处理、日志、审计轨迹和受控上线计划。

在降低对昂贵供应商定制开发依赖的同时，使方案符合挪威工资流程。

<strong style="color: #000;">创造的价值</strong>：

创建了一个节省成本的内部替代方案，用于替代供应商定制的 ClickTime 集成，使公司能够按项目和小组维度追踪工时，同时仍然符合 Visma 和挪威工资要求。

获得了紧凑型软件开发生命周期的实践经验，从利益相关方访谈、需求塑造，到 API 集成设计、实现、测试和生产规划。

最重要的收获不仅是写代码，而是与利益相关方沟通：理解他们的真实需求，帮助他们定义现实可行的需求，并控制项目范围。

通过将安全和业务风险纳入设计，而不是作为后期评审活动，提高了项目的生产就绪程度。


`项目`
<strong style="color: #b22222;">OpenShift Virtualization 迁移 MVP</strong>

<strong style="color: #000;">职责</strong>：

主导 MVP，评估将部分工作负载从 **VMware vSphere** 迁移到 **OpenShift Virtualization** 的可行性，目标是了解 OpenShift VM 是否能支持未来的成本降低和平台融合。

提前定义**网络、存储、操作系统依赖、命名空间和目标落地区域**的映射，以降低迁移不确定性并提升执行一致性。

评估工作负载适配性、性能特征和运维约束，判断哪些系统可在 OpenShift Virtualization 上测试，哪些应继续保留在 VMware 上。

在非生产 MVP 环境中测试迁移场景，并记录未来生产采用时需要考虑的上线事项、回滚需求、变更控制要求和业务影响。

采用**平台工程方法论**，而不是仅以工具为中心的迁移方式，重点关注标准化、可复用模式、自动化、基础设施即代码、自助服务护栏、可观测性和治理。

与基础设施和应用利益相关方协作，平衡停机预期、性能风险、合规要求和交付时间线。

<strong style="color: #000;">创造的价值</strong>：

为潜在的**成本降低**和长期**平台融合**创建了务实的评估路径，将 OpenShift 作为同时承载虚拟机和容器工作负载的可能基础。

通过提前定义映射和权衡，降低迁移风险，提高围绕存储、网络、性能和运维责任的可预测性。

建立了可复用的评估模式和治理考量，如果公司决定向生产采用推进，可使未来工作负载接入更快、更安全且更易审计。


`项目`
<strong style="color: #b22222;">平台工程</strong>

<strong style="color: #000;">主要职责</strong>:

构建并维护由 Rancher 管理、运行在 Flatcar（不可变操作系统）上的**裸金属 Kubernetes 集群**，支持使用 Rust、C++、Python、Yocto 和 TypeScript 的内部研发团队。

使用 GitLab + ArgoCD 与 Kustomize 设计端到端 **GitOps 工作流**，实现自动化部署、一致的环境管理，并降低运维开销。

使用 **Terraform** 自动化基础设施供应，GitLab 流水线触发 Terraform apply，实现可预测、可审计的变更。

集成 **TrueNAS NFS 后端**，为无状态工作负载提供解耦的持久化存储能力。

管理并优化内部平台组件：**Harbor 镜像仓库、PXE 引导节点、VMware VM 生命周期、ExternalDNS、Bind9、MetalLB、Replicator、GitLab Runners**。

使用 **Prometheus + Grafana** 构建可观测性栈，提供系统健康指标、仪表板和告警。

直接与 **CISO** 协作，确保 CI/CD 流水线、Kubernetes 集群设置和部署工作流符合安全要求和内部治理规范。

通过自动化和平台标准化，提高开发工作流可靠性，降低部署摩擦，并改善整体软件交付生命周期。

参与构建 Appear Hub 项目，这是面向客户的固件、文档和许可证分发平台。协助在 Azure 上使用 Container Apps 实现可扩展后端服务，并使用 Azure Front Door 进行全球路由。


`2022-2025`
***<font size= "3">Sopra Steria 高级基础设施工程师</font>***

Sopra Steria 是欧洲主要的数字服务和咨询公司之一，在挪威是数字化、创新和可持续发展领域的领先咨询公司，服务大型私营企业和公共部门组织。

在 Sopra Steria 期间，程刚 担任 <span class="accent">DevOps</span>/<span class="accent">基础设施工程师</span>，并为客户主导或参与多个项目，包括：

`项目`
<strong style="color: #b22222;">构建高可用 Kubernetes 与 GitHub Actions Runner Controller（ARC）（独立负责）</strong>

描述：现有的 GitHub self-hosted runners 运行在虚拟机（VM）上，带来了明显的扩展性问题、竞态条件和工作负载隔离不足。随着 CI/CD 工作流数量增长，基于 VM 的 runner 已无法提供灵活且易管理的方案。为解决该问题，需要一个容器编排平台按需动态供应和扩展 runner，为 GitHub Actions 工作流提供标准化、隔离且可扩展的基础设施。

贡献：独立负责设计并实施高可用 Kubernetes 集群，并通过 GitHub Actions Runner Controller（ARC）管理动态 runner 供应。将 CI/CD 工作流从基于 VM 的 runner 迁移到 Kubernetes，实现自动扩缩容和隔离，并与开发人员协作重构流水线。建立平台监控和持续维护流程。

<strong style="color: #000;">创造的价值</strong>: 交付了安全、可扩展和自动化的 CI/CD runner 平台，减少人工开销，并提升隔离性、可靠性和开发者生产力。标准化 CI/CD 流水线基础设施以保证一致性和可扩展性，同时支持按需扩缩容以应对工作负载峰值。


`项目`
<strong style="color: #b22222;">使用 Kubernetes 上的 MinIO 实现本地 S3 兼容 Terraform State 后端（独立负责）</strong>

描述：Terraform state 文件此前存储在本地磁盘，导致缺少版本控制、协作困难等问题。由于策略限制，无法使用公共云存储（例如 AWS S3）。

贡献：在内部 Kubernetes 平台上设计并部署基于 MinIO 的 S3 兼容后端。将其与 GitHub Actions 流水线集成，在 CI/CD 工作流中实现安全且带版本控制的 Terraform state 存储。

<strong style="color: #000;">创造的价值</strong>: 建立了可靠、集中且带版本控制的 Terraform state 后端，在不依赖公共云服务的情况下提升协作效率、可审计性和基础设施稳定性。

`项目`
<strong style="color: #b22222;">使用 Argo CD 实现 GitOps 部署工作流（初始实施，唯一平台角色）</strong>

描述：随着开发人员对更快、更灵活部署的需求增长，需要一个允许开发人员动态选择代码部署环境的平台。目标是创建自动化工作流，使 GitHub 中的代码合并能够自动触发 Kubernetes 中新版本部署，从而实现自助服务、减少人工操作，并与现代 DevOps 实践保持一致。

贡献：使用 Argo CD 设计并实现初始 GitOps 工作流，将 GitHub 分支连接到 Kubernetes 命名空间以实现自动化部署。构建基于 Helm 的可复用模板和动态环境仓库结构，并实现 RBAC 与项目隔离以满足安全要求。协调开发团队定义部署流程并确保顺利集成。

<strong style="color: #000;">创造的价值</strong>: 建立了符合 GitOps 的灵活自动化部署流水线，使开发人员能够在不同环境中无缝部署代码。提升部署速度、一致性和安全性，并通过自助服务工作流降低运维开销。

`项目`
<strong style="color: #b22222;">为 OpenShift 实现 Ceph 存储集成</strong>

描述：客户需要一个可扩展且高可用的存储后端，以支持运行在 OpenShift 上的有状态工作负载。我参与部署并集成基于 Ceph 的存储方案，为平台提供可靠的 Persistent Volume 供应能力。

贡献：部署并配置 Ceph 集群作为 OpenShift 的存储后端，确保跨节点高可用和副本能力。通过 StorageClass 和动态 PVC 供应将 Ceph 与 OpenShift 集成，支持有状态应用。验证读写性能、冗余和故障恢复场景。编写运维文档，包括节点替换、OSD 恢复、监控和容量规划。

<strong style="color: #000;">创造的价值</strong>: 为 OpenShift 工作负载交付生产可用的存储基础，使平台能够可靠运行数据库、消息队列和其他有状态服务。通过自动故障转移和自愈存储能力提高弹性并降低运维风险。


`项目`
<strong style="color: #b22222;">构建基础设施监控系统（进行中）（独立负责）</strong>

描述：随着容器和虚拟机数量不断增加，统一监控整个平台基础设施变得非常关键。

贡献：在现有 Kubernetes 平台上构建 Prometheus 和 Grafana，用于同时监控容器和虚拟机，并集成告警和可视化。

<strong style="color: #000;">创造的价值</strong>: 提供实时基础设施可见性、自动告警，并提升平台稳定性。
 
`项目`
<strong style="color: #b22222;">故障排查并改进 CI/CD 流水线</strong>

描述：开发团队在 self-hosted runners 上运行流水线时遇到多种错误和不稳定问题。

贡献：排查流水线错误，优化性能，提高可靠性，并与开发人员密切合作维护有序的工作流。

<strong style="color: #000;">创造的价值</strong>: 将开发人员从故障排查中释放出来，使他们能够专注于开发，并提升整体流水线效率。

`项目`
<strong style="color: #b22222;">基础设施标准化与自动化（独立负责）</strong>

描述：当时的基础设施管理依赖人工操作，缺乏一致性和标准化，导致不同环境中出现低效率和错误。

贡献：标准化操作系统，简化并自动化虚拟机供应和管理流程。

<strong style="color: #000;">创造的价值</strong>: 提升基础设施一致性，减少人工错误，增强安全性，并通过自动化显著加快部署速度。


`项目`
<strong style="color: #b22222;">自动化 RHEL7 到 RHEL8 升级</strong>

描述：RHEL7 即将停止支持，因此升级数百台 RHEL7 系统成为高优先级任务。

贡献：与应用负责人一起设计升级计划，并使用 Ansible 自动化升级任务。

<strong style="color: #000;">创造的价值</strong>: 确保系统符合安全合规标准。


`项目`
<strong style="color: #b22222;">OpenShift 上的 Ansible Automation Platform</strong>

描述：随着 playbook、inventory 和 workflow 数量持续增加，手动管理变得困难。需要一个集中平台来编排所有与 Ansible 相关的元素。

贡献：与团队合作，在 OpenShift 上部署 Ansible Automation Platform。

<strong style="color: #000;">创造的价值</strong>: 在管理 playbook、inventory 和 secret 时减少人工任务和错误，提高运维效率并增强安全性。


`项目`
<strong style="color: #b22222;">为生产基础设施准备 Red Hat 9</strong>

描述：需要测试 RHEL9 并使其准备好用于生产环境。

贡献：使用 Ansible 部署 Red Hat 9，为 VMware 创建定制化 Red Hat 镜像模板，并将系统集成到 Windows AD。

<strong style="color: #000;">创造的价值</strong>: 实现无缝部署，确保系统兼容性，并使新操作系统可用于生产环境。


`项目`
<strong style="color: #b22222;">自动化 Red Hat VM 补丁管理</strong>

描述：大规模 Red Hat 环境中的手动补丁流程耗时且容易出错，因此需要更高效的自动化方案。

贡献：设计并实现基于 Ansible 和 Red Hat Satellite 的自动化补丁工作流。

<strong style="color: #000;">创造的价值</strong>: 简化补丁流程，减少错误，并提升整个基础设施的系统可用性和安全性。

`项目`
<strong style="color: #b22222;">在 VMware 私有云平台上自动化供应 Red Hat VM</strong>

描述：大规模 Red Hat VM 的手动供应工作几乎无法持续。

贡献：设计并实现基于 Ansible 的工作流，将 VM 供应到生产环境的过程自动化。

<strong style="color: #000;">创造的价值</strong>: 简化 VM 的安装、配置和管理。


`项目`
<strong style="color: #b22222;">部署关键应用到基础设施（独立负责）</strong>

描述：一个关键云端应用需要在整个平台上部署、配置和测试。
贡献：独立负责应用安装、配置和故障排查。

<strong style="color: #000;">创造的价值</strong>: 确保系统符合组织策略。

`项目`
<strong style="color: #b22222;">Splunk 实施</strong>

描述：实施 Splunk，用于监控和分析整个基础设施中的日志和指标。项目涉及集中式日志采集、高效索引和可操作洞察，以增强系统可观测性和运维效率。

贡献：部署并配置 Splunk Enterprise，用于集中式日志聚合和实时监控。开发用于基础设施健康监控的自定义仪表板，包括 CPU 使用率、内存消耗、磁盘 I/O 和应用性能指标。

<strong style="color: #000;">创造的价值</strong>: 通过主动识别事件，提升系统可靠性和性能。


`2012-2022`
***<font size= "3">奥斯陆大学系统工程师</font>***

在奥斯陆大学，程刚 担任系统工程师，负责管理和运维一个本地数据中心，为挪威分子医学中心（NCMM）的研究人员提供稳定可靠的科学计算基础设施。他的职责覆盖<span class="accent">核心 IT 运维</span>、<span class="accent">分布式系统工程</span>以及与科研人员的紧密<span class="accent">协作</span>。

<strong style="color: #000;">职责</strong>

服务器与基础设施管理：安装、配置和维护面向科学工作负载的计算系统，包括基于 Linux 的计算节点、分布式 HPC 服务器和 NVIDIA GPU 加速机器。构建并运维大学高性能计算环境的基础组件，确保科研工作负载中的系统可靠性、性能和可扩展性。

Windows 部署与管理：使用 PXE 和 SCCM（System Center Configuration Manager）自动化 Windows 客户端供应和生命周期管理。简化软件分发、安全补丁和策略合规流程，确保稳定运行。

网络运维：使用 <span class="accent">Cisco</span> 交换和路由技术，维护公共大学网络和用于科研设备的内部实验室网络，包括 <span class="accent">VLAN</span>、<span class="accent">trunk</span>、<span class="accent">NAT</span>、基于 <span class="accent">iptables</span> 的防火墙、内部 <span class="accent">DNS</span> 与 <span class="accent">DHCP</span>、端口分配和连接故障排查。支持 NAT 后方通过内部交换实现隔离的内部基础设施。

科学软件与分布式计算环境：安装并维护依赖复杂且不稳定的科学软件栈。为生物信息学、分子建模和大规模数据分析优化计算环境，并为高级分布式工作负载提供技术指导。

日常 IT 运维：执行用户供应、访问控制、存储管理、系统监控（Nagios、Zabbix）和事件故障排查等日常职责，最大限度减少关键科研系统停机时间。

高性能计算（HPC）工程与并行工作负载支持：参与大学 HPC 集群的建设和持续运维，包括配置带 NVIDIA GPU 节点的分布式计算节点、共享存储和 Slurm 调度服务。支持研究人员运行并行和 GPU 加速任务，优化工作负载性能，并排查多节点和高吞吐工作流中的问题。


## 证书
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-程刚-cheng"> Red Hat Certified Professional of the Year 2024</a>

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

## 活动与会议

<a href="https://cloud-native-day-oslo-2025.sessionize.com/schedule"> Cloud Native Day Oslo 2025 </a>

<a href="https://www.redhat.com/en/summit?sc_cid=7013a000003SgNoAAK&gad_source=1&gclid=Cj0KCQjwkN--BhDkARIsAD_mnIrWsK8FpcovhjhNkmFLjS6y1CHJ86KXi1ZhIma1cS59K3BK2zOzx9QaAp_EEALw_wcB&gclsrc=aw.ds"> Red Hat Summit - Red Hat Ansible Fest </a>

## 文章

<a href="https://medium.com/@gcccheng/lets-talk-about-troubleshooting-090ab6cbb95c"> Let´s talk about troubleshooting </a>

<a href="https://medium.com/@gcccheng/challenges-tips-and-rewards-working-as-a-consultant-in-norway-4b6ddce2ff3b"> Challenges, tips, and rewards: working as a consultant in Norway </a>

<a href="https://www.linkedin.com/pulse/cloud-native-day-oslo-reflections-highlights-程刚-cheng-ripaf/?trackingId=rpGDQr2us8CpWZiuR3Sx%2FA%3D%3D"> Cloud Native Day Oslo — From DevOps to DevEx </a>

## 课程

<a href="https://www.coursera.org/learn/gcp-fundamentals"> Google Cloud Fundamentals </a>

<a href="https://www.nvidia.com/en-us/learn/certification/ai-infrastructure-operations-associate/"> Nvidia Academy: AI Infrastructure and Operations
 </a>

<a href="https://www.coursera.org/learn/genai-for-devops-practitioners"> GenAI for DevOps Practitioners </a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS162x+3T2019/home"> Linux Foundation: Introduction to DevOps and Site Reliability Engineering（评分认证课程）</a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS151.x+2T2020/home"> Linux Foundation: Introduction to Cloud Infrastructure Technologies

 
<a href="https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/"> Microsoft Azure Fundamentals </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5004NSA/index.html"> 入侵检测与防火墙 </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF4018NSA/index.html"> 企业网络：实践与技术 </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5100NSA/index.html"> 研究方法与数据分析 </a>

<a href="https://www.udemy.com/course/mastering-ansible/?gclid=Cj0KCQiAhMOMBhDhARIsAPVml-HCo3Nm7AYmD15j425Ld7FLtLZOYQ9vTev6CMsi5-DeO7ST9exGqw0aAuX3EALw_wcB&matchtype=e&utm_campaign=LongTail_la.EN_cc.ROW&utm_content=deal4584&utm_medium=udemyads&utm_source=adwords&utm_term=_._ag_80675493522_._ad_535700245675_._kw_ansible+course_._de_c_._dm__._pl__._ti_kwd-822946965094_._li_1010826_._pd__"> Ansible For System Automation </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF1100/index-eng.html">Introduction to programming with scientific applications</a>

<a href="https://www.edx.org/course/fundamentals-of-containers-kubernetes-and-red-hat">Red Hat: Fundamentals of Containers, Kubernetes, and Red Hat OpenShift</a>

## 工作坊
<a href="https://events.redhat.com/profile/form/index.cfm?PKformID=0x11991670001">Azure Red Hat OpenShift AI</a>

<a href="https://aws-experience.com/emea/north/e/ddd34/aws-immersion-day-generative-ai"> AWS RAG and Fine-tuned AI</a>
            
<a href="https://www.uio.no/english/services/it/research/hpc/fox/index.html"> 为 Educloud Research 用户使用高性能计算集群 </a>
    
<a href="https://isovalent.com/isovalent-hands-on-workshop-oslo/"> Cilium Hands-On Workshop & Deep Dive Oslo </a>

在 Azure 上管理 VM、虚拟网络和防火墙
  
<a href="http://modules.sourceforge.net/">使用 Environment Modules 初始化 shell 并修改 shell 环境</a>
  
使用 Terraform 部署 AWS EC2 实例

使用 Podman 运行容器
  
<a href="https://www.ub.uio.no/english/courses-events/courses/other/Carpentry/211103_github"> 使用 Git 进行版本控制 </a>

密码学与 SSH 远程登录
  
<a href="https://www.ub.uio.no/english/courses-events/courses/other/coderefinery/Python%20for%20Scientific%20Computing%20%28internediate%29"> 面向科学计算的 Python</a>

<a href="https://arnsteio.github.io/UH-IaaS-mini-workshop/"> 使用 OpenStack 的虚拟化科研架构</a>
  
<a href="https://www.uio.no/tjenester/it/forskning/kompetansehuber/uio-ai-hub-node-project/it-resources/"> UiO 的 AI </a>

## 其他项目

在 Azure OpenShift 上构建多模型生成式 AI 体验

使用 Terraform 供应 VM，并在 Azure 上配置 CI/CD 流水线

构建用于复杂 IT 系统的 Proxmox 虚拟化基础设施
  
构建 Foreman + Ansible + Smart Proxy，并为大规模基础设施供应主机
  
将 Linux 集成到 Windows 域

构建基于 OCS Inventory 的现代资产清单系统
  
使用 OpenLDAP 搭建本地目录服务
  
<a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus"> 为实验室网络搭建 Windows Server Update Services</a>

<a href="https://guacamole.apache.org/">使用 Apache Guacamole 作为免费开源跨平台远程桌面网关</a>
  
使用 Snort 和 Munin 进行入侵检测与监控

## 熟悉的技术栈
<span class="accent">OpenShift</span>, <span class="accent">Kubernetes</span>, <span class="accent">Docker</span>, <span class="accent">Podman</span>, <span class="accent">GitHub Actions</span>, GitHub Actions Runner Controller(ARC), <span class="accent">Red Hat Linux</span>, Red Hat Satellite, <span class="accent">Red Hat Ansible</span>, Atlassian Bitbucket, Atlassian Confluence, Atlassian Jira, <span class="accent">Grafana</span>, <span class="accent">Prometheus</span>, Dell PowerEdge, <span class="accent">Cisco Switch</span>, Windows Server 2016, <span class="accent">Ansible</span>, <span class="accent">Terraform</span>, <span class="accent">Bash</span>, Perl, <span class="accent">Python</span>, Windows SCCM, Samba, <span class="accent">NFS</span>, FirewallD, Active Directory, <span class="accent">Networking</span>

## 接触过的技能
<span class="accent">AWS</span>, <span class="accent">MS Azure</span>, <span class="accent">OpenStack</span>, Vagrant

## 教育背景
`2010-2012`
奥斯陆大学：网络与系统管理硕士
  
## 兴趣爱好
写博客、滑雪和徒步

## 语言
英语：完全专业工作能力
  
挪威语：专业工作能力


  

<!-- ### Footer

Last updated: May 2013 -->
