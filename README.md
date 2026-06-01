<h1 align="center">Awesome-Auto-Penetration-Testing</h1>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  <img src="https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey.svg" alt="License">
</p>

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
![CCF-B](https://img.shields.io/badge/CCF-B-orange.svg)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Type-Survey](https://img.shields.io/badge/Type-Survey-purple.svg)
![Code](https://img.shields.io/badge/Code-Unavailable-lightgrey)
![Type-Survey](https://img.shields.io/badge/Type-Survey-purple.svg)  
Published: 2024-08  
Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
In the still growing field of cyber security, machine learning methods have largely been employed for detection tasks. Only a small portion revolves around offensive capabilities. Through the rise of Deep Reinforcement Learning, agents have also emerged with the goal of actively assessing the security of systems by the means of penetration testing. Thus learning the usage of different tools to emulate humans. In this paper we present an overview, and comparison of different autonomous penetration testing agents found within the literature. Various agents have been proposed, making use of distinct methods, but several factors such as modelling of the environment and scenarios, different algorithms, and the difference in chosen methods themselves, make it difficult to draw conclusions on the current state and performance of those agents. This comparison also lets us identify research challenges that present a major limiting factor, such as handling large action spaces, partial observability, defining the right reward structure, and learning in a real-world scenario.</details>

---

### Regular Papers

**AWE: Adaptive Agents for Dynamic Web Penetration Testing** [[Paper](https://www.ndss-symposium.org/ndss-paper/auto-draft-680/)] [[Code](https://github.com/stuxlabs/AWE)]  
![NDSS](https://img.shields.io/badge/NDSS-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Regular Paper](https://img.shields.io/badge/Type-Regular%20Paper-00A6A6)   
Published: 2026-02  
Tags: `WEB` | `LLM` | `Agent`
<details><summary>Abstract</summary>
Modern web applications are increasingly produced through AI-assisted development and rapid no-code deployment pipelines, widening the gap between accelerating software velocity and the limited adaptability of existing security tooling. Pattern-driven scanners fail to reason about novel contexts, while emerging LLM-based penetration testers rely on unconstrained exploration, yielding high cost, unstable behavior, and poor reproducibility.

We introduce AWE, a memory-augmented multi-agent framework for autonomous web penetration testing that embeds structured, vulnerability-specific analysis pipelines within a lightweight LLM orchestration layer. Unlike general-purpose agents, AWE couples context aware payload mutations and generations with persistent memory and browser-backed verification to produce deterministic, exploitation-driven results.

Evaluated on the 104-challenge XBOW benchmark, AWE achieves substantial gains on injection-class vulnerabilities - 87% XSS success (+30.5% over MAPTA) and 66.7% blind SQL injection success (+33.3%) - while being much faster, cheaper, and more token-efficient than MAPTA, despite using a midtier model (Claude Sonnet 4) versus MAPTA’s GPT-5. MAPTA retains higher overall coverage due to broader exploratory capabilities, underscoring the complementary strengths of specialized and general-purpose architectures. Our results demonstrate that architecture matters as much as model reasoning capabilities: integrating LLMs into principled, vulnerability-aware pipelines yields substantial gains in accuracy, efficiency, and determinism for injection-class exploits. The source code for AWE is available at: https://github.com/stuxlabs/AWE </details>

---
**Cyber-Zero: Training Cybersecurity Agents without Runtime** [[Paper](https://openreview.net/pdf?id=1gRTeAik4G)] [[Code](https://github.com/amazon-science/cyber-zero)]    
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Unavailable-lightgrey)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Regular Paper](https://img.shields.io/badge/Type-Regular%20Paper-00A6A6)   
Published: 2026-04   
Tags: `CTF` | `LLM`
 <details><summary>Abstract</summary>
Large Language Models (LLMs) have achieved remarkable success in software engineering tasks when trained with executable runtime environments, particularly in resolving GitHub issues. However, such runtime environments are often unavailable in other domains, especially cybersecurity, where challenge configurations and execution contexts are ephemeral or restricted. We present Cyber-Zero, the first runtime-free framework for synthesizing high-quality agent trajectories to train cybersecurity LLMs. Cyber-Zero leverages publicly available CTF writeups and employs persona-driven LLM simulation to reverse-engineer runtime behaviors and generate realistic, long-horizon interaction sequences without actual environments. Using trajectories synthesized by Cyber-Zero, we train LLM-based agents that achieve up to 13.1% absolute performance gains over baseline models on three prominent CTF benchmarks: InterCode-CTF, NYU CTF Bench, and Cybench. Our best model, Cyber-Zero-32B, establishes new state-of-the-art performance among open-weight models, matching the capabilities of proprietary systems like DeepSeek-V3-0324 and Claude-3.5-Sonnet while offering superior cost-effectiveness, and demonstrating that runtime-free trajectory synthesis can effectively democratize the development of state-of-the-art cybersecurity agents.
  </details> 

---


## Benchmarks and Cyber Ranges
**ExploitGym: Can AI Agents Turn Security Vulnerabilities into Real Attacks?** [[Paper](https://arxiv.org/abs/2605.11086)]   
![arXiv](https://img.shields.io/badge/arXiv-ID-b31b1b.svg)
![Rank-N/A](https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg)
![Website](https://img.shields.io/badge/Website-Unavailable-lightgrey)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Unavailable-lightgrey)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2026-05  
Tags: `Exploit` | `LLM`
<details>
<summary>Abstract</summary>
AI agents are rapidly gaining capabilities that could significantly reshape cybersecurity, making rigorous evaluation urgent. A critical capability is exploitation: turning a vulnerability, which is not yet an attack, into a concrete security impact, such as unauthorized file access or code execution. Exploitation is a particularly challenging task because it requires low-level program reasoning (e.g., about memory layout), runtime adaptation, and sustained progress over long horizons. Meanwhile, it is inherently dual-use, supporting defensive workflows while lowering the barrier for offense. Despite its importance and diagnostic value, exploitation remains under-evaluated. To address this gap, we introduce ExploitGym, a large-scale, diverse, realistic benchmark on the exploitation capabilities of AI agents. Given a program input that triggers a vulnerability, ExploitGym tasks agents with progressively extending it into a working exploit. The benchmark comprises 898 instances sourced from real-world vulnerabilities across three domains, including userspace programs, Google's V8 JavaScript engine, and the Linux kernel. We vary the security protections applied to each instance, isolating their impact on agent performance. All configurations are packaged in reproducible containerized environments. Our evaluation shows that while exploitation remains challenging, frontier models can successfully exploit a non-trivial fraction of vulnerabilities. For example, the strongest configurations are Anthropic's latest model Claude Mythos Preview and OpenAI's GPT-5.5, which produce working exploits for 157 and 120 instances, respectively. Notably, even with widely used defenses enabled, models retain non-trivial success rates. These results establish ExploitGym as an effective testbed for exploitation and highlight the growing cybersecurity risks posed by increasingly capable AI agents.
</details>

---
**HackWorld: Evaluating Computer-Use Agents on Exploiting Web Application Vulnerabilities** [[Paper](https://openreview.net/pdf?id=nLfZPoJbO7)] [[Code](https://github.com/GUI-Agent/HackWorld)]    
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Unavailable-lightgrey)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)  
Published: 2026-04   
Tags: `WEB` | `LLM`
 <details><summary>Abstract</summary>
Web applications are prime targets for cyberattacks due to their role as entry points to vital services and sensitive data repositories. Traditional penetration testing is expensive and requires specialized expertise, creating scalability challenges for securing the expanding web ecosystem. While language model agents have shown promise in certain cybersecurity tasks, modern web applications require visual understanding of complex user interfaces, dynamic content rendering, and multi-step interactive workflows that only computer-use agents (CUAs) can handle. Despite CUAs' demonstrated capabilities in web browsing and visual task automation, their potential to discover and exploit web application vulnerabilities through graphical interfaces remains unknown. We introduce HackWorld, the first evaluation framework for systematically assessing CUAs' capabilities in exploiting web application vulnerabilities through visual interaction. Unlike existing benchmarks using sanitized environments, HackWorld exposes CUAs to 36 curated applications spanning 11 frameworks and 7 languages, containing realistic vulnerabilities including injection flaws, authentication bypasses, and unsafe input handling. Our framework directly evaluates CUAs' ability to discover and exploit these vulnerabilities using Capture-the-Flag (CTF) methodology while navigating complex web interfaces. Evaluation of state-of-the-art CUAs reveals exploitation rates below 12%, struggling to plan multi-step attacks and use security tools effectively. Our results expose CUAs' limited cybersecurity skills when operating on vulnerable web applications, opening future research directions on developing security-aware CUAs for vulnerability detection and exploitation.
  </details> 

---
**PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities** [[WebSite](https://pacebench.github.io/)] [[Paper](https://openreview.net/pdf?id=kGEuZXaXU6)] [[Code](https://github.com/RyuKosei/PACEbench)]    
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2026-04   
Tags: `ATTACK&DEFENCE` | `LLM`
<details><summary>Abstract</summary>
The increasing autonomy of Large Language Models (LLMs) necessitates a rigorous evaluation of their potential to aid in cyber offense. Existing benchmarks often lack real-world complexity and are thus unable to accurately assess LLMs' cybersecurity capabilities. To address this gap, we introduce PACEbench, a practical AI cyber-exploitation benchmark built on the principles of realistic vulnerability difficulty, environmental complexity, and cyber defenses. Specifically, PACEbench comprises four scenarios spanning single, blended, chained, and defense vulnerability exploitations. To handle these complex challenges, we propose PACEagent, a novel agent that emulates human penetration testers by supporting multi-phase reconnaissance, analysis, and exploitation. Extensive experiments with seven frontier LLMs demonstrate that current models struggle with complex cyber scenarios, and none can bypass defenses. These findings suggest that current models do not yet pose a generalized cyber offense threat. Nonetheless, our work provides a robust benchmark to guide the trustworthy development of future models.
  </details> 

---
**RedTeamCUA: Towards Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments** [[WebSite](https://osu-nlp-group.github.io/RedTeamCUA/)] [[Paper](https://openreview.net/forum?id=yWwrgcBoK3)] [[Code](https://github.com/OSU-NLP-Group/RedTeamCUA.git)]   
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2026-04   
Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
Computer-use agents (CUAs) promise to automate complex tasks across operating systems (OS) and the web, but remain vulnerable to indirect prompt injection, where attackers embed malicious content into the environment to hijack agent behavior. Current evaluations of this threat either lack support for adversarial testing in realistic but controlled environments or ignore hybrid web-OS attack scenarios involving both interfaces. To address this, we propose RedTeamCUA, an adversarial testing framework featuring a novel hybrid sandbox that integrates a VM-based OS environment with Docker-based web platforms. Our sandbox supports key features tailored for red teaming, such as flexible adversarial scenario configuration, and a setting that decouples adversarial evaluation from navigational limitations of CUAs by initializing tests directly at the point of an adversarial injection. Using RedTeamCUA, we develop RTC-Bench, a comprehensive benchmark with 864 examples that investigate realistic, hybrid web-OS attack scenarios and fundamental security vulnerabilities. Benchmarking current frontier CUAs identifies significant vulnerabilities: Claude 3.7 Sonnet | CUA demonstrates an Attack Success Rate (ASR) of 42.9%, while Operator, the most secure CUA evaluated, still exhibits an ASR of 7.6%. Notably, CUAs often attempt to execute adversarial tasks with an Attempt Rate as high as 92.5%, although failing to complete them due to capability limitations. Nevertheless, we observe concerning ASRs of up to 50% in realistic end-to-end settings, indicating that CUA threats can already result in tangible risks to users and computer systems. Overall, RedTeamCUA provides an essential framework for advancing realistic, controlled, and systematic analysis of CUA vulnerabilities, highlighting the urgent need for robust defenses to indirect prompt injection prior to real-world deployment.
  </details> 

---
**CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale** [[WebSite](https://www.cybergym.io/)] [[Paper](https://openreview.net/pdf?id=2YvbLQEdYt)] [[Code](https://github.com/sunblaze-ucb/cybergym.git)]   
![ICLR](https://img.shields.io/badge/ICLR-2026-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Type-Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)  
Published: 2026-04   
Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
AI agents have significant potential to reshape cybersecurity, making a thorough assessment of their capabilities critical. However, existing evaluations fall short, because they are based on small-scale benchmarks and only measure static outcomes, failing to capture the full, dynamic range of real-world security challenges. To address these limitations, we introduce CyberGym, a large-scale benchmark featuring 1,507 real-world vulnerabilities across 188 software projects. Adjustable to different vulnerability analysis settings, CyberGym primarily tasks agents with generating a proof-of-concept test that reproduces a vulnerability, given only its text description and the corresponding codebase. Our extensive evaluation highlights that CyberGym effectively differentiates agents' and models' cybersecurity capabilities. Even the top-performing combinations only achieve a ~20% success rate, demonstrating the overall difficulty of CyberGym. Beyond static benchmarking, we show that CyberGym leads to the discovery of 34 zero-day vulnerabilities and 18 historically incomplete patches. These results underscore that CyberGym is not only a robust benchmark for measuring AI's progress in cybersecurity but also a platform for creating direct, real-world security impact.
</details>

--- 
**CVE-Bench: A Benchmark for AI Agents’ Ability to Exploit Real-World Web Application Vulnerabilities** [[WebSite](https://cvebench.com/)] [[Paper](https://icml.cc/virtual/2025/poster/46522)] [[Code](https://github.com/uiuc-kang-lab/cve-bench.git)]   
![ICML](https://img.shields.io/badge/ICML-2025-blue.svg)
![CCF-A](https://img.shields.io/badge/CCF-A-red.svg)
![Website](https://img.shields.io/badge/Website-Available-7B61FF)
![Paper](https://img.shields.io/badge/Paper-blue.svg)
![Code](https://img.shields.io/badge/Code-Available-181717)
![Type-Benchmark](https://img.shields.io/badge/Type-Benchmark-orange.svg)   
Published: 2025-07  
Tags: `WEB` | `Exploit` | `LLM`
<details><summary>Abstract</summary>
Large language model (LLM) agents are increasingly capable of autonomously conducting cyberattacks, posing significant threats to existing applications. This growing risk highlights the urgent need for a real-world benchmark to evaluate the ability of LLM agents to exploit web application vulnerabilities. However, existing benchmarks fall short as they are limited to abstracted Capture-the-Flag competitions or lack comprehensive coverage. Building a benchmark for real-world vulnerabilities involves both specialized exper-tise to reproduce exploits and a systematic approach to evaluating unpredictable attacks. To address this challenge, we introduce CVE-Bench, a real-world cybersecurity benchmark based on critical-severity Common Vulnerabilities and Exposures. In CVE-Bench, we design a sandbox framework that enables LLM agents to exploit vulnerable web applications in scenarios that mimic real-world conditions, while also providing effective evaluation of their exploits. Our experiments show that the state-of-the-art agent framework can exploit up to 13% of the vulnerabilities.   
  </details> 

---
