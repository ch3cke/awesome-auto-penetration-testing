# awesome-auto-penetration-testing

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)
![License](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey.svg)

A curated list of papers, tools, benchmarks, datasets, and resources for automated penetration testing.

## Contents

- [Papers](#papers)
    - [Surveys and SoK](#surveys-and-sok)
    - [Regular Papers](#regular-papers)
- [Benchmarks and Cyber Ranges](#benchmarks-and-cyber-ranges)
- [Blogs](#blog)

## Papers

### Surveys and SoK

**Frontier AI's Impact on the Cybersecurity Landscape** [[WebSite](https://rdi.berkeley.edu/frontier-ai-impact-on-cybersecurity/)] [[Paper](https://arxiv.org/abs/2504.05408)]  
![arXiv](https://img.shields.io/badge/arXiv-ID-b31b1b.svg)
![Rank-N/A](https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Type-Survey](https://img.shields.io/badge/Type-Survey-purple.svg)  
Published: 2025-11  
Tags: `LLM`

<details><summary>Abstract</summary>
The impact of frontier AI (i.e., AI agents and foundation models) in cybersecurity is rapidly increasing. In this paper, we comprehensively analyze this trend through multiple aspects: quantitative benchmarks, qualitative literature review, empirical evaluation, and expert survey. Our analyses consistently show that AI's capabilities and applications in attacks have exceeded those on the defensive side. Our empirical evaluation of widely used agent systems on cybersecurity benchmarks highlights that current AI agents struggle with flexible workflow planning and using domain-specific tools for complex security analysis -- capabilities particularly critical for defensive applications. Our expert survey of AI and security researchers and practitioners indicates a prevailing view that AI will continue to benefit attackers over defenders, though the gap is expected to narrow over time. These results show the urgent need to evaluate and mitigate frontier AI's risks, steering it towards benefiting cyber defenses. Responding to this need, we provide concrete calls to action regarding: the construction of new cybersecurity benchmarks, the development of AI agents for defense, the design of provably secure AI agents, the improvement of pre-deployment security testing and transparency, and the strengthening of user-oriented education and defenses.
  </details> 

---

**SoK: A Comparison of Autonomous Penetration Testing Agents** [[Paper](https://dl.acm.org/doi/10.1145/3664476.3664484)]  
![ARES](https://img.shields.io/badge/ARES-2024-blue.svg)
![Rank-N/A](https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Type-Survey](https://img.shields.io/badge/Type-Survey-purple.svg)
![Code](https://img.shields.io/badge/Code-Unavailable-lightgrey)  
Published: 2024-08  
Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
In the still growing field of cyber security, machine learning methods have largely been employed for detection tasks. Only a small portion revolves around offensive capabilities. Through the rise of Deep Reinforcement Learning, agents have also emerged with the goal of actively assessing the security of systems by the means of penetration testing. Thus learning the usage of different tools to emulate humans. In this paper we present an overview, and comparison of different autonomous penetration testing agents found within the literature. Various agents have been proposed, making use of distinct methods, but several factors such as modelling of the environment and scenarios, different algorithms, and the difference in chosen methods themselves, make it difficult to draw conclusions on the current state and performance of those agents. This comparison also lets us identify research challenges that present a major limiting factor, such as handling large action spaces, partial observability, defining the right reward structure, and learning in a real-world scenario.</details>

---

### Regular Papers


---

## Benchmarks and Cyber Ranges
**ExploitGym: Can AI Agents Turn Security Vulnerabilities into Real Attacks?** [[Paper](https://arxiv.org/abs/2605.11086)]   
![arXiv](https://img.shields.io/badge/arXiv-ID-b31b1b.svg)
![Rank-N/A](https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Unavailable-lightgrey)
![Type-Regular Paper](https://img.shields.io/badge/Type-Regular%20Paper-00A6A6)   
Published: 2026-05-11   
Tags: `Exploit` | `LLM`
<details>
<summary>Abstract</summary>
AI agents are rapidly gaining capabilities that could significantly reshape cybersecurity, making rigorous evaluation urgent. A critical capability is exploitation: turning a vulnerability, which is not yet an attack, into a concrete security impact, such as unauthorized file access or code execution. Exploitation is a particularly challenging task because it requires low-level program reasoning (e.g., about memory layout), runtime adaptation, and sustained progress over long horizons. Meanwhile, it is inherently dual-use, supporting defensive workflows while lowering the barrier for offense. Despite its importance and diagnostic value, exploitation remains under-evaluated. To address this gap, we introduce ExploitGym, a large-scale, diverse, realistic benchmark on the exploitation capabilities of AI agents. Given a program input that triggers a vulnerability, ExploitGym tasks agents with progressively extending it into a working exploit. The benchmark comprises 898 instances sourced from real-world vulnerabilities across three domains, including userspace programs, Google's V8 JavaScript engine, and the Linux kernel. We vary the security protections applied to each instance, isolating their impact on agent performance. All configurations are packaged in reproducible containerized environments. Our evaluation shows that while exploitation remains challenging, frontier models can successfully exploit a non-trivial fraction of vulnerabilities. For example, the strongest configurations are Anthropic's latest model Claude Mythos Preview and OpenAI's GPT-5.5, which produce working exploits for 157 and 120 instances, respectively. Notably, even with widely used defenses enabled, models retain non-trivial success rates. These results establish ExploitGym as an effective testbed for exploitation and highlight the growing cybersecurity risks posed by increasingly capable AI agents.
</details>

---
**RedTeamCUA: Towards Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments** [[WebSite](https://osu-nlp-group.github.io/RedTeamCUA/)][[Paper](https://openreview.net/forum?id=yWwrgcBoK3)][[Code](https://github.com/OSU-NLP-Group/RedTeamCUA.git)]   
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2026-04-11   
Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
Computer-use agents (CUAs) promise to automate complex tasks across operating systems (OS) and the web, but remain vulnerable to indirect prompt injection, where attackers embed malicious content into the environment to hijack agent behavior. Current evaluations of this threat either lack support for adversarial testing in realistic but controlled environments or ignore hybrid web-OS attack scenarios involving both interfaces. To address this, we propose RedTeamCUA, an adversarial testing framework featuring a novel hybrid sandbox that integrates a VM-based OS environment with Docker-based web platforms. Our sandbox supports key features tailored for red teaming, such as flexible adversarial scenario configuration, and a setting that decouples adversarial evaluation from navigational limitations of CUAs by initializing tests directly at the point of an adversarial injection. Using RedTeamCUA, we develop RTC-Bench, a comprehensive benchmark with 864 examples that investigate realistic, hybrid web-OS attack scenarios and fundamental security vulnerabilities. Benchmarking current frontier CUAs identifies significant vulnerabilities: Claude 3.7 Sonnet | CUA demonstrates an Attack Success Rate (ASR) of 42.9%, while Operator, the most secure CUA evaluated, still exhibits an ASR of 7.6%. Notably, CUAs often attempt to execute adversarial tasks with an Attempt Rate as high as 92.5%, although failing to complete them due to capability limitations. Nevertheless, we observe concerning ASRs of up to 50% in realistic end-to-end settings, indicating that CUA threats can already result in tangible risks to users and computer systems. Overall, RedTeamCUA provides an essential framework for advancing realistic, controlled, and systematic analysis of CUA vulnerabilities, highlighting the urgent need for robust defenses to indirect prompt injection prior to real-world deployment.
  </details> 

---

**CVE-Bench: A Benchmark for AI Agents’ Ability to Exploit Real-World Web Application Vulnerabilities** [[Paper](https://icml.cc/virtual/2025/poster/46522)][[Code](https://github.com/uiuc-kang-lab/cve-bench.git)]   
![ICML](https://img.shields.io/badge/ICML-2025-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2025-07-13   
Tags: `WEB` | `Exploit` | `LLM`
<details><summary>Abstract</summary>
Large language model (LLM) agents are increasingly capable of autonomously conducting cyberattacks, posing significant threats to existing applications. This growing risk highlights the urgent need for a real-world benchmark to evaluate the ability of LLM agents to exploit web application vulnerabilities. However, existing benchmarks fall short as they are limited to abstracted Capture-the-Flag competitions or lack comprehensive coverage. Building a benchmark for real-world vulnerabilities involves both specialized exper-tise to reproduce exploits and a systematic approach to evaluating unpredictable attacks. To address this challenge, we introduce CVE-Bench, a real-world cybersecurity benchmark based on critical-severity Common Vulnerabilities and Exposures. In CVE-Bench, we design a sandbox framework that enables LLM agents to exploit vulnerable web applications in scenarios that mimic real-world conditions, while also providing effective evaluation of their exploits. Our experiments show that the state-of-the-art agent framework can exploit up to 13% of the vulnerabilities.   
  </details> 

---
