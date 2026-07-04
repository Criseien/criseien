# Cristian Aranda

Kubernetes networking, traced from the kernel up. 8 years keeping production alive at a top-tier
LATAM bank; now a full-time deep dive (2026–27): Linux networking → Kubernetes → Cilium/eBPF.

problems, transformed phase by phase. CI, Ansible, 8 ADRs documenting every deliberate anti-pattern
before the fix. Production judgment, not just commands.

**Writing — the *From Scratch* series, in order:**
1. [Building a container network from scratch: namespaces, veth, bridges](https://www.icris.me/posts/building-container-network-from-scratch/)
2. [How pods reach the internet: NAT and masquerading](https://www.icris.me/posts/how-pods-reach-internet-nat-masquerading/)
3. [Exposing a service without Kubernetes: DNAT load balancing with iptables](https://www.icris.me/posts/exposing-service-dnat-load-balancing-iptables/)
4. [From Splunk to Kubernetes: what 8 years of alert fatigue taught me about self-healing systems](https://www.icris.me/posts/from-splunk-to-kubernetes-rollout-self-healing/)

Next: kube-proxy's real DNAT path → why iptables stops scaling (conntrack, O(n)) → a first trace
through the Cilium/eBPF datapath.

Earlier hands-on labs (Linux internals, Docker, networking) are archived at
[platform-fundamentals](https://github.com/Criseien/platform-fundamentals) — reference material,
not active work.

---

[![Blog](https://img.shields.io/badge/Blog-icris.me-2ea44f?style=flat-square&logo=rss)](https://icris.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Cristian_Aranda-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/cristiangomezaranda/?locale=en_US)
