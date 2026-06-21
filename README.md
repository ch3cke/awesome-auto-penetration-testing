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

**A Survey of Agentic AI and Cybersecurity: Challenges, Opportunities and Use-case Prototypes** [[Paper](https://arxiv.org/pdf/2601.05293)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2026-01

Tags: `LLM` | `Agent` | `Survey`
<details><summary>Abstract</summary>
Agentic AI marks an important transition from single-step generative models to systems capable of reasoning, planning, acting, and adapting over long-lasting tasks. By integrating memory, tool use, and iterative decision cycles, these systems enable continuous, autonomous workflows in real-world environments. This survey examines the implications of agentic AI for cybersecurity. On the defensive side, agentic capabilities enable continuous monitoring, autonomous incident response, adaptive threat hunting, and fraud detection at scale. Conversely, the same properties amplify adversarial power by accelerating reconnaissance, exploitation, coordination, and social-engineering attacks. These dual-use dynamics expose fundamental gaps in existing governance, assurance, and accountability mechanisms, which were largely designed for non-autonomous and short-lived AI systems. To address these challenges, we survey emerging threat models, security frameworks, and evaluation pipelines tailored to agentic systems, and analyze systemic risks including agent collusion, cascading failures, oversight evasion, and memory poisoning. Finally, we present three representative use-case implementations that illustrate how agentic AI behaves in practical cybersecurity workflows, and how design choices shape reliability, safety, and operational effectiveness.
</details>

---

**The Evolution of Agentic AI in Cybersecurity: From Single LLM Reasoners to Multi-Agent Systems and Autonomous Pipelines** [[Paper](https://arxiv.org/pdf/2512.06659)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-12

Tags: `LLM` | `Agent` | `Multi-Agent` | `Survey`
<details><summary>Abstract</summary>
Cybersecurity has become one of the earliest adopters of agentic AI, as security operations centers increasingly rely on multi-step reasoning, tool-driven analysis, and rapid decision-making under pressure. While individual large language models can summarize alerts or interpret unstructured reports, they fall short in real SOC environments that require grounded data access, reproducibility, and accountable workflows. In response, the field has seen a rapid architectural evolution from single-model helpers toward tool-augmented agents, distributed multi-agent systems, schema-bound tool ecosystems, and early explorations of semi-autonomous investigative pipelines. This survey presents a five-generation taxonomy of agentic AI in cybersecurity. It traces how capabilities and risks change as systems advance from text-only LLM reasoners to multi-agent collaboration frameworks and constrained-autonomy pipelines. We compare these generations across core dimensions - reasoning depth, tool use, memory, reproducibility, and safety. In addition, we also synthesize emerging benchmarks used to evaluate cyber-oriented agents. Finally, we outline the unresolved challenges that accompany this evolution, such as response validation, tool-use correctness, multi-agent coordination, long-horizon reasoning, and safeguards for high-impact actions. Collectively, this work provides a structured perspective on how agentic AI is taking shape within cybersecurity and what is required to ensure its safe and reliable deployment.
</details>

---

**On the Potential of LLMs for Offensive Security: Benchmarks vs. Operational Reality** [[Paper](https://ieeexplore.ieee.org/abstract/document/11418021)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ACSAC%20Workshops-2025-blue.svg" alt="ACSAC Workshops">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-12

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
Large Language Models (LLMs), through their strong capabilities in code generation, reasoning, and tool use, have demonstrated promising results in security tasks involving vulnerability discovery and exploitation. However, evaluating their offensive potential in automating penetration testing—a more complex and multi-stage process—remains a critical research challenge. While existing evaluation frameworks effectively demonstrate LLM capabilities in isolated or simplified scenarios, they often do not extend toward the complexity of interconnected attack chains characteristic of real-world adversarial operations. In this analytical study, we examine the challenge of assessing the feasibility of LLM-powered automation across the full adversarial pipeline within realistic environments. We contribute an analysis of current benchmarks and associated environments, and highlight opportunities for methodological enhancements that would strengthen alignment between academic evaluations and operational realities.
</details>

---

**LLM-Driven Automated Penetration Testing: Architectures, Benchmarks, and Safety Considerations** [[Paper](https://ieeexplore.ieee.org/document/11346427)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICSSS-2025-blue.svg" alt="ICSSS">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-12

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
In recent years, there has been a growing trend toward using large language models (LLMs) to automate penetration testing tasks, including reconnaissance, vulnerability discovery, exploit identification, and reporting. Previous works, including PentestGPT, Curriculum PT, RapidPen, White Rabbit Neo- PentestGPT, and HackSynth, have shown that LLM guided workflows can be superior to naive prompting and traditional scripting-based approaches on both capture the flag (CTF) challenges and realistic lab environments, and have attracted significant community interest and public benchmarking. Nevertheless, the complete automation of penetration testing remains an unsolved problem: current tools continue to fail to address issues related to managing context, orchestrating tools, handling environmental variations, and enforcing safety constraints. In this paper, we introduce a unified LLM-driven automated Penetration Testing Framework that divides the workflow of penetration testing into formally defined tasks, states, and actions, utilizing LLM-based agents to develop, execute, and modify multi-step attack chains across multiple layers of networks, web, cloud, and application environments. We detail how to integrate external tools (scanners, exploit frameworks, and knowledge bases) into the framework, design a memory and reasoning layer to prevent the loss of context, and define safety and governance controls to limit the misuse of the system. We conduct experiments using synthetic labs, standardized CTFstyle benchmarks, and real-world-inspired scenarios, and compare our results against those obtained from human testers, scripted pipelines, and previous LLM-based systems. Our results indicate significant improvements in task completion, coverage, and time-to-compromise, while also identifying failure modes and informing future research directions. The purpose of this paper is to provide a reference architecture and experimental guide for next-generation, LLM-driven penetration testing
</details>

---

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

**SoK: Potentials and Challenges of Large Language Models for Reverse Engineering** [[Paper](https://arxiv.org/pdf/2509.21821)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-09

Tags: `LLM` | `Reverse Engineering` | `SoK`
<details><summary>Abstract</summary>
Reverse Engineering (RE) is central to software security, enabling tasks such as vulnerability discovery and malware analysis, but it remains labor-intensive and requires substantial expertise. Earlier advances in deep learning start to automate parts of RE, particularly for malware detection and vulnerability classification. More recently, a rapidly growing body of work has applied Large Language Models (LLMs) to similar purposes. Their role compared to prior machine learning remains unclear, since some efforts simply adapt existing pipelines with minimal change while others seek to exploit broader reasoning and generative abilities. These differences, combined with varied problem definitions, methods, and evaluation practices, limit comparability, reproducibility, and cumulative progress. This paper systematizes the field by reviewing 44 research papers, including peer-reviewed publications and preprints, and 18 additional open-source projects that apply LLMs in RE. We propose a taxonomy that organizes existing work by objective, target, method, evaluation strategy, and data scale. Our analysis identifies strengths and limitations, highlights reproducibility and evaluation gaps, and examines emerging risks. We conclude with open challenges and future research directions that aim to guide more coherent and security-relevant applications of LLMs in RE.
</details>

---

**Benchmarking Practices in LLM-driven Offensive Security: Testbeds, Metrics, and Experiment Design** [[Paper](https://arxiv.org/pdf/2504.10112)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-04

Tags: `LLM` | `Offensive Security` | `Benchmark`
<details><summary>Abstract</summary>
Large Language Models (LLMs) have emerged as a powerful approach for driving offensive penetration-testing tooling. Due to the opaque nature of LLMs, empirical methods are typically used to analyze their efficacy. The quality of this analysis is highly dependent on the chosen testbed, captured metrics and analysis methods employed. This paper analyzes the methodology and benchmarking practices used for evaluating Large Language Model (LLM)-driven attacks, focusing on offensive uses of LLMs in cybersecurity. We review 19 research papers detailing 18 prototypes and their respective testbeds. We detail our findings and provide actionable recommendations for future research, emphasizing the importance of extending existing testbeds, creating baselines, and including comprehensive metrics and qualitative analysis. We also note the distinction between security research and practice, suggesting that CTF-based challenges may not fully represent real-world penetration testing scenarios.
</details>

---

**Autonomous Pentesting Using Reinforcement Learning: A Systematic Literature Review** [[Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5208526)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/SSRN-2025-blue.svg" alt="SSRN">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-04

Tags: `RL` | `Survey` | `Autonomous Pentesting`
<details><summary>Abstract</summary>
Emerging threats against systems resulting in cyberattacks are making a significant impact. Companies face huge challenges in creating solutions due to the lack of experts, resources and time. This problem creates the opportunity to research and develop innovative approaches to enhance security, particularly through the use of Autonomous Penetration Testing (APT). APT leverages Artificial Intelligence (AI) to continuously assess vulnerabilities and integrate seamlessly into the Software Development Life Cycle (SDLC), reducing the need for extensive human intervention. This research offers an updated comprehensive literature review focused on APT, aiming to identify key challenges, ongoing developments, and future directions in this field. By analysing recent articles, the review highlights that simulators such as CyberbattleSim, Cyborg, and NASim are among the most frequently used. It also finds that advanced architectures like DUSC-DQN and NHSC-PPO surpass traditional models in performance. The study concludes by recommending further research to evaluate these new simulators and algorithms in real-world scenarios to better understand their effectiveness.
</details>

---

**Red Teaming with Artificial Intelligence-Driven Cyberattacks: A Scoping Review** [[Paper](https://arxiv.org/pdf/2503.19626)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2025-03

Tags: `LLM` | `Red Teaming` | `Survey`
<details><summary>Abstract</summary>
The progress of artificial intelligence (AI) has made sophisticated methods available for cyberattacks and red team activities. These AI attacks can automate the process of penetrating a target or collecting sensitive data. The new methods can also accelerate the execution of the attacks. This review article examines the use of AI technologies in cybersecurity attacks. It also tries to describe typical targets for such attacks. We employed a scoping review methodology to analyze articles and identify AI methods, targets, and models that red teams can utilize to simulate cybercrime. From the 470 records screened, 11 were included in the review. Various cyberattack methods were identified, targeting sensitive data, systems, social media profiles, passwords, and URLs. The application of AI in cybercrime to develop versatile attack models presents an increasing threat. Furthermore, AI-based techniques in red team use can provide new ways to address these issues.
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

**An Empirical Evaluation of LLMs for Solving Offensive Security Challenges** [[Paper](https://arxiv.org/abs/2402.11814)] [[Code](https://github.com/NickNameInvalid/LLM_CTF)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2024-02

Tags: `LLM` | `CTF` | `Offensive Security`
<details><summary>Abstract</summary>
Capture The Flag (CTF) challenges are puzzles related to computer security scenarios. With the advent of large language models (LLMs), more and more CTF participants are using LLMs to understand and solve the challenges. However, so far no work has evaluated the effectiveness of LLMs in solving CTF challenges with a fully automated workflow. We develop two CTF-solving workflows, human-in-the-loop (HITL) and fully-automated, to examine the LLMs' ability to solve a selected set of CTF challenges, prompted with information about the question. We collect human contestants' results on the same set of questions, and find that LLMs achieve higher success rate than an average human participant. This work provides a comprehensive evaluation of the capability of LLMs in solving real world CTF challenges, from real competition to fully automated workflow. Our results provide references for applying LLMs in cybersecurity education and pave the way for systematic evaluation of offensive cybersecurity capabilities in LLMs.
</details>

---

**An Empirical Survey of Functions and Configurations of Open-Source Capture the Flag (CTF) Environments** [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1084804519303303)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/JNCA-2019-blue.svg" alt="JNCA">
  <img src="https://img.shields.io/badge/CCF-C-yellow.svg" alt="CCF-C">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Survey-purple.svg" alt="Type-Survey">
</div>
Published: 2019-12

Tags: `CTF` | `Survey` | `Cyber Range`
<details><summary>Abstract</summary>
Capture the Flag (CTF) is a computer security competition that is generally used to give participants experience in securing (virtual) machines and responding to cyber attacks. CTF contests have been getting larger and are receiving many participants every year (e.g., DEFCON, NYU-CSAW). CTF competitions are typically hosted in virtual environments, specifically set up to fulfill the goals and scenarios of the CTF. This article investigates the underlying infrastructures and CTF environments, specifically open-source CTF environments. A systematic review is conducted to assess functionality and game configuration in CTF environments where the source code is available on the web (i.e., open-source software). In particular, from out of 28 CTF platforms, we found 12 open-source CTF environments. As four platforms were not installable for several reasons, we finally examined 8 open-source CTF environments (PicoCTF, FacebookCTF, HackTheArch, WrathCTF, Pedagogic-CTF, RootTheBox, CTFd and Mellivora) regarding their features and functions for hosting CTFs (e.g., scoring, statistics or supported challenge types) and providing game configurations (e.g., multiple flags, points, hint penalities). Surprisingly, while many platforms provide similar base functionality, game configurations between the platforms varied strongly. For example, hint penalty, time frames for solving challenges, limited number of attempts or dependencies between challenges are game options that might be relevant for potential CTF organizers and for choosing a technology. This article contributes to the general understanding of CTF software configurations and technology design and implementation. Potential CTF organizers and participants may use this as a reference for challenge configurations and technology utilization. Based on our analysis, we would like to further review commercial and other platforms in order to establish a golden standard for CTF environments and further contribute to a better understanding of CTF design and development.
</details>

---

### Regular Papers

**ZERO-APT: A Closed-Loop Adversarial Framework for LLM-Driven Automated Penetration Testing under Intelligent Defense** [[Paper](https://arxiv.org/pdf/2606.05567)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-06

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
LLM-driven automated penetration testing agents are typically evaluated against static targets that neither detect nor respond to attacks, so their behavior under intelligent defense remains untested. The causal consistency of multi-step attack chains likewise hinges on unstable LLM reasoning, and agent decisions remain opaque to human analysts. These three shortcomings, in realism, consistency, and auditability, are usually patched in isolation. We present ZERO-APT, a turn-based attacker-defender-judge framework that addresses them within a single architecture. For realism, ZERO-APT embeds a configurable LLM Defender that consumes Sysmon telemetry and detects attacks in real time, exposing the attacker to a live opponent rather than a passive target. For consistency, three architectural mechanisms move causal consistency from unstable LLM reasoning into enforced system architecture: separation of planning from execution, multi-dimensional ReAct feedback, and a hard-constraint-filtered action library. For auditability, a dedicated Judge agent adjudicates each round, maintains global state, and emits structured post-hoc CTI reports that make every decision traceable. We evaluate a Windows Server 2022 post-exploitation prototype across five scenarios with three Defender configurations. ZERO-APT reaches 79% attack success rate (Aurora 22%, PentestGPT 39%), a Causal Consistency Score of 0.860 (Aurora 0.930, Claude Code 0.520), and end-to-end decision auditability through structured CTI reports. We release the benchmark to support evaluation of penetration agents under intelligent defense.
</details>

---

**Synthetic APTs: the Collapse of TTP-Based Attribution** [[Paper](https://arxiv.org/pdf/2606.07158)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-06

Tags: `LLM` | `APT`
<details><summary>Abstract</summary>
Cyber Threat Intelligence CTI attribution relies on identifying the Tactics, Techniques, and Procedures TTPs that distinguish one threat actor from another. This approach presupposes that each adversary leaves a recognizable operational fingerprint. This work investigates whether AI driven adversary emulation challenges that presupposition. We deploy agents from our Cybersecurity SuperIntelligence CSI framework, configured as five Advanced Persistent Threat APT groups, APT28, APT29, APT41, APT44, and Lazarus Group, against AI driven Defender agents across two cyber ranges provided by CYBER RANGES, equipped with defensive software Wazuh, Velociraptor, Elasticsearch and active AI driven defenders: an enterprise network and a military infrastructure. Across 20 experiments using two defender models, a binary pattern emerges: all 10 Enterprise range experiments resulted in compromise 2 to 12 hosts per experiment, while all 10 Military range experiments were successfully defended or resulted in stalemates, regardless of APT profile or defender model. In 8 of 10 Enterprise experiments, attackers independently weaponized the defender's own Velociraptor endpoint management platform as a command and control channel, a convergent behavior not encoded in any threat intelligence profile. We argue that in the AI era, wherein agents can be deployed provided the right models are available and subject to the right scaffolding and agentic configuration, the entry barrier for operating like a nation state APT collapses: beyond nation states, individuals can now act like commonly identified threat actors, and with it, fundamentally undermine TTP based attribution.
</details>

---

**Incalmo: An Autonomous LLM-assisted System for Red Teaming Multi-Host Networks** [[WebSite](https://www.incalmo.ai/)] [[Paper](https://arxiv.org/abs/2501.16466)] [[Code](https://github.com/cylabcyberautonomy/Incalmo)] [[Dataset](https://github.com/bsinger98/MHBench)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/S%26P-2026-blue.svg" alt="S&amp;P">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-05

Tags: `LLM` | `Agent`
<details><summary>Abstract</summary>
Security operators use red teams to simulate real attackers and proactively find defense gaps. In realistic enterprise settings, this involves executing multi-host network attacks spanning many "stepping stone" hosts. Unfortunately, red teams are expensive and entail significant expertise and effort. Given the promise of LLMs in CTF challenges, we first analyze if LLMs can autonomously execute multi-host red team exercises. We find that state-of-the-art LLM-assisted offense systems (e.g., PentestGPT, CyberSecEval3) with leading LLMs (e.g., Sonnet 4, Gemini 2.5 Pro) are unable to do so.
Building on our observations in understanding the failure modes of state-of-the-art systems, we argue the need to improve the abstractions and interfaces for LLM-assisted red teaming. Based on this insight, we present the design and implementation of Incalmo, an LLM-assisted system for autonomously red teaming multi-host networks. Incalmo uses LLMs to plan red team exercises in terms of high-level declarative tasks that are executed by domain-specific task agents. Incalmo also uses auxiliary services to manage context and acquired assets.
For our evaluation, we develop MHBench, a novel multi-host attack benchmark with 40 realistic emulated networks (from 22 to 50 hosts). We find that Incalmo successfully acquires critical assets (i.e., key hosts or data) in 37 out of 40 MHBench environments. In contrast, state-of-the-art LLM-assisted systems succeed in only 3 out of 40 environments. We show that Incalmo is efficient-successful attacks took 12-54 minutes and cost <$15 in LLM credits.
</details>

---

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

**When Bots Take the Bait: Exposing and Mitigating the Emerging Social Engineering Attack in Web Automation Agent** [[Paper](https://arxiv.org/pdf/2601.07263)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-01

Tags: `LLM` | `Agent` | `Social Engineering` | `Web Automation`
<details><summary>Abstract</summary>
Web agents, powered by large language models (LLMs), are increasingly deployed to automate complex web interactions. The rise of open-source frameworks (e.g., Browser Use, Skyvern-AI) has accelerated adoption, but also broadened the attack surface. While prior research has focused on model threats such as prompt injection and backdoors, the risks of social engineering remain largely unexplored. We present the first systematic study of social engineering attacks against web automation agents and design a pluggable runtime mitigation solution. On the attack side, we introduce the AgentBait paradigm, which exploits intrinsic weaknesses in agent execution: inducement contexts can distort the agent's reasoning and steer it toward malicious objectives misaligned with the intended task. On the defense side, we propose SUPERVISOR, a lightweight runtime module that enforces environment and intention consistency alignment between webpage context and intended goals to mitigate unsafe operations before execution. Empirical results show that mainstream frameworks are highly vulnerable to AgentBait, with an average attack success rate of 67.5% and peaks above 80% under specific strategies (e.g., trusted identity forgery). Compared with existing lightweight defenses, our module can be seamlessly integrated across different web automation frameworks and reduces attack success rates by up to 78.1% on average while incurring only a 7.7% runtime overhead and preserving usability. This work reveals AgentBait as a critical new threat surface for web agents and establishes a practical, generalizable defense, advancing the security of this rapidly emerging ecosystem. We reported the details of this attack to the framework developers and received acknowledgment before submission.
</details>

---

**PenForge: On-the-Fly Expert Agent Construction for Automated Penetration Testing** [[Paper](https://arxiv.org/pdf/2601.06910)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-01

Tags: `LLM` | `Agent` | `Automated Pentesting`
<details><summary>Abstract</summary>
Penetration testing is essential for identifying vulnerabilities in web applications before real adversaries can exploit them. Recent work has explored automating this process with Large Language Model (LLM)-powered agents, but existing approaches either rely on a single generic agent that struggles in complex scenarios or narrowly specialized agents that cannot adapt to diverse vulnerability types. We therefore introduce PenForge, a framework that dynamically constructs expert agents during testing rather than relying on those prepared beforehand. By integrating automated reconnaissance of potential attack surfaces with agents instantiated on the fly for context-aware exploitation, PenForge achieves a 30.0% exploit success rate (12/40) on CVE-Bench in the particularly challenging zero-day setting, which is a 3 times improvement over the state-of-the-art. Our analysis also identifies three opportunities for future work: (1) supplying richer tool-usage knowledge to improve exploitation effectiveness; (2) extending benchmarks to include more vulnerabilities and attack types; and (3) fostering developer trust by incorporating explainable mechanisms and human review. As an emerging result with substantial potential impact, PenForge embodies the early-stage yet paradigm-shifting idea of on-the-fly agent construction, marking its promise as a step toward scalable and effective LLM-driven penetration testing.
</details>

---

**Cybersecurity AI: A Game-Theoretic AI for Guiding Attack and Defense** [[Paper](https://arxiv.org/pdf/2601.05887)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2026-01

Tags: `LLM` | `Agent` | `Attack and Defense`
<details><summary>Abstract</summary>
AI-driven penetration testing now executes thousands of actions per hour but still lacks the strategic intuition humans apply in competitive security. To build cybersecurity superintelligence --Cybersecurity AI exceeding best human capability-such strategic intuition must be embedded into agentic reasoning processes. We present Generative Cut-the-Rope (G-CTR), a game-theoretic guidance layer that extracts attack graphs from agent's context, computes Nash equilibria with effort-aware scoring, and feeds a concise digest back into the LLM loop \emph{guiding} the agent's actions. Across five real-world exercises, G-CTR matches 70--90% of expert graph structure while running 60--245x faster and over 140x cheaper than manual analysis. In a 44-run cyber-range, adding the digest lifts success from 20.0% to 42.9%, cuts cost-per-success by 2.7x, and reduces behavioral variance by 5.2x. In Attack-and-Defense exercises, a shared digest produces the Purple agent, winning roughly 2:1 over the LLM-only baseline and 3.7:1 over independently guided teams. This closed-loop guidance is what produces the breakthrough: it reduces ambiguity, collapses the LLM's search space, suppresses hallucinations, and keeps the model anchored to the most relevant parts of the problem, yielding large gains in success rate, consistency, and reliability.
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
Published: 2025-5

Tags: `LLM` | `Agent` | `Offensive Security`
<details><summary>Abstract</summary>
From automated intrusion testing to discovery of zero-day attacks before software launch, agentic AI calls for great promises in security engineering. This strong capability is bound with a similar threat: the security and research community must build up its models before the approach is leveraged by malicious actors for cybercrime. We therefore propose and evaluate RedTeamLLM, an integrated architecture with a comprehensive security model for automatization of pentest tasks. RedTeamLLM follows three key steps: summarizing, reasoning and act, which embed its operational capacity. This novel framework addresses four open challenges: plan correction, memory management, context window constraint, and generality vs. specialization. Evaluation is performed through the automated resolution of a range of entry-level, but not trivial, CTF challenges. The contribution of the reasoning capability of our agentic AI framework is specifically evaluated.
</details>

---

**Scalable and Generalizable RL Agents for Attack Path Discovery via Continuous Invariant Spaces** [[WebSite](https://c-cyberbattlesim.readthedocs.io/en/latest/home.html)] [[Paper](https://ieeexplore.ieee.org/document/11352493)] [[Code](https://github.com/terranovafr/C-CyberBattleSim)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/RAID-2025-blue.svg" alt="RAID">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Available-7B61FF" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-10

Tags: `RL` | `Attack Path` | `CyberBattleSim`
<details><summary>Abstract</summary>
Identifying critical attack paths in a net-work-sequences of vulnerabilities an attacker can chain to achieve a specific threat model-is crucial for pinpointing vulnerable areas where defensive measures should be focused. Recently, Reinforcement Learning (RL) has gained traction for training agents in identifying these critical paths. However, current solutions typically train RL agents tailored to a specific environment-defined by a fixed network structure and vulnerability set-requiring costly retraining whenever either changes. This limitation arises from optimizing the agent to map between discrete input and output spaces, treating network nodes and vulnerabilities as atomic discrete elements. In this paper, we propose a method for constructing continuous and invariant input and output spaces for RL agents, enabling them to learn transferable policies that generalize across diverse network configurations and vulnerability sets. We also release Continuous CyberBattleSim (C-CyberBattleSim), an enhanced version of Microsoft CyberBattleSim designed to train agents with the novel continuous spaces. The tool is further extended to integrate realworld vulnerability data and a new scenario generation pipeline to improve the realism of training and testing environments. Agents trained in continuous spaces are assessed in 800 scenarios with varying sizes and various allocations of 829 real-world vulnerabilities, demonstrating an average improvement of 9.3x in scalability against agents trained in discrete spaces, as well as an average generalization score of 89% to more complex scenarios when trained in simpler scenarios. A final study evaluates whether continuous agents trained in simulation can adapt to real-world and emulated scans. On average, agents achieve 75% of the score they would have if trained directly on the scans, demonstrating effective knowledge transfer.
</details>

---

**LLM Agents for Automated Web Vulnerability Reproduction: Are We There Yet?** [[Paper](https://arxiv.org/pdf/2510.14700)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-10

Tags: `LLM` | `Agent` | `Web Vulnerability`
<details><summary>Abstract</summary>
Large language model (LLM) agents have demonstrated remarkable capabilities in software engineering and cybersecurity tasks, including code generation, vulnerability discovery, and automated testing. One critical but underexplored application is automated web vulnerability reproduction, which transforms vulnerability reports into working exploits. Although recent advances suggest promising potential, challenges remain in applying LLM agents to real-world web vulnerability reproduction scenarios. In this paper, we present the first comprehensive evaluation of state-of-the-art LLM agents for automated web vulnerability reproduction. We systematically assess 20 agents from software engineering, cybersecurity, and general domains across 16 dimensions, including technical capabilities, environment adaptability, and user experience factors, on 3 representative web vulnerabilities. Based on the results, we select three top-performing agents (OpenHands, SWE-agent, and CAI) for in-depth evaluation on our benchmark dataset of 80 real-world CVEs spanning 7 vulnerability types and 6 web technologies. Our results reveal that while LLM agents achieve reasonable success on simple library-based vulnerabilities, they consistently fail on complex service-based vulnerabilities requiring multi-component environments. Complex environment configurations and authentication barriers create a gap where agents can execute exploit code but fail to trigger actual vulnerabilities. We observe high sensitivity to input guidance, with performance degrading by over 33% under incomplete authentication information. Our findings highlight the significant gap between current LLM agent capabilities and the demands of reliable automated vulnerability reproduction, emphasizing the need for advances in environmental adaptation and autonomous problem-solving capabilities.
</details>

---

**Genesis: Evolving Attack Strategies for LLM Web Agent Red-Teaming** [[Paper](https://arxiv.org/pdf/2510.18314)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-10

Tags: `LLM` | `Red Teaming` | `Web Agent`
<details><summary>Abstract</summary>
As large language model (LLM) agents increasingly automate complex web tasks, they boost productivity while simultaneously introducing new security risks. However, relevant studies on web agent attacks remain limited. Existing red-teaming approaches mainly rely on manually crafted attack strategies or static models trained offline. Such methods fail to capture the underlying behavioral patterns of web agents, making it difficult to generalize across diverse environments. In web agent attacks, success requires the continuous discovery and evolution of attack strategies. To this end, we propose Genesis, a novel agentic framework composed of three modules: Attacker, Scorer, and Strategist. The Attacker generates adversarial injections by integrating the genetic algorithm with a hybrid strategy representation. The Scorer evaluates the target web agent's responses to provide feedback. The Strategist dynamically uncovers effective strategies from interaction logs and compiles them into a continuously growing strategy library, which is then re-deployed to enhance the Attacker's effectiveness. Extensive experiments across various web tasks show that our framework discovers novel strategies and consistently outperforms existing attack baselines. Our code is available at https://github.com/CjangCjengh/web_agent_attack.
</details>

---

**AutoPentester: An LLM Agent-based Framework for Automated Pentesting** [[Paper](https://arxiv.org/pdf/2510.05605)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-10

Tags: `LLM` | `Agent` | `Automated Pentesting`
<details><summary>Abstract</summary>
Penetration testing and vulnerability assessment are essential industry practices for safeguarding computer systems. As cyber threats grow in scale and complexity, the demand for pentesting has surged, surpassing the capacity of human professionals to meet it effectively. With advances in AI, particularly Large Language Models (LLMs), there have been attempts to automate the pentesting process. However, existing tools such as PentestGPT are still semi-manual, requiring significant professional human interaction to conduct pentests. To this end, we propose a novel LLM agent-based framework, AutoPentester, which automates the pentesting process. Given a target IP, AutoPentester automatically conducts pentesting steps using common security tools in an iterative process. It can dynamically generate attack strategies based on the tool outputs from the previous iteration, mimicking the human pentester approach. We evaluate AutoPentester using Hack The Box and custom-made VMs, comparing the results with the state-of-the-art PentestGPT. Results show that AutoPentester achieves a 27.0% better subtask completion rate and 39.5% more vulnerability coverage with fewer steps. Most importantly, it requires significantly fewer human interactions and interventions compared to PentestGPT. Furthermore, we recruit a group of security industry professional volunteers for a user survey and perform a qualitative analysis to evaluate AutoPentester against industry practices and compare it with PentestGPT. On average, AutoPentester received a score of 3.93 out of 5 based on user reviews, which was 19.8% higher than PentestGPT.
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
Published: 2025-09

Tags: `LLM` | `Agent` | `Offensive Security`
<details><summary>Abstract</summary>
This work introduces xOffense, an AI-driven, multi-agent penetration testing framework that shifts the process from labor-intensive, expert-driven manual efforts to fully automated, machine-executable workflows capable of scaling seamlessly with computational infrastructure. At its core, xOffense leverages a fine-tuned, mid-scale open-source LLM (Qwen3-32B) to drive reasoning and decision-making in penetration testing. The framework assigns specialized agents to reconnaissance, vulnerability scanning, and exploitation, with an orchestration layer ensuring seamless coordination across phases. Fine-tuning on Chain-of-Thought penetration testing data further enables the model to generate precise tool commands and perform consistent multi-step reasoning. We evaluate xOffense on two rigorous benchmarks: AutoPenBench and AI-Pentest-Benchmark. The results demonstrate that xOffense consistently outperforms contemporary methods, achieving a sub-task completion rate of 79.17%, decisively surpassing leading systems such as VulnBot and PentestGPT. These findings highlight the potential of domain-adapted mid-scale LLMs, when embedded within structured multi-agent orchestration, to deliver superior, cost-efficient, and reproducible solutions for autonomous penetration testing.
</details>

---

**Guided Reasoning in LLM-Driven Penetration Testing Using Structured Attack Trees** [[Paper](https://arxiv.org/pdf/2509.07939)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-09

Tags: `LLM` | `Penetration Testing` | `Attack Tree`
<details><summary>Abstract</summary>
Recent advances in Large Language Models (LLMs) have driven interest in automating cybersecurity penetration testing workflows, offering the promise of faster and more consistent vulnerability assessment for enterprise systems. Existing LLM agents for penetration testing primarily rely on self-guided reasoning, which can produce inaccurate or hallucinated procedural steps. As a result, the LLM agent may undertake unproductive actions, such as exploiting unused software libraries or generating cyclical responses that repeat prior tactics. In this work, we propose a guided reasoning pipeline for penetration testing LLM agents that incorporates a deterministic task tree built from the MITRE ATT&CK Matrix, a proven penetration testing kll chain, to constrain the LLM's reaoning process to explicitly defined tactics, techniques, and procedures. This anchors reasoning in proven penetration testing methodologies and filters out ineffective actions by guiding the agent towards more productive attack procedures. To evaluate our approach, we built an automated penetration testing LLM agent using three LLMs (Llama-3-8B, Gemini-1.5, and GPT-4) and applied it to navigate 10 HackTheBox cybersecurity exercises with 103 discrete subtasks representing real-world cyberattack scenarios. Our proposed reasoning pipeline guided the LLM agent through 71.8\%, 72.8\%, and 78.6\% of subtasks using Llama-3-8B, Gemini-1.5, and GPT-4, respectively. Comparatively, the state-of-the-art LLM penetration testing tool using self-guided reasoning completed only 13.5\%, 16.5\%, and 75.7\% of subtasks and required 86.2\%, 118.7\%, and 205.9\% more model queries. This suggests that incorporating a deterministic task tree into LLM reasoning pipelines can enhance the accuracy and efficiency of automated cybersecurity assessments
</details>

---

**From CVE Entries to Verifiable Exploits: An Automated Multi-Agent Framework for Reproducing CVEs** [[Paper](https://arxiv.org/pdf/2509.01835)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-09

Tags: `LLM` | `Multi-Agent` | `CVE` | `Exploit Reproduction`
<details><summary>Abstract</summary>
High-quality datasets of real-world vulnerabilities and their corresponding verifiable exploits are crucial resources in software security research. Yet such resources remain scarce, as their creation demands intensive manual effort and deep security expertise. In this paper, we present CVE-GENIE, an automated, large language model (LLM)-based multi-agent framework designed to reproduce real-world vulnerabilities, provided in Common Vulnerabilities and Exposures (CVE) format, to enable creation of high-quality vulnerability datasets. Given a CVE entry as input, CVE-GENIE gathers the relevant resources of the CVE, automatically reconstructs the vulnerable environment, and (re)produces a verifiable exploit. Our systematic evaluation highlights the efficiency and robustness of CVE-GENIE's design and successfully reproduces approximately 51% (428 of 841) CVEs published in 2024-2025, complete with their verifiable exploits, at an average cost of $2.77 per CVE. Our pipeline offers a robust method to generate reproducible CVE benchmarks, valuable for diverse applications such as fuzzer evaluation, vulnerability patching, and assessing AI's security capabilities.
</details>

---

**Prompt to Pwn: Automated Exploit Generation for Smart Contracts** [[Paper](https://arxiv.org/pdf/2508.01371)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-08

Tags: `LLM` | `Exploit Generation` | `Smart Contract`
<details><summary>Abstract</summary>
Smart contracts are important for digital finance, yet they are hard to patch once deployed. Prior work has mainly explored LLMs for smart contract vulnerability detection, leaving end-to-end automated exploit generation (AEG) much less understood. We study that gap with \textsc{ReX}, an execution-grounded framework that links LLM-based exploit synthesis to the Foundry stack for end-to-end generation, compilation, execution, and validation. Five recent LLMs are evaluated across eight common vulnerability classes, supported by a curated dataset of 38{+} real incident PoCs and three automation aids: prompt refactoring, a compiler feedback loop, and templated test harnesses. Results indicate that current frontier LLMs can often produce deterministic PoCs for single-contract vulnerabilities, but remain weak on cross-contract attacks; outcomes depend mainly on the model and bug type, while code structure and prompt tuning contribute less in our setting. The study also surfaces important boundary conditions of LLM-driven AEG, including gaps between oracle-validated exploitability and real-world economic attacks, pointing to the need for stronger defenses and more realistic evaluation.
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
Published: 2025-08

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>
Penetration testing is a critical technique for identifying security vulnerabilities, traditionally performed manually by skilled security specialists. This complex process involves gathering information about the target system, identifying entry points, exploiting the system, and reporting findings. Despite its effectiveness, manual penetration testing is time-consuming and expensive, often requiring significant expertise and resources that many organizations cannot afford. While automated penetration testing methods have been proposed, they often fall short in real-world applications due to limitations in flexibility, adaptability, and implementation.
Recent advancements in large language models offer new opportunities for enhancing penetration testing through increased intelligence and automation. However, current LLM-based approaches still face significant challenges, including limited penetration testing knowledge and a lack of comprehensive automation capabilities. To address these gaps, we propose PentestAgent, a novel LLM-based automated penetration testing framework that leverages the power of LLMs and various LLM-based techniques like retrieval augmented generation to enhance penetration testing knowledge and automate various tasks. Our framework leverages multi-agent collaboration to automate intelligence gathering, vulnerability analysis, and exploitation stages, reducing manual intervention. We evaluate PentestAgent using a comprehensive benchmark, demonstrating superior performance in task completion and overall efficiency.
</details>

---

**PenTest2.0: Towards Autonomous Privilege Escalation Using GenAI** [[Paper](https://arxiv.org/pdf/2507.06742)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-08

Tags: `LLM` | `Privilege Escalation` | `Agent`
<details><summary>Abstract</summary>
Ethical hacking today relies on highly skilled practitioners executing complex sequences of commands, which is inherently time-consuming, difficult to scale, and prone to human error. To help mitigate these limitations, we previously introduced 'PenTest++', an AI-augmented system combining automation with generative AI supporting ethical hacking workflows. However, a key limitation of PenTest++ was its lack of support for privilege escalation, a crucial element of ethical hacking. In this paper we present 'PenTest2.0', a substantial evolution of PenTest++ supporting automated privilege escalation driven entirely by Large Language Model reasoning. It also incorporates several significant enhancements: 'Retrieval-Augmented Generation', including both one-line and offline modes; 'Chain-of-Thought' prompting for intermediate reasoning; persistent 'PenTest Task Trees' to track goal progression across turns; and the optional integration of human-authored hints. We describe how it operates, present a proof-of-concept prototype, and discuss its benefits and limitations. We also describe application of the system to a controlled Linux target, showing it can carry out multi-turn, adaptive privilege escalation. We explain the rationale behind its core design choices, and provide comprehensive testing results and cost analysis. Our findings indicate that 'PenTest2.0' represents a meaningful step toward practical, scalable, AI-automated penetration testing, whilst highlighting the shortcomings of generative AI systems, particularly their sensitivity to prompt structure, execution context, and semantic drift, reinforcing the need for further research and refinement in this emerging space. Keywords: AI, Ethical Hacking, Privilege Escalation, GenAI, ChatGPT, LLM (Large Language Model), HITL (Human-in-the-Loop)
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

**Autonomous Penetration Testing: Solving Capture-the-Flag Challenges with LLMs** [[Paper](https://arxiv.org/pdf/2508.01054)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-08

Tags: `LLM` | `CTF` | `Autonomous Pentesting`
<details><summary>Abstract</summary>
This study evaluates the ability of GPT-4o to autonomously solve beginner-level offensive security tasks by connecting the model to OverTheWire's Bandit capture-the-flag game. Of the 25 levels that were technically compatible with a single-command SSH framework, GPT-4o solved 18 unaided and another two after minimal prompt hints for an overall 80% success rate. The model excelled at single-step challenges that involved Linux filesystem navigation, data extraction or decoding, and straightforward networking. The approach often produced the correct command in one shot and at a human-surpassing speed. Failures involved multi-command scenarios that required persistent working directories, complex network reconnaissance, daemon creation, or interaction with non-standard shells. These limitations highlight current architectural deficiencies rather than a lack of general exploit knowledge. The results demonstrate that large language models (LLMs) can automate a substantial portion of novice penetration-testing workflow, potentially lowering the expertise barrier for attackers and offering productivity gains for defenders who use LLMs as rapid reconnaissance aides. Further, the unsolved tasks reveal specific areas where secure-by-design environments might frustrate simple LLM-driven attacks, informing future hardening strategies. Beyond offensive cybersecurity applications, results suggest the potential to integrate LLMs into cybersecurity education as practice aids.
</details>

---

**LLMalMorph: On The Feasibility of Generating Variant Malware using Large-Language-Models** [[Paper](https://arxiv.org/pdf/2507.09411)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-07

Tags: `LLM` | `Malware` | `Generation`
<details><summary>Abstract</summary>
Large Language Models (LLMs) have transformed software development and automated code generation. Motivated by these advancements, this paper explores the feasibility of LLMs in modifying malware source code to generate variants. We introduce LLMalMorph, a semi-automated framework that leverages semantical and syntactical code comprehension by LLMs to generate new malware variants. LLMalMorph extracts function-level information from the malware source code and employs custom-engineered prompts coupled with strategically defined code transformations to guide the LLM in generating variants without resource-intensive fine-tuning. To evaluate LLMalMorph, we collected 10 diverse Windows malware samples of varying types, complexity and functionality and generated 618 variants. Our experiments demonstrate that LLMalMorph variants can effectively evade antivirus engines, achieving typical detection rate reductions of 10-15% across multiple complex samples. Furthermore, without explicitly targeting learning-based detectors, LLMalMorph attained attack success rates of up to 91% against a Machine Learning (ML) based malware detector. We also discuss the limitations of current LLM capabilities in generating malware variants from source code and assess where this emerging technology stands in the broader context of malware variant generation.
</details>

---

**FaultLine: Automated Proof-of-Vulnerability Generation Using LLM Agents** [[Paper](https://arxiv.org/pdf/2507.15241)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-07

Tags: `LLM` | `Agent` | `Proof-of-Vulnerability`
<details><summary>Abstract</summary>
Despite the critical threat posed by software security vulnerabilities, reports are often incomplete, lacking the proof-of-vulnerability (PoV) tests needed to validate fixes and prevent regressions. These tests are crucial not only for ensuring patches work, but also for helping developers understand how vulnerabilities can be exploited. Generating PoV tests is a challenging problem, requiring reasoning about the flow of control and data through deeply nested levels of a program. We present FaultLine, an LLM agent workflow that uses a set of carefully designed reasoning steps, inspired by aspects of traditional static and dynamic program analysis, to automatically generate PoV test cases. Given a software project with an accompanying vulnerability report, FaultLine 1) traces the flow of an input from an externally accessible API ("source") to the "sink" corresponding to the vulnerability, 2) reasons about the conditions that an input must satisfy in order to traverse the branch conditions encountered along the flow, and 3) uses this reasoning to generate a PoV test case in a feedback-driven loop. FaultLine does not use language-specific static or dynamic analysis components, which enables it to be used across programming languages. To evaluate FaultLine, we collate a challenging multi-lingual dataset of 100 known vulnerabilities in Java, C and C++ projects. On this dataset, FaultLine is able to generate PoV tests for 16 projects, compared to just 9 for CodeAct 2.1, a popular state-of-the-art open-source agentic framework. Thus, FaultLine represents a 77% relative improvement over the state of the art. Our findings suggest that hierarchical reasoning can enhance the performance of LLM agents on PoV test generation, but the problem in general remains challenging. We make our code and dataset publicly available in the hope that it will spur further research in this area.
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

**RefPentester: A Knowledge-Informed Self-Reflective Penetration Testing Framework Based on Large Language Models** [[Paper](https://arxiv.org/abs/2505.07089)] [[Code](https://github.com/ipa-lab/hackingBuddyGPT)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-06

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>
Automated penetration testing (AutoPT) powered by large language models (LLMs) has gained attention for its ability to automate ethical hacking processes and identify vulnerabilities in target systems by leveraging the inherent knowledge of LLMs. However, existing LLM-based AutoPT frameworks often underperform compared to human experts in challenging tasks for several reasons: the imbalanced knowledge used in LLM training, short-sightedness in the planning process, and hallucinations during command generation. Moreover, the trial-and-error nature of the PT process is constrained by existing frameworks lacking mechanisms to learn from previous failures, restricting adaptive improvement of PT strategies. To address these limitations, we propose a knowledge-informed, self-reflective PT framework powered by LLMs, called RefPentester. This AutoPT framework is designed to assist human operators in identifying the current stage of the PT process, selecting appropriate tactics and techniques for each stage, choosing suggested actions, providing step-by-step operational guidance, and reflecting on and learning from previous failed operations. We also modeled the PT process as a seven-state Stage Machine to integrate the proposed framework effectively. The evaluation shows that RefPentester can successfully reveal credentials on Hack The Box's Sau machine, outperforming the baseline GPT-4o model by 16.7%. Across PT stages, RefPentester also demonstrates superior success rates on PT stage transitions.
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

**ReCopilot: Reverse Engineering Copilot in Binary Analysis** [[Paper](https://arxiv.org/pdf/2505.16366)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-05

Tags: `LLM` | `Reverse Engineering` | `Binary Analysis`
<details><summary>Abstract</summary>
Binary analysis plays a pivotal role in security domains such as malware detection and vulnerability discovery, yet it remains labor-intensive and heavily reliant on expert knowledge. General-purpose large language models (LLMs) perform well in programming analysis on source code, while binaryspecific LLMs are underexplored. In this work, we present ReCopilot, an expert LLM designed for binary analysis tasks. ReCopilot integrates binary code knowledge through a meticulously constructed dataset, encompassing continue pretraining (CPT), supervised fine-tuning (SFT), and direct preference optimization (DPO) stages. It leverages variable data flow and call graph to enhance context awareness and employs test-time scaling to improve reasoning capabilities. Evaluations on a comprehensive binary analysis benchmark demonstrate that ReCopilot achieves state-of-the-art performance in tasks such as function name recovery and variable type inference on the decompiled pseudo code, outperforming both existing tools and LLMs by 13%. Our findings highlight the effectiveness of domain-specific training and context enhancement, while also revealing challenges in building super long chain-of-thought. ReCopilot represents a significant step toward automating binary analysis with interpretable and scalable AI assistance in this domain.
</details>

---

**LLMs unlock new paths to monetizing exploits** [[Paper](https://arxiv.org/pdf/2505.11449)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-05

Tags: `LLM` | `Exploit` | `Offensive Security`
<details><summary>Abstract</summary>
We argue that Large language models (LLMs) will soon alter the economics of cyberattacks. Instead of attacking the most commonly used software and monetizing exploits by targeting the lowest common denominator among victims, LLMs enable adversaries to launch tailored attacks on a user-by-user basis. On the exploitation front, instead of human attackers manually searching for one difficult-to-identify bug in a product with millions of users, LLMs can find thousands of easy-to-identify bugs in products with thousands of users. And on the monetization front, instead of generic ransomware that always performs the same attack (encrypt all your data and request payment to decrypt), an LLM-driven ransomware attack could tailor the ransom demand based on the particular content of each exploited device. We show that these two attacks (and several others) are imminently practical using state-of-the-art LLMs. For example, we show that without any human intervention, an LLM finds highly sensitive personal information in the Enron email dataset (e.g., an executive having an affair with another employee) that could be used for blackmail. While some of our attacks are still too expensive to scale widely today, the incentives to implement these attacks will only increase as LLMs get cheaper. Thus, we argue that LLMs create a need for new defense-in-depth approaches.
</details>

---

**PwnGPT: Automatic Exploit Generation Based on Large Language Models** [[Paper](https://aclanthology.org/2025.acl-long.562.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ACL-2025-blue.svg" alt="ACL">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-04

Tags: `LLM` | `Exploit Generation` | `Offensive Security`
<details><summary>Abstract</summary>
PwnGPT studies automatic exploit generation with large language models. It focuses on using LLM reasoning and code generation capabilities to produce exploits from vulnerability information, supporting offensive security research and evaluation.
</details>

---

**Malware analysis assisted by AI with R2AI** [[Paper](https://arxiv.org/pdf/2504.07574)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-04

Tags: `LLM` | `Malware Analysis` | `Reverse Engineering`
<details><summary>Abstract</summary>
This research studies the quality, speed and cost of malware analysis assisted by artificial intelligence. It focuses on Linux and IoT malware of 2024-2025, and uses r2ai, the AI extension of Radare2's disassembler. Not all malware and not all LLMs are equivalent but the study shows excellent results with Claude 3.5 and 3.7 Sonnet. Despite a few errors, the quality of analysis is overall equal or better than without AI assistance. For good results, the AI cannot operate alone and must constantly be guided by an experienced analyst. The gain of speed is largely visible with AI assistance, even when taking account the time to understand AI's hallucinations, exaggerations and omissions. The cost is usually noticeably lower than the salary of a malware analyst, but attention and guidance is needed to keep it under control in cases where the AI would naturally loop without showing progress.
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
Published: 2025-02

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>
We present RapidPen, a fully automated penetration testing (pentesting) framework that addresses the challenge of achieving an initial foothold (IP-to-Shell) without human intervention. Unlike prior approaches that focus primarily on post-exploitation or require a human-in-the-loop, RapidPen leverages large language models (LLMs) to autonomously discover and exploit vulnerabilities, starting from a single IP address. By integrating advanced ReAct-style task planning (Re) with retrieval-augmented knowledge bases of successful exploits, along with a command-generation and direct execution feedback loop (Act), RapidPen systematically scans services, identifies viable attack vectors, and executes targeted exploits in a fully automated manner.

In our evaluation against a vulnerable target from the Hack The Box platform, RapidPen achieved shell access within 200–400 seconds at a per-run cost of approximately $0.3–$0.6, demonstrating a 60% success rate when reusing prior “success-case” data. These results underscore the potential of truly autonomous pentesting for both security novices and seasoned professionals. Organizations without dedicated security teams can leverage RapidPen to quickly identify critical vulnerabilities, while expert pentesters can offload repetitive tasks and focus on complex challenges. Ultimately, our work aims to make penetration testing more accessible and cost-efficient, thereby enhancing the overall security posture of modern software ecosystems.
</details>

---

**PenTest++: Elevating Ethical Hacking with AI and Automation** [[Paper](https://arxiv.org/pdf/2502.09484)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-02

Tags: `LLM` | `Ethical Hacking` | `Automation`
<details><summary>Abstract</summary>
Traditional ethical hacking relies on skilled professionals and time-intensive command management, which limits its scalability and efficiency. To address these challenges, we introduce PenTest++, an AI-augmented system that integrates automation with generative AI (GenAI) to optimise ethical hacking workflows. Developed in a controlled virtual environment, PenTest++ streamlines critical penetration testing tasks, including reconnaissance, scanning, enumeration, exploitation, and documentation, while maintaining a modular and adaptable design. The system balances automation with human oversight, ensuring informed decision-making at key stages, and offers significant benefits such as enhanced efficiency, scalability, and adaptability. However, it also raises ethical considerations, including privacy concerns and the risks of AI-generated inaccuracies (hallucinations). This research underscores the potential of AI-driven systems like PenTest++ to complement human expertise in cybersecurity by automating routine tasks, enabling professionals to focus on strategic decision-making. By incorporating robust ethical safeguards and promoting ongoing refinement, PenTest++ demonstrates how AI can be responsibly harnessed to address operational and ethical challenges in the evolving cybersecurity landscape.
</details>

---

**Construction and Evaluation of LLM-based agents for Semi-Autonomous penetration testing** [[Paper](https://arxiv.org/pdf/2502.15506)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025-02

Tags: `LLM` | `Agent` | `Semi-Autonomous Pentesting`
<details><summary>Abstract</summary>
With the emergence of high-performance large language models (LLMs) such as GPT, Claude, and Gemini, the autonomous and semi-autonomous execution of tasks has significantly advanced across various domains. However, in highly specialized fields such as cybersecurity, full autonomy remains a challenge. This difficulty primarily stems from the limitations of LLMs in reasoning capabilities and domain-specific knowledge. We propose a system that semi-autonomously executes complex cybersecurity workflows by employing multiple LLMs modules to formulate attack strategies, generate commands, and analyze results, thereby addressing the aforementioned challenges. In our experiments using Hack The Box virtual machines, we confirmed that our system can autonomously construct attack strategies, issue appropriate commands, and automate certain processes, thereby reducing the need for manual intervention.
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
Published: 2025-01

Tags: `LLM` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>
Penetration testing is a vital practice for identifying and mitigating vulnerabilities in cybersecurity systems, but its manual execution is labor-intensive and time-consuming. Existing large language model (LLM)-assisted or automated penetration testing approaches often suffer from inefficiencies, such as a lack of contextual understanding and excessive, unstructured data generation. This paper presents VulnBot, an automated penetration testing framework that leverages LLMs to simulate the collaborative workflow of human penetration testing teams through a multi-agent system. To address the inefficiencies and reliance on manual intervention in traditional penetration testing methods, VulnBot decomposes complex tasks into three specialized phases: reconnaissance, scanning, and exploitation. These phases are guided by a penetration task graph (PTG) to ensure logical task execution. Key design features include role specialization, penetration path planning, inter-agent communication, and generative penetration behavior. Experimental results demonstrate that VulnBot outperforms baseline models such as GPT-4 and Llama3 in automated penetration testing tasks, particularly showcasing its potential in fully autonomous testing on real-world machines.
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
Automating penetration testing is crucial for enhancing cybersecurity, yet current Large Language Models (LLMs) face significant limitations in this domain, including poor error handling, inefficient reasoning, and an inability to perform complex end-to-end tasks autonomously. To address these challenges, we introduce Pentest-R1, a novel framework designed to optimize LLM reasoning capabilities for this task through a two-stage reinforcement learning pipeline. We first construct a dataset of over 500 real-world, multi-step walkthroughs, which Pentest-R1 leverages for offline reinforcement learning (RL) to instill foundational attack logic. Subsequently, the LLM is fine-tuned via online RL in an interactive Capture The Flag (CTF) environment, where it learns directly from environmental feedback to develop robust error self-correction and adaptive strategies. Our extensive experiments on the Cybench and AutoPenBench benchmarks demonstrate the framework's effectiveness. On AutoPenBench, Pentest-R1 achieves a 24.2\% success rate, surpassing most state-of-the-art models and ranking second only to Gemini 2.5 Flash. On Cybench, it attains a 15.0\% success rate in unguided tasks, establishing a new state-of-the-art for open-source LLMs and matching the performance of top proprietary models. Ablation studies confirm that the synergy of both training stages is critical to its success.
</details>

---

**Penetration Testing with AI: Case Studies on LLM and RL-Based Attack Agents** [[Paper](https://link.springer.com/chapter/10.1007/978-3-032-02725-2_5)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Springer-2025-blue.svg" alt="Springer">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2025

Tags: `LLM` | `RL` | `Agent` | `Penetration Testing`
<details><summary>Abstract</summary>
This chapter presents case studies on AI-assisted penetration testing with both LLM-based and reinforcement-learning-based attack agents. It discusses how these agents support reconnaissance, exploitation, and decision making, while highlighting practical limitations in autonomy, reliability, and evaluation.
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
This paper presents a critical examination of the surprising efficacy of Large Language Models (LLMs) in penetration testing. The paper thoroughly reviews the evolution of LLMs and their rapidly expanding capabilities which render them increasingly suitable for complex penetration testing operations. It systematically details the historical adoption of LLMs in both academic research and industry, showcasing their application across various offensive security tasks and covering broader phases of the cyber kill chain. Crucially, the analysis also extends to the observed adoption of LLMs by malicious actors, underscoring the inherent dual-use challenge of this technology within the security landscape. The unexpected effectiveness of LLMs in this context is elucidated by several key factors: the strong alignment between penetration testing's reliance on pattern-matching and LLMs' core strengths, their inherent capacity to manage uncertainty in dynamic environments, and cost-effective access to competent pre-trained models through LLM providers. The current landscape of LLM-aided penetration testing is categorized into interactive 'vibe-hacking' and the emergence of fully autonomous systems. The paper identifies and discusses significant obstacles impeding wider adoption and safe deployment. These include critical issues concerning model reliability and stability, paramount safety and security concerns, substantial monetary and ecological costs, implications for privacy and digital sovereignty, complex questions of accountability, and profound ethical dilemmas. This comprehensive review and analysis provides a foundation for discussion on future research directions and the development of robust safeguards at the intersection of AI and security.
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
This work evaluates and improves large language models on Capture-the-Flag style offensive security challenges. It examines how model capabilities, task structure, and augmentation strategies affect the ability of LLMs to solve multi-step cybersecurity problems.
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
Security operators use red teams to simulate real attackers and proactively find defense gaps. In realistic enterprise settings, this involves executing multi-host network attacks spanning many "stepping stone" hosts. Unfortunately, red teams are expensive and entail significant expertise and effort. Given the promise of LLMs in CTF challenges, we first analyze if LLMs can autonomously execute multi-host red team exercises. We find that state-of-the-art LLM-assisted offense systems (e.g., PentestGPT, CyberSecEval3) with leading LLMs (e.g., Sonnet 4, Gemini 2.5 Pro) are unable to do so. Building on our observations in understanding the failure modes of state-of-the-art systems, we argue the need to improve the abstractions and interfaces for LLM-assisted red teaming. Based on this insight, we present the design and implementation of Incalmo, an LLM-assisted system for autonomously red teaming multi-host networks. Incalmo uses LLMs to plan red team exercises in terms of high-level declarative tasks that are executed by domain-specific task agents. Incalmo also uses auxiliary services to manage context and acquired assets. For our evaluation, we develop MHBench, a novel multi-host attack benchmark with 40 realistic emulated networks (from 22 to 50 hosts). We find that Incalmo successfully acquires critical assets (i.e., key hosts or data) in 37 out of 40 MHBench environments. In contrast, state-of-the-art LLM-assisted systems succeed in only 3 out of 40 environments. We show that Incalmo is efficient-successful attacks took 12-54 minutes and cost <$15 in LLM credits.
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
Lanxiao Huang, Daksh Dave, Tyler Cody, Peter A. Beling, Ming Jin. Proceedings of the 2025 Conference on Empirical Methods in Natural Language Processing. 2025.
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
This work studies whether large language model agents can perform autonomous assumed-breach penetration testing in enterprise Active Directory environments. It focuses on multi-step network compromise, tool use, privilege escalation, and the operational constraints that arise when LLM-based agents attempt realistic post-compromise attack paths.
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
A recent area of increasing research is the use of Large Language Models (LLMs) in penetration testing, which promises to reduce costs and thus allow for higher frequency. We conduct a review of related work, identifying best practices and common evaluation issues. We then present AutoPentest, an application for performing black-box penetration tests with a high degree of autonomy. AutoPentest is based on the LLM GPT-4o from OpenAI and the LLM agent framework LangChain. It can perform complex multi-step tasks, augmented by external tools and knowledge bases. We conduct a study on three capture-the-flag style Hack The Box (HTB) machines, comparing our implementation AutoPentest with the baseline approach of manually using the ChatGPT-4o user interface. Both approaches are able to complete 15-25 % of the subtasks on the HTB machines, with AutoPentest slightly outperforming ChatGPT. We measure a total cost of \$96.20 US when using AutoPentest across all experiments, while a one-month subscription to ChatGPT Plus costs \$20. The results show that further implementation efforts and the use of more powerful LLMs released in the future are likely to make this a viable part of vulnerability management.
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
While penetration testing plays a vital role in cybersecurity, achieving fully automated, hands-off-the-keyboard execution remains a significant research challenge. In this paper, we introduce the "Planner-Executor-Perceptor (PEP)" design paradigm and use it to systematically review existing work and identify the key challenges in this area. We also evaluate existing penetration testing systems, with a particular focus on the use of Large Language Model (LLM) agents for this task. The results show that the out-of-the-box Claude Code and Sonnet 4.5 exhibit superior penetration capabilities observed to date, substantially outperforming all prior systems. However, a detailed analysis of their testing processes reveals specific strengths and limitations; notably, LLM agents struggle with maintaining coherent long-horizon plans, performing complex reasoning, and effectively utilizing specialized tools. These limitations significantly constrain its overall capability, efficiency, and stability. To address these limitations, we propose CHECKMATE, a framework that integrates enhanced classical planning with LLM agents, providing an external, structured "brain" that mitigates the inherent weaknesses of LLM agents. Our evaluation shows that CHECKMATE outperforms the state-of-the-art system (Claude Code) in penetration capability, improving benchmark success rates by over 20%. In addition, it delivers substantially greater stability, cutting both time and monetary costs by more than 50%.
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
We introduce ARACNE, a fully autonomous LLM-based pentesting agent tailored for SSH services that can execute commands on real Linux shell systems. Introduces a new agent architecture with multi-LLM model support. Experiments show that ARACNE can reach a 60\% success rate against the autonomous defender ShelLM and a 57.58\% success rate against the Over The Wire Bandit CTF challenges, improving over the state-of-the-art. When winning, the average number of actions taken by the agent to accomplish the goals was less than 5. The results show that the use of multi-LLM is a promising approach to increase accuracy in the actions.
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
This paper proposes a unified modeling framework for automated penetration testing. It frames penetration testing as a structured decision-making and system-modeling problem, aiming to support attack-path reasoning, environment representation, and repeatable evaluation of automated pentesting methods.
</details>

---

**Hacking CTFs with Plain Agents** [[Paper](https://arxiv.org/pdf/2412.02776)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-12

Tags: `LLM` | `Agent` | `CTF`
<details><summary>Abstract</summary>
We saturate a high-school-level hacking benchmark with plain LLM agent design. Concretely, we obtain 95% performance on InterCode-CTF, a popular offensive security benchmark, using prompting, tool use, and multiple attempts. This beats prior work by Phuong et al. 2024 (29%) and Abramovich et al. 2024 (72%). Our results suggest that current LLMs have surpassed the high school level in offensive cybersecurity. Their hacking capabilities remain underelicited: our ReAct&Plan prompting strategy solves many challenges in 1-2 turns without complex engineering or advanced harnessing.
</details>

---

**Next-Generation Phishing: How LLM Agents Empower Cyber Attackers** [[Paper](https://arxiv.org/pdf/2411.13874)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-11

Tags: `LLM` | `Agent` | `Phishing`
<details><summary>Abstract</summary>
The escalating threat of phishing emails has become increasingly sophisticated with the rise of Large Language Models (LLMs). As attackers exploit LLMs to craft more convincing and evasive phishing emails, it is crucial to assess the resilience of current phishing defenses. In this study we conduct a comprehensive evaluation of traditional phishing detectors, such as Gmail Spam Filter, Apache SpamAssassin, and Proofpoint, as well as machine learning models like SVM, Logistic Regression, and Naive Bayes, in identifying both traditional and LLM-rephrased phishing emails. We also explore the emerging role of LLMs as phishing detection tools, a method already adopted by companies like NTT Security Holdings and JPMorgan Chase. Our results reveal notable declines in detection accuracy for rephrased emails across all detectors, highlighting critical weaknesses in current phishing defenses. As the threat landscape evolves, our findings underscore the need for stronger security controls and regulatory oversight on LLM-generated content to prevent its misuse in creating advanced phishing attacks. This study contributes to the development of more effective Cyber Threat Intelligence (CTI) by leveraging LLMs to generate diverse phishing variants that can be used for data augmentation, harnessing the power of LLMs to enhance phishing detection, and paving the way for more robust and adaptable threat detection systems.
</details>

---

**AutoPT: How Far Are We from the End2End Automated Web Penetration Testing?** [[Paper](https://arxiv.org/pdf/2411.01236)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-11

Tags: `LLM` | `Web Security` | `Automated Pentesting`
<details><summary>Abstract</summary>
Penetration testing is essential to ensure Web security, which can detect and fix vulnerabilities in advance, and prevent data leakage and serious consequences. The powerful inference capabilities of large language models (LLMs) have made significant progress in various fields, and the development potential of LLM-based agents can revolutionize the cybersecurity penetration testing industry. In this work, we establish a comprehensive end-to-end penetration testing benchmark using a real-world penetration testing environment to explore the capabilities of LLM-based agents in this domain. Our results reveal that the agents are familiar with the framework of penetration testing tasks, but they still face limitations in generating accurate commands and executing complete processes. Accordingly, we summarize the current challenges, including the difficulty of maintaining the entire message history and the tendency for the agent to become stuck. Based on the above insights, we propose a Penetration testing State Machine (PSM) that utilizes the Finite State Machine (FSM) methodology to address these limitations. Then, we introduce AutoPT, an automated penetration testing agent based on the principle of PSM driven by LLMs, which utilizes the inherent inference ability of LLM and the constraint framework of state machines. Our evaluation results show that AutoPT outperforms the baseline framework ReAct on the GPT-4o mini model and improves the task completion rate from 22% to 41% on the benchmark target. Compared with the baseline framework and manual work, AutoPT also reduces time and economic costs further. Hence, our AutoPT has facilitated the development of automated penetration testing and significantly impacted both academia and industry.
</details>

---

**AI-Augmented Ethical Hacking: A Practical Examination of Manual Exploitation and Privilege Escalation in Linux Environments** [[Paper](https://arxiv.org/pdf/2411.17539)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-11

Tags: `LLM` | `Ethical Hacking` | `Privilege Escalation`
<details><summary>Abstract</summary>
This study explores the application of generative AI (GenAI) within manual exploitation and privilege escalation tasks in Linux-based penetration testing environments, two areas critical to comprehensive cybersecurity assessments. Building on previous research into the role of GenAI in the ethical hacking lifecycle, this paper presents a hands-on experimental analysis conducted in a controlled virtual setup to evaluate the utility of GenAI in supporting these crucial, often manual, tasks. Our findings demonstrate that GenAI can streamline processes, such as identifying potential attack vectors and parsing complex outputs for sensitive data during privilege escalation. The study also identifies key benefits and challenges associated with GenAI, including enhanced efficiency and scalability, alongside ethical concerns related to data privacy, unintended discovery of vulnerabilities, and potential for misuse. This work contributes to the growing field of AI-assisted cybersecurity by emphasising the importance of human-AI collaboration, especially in contexts requiring careful decision-making, rather than the complete replacement of human input.
</details>

---

**Hacking, The Lazy Way: LLM Augmented Pentesting** [[Paper](https://arxiv.org/pdf/2409.09493)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-09

Tags: `LLM` | `Penetration Testing`
<details><summary>Abstract</summary>
In our research, we introduce a new concept called "LLM Augmented Pentesting" demonstrated with a tool named "Pentest Copilot," that revolutionizes the field of ethical hacking by integrating Large Language Models (LLMs) into penetration testing workflows, leveraging the advanced GPT-4-turbo model. Our approach focuses on overcoming the traditional resistance to automation in penetration testing by employing LLMs to automate specific sub-tasks while ensuring a comprehensive understanding of the overall testing process. Pentest Copilot showcases remarkable proficiency in tasks such as utilizing testing tools, interpreting outputs, and suggesting follow-up actions, efficiently bridging the gap between automated systems and human expertise. By integrating a "chain of thought" mechanism, Pentest Copilot optimizes token usage and enhances decision-making processes, leading to more accurate and context-aware outputs. Additionally, our implementation of Retrieval-Augmented Generation (RAG) minimizes hallucinations and ensures the tool remains aligned with the latest cybersecurity techniques and knowledge. We also highlight a unique infrastructure system that supports in-browser penetration testing, providing a robust platform for cybersecurity professionals. Our findings demonstrate that LLM Augmented Pentesting can not only significantly enhance task completion rates in penetration testing but also effectively addresses real-world challenges, marking a substantial advancement in the cybersecurity domain.
</details>

---

**Using Retriever Augmented Large Language Models for Attack Graph Generation** [[Paper](https://arxiv.org/pdf/2408.05855)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-08

Tags: `LLM` | `Attack Graph` | `RAG`
<details><summary>Abstract</summary>
As the complexity of modern systems increases, so does the importance of assessing their security posture through effective vulnerability management and threat modeling techniques. One powerful tool in the arsenal of cybersecurity professionals is the attack graph, a representation of all potential attack paths within a system that an adversary might exploit to achieve a certain objective. Traditional methods of generating attack graphs involve expert knowledge, manual curation, and computational algorithms that might not cover the entire threat landscape due to the ever-evolving nature of vulnerabilities and exploits. This paper explores the approach of leveraging large language models (LLMs), such as ChatGPT, to automate the generation of attack graphs by intelligently chaining Common Vulnerabilities and Exposures (CVEs) based on their preconditions and effects. It also shows how to utilize LLMs to create attack graphs from threat reports.
</details>

---

**CIPHER: Cybersecurity Intelligent Penetration-testing Helper for Ethical Researcher** [[Paper](https://arxiv.org/pdf/2408.11650)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Sensors-2024-blue.svg" alt="Sensors">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-08

Tags: `LLM` | `Penetration Testing` | `Assistant`
<details><summary>Abstract</summary>
Penetration testing, a critical component of cybersecurity, typically requires extensive time and effort to find vulnerabilities. Beginners in this field often benefit from collaborative approaches with the community or experts. To address this, we develop CIPHER (Cybersecurity Intelligent Penetration-testing Helper for Ethical Researchers), a large language model specifically trained to assist in penetration testing tasks. We trained CIPHER using over 300 high-quality write-ups of vulnerable machines, hacking techniques, and documentation of open-source penetration testing tools. Additionally, we introduced the Findings, Action, Reasoning, and Results (FARR) Flow augmentation, a novel method to augment penetration testing write-ups to establish a fully automated pentesting simulation benchmark tailored for large language models. This approach fills a significant gap in traditional cybersecurity Q\&A benchmarks and provides a realistic and rigorous standard for evaluating AI's technical knowledge, reasoning capabilities, and practical utility in dynamic penetration testing scenarios. In our assessments, CIPHER achieved the best overall performance in providing accurate suggestion responses compared to other open-source penetration testing models of similar size and even larger state-of-the-art models like Llama 3 70B and Qwen1.5 72B Chat, particularly on insane difficulty machine setups. This demonstrates that the current capabilities of general LLMs are insufficient for effectively guiding users through the penetration testing process. We also discuss the potential for improvement through scaling and the development of better benchmarks using FARR Flow augmentation results. Our benchmark will be released publicly at https://github.com/ibndias/CIPHER.
</details>

---

**Tactics, Techniques, and Procedures (TTPs) in Interpreted Malware: A Zero-Shot Generation with Large Language Models** [[Paper](https://arxiv.org/pdf/2407.08532)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-07

Tags: `LLM` | `Malware` | `TTP`
<details><summary>Abstract</summary>
Nowadays, the open-source software (OSS) ecosystem suffers from security threats of software supply chain (SSC) attacks. Interpreted OSS malware plays a vital role in SSC attacks, as criminals have an arsenal of attack vectors to deceive users into installing malware and executing malicious activities. In this paper, we introduce tactics, techniques, and procedures (TTPs) proposed by MITRE ATT\&CK into the interpreted malware analysis to characterize different phases of an attack lifecycle. Specifically, we propose GENTTP, a zero-shot approach to extracting a TTP of an interpreted malware package. GENTTP leverages large language models (LLMs) to automatically generate a TTP, where the input is a malicious package, and the output is a deceptive tactic and an execution tactic of attack vectors. To validate the effectiveness of GENTTP, we collect two datasets for evaluation: a dataset with ground truth labels and a large dataset in the wild. Experimental results show that GENTTP can generate TTPs with high accuracy and efficiency. To demonstrate GENTTP's benefits, we build an LLM-based Chatbot from 3,700+ PyPI malware's TTPs. We further conduct a quantitative analysis of malware's TTPs at a large scale. Our main findings include: (1) many OSS malicious packages share a relatively stable TTP, even with the increasing emergence of malware and attack campaigns, (2) a TTP reflects characteristics of a malware-based attack, and (3) an attacker's intent behind the malware is linked to a TTP.
</details>

---

**PenHeal: A Two-Stage LLM Framework for Automated Pentesting and Optimal Remediation** [[Paper](https://arxiv.org/pdf/2407.17788)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Workshop%20on%20Autonomous%20Cybersecurity-2024-blue.svg" alt="Workshop on Autonomous Cybersecurity">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-07

Tags: `LLM` | `Automated Pentesting` | `Remediation`
<details><summary>Abstract</summary>
Recent advances in Large Language Models (LLMs) have shown significant potential in enhancing cybersecurity defenses against sophisticated threats. LLM-based penetration testing is an essential step in automating system security evaluations by identifying vulnerabilities. Remediation, the subsequent crucial step, addresses these discovered vulnerabilities. Since details about vulnerabilities, exploitation methods, and software versions offer crucial insights into system weaknesses, integrating penetration testing with vulnerability remediation into a cohesive system has become both intuitive and necessary. This paper introduces PenHeal, a two-stage LLM-based framework designed to autonomously identify and mitigate security vulnerabilities. The framework integrates two LLM-enabled components: the Pentest Module, which detects multiple vulnerabilities within a system, and the Remediation Module, which recommends optimal remediation strategies. The integration is facilitated through Counterfactual Prompting and an Instructor module that guides the LLMs using external knowledge to explore multiple potential attack paths effectively. Our experimental results demonstrate that PenHeal not only automates the identification and remediation of vulnerabilities but also significantly improves vulnerability coverage by 31%, increases the effectiveness of remediation strategies by 32%, and reduces the associated costs by 46% compared to baseline models. These outcomes highlight the transformative potential of LLMs in reshaping cybersecurity practices, offering an innovative solution to defend against cyber threats.
</details>

---

**From Sands to Mansions: Enabling Automatic Full-Life-Cycle Cyberattack Construction with LLM** [[Paper](https://arxiv.org/pdf/2407.16928)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-07

Tags: `LLM` | `Cyberattack Construction` | `Offensive Security`
<details><summary>Abstract</summary>
Evolving attacker capabilities demand realistic and continuously updated cyberattack emulation for threat-informed defense and security benchmarking. Towards automated attack emulation, this paper defines modular attack actions and a linking model to organize and chain heterogeneous attack tools into causality-preserving cyberattacks. Building on this foundation, we introduce Aurora: an automated cyberattack emulation system powered by symbolic planning and large language models (LLMs). Aurora crafts actionable, causality-preserving attack chains tailored to Cyber Threat Intelligence (CTI) reports and target environments, and automatically executes these emulations. Using Aurora, we generated an extensive cyberattack emulation dataset from 250 attack reports, 15 times larger than the leading expert-crafted dataset. Our evaluation shows that Aurora significantly outperforms existing methods in creating actionable, diverse, and realistic attack chains. We release the dataset and use it to evaluate three state-of-the-art intrusion detection systems, whose performance differed notably from results on older datasets, highlighting the need for up-to-date, automated attack emulation.
</details>

---

**Teams of LLM Agents can Exploit Zero-Day Vulnerabilities** [[Paper](https://arxiv.org/pdf/2406.01637)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-06

Tags: `LLM` | `Agent` | `Zero-Day` | `Exploit`
<details><summary>Abstract</summary>
LLM agents have become increasingly sophisticated, especially in the realm of cybersecurity. Researchers have shown that LLM agents can exploit real-world vulnerabilities when given a description of the vulnerability and toy capture-the-flag problems. However, these agents still perform poorly on real-world vulnerabilities that are unknown to the agent ahead of time (zero-day vulnerabilities). In this work, we show that teams of LLM agents can exploit real-world, zero-day vulnerabilities. Prior agents struggle with exploring many different vulnerabilities and long-range planning when used alone. To resolve this, we introduce HPTSA, a system of agents with a planning agent that can launch subagents. The planning agent explores the system and determines which subagents to call, resolving long-term planning issues when trying different vulnerabilities. We construct a benchmark of 14 real-world vulnerabilities and show that our team of agents improve over prior agent frameworks by up to 4.3X.
</details>

---

**LLM Agents can Autonomously Exploit One-day Vulnerabilities** [[Paper](https://arxiv.org/pdf/2404.08144)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-04

Tags: `LLM` | `Agent` | `One-Day` | `Exploit`
<details><summary>Abstract</summary>
LLMs have becoming increasingly powerful, both in their benign and malicious uses. With the increase in capabilities, researchers have been increasingly interested in their ability to exploit cybersecurity vulnerabilities. In particular, recent work has conducted preliminary studies on the ability of LLM agents to autonomously hack websites. However, these studies are limited to simple vulnerabilities. In this work, we show that LLM agents can autonomously exploit one-day vulnerabilities in real-world systems. To show this, we collected a dataset of 15 one-day vulnerabilities that include ones categorized as critical severity in the CVE description. When given the CVE description, GPT-4 is capable of exploiting 87% of these vulnerabilities compared to 0% for every other model we test (GPT-3.5, open-source LLMs) and open-source vulnerability scanners (ZAP and Metasploit). Fortunately, our GPT-4 agent requires the CVE description for high performance: without the description, GPT-4 can exploit only 7% of the vulnerabilities. Our findings raise questions around the widespread deployment of highly capable LLM agents.
</details>

---

**Assessing LLMs in Malicious Code Deobfuscation of Real-world Malware Campaigns** [[Paper](https://arxiv.org/pdf/2404.19715)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-04

Tags: `LLM` | `Malware` | `Deobfuscation`
<details><summary>Abstract</summary>
The integration of large language models (LLMs) into various pipelines is increasingly widespread, effectively automating many manual tasks and often surpassing human capabilities. Cybersecurity researchers and practitioners have recognised this potential. Thus, they are actively exploring its applications, given the vast volume of heterogeneous data that requires processing to identify anomalies, potential bypasses, attacks, and fraudulent incidents. On top of this, LLMs' advanced capabilities in generating functional code, comprehending code context, and summarising its operations can also be leveraged for reverse engineering and malware deobfuscation. To this end, we delve into the deobfuscation capabilities of state-of-the-art LLMs. Beyond merely discussing a hypothetical scenario, we evaluate four LLMs with real-world malicious scripts used in the notorious Emotet malware campaign. Our results indicate that while not absolutely accurate yet, some LLMs can efficiently deobfuscate such payloads. Thus, fine-tuning LLMs for this task can be a viable potential for future AI-powered threat intelligence pipelines in the fight against obfuscated malware.
</details>

---

**LLM Agents can Autonomously Hack Websites** [[Paper](https://arxiv.org/abs/2402.06664v1)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024-02

Tags: `LLM` | `Agent` | `Web Security`
<details><summary>Abstract</summary>
In recent years, large language models (LLMs) have become increasingly capable and can now interact with tools (i.e., call functions), read documents, and recursively call themselves. As a result, these LLMs can now function autonomously as agents. With the rise in capabilities of these agents, recent work has speculated on how LLM agents would affect cybersecurity. However, not much is known about the offensive capabilities of LLM agents. In this work, we show that LLM agents can autonomously hack websites, performing tasks as complex as blind database schema extraction and SQL injections without human feedback. Importantly, the agent does not need to know the vulnerability beforehand. This capability is uniquely enabled by frontier models that are highly capable of tool use and leveraging extended context. Namely, we show that GPT-4 is capable of such hacks, but existing open-source models are not. Finally, we show that GPT-4 is capable of autonomously finding vulnerabilities in websites in the wild. Our findings raise questions about the widespread deployment of LLMs.
</details>

---

**WENDIGO: Deep Reinforcement Learning for Denial-of-Service Query Discovery in GraphQL** [[Paper](https://kclpure.kcl.ac.uk/ws/portalfiles/portal/251249221/Wendigo.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/KCL-2024-blue.svg" alt="KCL">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `GraphQL` | `DoS` | `Web Security`
<details><summary>Abstract</summary>
WENDIGO applies deep reinforcement learning to discover denial-of-service query patterns in GraphQL systems. The work focuses on automated generation of costly queries that stress application behavior, supporting security testing for GraphQL APIs.
</details>

---

**Towards Generalizable Autonomous Penetration Testing via Domain Randomization and Meta-Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2412.04078)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Autonomous Pentesting` | `Meta-RL`
<details><summary>Abstract</summary>
With increasing numbers of vulnerabilities exposed on the internet, autonomous penetration testing (pentesting) has emerged as a promising research area. Reinforcement learning (RL) is a natural fit for studying this topic. However, two key challenges limit the applicability of RL-based autonomous pentesting in real-world scenarios: (a) training environment dilemma -- training agents in simulated environments is sample-efficient while ensuring their realism remains challenging; (b) poor generalization ability -- agents' policies often perform poorly when transferred to unseen scenarios, with even slight changes potentially causing significant generalization gap. To this end, we propose GAP, a generalizable autonomous pentesting framework that aims to realizes efficient policy training in realistic environments and train generalizable agents capable of drawing inferences about other cases from one instance. GAP introduces a Real-to-Sim-to-Real pipeline that (a) enables end-to-end policy learning in unknown real environments while constructing realistic simulations; (b) improves agents' generalization ability by leveraging domain randomization and meta-RL learning.Specially, we are among the first to apply domain randomization in autonomous pentesting and propose a large language model-powered domain randomization method for synthetic environment generation. We further apply meta-RL to improve agents' generalization ability in unseen environments by leveraging synthetic environments. The combination of two methods effectively bridges the generalization gap and improves agents' policy adaptation performance.Experiments are conducted on various vulnerable virtual machines, with results showing that GAP can enable policy learning in various realistic environments, achieve zero-shot policy transfer in similar environments, and realize rapid policy adaptation in dissimilar environments.
</details>

---

**Reinforcement learning-based autonomous attacker to uncover computer network vulnerabilities** [[Paper](https://link.springer.com/article/10.1007/s00521-024-09668-0)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Neural%20Computing%20and%20Applications-2024-blue.svg" alt="Neural Computing and Applications">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Autonomous Attacker` | `Vulnerability Discovery`
<details><summary>Abstract</summary>
This paper presents an autonomous attacker based on reinforcement learning for uncovering vulnerabilities in computer networks. It models attack behavior as sequential decision making and studies how an agent can learn to identify vulnerable nodes and useful attack actions.
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
PentestGPT investigates how large language models can be used as an interactive assistant for penetration testing. The work organizes pentesting workflows into reasoning and task-management stages, helping practitioners plan attacks, interpret tool output, and progress through security assessment tasks.
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
In the digital transformation era, the surge of better development technologies and citizen developers disrupted the space of innovation by increasing the numbe
</details>

---

**Penetration Test Path Discovery Based on NHSC-PPO** [[Paper](https://dl.acm.org/doi/10.1145/3650400.3650693)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ACM-2024-blue.svg" alt="ACM">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Attack Path` | `Penetration Testing`
<details><summary>Abstract</summary>
/a> Abstract AI Summary References Information & Contributors Bibliometrics & Citations Reading Options References Figures Tables Media <i aria-hidden="true" class="i
</details>

---

**Leveraging Reinforcement Learning in Red Teaming for Advanced Ransomware Attack Simulations** [[Paper](https://arxiv.org/pdf/2406.17576)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Red Teaming` | `Ransomware`
<details><summary>Abstract</summary>
Ransomware presents a significant and increasing threat to individuals and organizations by encrypting their systems and not releasing them until a large fee has been extracted. To bolster preparedness against potential attacks, organizations commonly conduct red teaming exercises, which involve simulated attacks to assess existing security measures. This paper proposes a novel approach utilizing reinforcement learning (RL) to simulate ransomware attacks. By training an RL agent in a simulated environment mirroring real-world networks, effective attack strategies can be learned quickly, significantly streamlining traditional, manual penetration testing processes. The attack pathways revealed by the RL agent can provide valuable insights to the defense team, helping them identify network weak points and develop more resilient defensive measures. Experimental results on a 152-host example network confirm the effectiveness of the proposed approach, demonstrating the RL agent's capability to discover and orchestrate attacks on high-value targets while evading honeyfiles (decoy files strategically placed to detect unauthorized access).
</details>

---

**Leveraging Deep Reinforcement Learning for Cyber-Attack Paths Prediction: Formulation, Generalization, and Evaluation** [[Paper](https://hal.science/hal-04662428/document)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/HAL-2024-blue.svg" alt="HAL">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Attack Path` | `Prediction`
<details><summary>Abstract</summary>
This paper formulates cyber-attack path prediction as a deep reinforcement learning problem. It studies how learned policies can generalize across network configurations and support automated reasoning about likely attack paths in cybersecurity environments.
</details>

---

**Knowledge-Informed Auto-Penetration Testing Based on Reinforcement Learning with Reward Machine** [[Paper](https://arxiv.org/pdf/2405.15908)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Autonomous Pentesting` | `Reward Machine`
<details><summary>Abstract</summary>
Automated penetration testing (AutoPT) based on reinforcement learning (RL) has proven its ability to improve the efficiency of vulnerability identification in information systems. However, RL-based PT encounters several challenges, including poor sampling efficiency, intricate reward specification, and limited interpretability. To address these issues, we propose a knowledge-informed AutoPT framework called DRLRM-PT, which leverages reward machines (RMs) to encode domain knowledge as guidelines for training a PT policy. In our study, we specifically focus on lateral movement as a PT case study and formulate it as a partially observable Markov decision process (POMDP) guided by RMs. We design two RMs based on the MITRE ATT\&CK knowledge base for lateral movement. To solve the POMDP and optimize the PT policy, we employ the deep Q-learning algorithm with RM (DQRM). The experimental results demonstrate that the DQRM agent exhibits higher training efficiency in PT compared to agents without knowledge embedding. Moreover, RMs encoding more detailed domain knowledge demonstrated better PT performance compared to RMs with simpler knowledge.
</details>

---

**How to Train your Antivirus: RL-based Hardening through the Problem Space** [[Paper](https://kclpure.kcl.ac.uk/ws/portalfiles/portal/278114787/AutoRobust_RAID_Accepted.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/RAID-2024-blue.svg" alt="RAID">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Malware` | `Antivirus`
<details><summary>Abstract</summary>
This work studies reinforcement-learning-based hardening for antivirus systems in the problem space. It investigates how adaptive training against malicious variants can improve robustness of malware detection models while preserving practical constraints on generated samples.
</details>

---

**Evolving malware detection through instant dynamic graph inverse reinforcement learning** [[Paper](https://www.sciencedirect.com/science/article/pii/S0950705124006257)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Knowledge-Based%20Systems-2024-blue.svg" alt="Knowledge-Based Systems">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Malware` | `Detection`
<details><summary>Abstract</summary>
This paper uses inverse reinforcement learning with dynamic graph representations for malware detection. It focuses on modeling evolving malware behavior and learning discriminative behavioral patterns that can support adaptive detection.
</details>

---

**Evaluation of Reinforcement Learning for Autonomous Penetration Testing using A3C, Q-learning and DQN** [[Paper](https://arxiv.org/pdf/2407.15656)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Autonomous Pentesting` | `Evaluation`
<details><summary>Abstract</summary>
Penetration testing is the process of searching for security weaknesses by simulating an attack. It is usually performed by experienced professionals, where scanning and attack tools are applied. By automating the execution of such tools, the need for human interaction and decision-making could be reduced. In this work, a Network Attack Simulator (NASim) was used as an environment to train reinforcement learning agents to solve three predefined security scenarios. These scenarios cover techniques of exploitation, post-exploitation and wiretapping. A large hyperparameter grid search was performed to find the best hyperparameter combinations. The algorithms Q-learning, DQN and A3C were used, whereby A3C was able to solve all scenarios and achieve generalization. In addition, A3C could solve these scenarios with fewer actions than the baseline automated penetration testing. Although the training was performed on rather small scenarios and with small state and action spaces for the agents, the results show that a penetration test can successfully be performed by the RL agent.
</details>

---

**Efficient Penetration Testing Path Planning Based on Reinforcement Learning with Episodic Memory** [[Paper](https://cdn.techscience.cn/files/CMES/2024/TSP_CMES-140-3/TSP_CMES_28553/TSP_CMES_28553.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/CMES-2024-blue.svg" alt="CMES">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2024

Tags: `RL` | `Path Planning` | `Penetration Testing`
<details><summary>Abstract</summary>
This work explores efficient penetration testing path planning with reinforcement learning and episodic memory. It aims to improve automated agent exploration by reusing previous experience when selecting attack actions and planning paths through target networks.
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
The increasing complexity and scale of modern digital environments have exposed significant gaps in traditional cybersecurity penetration testing methods, which are often time-consuming, labor-intensive, and unable to rapidly adapt to emerging threats. There is a critical need for an automated solution that can efficiently identify and exploit vulnerabilities across diverse systems without extensive human intervention. BreachSeek addresses this challenge by providing an AI-driven multi-agent software platform that leverages Large Language Models (LLMs) integrated through LangChain and LangGraph in Python. This system enables autonomous agents to conduct thorough penetration testing by identifying vulnerabilities, simulating a variety of cyberattacks, executing exploits, and generating comprehensive security reports. In preliminary evaluations, BreachSeek successfully exploited vulnerabilities in exploitable machines within local networks, demonstrating its practical effectiveness. Future developments aim to expand its capabilities, positioning it as an indispensable tool for cybersecurity professionals.
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
Large language models (LLMs) have demonstrated impressive results on natural language tasks, and security researchers are beginning to employ them in both offensive and defensive systems. In cyber-security, there have been multiple research efforts that utilize LLMs focusing on the pre-breach stage of attacks like phishing and malware generation. However, so far there lacks a comprehensive study regarding whether LLM-based systems can be leveraged to simulate the post-breach stage of attacks that are typically human-operated, or "hands-on-keyboard" attacks, under various attack techniques and environments. As LLMs inevitably advance, they may be able to automate both the pre- and post-breach attack stages. This shift may transform organizational attacks from rare, expert-led events to frequent, automated operations requiring no expertise and executed at automation speed and scale. This risks fundamentally changing global computer security and correspondingly causing substantial economic impacts, and a goal of this work is to better understand these risks now so we can better prepare for these inevitable ever-more-capable LLMs on the horizon. On the immediate impact side, this research serves three purposes. First, an automated LLM-based, post-breach exploitation framework can help analysts quickly test and continually improve their organization's network security posture against previously unseen attacks. Second, an LLM-based penetration test system can extend the effectiveness of red teams with a limited number of human analysts. Finally, this research can help defensive systems and teams learn to detect novel attack behaviors preemptively before their use in the wild....
</details>

---

**Prompt Engineering-assisted Malware Dynamic Analysis Using GPT-4** [[Paper](https://arxiv.org/abs/2312.08317)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-12

Tags: `LLM` | `Malware` | `Dynamic Analysis`
<details><summary>Abstract</summary>
Dynamic analysis methods effectively identify shelled, wrapped, or obfuscated malware, thereby preventing them from invading computers. As a significant representation of dynamic malware behavior, the API (Application Programming Interface) sequence, comprised of consecutive API calls, has progressively become the dominant feature of dynamic analysis methods. Though there have been numerous deep learning models for malware detection based on API sequences, the quality of API call representations produced by those models is limited. These models cannot generate representations for unknown API calls, which weakens both the detection performance and the generalization. Further, the concept drift phenomenon of API calls is prominent. To tackle these issues, we introduce a prompt engineering-assisted malware dynamic analysis using GPT-4. In this method, GPT-4 is employed to create explanatory text for each API call within the API sequence. Afterward, the pre-trained language model BERT is used to obtain the representation of the text, from which we derive the representation of the API sequence. Theoretically, this proposed method is capable of generating representations for all API calls, excluding the necessity for dataset training during the generation process. Utilizing the representation, a CNN-based detection model is designed to extract the feature. We adopt five benchmark datasets to validate the performance of the proposed model. The experimental results reveal that the proposed detection algorithm performs better than the state-of-the-art method (TextCNN). Specifically, in cross-database experiments and few-shot learning experiments, the proposed model achieves excellent detection performance and almost a 100% recall rate for malware, verifying its superior generalization performance. The code is available at: github.com/yan-scnu/Prompted_Dynamic_Detection.
</details>

---

**LLMs Killed the Script Kiddie: How Agents Supported by Large Language Models Change the Landscape of Network Threat Testing** [[Paper](https://arxiv.org/abs/2310.06936)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-10

Tags: `LLM` | `Agent` | `Network Threat Testing`
<details><summary>Abstract</summary>
In this paper, we explore the potential of Large Language Models (LLMs) to reason about threats, generate information about tools, and automate cyber campaigns. We begin with a manual exploration of LLMs in supporting specific threat-related actions and decisions. We proceed by automating the decision process in a cyber campaign. We present prompt engineering approaches for a plan-act-report loop for one action of a threat campaign and and a prompt chaining design that directs the sequential decision process of a multi-action campaign. We assess the extent of LLM's cyber-specific knowledge w.r.t the short campaign we demonstrate and provide insights into prompt design for eliciting actionable responses. We discuss the potential impact of LLMs on the threat landscape and the ethical considerations of using LLMs for accelerating threat actor capabilities. We report a promising, yet concerning, application of generative AI to cyber threats. However, the LLM's capabilities to deal with more complex networks, sophisticated vulnerabilities, and the sensitivity of prompts are open questions. This research should spur deliberations over the inevitable advancements in LLM-supported cyber adversarial landscape.
</details>

---

**Evaluating LLMs for Privilege-Escalation Scenarios** [[Paper](https://arxiv.org/abs/2310.11409)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-10

Tags: `LLM` | `Privilege Escalation` | `Evaluation`
<details><summary>Abstract</summary>
Penetration-testing is crucial for identifying system vulnerabilities, with privilege-escalation being a critical subtask to gain elevated access to protected resources. Language Models (LLMs) presents new avenues for automating these security practices by emulating human behavior. However, a comprehensive understanding of LLMs' efficacy and limitations in performing autonomous Linux privilege-escalation attacks remains under-explored. To address this gap, we introduce hackingBuddyGPT, a fully automated LLM-driven prototype designed for autonomous Linux privilege-escalation. We curated a novel, publicly available Linux privilege-escalation benchmark, enabling controlled and reproducible evaluation. Our empirical analysis assesses the quantitative success rates and qualitative operational behaviors of various LLMs -- GPT-3.5-Turbo, GPT-4-Turbo, and Llama3 -- against baselines of human professional pen-testers and traditional automated tools. We investigate the impact of context management strategies, different context sizes, and various high-level guidance mechanisms on LLM performance. Results show that GPT-4-Turbo demonstrates high efficacy, successfully exploiting 33-83% of vulnerabilities, a performance comparable to human pen-testers (75%). In contrast, local models like Llama3 exhibited limited success (0-33%), and GPT-3.5-Turbo achieved moderate rates (16-50%). We show that both high-level guidance and state-management through LLM-driven reflection significantly boost LLM success rates. Qualitative analysis reveals both LLMs' strengths and weaknesses in generating valid commands and highlights challenges in common-sense reasoning, error handling, and multi-step exploitation, particularly with temporal dependencies. Cost analysis indicates that GPT-4-Turbo can achieve human-comparable performance at competitive costs, especially with optimized context management.
</details>

---

**RatGPT: Turning online LLMs into Proxies for Malware Attacks** [[Paper](https://arxiv.org/abs/2308.09183)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-09

Tags: `LLM` | `Malware` | `Attack`
<details><summary>Abstract</summary>
The evolution of Generative AI and the capabilities of the newly released Large Language Models (LLMs) open new opportunities in software engineering. However, they also lead to new challenges in cybersecurity. Recently, researchers have shown the possibilities of using LLMs such as ChatGPT to generate malicious content that can directly be exploited or guide inexperienced hackers to weaponize tools and code. These studies covered scenarios that still require the attacker to be in the middle of the loop. In this study, we leverage openly available plugins and use an LLM as proxy between the attacker and the victim. We deliver a proof-of-concept where ChatGPT is used for the dissemination of malicious software while evading detection, alongside establishing the communication to a command and control (C2) server to receive commands to interact with a victim's system. Finally, we present the general approach as well as essential elements in order to stay undetected and make the attack a success. This proof-of-concept highlights significant cybersecurity issues with openly available plugins and LLMs, which require the development of security guidelines, controls, and mitigation strategies.
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

**From Text to MITRE Techniques: Exploring the Malicious Use of Large Language Models for Generating Cyber Attack Payloads** [[Paper](https://arxiv.org/abs/2305.15336)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023-05

Tags: `LLM` | `Payload Generation` | `MITRE ATT&CK`
<details><summary>Abstract</summary>
This research article critically examines the potential risks and implications arising from the malicious utilization of large language models(LLM), focusing specifically on ChatGPT and Google's Bard. Although these large language models have numerous beneficial applications, the misuse of this technology by cybercriminals for creating offensive payloads and tools is a significant concern. In this study, we systematically generated implementable code for the top-10 MITRE Techniques prevalent in 2022, utilizing ChatGPT, and conduct a comparative analysis of its performance with Google's Bard. Our experimentation reveals that ChatGPT has the potential to enable attackers to accelerate the operation of more targeted and sophisticated attacks. Additionally, the technology provides amateur attackers with more capabilities to perform a wide range of attacks and empowers script kiddies to develop customized tools that contribute to the acceleration of cybercrime. Furthermore, LLMs significantly benefits malware authors, particularly ransomware gangs, in generating sophisticated variants of wiper and ransomware attacks with ease. On a positive note, our study also highlights how offensive security researchers and pentesters can make use of LLMs to simulate realistic attack scenarios, identify potential vulnerabilities, and better protect organizations. Overall, we conclude by emphasizing the need for increased vigilance in mitigating the risks associated with LLMs. This includes implementing robust security measures, increasing awareness and education around the potential risks of this technology, and collaborating with security experts to stay ahead of emerging threats.
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
The assessment of cybersecurity Capture-The-Flag (CTF) exercises involves participants finding text strings or ``flags'' by exploiting system vulnerabilities. Large Language Models (LLMs) are natural-language models trained on vast amounts of words to understand and generate text; they can perform well on many CTF challenges. Such LLMs are freely available to students. In the context of CTF exercises in the classroom, this raises concerns about academic integrity. Educators must understand LLMs' capabilities to modify their teaching to accommodate generative AI assistance. This research investigates the effectiveness of LLMs, particularly in the realm of CTF challenges and questions. Here we evaluate three popular LLMs, OpenAI ChatGPT, Google Bard, and Microsoft Bing. First, we assess the LLMs' question-answering performance on five Cisco certifications with varying difficulty levels. Next, we qualitatively study the LLMs' abilities in solving CTF challenges to understand their limitations. We report on the experience of using the LLMs for seven test cases in all five types of CTF challenges. In addition, we demonstrate how jailbreak prompts can bypass and break LLMs' ethical safeguards. The paper concludes by discussing LLM's impact on CTF exercises and its implications.
</details>

---

**SSQLi: A Black-Box Adversarial Attack Method for SQL Injection Based on Reinforcement Learning** [[Paper](https://www.mdpi.com/1999-5903/15/4/133)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Future%20Internet-2023-blue.svg" alt="Future Internet">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `SQL Injection` | `Adversarial Attack`
<details><summary>Abstract</summary>
SSQLi proposes a black-box adversarial attack method for SQL injection based on reinforcement learning. The approach treats payload construction as a sequential decision process and learns to generate inputs that can trigger or reveal SQL injection behavior.
</details>

---

**SQIRL: Grey-Box Detection of SQL Injection Vulnerabilities Using Reinforcement Learning** [[Paper](http://www.doc.ic.ac.uk/~maffeis/papers/usenix23.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/USENIX%20Security-2023-blue.svg" alt="USENIX Security">
  <img src="https://img.shields.io/badge/CCF-A-red.svg" alt="CCF-A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `SQL Injection` | `Web Security`
<details><summary>Abstract</summary>
SQIRL presents a grey-box approach for detecting SQL injection vulnerabilities using reinforcement learning. It uses feedback from application behavior to guide query generation and explore input spaces likely to expose injection flaws.
</details>

---

**Simulating all archetypes of SQL injection vulnerability exploitation using reinforcement learning agents** [[Paper](https://link.springer.com/article/10.1007/s10207-023-00738-3)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Information%20Systems%20Frontiers-2023-blue.svg" alt="Information Systems Frontiers">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `SQL Injection` | `Exploitation`
<details><summary>Abstract</summary>
Vulnerabilities such as SQL injection represent a serious challenge to security. While tools with a pre-defined logic are commonly used in the field of pen
</details>

---

**ReinforSec: An Automatic Generator of Synthetic Malware Samples and Denial-of-Service Attacks through Reinforcement Learning** [[Paper](https://www.mdpi.com/1424-8220/23/3/1231)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Sensors-2023-blue.svg" alt="Sensors">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Malware` | `Synthetic Samples` | `DoS`
<details><summary>Abstract</summary>
ReinforSec presents a reinforcement-learning-based generator for synthetic malware samples and denial-of-service attack data. The work targets security dataset generation and attack simulation, supporting evaluation of defensive models under generated adversarial behavior.
</details>

---

**Raiju: Reinforcement Learning-Guided Post-Exploitation for Automating Security Assessment of Network Systems** [[Paper](https://arxiv.org/pdf/2309.15518.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Post-Exploitation` | `Security Assessment`
<details><summary>Abstract</summary>
In order to assess the risks of a network system, it is important to investigate the behaviors of attackers after successful exploitation, which is called post-exploitation. Although there are various efficient tools supporting post-exploitation implementation, no application can automate this process. Most of the steps of this process are completed by experts who have profound knowledge of security, known as penetration testers or pen-testers. To this end, our study proposes the Raijū framework, a Reinforcement Learning (RL)-driven automation approach that assists pen-testers in quickly implementing the process of post-exploitation for security-level evaluation in network systems. We implement two RL algorithms, Advantage Actor-Critic (A2C) and Proximal Policy Optimization (PPO), to train specialized agents capable of making intelligent actions, which are Metasploit modules to automatically launch attacks of privileges escalation, gathering hashdump, and lateral movement. By leveraging RL, we aim to empower these agents with the ability to autonomously select and execute actions that can exploit vulnerabilities in target systems. This approach allows us to automate certain aspects of the penetration testing workflow, making it more efficient and responsive to emerging threats and vulnerabilities. The experiments are performed in four real environments with agents trained in thousands of episodes. The agents automatically select actions and launch attacks on the environments and achieve over 84\% of successful attacks with under 55 attack steps given. Moreover, the A2C algorithm has proved extremely effective in the selection of proper actions for automation of post-exploitation.
</details>

---

**PSP-Mal: Evading Malware Detection via Prioritized Experience-based Reinforcement Learning with Shapley Prior** [[Paper](https://dl.acm.org/doi/abs/10.1145/3627106.3627178)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ACM-2023-blue.svg" alt="ACM">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Malware` | `Evasion`
<details><summary>Abstract</summary>
PSP-Mal studies malware detection evasion with prioritized experience-based reinforcement learning and Shapley-prior guidance. It focuses on selecting functionality-preserving malware transformations that improve evasion against detection models.
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
The assessment of cybersecurity Capture-The-Flag (CTF) exercises involves participants finding text strings or ``flags'' by exploiting system vulnerabilities. Large Language Models (LLMs) are natural-language models trained on vast amounts of words to understand and generate text; they can perform well on many CTF challenges. Such LLMs are freely available to students. In the context of CTF exercises in the classroom, this raises concerns about academic integrity. Educators must understand LLMs' capabilities to modify their teaching to accommodate generative AI assistance. This research investigates the effectiveness of LLMs, particularly in the realm of CTF challenges and questions. Here we evaluate three popular LLMs, OpenAI ChatGPT, Google Bard, and Microsoft Bing. First, we assess the LLMs' question-answering performance on five Cisco certifications with varying difficulty levels. Next, we qualitatively study the LLMs' abilities in solving CTF challenges to understand their limitations. We report on the experience of using the LLMs for seven test cases in all five types of CTF challenges. In addition, we demonstrate how jailbreak prompts can bypass and break LLMs' ethical safeguards. The paper concludes by discussing LLM's impact on CTF exercises and its implications.
</details>

---

**HAXSS: Hierarchical Reinforcement Learning for XSS Payload Generation** [[Paper](http://wwwhomes.doc.ic.ac.uk/~maffeis/papers/trustcom22.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/TrustCom-2023-blue.svg" alt="TrustCom">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `XSS` | `Payload Generation`
<details><summary>Abstract</summary>
HAXSS applies hierarchical reinforcement learning to XSS payload generation. It decomposes payload construction into structured decisions so that an agent can generate and refine cross-site scripting payloads for web vulnerability assessment.
</details>

---

**Greybox Penetration Testing on Cloud Access Control with IAM Modeling and Deep Reinforcement Learning** [[Paper](https://arxiv.org/pdf/2304.14540.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Cloud Security` | `Penetration Testing` | `IAM`
<details><summary>Abstract</summary>
IAM misconfigurations are a major cause of privilege escalation (PE) attacks in the cloud, leading to data breaches and major financial losses. Existing PE detectors have two main limits: they cover only some PE types, so many attacks are missed, and they require full access to cloud configurations, which customers may not want to share because of sensitive information. We present TAC, the first IAM PE detection framework that supports both whitebox and greybox analysis for Amazon Web Services (AWS). To improve coverage, we systematically study how permissions are acquired in AWS IAM and identify five PE categories. All five share one pattern: permissions spread across entities. We define this as permission flows and manually extract 219 templates from more than 14,000 AWS operations. Based on this, we build TAC-WB, a whitebox detector with broad PE coverage. We also build TAC-GB, the first greybox PE detector, which works with partial configurations. Customers can choose which entities to reveal and whether to answer questions about permissions. TAC-GB uses a dynamic query process that adapts to each response and uses reinforcement learning with graph neural networks to ask the most useful questions while reducing interaction. We also create TAC-Bench, a benchmark with 2,500 tasks reflecting real-world IAM misconfigurations. Experiments show that TAC-WB finds all PEs missed by prior tools, while TAC-GB outperforms other greybox methods and often matches whitebox methods even with limited query budgets.
</details>

---

**Distributed Web Hacking by Adaptive Consensus-based Reinforcement Learning** [[Paper](https://www.sciencedirect.com/science/article/pii/S0004370223001789)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Artificial%20Intelligence-2023-blue.svg" alt="Artificial Intelligence">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Web Security` | `Distributed Hacking`
<details><summary>Abstract</summary>
This work studies distributed web hacking with adaptive consensus-based reinforcement learning. It frames web attack automation as a coordinated learning problem in which agents collaborate or adapt their strategies to discover and exploit web vulnerabilities.
</details>

---

**Deep Reinforcement Learning for Intelligent Penetration Testing Path Design** [[Paper](https://www.mdpi.com/2076-3417/13/16/9467)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Applied%20Sciences-2023-blue.svg" alt="Applied Sciences">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Path Planning` | `Penetration Testing`
<details><summary>Abstract</summary>
This paper studies deep reinforcement learning for intelligent penetration testing path design. It models penetration testing as a path-planning task and explores how learned policies can select attack steps efficiently in simulated or modeled network environments.
</details>

---

**Automated Penetration Testing with Fine-Grained Control through Deep Reinforcement Learning** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10272349&tag=1)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2023-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Autonomous Pentesting` | `Fine-Grained Control`
<details><summary>Abstract</summary>
Penetration testing (PT) is an active method of evaluating the security of a network by simulating various types of cyber attacks in order to identify and explo
</details>

---

**Application of deep reinforcement learning in attacking and protecting structural features-based malicious PDF detector** [[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167739X22003740)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Future%20Generation%20Computer%20Systems-2023-blue.svg" alt="Future Generation Computer Systems">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2023

Tags: `RL` | `Malware` | `PDF` | `Adversarial Attack`
<details><summary>Abstract</summary>
This work examines deep reinforcement learning for both attacking and protecting malicious PDF detectors based on structural features. It studies how adaptive transformations can evade detection and how defensive training can improve model robustness.
</details>

---

**Reinforcement Learning based Adversarial Malware Example Generation Against Black-Box Detectors** [[Paper](https://www.sciencedirect.com/science/article/pii/S0167404822002632)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Computers%20%26%20Security-2022-blue.svg" alt="Computers &amp; Security">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Malware` | `Adversarial Examples`
<details><summary>Abstract</summary>
This paper presents reinforcement-learning-based adversarial malware example generation against black-box detectors. It learns sequences of malware transformations that preserve functionality while attempting to evade models without requiring internal detector access.
</details>

---

**MAB-Malware: A Reinforcement Learning Framework for Attacking Static Malware Classifiers** [[Paper](https://arxiv.org/pdf/2003.03100.pdf)] [[Code](https://github.com/weisong-ucr/MAB-malware)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Malware` | `Evasion`
<details><summary>Abstract</summary>
Modern commercial antivirus systems increasingly rely on machine learning to keep up with the rampant inflation of new malware. However, it is well-known that machine learning models are vulnerable to adversarial examples (AEs). Previous works have shown that ML malware classifiers are fragile to the white-box adversarial attacks. However, ML models used in commercial antivirus products are usually not available to attackers and only return hard classification labels. Therefore, it is more practical to evaluate the robustness of ML models and real-world AVs in a pure black-box manner. We propose a black-box Reinforcement Learning (RL) based framework to generate AEs for PE malware classifiers and AV engines. It regards the adversarial attack problem as a multi-armed bandit problem, which finds an optimal balance between exploiting the successful patterns and exploring more varieties. Compared to other frameworks, our improvements lie in three points. 1) Limiting the exploration space by modeling the generation process as a stateless process to avoid combination explosions. 2) Due to the critical role of payload in AE generation, we design to reuse the successful payload in modeling. 3) Minimizing the changes on AE samples to correctly assign the rewards in RL learning. It also helps identify the root cause of evasions. As a result, our framework has much higher black-box evasion rates than other off-the-shelf frameworks. Results show it has over 74\%--97\% evasion rate for two state-of-the-art ML detectors and over 32\%--48\% evasion rate for commercial AVs in a pure black-box setting. We also demonstrate that the transferability of adversarial attacks among ML-based classifiers is higher than the attack transferability between purely ML-based and commercial AVs.
</details>

---

**Improved Deep Recurrent Q-Network of POMDPs for Automated Penetration Testing** [[Paper](https://www.mdpi.com/2076-3417/12/20/10339)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Applied%20Sciences-2022-blue.svg" alt="Applied Sciences">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `POMDP` | `Autonomous Pentesting`
<details><summary>Abstract</summary>
This paper applies improved deep recurrent Q-networks under partially observable Markov decision processes to automated penetration testing. It addresses uncertainty and incomplete observability when an agent chooses reconnaissance and exploitation actions.
</details>

---

**H4rm0ny: A Competitive Zero-Sum Two-Player Markov Game for Multi-Agent Learning on Evasive Malware Generation and Detection** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9850345)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2022-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Malware` | `Multi-Agent`
<details><summary>Abstract</summary>
H4rm0ny models evasive malware generation and detection as a competitive two-player Markov game. It studies multi-agent learning dynamics between malware generators and detectors, emphasizing the adversarial nature of malware defense.
</details>

---

**DUSC-DQN: An Improved Deep Q-Network for Intelligent Penetration Testing Path Design** [[Paper](https://ieeexplore.ieee.org/document/9846482)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2022-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `DQN` | `Path Planning`
<details><summary>Abstract</summary>
With the development of internet technology, the security risks in the network are increasing. Malicious network attacks will cause huge losses to users, so it
</details>

---

**Cascaded Reinforcement Learning Agents for Large Action Spaces in Autonomous Penetration Testing** [[Paper](https://www.mdpi.com/2076-3417/12/21/11265)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Applied%20Sciences-2022-blue.svg" alt="Applied Sciences">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Autonomous Pentesting` | `Large Action Space`
<details><summary>Abstract</summary>
This work proposes cascaded reinforcement learning agents for autonomous penetration testing with large action spaces. It decomposes action selection to make learning and decision making more tractable in complex pentesting environments.
</details>

---

**Behaviour-Diverse Automatic Penetration Testing: A Curiosity-Driven Multi-Objective Deep Reinforcement Learning Approach** [[Paper](https://arxiv.org/pdf/2202.10630.pdf)] [[Code](https://github.com/yyzpiero/RL4RedTeam)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Autonomous Pentesting` | `Red Teaming`
<details><summary>Abstract</summary>
Penetration Testing plays a critical role in evaluating the security of a target network by emulating real active adversaries. Deep Reinforcement Learning (RL) is seen as a promising solution to automating the process of penetration tests by reducing human effort and improving reliability. Existing RL solutions focus on finding a specific attack path to impact the target hosts. However, in reality, a diverse range of attack variations are needed to provide comprehensive assessments of the target network's security level. Hence, the attack agents must consider multiple objectives when penetrating the network. Nevertheless, this challenge is not adequately addressed in the existing literature. To this end, we formulate the automatic penetration testing in the Multi-Objective Reinforcement Learning (MORL) framework and propose a Chebyshev decomposition critic to find diverse adversary strategies that balance different objectives in the penetration test. Additionally, the number of available actions increases with the agent consistently probing the target network, making the training process intractable in many practical situations. Thus, we introduce a coverage-based masking mechanism that reduces attention on previously selected actions to help the agent adapt to future exploration. Experimental evaluation on a range of scenarios demonstrates the superiority of our proposed approach when compared to adapted algorithms in terms of multi-objective learning and performance efficiency.
</details>

---

**A Layered Reference Model for Penetration Testing with Reinforcement Learning and Attack Graphs** [[Paper](https://arxiv.org/pdf/2206.06934.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2022

Tags: `RL` | `Attack Graph` | `Penetration Testing`
<details><summary>Abstract</summary>
This paper considers key challenges to using reinforcement learning (RL) with attack graphs to automate penetration testing in real-world applications from a systems perspective. RL approaches to automated penetration testing are actively being developed, but there is no consensus view on the representation of computer networks with which RL should be interacting. Moreover, there are significant open challenges to how those representations can be grounded to the real networks where RL solution methods are applied. This paper elaborates on representation and grounding using topic challenges of interacting with real networks in real-time, emulating realistic adversary behavior, and handling unstable, evolving networks. These challenges are both practical and mathematical, and they directly concern the reliability and dependability of penetration testing systems. This paper proposes a layered reference model to help organize related research and engineering efforts. The presented layered reference model contrasts traditional models of attack graph workflows because it is not scoped to a sequential, feed-forward generation and analysis process, but to broader aspects of lifecycle and continuous deployment. Researchers and practitioners can use the presented layered reference model as a first-principles outline to help orient the systems engineering of their penetration testing systems.
</details>

---

**Using Cyber Terrain in Reinforcement Learning for Penetration Testing** [[Paper](https://arxiv.org/abs/2108.07124)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2021

Tags: `RL` | `Cyber Terrain` | `Penetration Testing`
<details><summary>Abstract</summary>
Reinforcement learning (RL) has been applied to attack graphs for penetration testing, however, trained agents do not reflect reality because the attack graphs lack operational nuances typically captured within the intelligence preparation of the battlefield (IPB) that include notions of (cyber) terrain. In particular, current practice constructs attack graphs exclusively using the Common Vulnerability Scoring System (CVSS) and its components. We present methods for constructing attack graphs using notions from IPB on cyber terrain analysis of obstacles, avenues of approach, key terrain, observation and fields of fire, and cover and concealment. We demonstrate our methods on an example where firewalls are treated as obstacles and represented in (1) the reward space and (2) the state dynamics. We show that terrain analysis can be used to bring realism to attack graphs for RL.
</details>

---

**SQL Injections and Reinforcement Learning: An Empirical Evaluation of the Role of Action Structure** [[Paper](https://link.springer.com/chapter/10.1007/978-3-030-91625-1_6)] [[Code](https://github.com/manuel-delverme/sql_env)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Springer-2021-blue.svg" alt="Springer">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2021

Tags: `RL` | `SQL Injection` | `Web Security`
<details><summary>Abstract</summary>
This paper empirically evaluates the role of action structure in applying reinforcement learning to SQL injection. It studies how different action representations affect an agent's ability to learn effective injection strategies.
</details>

---

**Enhancing the insertion of NOP instructions to obfuscate malware via deep reinforcement learning** [[Paper](https://www.sciencedirect.com/science/article/pii/S0167404821003679)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Computers%20%26%20Security-2021-blue.svg" alt="Computers &amp; Security">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2021

Tags: `RL` | `Malware` | `Obfuscation`
<details><summary>Abstract</summary>
This work uses deep reinforcement learning to enhance malware obfuscation through insertion of NOP instructions. It studies how an agent can select code transformations that preserve malicious functionality while changing detectable characteristics.
</details>

---

**Reinforcement Learning for Efficient Network Penetration Testing** [[Paper](https://www.mdpi.com/2078-2489/11/1/6)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Information-2020-blue.svg" alt="Information">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2020

Tags: `RL` | `Network Pentesting` | `Efficiency`
<details><summary>Abstract</summary>
This paper studies reinforcement learning for efficient network penetration testing. It models network exploitation as a sequential decision problem and evaluates how learned attack policies can reduce exploration cost while reaching target compromise states.
</details>

---

**POMDP + Information-Decay: Incorporating Defender's Behaviour in Autonomous Penetration Testing** [[Paper](https://ojs.aaai.org/index.php/ICAPS/article/view/6666/6520)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/ICAPS-2020-blue.svg" alt="ICAPS">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2020

Tags: `RL` | `POMDP` | `Autonomous Pentesting`
<details><summary>Abstract</summary>
This work incorporates defender behavior into autonomous penetration testing using a POMDP model with information decay. It studies decision making under uncertainty when attacker observations become stale or incomplete during multi-step penetration testing.
</details>

---

**Modeling Penetration Testing with Reinforcement Learning Using Capture-the-Flag Challenges: Trade-offs between Model-free Learning and A Priori Knowledge** [[Paper](https://arxiv.org/pdf/2005.12632.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2020

Tags: `RL` | `CTF` | `Penetration Testing`
<details><summary>Abstract</summary>
Penetration testing is a security exercise aimed at assessing the security of a system by simulating attacks against it. So far, penetration testing has been carried out mainly by trained human attackers and its success critically depended on the available expertise. Automating this practice constitutes a non-trivial problem, as the range of actions that a human expert may attempts against a system and the range of knowledge she relies on to take her decisions are hard to capture. In this paper, we focus our attention on simplified penetration testing problems expressed in the form of capture the flag hacking challenges, and we analyze how model-free reinforcement learning algorithms may help to solve them. In modeling these capture the flag competitions as reinforcement learning problems we highlight that a specific challenge that characterize penetration testing is the problem of discovering the structure of the problem at hand. We then show how this challenge may be eased by relying on different forms of prior knowledge that may be provided to the agent. In this way we demonstrate how the feasibility of tackling penetration testing using reinforcement learning may rest on a careful trade-off between model-free and model-based algorithms. By using techniques to inject a priori knowledge, we show it is possible to better direct the agent and restrict the space of its exploration problem, thus achieving solutions more efficiently.
</details>

---

**Autonomous Security Analysis and Penetration Testing** [[Paper](https://ieeexplore.ieee.org/document/9394285)] [[Code](https://github.com/ankur8931/asap)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2020-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2020

Tags: `RL` | `Autonomous Pentesting` | `Security Analysis`
<details><summary>Abstract</summary>
Security Assessment of large networks is a challenging task. Penetration testing (pentesting) is a method of analyzing the attack surface of a network to find s
</details>

---

**Automated Post-Breach Penetration Testing through Reinforcement Learning** [[Paper](https://ieeexplore.ieee.org/abstract/document/9162301)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2020-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2020

Tags: `RL` | `Post-Breach` | `Penetration Testing`
<details><summary>Abstract</summary>
Predicting cyber attacks to networks is ever present challenges in the security domain. Rapid growth of Artificial Intelligence (AI) has made this even more cha
</details>

---

**Autonomous Penetration Testing using Reinforcement Learning** [[Paper](https://arxiv.org/abs/1905.05965)] [[Code](https://github.com/Jjschwartz/NetworkAttackSimulator)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2019

Tags: `RL` | `Autonomous Pentesting` | `NASim`
<details><summary>Abstract</summary>
Penetration testing (pentesting) involves performing a controlled attack on a computer system in order to assess it's security. Although an effective method for testing security, pentesting requires highly skilled practitioners and currently there is a growing shortage of skilled cyber security professionals. One avenue for alleviating this problem is automate the pentesting process using artificial intelligence techniques. Current approaches to automated pentesting have relied on model-based planning, however the cyber security landscape is rapidly changing making maintaining up-to-date models of exploits a challenge. This project investigated the application of model-free Reinforcement Learning (RL) to automated pentesting. Model-free RL has the key advantage over model-based planning of not requiring a model of the environment, instead learning the best policy through interaction with the environment. We first designed and built a fast, low compute simulator for training and testing autonomous pentesting agents. We did this by framing pentesting as a Markov Decision Process with the known configuration of the network as states, the available scans and exploits as actions, the reward determined by the value of machines on the network. We then used this simulator to investigate the application of model-free RL to pentesting. We tested the standard Q-learning algorithm using both tabular and neural network based implementations. We found that within the simulated environment both tabular and neural network implementations were able to find optimal attack paths for a range of different network topologies and sizes without having a model of action behaviour. However, the implemented algorithms were only practical for smaller networks and numbers of actions. Further work is needed in developing scalable RL algorithms and testing these algorithms in larger and higher fidelity environments.
</details>

---

**Automating Penetration Testing using Reinforcement Learning** [[Paper](https://stefann.eu/files/Automating%20Penetration%20Testing%20using%20Reinforcement%20Learning.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Independent-2019-blue.svg" alt="Independent">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2019

Tags: `RL` | `Automated Pentesting`
<details><summary>Abstract</summary>
This work explores automation of penetration testing using reinforcement learning. It models attack planning as a learning problem in which an agent selects reconnaissance and exploitation actions to progress through a target environment.
</details>

---

**Simulating SQL Injection Vulnerability Exploitation Using Q-Learning Reinforcement Learning Agents** [[Paper](https://arxiv.org/abs/2101.03118)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2018

Tags: `RL` | `SQL Injection` | `Exploitation`
<details><summary>Abstract</summary>
In this paper, we propose a formalization of the process of exploitation of SQL injection vulnerabilities. We consider a simplification of the dynamics of SQL injection attacks by casting this problem as a security capture-the-flag challenge. We model it as a Markov decision process, and we implement it as a reinforcement learning problem. We then deploy reinforcement learning agents tasked with learning an effective policy to perform SQL injection; we design our training in such a way that the agent learns not just a specific strategy to solve an individual challenge but a more generic policy that may be applied to perform SQL injection attacks against any system instantiated randomly by our problem generator. We analyze the results in terms of the quality of the learned policy and in terms of convergence time as a function of the complexity of the challenge and the learning agent's complexity. Our work fits in the wider research on the development of intelligent agents for autonomous penetration testing and white-hat hacking, and our results aim to contribute to understanding the potential and the limits of reinforcement learning in a security environment.
</details>

---

**Reinforcement Learning for Intelligent Penetration Testing** [[Paper](https://ieeexplore.ieee.org/document/8611595)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2018-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2018

Tags: `RL` | `Intelligent Pentesting`
<details><summary>Abstract</summary>
This paper investigates reinforcement learning for intelligent penetration testing. It studies how an autonomous agent can learn attack strategies over modeled network states, supporting automated selection of penetration testing actions.
</details>

---

**Learning to Evade Static PE Machine Learning Malware Models via Reinforcement Learning** [[Paper](https://arxiv.org/abs/1801.08917)] [[Code](https://github.com/endgameinc/gym-malware)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Regular%20Paper-00A6A6" alt="Type-Regular Paper">
</div>
Published: 2018

Tags: `RL` | `Malware` | `Evasion` | `PE`
<details><summary>Abstract</summary>
Machine learning is a popular approach to signatureless malware detection because it can generalize to never-before-seen malware families and polymorphic strains. This has resulted in its practical use for either primary detection engines or for supplementary heuristic detection by anti-malware vendors. Recent work in adversarial machine learning has shown that deep learning models are susceptible to gradient-based attacks, whereas non-differentiable models that report a score can be attacked by genetic algorithms that aim to systematically reduce the score. We propose a more general framework based on reinforcement learning (RL) for attacking static portable executable (PE) anti-malware engines. The general framework does not require a differentiable model nor does it require the engine to produce a score. Instead, an RL agent is equipped with a set of functionality-preserving operations that it may perform on the PE file. Through a series of games played against the anti-malware engine, it learns which sequences of operations are likely to result in evading the detector for any given malware sample. This enables completely black-box attacks against static PE anti-malware, and produces functional evasive malware samples as a direct result. We show in experiments that our method can attack a gradient-boosted machine learning model with evasion rates that are substantial and appear to be strongly dependent on the dataset. We demonstrate that attacks against this model appear to also evade components of publicly hosted antivirus engines. Adversarial training results are also presented: by retraining the model on evasive ransomware samples, a subsequent attack is 33% less effective. However, there are overfitting dangers when adversarial training, which we note. We release code to allow researchers to reproduce and improve this approach.
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

**CSLE: A Reinforcement Learning Platform for Autonomous Security Management** [[Paper](https://arxiv.org/abs/2604.15590)] [[Code](https://github.com/Limmen/csle)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2026

Tags: `RL` | `Cyber Range` | `Autonomous Security`
<details><summary>Abstract</summary>
Reinforcement learning is a promising approach to autonomous and adaptive security management in networked systems. However, current reinforcement learning solutions for security management are mostly limited to simulation environments and it is unclear how they generalize to operational systems. In this paper, we address this limitation by presenting CSLE: a reinforcement learning platform for autonomous security management that enables experimentation under realistic conditions. Conceptually, CSLE encompasses two systems. First, it includes an emulation system that replicates key components of the target system in a virtualized environment. We use this system to gather measurements and logs, based on which we identify a system model, such as a Markov decision process. Second, it includes a simulation system where security strategies are efficiently learned through simulations of the system model. The learned strategies are then evaluated and refined in the emulation system to close the gap between theoretical and operational performance. We demonstrate CSLE through four use cases: flow control, replication control, segmentation control, and recovery control. Through these use cases, we show that CSLE enables near-optimal security management in an environment that approximates an operational system.
</details>

---

**Cybersecurity AI: Evaluating Agentic Cybersecurity in Attack/Defense CTFs** [[Paper](https://arxiv.org/pdf/2510.17521)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-10

Tags: `LLM` | `Agent` | `CTF` | `Benchmark`
<details><summary>Abstract</summary>
We empirically evaluate whether AI systems are more effective at attacking or defending in cybersecurity. Using CAI (Cybersecurity AI)'s parallel execution framework, we deployed autonomous agents in 23 Attack/Defense CTF battlegrounds. Statistical analysis reveals defensive agents achieve 54.3% unconstrained patching success versus 28.3% offensive initial access (p=0.0193), but this advantage disappears under operational constraints: when defense requires maintaining availability (23.9%) and preventing all intrusions (15.2%), no significant difference exists (p>0.05). Exploratory taxonomy analysis suggests potential patterns in vulnerability exploitation, though limited sample sizes preclude definitive conclusions. This study provides the first controlled empirical evidence challenging claims of AI attacker advantage, demonstrating that defensive effectiveness critically depends on success criteria, a nuance absent from conceptual analyses but essential for deployment. These findings underscore the urgency for defenders to adopt open-source Cybersecurity AI frameworks to maintain security equilibrium against accelerating offensive automation.
</details>

---

**AgentCyTE: Leveraging Agentic AI to Generate Cybersecurity Training & Experimentation Scenarios** [[Paper](https://arxiv.org/pdf/2510.25189)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-10

Tags: `LLM` | `Agent` | `Cyber Range` | `Scenario Generation`
<details><summary>Abstract</summary>
Designing realistic and adaptive networked threat scenarios remains a core challenge in cybersecurity research and training, still requiring substantial manual effort. While large language models (LLMs) show promise for automated synthesis, unconstrained generation often yields configurations that fail validation or execution. We present AgentCyTE, a framework integrating LLM-based reasoning with deterministic, schema-constrained network emulation to generate and refine executable threat environments. Through an agentic feedback loop, AgentCyTE observes scenario outcomes, validates correctness, and iteratively enhances realism and consistency. This hybrid approach preserves LLM flexibility while enforcing structural validity, enabling scalable, data-driven experimentation and reliable scenario generation for threat modeling and adaptive cybersecurity training. Our framework can be accessed at: https://github.com/AnantaaKotal/AgentCyTE
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

**Training Language Model Agents to Find Vulnerabilities with CTF-Dojo** [[Paper](https://arxiv.org/pdf/2508.18370)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-08

Tags: `LLM` | `Agent` | `CTF` | `Vulnerability Discovery`
<details><summary>Abstract</summary>
Large language models (LLMs) have demonstrated exceptional capabilities when trained within executable runtime environments, notably excelling at software engineering tasks through verified feedback loops. Yet, scalable and generalizable execution-grounded environments remain scarce, limiting progress in training more capable ML agents. We introduce CTF-Dojo, the first large-scale executable runtime tailored for training LLMs with verifiable feedback, featuring 658 fully functional Capture-The-Flag (CTF)-style challenges containerized in Docker with guaranteed reproducibility. To enable rapid scaling without manual intervention, we develop CTF-Forge, an automated pipeline that transforms publicly available artifacts into ready-to-use execution environments in minutes, eliminating weeks of expert configuration traditionally required. We trained LLM-based agents on just 486 high-quality, execution-verified trajectories from CTF-Dojo, achieving up to 11.6% absolute gains over strong baselines across three competitive benchmarks: InterCode-CTF, NYU CTF Bench, and Cybench. Our best-performing 32B model reaches 31.9% Pass@1, establishing a new open-weight state-of-the-art that rivals frontier models like DeepSeek-V3-0324 and Gemini-2.5-Flash. By framing CTF-style tasks as a benchmark for executable-agent learning, CTF-Dojo demonstrates that execution-grounded training signals are not only effective but pivotal in advancing high-performance ML agents without dependence on costly proprietary systems.
</details>

---

**Towards Effective Offensive Security LLM Agents: Hyperparameter Tuning, LLM as a Judge, and a Lightweight CTF Benchmark** [[Paper](https://arxiv.org/pdf/2508.05674)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-08

Tags: `LLM` | `Agent` | `CTF` | `Offensive Security`
<details><summary>Abstract</summary>
Recent advances in LLM agentic systems have improved the automation of offensive security tasks, particularly for Capture the Flag (CTF) challenges. We systematically investigate the key factors that drive agent success and provide a detailed recipe for building effective LLM-based offensive security agents. First, we present CTFJudge, a framework leveraging LLM as a judge to analyze agent trajectories and provide granular evaluation across CTF solving steps. Second, we propose a novel metric, CTF Competency Index (CCI) for partial correctness, revealing how closely agent solutions align with human-crafted gold standards. Third, we examine how LLM hyperparameters, namely temperature, top-p, and maximum token length, influence agent performance and automated cybersecurity task planning. For rapid evaluation, we present CTFTiny, a curated benchmark of 50 representative CTF challenges across binary exploitation, web, reverse engineering, forensics, and cryptography. Our findings identify optimal multi-agent coordination settings and lay the groundwork for future LLM agent research in cybersecurity. We make CTFTiny open source to public https://github.com/NYU-LLM-CTF/CTFTiny along with CTFJudge on https://github.com/NYU-LLM-CTF/CTFJudge.
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

**BountyBench: Dollar Impact of AI Agent Attackers and Defenders on Real-World Cybersecurity Systems** [[Paper](https://arxiv.org/pdf/2505.15216)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-07

Tags: `LLM` | `Agent` | `Bug Bounty` | `Benchmark`
<details><summary>Abstract</summary>
AI agents have the potential to significantly alter the cybersecurity landscape. Here, we introduce the first framework to capture offensive and defensive cyber-capabilities in evolving real-world systems. Instantiating this framework with BountyBench, we set up 25 systems with complex, real-world codebases. To capture the vulnerability lifecycle, we define three task types: Detect (detecting a new vulnerability), Exploit (exploiting a given vulnerability), and Patch (patching a given vulnerability). For Detect, we construct a new success indicator, which is general across vulnerability types and provides localized evaluation. We manually set up the environment for each system, including installing packages, setting up server(s), and hydrating database(s). We add 40 bug bounties, which are vulnerabilities with monetary awards from \$10 to \$30,485, covering 9 of the OWASP Top 10 Risks. To modulate task difficulty, we devise a new strategy based on information to guide detection, interpolating from identifying a zero day to exploiting a given vulnerability. We evaluate 10 agents: Claude Code, OpenAI Codex CLI with o3-high and o4-mini, and custom agents with o3-high, GPT-4.1, Gemini 2.5 Pro Preview, Claude 3.7 Sonnet Thinking, Qwen3 235B A22B, Llama 4 Maverick, and DeepSeek-R1. Given up to three attempts, the top-performing agents are Codex CLI: o3-high (12.5% on Detect, mapping to \$3,720; 90% on Patch, mapping to \$14,152), Custom Agent: Claude 3.7 Sonnet Thinking (67.5% on Exploit), and Codex CLI: o4-mini (90% on Patch, mapping to \$14,422). Codex CLI: o3-high, Codex CLI: o4-mini, and Claude Code are more capable at defense, achieving higher Patch scores of 90%, 90%, and 87.5%, compared to Exploit scores of 47.5%, 32.5%, and 57.5% respectively; while the custom agents are relatively balanced between offense and defense, achieving Exploit scores of 17.5-67.5% and Patch scores of 25-60%.
</details>

---

**AIRTBench: Measuring Autonomous AI Red Teaming Capabilities in Language Models** [[Paper](https://arxiv.org/pdf/2506.14682)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-06

Tags: `LLM` | `Red Teaming` | `Benchmark`
<details><summary>Abstract</summary>
We introduce AIRTBench, an AI red teaming benchmark for evaluating language models' ability to autonomously discover and exploit Artificial Intelligence and Machine Learning (AI/ML) security vulnerabilities. The benchmark consists of 70 realistic black-box capture-the-flag (CTF) challenges from the Crucible challenge environment on the Dreadnode platform, requiring models to write python code to interact with and compromise AI systems. Claude-3.7-Sonnet emerged as the clear leader, solving 43 challenges (61% of the total suite, 46.9% overall success rate), with Gemini-2.5-Pro following at 39 challenges (56%, 34.3% overall), GPT-4.5-Preview at 34 challenges (49%, 36.9% overall), and DeepSeek R1 at 29 challenges (41%, 26.9% overall). Our evaluations show frontier models excel at prompt injection attacks (averaging 49% success rates) but struggle with system exploitation and model inversion challenges (below 26%, even for the best performers). Frontier models are far outpacing open-source alternatives, with the best truly open-source model (Llama-4-17B) solving 7 challenges (10%, 1.0% overall), though demonstrating specialized capabilities on certain hard challenges. Compared to human security researchers, large language models (LLMs) solve challenges with remarkable efficiency completing in minutes what typically takes humans hours or days-with efficiency advantages of over 5,000x on hard challenges. Our contribution fills a critical gap in the evaluation landscape, providing the first comprehensive benchmark specifically designed to measure and track progress in autonomous AI red teaming capabilities.
</details>

---

**A Framework for Evaluating Emerging Cyberattack Capabilities of AI** [[Paper](https://arxiv.org/pdf/2503.11917)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-03

Tags: `LLM` | `Benchmark` | `Cyberattack Capability`
<details><summary>Abstract</summary>
As frontier AI models become more capable, evaluating their potential to enable cyberattacks is crucial for ensuring the safe development of Artificial General Intelligence (AGI). Current cyber evaluation efforts are often ad-hoc, lacking systematic analysis of attack phases and guidance on targeted defenses. This work introduces a novel evaluation framework that addresses these limitations by: (1) examining the end-to-end attack chain, (2) identifying gaps in AI threat evaluation, and (3) helping defenders prioritize targeted mitigations and conduct AI-enabled adversary emulation for red teaming. Our approach adapts existing cyberattack chain frameworks for AI systems. We analyzed over 12,000 real-world instances of AI involvement in cyber incidents, catalogued by Google's Threat Intelligence Group, to curate seven representative attack chain archetypes. Through a bottleneck analysis on these archetypes, we pinpointed phases most susceptible to AI-driven disruption. We then identified and utilized externally developed cybersecurity model evaluations focused on these critical phases. We report on AI's potential to amplify offensive capabilities across specific attack stages, and offer recommendations for prioritizing defenses. We believe this represents the most comprehensive AI cyber risk evaluation framework published to date.
</details>

---

**OCCULT: Evaluating Large Language Models for Offensive Cyber Operation Capabilities** [[Paper](https://arxiv.org/pdf/2502.15797)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025-02

Tags: `LLM` | `Benchmark` | `Offensive Cyber Operations`
<details><summary>Abstract</summary>
The prospect of artificial intelligence (AI) competing in the adversarial landscape of cyber security has long been considered one of the most impactful, challenging, and potentially dangerous applications of AI. Here, we demonstrate a new approach to assessing AI's progress towards enabling and scaling real-world offensive cyber operations (OCO) tactics in use by modern threat actors. We detail OCCULT, a lightweight operational evaluation framework that allows cyber security experts to contribute to rigorous and repeatable measurement of the plausible cyber security risks associated with any given large language model (LLM) or AI employed for OCO. We also prototype and evaluate three very different OCO benchmarks for LLMs that demonstrate our approach and serve as examples for building benchmarks under the OCCULT framework. Finally, we provide preliminary evaluation results to demonstrate how this framework allows us to move beyond traditional all-or-nothing tests, such as those crafted from educational exercises like capture-the-flag environments, to contextualize our indicators and warnings in true cyber threat scenarios that present risks to modern infrastructure. We find that there has been significant recent advancement in the risks of AI being used to scale realistic cyber threats. For the first time, we find a model (DeepSeek-R1) is capable of correctly answering over 90% of challenging offensive cyber knowledge tests in our Threat Actor Competency Test for LLMs (TACTL) multiple-choice benchmarks. We also show how Meta's Llama and Mistral's Mixtral model families show marked performance improvements over earlier models against our benchmarks where LLMs act as offensive agents in MITRE's high-fidelity offensive and defensive cyber operations simulation environment, CyberLayer.
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
/a> Abstract AI Summary 1 Introduction 2 Background 3 Benchmark 4 Evaluation 4.1 Experiment Setup 4.2 Evaluating Performance 4.3 Ablations 4.3.1 Ablation 1: Inject Summary. 4.3.2 Ablation 2: Structured Generation. 4.3.3 Ablation 3: Retrieval Augmented Generation. 5 Discussion 6 Conclusion and Future work 7 Potential Risks 8 Limitations A Additional analysis on different approaches of llama 3.1 and GPT4o B RAG knowledge bases C Specific cases where both LLMs failed D Penetration Testing Rules and Procedures E Additional Analyses F Prompts G Categories and Task Types H PTT & TODO List Footnotes References Information & Contributors Bibliometrics & Citations <i
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
Penetration testing is essential for assessing and strengthening system security against real-world threats, yet traditional workflows remain highly manual, expertise-intensive, and difficult to scale. Although recent advances in Large Language Models (LLMs) offer promising opportunities for automation, existing applications rely on simplistic prompting without task decomposition or domain adaptation, resulting in unreliable black-box behavior and limited insight into model capabilities across penetration testing stages. To address this gap, we introduce PentestEval, the first comprehensive benchmark for evaluating LLMs across six decomposed penetration testing stages: Information Collection, Weakness Gathering and Filtering, Attack Decision-Making, Exploit Generation and Revision. PentestEval integrates expert-annotated ground truth with a fully automated evaluation pipeline across 346 tasks covering all stages in 12 realistic vulnerable scenarios. Our stage-level evaluation of 9 widely used LLMs reveals generally weak performance and distinct limitations across the stages of penetration-testing workflow. End-to-end pipelines reach only 31% success rate, and existing LLM-powered systems such as PentestGPT, PentestAgent, and VulnBot exhibit similar limitations, with autonomous agents failing almost entirely. These findings highlight that autonomous penetration testing demands stronger structured reasoning, where modularization enhances each individual stage and improves overall performance. PentestEval provides the foundational benchmark needed for future research on fine-grained, stage-level evaluation, paving the way toward more reliable LLM-based automation.
</details>

---

**PenGym: Realistic training environment for reinforcement learning pentesting agents** [[Paper](https://www.sciencedirect.com/science/article/pii/S0167404824004450)] [[Code](https://github.com/cyb3rlab/PenGym)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/Computers%20%26%20Security-2025-blue.svg" alt="Computers &amp; Security">
  <img src="https://img.shields.io/badge/CCF-B-orange.svg" alt="CCF-B">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2025

Tags: `RL` | `Cyber Range` | `Penetration Testing`
<details><summary>Abstract</summary>
This paper presents PenGym as a realistic training environment for reinforcement-learning-based pentesting agents. It focuses on bridging simulation and practical pentesting workflows so agents can be evaluated under more realistic assumptions.
</details>

---

**AutoPenBench: Benchmarking Generative Agents for Penetration Testing** [[Paper](https://arxiv.org/pdf/2410.03225)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2024-10

Tags: `LLM` | `Agent` | `Benchmark` | `Penetration Testing`
<details><summary>Abstract</summary>
Generative AI agents, software systems powered by Large Language Models (LLMs), are emerging as a promising approach to automate cybersecurity tasks. Among the others, penetration testing is a challenging field due to the task complexity and the diverse strategies to simulate cyber-attacks. Despite growing interest and initial studies in automating penetration testing with generative agents, there remains a significant gap in the form of a comprehensive and standard framework for their evaluation and development. This paper introduces AutoPenBench, an open benchmark for evaluating generative agents in automated penetration testing. We present a comprehensive framework that includes 33 tasks, each representing a vulnerable system that the agent has to attack. Tasks are of increasing difficulty levels, including in-vitro and real-world scenarios. We assess the agent performance with generic and specific milestones that allow us to compare results in a standardised manner and understand the limits of the agent under test. We show the benefits of AutoPenBench by testing two agent architectures: a fully autonomous and a semi-autonomous supporting human interaction. We compare their performance and limitations. For example, the fully autonomous agent performs unsatisfactorily achieving a 21% Success Rate (SR) across the benchmark, solving 27% of the simple tasks and only one real-world task. In contrast, the assisted agent demonstrates substantial improvements, with 64% of SR. AutoPenBench allows us also to observe how different LLMs like GPT-4o or OpenAI o1 impact the ability of the agents to complete the tasks. We believe that our benchmark fills the gap with a standard and flexible framework to compare penetration testing agents on a common ground. We hope to extend AutoPenBench along with the research community by making it available under https://github.com/lucagioacchini/auto-pen-bench.
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

**PenGym: Pentesting Training Framework for Reinforcement Learning Agents** [[Paper](https://www.jaist.ac.jp/~razvan/publications/pengym_framework_rl_agents.pdf)] [[Code](https://github.com/cyb3rlab/PenGym)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/JAIST-2024-blue.svg" alt="JAIST">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2024

Tags: `RL` | `Cyber Range` | `Penetration Testing`
<details><summary>Abstract</summary>
PenGym introduces a pentesting training framework for reinforcement learning agents. It provides environments and interfaces for training, testing, and evaluating agents on penetration testing tasks using realistic workflow assumptions.
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
Large Language Models (LLMs) are being deployed across various domains today. However, their capacity to solve Capture the Flag (CTF) challenges in cybersecurity has not been thoroughly evaluated. To address this, we develop a novel method to assess LLMs in solving CTF challenges by creating a scalable, open-source benchmark database specifically designed for these applications. This database includes metadata for LLM testing and adaptive learning, compiling a diverse range of CTF challenges from popular competitions. Utilizing the advanced function calling capabilities of LLMs, we build a fully automated system with an enhanced workflow and support for external tool calls. Our benchmark dataset and automated framework allow us to evaluate the performance of five LLMs, encompassing both black-box and open-source models. This work lays the foundation for future research into improving the efficiency of LLMs in interactive cybersecurity tasks and automated task planning. By providing a specialized benchmark, our project offers an ideal platform for developing, testing, and refining LLM-based approaches to vulnerability detection and resolution. Evaluating LLMs on these challenges and comparing with human performance yields insights into their potential for AI-driven cybersecurity solutions to perform real-world threat management. We make our benchmark dataset open source to public https://github.com/NYU-LLM-CTF/NYU CTF Bench along with our playground automated framework https://github.com/NYU-LLM-CTF/llm ctf automation. DOI 10.52202/079017-1832 <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymou
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
We introduce HackSynth, a novel Large Language Model (LLM)-based agent capable of autonomous penetration testing. HackSynth's dual-module architecture includes a Planner and a Summarizer, which enable it to generate commands and process feedback iteratively. To benchmark HackSynth, we propose two new Capture The Flag (CTF)-based benchmark sets utilizing the popular platforms PicoCTF and OverTheWire. These benchmarks include two hundred challenges across diverse domains and difficulties, providing a standardized framework for evaluating LLM-based penetration testing agents. Based on these benchmarks, extensive experiments are presented, analyzing the core parameters of HackSynth, including creativity (temperature and top-p) and token utilization. Multiple open source and proprietary LLMs were used to measure the agent's capabilities. The experiments show that the agent performed best with the GPT-4o model, better than what the GPT-4o's system card suggests. We also discuss the safety and predictability of HackSynth's actions. Our findings indicate the potential of LLM-based agents in advancing autonomous penetration testing and the importance of robust safeguards. HackSynth and the benchmarks are publicly available to foster research on autonomous cybersecurity solutions.
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
Language Model (LM) agents for cybersecurity that are capable of autonomously identifying vulnerabilities and executing exploits have potential to cause real-world impact. Policymakers, model providers, and researchers in the AI and cybersecurity communities are interested in quantifying the capabilities of such agents to help mitigate cyberrisk and investigate opportunities for penetration testing. Toward that end, we introduce Cybench, a framework for specifying cybersecurity tasks and evaluating agents on those tasks. We include 40 professional-level Capture the Flag (CTF) tasks from 4 distinct CTF competitions, chosen to be recent, meaningful, and spanning a wide range of difficulties. Each task includes its own description, starter files, and is initialized in an environment where an agent can execute commands and observe outputs. Since many tasks are beyond the capabilities of existing LM agents, we introduce subtasks for each task, which break down a task into intermediary steps for a more detailed evaluation. To evaluate agent capabilities, we construct a cybersecurity agent and evaluate 8 models: GPT-4o, OpenAI o1-preview, Claude 3 Opus, Claude 3.5 Sonnet, Mixtral 8x22b Instruct, Gemini 1.5 Pro, Llama 3 70B Chat, and Llama 3.1 405B Instruct. For the top performing models (GPT-4o and Claude 3.5 Sonnet), we further investigate performance across 4 agent scaffolds (structed bash, action-only, pseudoterminal, and web search). Without subtask guidance, agents leveraging Claude 3.5 Sonnet, GPT-4o, OpenAI o1-preview, and Claude 3 Opus successfully solved complete tasks that took human teams up to 11 minutes to solve. In comparison, the most difficult task took human teams 24 hours and 54 minutes to solve. All code and data are publicly available at https://cybench.github.io.
</details>

---

**Towards Dynamic Capture-The-Flag Training Environments For Reinforcement Learning Offensive Security Agents** [[Paper](https://ieeexplore.ieee.org/abstract/document/10020389)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/IEEE-2023-blue.svg" alt="IEEE">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2023

Tags: `RL` | `CTF` | `Offensive Security` | `Cyber Range`
<details><summary>Abstract</summary>
In this paper, we propose a formalised process for the generation of dynamically generated SQL queries that are vulnerable to SQL injection attacks for the trai
</details>

---

**NASimEmu: Network Attack Simulator & Emulator for Training Agents Generalizing to Novel Scenarios** [[Paper](https://arxiv.org/abs/2305.17246)] [[Code](https://github.com/jaromiru/NASimEmu)] [[Project](https://github.com/jaromiru/NASimEmu-agents)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2023

Tags: `RL` | `Cyber Range` | `Network Attack` | `Benchmark`
<details><summary>Abstract</summary>
Current frameworks for training offensive penetration testing agents with deep reinforcement learning struggle to produce agents that perform well in real-world scenarios, due to the reality gap in simulation-based frameworks and the lack of scalability in emulation-based frameworks. Additionally, existing frameworks often use an unrealistic metric that measures the agents' performance on the training data. NASimEmu, a new framework introduced in this paper, addresses these issues by providing both a simulator and an emulator with a shared interface. This approach allows agents to be trained in simulation and deployed in the emulator, thus verifying the realism of the used abstraction. Our framework promotes the development of general agents that can transfer to novel scenarios unseen during their training. For the simulation part, we adopt an existing simulator NASim and enhance its realism. The emulator is implemented with industry-level tools, such as Vagrant, VirtualBox, and Metasploit. Experiments demonstrate that a simulation-trained agent can be deployed in emulation, and we show how to use the framework to train a general agent that transfers into novel, structurally different scenarios. NASimEmu is available as open-source.
</details>

---

**A Multiagent CyberBattleSim for RL Cyber Operation Agents** [[Paper](https://arxiv.org/pdf/2304.11052.pdf)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2023

Tags: `RL` | `CyberBattleSim` | `Multi-Agent`
<details><summary>Abstract</summary>
Hardening cyber physical assets is both crucial and labor-intensive. Recently, Machine Learning (ML) in general and Reinforcement Learning RL) more specifically has shown great promise to automate tasks that otherwise would require significant human insight/intelligence. The development of autonomous RL agents requires a suitable training environment that allows us to quickly evaluate various alternatives, in particular how to arrange training scenarios that pit attackers and defenders against each other. CyberBattleSim is a training environment that supports the training of red agents, i.e., attackers. We added the capability to train blue agents, i.e., defenders. The paper describes our changes and reports on the results we obtained when training blue agents, either in isolation or jointly with red agents. Our results show that training a blue agent does lead to stronger defenses against attacks. In particular, training a blue agent jointly with a red agent increases the blue agent's capability to thwart sophisticated red agents.
</details>

---

**CyGIL: A Cyber Gym for Training Autonomous Agents over Emulated Network Systems** [[Paper](https://arxiv.org/abs/2109.03331)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Unavailable-lightgrey" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2021

Tags: `RL` | `Cyber Range` | `APT`
<details><summary>Abstract</summary>
Given the success of reinforcement learning (RL) in various domains, it is promising to explore the application of its methods to the development of intelligent and autonomous cyber agents. Enabling this development requires a representative RL training environment. To that end, this work presents CyGIL: an experimental testbed of an emulated RL training environment for network cyber operations. CyGIL uses a stateless environment architecture and incorporates the MITRE ATT&CK framework to establish a high fidelity training environment, while presenting a sufficiently abstracted interface to enable RL training. Its comprehensive action space and flexible game design allow the agent training to focus on particular advanced persistent threat (APT) profiles, and to incorporate a broad range of potential threats and vulnerabilities. By striking a balance between fidelity and simplicity, it aims to leverage state of the art RL algorithms for application to real-world cyber defence.
</details>

---

**CybORG: A Gym for the Development of Autonomous Cyber Agents** [[Paper](https://arxiv.org/abs/2108.09118)] [[Code](https://github.com/cage-challenge/CybORG)]
<div style="display: flex; flex-wrap: wrap; align-items: center; gap: 4px; margin: 2px 0 0;">
  <img src="https://img.shields.io/badge/arXiv-ID-b31b1b.svg" alt="arXiv">
  <img src="https://img.shields.io/badge/Rank-N%2FA-lightgrey.svg" alt="Rank-N/A">
  <img src="https://img.shields.io/badge/Website-Unavailable-lightgrey" alt="Website">
  <img src="https://img.shields.io/badge/Paper-blue.svg" alt="Type-Paper">
  <img src="https://img.shields.io/badge/Code-Available-181717" alt="Code">
  <img src="https://img.shields.io/badge/Type-Benchmark-orange.svg" alt="Type-Benchmark">
</div>
Published: 2021

Tags: `RL` | `Cyber Range` | `Autonomous Cyber Agents`
<details><summary>Abstract</summary>
Autonomous Cyber Operations (ACO) involves the development of blue team (defender) and red team (attacker) decision-making agents in adversarial scenarios. To support the application of machine learning algorithms to solve this problem, and to encourage researchers in this field to attend to problems in the ACO setting, we introduce CybORG, a work-in-progress gym for ACO research. CybORG features a simulation and emulation environment with a common interface to facilitate the rapid training of autonomous agents that can then be tested on real-world systems. Initial testing demonstrates the feasibility of this approach.
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
By 2028 most cybersecurity actions will be autonomous, with humans teleoperating. We present the first classification of autonomy levels in cybersecurity and introduce Cybersecurity AI (CAI), an open-source framework that democratizes advanced security testing through specialized AI agents. Through rigorous empirical evaluation, we demonstrate that CAI consistently outperforms state-of-the-art results in CTF benchmarks, solving challenges across diverse categories with significantly greater efficiency -up to 3,600x faster than humans in specific tasks and averaging 11x faster overall. CAI achieved first place among AI teams and secured a top-20 position worldwide in the "AI vs Human" CTF live Challenge, earning a monetary reward of $750. Based on our results, we argue against LLM-vendor claims about limited security capabilities. Beyond cybersecurity competitions, CAI demonstrates real-world effectiveness, reaching top-30 in Spain and top-500 worldwide on Hack The Box within a week, while dramatically reducing security testing costs by an average of 156x. Our framework transcends theoretical benchmarks by enabling non-professionals to discover significant security bugs (CVSS 4.3-7.5) at rates comparable to experts during bug bounty exercises. By combining modular agent design with seamless tool integration and human oversight (HITL), CAI addresses critical market gaps, offering organizations of all sizes access to AI-powered bug bounty security testing previously available only to well-resourced firms -thereby challenging the oligopolistic ecosystem currently dominated by major bug bounty platforms.
</details>

---
