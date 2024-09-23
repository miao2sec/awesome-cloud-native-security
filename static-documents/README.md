# 静态文档

> 🚥
>
> **一旦完成后内容基本不再变化的文档**。它们通常在首次创建和发布后不进行定期更新。

## 2024-09

63. Ransomware in the Cloud: Scattered Spider Targeting Insurance and Financial Industries
- 🔗 链接：<https://blog.eclecticiq.com/ransomware-in-the-cloud-scattered-spider-targeting-insurance-and-financial-industries>
- 💬 简介：这篇文章讨论了名为 Scattered Spider 的勒索软件组织，如何专门针对云环境中的金融和保险行业进行攻击。攻击者主要使用社工手段获取员工账户的访问权限，然后利用合法工具在网络中横向移动，执行勒索软件攻击。文章还强调了组织在防范此类威胁时，应加强对云基础设施的保护，并提高员工的安全意识。

62.  The Cloud is Darker and More Full of Terrors
- 🔗 链接：<https://www.chrisfarris.com/post/sect2024/>
- 💬 简介：Chris Farris在2024年Sec-T会议上的演讲总结，主题是公共云服务的安全问题。当前IT行业在使用公共云服务时存在根本性的不安全问题。作者通过多个案例分析，强调了云服务提供商和用户在云安全方面的责任和挑战。

61. Kubernetes CRD generation pitfalls
- 🔗 链接：<https://ahmet.im/blog/crd-generation-pitfalls/>
- 💬 简介：这篇文章讨论了使用 controller-gen 生成 Kubernetes 自定义资源定义（CRD）时常见的陷阱和注意事项。文章建议开发者严格验证字段，确保标记字段为必需或可选，避免错误的零值处理，解决嵌套字段的默认值和验证问题。它还指出，某些注释标记不会被自动验证，导致潜在问题。文章建议使用更好的静态分析工具来检测这些问题，并呼吁开发者贡献改进。

60. Noisy Neighbor Detection with eBPF——基于eBPF的噪声邻居检测
- 🔗 链接：<https://netflixtechblog.com/noisy-neighbor-detection-with-ebpf-64b1f4b3bbdd>
- 💬 简介：这篇文章讨论了 Netflix 使用 eBPF来检测云环境中的 "Noisy Neighbor"(噪声邻居)问题。这种问题发生在共享资源的多租户环境中，当某个租户占用过多资源时，可能会影响到其他租户的性能。eBPF 通过高效、低开销地监控系统行为和网络流量，帮助 Netflix 识别并缓解这种资源争夺现象，从而提高系统性能和稳定性。

## 2024-08

59. How Container Networking Works: a Docker Bridge Network From Scratch：
- 🔗 链接：<https://labs.iximiuz.com/tutorials/container-networking-from-scratch>
- 💬 简介：这篇是关于如何从头开始构建容器网络的详细教程，特别是单主机容器网络。作者通过逐步指导读者创建和配置网络环境，解释了容器网络的工作原理。

58. Binary secret scanning helped us prevent (what might have been) the worst supply chain attack you can imagine
- 🔗 链接：<https://jfrog.com/blog/leaked-pypi-secret-token-revealed-in-binary-preventing-suppy-chain-attack/>
- 💬 简介：JFrog安全研究团队通过二进制扫描发现并报告了一个泄露的访问令牌，该令牌具有管理员权限，可以访问Python、PyPI和Python软件基金会的GitHub仓库。这个令牌被泄露在Docker Hub托管的一个公共Docker容器中。JFrog的报告给出了对二进制扫描和Secret检测的一些建议。

57. SeamlessPass: Leveraging Kerberos Tickets to Access the Cloud
- 🔗 链接：[SeamlessPass: Leveraging Kerberos Tickets to Access the Cloud](https://malcrove.com/seamlesspass-leveraging-kerberos-tickets-to-access-the-cloud/)
- 💬 简介：介绍了一个名为SeamlessPass的工具，它利用微软的无缝单点登录（Seamless SSO）功能，通过使用本地Active Directory Kerberos票据来获取Microsoft 365服务的访问令牌，适用于红队场景。

56. ECS任务元数据证书获取的新视角
- 🔗 链接：[A Fresh Perspective on Exfiltrating ECS Task Metadata Credentials](https://saransh-rana.gitbook.io/aboutme/a-fresh-perspective-on-exfiltrating-ecs-task-metadata-credentials)
- 💬 简介：用非常简单的术语列出了攻击者登录到运行ECS任务的ec2主机之后的时间内，如果没有及时发现攻击者后渗透会很容易和自动化。Saransh在文章的最后给出了一个脚本，用于收集和提取任务凭据，这对蓝队和红队成员都很有用。

55. AWS安全检测工程系列
- 🔗 链接：[My Methodology to AWS Detection Engineering (Part 1: Object Selection)](https://chesterlebron.blogspot.com/2024/08/my-methodology-to-aws-detection-engineering-part-1.html)
- 💬 简介：Chester Le Bron介绍了一些列AWS攻击检测的方法，值得参考。

54. CVE-2024-43044的分析：Jenkins通过agent文件读取到RCE
- 🔗 链接：[Analysis of CVE-2024-43044 — From file read to RCE in Jenkins through agents](https://blog.convisoappsec.com/en/analysis-of-cve-2024-43044/)
- 💬 简介：2024年8月7日，Jenkins 官方披露 CVE-2024-43044 Jenkins agent connections 文件读取漏洞。Jenkins 受影响版本中，攻击者在获取agent权限后，可利用agent功能与Jenkins交互，从而读取 Jenkins 控制器文件系统上的任意文件，并结合其他功能等可能导致任意代码执行。这篇博客分析了详细的漏洞利用过程。

53. Linux持久化攻击及检测手段
- 🔗 链接：[Linux Detection Engineering -  A primer on persistence mechanisms](https://www.elastic.co/security-labs/primer-on-persistence-mechanisms)
- 💬 简介：来自elastic security labs博客，这篇文章主要介绍了攻击者如何在Linux系统上建立持久化攻击以及如何有效检测这些攻击手段。文章前传：[使用Auditd进行Linux检测](https://www.elastic.co/security-labs/linux-detection-engineering-with-auditd)

52. ShinyHunters勒索软件的探究（针对AWS进行攻击）
- 🔗 链接：[Bling Libra’s Tactical Evolution: The Threat Actor Group Behind ShinyHunters Ransomware](https://unit42.paloaltonetworks.com/shinyhunters-ransomware-extortion/)
- 💬 简介：这篇文章探讨了一个名为 ShinyHunters 的黑客组织，他们通过勒索软件和数据泄露来实施勒索。该组织以入侵多个公司系统、窃取敏感数据为目标，然后威胁公开这些数据以勒索赎金。文章分析了 ShinyHunters 的攻击策略和行为模式，并提出了一些安全建议，帮助企业防范此类攻击，保护自身数据和系统安全。

51. 深入探究Kubernetes威胁模型
- 🔗 链接：[A Deep Dive Into Kubernetes Threat Modeling](https://www.trendmicro.com/vinfo/us/security/news/security-technology/a-deep-dive-into-kubernetes-threat-modeling)
- 💬 简介：这篇文章探讨了在Kubernetes环境中正确执行威胁建模所需的方面和注意事项。分析了与Kubernetes环境相关的安全风险，介绍了各种攻击面，例如API服务器、节点、控制平面组件等，并讨论了潜在的攻击手法和威胁场景。此外，还提供了一些最佳实践和防护策略，以帮助用户更好地保护Kubernetes集群。

50. Kanister默认Kanister-Operator权限提升漏洞(CVE-2024-43403)
Kanister Vulnerability Opens Door to Cluster-Level Privilege Escalation(CVE-2024-43403)
- 🔗 链接：<https://cvefeed.io/vuln/detail/CVE-2024-43403>
- 🔗 相关博客：<https://securityonline.info/cve-2024-43403-kanister-vulnerability-opens-door-to-cluster-level-privilege-escalation/>
- 💬 简介：Kanister工具存在严重漏洞CVE-2024-43403，攻击者可利用该漏洞获取对Kubernetes集群的完全控制。Kanister是一个数据保护工作流管理工具。Kanister有一个名为default-kanister-operator的部署，它与一个名为edit的ClusterRole通过ClusterRoleBinding绑定。该“edit”ClusterRole是Kubernetes默认创建的ClusterRole之一，它具有对daemonset资源的创建/修补/更新操作权限，对serviceaccount/token资源的创建权限以及对serviceaccounts资源的模拟权限。恶意用户可以利用访问拥有此组件的工作节点来进行集群级别的权限提升。目前尚未记录受影响的产品的具体版本，需要进一步跟踪。

49. K8s RBAC最佳安全实践
- 🔗 链接：[K8s RBAC最佳安全实践](https://mp.weixin.qq.com/s/XuNx9WNKmCJEo_FS8lfwYw)
- 💬 简介："K8s RBAC最佳安全实践"是来自字节跳动技术团队的文章。文章首先介绍了Kubernetes的认证与授权体系以及RBAC授权原理,然后通过实际案例展示RBAC管理不当可能导致的安全风险，并分享RBAC安全研发与运维的最佳实践，以及在字节跳动内部的安全防护和治理经验。

48. K8s安全基础系列文章（DataDog）
- 🔗 链接： [Kubernetes security fundamentals: Authorization](https://securitylabs.datadoghq.com/articles/kubernetes-security-fundamentals-part-4/)
- 🔗 作者视频：<https://www.youtube.com/watch?v=2setap7IgNc>
- 💬 简介：Kubernetes安全基础——授权。来自Rory McCune发布在datadog的文章，这是他"Kubernetes安全基础"系列的第四篇文章。前三篇分别是Kubernetes安全基础简介、Kubernetes API安全、Kubernetes认证；可以从第一篇开始阅读学习。在youtube上也有他的分享。更新第5篇：[Kubernetes安全基础——准入控制](https://securitylabs.datadoghq.com/articles/kubernetes-security-fundamentals-part-5/)

47. 容器安全的系列文章（DataDog）
- 🔗 链接：[container security fundamentals](https://securitylabs.datadoghq.com/articles/?s=container%20security%20fundamentals)
- 💬 简介：同样是来自Rory McCune发布在datadog的系列文章，“容器安全基础”系列共有6篇文章。

46. 针对云环境的大规模勒索攻击
    
- 📅 日期：2024-08-15
- 🔗 链接：[Leaked Environment Variables Allow Large-Scale Extortion Operation of Cloud Environments](https://unit42.paloaltonetworks.com/large-scale-cloud-extortion-operation/)
- 💬 简介：这篇文章由Palo Alto Networks的Unit 42研究团队撰写，揭露了一个针对云环境的大规模勒索攻击。攻击者利用泄露的环境变量来访问敏感信息，并要求受害者支付赎金以避免数据泄露或服务中断。文章强调了安全配置云环境的重要性，建议企业定期审查和监控云基础设施的安全措施，包括访问控制和日志记录，以预防此类勒索攻击。文章还指出云安全漏洞是网络犯罪分子的一个主要攻击目标。

45. 深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线

- 📅 日期：2024-08-04
- 🔗 链接：[深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线（来自"WAKE UP技术"公众号）](https://mp.weixin.qq.com/s/HHGDJ_xtyNTcw0xTrWP7AA)

44. ArtiPACKED：GitHub Actions Artifacts

- 📅 日期：2024-08-13
- 🔗 链接：[ArtiPACKED：GitHub Actions Artifacts](https://unit42.paloaltonetworks.com/github-repo-artifacts-leak-tokens/)
- 💬 简介：这篇博客分析了在GitHub Actions中由于竞态条件导致的漏洞，该漏洞可以让攻击者通过上传恶意工件来窃取敏感信息，比如访问令牌(如GitHub令牌和第三方云服务凭据)。这种攻击方式被称为“ArtiPACKED”。文章详细描述了这一攻击的工作原理、潜在的危害以及如何防范此类攻击。

43. Grand Theft Actions: Abusing Self-Hosted GitHub Runners at Scale

- 📅 日期：2024-08
- 🔗 链接：<https://github.com/AdnaneKhan/ConferenceTalks/blob/main/DEFCON32_GrandTheftActions.pdf>
- 🔗 链接：Gato-X：<https://github.com/AdnaneKhan/Gato-X>
- 💬 简介：AdnanKhan和John Stawinski在DEF CON演讲中分享了他们一直在做的GitHub Action研究，他们已经发现了许多互联网规模的供应链安全漏洞，同时发布了Gato-X工具，以帮助其他安全研究人员大规模发现这些类型的漏洞。

42. CVE-2024-7646：Ingress-nginx注释验证绕过

- 📅 日期：2024-08-16
- 🔗 链接1：[K8s issue](https://github.com/kubernetes/kubernetes/issues/126744)
- 🔗 链接2：[CVE-2024-7646: Ingress-NGINX Annotation Validation Bypass – A Deep Dive](https://securityboulevard.com/2024/08/cve-2024-7646-ingress-nginx-annotation-validation-bypass-a-deep-dive/)
- 🔗 链接3：[CVE-2024-7646：Ingress-nginx注释验证绕过【高危】](https://mp.weixin.qq.com/s/heUTzB0clK0TP0bDGEunGw)

## 2024-07

41. 利用gitRepo volumes创建权限如何拿下K8s节点root权限

- 📅 日期：2024-07
- 🔗 链接1：[Sneaky write hook: git clone to root on k8s node](https://irsl.medium.com/sneaky-write-hook-git-clone-to-root-on-k8s-node-e38236205d54)
- 🔗 链接2：[Fun With GitRepo Volumes](https://raesene.github.io/blog/2024/07/10/Fun-With-GitRepo-Volumes/)
- 💬 简介：这两篇博客文章讨论了一个Kubernetes中未修补的安全问题，允许任何有权限创建gitRepo卷的用户以root用户身份在底层主机上执行代码。

40. Kubernetes 历史：它如何征服云原生编排

- 📅 日期：2024-07-25
- 🔗 链接：[Kubernetes History: How It Conquered Cloud Native Orchestration](https://www.aquasec.com/blog/kubernetes-history-how-it-conquered-cloud-native-orchestration/)


39. 过时的安全：为什么我们使用隔离虚拟机

- 📅 日期：2024-07-25
- 🔗 链接：[Unfashionably secure: why we use isolated VMs](https://blog.thinkst.com/2024/07/unfashionably-secure-why-we-use-isolated-vms.html)


38. 揭示AWS会话令牌的内部结构

- 📅 日期：2024-07-25
- 🔗 链接：[Revealing the Inner Structure of AWS Session Tokens](https://medium.com/@TalBeerySec/revealing-the-inner-structure-of-aws-session-tokens-a6c76469cba7)

37. 一份循序渐进的AWS渗透测试指南

- 📅 日期：2024-07-22
- 🔗 链接：[An Opinionated Ramp Up Guide to AWS Pentesting](https://awssecuritydigest.com/articles/opinionated-ramp-up-guide-to-aws-pentesting)
- 💬 简介：Lizzie Moratti提供了一份深入的AWS渗透测试指南，利用了[pwnedlabs.io](https://pwnedlabs.io/)靶场、Rich Mogull的[Cloud Security Lab a Week](https://slaw.securosis.com/)(每周云安全实验室)以及Scott Piper的[AWS Security Maturity Roadmap](https://summitroute.com/downloads/aws_security_maturity_roadmap-Summit_Route.pdf)（AWS安全成熟度路线图）等资源。Lizzie 提供了一些关于云渗透测试的热门观点，以及五阶段学习方法。


36. 容器逃逸：云环境中的逃逸技术(来自Palo Alto博客)

- 📅 日期：2024-07-18
- 💬 标题：Container Breakouts: Escape Techniques in Cloud Environments
- 🔗 链接：[Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/)

35. 启用安全防护：使用 CDK for Terraform 实现基础设施即代码

- 📅 日期：2024-07-15
- 💬 标题：Enabling Security Guardrails: Infra as Code with CDK for Terraform
- 🔗 链接：[Enabling Security Guardrails: Infra as Code with CDK for Terraform](https://engineering.ziphq.com/enabling-security-guardrails-infra-as-code-with-cdk-for-terraform/)

34. 启动您的Kubernetes安全

- 📅 日期：2024-07-02
- 🔗 链接：[Kickstart Your Kubernetes Security](https://cloudnativenow.com/social-facebook/kickstart-your-kubernetes-security/)

## 2024-06

34. Reverse Engineering eBPF Programs: A Deep Dive
- 📅 日期：2024-06-25
- 🔗 链接：[Reverse engineering eBPF programs](https://www.armosec.io/blog/ebpf-reverse-engineering-programs/)
- 💬 简介：介绍了eBPF技术在增强Kubernetes安全性方面的重要性，深入剖析了eBPF的内部工作机制和用法

33. K8s日志指南

- 📅 日期：2024-06-01  
- 🔗 链接：[A Guide To Kubernetes Logs That Isn't A Vendor Pitch](https://grahamhelton.com/blog/k8slogs/)

32. 天翼云对象存储ZOS攻防

- 📅 日期：2024-06-26
- 🔗 链接：[天翼云对象存储ZOS攻防](https://zone.huoxian.cn/d/2916-zos)

31. 攻击者针对暴露的Docker API利用新技巧

- 📅 日期：2024-06-13
- 🔗 链接：[Attackers deploying new tactics in campaign targeting exposed Docker APIs](https://securitylabs.datadoghq.com/articles/attackers-deploying-new-tactics-in-campaign-targeting-exposed-docker-apis/)

## 2024-05

30. Docker 逃逸中被忽略的 pid namespace
- 📅 日期：2024-05-25
- 🔗 链接：[Docker 逃逸中被忽略的 pid namespace](https://tiangonglab.github.io/blog/tiangongarticle030/)

29. 实战-关于KEY泄露API接口利用

- 📅 日期：2024-05-11
- 🔗 链接：[实战-关于KEY泄露API接口利用](https://zone.huoxian.cn/d/2909-keyapi)

## 2024-04

28. 腾讯云对象存储COS（Cloud Object Storage）攻防

- 📅 日期：2024-04-15
- 🔗 链接：[腾讯云对象存储COS（Cloud Object Storage）攻防](https://zone.huoxian.cn/d/2903-coscloud-object-storage)

27. 京东云OSS攻防

- 📅 日期：2024-04-08
- 🔗 链接：[京东云OSS攻防](https://zone.huoxian.cn/d/2901-oss)

## 2024-02

26. TeamTNT攻击组织分析
- 📅 日期：2024-02-01
- 🔗 链接：[An analysis of a TeamTNT doppelgänger](https://securitylabs.datadoghq.com/articles/analysis-of-teamtnt-doppelganger/)

## 2023-11

25. 针对新手的Rego介绍

- 📅 日期：2023-11-03
- 🔗 链接：[Rego for beginners: Introduction to Rego](https://medium.com/@snyksec/rego-for-beginners-introduction-to-rego-0d293d52a654)

## 2023-10

24. MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1

- 📅 日期：2023-10-31～至今
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1](https://attack.mitre.org/matrices/enterprise/containers/)

## 2023-04

23. MITRE 的 Container ATT&CK 攻防矩阵 v13.1

- 📅 日期：2023-04-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v13.1](https://attack.mitre.org/versions/v13/matrices/enterprise/containers/)

22. 容器镜像的妙用——绕过漏洞扫描程序

- 📅 日期：2023-04-22
- 🔗 链接：[Fun with container images - Bypassing vulnerability scanners](https://raesene.github.io/blog/2023/04/22/Fun-with-container-images-Bypassing-vulnerability-scanners/)

## 2022-09

21. NSA 需要强大的 Kubernetes 身份验证和授权

- 📅 日期：2022-09-12
- 🔗 链接：[NSA Wants Strong Kubernetes Authentication and Authorization](https://cloudnativenow.com/features/nsa-wants-strong-kubernetes-authentication-and-authorization/)

## 2022-10

20. MITRE 的 Container ATT&CK 攻防矩阵 v12.1

- 📅 日期：2022-10-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v12.1](https://attack.mitre.org/versions/v12/matrices/enterprise/containers/)

## 2022-07

19. 攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解

- 📅 日期：2022-10-25
- 🔗 链接：[攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解](https://unit42.paloaltonetworks.com/incident-response-report/)

## 2022-04

18. MITRE 的 Container ATT&CK 攻防矩阵 v11.3

- 📅 日期：2022-04-25
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v11.3](https://attack.mitre.org/versions/v11/matrices/enterprise/containers/)

## 2021-11

17. 云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考

- 📅 日期：2021-11-01
- 🔗 链接：[云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考](https://www.freebuf.com/articles/security-management/303010.html)

## 2021-10

16. MITRE 的 Container ATT&CK 攻防矩阵 v10.1

- 📅 日期：2021-10-21
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v10.1](https://attack.mitre.org/versions/v10/matrices/enterprise/containers/)

## 2021-09

15. 腾讯云鼎实验室的云安全攻防矩阵

- 📅 日期：2021-09-26
- 🔗 链接：[云安全攻防矩阵](https://cloudsec.tencent.com/home/)

## 2021-08

14. 青藤的 Kubernetes ATT&CK 攻防矩阵

- 📅 日期：2021-08-25
- 🔗 链接：[最佳实践：发布国内首个K8S ATT&CK攻防矩阵](https://mp.weixin.qq.com/s/-FTJRl1ZK2Etgq7KO17r7w)

## 2021-06

13. 如何设定切实可行的时间框架来修复安全漏洞

- 📅 日期：2021-06-23
- 🔗 链接：[How to Set Practical Time Frames to Remedy Security Vulnerabilities](https://www.gartner.com/smarterwithgartner/how-to-set-practical-time-frames-to-remedy-security-vulnerabilities)

## 2021-05

12. Metarget：云原生攻防靶场开源啦！

- 📅 日期：2021-05-10
- 🔗 链接：[Metarget：云原生攻防靶场开源啦！](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247489415&idx=1&sn=4aea7b7ecff51710c79037ab07a889bc)

## 2021-04

11. MITRE 的 Container ATT&CK 攻防矩阵 v9.0

- 📅 日期：2021-04-29
- 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v9.0](https://attack.mitre.org/versions/v9/matrices/enterprise/containers/)

## 2021-03

10. 微软的 Kubernetes 威胁矩阵（二）

- 📅 日期：2021-03-23
- 🔗 链接：[Secure containerized environments with updated threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/)

9. 红蓝对抗中的云原生漏洞挖掘及利用实录

- 📅 日期：2021-03-02
- 🔗 链接：[红蓝对抗中的云原生漏洞挖掘及利用实录](https://mp.weixin.qq.com/s/Aq8RrH34PTkmF8lKzdY38g)

## 2021-01

8. 伸手党的容器镜像加固流程

- 📅 日期：2021-01-06
- 🔗 链接：[伸手党的容器镜像加固流程](https://blog.fleeto.us/post/harden-docker-image-flow-chart/)

## 2020-10

7. 微软的 Kubernetes 威胁矩阵缺失的内容

- 📅 日期：2020-10-26
- 🔗 链接：[Microsoft's Kubernetes Threat Matrix: Here's What's Missing](https://www.darkreading.com/threat-intelligence/microsoft-s-kubernetes-threat-matrix-here-s-what-s-missing)

## 2020-06

6. 云原生环境渗透相关工具考察

- 📅 日期：2020-06-20
- 🔗 链接：[云原生环境渗透相关工具考察](https://blog.wohin.me/posts/cloud-native-pentest-tools/)

5. 阿里云的云上容器 ATT&CK 攻防矩阵

- 📅 日期：2020-06-18
- 🔗 链接：[国内首个云上容器ATT&CK攻防矩阵发布，阿里云助力企业容器化安全落地](https://developer.aliyun.com/article/765449)

## 2020-04

4. 微软的 Kubernetes 威胁矩阵（一）

- 📅 日期：2020-04-02
- 🔗 链接：[Threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2020/04/02/attack-matrix-kubernetes/)

## 2020-02

3. 深入研究现实世界的Kubernetes威胁

- 📅 日期：2020-02-12
- 🔗 链接：[Deep Dive into Real-World Kubernetes Threats](https://research.nccgroup.com/2020/02/12/command-and-kubectl-talk-follow-up/)

## 2019-05

2. 容器安全：检查容器环境的潜在威胁

- 📅 日期：2019-05-14
- 🔗 链接：[Container Security: Examining Potential Threats to the Container Environment](https://www.trendmicro.com/vinfo/us/security/news/security-technology/container-security-examining-potential-threats-to-the-container-environment)

1. Falco 提供的针对容器运行时安全的 MITRE ATT&CK 框架

- 📅 日期：2019-05-10
- 🔗 链接：[MITRE ATT&CK framework for container runtime security with Falco](https://sysdig.com/blog/mitre-attck-framework-for-container-runtime-security-with-sysdig-falco/)
