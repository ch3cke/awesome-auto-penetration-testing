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

- [Contents](#contents)
- [Papers](#papers)
  - [Surveys and SoK](#surveys-and-sok)
  - [Regular Papers](#regular-papers)
- [Benchmarks and Cyber Ranges](#benchmarks-and-cyber-ranges)
- [Tools and Code](#tools-and-code)

## Papers

### Surveys and SoK

**Frontier AI's Impact on the Cybersecurity Landscape** [[WebSite](https://rdi.berkeley.edu/frontier-ai-impact-on-cybersecurity/)] [[Paper](https://arxiv.org/abs/2504.05408)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-11

Tags: `LLM`
<details><summary>Abstract</summary>
The impact of frontier AI (i.e., AI agents and foundation models) in cybersecurity is rapidly increasing. In this paper, we comprehensively analyze this trend through multiple aspects: quantitative benchmarks, qualitative literature review, empirical evaluation, and expert survey. Our analyses consistently show that AI's capabilities and applications in attacks have exceeded those on the defensive side. Our empirical evaluation of widely used agent systems on cybersecurity benchmarks highlights that current AI agents struggle with flexible workflow planning and using domain-specific tools for complex security analysis -- capabilities particularly critical for defensive applications. Our expert survey of AI and security researchers and practitioners indicates a prevailing view that AI will continue to benefit attackers over defenders, though the gap is expected to narrow over time. These results show the urgent need to evaluate and mitigate frontier AI's risks, steering it towards benefiting cyber defenses. Responding to this need, we provide concrete calls to action regarding: the construction of new cybersecurity benchmarks, the development of AI agents for defense, the design of provably secure AI agents, the improvement of pre-deployment security testing and transparency, and the strengthening of user-oriented education and defenses.
</details>

---

**SoK: A Comparison of Autonomous Penetration Testing Agents** [[Paper](https://dl.acm.org/doi/10.1145/3664476.3664484)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ARES-2024-blue.svg" alt="ARES">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2024-08

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
In the still growing field of cyber security, machine learning methods have largely been employed for detection tasks. Only a small portion revolves around offensive capabilities. Through the rise of Deep Reinforcement Learning, agents have also emerged with the goal of actively assessing the security of systems by the means of penetration testing. Thus learning the usage of different tools to emulate humans. In this paper we present an overview, and comparison of different autonomous penetration testing agents found within the literature. Various agents have been proposed, making use of distinct methods, but several factors such as modelling of the environment and scenarios, different algorithms, and the difference in chosen methods themselves, make it difficult to draw conclusions on the current state and performance of those agents. This comparison also lets us identify research challenges that present a major limiting factor, such as handling large action spaces, partial observability, defining the right reward structure, and learning in a real-world scenario.
</details>

---

**An Empirical Survey of Functions and Configurations of Open-Source Capture the Flag (CTF) Environments** [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1084804519303303)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/JNCA-2023-blue.svg" alt="JNCA">
  <img src="https://img.shields.io/badge/CCF-C-yellow.svg" alt="CCF-C">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2023

Tags: `CTF` | `Survey` | `Cyber Range`
<details><summary>Abstract</summary>

</details>

---

### Regular Papers

**Cyber-Zero: Training Cybersecurity Agents without Runtime** [[Paper](https://openreview.net/pdf?id=1gRTeAik4G)] [[Code](https://github.com/amazon-science/cyber-zero)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICLR-2026-blue.svg" alt="ICLR">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-04

Tags: `CTF` | `LLM`
<details><summary>Abstract</summary>
Large Language Models (LLMs) have achieved remarkable success in software engineering tasks when trained with executable runtime environments, particularly in resolving GitHub issues. However, such runtime environments are often unavailable in other domains, especially cybersecurity, where challenge configurations and execution contexts are ephemeral or restricted. We present Cyber-Zero, the first runtime-free framework for synthesizing high-quality agent trajectories to train cybersecurity LLMs. Cyber-Zero leverages publicly available CTF writeups and employs persona-driven LLM simulation to reverse-engineer runtime behaviors and generate realistic, long-horizon interaction sequences without actual environments. Using trajectories synthesized by Cyber-Zero, we train LLM-based agents that achieve up to 13.1% absolute performance gains over baseline models on three prominent CTF benchmarks: InterCode-CTF, NYU CTF Bench, and Cybench. Our best model, Cyber-Zero-32B, establishes new state-of-the-art performance among open-weight models, matching the capabilities of proprietary systems like DeepSeek-V3-0324 and Claude-3.5-Sonnet while offering superior cost-effectiveness, and demonstrating that runtime-free trajectory synthesis can effectively democratize the development of state-of-the-art cybersecurity agents.
</details>

---

**PTFusion: LLM-driven Context-aware Knowledge Fusion for Web Penetration Testing** [[Paper](https://www.sciencedirect.com/science/article/pii/S1566253525007936)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Information%20Fusion-blue.svg" alt="Information Fusion">
  <img src="https://img.shields.io/badge/SCI-Q1-brightgreen.svg" alt="SCI-Q1">
  <img src="https://img.shields.io/badge/JCR-Q1-brightgreen.svg" alt="JCR-Q1">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-03

Tags: `WEB` | `LLM` | `Agent`
<details><summary>Abstract</summary>
This paper presents PTFusion, an LLM-driven web penetration testing framework that addresses inefficient task guidance and imprecise command execution challenges in web penetration testing. Employing a semi-decentralized multi-agent collaborative architecture, PTFusion maintains strategic coherence while enabling autonomous tactical execution, and uses the Model Context Protocol to more conveniently call different types of penetration testing tools. To effectively guide task execution, the PTFusion designs a context-aware knowledge fusion mechanism to plan tasks based on the dynamic knowledge graph and executed actions, and uses the preference-based chain-of-thought prompting to address the issue of redundant and difficult to align outputs from different types of penetration testing tools. Compared to methods like PentestGPT, PTFusion demonstrates significantl superior performance in both task completion effectiveness and stability. The context-aware knowledge fusion mechanism enables PTFusion to conduct more precise strategic planning and execute penetration testing commands with greater accuracy, ensuring reliable completion of web penetration testing tasks across various scenarios.
</details>

---

**What Makes a Good LLM Agent for Real-world Penetration Testing?** [[Paper](https://arxiv.org/pdf/2602.17622)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-02

Tags: `CTF` | `LLM`
<details><summary>Abstract</summary>
LLM-based agents show promise for automating penetration testing, yet reported performance varies widely across systems and benchmarks. We analyze 28 LLM-based penetration testing systems and evaluate five representative implementations across three benchmarks of increasing complexity. Our analysis reveals two distinct failure modes: Type A failures stem from capability gaps (missing tools, inadequate prompts) that engineering readily addresses, while Type B failures persist regardless of tooling due to planning and state management limitations. We show that Type B failures share a root cause that is largely invariant to the underlying LLM: agents lack real-time task difficulty estimation. As a result, agents misallocate effort, over-commit to low-value branches, and exhaust context before completing attack chains.
Based on this insight, we present Excalibur, a penetration testing agent that couples strong tooling with difficulty-aware planning. A Tool and Skill Layer eliminates Type A failures through typed interfaces and retrieval-augmented knowledge. A Task Difficulty Assessment (TDA) mechanism addresses Type B failures by estimating tractability through four measurable dimensions (horizon estimation, evidence confidence, context load, and historical success) and uses these estimates to guide exploration-exploitation decisions within an Evidence-Guided Attack Tree Search (EGATS) framework. Excalibur achieves up to 91% task completion on CTF benchmarks with frontier models (39 to 49% relative improvement over baselines) and compromises 4 of 5 hosts on the GOAD Active Directory environment versus 2 by prior systems. These results show that difficulty-aware planning yields consistent end-to-end gains across models and addresses a limitation that model scaling alone does not eliminate.
</details>

---

**LLMs as Hackers: Autonomous Linux Privilege Escalation Attacks** [[WebSite](https://hackingbuddy.ai/)] [[Paper](https://link.springer.com/article/10.1007/s10664-025-10758-3#Sec23)] [[Code](https://github.com/ipa-lab/hackingBuddyGPT)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/SCI-Q1-brightgreen.svg" alt="SCI-Q1">
  <img src="https://img.shields.io/badge/JCR-Q1-brightgreen.svg" alt="JCR-Q1">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-02

Tags: `Privilege Escalation` | `LLM`
<details><summary>Abstract</summary>
Penetration-testing is crucial for identifying and mitigating system vulnerabilities, with privilege-escalation being a critical subtask involving gaining elevated access to protected resources. The emergence of Large Language Models (LLMs) presents new avenues for automating these security practices by emulating human behavior. However, a comprehensive understanding of LLMs’ efficacy and limitations in performing autonomous Linux privilege-escalation attacks remains underexplored. To address this gap, we introduce hackingBuddyGPT, a fully automated LLM-driven prototype designed for evaluating autonomous Linux privilege-escalation. We curated a novel, publicly available Linux privilege-escalation benchmark comprising distinct, single-vulnerability virtual machines, enabling controlled and reproducible evaluation. Our empirical analysis assesses the quantitative success rates and qualitative operational behaviors of various LLMs—GPT-3.5-Turbo, GPT-4-Turbo, and Llama3—against baselines of human professional penetration-testers and traditional automated tools. We investigate the impact of context management strategies, different context sizes, and various high-level guidance mechanisms on LLM performance. Results show that GPT-4-Turbo demonstrates high efficacy, successfully exploiting 33–83% of vulnerabilities, a performance comparable to human penetration testers (75%). In contrast, local models like Llama3 exhibited limited success (0–33%), and GPT-3.5-Turbo achieved moderate rates (16–50%). High-level guidance significantly boosts LLM success rates, for instance when using GPT-4-Turbofrom 33% to 66% (without guidance) or from 66% to 83%, while state management through LLM-driven reflection doubled unaided GPT-4-Turbo success rates (from 33% to 66%). Qualitative analysis reveals both LLMs’ strengths and weaknesses in generating valid commands and highlights challenges in common-sense reasoning, error handling, and multi-step exploitation, particularly with temporal dependencies. Cost analysis indicates that GPT-4-Turbo can achieve human-comparable performance at competitive costs per exploited vulnerability, especially with optimized context management. Our work provides a baseline for evaluating LLM capabilities in autonomous privilege escalation, guiding future research toward more effective and reliable LLM-guided penetration-testing.
</details>

---

**AWE: Adaptive Agents for Dynamic Web Penetration Testing** [[Paper](https://www.ndss-symposium.org/ndss-paper/auto-draft-680/)] [[Code](https://github.com/stuxlabs/AWE)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/NDSS-2026-blue.svg" alt="NDSS">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-02

Tags: `WEB` | `LLM` | `Agent`
<details><summary>Abstract</summary>
Modern web applications are increasingly produced through AI-assisted development and rapid no-code deployment pipelines, widening the gap between accelerating software velocity and the limited adaptability of existing security tooling. Pattern-driven scanners fail to reason about novel contexts, while emerging LLM-based penetration testers rely on unconstrained exploration, yielding high cost, unstable behavior, and poor reproducibility.    
We introduce AWE, a memory-augmented multi-agent framework for autonomous web penetration testing that embeds structured, vulnerability-specific analysis pipelines within a lightweight LLM orchestration layer. Unlike general-purpose agents, AWE couples context aware payload mutations and generations with persistent memory and browser-backed verification to produce deterministic, exploitation-driven results.     
Evaluated on the 104-challenge XBOW benchmark, AWE achieves substantial gains on injection-class vulnerabilities - 87% XSS success (+30.5% over MAPTA) and 66.7% blind SQL injection success (+33.3%) - while being much faster, cheaper, and more token-efficient than MAPTA, despite using a midtier model (Claude Sonnet 4) versus MAPTA’s GPT-5. MAPTA retains higher overall coverage due to broader exploratory capabilities, underscoring the complementary strengths of specialized and general-purpose architectures. Our results demonstrate that architecture matters as much as model reasoning capabilities: integrating LLMs into principled, vulnerability-aware pipelines yields substantial gains in accuracy, efficiency, and determinism for injection-class exploits. The source code for AWE is available at: https://github.com/stuxlabs/AWE
</details>

---

**Multi-Agent Penetration Testing AI for the Web** [[Paper](https://arxiv.org/abs/2508.20816)] [[Code](https://github.com/arthurgervais/mapta)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-08

Tags: `WEB` | `LLM` | `Agent`
<details><summary>Abstract</summary>
AI-powered development platforms are making software creation accessible to a broader audience, but this democratization has triggered a scalability crisis in security auditing. With studies showing that up to 40% of AI-generated code contains vulnerabilities, the pace of development now vastly outstrips the capacity for thorough security assessment.
We present MAPTA, a multi-agent system for autonomous web application security assessment that combines large language model orchestration with tool-grounded execution and end-to-end exploit validation. On the 104-challenge XBOW benchmark, MAPTA achieves 76.9% overall success with perfect performance on SSRF and misconfiguration vulnerabilities, 83% success on broken authorization, and strong results on injection attacks including server-side template injection (85%) and SQL injection (83%). Cross-site scripting (57%) and blind SQL injection (0%) remain challenging. Our comprehensive cost analysis across all challenges totals 21.38withamediancostof0.073 for successful attempts versus 0.357forfailures.Successcorrelatesstronglywithresourceefficiency,enablingpracticalearly−stoppingthresholdsatapproximately40toolcallsor0.30 per challenge.
MAPTA's real-world findings are impactful given both the popularity of the respective scanned GitHub repositories (8K-70K stars) and MAPTA's low average operating cost of $3.67 per open-source assessment: MAPTA discovered critical vulnerabilities including RCEs, command injections, secret exposure, and arbitrary file write vulnerabilities. Findings are responsibly disclosed, 10 findings are under CVE review.
</details>

---

**Cloak, Honey, Trap: Proactive Defenses Against LLM Agents** [[Paper](https://www.usenix.org/conference/usenixsecurity25/presentation/ayzenshteyn)] [[Code](https://github.com/Daniel-Ayz/CHeaT.git)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/USENIX-2025-blue.svg" alt="USENIX">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-08

Tags: `Defence` | `LLM` | `Agent`
<details><summary>Abstract</summary>
Recent advances in large language models (LLMs) have enabled autonomous penetration testing tools capable of assessing network security by compromising hosts. However, the same artificial intelligence (AI) capabilities can empower attackers to automate attacks at scale.

This paper presents a cost-effective defense framework using deception and counterattacks to exploit LLM weaknesses—such as biases, memory limitations, and tokenization issues—to disrupt, detect, or neutralize malicious agents. For example, we are able to cloak assets with misdirection, lure, and expose AI adversaries by using LLM-specific honey-tokens and trap agents using loops and other techniques. We also demonstrate several novel exploits such as inducing an agent to execute untrusted code, potentially giving defenders reverse access to the attacker's infrastructure. Overall, our approach introduces 6 strategies and 15 techniques, most of which do not rely on prompt injection.

With black box assumptions, we are able to protect a variety of 11 different Capture the Flag (CTF) machines with a 100% success rate. To help the community, we release CHeaT, an open-source tool that automatically inserts traps, cloaks, and honey-tokens seamlessly into network assets. This work establishes a scalable proactive defense paradigm leveraging LLM vulnerabilities to counter AI-driven threats.
</details>

---

**EnIGMA: Interactive Tools Substantially Assist LM Agents in Finding Security Vulnerabilities** [[WebSite](https://enigma-agent.com/)] [[Paper](https://icml.cc/virtual/2025/poster/45428)] [[Code](https://github.com/princeton-nlp/SWE-agent)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICML-2025-blue.svg" alt="ICML">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-07

Tags: `Exploit` | `LLM` | `Agent`
<details><summary>Abstract</summary>
Although language model (LM) agents have demonstrated increased performance in multiple domains, including coding and web-browsing, their success in cybersecurity has been limited. We present EnIGMA, an LM agent for autonomously solving Capture The Flag (CTF) challenges. We introduce new tools and interfaces to improve the agent's ability to find and exploit security vulnerabilities, focusing on interactive terminal programs. These novel Interactive Agent Tools enable LM agents, for the first time, to run interactive utilities, such as a debugger and a server connection tool, which are essential for solving these challenges.Empirical analysis on 390 CTF challenges across four benchmarks demonstrate that these new tools and interfaces substantially improve our agent's performance, achieving state-of-the-art results on NYU CTF, Intercode-CTF, and CyBench. Finally, we analyze data leakage, developing new methods to quantify it and identifying a new phenomenon we term soliloquizing, where the model self-generates hallucinated observations without interacting with the environment.
</details>

---

**Perry: A High-level Framework for Accelerating Cyber Deception Experimentation** [[Paper](https://arxiv.org/abs/2506.20770)] [[Code](https://github.com/bsinger98/Perry)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-06

Tags: `Cyber Deception` | `Agent`
<details><summary>Abstract</summary>
Cyber deception aims to distract, delay, and detect network attackers with fake assets such as honeypots, decoy credentials, or decoy files. However, today, it is difficult for operators to experiment, explore, and evaluate deception approaches. Existing tools and platforms have non-portable and complex implementations that are difficult to modify and extend. We address this pain point by introducing Perry, a high-level framework that accelerates the design and exploration of deception what-if scenarios. Perry has two components: a high-level abstraction layer for security operators to specify attackers and deception strategies, and an experimentation module to run these attackers and defenders in realistic emulated networks. To translate these high-level specifications we design four key modules for Perry: 1) an action planner that translates high-level actions into low-level implementations, 2) an observability module to translate low-level telemetry into high-level observations, 3) an environment state service that enables environment agnostic strategies, and 4) an attack graph service to reason about how attackers could explore an environment. We illustrate that Perry's abstractions reduce the implementation effort of exploring a wide variety of deception defenses, attackers, and environments. We demonstrate the value of Perry by emulating 55 unique deception what-if scenarios and illustrate how these experiments enable operators to shed light on subtle tradeoffs.
</details>

---

**xOffense: An AI-driven Autonomous Penetration Testing Framework with Offensive Knowledge-enhanced LLMs and Multi-Agent Systems** [[Paper](https://arxiv.org/abs/2509.13021)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Offensive Security`
<details><summary>Abstract</summary>

</details>

---

**VulnBot: Autonomous Penetration Testing for a Multi-Agent Collaborative Framework** [[Paper](https://arxiv.org/abs/2501.13411)] [[Code](https://github.com/KHenryAegis/VulnBot)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**RefPentester: A Knowledge-Informed Self-Reflective Penetration Testing Framework Based on Large Language Models** [[Paper](https://arxiv.org/abs/2505.07089)] [[Code](https://github.com/ipa-lab/hackingBuddyGPT)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**RedTeamLLM: An Agentic AI Framework For Offensive Security** [[Paper](https://arxiv.org/abs/2512.14233)] [[Code](https://github.com/lre-security-systems-team/redteamllm)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Offensive Security`
<details><summary>Abstract</summary>

</details>

---

**RapidPen: Fully Automated IP-to-Shell Penetration Testing with LLM-based Agents** [[Paper](https://arxiv.org/abs/2502.16730)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**PentestAgent: Incorporating LLM Agents to Automated Penetration Testing** [[Paper](https://dl.acm.org/doi/full/10.1145/3708821.3733882)] [[Code](https://github.com/GH05TCREW/PentestAgent)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/AsiaCCS-2025-blue.svg" alt="AsiaCCS">
  <img src="https://img.shields.io/badge/CCF-C-yellow.svg" alt="CCF-C">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**Pentest-R1: Towards Autonomous Penetration Testing Reasoning Optimized via Two-Stage Reinforcement Learning** [[Paper](https://arxiv.org/abs/2508.07382)] [[Code](https://github.com/KHenryAegis/Pentest-R1)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Reinforcement Learning`
<details><summary>Abstract</summary>

</details>

---

**On the Surprising Efficacy of LLMs for Penetration-Testing** [[Paper](https://arxiv.org/abs/2507.00829)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**Measuring and Augmenting Large Language Models for Solving Capture-the-Flag Challenges** [[Paper](https://dl.acm.org/doi/abs/10.1145/3719027.3744855)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ACM%20CCS-2025-blue.svg" alt="ACM CCS">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `CTF` | `Benchmark`
<details><summary>Abstract</summary>

</details>

---

**Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks** [[Paper](https://arxiv.org/abs/2501.16466)] [[Code](https://github.com/bsinger98/Incalmo)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Red Teaming`
<details><summary>Abstract</summary>

</details>

---

**From Capabilities to Performance: Evaluating Key Functional Properties of LLM Architectures in Penetration Testing** [[Paper](https://aclanthology.org/2025.emnlp-main.802/)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/EMNLP-2025-blue.svg" alt="EMNLP">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**Can LLMs Hack Enterprise Networks? Autonomous Assumed Breach Penetration-Testing Active Directory Networks** [[Paper](https://dl.acm.org/doi/abs/10.1145/3766895)] [[Code](https://github.com/andreashappe/cochise)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/TOSEM-2025-blue.svg" alt="TOSEM">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Penetration Testing` | `Active Directory`
<details><summary>Abstract</summary>

</details>

---

**AutoPentest: Enhancing Vulnerability Management With Autonomous LLM Agents** [[Paper](https://arxiv.org/abs/2505.10321)] [[Code](https://github.com/JuliusHenke/autopentest)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Vulnerability Management`
<details><summary>Abstract</summary>

</details>

---

**Automated Penetration Testing with LLM Agents and Classical Planning** [[Paper](https://arxiv.org/abs/2512.11143)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Planning`
<details><summary>Abstract</summary>

</details>

---

**ARACNE: An LLM-Based Autonomous Shell Pentesting Agent** [[Paper](https://arxiv.org/abs/2502.18528)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Shell`
<details><summary>Abstract</summary>

</details>

---

**A Unified Modeling Framework for Automated Penetration Testing** [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167404825004766)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Computers%20%26%20Security-2025-blue.svg" alt="Computers &amp; Security">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `Automated Penetration Testing` | `Modeling`
<details><summary>Abstract</summary>

</details>

---

**PentestGPT: Evaluating and Harnessing Large Language Models for Automated Penetration Testing** [[Paper](https://www.usenix.org/conference/usenixsecurity24/presentation/deng)] [[Code](https://github.com/GreyDGL/PentestGPT)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/USENIX%20Security-2024-blue.svg" alt="USENIX Security">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**PENTEST-AI: An LLM-Powered Multi-Agents Framework for Penetration Testing Automation Leveraging MITRE ATT&CK** [[Paper](https://ieeexplore.ieee.org/abstract/document/10679480)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/CSR-2024-blue.svg" alt="CSR">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `LLM` | `Agent` | `MITRE ATT&CK`
<details><summary>Abstract</summary>

</details>

---

**BreachSeek: A Multi-Agent Automated Penetration Tester** [[Paper](https://arxiv.org/abs/2409.03789)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**AutoAttacker: A Large Language Model Guided System to Implement Automatic Cyber-attacks** [[Paper](https://arxiv.org/abs/2403.01038)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `LLM` | `Agent` | `Cyber Attack`
<details><summary>Abstract</summary>

</details>

---

**An Empirical Evaluation of LLMs for Solving Offensive Security Challenges** [[Paper](https://arxiv.org/abs/2402.11814)] [[Code](https://github.com/NickNameInvalid/LLM_CTF)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `LLM` | `CTF` | `Offensive Security`
<details><summary>Abstract</summary>

</details>

---

**Getting pwn’d by AI: Penetration Testing with Large Language Models** [[WebSite](https://hackingbuddy.ai/)] [[Paper](https://dl.acm.org/doi/10.1145/3611643.3613083)] [[Code](https://github.com/ipa-lab/hackingBuddyGPT)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ESEC%2FFSE-2023-blue.svg" alt="ESEC/FSE">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-07

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
The field of software security testing, more specifically penetration testing, requires high levels of expertise and involves many manual testing and analysis steps. This paper explores the potential use of large-language models, such as GPT3.5, to augment penetration testers with AI sparring partners. We explore two distinct use cases: high-level task planning for security testing assignments and low-level vulnerability hunting within a vulnerable virtual machine. For the latter, we implemented a closed-feedback loop between LLM-generated low-level actions with a vulnerable virtual machine (connected through SSH) and allowed the LLM to analyze the machine state for vulnerabilities and suggest concrete attack vectors which were automatically executed within the virtual machine. We discuss promising initial results, detail avenues for improvement, and close deliberating on the ethics of AI sparring partners.
</details>

---

**Using Large Language Models for Cybersecurity Capture-The-Flag Challenges and Certification Questions** [[Paper](https://arxiv.org/abs/2308.10443)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `LLM` | `CTF` | `Certification`
<details><summary>Abstract</summary>

</details>

---

**Language Agents as Hackers: Evaluating Cybersecurity Skills with Capture the Flag** [[Paper](https://arxiv.org/abs/2308.10443)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/MASEC%40NeurIPS-2023-blue.svg" alt="MASEC@NeurIPS">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `LLM` | `Agent` | `CTF`
<details><summary>Abstract</summary>

</details>

---

## Benchmarks and Cyber Ranges

**ExploitGym: Can AI Agents Turn Security Vulnerabilities into Real Attacks?** [[Paper](https://arxiv.org/abs/2605.11086)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-05

Tags: `Exploit` | `LLM`
<details><summary>Abstract</summary>
AI agents are rapidly gaining capabilities that could significantly reshape cybersecurity, making rigorous evaluation urgent. A critical capability is exploitation: turning a vulnerability, which is not yet an attack, into a concrete security impact, such as unauthorized file access or code execution. Exploitation is a particularly challenging task because it requires low-level program reasoning (e.g., about memory layout), runtime adaptation, and sustained progress over long horizons. Meanwhile, it is inherently dual-use, supporting defensive workflows while lowering the barrier for offense. Despite its importance and diagnostic value, exploitation remains under-evaluated. To address this gap, we introduce ExploitGym, a large-scale, diverse, realistic benchmark on the exploitation capabilities of AI agents. Given a program input that triggers a vulnerability, ExploitGym tasks agents with progressively extending it into a working exploit. The benchmark comprises 898 instances sourced from real-world vulnerabilities across three domains, including userspace programs, Google's V8 JavaScript engine, and the Linux kernel. We vary the security protections applied to each instance, isolating their impact on agent performance. All configurations are packaged in reproducible containerized environments. Our evaluation shows that while exploitation remains challenging, frontier models can successfully exploit a non-trivial fraction of vulnerabilities. For example, the strongest configurations are Anthropic's latest model Claude Mythos Preview and OpenAI's GPT-5.5, which produce working exploits for 157 and 120 instances, respectively. Notably, even with widely used defenses enabled, models retain non-trivial success rates. These results establish ExploitGym as an effective testbed for exploitation and highlight the growing cybersecurity risks posed by increasingly capable AI agents.
</details>

---

**RedTeamCUA: Towards Realistic Adversarial Testing of Computer-Use Agents in Hybrid Web-OS Environments** [[WebSite](https://osu-nlp-group.github.io/RedTeamCUA/)] [[Paper](https://openreview.net/forum?id=yWwrgcBoK3)] [[Code](https://github.com/OSU-NLP-Group/RedTeamCUA.git)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICLR-2026-blue.svg" alt="ICLR">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-04

Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
Computer-use agents (CUAs) promise to automate complex tasks across operating systems (OS) and the web, but remain vulnerable to indirect prompt injection, where attackers embed malicious content into the environment to hijack agent behavior. Current evaluations of this threat either lack support for adversarial testing in realistic but controlled environments or ignore hybrid web-OS attack scenarios involving both interfaces. To address this, we propose RedTeamCUA, an adversarial testing framework featuring a novel hybrid sandbox that integrates a VM-based OS environment with Docker-based web platforms. Our sandbox supports key features tailored for red teaming, such as flexible adversarial scenario configuration, and a setting that decouples adversarial evaluation from navigational limitations of CUAs by initializing tests directly at the point of an adversarial injection. Using RedTeamCUA, we develop RTC-Bench, a comprehensive benchmark with 864 examples that investigate realistic, hybrid web-OS attack scenarios and fundamental security vulnerabilities. Benchmarking current frontier CUAs identifies significant vulnerabilities: Claude 3.7 Sonnet | CUA demonstrates an Attack Success Rate (ASR) of 42.9%, while Operator, the most secure CUA evaluated, still exhibits an ASR of 7.6%. Notably, CUAs often attempt to execute adversarial tasks with an Attempt Rate as high as 92.5%, although failing to complete them due to capability limitations. Nevertheless, we observe concerning ASRs of up to 50% in realistic end-to-end settings, indicating that CUA threats can already result in tangible risks to users and computer systems. Overall, RedTeamCUA provides an essential framework for advancing realistic, controlled, and systematic analysis of CUA vulnerabilities, highlighting the urgent need for robust defenses to indirect prompt injection prior to real-world deployment.
</details>

---

**PACEbench: A Framework for Evaluating Practical AI Cyber-Exploitation Capabilities** [[WebSite](https://pacebench.github.io/)] [[Paper](https://openreview.net/pdf?id=kGEuZXaXU6)] [[Code](https://github.com/RyuKosei/PACEbench)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICLR-2026-blue.svg" alt="ICLR">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-04

Tags: `ATTACK&DEFENCE` | `LLM`
<details><summary>Abstract</summary>
The increasing autonomy of Large Language Models (LLMs) necessitates a rigorous evaluation of their potential to aid in cyber offense. Existing benchmarks often lack real-world complexity and are thus unable to accurately assess LLMs' cybersecurity capabilities. To address this gap, we introduce PACEbench, a practical AI cyber-exploitation benchmark built on the principles of realistic vulnerability difficulty, environmental complexity, and cyber defenses. Specifically, PACEbench comprises four scenarios spanning single, blended, chained, and defense vulnerability exploitations. To handle these complex challenges, we propose PACEagent, a novel agent that emulates human penetration testers by supporting multi-phase reconnaissance, analysis, and exploitation. Extensive experiments with seven frontier LLMs demonstrate that current models struggle with complex cyber scenarios, and none can bypass defenses. These findings suggest that current models do not yet pose a generalized cyber offense threat. Nonetheless, our work provides a robust benchmark to guide the trustworthy development of future models.
</details>

---

**HackWorld: Evaluating Computer-Use Agents on Exploiting Web Application Vulnerabilities** [[Paper](https://openreview.net/pdf?id=nLfZPoJbO7)] [[Code](https://github.com/GUI-Agent/HackWorld)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICLR-2026-blue.svg" alt="ICLR">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-04

Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
Web applications are prime targets for cyberattacks due to their role as entry points to vital services and sensitive data repositories. Traditional penetration testing is expensive and requires specialized expertise, creating scalability challenges for securing the expanding web ecosystem. While language model agents have shown promise in certain cybersecurity tasks, modern web applications require visual understanding of complex user interfaces, dynamic content rendering, and multi-step interactive workflows that only computer-use agents (CUAs) can handle. Despite CUAs' demonstrated capabilities in web browsing and visual task automation, their potential to discover and exploit web application vulnerabilities through graphical interfaces remains unknown. We introduce HackWorld, the first evaluation framework for systematically assessing CUAs' capabilities in exploiting web application vulnerabilities through visual interaction. Unlike existing benchmarks using sanitized environments, HackWorld exposes CUAs to 36 curated applications spanning 11 frameworks and 7 languages, containing realistic vulnerabilities including injection flaws, authentication bypasses, and unsafe input handling. Our framework directly evaluates CUAs' ability to discover and exploit these vulnerabilities using Capture-the-Flag (CTF) methodology while navigating complex web interfaces. Evaluation of state-of-the-art CUAs reveals exploitation rates below 12%, struggling to plan multi-step attacks and use security tools effectively. Our results expose CUAs' limited cybersecurity skills when operating on vulnerable web applications, opening future research directions on developing security-aware CUAs for vulnerability detection and exploitation.
</details>

---

**CyberGym: Evaluating AI Agents' Real-World Cybersecurity Capabilities at Scale** [[WebSite](https://www.cybergym.io/)] [[Paper](https://openreview.net/pdf?id=2YvbLQEdYt)] [[Code](https://github.com/sunblaze-ucb/cybergym.git)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICLR-2026-blue.svg" alt="ICLR">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-04

Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
AI agents have significant potential to reshape cybersecurity, making a thorough assessment of their capabilities critical. However, existing evaluations fall short, because they are based on small-scale benchmarks and only measure static outcomes, failing to capture the full, dynamic range of real-world security challenges. To address these limitations, we introduce CyberGym, a large-scale benchmark featuring 1,507 real-world vulnerabilities across 188 software projects. Adjustable to different vulnerability analysis settings, CyberGym primarily tasks agents with generating a proof-of-concept test that reproduces a vulnerability, given only its text description and the corresponding codebase. Our extensive evaluation highlights that CyberGym effectively differentiates agents' and models' cybersecurity capabilities. Even the top-performing combinations only achieve a ~20% success rate, demonstrating the overall difficulty of CyberGym. Beyond static benchmarking, we show that CyberGym leads to the discovery of 34 zero-day vulnerabilities and 18 historically incomplete patches. These results underscore that CyberGym is not only a robust benchmark for measuring AI's progress in cybersecurity but also a platform for creating direct, real-world security impact.
</details>

---

**Comparing AI Agents to Cybersecurity Professionals in Real-World Penetration Testing** [[Paper](https://openreview.net/pdf?id=Us00XndbVi)] [[Code](https://github.com/Stanford-Trinity/ARTEMIS)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICML-2025-blue.svg" alt="ICML">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026-04

Tags: `WEB` | `LLM`
<details><summary>Abstract</summary>
We present the first comprehensive evaluation of AI agents against human cybersecurity professionals in a live enterprise environment. We evaluate ten cybersecurity professionals alongside six existing AI agents and ARTEMIS, our new agent scaffold, on a large university network consisting of 
8,000 hosts across 12 subnets. ARTEMIS is a multi-agent framework featuring dynamic prompt generation, arbitrary sub-agents, and automatic vulnerability triaging. In our comparative study, ARTEMIS placed second overall, discovering 9 valid vulnerabilities with an 82% valid submission rate and outperforming 9 of 10 human participants. While existing scaffolds such as Codex and CyAgent underperformed relative to most human participants, ARTEMIS demonstrated technical sophistication and submission quality comparable to the strongest participants. AI agents offer advantages in systematic enumeration, parallel exploitation, and cost---certain ARTEMIS variants cost 
60/hour for professional penetration testers. We also identify key capability gaps: AI agents exhibit higher false-positive rates and struggle with GUI-based tasks.
</details>

---

**Shell or Nothing: Real-World Benchmarks and Memory-Activated Agents for Automated Penetration Testing** [[Paper](https://arxiv.org/abs/2509.09207)] [[Code](https://zenodo.org/records/17479793)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-09

Tags: `Penetration` | `LLM` | `Agent`
<details><summary>Abstract</summary>
Penetration testing is critical for identifying and mitigating security vulnerabilities, yet traditional approaches remain expensive, time-consuming, and dependent on expert human labor. Recent work has explored AI-driven pentesting agents, but their evaluation relies on oversimplified capture-the-flag (CTF) settings that embed prior knowledge and reduce complexity, leading to performance estimates far from real-world practice. We close this gap by introducing the first real-world, agent-oriented pentesting benchmark, TermiBench, which shifts the goal from “flag finding” to achieving full system control. The benchmark spans 510 hosts across 25 services and 30 CVEs, with realistic environments that require autonomous reconnaissance, discrimination between benign and exploitable services, and robust exploit execution. Using this benchmark, we find that existing systems can hardly obtain system shells under realistic conditions.

To address these challenges, we propose TermiAgent, a multi-agent penetration testing framework. TermiAgent mitigates long-context forgetting with a Located Memory Activation mechanism and builds a reliable exploit arsenal via structured code understanding rather than naïve retrieval. In evaluations, our work outperforms state-of-the-art agents—exhi-biting stronger penetration testing capability, reducing execution time and financial cost, and demonstrating practicality even on laptop-scale deployments. Our work delivers both the first open-source benchmark for real-world autonomous pentesting and a novel agent framework that establishes a milestone for AI-driven penetration testing.
</details>

---

**CVE-Bench: A Benchmark for AI Agents’ Ability to Exploit Real-World Web Application Vulnerabilities** [[WebSite](https://cvebench.com/)] [[Paper](https://icml.cc/virtual/2025/poster/46522)] [[Code](https://github.com/uiuc-kang-lab/cve-bench.git)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICML-2025-blue.svg" alt="ICML">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-07

Tags: `WEB` | `Exploit` | `LLM`
<details><summary>Abstract</summary>
Large language model (LLM) agents are increasingly capable of autonomously conducting cyberattacks, posing significant threats to existing applications. This growing risk highlights the urgent need for a real-world benchmark to evaluate the ability of LLM agents to exploit web application vulnerabilities. However, existing benchmarks fall short as they are limited to abstracted Capture-the-Flag competitions or lack comprehensive coverage. Building a benchmark for real-world vulnerabilities involves both specialized exper-tise to reproduce exploits and a systematic approach to evaluating unpredictable attacks. To address this challenge, we introduce CVE-Bench, a real-world cybersecurity benchmark based on critical-severity Common Vulnerabilities and Exposures. In CVE-Bench, we design a sandbox framework that enables LLM agents to exploit vulnerable web applications in scenarios that mimic real-world conditions, while also providing effective evaluation of their exploits. Our experiments show that the state-of-the-art agent framework can exploit up to 13% of the vulnerabilities.
</details>

---

**Towards Automated Penetration Testing: Introducing LLM Benchmark, Analysis, and Improvements** [[Paper](https://dl.acm.org/doi/full/10.1145/3708319.3733804)] [[Code](https://github.com/anonyippi/PentestBenchmarkPaper)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/UMAP-2025-blue.svg" alt="UMAP">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025

Tags: `LLM` | `Benchmark` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**PentestEval: Benchmarking LLM-based Penetration Testing with Modular and Stage-Level Design** [[Paper](https://arxiv.org/abs/2512.14233)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025

Tags: `LLM` | `Benchmark` | `Penetration Testing`
<details><summary>Abstract</summary>

</details>

---

**Got Root? A Linux Priv-Esc Benchmark** [[Paper](https://arxiv.org/abs/2405.02106)] [[Code](https://github.com/ipa-lab/benchmark-privesc-linux)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2024-05

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
Linux systems are integral to the infrastructure of modern computing environments, necessitating robust security measures to prevent unauthorized access. Privilege escalation attacks represent a significant threat, typically allowing attackers to elevate their privileges from an initial low-privilege account to the all-powerful root account. A benchmark set of vulnerable systems is of high importance to evaluate the effectiveness of privilege-escalation techniques performed by both humans and automated tooling. Analyzing their behavior allows defenders to better fortify their entrusted Linux systems and thus protect their infrastructure from potentially devastating attacks. To address this gap, we developed a comprehensive benchmark for Linux privilege escalation. It provides a standardized platform to evaluate and compare the performance of human and synthetic actors, e.g., hacking scripts or automated tooling.
</details>

---

**NYU CTF Bench: A Scalable Open-Source Benchmark Dataset for Evaluating LLMs in Offensive Security** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/69d97a6493fbf016fff0a751f253ad18-Abstract-Datasets_and_Benchmarks_Track.html)] [[Code](https://github.com/NYU-LLM-CTF/NYUCTFBench)] [[Dataset](https://github.com/NYU-LLM-CTF/NYUCTFBench)] [[Project](https://github.com/NYU-LLM-CTF/LLMctfautomation)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/NeurIPS-2024-blue.svg" alt="NeurIPS">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Dataset-lightblue.svg" alt="Type-Dataset">
</div>
Published: 2024

Tags: `LLM` | `CTF` | `Benchmark` | `Dataset`
<details><summary>Abstract</summary>

</details>

---

**HackSynth: LLM Agent and Evaluation Framework for Autonomous Penetration Testing** [[Paper](https://arxiv.org/abs/2412.01778)] [[Code](https://github.com/aielte-research/HackSynth)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2024

Tags: `LLM` | `Agent` | `Benchmark`
<details><summary>Abstract</summary>

</details>

---

**Cybench: A Framework for Evaluating Cybersecurity Capabilities and Risks of Language Models** [[Paper](https://arxiv.org/abs/2408.08926)] [[Code](https://cybench.github.io/)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2024

Tags: `LLM` | `Benchmark` | `Cybersecurity`
<details><summary>Abstract</summary>

</details>

---

## Tools and Code

**CAI: An Open, Bug Bounty-Ready Cybersecurity AI** [[Paper](https://arxiv.org/abs/2504.06017)] [[Code](https://github.com/aliasrobotics/CAI)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Tool-green.svg" alt="Type-Tool">
</div>
Published: 2025

Tags: `LLM` | `Agent` | `Bug Bounty`
<details><summary>Abstract</summary>

</details>

---
