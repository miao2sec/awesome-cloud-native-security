# 演示文稿

## 2024-09

16. How to 10X Your Cloud Security (Without the Series D)
- 🔗 链接：<https://speakerdeck.com/ramimac/how-to-10x-your-cloud-security-without-the-series-d>
- 💬 简介：Rami McCarthy 在fwd cloudsec EU会议上的精彩演讲，他对构建安全程序、不变量、漏洞和资产管理、身份和访问管理、检测工程、部署等方面的有用资源和想法。作者总结提炼了将云安全项目规模化的可行指导，这些指导来自众多的演讲和博客文章。将快速浏览云安全是什么，如何更有效地进行云安全工作，以及未来可能的发展方向。演讲结束也会获得实用的要点，以及一份详尽的参考文献。

## 2024-08

15. 加强容器安全性：共同的旅程｜KC24
- 📅 日期：2024-08-21-23
- 🔗 链接：<https://mp.weixin.qq.com/s/arrxfJOnctaGb4eoWFR9pQ>
- 💬 简介：Strengthening Container Security: A Collaborative Journey | 加强容器安全性：共同的旅程 - Yi Zha, Microsoft & Beltran Rueda Borrego, VMware (part of Broadcom)
- 💬 简介：确保容器镜像的完整性和真实性对于保护容器供应链至关重要。随着开发人员越来越多地使用来自外部来源的镜像，一些问题浮出水面：我们如何验证这些镜像来自可信赖的供应商？我们如何确保它们自创建以来没有被篡改？在这场演讲中，您将从VMware Bitnami的实际经验中学习，他们与Notary项目社区合作实施了镜像签名和验证。Bitnami将向您展示他们如何使用Notary项目签名来确保来自Docker Hub的镜像的完整性和真实性。不要错过这个机会，在您的CI/CD流水线和Kubernetes部署中通过Notary项目获得容器安全的实用见解！此外，我们将探讨未来的增强功能，包括证明支持，使用户能够从各种角度验证镜像，如来源、漏洞评估和软件合规性。

14. Exploiting Common Vulnerabilities in AWS environments
- 📅 日期：2024-08-09
- 📑 文件：<https://docs.google.com/presentation/d/1-oYd-qv_b09gdAflJ3LSJzs1WQjWbjWHACHvGhKgBIo/edit>
- 🔗 链接：DEFCON 32会议的云安全专题 <https://dc32.cloud-village.org/>
- 💬 简介：作者Seth Art分享了在AWS环境下，攻击者通常如何突破云环境以及后期利用的方式。在大多数情况下，攻击者获得初步访问云环境的方式有三种：突破了云中的一个易受攻击的应用程序或服务、一个配置错误的云资源，或者一个具有云访问权限的用户。这是来自DEFCON 32会议的云安全专题众多议题中的一个分享。

## 2024-06

13. 作为新手如何开展AWS安全研究  
- 📅 日期：2024-06-17
- 📑 标题：Get into AWS security research as a n00bcake
- 💬 简介：想要进入 AWS 安全研究，但不知道从哪里开始？这个演讲就是为你准备的
- 🔗 在线观看：<https://www.youtube.com/watch?v=jEFGzLbG1r4&list=PLCPCP1pNWD7PoUaDtU_T9XJSJ6d7cSfjl&index=40>


12. 云服务常见漏洞分享

- 📅 日期：2024-06-21
- 📑 文件：[云服务常见漏洞分享](./4-云服务常见漏洞分享.pdf)
- 🔗 在线观看：<https://bytedance.larkoffice.com/file/X29Zbl80LoOE7uxSq8RcV8Zwnmd>

## 2024-03

11. KubeHound及拓展：通过图和自动化探究安全

- 📅 日期：2024-03-11
- 💬 标题：KubeHound and Beyond: Evolving Security Through Graphs & Automation - Jeremy Fox [SO-CON 2024](https://youtube.com/playlist?list=PLJK0fZNGiFU_Zh8PkjCws_Rw_8WdWKyd7&si=41KaKcoldSzIrhMn)
- 📃 简介：这是Jeremy Fox在[SO-CON 2024](https://specterops.io/so-con/)会上的一篇演讲。本次演讲中Jeremy Fox将重点介绍Kubernetes安全，使用开源攻击路径计算工具KubeHound将防御模型从基于列表思维转变为基于图的思维(graph-based)。首先介绍基于列表方法的一些缺点，然后将以KubeHound为例，演示攻击"图数据"(attack graphs)如何解决这些缺点。最后介绍 KubeHound 的开发过程，如何根据公开研究创建Kubernetes中的攻击抽象图数据模型，以及如何将该过程扩展到其他领域。让我们更好地理解基于图的技术如何帮助解决现代Kubernetes中的安全复杂性，以及在其他领域创建自己的基于图的攻击模型路线图。
- 📑 文件：[KubeHound and Beyond_Jeremy Fox](https://github.com/SpecterOps/presentations/tree/main/SO-CON%202024/Jeremy%20Fox%20-%20KubeHound%20and%20Beyond)
- 🔗 在线观看：<https://youtu.be/pdCcJ-Kenf8?si=JyFUtRfJfFU2cDAP>


10. Apeman项目：绘制AWS身份攻击路径

- 📅 日期：2024-03-11
- 💬 标题：Project Apeman: Mapping AWS Identity Attack Paths - Daniel Heinsen [SO-CON 2024](https://youtube.com/playlist?list=PLJK0fZNGiFU_Zh8PkjCws_Rw_8WdWKyd7&si=41KaKcoldSzIrhMn)
- 📃 简介：这是Daniel Heinsen在[SO-CON 2024](https://specterops.io/so-con/)会上的一篇演讲。在不断发展的云安全格局中，自动发现身份攻击路径已成为缓解网络威胁的关键策略。本次演讲深入探讨了AWS生态系统中的"Tier 0"安全概念，并介绍了Apeman，这是一种新的原型工具，旨在映射和可视化AWS身份攻击路径。讨论还将深入探讨Apeman开发过程中遇到的挑战。
- 📑 文件：[Project Apeman_Daniel Heinsen](https://github.com/SpecterOps/presentations/tree/main/SO-CON%202024/Daniel%20Heinsen%20-%20Project%20Apeman)
- 🔗 在线观看：<https://youtu.be/Gs5BZplrxe4?si=anDhx4cXyukgSEgJ>


9. 用这5个简单的技巧让黑客远离你的Kubernetes集群

- 📅 日期：2024-03-22
- 💬 博客：Keep Hackers Out of Your Cluster with These 5 Simple Tricks: <https://tldrsec.com/p/kubernetes-security-threat-informed-defense>
- 📑 文件：[Keep Hackers Out of Your Cluster with These 5 Simple Tricks](https://docs.google.com/presentation/d/1FDzzxo7U_890_nHZyNK9L3XNisqao5aVyJrqI1ntgmE/edit#slide=id.g2c3c3dab940_0_481)
- 🔗 在线观看：<https://www.youtube.com/watch?v=UZz44j8bszU>

## 2022-11

8. Kubernetes特权升级：容器逃逸==集群管理员？

- 📅 日期：2022-11-29
- 📑 文件：[Kubernetes Privilege Escalation: Container Escape == Cluster Admin?](./Kubernetes%20Privilege%20Escalation:%20Container%20Escape%20equal%20to%20Cluster%20Admin.pdf)
- 🔗 在线观看：<https://www.youtube.com/watch?v=oc1tq_r6VNM>


## 2021-12

7. Exploit Symlink for Fun and Profit From Native to Cloud Native

- 📅 日期：2021-12
- 📑 文件：[Exploit Symlink for Fun and Profit From Native to Cloud Native](./TechWorld创新沙龙-202112-symlink.pdf)
- 🔗 链接：<https://github.com/brant-ruan/slides-and-papers/blob/master/TechWorld%E5%88%9B%E6%96%B0%E6%B2%99%E9%BE%99-202112-symlink.pdf>

## 2021-07

6. 如何找到容器平台的 bug？

- 📅 日期：2021-07-05
- 📑 文件：[2021 CodeEngn Conference 17 | 컨테이너에서 버그 찾기 어디까지 해봤니?](./2021%20CodeEngn%20Conference%2017,%20컨테이너에서%20버그%20찾기%20어디까지%20해봤니%20[김우석].pdf)
- 🔗 在线观看：<https://www.youtube.com/watch?v=cBQg3m9bO48>

## 2020-12

5. k0otkit:针对K8s集群的通用后渗透控制技术

- 📅 日期：2020-12-30
- 📑 文件：[k0otkit:针对K8s集群的通用后渗透控制技术](./k0otkit：针对K8s集群的通用后渗透控制技术.pdf)
- 🔗 链接：<https://blog.nsfocus.net/k0otkithack-k8s-in-a-k8s-way/>

## 2020-02

4. 高级持久性威胁：Kubernetes攻击的未来

- 📅 日期：2020-02-28
- 📑 文件：[Advanced Persistence Threats: The Future of Kubernetes Attacks](./2020_USA20_csv-f01_01_advanced-persistence-threats-the-future-of-kubernetes-attacks.pdf)
- 🔗 链接：<https://www.youtube.com/watch?v=CH7S5rE3j8w>

3. 通过利用 RBAC 权限来入侵 Kubernetes 集群

- 📅 日期：2020-02-26
- 📑 文件：[Compromising Kubernetes Cluster by Exploiting RBAC Permissions](./2020_USA20_dso-w01_01_compromising-kubernetes-cluster-by-exploiting-rbac-permissions.pdf)
- 🔗 链接：<https://www.youtube.com/watch?v=1LMo0CftVC4>


## 2019-11

2. 墙内墙：如果你的攻击者知道跑酷怎么办？

- 📅 日期：2019-11-22
- 📑 文件：[Walls Within Walls: What if Your Attacker Knows Parkour?](./walls_within_walls_castle_tallclair_kubeconUSA2019.pdf)
- 🔗 在线观看：<https://www.youtube.com/watch?v=6rMGRvcjvKc>

## 2017-12

1. Hacking and Hardening Kubernetes Clusters by Example

- 📅 日期：2017-12-16
- 📑 文件：[Hacking and Hardening Kubernetes Clusters by Example](./Hacking%20and%20Hardening%20Kubernetes%20Clusters%20by%20Example.pdf)
- 🔗 在线观看：<https://www.youtube.com/watch?v=vTgQLzeBfRU&t=73s>
