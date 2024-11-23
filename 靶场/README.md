# 靶场

> 🚥
>
> 免费的云原生安全靶场。包括 CTF、自我托管研讨会、引导式漏洞实验室和研究实验室。

## 容器

1. contained.af

1. Container Security 101
- 🔗 链接：<https://github.com/genuinetools/contained.af>
- 💬 简介：一个学习容器、capability 和系统调用的游戏

1. Container Security 101

- 🔗 链接：<https://jonzeolla.com/labs/container-security-101.html>
- 💬 简介：一个关于“容器安全”的引导式漏洞工作坊。您只需要使用 cloudFormation 构建一个虚拟机（VM），创建一个容器，就可以按照网页上的步骤进行操作了。

1. Container Security 201

- 🔗 链接：<https://jonzeolla.com/labs/container-security-201.html>
- 💬 简介：一个关于“容器安全”的引导式漏洞工作坊。您只需要使用 cloudFormation 构建一个虚拟机（VM），创建一个容器，就可以按照网页上的步骤进行操作了。

1. Policy as Code

- 🔗 链接：<https://jonzeolla.com/labs/policy-as-code.html>
- 💬 简介：一个关于“策略即代码”的引导式漏洞工作坊。您只需要使用 cloudFormation 构建一个虚拟机（VM），创建一个容器，就可以按照网页上的步骤进行操作了。

1. metarget

- 🔗 链接：<https://github.com/Metarget/metarget>
- 💬 简介：一个脆弱基础设施自动化构建框架，主要用于快速、自动化搭建从简单到复杂的脆弱云原生靶机环境。目前涉及到的有：docker、containerd、runc、kubectl、kubernetes-cni、kernel、kata-containers和危险配置等。

1. KernJC

- 🔗 链接：<https://github.com/NUS-Curiosity/KernJC>
- 💬 简介：KernJC是Linux内核的漏洞复制工具。KernJC的目标是为Linux内核漏洞构建可重现的环境，其中真正的易受攻击的内核版本使用正确的内核配置编译，以使漏洞可用和可触发。

## Kubernetes

1. k8s lan party

- 🔗 链接：<https://www.k8slanparty.com/>
- 💬 简介：在线的需要注册的靶场，可以练习 Kubernetes 的错误配置和漏洞。

1. eks cluster games

- 🔗 链接：<https://eksclustergames.com/>
- 💬 简介：在线的需要注册的靶场，可以练习 EKS 集群 的错误配置和安全问题。

9. Bust a Kube

- 🔗 链接：<https://www.bustakube.com/>
- 💬 简介：下载有漏洞的 K8S 集群虚拟机，可以在 VMWare 中导入运行。

10. kubernetes goat

- 🔗 链接：<https://github.com/madhuakula/kubernetes-goat>
- 💬 简介：可以在云账号（GKE、EKS、AKS）或者是 K3S中创建托管的有漏洞的 K8S 集群，还有一个指导手册。

11. KubeCon NA 2019 CTF

- 🔗 链接：<https://securekubernetes.com/>
- 💬 简介：可以在 GCP 账户中创建的 CTF 靶场。包括2个攻击场景和2个防御场景。

12. kube security lab

- 🔗 链接：<https://github.com/raesene/kube_security_lab>
- 💬 简介：使用 Docker、Kind 和 Ansible 创建的本地 K8S 环境，包含 14 个易受攻击的场景。


## AWS

13. Pwned Labs

- 🔗 链接：<https://pwnedlabs.io/>
- 💬 简介：AWS公有云安全靶场，有官方配套题解，除了攻还有防，很适合入门和补缺～每个靶场有相应的场景和 RealWorld 描述，也把像 BlackHat 议题的点做成靶场，整体质量很高。来自@tari大佬的推荐，他整理的思维导图知识点很值得参考：<https://tari.moe/2024/pwnedlabs-aws-free.html>

14. cloudfoxable

- 🔗 链接：<https://github.com/BishopFox/cloudfoxable>
- 💬 简介：CloudGoat 是 Rhino Security Labs 的“设计易受攻击”的 AWS 部署工具。

## 一些综合平台

15. iximiuz Labs

- 🔗 链接：<https://labs.iximiuz.com/>
- 💬 简介：iximiuz Labs是由[Ivan Velichko](https://iximiuz.com/about)创建的独立学习平台。主要包括Linux、网络、Docker、K8s以及DevOps，SRE相关知识。

16. traefik漏洞CVE-2024-45410利用复现CTF靶场

- 🔗 链接：<https://github.com/jphetphoumy/traefik-CVE-2024-45410-poc>
- 💬 简介：Traefik是一个云原生的新型的 HTTP 反向代理、负载均衡软件。它负责接收系统的请求，然后使用合适的组件来对这些请求进行处理。Traefik兼容所有主流的集群技术，比如 Kubernetes，Docker，Docker Swarm，AWS，Mesos，Marathon，等等；并且可以同时处理多种方式。这个CTF复现靶场提供了traefik CVE-2024-45410的验证poc，了解漏洞影响。
