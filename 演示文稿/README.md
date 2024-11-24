# 演示文稿

## 2024-11

1. 基于 KBOM 保障 Kubernetes 组件安全

    - 📅 日期：2024-11-09
    - 📑 文件：[基于 KBOM 保障 Kubernetes 组件安全](./基于%20KBOM%20保障%20Kubernetes%20组件安全.pdf)
    - 💬 简介：当前，Kubernetes的安全防护主要依赖于配置扫描和漏洞扫描，而Kubernetes组件安全则显得相对滞后。2024年2月，Leaky Vessels漏洞的爆发引发了全球范围内的容器逃逸事件，使得Kubernetes组件安全问题备受关注。同年，我国公安三所发布的软件供应链安全动态报告，进一步推动了我国供应链安全领域的进步。在这一背景下，本次议题将深入探讨如何为Kubernetes集群自动生成Kubernetes软件物料清单（KBOM），并基于KBOM构建一个简易的Kubernetes组件安全扫描器，以保障Kubernetes组件安全。

## 2024-10

1. 通过影子资源破坏 AWS

    - 📅 日期：2024-10-17
    - 📑 文件：[DEF CON 32 - Breaching AWS Through Shadow Resources](./US24-Kadkoda-Breaching-AWS-Accounts-Through-Shadow-Resources-Wednesday.pdf)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=m9QVfYVJ7R8>
    - 💬 简介：云看起来很复杂，但真正让事情变得复杂的是幕后发生的事情。一些服务利用其他服务作为其逻辑/操作的一部分的资源。有趣的是，事实证明，如果操作不安全，这可能会导致灾难性的结果。
本次演讲将介绍我们在 AWS 中发现的六个关键漏洞，以及它们背后的故事和方法。 AWS 立即承认并修复了这些漏洞，这些漏洞可能允许外部攻击者破坏几乎所有 AWS 账户。这些漏洞的范围从可能导致帐户完全被接管的远程代码执行到信息泄露、可能暴露敏感数据或导致拒绝服务。本次会议将分享我们的发现故事，我们如何能够识别它们之间的共性，以及我们如何开发一种方法来发现更多漏洞并通过使用导致权限升级的常见技术来增强影响。然后，我们将详细介绍映射服务外部资源的方法，并发布我们的开源工具来研究服务内部 API 调用。我们还将提出一种方法来检查帐户过去是否容易受到此向量的影响。
我们将总结本次研究中吸取的经验教训以及我们未来的研究方向。我们将重点介绍云研究人员在寻找云漏洞时需要探索的新领域，并重点介绍开发人员在复杂环境中使用的最佳实践。

## 2024-09

1. 金融科技中的容器安全：基于 eBPF 和 WASM 的漏洞降噪技术

    - 📑 文件：[金融科技中的容器安全：基于 eBPF 和 WASM 的漏洞降噪技术](./金融科技中的容器安全：基于%20eBPF%20和%20WASM%20的漏洞降噪技术.pdf)
    - 💬 简介：本次演讲将展示如何通过eBPF和WASM技术优化金融科技领域的容器安全管理。通过镜像漏洞降噪技术和漏洞优先级技术，金融机构能够更高效地应对容器镜像中的漏洞，减少无效的修复工作，专注于真正影响业务安全的关键问题，推动新技术在金融行业中的安全应用。

1. How to 10X Your Cloud Security (Without the Series D)

    - 🔗 链接：<https://speakerdeck.com/ramimac/how-to-10x-your-cloud-security-without-the-series-d>
    - 💬 简介：Rami McCarthy 在fwd cloudsec EU会议上的精彩演讲，他对构建安全程序、不变量、漏洞和资产管理、身份和访问管理、检测工程、部署等方面的有用资源和想法。作者总结提炼了将云安全项目规模化的可行指导，这些指导来自众多的演讲和博客文章。将快速浏览云安全是什么，如何更有效地进行云安全工作，以及未来可能的发展方向。演讲结束也会获得实用的要点，以及一份详尽的参考文献。

## 2024-08

1. 加强容器安全性：共同的旅程｜KC24

    - 📅 日期：2024-08-21~2024-08-23
    - 🔗 链接：<https://mp.weixin.qq.com/s/arrxfJOnctaGb4eoWFR9pQ>
    - 💬 简介：Strengthening Container Security: A Collaborative Journey | 加强容器安全性：共同的旅程 - Yi Zha, Microsoft & Beltran Rueda Borrego, VMware (part of Broadcom)
    - 💬 简介：确保容器镜像的完整性和真实性对于保护容器供应链至关重要。随着开发人员越来越多地使用来自外部来源的镜像，一些问题浮出水面：我们如何验证这些镜像来自可信赖的供应商？我们如何确保它们自创建以来没有被篡改？在这场演讲中，您将从VMware Bitnami的实际经验中学习，他们与Notary项目社区合作实施了镜像签名和验证。Bitnami将向您展示他们如何使用Notary项目签名来确保来自Docker Hub的镜像的完整性和真实性。不要错过这个机会，在您的CI/CD流水线和Kubernetes部署中通过Notary项目获得容器安全的实用见解！此外，我们将探讨未来的增强功能，包括证明支持，使用户能够从各种角度验证镜像，如来源、漏洞评估和软件合规性。

1. Exploiting Common Vulnerabilities in AWS environments

    - 📅 日期：2024-08-09
    - 📑 文件：<https://docs.google.com/presentation/d/1-oYd-qv_b09gdAflJ3LSJzs1WQjWbjWHACHvGhKgBIo/edit>
    - 🔗 链接：DEFCON 32会议的云安全专题 <https://dc32.cloud-village.org/>
    - 💬 简介：作者Seth Art分享了在AWS环境下，攻击者通常如何突破云环境以及后期利用的方式。在大多数情况下，攻击者获得初步访问云环境的方式有三种：突破了云中的一个易受攻击的应用程序或服务、一个配置错误的云资源，或者一个具有云访问权限的用户。这是来自DEFCON 32会议的云安全专题众多议题中的一个分享。

## 2024-06

1. 云服务常见漏洞分享

    - 📅 日期：2024-06-21
    - 📑 文件：[云服务常见漏洞分享](./4-云服务常见漏洞分享.pdf)
    - 🔗 在线观看：<https://bytedance.larkoffice.com/file/X29Zbl80LoOE7uxSq8RcV8Zwnmd>

1. 作为新手如何开展AWS安全研究  

    - 📅 日期：2024-06-17
    - 📑 标题：Get into AWS security research as a n00bcake
    - 💬 简介：想要进入 AWS 安全研究，但不知道从哪里开始？这个演讲就是为你准备的
    - 🔗 在线观看：<https://www.youtube.com/watch?v=jEFGzLbG1r4&list=PLCPCP1pNWD7PoUaDtU_T9XJSJ6d7cSfjl&index=40>

1. Kubernetes 安全：现代基础设施的攻击和防御

    - 📅 日期：2024-06-10
    - 📑 文件：[Kubernetes Security: Attacking and Defending Modern Infrastructure](./2024_USA24_SBX-R06_01_Kubernetes-Security-Attacking-And-Defending-Modern-Infrastructure_1713897952938001Snax.pdf)
    - 📑 标题：Kubernetes Security: Attacking and Defending Modern Infrastructure
    - 💬 简介：在云中运行工作负载会增加集群配置错误、凭据泄露、加密矿工和容器逃逸漏洞的风险。讨论 OWASP Kubernetes 十大威胁和 Kubernetes 威胁矩阵并探索减轻这些风险的保护措施将有助于防止攻击者使用 RBAC、OPA、安全性和其他内置功能损害您的组织。
    - 🔗 在线观看：<https://www.youtube.com/watch?v=iCzUv6-9zrI>


## 2024-03

1. KubeHound及拓展：通过图和自动化探究安全

    - 📅 日期：2024-03-11
    - 💬 标题：KubeHound and Beyond: Evolving Security Through Graphs & Automation - Jeremy Fox [SO-CON 2024](https://youtube.com/playlist?list=PLJK0fZNGiFU_Zh8PkjCws_Rw_8WdWKyd7&si=41KaKcoldSzIrhMn)
    - 📃 简介：这是Jeremy Fox在[SO-CON 2024](https://specterops.io/so-con/)会上的一篇演讲。本次演讲中Jeremy Fox将重点介绍Kubernetes安全，使用开源攻击路径计算工具KubeHound将防御模型从基于列表思维转变为基于图的思维(graph-based)。首先介绍基于列表方法的一些缺点，然后将以KubeHound为例，演示攻击"图数据"(attack graphs)如何解决这些缺点。最后介绍 KubeHound 的开发过程，如何根据公开研究创建Kubernetes中的攻击抽象图数据模型，以及如何将该过程扩展到其他领域。让我们更好地理解基于图的技术如何帮助解决现代Kubernetes中的安全复杂性，以及在其他领域创建自己的基于图的攻击模型路线图。
    - 📑 文件：[KubeHound and Beyond_Jeremy Fox](https://github.com/SpecterOps/presentations/tree/main/SO-CON%202024/Jeremy%20Fox%20-%20KubeHound%20and%20Beyond)
    - 🔗 在线观看：<https://youtu.be/pdCcJ-Kenf8?si=JyFUtRfJfFU2cDAP>

1. Apeman项目：绘制AWS身份攻击路径

    - 📅 日期：2024-03-11
    - 💬 标题：Project Apeman: Mapping AWS Identity Attack Paths - Daniel Heinsen [SO-CON 2024](https://youtube.com/playlist?list=PLJK0fZNGiFU_Zh8PkjCws_Rw_8WdWKyd7&si=41KaKcoldSzIrhMn)
    - 📃 简介：这是Daniel Heinsen在[SO-CON 2024](https://specterops.io/so-con/)会上的一篇演讲。在不断发展的云安全格局中，自动发现身份攻击路径已成为缓解网络威胁的关键策略。本次演讲深入探讨了AWS生态系统中的"Tier 0"安全概念，并介绍了Apeman，这是一种新的原型工具，旨在映射和可视化AWS身份攻击路径。讨论还将深入探讨Apeman开发过程中遇到的挑战。
    - 📑 文件：[Project Apeman_Daniel Heinsen](https://github.com/SpecterOps/presentations/tree/main/SO-CON%202024/Daniel%20Heinsen%20-%20Project%20Apeman)
    - 🔗 在线观看：<https://youtu.be/Gs5BZplrxe4?si=anDhx4cXyukgSEgJ>

1. 用这5个简单的技巧让黑客远离你的Kubernetes集群

    - 📅 日期：2024-03-22
    - 💬 博客：Keep Hackers Out of Your Cluster with These 5 Simple Tricks: <https://tldrsec.com/p/kubernetes-security-threat-informed-defense>
    - 📑 文件：[Keep Hackers Out of Your Cluster with These 5 Simple Tricks](https://docs.google.com/presentation/d/1FDzzxo7U_890_nHZyNK9L3XNisqao5aVyJrqI1ntgmE/edit#slide=id.g2c3c3dab940_0_481)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=UZz44j8bszU>

## 2022-11

1. Kubernetes特权升级：容器逃逸==集群管理员？

    - 📅 日期：2022-11-29
    - 📑 文件：[Kubernetes Privilege Escalation: Container Escape == Cluster Admin?](./Kubernetes%20Privilege%20Escalation:%20Container%20Escape%20equal%20to%20Cluster%20Admin.pdf)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=oc1tq_r6VNM>

## 2021-12

1. Exploit Symlink for Fun and Profit From Native to Cloud Native

    - 📅 日期：2021-12
    - 📑 文件：[Exploit Symlink for Fun and Profit From Native to Cloud Native](./TechWorld创新沙龙-202112-symlink.pdf)
    - 🔗 链接：<https://github.com/brant-ruan/slides-and-papers/blob/master/TechWorld%E5%88%9B%E6%96%B0%E6%B2%99%E9%BE%99-202112-symlink.pdf>

## 2021-07

1. 如何找到容器平台的 bug？

    - 📅 日期：2021-07-05
    - 📑 文件：[2021 CodeEngn Conference 17 | 컨테이너에서 버그 찾기 어디까지 해봤니?](./2021%20CodeEngn%20Conference%2017,%20컨테이너에서%20버그%20찾기%20어디까지%20해봤니%20[김우석].pdf)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=cBQg3m9bO48>

## 2020-12

1. k0otkit:针对K8s集群的通用后渗透控制技术

    - 📅 日期：2020-12-30
    - 📑 文件：[k0otkit:针对K8s集群的通用后渗透控制技术](./k0otkit：针对K8s集群的通用后渗透控制技术.pdf)
    - 🔗 链接：<https://blog.nsfocus.net/k0otkithack-k8s-in-a-k8s-way/>

## 2020-02

1. 高级持久性威胁：Kubernetes攻击的未来

    - 📅 日期：2020-02-28
    - 📑 文件：[Advanced Persistence Threats: The Future of Kubernetes Attacks](./2020_USA20_csv-f01_01_advanced-persistence-threats-the-future-of-kubernetes-attacks.pdf)
    - 🔗 链接：<https://www.youtube.com/watch?v=CH7S5rE3j8w>

1. 通过利用 RBAC 权限来入侵 Kubernetes 集群

    - 📅 日期：2020-02-26
    - 📑 文件：[Compromising Kubernetes Cluster by Exploiting RBAC Permissions](./2020_USA20_dso-w01_01_compromising-kubernetes-cluster-by-exploiting-rbac-permissions.pdf)
    - 🔗 链接：<https://www.youtube.com/watch?v=1LMo0CftVC4>

## 2019-11

1. 墙内墙：如果你的攻击者知道跑酷怎么办？

    - 📅 日期：2019-11-22
    - 📑 文件：[Walls Within Walls: What if Your Attacker Knows Parkour?](./walls_within_walls_castle_tallclair_kubeconUSA2019.pdf)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=6rMGRvcjvKc>

## 2017-12

1. Hacking and Hardening Kubernetes Clusters by Example

    - 📅 日期：2017-12-16
    - 📑 文件：[Hacking and Hardening Kubernetes Clusters by Example](./Hacking%20and%20Hardening%20Kubernetes%20Clusters%20by%20Example.pdf)
    - 🔗 在线观看：<https://www.youtube.com/watch?v=vTgQLzeBfRU&t=73s>
