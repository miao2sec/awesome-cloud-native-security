# 静态文档

> 🚥
>
> **一旦完成后内容基本不再变化的文档**。它们通常在首次创建和发布后不进行定期更新。

## 2024-12

1. 使用云访问凭证蜜标及时发现入侵行为

    - 📅 日期：2024-12-9
    - 🔗 链接：<https://mp.weixin.qq.com/s/V-LfgmZ_5su6ikvd7bSsPQ>
    - 💬 简介：文章介绍了使用云访问凭证蜜标及时发现入侵行为的方法。云上访问凭证泄露是云安全事件常见且难解决的问题，云厂商虽有检测能力但存在不足。企业可使用蜜标（Honeytokens）快速发现凭证泄露，文中以腾讯云为例，介绍通过云访问凭证蜜标发现企业云上入侵行为的方法，包括创建蜜标凭证及部署操作审计服务和日志服务的步骤，如在访问管理中创建用户及访问凭证、在操作审计界面创建跟踪集、在日志服务中设置通知渠道和告警策略等。最后总结读者可根据自身情况调整通知平台、模版和告警频率，安全人员可放置不同蜜标凭证以快速发现入侵位置，企业应尽快响应以降低影响。

## 2024-11

1. 恶意 PyPI 软件包“Fabrice”窃取数千名开发人员的 AWS 密钥

    - 📅 日期：2024-11-7
    - 🔗 链接：<https://thehackernews.com/2024/11/malicious-pypi-package-fabrice-found.html>
    - 💬 简介：网络安全研究人员在Python包索引（PyPI）上发现了一个恶意软件包，该软件包在三年多的时间里下载了数千次，同时偷偷地窃取了开发人员的亚马逊网络服务（AWS）凭据。有问题的包是“fabrice”，它与一个名为“fabric”的流行Python库相匹配，该库旨在通过SSH远程执行shell命令。

1. 初探Linux内核eBPF之恶意程序行为监控

    - 📅 日期：2024-11-4
    - 🔗 链接：<https://mp.weixin.qq.com/s/wxxS0x8Q4XjqEE5MO_G52A>
    - 💬 简介：本文使用Go语言来编写用户态程序，设计一个可以监控恶意程序行为的沙箱，由于监测程序的命令执行和网络请求。（来自山石网科安全技术研究院）

1. Kubernetes RBAC：改善 K8s 的安全态势

    - 📅 日期：2024-11-8
    - 🔗 链接：<https://www.cncf.io/blog/2024/11/08/kubernetes-rbac-improve-the-k8s-security-posture/>
    - 💬 简介：这篇文章讨论了如何通过改善Kubernetes的角色访问控制（RBAC）来提升Kubernetes安全性。

1. A beginners guide to contributing to CNCF open source projects（初学者参与CNCF开源项目的指南）

    - 📅 日期：2024-11-11
    - 🔗 链接：<https://www.cncf.io/blog/2024/11/11/a-beginners-guide-to-contributing-to-cncf-open-source-projects/>
    - 💬 简介：在这篇博客文章中，将探讨如何参与CNCF（云原生计算基金会）开源项目，您需要贡献哪些知识，以及如何成为这个社区的一员。

1. Making Sense of Kubernetes Initial Access Vectors（理解Kubernetes初始访问向量）

    - 📅 日期：2024-11-14
    - 🔗 链接：[Making Sense of Kubernetes Initial Access Vectors Part 1 – Control Plane](https://www.wiz.io/blog/making-sense-of-kubernetes-initial-access-vectors-part-1-control-plane)
    - 🔗 链接：[Making Sense of Kubernetes Initial Access Vectors Part 2 - Data Plane](https://www.wiz.io/blog/kubernetes-data-plane)
    - 💬 简介：Wiz的文章分为两篇：Part 1 —— 控制平面，探索Kubernetes控制平面访问向量、风险和安全策略，以防止未经授权的访问并保护您的集群免受潜在威胁。Part 2 —— 数据平面，了解Kubernetes数据平面访问，包括在集群上运行的应用程序、容器映像和执行即服务工作负载类型。

1. Kubernetes Audit Log “Gotchas”（解决Kubernetes审计日志的挑战）

    - 📅 日期：2024-11-15
    - 🔗 链接：<https://www.wiz.io/blog/overcoming-kubernetes-audit-log-challenges>
    - 💬 简介：Wiz 的文章分析了 Kubernetes 环境中管理审计日志的复杂性，并提出了改进安全性和提升操作可见性的解决方案。Wiz 强调，这些能力是其更广泛 Kubernetes 和容器安全平台的一部分，旨在全面保护容器化环境。

1. GitHubActions & 阿里云解决国内镜像拉取问题

    - 📅 日期：2024-11-17
    - 🔗 链接1：<https://mp.weixin.qq.com/s/1NAuDD95mcu_zXzSRh7Fuw>
    - 🔗 链接2：<https://mp.weixin.qq.com/s/-bDrC63J52oSEcIfGcQ7pw>
    - 💬 简介：Docker Hub 仓库国内无法拉取镜像，如何应对? 利用Github-Action同步国外镜像到指定的个人Docker hub镜像仓库以及企业在互联网里的私有仓库中。

1. 深入可观测：基于 eBPF 构建下一代容器全栈观测的实践

    - 📅 日期：2024-11-15
    - 🔗 链接：<https://mp.weixin.qq.com/s/Z_-c2jSz_bOmvIceNfxCXg>
    - 💬 简介：随着云原生技术栈的迅速发展，系统复杂性逐渐下沉到服务网格、网关、通用 sidecar、serverless 运行时、内核等基础设施层面，给可观测性带来了巨大的挑战。本文结合真实的排障案例，介绍了火山引擎云原生团队在容器全栈观测方面的技术实践。

1. 绿盟科技发布云原生ATT&CK矩阵

    - 📅 日期：2024-11-12
    - 🔗 链接：<https://mp.weixin.qq.com/s/f5qXmjcghIpOnMR6mV9lhA>
    - 💬 简介：相比于之前微软、MITRE提出的云原生ATT&CK矩阵，此次绿盟提出的云原生ATT&CK矩阵在技术和子技术这两层更全面，对应的技术介绍更加详细。我们丰富了每层技术下对应的子技术数量，淘汰了一些过时的子技术，并且将同类的子技术尽可能归到一个技术中，使得整个云原生ATT&CK矩阵更通用更标准化。详细内容可参考开源项目[nsfocus-cloud-native-attack](https://github.com/Metarget/nsfocus-cloud-native-attack)

1. EMERALDWHALE黑客组织窃取15000+云凭据

    - 📅 日期：2024-11-1
    - 🔗 链接1：<https://hackread.com/emeraldwhale-steals-cloud-credentials-data-s3-bucket/>
    - 🔗 链接2：<https://sysdig.com/blog/emeraldwhale/>
    - 💬 简介：Sysdig 威胁研究团队发现名为 EMERALDWHALE 的全球攻击行动，窃取了超过15,000 个云服务凭证，主要通过滥用暴露的 Git 和 Laravel 文件进行攻击。攻击者利用这些凭证进行网络钓鱼和垃圾邮件活动，并将盗取的数据存储在被攻击者的 S3 桶中。这一事件突显了配置管理的重要性，提醒企业加强对敏感信息的保护。

## 2024-10

1. Ansible-runner配置使用

   - 📅 日期：2024-10-31
   - 🔗 链接：<https://www.cncf.io/blog/2024/10/31/ansible-runner/>
   - 💬 简介：通过适当的配置和设置，您可以创建封装的代码环境，该环境可以部署到容器或远程系统，并且可以解析结果以供进一步使用，例如在 CICD 管道中。

1. 针对 lottie-player 的供应链攻击：你需要知道的一切

    - 📅 日期：2024-10-31
    - 🔗 链接：<https://www.wiz.io/blog/lottie-player-supply-chain-attack>
    - 简介：2024年10月30日，针对流行的JavaScript库lottie-player发起了供应链攻击，注入恶意代码，在使用该库的合法网站上填充Web3钱包连接提示，可能针对主要的加密货币平台和其他高流量网站。lottie-player的受损版本后来从主要的CDN和npm中删除，但仍然使用该库的受损版本的网站仍然受到影响。

1. 什么是 CSPM，看这篇就够了！(探真科技)
   
    - 📅 日期：2024-10-31
    - 🔗 链接：<https://mp.weixin.qq.com/s/Du9h9NmP6KUkz7OqewOYTA>

1. 2024年第三季度软件供应链安全报告（Phylum研究团队）

    - 📅 日期：2024-10-31
    - 🔗 链接：<https://blog.phylum.io/q3-2024-evolution-of-software-supply-chain-security-report/>

1. 攻击者滥用受害者资源从Titan Network获取回报（趋势Trend博客）

    - 📅 日期：2024-10-30
    - 🔗 链接：<https://www.trendmicro.com/en_us/research/24/j/titan-network.html>
    - 💬 简介：在这篇博客文章中，讨论了攻击者如何利用Atlassian Confluence漏洞CVE-2023-22527将服务器连接到Titan网络进行加密挖矿。

1. 云漏洞管理的关键步骤
   
    - 📅 日期：2024-10-30
    - 🔗 链接：<https://www.wiz.io/blog/essential-steps-for-cloud-vulnerability-management>
    - 💬 简介：对云中的漏洞进行优先排序可能会非常困难，这篇Wiz博客帮助团队了解如何采用以速度和准确性为重点的工作流程。

1. 持续漏洞管理的最佳实践（snyk博客）
    - 📅 日期：2024-10-29
    - 🔗 链接：<https://snyk.io/blog/best-practices-continuous-vulnerability-management/>

1. TeamTNT 的 Docker Gatling Gun 战役

    - 📅 日期：2024-10-25
    - 🔗 链接：<https://www.aquasec.com/blog/threat-alert-teamtnts-docker-gatling-gun-campaign/>
    - 💬 简介：这是一篇关于网络安全威胁的文章，主要内容是Aqua Nautilus的研究人员发现了TeamTNT黑客组织正在进行的一项新活动。该组织正在利用云原生环境中的漏洞进行大规模攻击，他们使用了多种技术手段，包括利用Docker Swarm、Docker Hub等云原生工具来传播恶意软件，以及使用Sliver恶意软件进行攻击。


1. Metarget1.0将在TechWorld上亮相

    - 📅 日期：2024-10-25
    - 🔗 链接：<https://mp.weixin.qq.com/s/FzI9NcllIJnMgMMWY6EgVA>
    - 💬 简介：2024 TechWorld 绿盟科技智慧安全大会将在2024年11月1日举办，届时Metarget1.0将正式发布，同时将在TechWorld外展区进行展示。

1. AWS CDK 风险：利用缺失的 S3 存储桶实现账户接管

    - 📅 日期：2024-10-24
    - 🔗 链接：<https://www.aquasec.com/blog/aws-cdk-risk-exploiting-a-missing-s3-bucket-allowed-account-takeover/>
    - 💬 简介：这篇文章介绍了一个关于 AWS Cloud Development Kit（CDK）的安全问题，攻击者可以利用该问题获得目标 AWS 账户的管理访问权限，从而完全接管账户。具体来说，攻击者可以通过创建一个与目标账户的 AWS CDK 部署过程中使用的 S3 存储桶同名的存储桶来实现攻击。
  文章详细介绍了攻击的原理和过程，并提供了一些缓解措施，包括使用自定义的 S3 存储桶名称、使用 IAM 策略条件限制对 S3 存储桶的访问等。

1. 介绍SkyScalpel：一种在云环境中对抗策略混淆的开源工具

    - 📅 日期：2024-10-24
    - 🔗 链接：<https://permiso.io/blog/introducing-sky-scalpel-open-source-tool>
    - 💬 简介：SkyScalpel的是一款开源工具，可以对混淆的JSON文档进行模糊处理、去模糊处理和检测，并特别关注用于控制AWS云环境中权限的IAM策略。

1. CVE-2024-9486 和 CVE-2024-9594：K8S Image Builder 构建的 VM 镜像使用默认凭证

    - 📅 日期：2024-10-23
    - 🔗 链接：<https://mp.weixin.qq.com/s/PLSHLRYgtW09dp535-5aDA>
    - 💬 简介：文章概述了 Kubernetes 的 Image Builder 项目中的两个安全漏洞 CVE-2024-9486 和 CVE-2024-9594 ，描述了漏洞发现、修复过程及风险评估，提供了检测和缓解措施，并分析了漏洞原因。


1. 使用 gRPC 和 HTTP/2 部署加密货币挖矿机：一种非常规方法

    - 📅 日期：2024-10-22
    - 🔗 链接：<https://www.trendmicro.com/en_us/research/24/j/using-grpc-http-2-for-cryptominer-deployment.html>
    - 💬 简介：在这篇博文中，我们讨论了恶意行为者如何通过 gRPC/h2c 利用 Docker 远程 API 服务器来部署加密矿工 SRBMiner，以便在 Docker 主机上挖掘 XRP。


1. 攻击者利用 perfctl 恶意软件攻击暴露的 Docker 远程 API 服务器

    - 📅 日期：2024-10-21
    - 🔗 链接：<https://www.trendmicro.com/en_us/research/24/j/attackers-target-exposed-docker-remote-api-servers-with-perfctl-.html>
    - 💬 简介： 我们观察到一个未知的威胁行为者滥用暴露的 Docker 远程 API 服务器来部署 perfctl 恶意软件。

1. 如何限制容器的CPU使用量

    - 📅 日期：2024-10-21
    - 🔗 链接：<https://mp.weixin.qq.com/s/fwAxKSddJDmz2AffMUDXTA>
    - 💬 简介：云原生技术的日益普及，也意味着云安全的重要性在不断增加。CNCF 委托了 LF Research 在其社区中进行了一项调查，询问开发者和 IT 领导如何评价他们的组织在云原生安全方面的应对措施。
  调查分析显示，普遍认为应用程序的安全性比两年前有所提升，但仍面临重大挑战和担忧，例如应对新兴威胁、软件的复杂性和漏洞扫描。调查结果揭示了需要改进的领域，以及 CNCF 可以在其中发挥作用的地方。

1. 探索 Google Cloud 默认服务帐户：深入探究和实际应用趋势
    - 📅 日期：2024-10-17
    - 🔗 链接：<https://securitylabs.datadoghq.com/articles/google-cloud-default-service-accounts/>

1. 2024 云原生安全报告

    - 📅 日期：2024-10-17
    - 🔗 链接：<https://mp.weixin.qq.com/s/PeNI2zsq3SOOPOQUgBCFlg>
    - 💬 简介：在Linux系统中，容器化技术依赖于命名空间（Namespace）和控制组（Cgroups）这两个核心概念。Cgroups技术能够帮助我们限制容器所使用的资源，包括CPU、内存、存储和网络等。在本文中，我们将探讨如何利用Cgroups技术，针对Kubernetes平台上的容器，来限制CPU的使用量。

1. 趋势科技 Cloud Edge 漏洞可让攻击者执行任意代码

    - 📅 日期：2024-10-17
    - 🔗 链接：<https://cybersecuritynews.com/trend-micro-code-execution-vulnerability/#google_vignette>
    - 💬 简介：趋势科技发布紧急安全公告，警告其Cloud Edge设备存在严重漏洞（CVE-2024-48904），该漏洞允许远程攻击者无需认证即可执行任意代码。受影响的版本包括5.6SP2和7.0，趋势科技已发布更新版本以修复此安全漏洞，并强烈建议用户立即更新。该漏洞的发现再次强调了及时打补丁和定期进行安全更新的重要性。

1. 朝鲜 ScarCruft 黑客组织利用 Windows 0day漏洞传播 RokRAT 恶意软件

    - 📅 日期：2024-10-17
    - 🔗 链接：<https://cn-sec.com/archives/3280470.html>
    - 💬 简介：RokRAT 还因使用 Dropbox、Google Cloud、pCloud 和 Yandex Cloud 等合法云服务作为其命令和控制（C2）服务器而闻名，从而使其能够融入企业环境中的常规流量。

1. 假的 LockBit，真实的损害：勒索软件样本滥用 Amazon S3 窃取数据

    - 📅 日期：2024-10-16
    - 🔗 链接：<https://www.trendmicro.com/en_us/research/24/j/fake-lockbit-real-damage-ransomware-samples-abuse-aws-s3-to-stea.html>
    - 💬 简介：本文揭露了一个 Golang 勒索软件滥用 Amazon S3 窃取数据，并伪装成 LockBit 来进一步向受害者施压。在这些样本中发现硬编码的 AWS 凭证导致 AWS 账户被暂停。

1. 反思 eBPF 峰会 2024：创新与社区的回顾

    - 📅 日期：2024-10-16
    - 🔗 链接：<https://mp.weixin.qq.com/s/oi9raOUzlmPy4Bew_EkDnQ>
    - 💬 简介：这是一篇关于 eBPF 峰会 2024 的回顾文章。峰会展示了 eBPF 的最新进展和应用案例，突显了这项技术如何改变各行各业。例如，Confluent 在多云环境下的 Cilium 之旅，eBPF 和 Cilium 在优化不同云提供商的网络解决方案中发挥了关键作用；而字节跳动则分享了他们如何在百万台服务器上应用 Netkit，展示了 eBPF 在大规模环境下的网络性能提升。活动中充满了这样的深刻演讲和热情的社区互动，彰显了 eBPF 周围的巨大增长和热情。

1. 万豪因数据泄露面临5200万美元FTC罚款及谴责

    - 📅 日期：2024-10-14
    - 🔗 链接：<https://hackread.com/intel-broker-cisco-data-breach-selling-firms-data/>
    - 💬 简介：万豪和喜达屋因未能实施合理的数据安全措施，导致2014年至2020年间发生三起大型数据泄露事件，影响全球超过3.44亿客户。FTC要求万豪和喜达屋实施全面的安全计划，并同意为美国客户提供删除与电子邮件地址或忠诚度奖励账户号码相关的个人信息的方式。此外，万豪同意支付5200万美元罚款给49个州和哥伦比亚特区，以解决类似的数据安全指控。

1. 实战 | Druid未授权到cf接管云拿下

    - 📅 日期：2024-10-14
    - 🔗 链接：<https://mp.weixin.qq.com/s/wZU3u2jDU_H8kSCMJy6cZA>
    - 💬 简介：这篇文章介绍了一次通过 Druid 未授权漏洞攻击云控制台的实战经历。作者在挖某家 SRC 时，通过域名历史解析找到一个 IP，然后通过各种问题组合接管云控制台。文章详细描述了攻击过程，包括从 Druid 入手、利用 fastjson 漏洞、尝试反序列化攻击、最终通过下载源码获取 AK/SK 并接管控制台等步骤。

1. JFrog Integrates Runtime Security for Enhanced DevSecOps Platform

    - 📅 日期：2024-10-10
    - 🔗 链接：<https://www.infoq.com/news/2024/10/jfrog-devsecops-platform/?utm_campaign=infoq_content&utm_source=infoq&utm_medium=feed&utm_term=DevSecOps-news>
    - 💬 简介：JFrog 宣布将 JFrog Runtime 集成到其安全功能套件中，为其软件供应链平台增加实时漏洞检测功能，旨在帮助开发人员和 DevSecOps 团队更好地保护 Kubernetes 集群和云原生应用程序。

1. K8S节点路由的隐患&异步隧道穿透节点防火墙

    - 📅 日期：2024-10-09
    - 🔗 链接：<https://mp.weixin.qq.com/s/CY_7L4-KswYo-jGVW7UZcA>
    - 💬 简介：文章主要介绍了 K8S 节点路由的隐患，包括实验环境搭建、节点路由原理及可被外部访问风险，还提到提取证书泄露信息的方法。同时介绍了异步网络隧道及相关工具，以及节点路由隐患和网络封装技术对节点防火墙的影响。

1. PoC Exploit Releases for CVE-2023-52447: A Linux Kernel Flaw Enabling Container Escape

    - 📅 日期：2024-10-07
    - 🔗 链接：<https://securityonline.info/poc-exploit-releases-for-cve-2023-52447-a-linux-kernel-flaw-enabling-container-escape/>
    - 💬 简介：CVE-2023-52447 的 PoC 漏洞利用已经发布，影响 Linux 内核版本 v5.8 到 v6.6。该漏洞的 CVSS 评分为 7.8，属于 BPF 子系统中的释放后使用 (use-after-free) 问题。漏洞源于 BPF 程序中管理数组映射指针的引用计数不当，导致在执行耗时操作时可能被其他线程释放和回收内存。这种漏洞可以用于容器逃逸，对依赖容器隔离的系统构成严重安全威胁。

1. Cloudflare Thwarts Largest-Ever 3.8 Tbps DDoS Attack Targeting Global Sectors

    - 📅 日期：2024-10-04
    - 🔗 链接：<https://thehackernews.com/2024/10/cloudflare-thwarts-largest-ever-38-tbps.html>
    - 💬 简介：许多容量不足的云服务以及本地设备的使用不足以防御这种规模的 DDoS 攻击，因为高带宽利用率可能会堵塞互联网链路，并且由于高数据包速率可能会导致串联设备崩溃。

1. Hunting for M365 Password Spraying

    - 📅 日期：2024-10-03
    - 🔗 链接：<https://www.huntress.com/blog/hunting-for-m365-password-spraying>
    - 💬 简介：随着云在我们的计算现实中无处不在，密码喷洒工具开始利用各种云服务来逃避从单个 IP 地址寻找多个身份验证事件的密码喷洒检测。这些较新的密码喷洒策略现在涉及使用云服务，例如 Amazon Web Services (AWS) API 网关或 GitHub 操作，在每次身份验证尝试时轮换 IP 地址。

1. Kicking it Old-School with Time-Based Enumeration in Azure

    - 📅 日期：2024-10-03
    - 🔗 链接：<https://trustedsec.com/blog/kicking-it-old-school-with-time-based-enumeration-in-azure>
    - 💬 简介：在 Azure 中又发现了另一种用户枚举方法。虽然微软可能在一段时间前就禁用了基本身份验证，但我们仍然可以利用它来通过经典技术——基于时间的用户枚举来识别有效用户.

1.  perfctl: A Stealthy Malware Targeting Millions of Linux Servers

    - 📅 日期：2024-10-03
    - 🔗 链接：<https://www.aquasec.com/blog/perfctl-a-stealthy-malware-targeting-millions-of-linux-servers/>
    - 💬 简介：这篇博客介绍了一种名为 “perfctl” 的 Linux 恶意软件，它利用多种技术隐藏自身和维持持久性，攻击目标是 Linux 服务器，已存在 3-4 年，旨在窃取用户信息。该软件利用漏洞或错误配置进行攻击，采用 rootkit、修改系统文件、利用 Unix 套接字和 TOR 进行通信等手段，还会删除自身二进制文件并以服务形式在后台运行。建议采取监控系统行为、分析网络流量、限制文件执行权限等措施进行检测和防范。

1. Western Digital My Cloud Devices Flaw Let Attackers Execute Arbitrary Code

    - 📅 日期：2024-10-01
    - 🔗 链接：<https://cybersecuritynews.com/western-digital-my-cloud-flaw/>
    - 💬 简介：西部数据（Western Digital）的My Cloud设备存在一个严重的安全漏洞，该漏洞编号为CVE-2024-22170，CVSS评分9.2，允许攻击者执行任意代码。该漏洞通过动态DNS客户端被利用，影响多款My Cloud设备。用户需更新至My Cloud OS 5固件版本5.29.102以修复。此事件凸显了云服务设备在安全性方面需加强防护。

## 2024-09

1. Storm-0501 Ransomware Group Attacking Hybrid Cloud Environments

    - 📅 日期：2024-09-27
    - 🔗 链接：<https://cybersecuritynews.com/storm-0501-hybrid-cloud-attacks/>
    - 💬 简介：Storm-0501勒索软件集团针对美国多个部门和关键基础设施的混合云环境发起复杂多阶段攻击。该集团利用Zoho ManageEngine、Citrix NetScaler和ColdFusion 2016的漏洞获取系统访问权限，使用多种工具进行横向移动和凭证访问，并将攻击从本地环境转移到云环境。攻击者通过Rclone工具泄露数据，并部署了包括Hive、BlackCat和LockBit在内的多种勒索软件变种。这起事件凸显了混合云配置中日益增长的安全挑战。

1. 威胁者利用 Docker Swarm 和 Kubernetes 大规模挖掘加密货币（来自Datadog）
    - 📅 日期：2024-09-23
    - 🔗 链接：<https://securitylabs.datadoghq.com/articles/threat-actors-leveraging-docker-swarm-kubernetes-mine-cryptocurrency/>

1. CloudImposer: Executing Code on Millions of Google Servers with a Single Malicious Package

    - 📅 日期：2024-09-16
    - 🔗 链接：<https://www.tenable.com/blog/cloudimposer-executing-code-on-millions-of-google-servers-with-a-single-malicious-package>
    - 💬 简介：文章介绍了名为“CloudImposer”的恶意软件，它能够通过单个恶意包在数百万个谷歌服务器上执行代码。研究表明，该恶意软件利用了云计算环境中的安全漏洞，攻击者可以轻易部署并控制大规模的计算资源。文章强调了云安全的重要性，以及企业需要采取措施以防止类似攻击的发生。

1. Threat Actors leverage Docker Swarm and Kubernetes to mine cryptocurrency at scale

    - 📅 日期：2024-09-23
    - 🔗 链接：<https://securitylabs.datadoghq.com/articles/threat-actors-leveraging-docker-swarm-kubernetes-mine-cryptocurrency/>
    - 💬 简介：来自DataDog的文章探讨了威胁行为者如何利用Docker Swarm和Kubernetes等容器编排工具，大规模挖掘加密货币。攻击者通过滥用这些容器平台的计算资源，创建僵尸网络进行加密货币挖矿，并介绍了这些攻击的技术细节，以及如何识别和防御此类威胁。

1. Tracking cloud-fluent threat actors - Part one: Atomic cloud IOCs

    - 📅 日期：2024-09-23
    - 🔗 链接：<https://www.wiz.io/blog/mastering-cloud-specific-indicators-of-compromise-iocs>
    - 💬 简介：来自Wiz博客的文章，讨论了如何掌握应用云环境中的特定入侵指标（IOCs），以提升威胁检测能力。云计算环境与传统IT环境有显著不同，因此需要不同的工具和方法来识别和应对攻击。文章还介绍了几种常见的云特定入侵指标，帮助安全团队及时发现潜在威胁并采取防御措施。作者Merav Bar和Amitai Cohen的"Tracking cloud-fluent threat actors"新博客系列将涵盖跟踪和防御恶意活动和威胁的策略，同时他们在[wiz-research-iocs](https://github.com/wiz-sec-public/wiz-research-iocs)这个Github仓库中维护公开的云环境IOCs。

1. The Russian APT Tool Matrix（俄罗斯APT使用的工具矩阵）

    - 📅 日期：2024-09-22
    - 🔗 链接：<https://blog.bushidotoken.net/2024/09/the-russian-apt-tool-matrix.html>
    - 💬 简介：这篇文章讨论了俄罗斯高级持续性威胁（APT）组织使用的工具矩阵。文章分析了这些APT组常用的恶意软件和攻击工具，并提供了关于其技术和战术的详细信息。
  
1. Vulnerabilities in Open Source C2 Frameworks(开源C2框架中的漏洞)

    - 📅 日期：2024-09-18
    - 🔗 链接：<https://blog.includesecurity.com/2024/09/vulnerabilities-in-open-source-c2-frameworks/>
    - 简介：这篇文章探讨了开源C2框架中的安全漏洞。分析了这些框架在恶意攻击活动中的使用，以及其设计和实现中的漏洞可能导致的安全风险。文章通过研究不同C2框架的安全缺陷，提醒安全研究人员和开发者关注这些工具中的潜在问题，强调修复和改善这些框架的重要性，以减少攻击面和提升整体安全性。包括Sliver、Havoc、Ninja等开源C2框架的安全漏洞。

1. The Cloud is Darker and More Full of Terrors

    - 📅 日期：2024-09-13
    - 🔗 链接：<https://www.chrisfarris.com/post/sect2024/>
    - 💬 简介：Chris Farris在2024年Sec-T会议上的演讲总结，主题是公共云服务的安全问题。当前IT行业在使用公共云服务时存在根本性的不安全问题。作者通过多个案例分析，强调了云服务提供商和用户在云安全方面的责任和挑战。

1. 云安全的未来：行为检测和降低噪音

    - 📅 日期：2024-9-12
    - 🔗 链接：<https://rad.security/blog/future-cloud-security-behavioral-detection-noise>
    - 💬 简介：这篇文章探讨了云安全的未来，特别是如何通过行为检测技术来减少噪音，提高安全威胁的检测效率。传统基于签名的方法（如依赖预定义的威胁模式）在云原生环境中容易因高噪音率和复杂的威胁态势而失效。而行为检测通过分析用户和系统的正常行为基线，能够更好地识别异常活动，特别是针对未知或0 day攻击。

1. Noisy Neighbor Detection with eBPF——基于eBPF的噪声邻居检测

    - 📅 日期：2024-09-11
    - 🔗 链接：<https://netflixtechblog.com/noisy-neighbor-detection-with-ebpf-64b1f4b3bbdd>
    - 💬 简介：这篇文章讨论了Netflix使用eBPF来检测云环境中的"Noisy Neighbor"问题。这种问题发生在共享资源的多租户环境中，当某个租户占用过多资源时，可能会影响到其他租户的性能。eBPF 通过高效、低开销地监控系统行为和网络流量，帮助 Netflix 识别并缓解这种资源争夺现象，从而提高系统性能和稳定性。

1. Ransomware in the Cloud: Scattered Spider Targeting Insurance and Financial Industries

    - 📅 日期：2024-09-10
    - 🔗 链接：<https://blog.eclecticiq.com/ransomware-in-the-cloud-scattered-spider-targeting-insurance-and-financial-industries>
    - 💬 简介：这篇文章讨论了名为 Scattered Spider 的勒索软件组织，如何专门针对云环境中的金融和保险行业进行攻击。攻击者主要使用社工手段获取员工账户的访问权限，然后利用合法工具在网络中横向移动，执行勒索软件攻击。文章还强调了组织在防范此类威胁时，应加强对云基础设施的保护，并提高员工的安全意识。

1. Kubernetes CRD generation pitfalls

    - 📅 日期：2024-09-10
    - 🔗 链接：<https://ahmet.im/blog/crd-generation-pitfalls/>
    - 💬 简介：这篇文章讨论了使用 controller-gen 生成 Kubernetes 自定义资源定义（CRD）时常见的陷阱和注意事项。文章建议开发者严格验证字段，确保标记字段为必需或可选，避免错误的零值处理，解决嵌套字段的默认值和验证问题。它还指出，某些注释标记不会被自动验证，导致潜在问题。文章建议使用更好的静态分析工具来检测这些问题，并呼吁开发者贡献改进。

1. Cobalt Strike - CDN / Reverse Proxy Setup

    - 📅 日期：2024-09-04
    - 🔗 链接：<https://redops.at/en/blog/cobalt-strike-cdn-reverse-proxy-setup>
    - 💬 简介：探讨如何在 Microsoft Azure 下的内容交付网络 (CDN) 上下文中使用高信誉域以及 C2 域和 Nginx 作为我们红队基础设施的反向代理。接下来，我将概述所需的资源以及我们将详细介绍的主要主题。

1. Defining Reachability - is it just hype?

    - 📅 日期：2024-09-04
    - 🔗 链接：<https://pulse.latio.tech/p/reachability-matters-13>
    - 💬 简介：这篇文章讨论了漏洞管理中的误报问题以及可达性（reachability）在解决该问题中的作用。作者认为，漏洞扫描的目标是检测可利用的软件，而不是简单地发现漏洞。可达性可以帮助确定漏洞是否可利用，从而减少误报。文章还比较了静态可达性和运行时可达性的优缺点，并探讨了未来的发展方向。


## 2024-08

1. How Container Networking Works: a Docker Bridge Network From Scratch：

    - 🔗 链接：<https://labs.iximiuz.com/tutorials/container-networking-from-scratch>
    - 💬 简介：这篇是关于如何从头开始构建容器网络的详细教程，特别是单主机容器网络。作者通过逐步指导读者创建和配置网络环境，解释了容器网络的工作原理。

1. SeamlessPass: Leveraging Kerberos Tickets to Access the Cloud

    - 🔗 链接：[SeamlessPass: Leveraging Kerberos Tickets to Access the Cloud](https://malcrove.com/seamlesspass-leveraging-kerberos-tickets-to-access-the-cloud/)
    - 💬 简介：介绍了一个名为SeamlessPass的工具，它利用微软的无缝单点登录（Seamless SSO）功能，通过使用本地Active Directory Kerberos票据来获取Microsoft 365服务的访问令牌，适用于红队场景。

1. ECS任务元数据证书获取的新视角

    - 🔗 链接：[A Fresh Perspective on Exfiltrating ECS Task Metadata Credentials](https://saransh-rana.gitbook.io/aboutme/a-fresh-perspective-on-exfiltrating-ecs-task-metadata-credentials)
    - 💬 简介：用非常简单的术语列出了攻击者登录到运行ECS任务的ec2主机之后的时间内，如果没有及时发现攻击者后渗透会很容易和自动化。Saransh在文章的最后给出了一个脚本，用于收集和提取任务凭据，这对蓝队和红队成员都很有用。

1. AWS安全检测工程系列

    - 🔗 链接：[My Methodology to AWS Detection Engineering (Part 1: Object Selection)](https://chesterlebron.blogspot.com/2024/08/my-methodology-to-aws-detection-engineering-part-1.html)
    - 💬 简介：Chester Le Bron介绍了一些列AWS攻击检测的方法，值得参考。

1. CVE-2024-43044的分析：Jenkins通过agent文件读取到RCE

    - 🔗 链接：[Analysis of CVE-2024-43044 — From file read to RCE in Jenkins through agents](https://blog.convisoappsec.com/en/analysis-of-cve-2024-43044/)
    - 💬 简介：2024年8月7日，Jenkins 官方披露 CVE-2024-43044 Jenkins agent connections 文件读取漏洞。Jenkins 受影响版本中，攻击者在获取agent权限后，可利用agent功能与Jenkins交互，从而读取 Jenkins 控制器文件系统上的任意文件，并结合其他功能等可能导致任意代码执行。这篇博客分析了详细的漏洞利用过程。

1. Linux持久化攻击及检测手段

    - 🔗 链接：[Linux Detection Engineering -  A primer on persistence mechanisms](https://www.elastic.co/security-labs/primer-on-persistence-mechanisms)
    - 💬 简介：来自elastic security labs博客，这篇文章主要介绍了攻击者如何在Linux系统上建立持久化攻击以及如何有效检测这些攻击手段。文章前传：[使用Auditd进行Linux检测](https://www.elastic.co/security-labs/linux-detection-engineering-with-auditd)

1. ShinyHunters勒索软件的探究（针对AWS进行攻击）

    - 🔗 链接：[Bling Libra’s Tactical Evolution: The Threat Actor Group Behind ShinyHunters Ransomware](https://unit42.paloaltonetworks.com/shinyhunters-ransomware-extortion/)
    - 💬 简介：这篇文章探讨了一个名为 ShinyHunters 的黑客组织，他们通过勒索软件和数据泄露来实施勒索。该组织以入侵多个公司系统、窃取敏感数据为目标，然后威胁公开这些数据以勒索赎金。文章分析了 ShinyHunters 的攻击策略和行为模式，并提出了一些安全建议，帮助企业防范此类攻击，保护自身数据和系统安全。

1. 深入探究Kubernetes威胁模型

    - 🔗 链接：[A Deep Dive Into Kubernetes Threat Modeling](https://www.trendmicro.com/vinfo/us/security/news/security-technology/a-deep-dive-into-kubernetes-threat-modeling)
    - 💬 简介：这篇文章探讨了在Kubernetes环境中正确执行威胁建模所需的方面和注意事项。分析了与Kubernetes环境相关的安全风险，介绍了各种攻击面，例如API服务器、节点、控制平面组件等，并讨论了潜在的攻击手法和威胁场景。此外，还提供了一些最佳实践和防护策略，以帮助用户更好地保护Kubernetes集群。

1. Kanister默认Kanister-Operator权限提升漏洞(CVE-2024-43403)

Kanister Vulnerability Opens Door to Cluster-Level Privilege Escalation(CVE-2024-43403)

    - 🔗 链接：<https://cvefeed.io/vuln/detail/CVE-2024-43403>
    - 🔗 相关博客：<https://securityonline.info/cve-2024-43403-kanister-vulnerability-opens-door-to-cluster-level-privilege-escalation/>
    - 💬 简介：Kanister工具存在严重漏洞CVE-2024-43403，攻击者可利用该漏洞获取对Kubernetes集群的完全控制。Kanister是一个数据保护工作流管理工具。Kanister有一个名为default-kanister-operator的部署，它与一个名为edit的ClusterRole通过ClusterRoleBinding绑定。该“edit”ClusterRole是Kubernetes默认创建的ClusterRole之一，它具有对daemonset资源的创建/修补/更新操作权限，对serviceaccount/token资源的创建权限以及对serviceaccounts资源的模拟权限。恶意用户可以利用访问拥有此组件的工作节点来进行集群级别的权限提升。目前尚未记录受影响的产品的具体版本，需要进一步跟踪。

1. K8s RBAC最佳安全实践

    - 🔗 链接：[K8s RBAC最佳安全实践](https://mp.weixin.qq.com/s/XuNx9WNKmCJEo_FS8lfwYw)
    - 💬 简介："K8s RBAC最佳安全实践"是来自字节跳动技术团队的文章。文章首先介绍了Kubernetes的认证与授权体系以及RBAC授权原理,然后通过实际案例展示RBAC管理不当可能导致的安全风险，并分享RBAC安全研发与运维的最佳实践，以及在字节跳动内部的安全防护和治理经验。

1. K8s安全基础系列文章（DataDog）

    - 🔗 链接： [Kubernetes security fundamentals: Authorization](https://securitylabs.datadoghq.com/articles/kubernetes-security-fundamentals-part-4/)
    - 🔗 作者视频：<https://www.youtube.com/watch?v=2setap7IgNc>
    - 💬 简介：Kubernetes安全基础——授权。来自Rory McCune发布在datadog的文章，这是他"Kubernetes安全基础"系列的第四篇文章。前三篇分别是Kubernetes安全基础简介、Kubernetes API安全、Kubernetes认证；可以从第一篇开始阅读学习。在youtube上也有他的分享。更新第5篇：[Kubernetes安全基础——准入控制](https://securitylabs.datadoghq.com/articles/kubernetes-security-fundamentals-part-5/)

1. 容器安全的系列文章（DataDog）

    - 🔗 链接：[container security fundamentals](https://securitylabs.datadoghq.com/articles/?s=container%20security%20fundamentals)
    - 💬 简介：同样是来自Rory McCune发布在datadog的系列文章，“容器安全基础”系列共有6篇文章。

1. 针对云环境的大规模勒索攻击
    
    - 📅 日期：2024-08-15
    - 🔗 链接：[Leaked Environment Variables Allow Large-Scale Extortion Operation of Cloud Environments](https://unit42.paloaltonetworks.com/large-scale-cloud-extortion-operation/)
    - 💬 简介：这篇文章由Palo Alto Networks的Unit 42研究团队撰写，揭露了一个针对云环境的大规模勒索攻击。攻击者利用泄露的环境变量来访问敏感信息，并要求受害者支付赎金以避免数据泄露或服务中断。文章强调了安全配置云环境的重要性，建议企业定期审查和监控云基础设施的安全措施，包括访问控制和日志记录，以预防此类勒索攻击。文章还指出云安全漏洞是网络犯罪分子的一个主要攻击目标。

1. 深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线

    - 📅 日期：2024-08-04
    - 🔗 链接：[深入探究 K8S Pod 安全策略与准入控制器：构建坚不可摧的容器安全防线（来自"WAKE UP技术"公众号）](https://mp.weixin.qq.com/s/HHGDJ_xtyNTcw0xTrWP7AA)

1. ArtiPACKED：GitHub Actions Artifacts

    - 📅 日期：2024-08-13
    - 🔗 链接：[ArtiPACKED：GitHub Actions Artifacts](https://unit42.paloaltonetworks.com/github-repo-artifacts-leak-tokens/)
    - 💬 简介：这篇博客分析了在GitHub Actions中由于竞态条件导致的漏洞，该漏洞可以让攻击者通过上传恶意工件来窃取敏感信息，比如访问令牌(如GitHub令牌和第三方云服务凭据)。这种攻击方式被称为“ArtiPACKED”。文章详细描述了这一攻击的工作原理、潜在的危害以及如何防范此类攻击。

1. Grand Theft Actions: Abusing Self-Hosted GitHub Runners at Scale

    - 📅 日期：2024-08
    - 🔗 链接：<https://github.com/AdnaneKhan/ConferenceTalks/blob/main/DEFCON32_GrandTheftActions.pdf>
    - 🔗 链接：Gato-X：<https://github.com/AdnaneKhan/Gato-X>
    - 💬 简介：AdnanKhan和John Stawinski在DEF CON演讲中分享了他们一直在做的GitHub Action研究，他们已经发现了许多互联网规模的供应链安全漏洞，同时发布了Gato-X工具，以帮助其他安全研究人员大规模发现这些类型的漏洞。

1. CVE-2024-7646：Ingress-nginx注释验证绕过

    - 📅 日期：2024-08-16
    - 🔗 链接1：[K8s issue](https://github.com/kubernetes/kubernetes/issues/126744)
    - 🔗 链接2：[CVE-2024-7646: Ingress-NGINX Annotation Validation Bypass – A Deep Dive](https://securityboulevard.com/2024/08/cve-2024-7646-ingress-nginx-annotation-validation-bypass-a-deep-dive/)
    - 🔗 链接3：[CVE-2024-7646：Ingress-nginx注释验证绕过【高危】](https://mp.weixin.qq.com/s/heUTzB0clK0TP0bDGEunGw)

## 2024-07

1. 利用gitRepo volumes创建权限如何拿下K8s节点root权限

    - 📅 日期：2024-07
    - 🔗 链接1：[Sneaky write hook: git clone to root on k8s node](https://irsl.medium.com/sneaky-write-hook-git-clone-to-root-on-k8s-node-e38236205d54)
    - 🔗 链接2：[Fun With GitRepo Volumes](https://raesene.github.io/blog/2024/07/10/Fun-With-GitRepo-Volumes/)
    - 💬 简介：这两篇博客文章讨论了一个Kubernetes中未修补的安全问题，允许任何有权限创建gitRepo卷的用户以root用户身份在底层主机上执行代码。

1. Kubernetes 历史：它如何征服云原生编排

    - 📅 日期：2024-07-25
    - 🔗 链接：[Kubernetes History: How It Conquered Cloud Native Orchestration](https://www.aquasec.com/blog/kubernetes-history-how-it-conquered-cloud-native-orchestration/)


1. 过时的安全：为什么我们使用隔离虚拟机

    - 📅 日期：2024-07-25
    - 🔗 链接：[Unfashionably secure: why we use isolated VMs](https://blog.thinkst.com/2024/07/unfashionably-secure-why-we-use-isolated-vms.html)


1. 揭示AWS会话令牌的内部结构

    - 📅 日期：2024-07-25
    - 🔗 链接：[Revealing the Inner Structure of AWS Session Tokens](https://medium.com/@TalBeerySec/revealing-the-inner-structure-of-aws-session-tokens-a6c76469cba7)

1. 云原生应用保护平台市场指南
    - 📅 日期：2024-07-22
    - 🔗 链接：[Market Guide for Cloud-Native Application Protection Platforms](https://www.gartner.com/doc/reprints?id=1-2I6YT1ZQ&ct=240726&st=sb)


1. 一份循序渐进的AWS渗透测试指南

    - 📅 日期：2024-07-22
    - 🔗 链接：[An Opinionated Ramp Up Guide to AWS Pentesting](https://awssecuritydigest.com/articles/opinionated-ramp-up-guide-to-aws-pentesting)
    - 💬 简介：Lizzie Moratti提供了一份深入的AWS渗透测试指南，利用了[pwnedlabs.io](https://pwnedlabs.io/)靶场、Rich Mogull的[Cloud Security Lab a Week](https://slaw.securosis.com/)(每周云安全实验室)以及Scott Piper的[AWS Security Maturity Roadmap](https://summitroute.com/downloads/aws_security_maturity_roadmap-Summit_Route.pdf)（AWS安全成熟度路线图）等资源。Lizzie 提供了一些关于云渗透测试的热门观点，以及五阶段学习方法。


1. 容器逃逸：云环境中的逃逸技术(来自Palo Alto博客)

    - 📅 日期：2024-07-18
    - 💬 标题：Container Breakouts: Escape Techniques in Cloud Environments
    - 🔗 链接：[Container Breakouts: Escape Techniques in Cloud Environments](https://unit42.paloaltonetworks.com/container-escape-techniques/)

1. 启用安全防护：使用 CDK for Terraform 实现基础设施即代码

    - 📅 日期：2024-07-15
    - 💬 标题：Enabling Security Guardrails: Infra as Code with CDK for Terraform
    - 🔗 链接：[Enabling Security Guardrails: Infra as Code with CDK for Terraform](https://engineering.ziphq.com/enabling-security-guardrails-infra-as-code-with-cdk-for-terraform/)

1. Binary secret scanning helped us prevent (what might have been) the worst supply chain attack you can imagine

    - 🔗 链接：<https://jfrog.com/blog/leaked-pypi-secret-token-revealed-in-binary-preventing-suppy-chain-attack/>
    - 💬 简介：JFrog安全研究团队通过二进制扫描发现并报告了一个泄露的访问令牌，该令牌具有管理员权限，可以访问Python、PyPI和Python软件基金会的GitHub仓库。这个令牌被泄露在Docker Hub托管的一个公共Docker容器中。JFrog的报告给出了对二进制扫描和Secret检测的一些建议。

1. 启动您的Kubernetes安全

    - 📅 日期：2024-07-02
    - 🔗 链接：[Kickstart Your Kubernetes Security](https://cloudnativenow.com/social-facebook/kickstart-your-kubernetes-security/)

## 2024-06

1. Reverse Engineering eBPF Programs: A Deep Dive

    - 📅 日期：2024-06-25
    - 🔗 链接：[Reverse engineering eBPF programs](https://www.armosec.io/blog/ebpf-reverse-engineering-programs/)
    - 💬 简介：介绍了eBPF技术在增强Kubernetes安全性方面的重要性，深入剖析了eBPF的内部工作机制和用法

1. K8s日志指南

    - 📅 日期：2024-06-01  
    - 🔗 链接：[A Guide To Kubernetes Logs That Isn't A Vendor Pitch](https://grahamhelton.com/blog/k8slogs/)

1. 天翼云对象存储ZOS攻防

    - 📅 日期：2024-06-26
    - 🔗 链接：[天翼云对象存储ZOS攻防](https://zone.huoxian.cn/d/2916-zos)

1. 攻击者针对暴露的Docker API利用新技巧

    - 📅 日期：2024-06-13
    - 🔗 链接：[Attackers deploying new tactics in campaign targeting exposed Docker APIs](https://securitylabs.datadoghq.com/articles/attackers-deploying-new-tactics-in-campaign-targeting-exposed-docker-apis/)

## 2024-05

1. Docker 逃逸中被忽略的 pid namespace

    - 📅 日期：2024-05-25
    - 🔗 链接：[Docker 逃逸中被忽略的 pid namespace](https://tiangonglab.github.io/blog/tiangongarticle030/)

1. 实战-关于KEY泄露API接口利用

    - 📅 日期：2024-05-11
    - 🔗 链接：[实战-关于KEY泄露API接口利用](https://zone.huoxian.cn/d/2909-keyapi)

## 2024-04

1. 腾讯云对象存储COS（Cloud Object Storage）攻防

    - 📅 日期：2024-04-15
    - 🔗 链接：[腾讯云对象存储COS（Cloud Object Storage）攻防](https://zone.huoxian.cn/d/2903-coscloud-object-storage)

1. 京东云OSS攻防

    - 📅 日期：2024-04-08
    - 🔗 链接：[京东云OSS攻防](https://zone.huoxian.cn/d/2901-oss)

## 2024-02

1. TeamTNT攻击组织分析

    - 📅 日期：2024-02-01
    - 🔗 链接：[An analysis of a TeamTNT doppelgänger](https://securitylabs.datadoghq.com/articles/analysis-of-teamtnt-doppelganger/)

## 2024-01

1. Buildkit 构建时容器清理任意删除（CVE-2024-23652）
    - 📅 日期：2024-01-31
    - 🔗 链接：[Buildkit build-time container teardown arbitrary delete (CVE-2024-23652)](https://snyk.io/blog/cve-2024-23652-buildkit-build-time-container-teardown-arbitrary-delete/)
    - 💬 简介：Snyk 发现 Docker Buildkit <=v0.12.4 的所有版本中均存在漏洞，Docker 引擎正是使用这个漏洞。利用此漏洞，在使用恶意 Dockerfile 或上游镜像（即使用FROM）构建镜像时，底层主机操作系统中可能会出现任意文件和目录删除。此漏洞已分配 CVE-2024-23652。

## 2023-12

1. 增强供应链安全性：实施Sigstore以实现自动化容器镜像签名

    - 📅 日期：2023-12-18
    - 🔗 链接：[Scaling Up Supply Chain Security: Implementing Sigstore for Seamless Container Image Signing](https://www.yahooinc.com/paranoids/scaling-up-supply-chain-security-implementing-sigstore-for-seamless-container-image-signing)
    - 💬 简介：来自Yahoo博客，介绍了如何在企业内部使用Sigstore开源工具对容器镜像进行自动化签名验证。

1. 容器镜像加固：Docker 的最佳实践和案例

    - 📅 日期：2023-12-20
    - 🔗 链接：[Hardening Container Images: Best Practices and Examples for Docker](https://medium.com/@SecurityArchitect/hardening-container-images-best-practices-and-examples-for-docker-e941263cab13)


## 2023-11

1. 针对新手的Rego介绍

    - 📅 日期：2023-11-03
    - 🔗 链接：[Rego for beginners: Introduction to Rego](https://medium.com/@snyksec/rego-for-beginners-introduction-to-rego-0d293d52a654)

## 2023-10

1. MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1

    - 📅 日期：2023-10-31～至今
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v14.1-v15.1](https://attack.mitre.org/matrices/enterprise/containers/)

## 2023-04

1. MITRE 的 Container ATT&CK 攻防矩阵 v13.1

    - 📅 日期：2023-04-25
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v13.1](https://attack.mitre.org/versions/v13/matrices/enterprise/containers/)

1. 容器镜像的妙用——绕过漏洞扫描程序

    - 📅 日期：2023-04-22
    - 🔗 链接：[Fun with container images - Bypassing vulnerability scanners](https://raesene.github.io/blog/2023/04/22/Fun-with-container-images-Bypassing-vulnerability-scanners/)

## 2022-09

1. NSA 需要强大的 Kubernetes 身份验证和授权

    - 📅 日期：2022-09-12
    - 🔗 链接：[NSA Wants Strong Kubernetes Authentication and Authorization](https://cloudnativenow.com/features/nsa-wants-strong-kubernetes-authentication-and-authorization/)

## 2022-10

1. MITRE 的 Container ATT&CK 攻防矩阵 v12.1

    - 📅 日期：2022-10-25
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v12.1](https://attack.mitre.org/versions/v12/matrices/enterprise/containers/)

## 2022-07

1. 攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解

    - 📅 日期：2022-10-25
    - 🔗 链接：[攻击者能够迅速利用著名的零日漏洞：2022年Unit 42事件响应报告见解](https://unit42.paloaltonetworks.com/incident-response-report/)

## 2022-06

1. Docker 安全 – 构建时安全最佳实践（针对云安全工程师和开发人员）

    - 📅 日期：2022-06-01
    - 🔗 链接：[Docker Security – Build Time Security Best Practices (For Cloud Security Engineers and Developers)](https://payatu.com/blog/docker-security/)


## 2022-04

1. MITRE 的 Container ATT&CK 攻防矩阵 v11.3

    - 📅 日期：2022-04-25
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v11.3](https://attack.mitre.org/versions/v11/matrices/enterprise/containers/)

## 2022-03

1. Kubernetes 数据保护工作流程白皮书

    - 📅 日期：2022-03-17
    - 🔗 链接：[Data Protection Workflows White Paper](https://github.com/kubernetes/community/blob/master/wg-data-protection/data-protection-workflows-white-paper.md)
    - 💬 简介：本文档回答了以下问题：为什么我们需要在 Kubernetes 中进行数据保护、Kubernetes 目前可以提供哪些功能、Kubernetes 中缺少哪些支持数据保护的功能？我们将描述如何识别数据保护资源，什么是卷备份和恢复工作流程，以及什么是应用程序快照、备份和恢复工作流程。

## 2021-11

1. 云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考

    - 📅 日期：2021-11-01
    - 🔗 链接：[云原生安全：基于容器ATT&CK矩阵模拟攻防对抗的思考](https://www.freebuf.com/articles/security-management/303010.html)

## 2021-10

1. MITRE 的 Container ATT&CK 攻防矩阵 v10.1

    - 📅 日期：2021-10-21
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v10.1](https://attack.mitre.org/versions/v10/matrices/enterprise/containers/)

## 2021-09

1. 腾讯云鼎实验室的云安全攻防矩阵

    - 📅 日期：2021-09-26
    - 🔗 链接：[云安全攻防矩阵](https://cloudsec.tencent.com/home/)

## 2021-08

1. 青藤的 Kubernetes ATT&CK 攻防矩阵

    - 📅 日期：2021-08-25
    - 🔗 链接：[最佳实践：发布国内首个K8S ATT&CK攻防矩阵](https://mp.weixin.qq.com/s/-FTJRl1ZK2Etgq7KO17r7w)

## 2021-06

1. 如何设定切实可行的时间框架来修复安全漏洞

    - 📅 日期：2021-06-23
    - 🔗 链接：[How to Set Practical Time Frames to Remedy Security Vulnerabilities](https://www.gartner.com/smarterwithgartner/how-to-set-practical-time-frames-to-remedy-security-vulnerabilities)

## 2021-05

1. Metarget：云原生攻防靶场开源啦！

    - 📅 日期：2021-05-10
    - 🔗 链接：[Metarget：云原生攻防靶场开源啦！](https://mp.weixin.qq.com/s?__biz=MzIyODYzNTU2OA==&mid=2247489415&idx=1&sn=4aea7b7ecff51710c79037ab07a889bc)

## 2021-04

1. MITRE 的 Container ATT&CK 攻防矩阵 v9.0

    - 📅 日期：2021-04-29
    - 🔗 链接：[MITRE 的 Container ATT&CK 攻防矩阵 v9.0](https://attack.mitre.org/versions/v9/matrices/enterprise/containers/)

## 2021-03

1. 微软的 Kubernetes 威胁矩阵（二）

    - 📅 日期：2021-03-23
    - 🔗 链接：[Secure containerized environments with updated threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2021/03/23/secure-containerized-environments-with-updated-threat-matrix-for-kubernetes/)

1. 红蓝对抗中的云原生漏洞挖掘及利用实录

    - 📅 日期：2021-03-02
    - 🔗 链接：[红蓝对抗中的云原生漏洞挖掘及利用实录](https://mp.weixin.qq.com/s/Aq8RrH34PTkmF8lKzdY38g)

## 2021-01

1. 伸手党的容器镜像加固流程

    - 📅 日期：2021-01-06
    - 🔗 链接：[伸手党的容器镜像加固流程](https://blog.fleeto.us/post/harden-docker-image-flow-chart/)

## 2020-10

1. 微软的 Kubernetes 威胁矩阵缺失的内容

    - 📅 日期：2020-10-26
    - 🔗 链接：[Microsoft's Kubernetes Threat Matrix: Here's What's Missing](https://www.darkreading.com/threat-intelligence/microsoft-s-kubernetes-threat-matrix-here-s-what-s-missing)

## 2020-06

1. 云原生环境渗透相关工具考察

    - 📅 日期：2020-06-20
    - 🔗 链接：[云原生环境渗透相关工具考察](https://blog.wohin.me/posts/cloud-native-pentest-tools/)

1. 阿里云的云上容器 ATT&CK 攻防矩阵

    - 📅 日期：2020-06-18
    - 🔗 链接：[国内首个云上容器ATT&CK攻防矩阵发布，阿里云助力企业容器化安全落地](https://developer.aliyun.com/article/765449)

## 2020-04

1. 微软的 Kubernetes 威胁矩阵（一）

    - 📅 日期：2020-04-02
    - 🔗 链接：[Threat matrix for Kubernetes](https://www.microsoft.com/en-us/security/blog/2020/04/02/attack-matrix-kubernetes/)

## 2020-02

1. 深入研究现实世界的Kubernetes威胁

    - 📅 日期：2020-02-12
    - 🔗 链接：[Deep Dive into Real-World Kubernetes Threats](https://research.nccgroup.com/2020/02/12/command-and-kubectl-talk-follow-up/)

## 2019-05

1. 容器安全：检查容器环境的潜在威胁

    - 📅 日期：2019-05-14
    - 🔗 链接：[Container Security: Examining Potential Threats to the Container Environment](https://www.trendmicro.com/vinfo/us/security/news/security-technology/container-security-examining-potential-threats-to-the-container-environment)

1. Falco 提供的针对容器运行时安全的 MITRE ATT&CK 框架

    - 📅 日期：2019-05-10
    - 🔗 链接：[MITRE ATT&CK framework for container runtime security with Falco](https://sysdig.com/blog/mitre-attck-framework-for-container-runtime-security-with-sysdig-falco/)
