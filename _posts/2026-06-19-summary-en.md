---
layout: default
title: "Horizon Summary: 2026-06-19 (EN)"
date: 2026-06-19
lang: en
---

> From 51 items, 32 important content pieces were selected

---

1. [GLM-5.2: Most Powerful Open-Weight LLM Released](#item-1) ⭐️ 9.0/10
2. [Poolside Releases Laguna M.1: 225B MoE Model for Agentic Coding](#item-2) ⭐️ 9.0/10
3. [Zero-Touch OAuth for MCP Enables Enterprise Managed Auth](#item-3) ⭐️ 8.0/10
4. [10K GitHub Repos Found Distributing Trojan Malware](#item-4) ⭐️ 8.0/10
5. [Hospitals and universities repurpose drugs at 90% lower cost](#item-5) ⭐️ 8.0/10
6. [AI Flips Code Economics: Cheap, Disposable, Demands Discipline](#item-6) ⭐️ 8.0/10
7. [AI Reasoning Model Helps Diagnose Rare Childhood Diseases](#item-7) ⭐️ 8.0/10
8. [AI Chemist Improves Key Drug-Making Reaction](#item-8) ⭐️ 8.0/10
9. [MosaicLeaks: LLM Research Agents Leak Secrets via Web Queries](#item-9) ⭐️ 8.0/10
10. [Beyond LoRA: Exploring Advanced PEFT Methods](#item-10) ⭐️ 8.0/10
11. [Guide to Benchmarking Open Models on Custom Tooling](#item-11) ⭐️ 8.0/10
12. [Deploy AI Models from Hugging Face Hub to Robots](#item-12) ⭐️ 8.0/10
13. [Suitcase Robot Gets 'High' via Real Gas Sensor Tied to LLM Sampler](#item-13) ⭐️ 8.0/10
14. [GLM-5.2 (744B, 2-bit) runs at 7.3 tok/s on 4×3090 + 192GB RAM](#item-14) ⭐️ 8.0/10
15. [Open-Source Models Overtake Proprietary in Market Share](#item-15) ⭐️ 8.0/10
16. [Ubiquiti Launches Enterprise NAS with ZFS and 25GbE](#item-16) ⭐️ 7.0/10
17. [Cornell CS 6120 Advanced Compilers Self-Guided Online](#item-17) ⭐️ 7.0/10
18. [New Tool Probes LLM Recognition of Individuals](#item-18) ⭐️ 7.0/10
19. [Datasette Apps: Host Sandboxed HTML/JS Apps with SQL Queries](#item-19) ⭐️ 7.0/10
20. [MolmoMotion: Language-Guided 3D Motion Forecasting](#item-20) ⭐️ 7.0/10
21. [North Mini Code Gets 4-bit Quant, Ollama & OpenRouter Support](#item-21) ⭐️ 7.0/10
22. [Local Qwen vs Cloud Opus: Different Tools, Not Inferior](#item-22) ⭐️ 7.0/10
23. [SupraLabs Releases SupraVL-Nano-900k, a Tiny VLM Built from Scratch](#item-23) ⭐️ 7.0/10
24. [DeusData/codebase-memory-mcp: Fast Code Knowledge Graph](#item-24) ⭐️ 7.0/10
25. [uv 0.11.22 Released with Enhancements and Preview Features](#item-25) ⭐️ 6.0/10
26. [Beyond .gitignore: Alternative Git Ignore Methods](#item-26) ⭐️ 6.0/10
27. [datasette-acl 0.6a0 expands to general resource-sharing](#item-27) ⭐️ 6.0/10
28. [GLM Founder Hints at New Model 'GLM-fable'](#item-28) ⭐️ 6.0/10
29. [GLM-5.2 Runs on CPU at 4-5.5 tok/s with MTP Drafting](#item-29) ⭐️ 6.0/10
30. [Headroom: Compress LLM Inputs by 60-95% Without Losing Accuracy](#item-30) ⭐️ 6.0/10
31. [CodeGraph Pre-Indexes Codebases into Knowledge Graphs for AI Assistants](#item-31) ⭐️ 6.0/10
32. [Omnigent: A Meta-Harness for AI Agents](#item-32) ⭐️ 6.0/10

---

<a id="item-1"></a>
## [GLM-5.2: Most Powerful Open-Weight LLM Released](https://simonwillison.net/2026/Jun/17/glm-52/#atom-everything) ⭐️ 9.0/10

Z.ai released GLM-5.2, a 753B parameter open-weight LLM with 1M token context under MIT license, which is likely the most powerful text-only open model. This release significantly advances open-weight AI, offering a competitive alternative to proprietary models like GPT-5.5 and Claude Opus, with top benchmark scores and a permissive license. GLM-5.2 uses Mixture of Experts with 40 active parameters, achieves 51 on the Artificial Analysis Intelligence Index (leading open model), and ranks 2nd on Code Arena WebDev leaderboard behind Claude Fable 5.

rss · Simon Willison · Jun 17, 23:58

**Background**: Open-weight LLMs make model parameters publicly available, allowing researchers and developers to use and modify them freely. Mixture of Experts (MoE) is a technique that activates only a subset of parameters per task, enabling large models to be more efficient. GLM-5.2 is the latest in Z.ai's GLM series, building on GLM-5.1 with a larger context window and improved performance.

<details><summary>References</summary>
<ul>
<li><a href="https://artificialanalysis.ai/articles/glm-5-2-is-the-new-leading-open-weights-model-on-the-artificial-analysis-intelligence-index">GLM-5.2 is the new leading open weights model on the Artificial Analysis Intelligence Index</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://docs.z.ai/guides/llm/glm-5.2">GLM-5.2 - Overview - Z.AI DEVELOPER DOCUMENT</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#open weights`, `#AI`, `#GLM-5.2`, `#Z.ai`

---

<a id="item-2"></a>
## [Poolside Releases Laguna M.1: 225B MoE Model for Agentic Coding](https://www.reddit.com/r/LocalLLaMA/comments/1u9b2i3/poolsidelagunam1_hugging_face_225ba23b/) ⭐️ 9.0/10

Poolside has released Laguna M.1, a 225B-parameter Mixture-of-Experts model with 23B active parameters per token, optimized for agentic coding and long-horizon tasks. It achieves competitive results on benchmarks like SWE-bench Verified (74.6%) and Terminal-Bench 2.0 (45.8%), and is available under the Apache 2.0 license. This release demonstrates that large sparse MoE models can rival frontier models in agentic coding while being open-weight and permissively licensed. It lowers the barrier for developers to deploy state-of-the-art coding agents in production. Laguna M.1 uses 256 experts with top-k=16 routing and auxiliary-loss-free load balancing, along with 70 layers (3 dense SwiGLU + 67 sparse MoE), global attention with 64 Q-heads and 8 KV-heads, and a 262,144-token context window. It supports interleaved thinking between tool calls and can enable or disable reasoning per request.

reddit · r/LocalLLaMA · /u/pmttyji · Jun 18, 16:30

**Background**: Mixture-of-Experts (MoE) is a neural network architecture that activates only a subset of parameters per token, enabling larger model capacity without proportional compute cost. Agentic coding refers to AI agents that autonomously write, debug, and refactor code across multi-file contexts. SwiGLU is a gated activation function that improves expressivity in transformer feed-forward layers.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/@dewasheesh.rana/mixture-of-experts-moe-the-architecture-that-lets-ai-scale-without-exploding-costs-632ce4aab3c6">Mixture of Experts ( MoE ): The Architecture That Lets AI... | Medium</a></li>
<li><a href="https://en.wikipedia.org/wiki/Agentic_coding">Agentic coding</a></li>
<li><a href="https://abdulkaderhelwan.medium.com/swiglu-activation-function-77627e0b2b52">SwiGLU Activation Function . SwiGLU (Swish-Gated Linear... | Medium</a></li>

</ul>
</details>

**Discussion**: The Reddit community is highly engaged, with many praising the Apache 2.0 license and the model's strong benchmark performance. Some users discuss the trade-offs of 256 experts and the auxiliary-loss-free load balancing technique, while others compare it to DeepSeek-V4 and Qwen3.5. Overall sentiment is positive, with excitement about open-weight agentic coding models.

**Tags**: `#LLM`, `#MoE`, `#agentic coding`, `#open-weight`, `#Hugging Face`

---

<a id="item-3"></a>
## [Zero-Touch OAuth for MCP Enables Enterprise Managed Auth](https://blog.modelcontextprotocol.io/posts/enterprise-managed-auth/) ⭐️ 8.0/10

A new Zero-Touch OAuth flow for the Model Context Protocol (MCP) isolates authentication from the agent's context window, using the ID-JAG token format to enable secure cross-application data sharing without user interaction. This simplifies enterprise adoption of AI tools by centralizing authentication and audit through identity providers like Okta and Microsoft, improving both security and user experience for non-technical users. The ID-JAG token format is an IETF draft (draft-ietf-oauth-identity-assertion-authz-grant) that leverages existing SSO trust to obtain cross-domain access tokens without interactive flows, and is not specific to MCP.

hackernews · niyikiza · Jun 18, 21:54 · [Discussion](https://news.ycombinator.com/item?id=48592163)

**Background**: The Model Context Protocol (MCP) is an open standard introduced by Anthropic in November 2024 for AI systems to integrate with external tools and data sources. Traditional OAuth flows require user interaction within the agent's context, which can be cumbersome and insecure. Zero-Touch OAuth moves this flow outside the agent, leveraging enterprise identity providers for seamless authentication.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Model_Context_Protocol">Model Context Protocol - Wikipedia</a></li>
<li><a href="https://modelcontextprotocol.io/docs/getting-started/intro">What is the Model Context Protocol (MCP)?</a></li>
<li><a href="https://dev.to/kanywst/id-jag-deep-dive-1mhp">ID-JAG Deep Dive - DEV Community</a></li>

</ul>
</details>

**Discussion**: Community members praised the isolation of auth flow from the agent's context as a security and UX improvement. Some expressed concerns about delegated access without user awareness, while others noted the ID-JAG format's broader applicability beyond MCP.

**Tags**: `#OAuth`, `#MCP`, `#enterprise security`, `#authentication`, `#token format`

---

<a id="item-4"></a>
## [10K GitHub Repos Found Distributing Trojan Malware](https://orchidfiles.com/github-repositories-distributing-malware/) ⭐️ 8.0/10

A security researcher discovered 10,000 GitHub repositories distributing Trojan malware, using automated tactics to evade detection and infect developer dependencies. This large-scale supply chain attack targets developers and open-source ecosystems, potentially compromising countless downstream projects and user systems. The malicious repositories use techniques like frequent commit deletions and pushes to appear active, targeting automated agents rather than humans to slip into dependency searches.

hackernews · theorchid · Jun 18, 11:45 · [Discussion](https://news.ycombinator.com/item?id=48583928)

**Background**: Supply chain attacks in open source involve injecting malware into popular libraries or repositories, which then spreads to users who unknowingly install the compromised code. GitHub is a primary platform for open-source software, making it a prime target for such attacks.

<details><summary>References</summary>
<ul>
<li><a href="https://orchidfiles.com/github-repositories-distributing-malware/">I discovered a large-scale malware distribution on GitHub</a></li>
<li><a href="https://www.webasha.com/blog/trojanized-github-repositories-target-gamers-and-developers-in-massive-malware-campaign">Trojanized GitHub Repositories Target... - Web Asha Technologies</a></li>
<li><a href="https://github.com/tstromberg/supplychain-attack-data">GitHub - tstromberg/ supplychain - attack -data: Data about all known...</a></li>

</ul>
</details>

**Discussion**: Commenters noted that the malware targets automated agents, not humans, and that similar impersonation attacks have affected their own projects. The discussion highlights the ease with which malicious repos blend in with legitimate ones.

**Tags**: `#malware`, `#supply chain attack`, `#GitHub`, `#security`, `#open source`

---

<a id="item-5"></a>
## [Hospitals and universities repurpose drugs at 90% lower cost](https://www.kcl.ac.uk/news/hospitals-and-universities-repurposing-drugs-at-90-lower-cost) ⭐️ 8.0/10

Hospitals and universities are repurposing existing drugs for new medical uses at a fraction of the cost, challenging traditional pharmaceutical pricing models. This approach could dramatically reduce healthcare costs by providing effective treatments at a fraction of the price, especially for rare diseases where new drug development is not profitable. For example, the cancer drug Avastin (bevacizumab) costs about $50 per dose when repurposed for macular degeneration, compared to $1,500 for the similar drug Lucentis.

hackernews · giuliomagnifico · Jun 18, 10:33 · [Discussion](https://news.ycombinator.com/item?id=48583386)

**Background**: Drug repurposing involves investigating existing FDA-approved drugs for new therapeutic purposes, which can reduce development time and costs. However, there is often no regulatory pathway to extend use without manufacturer consent, limiting widespread adoption.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/Drug_repurposing">Drug repurposing</a></li>
<li><a href="https://www.fda.gov/drugs/resources-drugs/drug-repurposing">Drug Repurposing | FDA</a></li>

</ul>
</details>

**Discussion**: Commenters shared personal experiences, such as using Avastin for eye disease and esketamine (Spravato) for depression, highlighting how repurposing can expose pricing inefficiencies. Some noted that without manufacturer consent, repurposing studies may not lead to approved new indications.

**Tags**: `#drug repurposing`, `#healthcare costs`, `#pharmaceuticals`, `#innovation`

---

<a id="item-6"></a>
## [AI Flips Code Economics: Cheap, Disposable, Demands Discipline](https://simonwillison.net/2026/Jun/17/charity-majors/#atom-everything) ⭐️ 8.0/10

Charity Majors argues that AI has made code generation effectively free and instant, turning code from a treasured asset into a disposable commodity, which demands more engineering discipline, not less. This insight highlights a paradigm shift in software engineering economics, forcing teams to rethink code quality, maintenance, and architecture in an era of cheap AI-generated code. Majors specifically notes that the economics of code production were 'turned upside down' in 2025, with lines of code becoming 'disposable and regenerable' practically overnight.

rss · Simon Willison · Jun 17, 17:12

**Background**: Traditionally, writing code was labor-intensive and expensive, so code was carefully crafted and reused. AI coding assistants like GitHub Copilot now generate code instantly, reducing marginal cost to near zero, but this can lead to technical debt if not managed with discipline.

**Tags**: `#ai-assisted-programming`, `#software-engineering`, `#generative-ai`, `#economics-of-code`

---

<a id="item-7"></a>
## [AI Reasoning Model Helps Diagnose Rare Childhood Diseases](https://openai.com/index/diagnose-rare-childhood-diseases) ⭐️ 8.0/10

Researchers used an OpenAI reasoning model to identify 18 new diagnoses in previously unsolved cases of rare childhood genetic diseases. This demonstrates a practical application of advanced AI reasoning in healthcare, potentially reducing the diagnostic odyssey for families with rare diseases and improving treatment outcomes. The model used is likely OpenAI o3 or o4-mini, which are designed for complex reasoning tasks. The diagnoses were made by analyzing clinical data, genetic information, and literature searches.

rss · OpenAI Blog · Jun 18, 08:00

**Background**: Rare genetic diseases affect millions of children worldwide, but diagnosis often takes years due to limited knowledge and specialist availability. AI reasoning models can process vast amounts of data and provide explainable diagnostic suggestions, aiding physicians in identifying conditions that might otherwise be missed.

<details><summary>References</summary>
<ul>
<li><a href="https://en.wikipedia.org/wiki/OpenAI_o3">OpenAI o3 - Wikipedia</a></li>
<li><a href="https://www.nature.com/articles/d41586-026-00290-9">AI succeeds in diagnosing rare diseases</a></li>

</ul>
</details>

**Tags**: `#AI`, `#healthcare`, `#rare diseases`, `#diagnosis`, `#OpenAI`

---

<a id="item-8"></a>
## [AI Chemist Improves Key Drug-Making Reaction](https://openai.com/index/ai-chemist-improves-reaction) ⭐️ 8.0/10

OpenAI and Molecule.one demonstrated a near-autonomous AI chemist powered by GPT-5.4 that successfully improved a challenging reaction used in medicinal chemistry. This advancement could accelerate drug discovery by automating complex chemical synthesis, reducing the time and cost of developing new medicines. The system combines GPT-5.4's reasoning with Molecule.one's Maria platform to autonomously plan and execute experiments, achieving improved yields for a key reaction.

rss · OpenAI Blog · Jun 17, 10:00

**Background**: Medicinal chemistry relies on efficient reactions to synthesize drug candidates. AI-driven autonomous systems can optimize reaction conditions faster than traditional trial-and-error methods. GPT-5.4 is OpenAI's latest model with native computer-use capabilities, enabling it to interact with lab equipment and software.

<details><summary>References</summary>
<ul>
<li><a href="https://molecule.one/">molecule.one - Chemistry AI for Autonomous Discovery</a></li>
<li><a href="https://openai.com/index/introducing-gpt-5-4/">Introducing GPT-5.4 - OpenAI</a></li>

</ul>
</details>

**Tags**: `#AI`, `#chemistry`, `#drug discovery`, `#GPT-5.4`, `#autonomous systems`

---

<a id="item-9"></a>
## [MosaicLeaks: LLM Research Agents Leak Secrets via Web Queries](https://huggingface.co/blog/ServiceNow/mosaicleaks) ⭐️ 8.0/10

Researchers introduced MosaicLeaks, a benchmark of 1,001 multi-hop research tasks that force LLM-powered deep research agents to inadvertently leak sensitive information from private documents through their web search queries. This highlights a critical privacy vulnerability in autonomous AI agents that combine private data with public web search, potentially exposing trade secrets, personal data, or confidential documents to adversaries who monitor query logs. The attack surface includes prompts, plugins, model access, data egress, and agent actions; the adversary never sees the private documents or agent reasoning, only the web queries generated by the agent.

rss · Hugging Face Blog · Jun 18, 18:13

**Background**: LLM-powered research agents can autonomously browse the web to answer complex questions, often accessing both private enterprise documents and public web corpora. MosaicLeaks treats the web queries as a leakage channel, showing that agents may inadvertently include sensitive details from private documents in their search queries, which can be observed by third parties.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2605.30727v1">MosaicLeaks: Privacy Risks in Querying-in-the-Open for Deep Research Agents - arXiv</a></li>
<li><a href="https://huggingface.co/blog/ServiceNow/mosaicleaks">MosaicLeaks: Can your research agent keep a secret? - Hugging Face</a></li>
<li><a href="https://www.linkedin.com/posts/rafaelpardinas_reinforcementlearning-privacy-aiagents-activity-7467183373233373184-ACfx">MosaicLeaks: Benchmarking Privacy Leaks in Deep Research Agents | Rafael Pardinas posted on the topic | LinkedIn</a></li>

</ul>
</details>

**Tags**: `#AI Safety`, `#Privacy`, `#LLM`, `#Security`, `#Research`

---

<a id="item-10"></a>
## [Beyond LoRA: Exploring Advanced PEFT Methods](https://huggingface.co/blog/peft-beyond-lora) ⭐️ 8.0/10

Hugging Face published a blog post investigating parameter-efficient fine-tuning (PEFT) methods beyond LoRA, comparing their performance and efficiency for large models. This analysis helps practitioners choose the best fine-tuning technique for their needs, potentially reducing computational costs while maintaining model quality. The blog covers methods like (IA)3 and others available in the PEFT library, evaluating trade-offs between parameter count, training speed, and downstream task performance.

rss · Hugging Face Blog · Jun 18, 00:00

**Background**: Parameter-efficient fine-tuning (PEFT) methods adapt large pretrained models by updating only a small fraction of parameters, reducing memory and storage needs. LoRA (Low-Rank Adaptation) is a popular PEFT technique that injects trainable low-rank matrices into model layers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/huggingface/peft">GitHub - huggingface/peft: 🤗 PEFT: State-of-the-art Parameter-Efficient Fine-Tuning.</a></li>
<li><a href="https://huggingface.co/docs/peft/en/index">PEFT · Hugging Face</a></li>
<li><a href="https://www.geeksforgeeks.org/deep-learning/fine-tuning-using-lora-and-qlora/">Fine-Tuning using LoRA and QLoRA - GeeksforGeeks</a></li>

</ul>
</details>

**Tags**: `#fine-tuning`, `#LoRA`, `#PEFT`, `#efficient ML`, `#transformers`

---

<a id="item-11"></a>
## [Guide to Benchmarking Open Models on Custom Tooling](https://huggingface.co/blog/is-it-agentic-enough) ⭐️ 8.0/10

Hugging Face published a practical guide on how to benchmark open-source AI models using your own tools and datasets to evaluate their agentic capabilities. This guide addresses a critical gap between standardized benchmarks and real-world deployment, helping practitioners assess whether open models are truly agentic enough for their specific use cases. The blog likely provides methodology for setting up custom evaluation pipelines, selecting appropriate metrics, and interpreting results for agentic tasks such as planning and tool use.

rss · Hugging Face Blog · Jun 18, 00:00

**Background**: Agentic AI refers to systems that can autonomously plan, decide, and execute tasks without constant human intervention. Standardized benchmarks like the Holistic Agent Leaderboard exist but are expensive and may not reflect real-world conditions, making custom benchmarking essential for production deployment.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2603.23749v1">Efficient Benchmarking of AI Agents - arXiv.org</a></li>
<li><a href="https://www.infoq.com/articles/evaluating-ai-agents-lessons-learned/">Evaluating AI Agents in Practice: Benchmarks ... - InfoQ</a></li>

</ul>
</details>

**Tags**: `#AI/ML`, `#benchmarking`, `#open-source`, `#agents`, `#Hugging Face`

---

<a id="item-12"></a>
## [Deploy AI Models from Hugging Face Hub to Robots](https://huggingface.co/blog/amazon/strands-lerobot-hub-to-hardware) ⭐️ 8.0/10

A blog post demonstrates how to deploy AI models from the Hugging Face Hub onto physical robots using Strands Agents and LeRobot, bridging the gap between AI model repositories and real-world hardware. This integration enables practical deployment of AI models in robotics, lowering the barrier for researchers and developers to test and run models on actual hardware, accelerating robotics research and industrial applications. Strands Agents is an open-source, model-driven SDK for building AI agents, while LeRobot provides models, datasets, and tools for real-world robotics in PyTorch. The combination allows seamless deployment from the Hub to hardware.

rss · Hugging Face Blog · Jun 17, 10:18

**Background**: Hugging Face Hub is a popular repository for pretrained AI models. LeRobot is a platform by Hugging Face for deep learning robotics experiments, offering standardized interfaces for diverse robot hardware. Strands Agents, developed by AWS, is an open-source SDK for building AI agents that can reason and act autonomously.

<details><summary>References</summary>
<ul>
<li><a href="https://aws.amazon.com/blogs/opensource/introducing-strands-agents-an-open-source-ai-agents-sdk/">Introducing Strands Agents, an Open Source AI Agents SDK | AWS Open Source Blog</a></li>
<li><a href="https://github.com/huggingface/lerobot">GitHub - huggingface/lerobot: LeRobot: Making AI for ...</a></li>

</ul>
</details>

**Tags**: `#robotics`, `#Hugging Face`, `#LeRobot`, `#AI deployment`, `#hardware`

---

<a id="item-13"></a>
## [Suitcase Robot Gets 'High' via Real Gas Sensor Tied to LLM Sampler](https://www.reddit.com/r/LocalLLaMA/comments/1u9a17y/my_suitcase_robot_gets_high_now_off_a_real_gas/) ⭐️ 8.0/10

A suitcase robot named Sparky uses an MQ-2 gas sensor to dynamically adjust LLM sampling parameters (temperature, top_p, top_k) in real time, causing its generated speech to become increasingly 'loopy' without any scripted behavior. This novel integration of a physical sensor with LLM sampling parameters demonstrates a creative approach to embodied AI, where environmental input directly influences model behavior in a non-scripted, emergent way. The MQ-2 sensor reads smoke concentration every 0.5 seconds, mapping it to a 0–10 phase that decays over minutes. As the phase climbs, temperature increases from 1.0 to ~1.6, top_p from 0.95 to 0.99, and top_k from 64 to 120, making the model's word choice more associative and less predictable.

reddit · r/LocalLLaMA · /u/CreativelyBankrupt · Jun 18, 15:52

**Background**: LLM sampling parameters like temperature, top_p, and top_k control the randomness and diversity of generated text. Higher temperature increases randomness, while higher top_p and top_k allow the model to consider a wider range of possible tokens. The MQ-2 is a metal oxide semiconductor sensor that detects combustible gases and smoke by measuring resistance changes in a heated tin dioxide layer.

<details><summary>References</summary>
<ul>
<li><a href="https://components101.com/sensors/mq2-gas-sensor">MQ2 Gas Sensor Pinout, Features, Equivalents & Datasheet</a></li>
<li><a href="https://lastminuteengineers.com/mq2-gas-senser-arduino-tutorial/">How MQ2 Gas/Smoke Sensor Works? & Interface it with Arduino Images MQ-2 Smoke/Gas Sensor: Datasheet, Pinout & Working Arduino - Gas Sensor | Arduino Tutorial MQ-2 Gas Sensor Arduino: Complete Guide to Smoke and LPG ... MQ-2.doc - Mouser Electronics MQ Gas Sensor Series - The Engineering Projects</a></li>
<li><a href="https://rumn.medium.com/setting-top-k-top-p-and-temperature-in-llms-3da3a8f74832">Setting Top - K , Top - P and Temperature in LLMs | Medium</a></li>

</ul>
</details>

**Discussion**: The community praised the project for its creativity and technical depth, with many finding the real-time sensor-to-sampler integration both humorous and impressive. Some users discussed the limitations of the MQ-2 sensor in distinguishing cannabis smoke from other smoke, and suggested alternative sensors like MQ-3 or MQ-135 for more specific detection.

**Tags**: `#LLM`, `#embodied AI`, `#creative coding`, `#sensor integration`, `#real-time sampling`

---

<a id="item-14"></a>
## [GLM-5.2 (744B, 2-bit) runs at 7.3 tok/s on 4×3090 + 192GB RAM](https://www.reddit.com/r/LocalLLaMA/comments/1u9mpty/glm52_744b_2bit_at_73_toks_on_43090_192gb_and_why/) ⭐️ 8.0/10

A user successfully runs the 744B-parameter GLM-5.2 Mixture-of-Experts model at 2-bit quantization (UD-IQ2_M) across four RTX 3090 GPUs and 192GB DDR5 RAM, achieving ~7.3 tokens per second decode speed. They also discovered that switching to IQ1_M quantization did not improve speed, while increasing CPU threads from 6 to 12 boosted performance by 22%. This demonstrates that massive MoE models like GLM-5.2 can be run locally on consumer-grade hardware, reducing reliance on cloud services. The detailed performance analysis provides practical optimization guidance for the community, especially regarding the trade-offs between quantization, CPU threads, and expert offloading. The model uses unsloth's UD-IQ2_M quantization (223GB on disk) with llama.cpp's glm-dsa architecture, offloading 19 of 75 MoE layers to GPUs (~83GB) and the rest to CPU RAM (~166GB). The user found that IQ1_M (213GB) offered identical speed to IQ2_M, confirming that offloaded expert decode is CPU compute-bound, not memory bandwidth-bound. They also noted that the x1 PCIe slot is useless for model splitting but works well for a separate single-card model.

reddit · r/LocalLLaMA · /u/Important_Quote_1180 · Jun 19, 00:06

**Background**: GLM-5.2 is a 744-billion-parameter Mixture-of-Experts (MoE) model with a 1-million-token context window, developed by Z.AI. MoE models activate only a subset of parameters per token (40B active for GLM-5.2), enabling efficient inference despite large total size. Quantization reduces model precision (e.g., 2-bit) to shrink memory footprint, while expert offloading places some layers on CPU RAM when GPU VRAM is insufficient. The llama.cpp framework supports running such models on consumer hardware with CUDA acceleration.

<details><summary>References</summary>
<ul>
<li><a href="https://www.buildfastwithai.com/blogs/glm-5-2-review-2026">GLM-5.2 Review 2026: Z.ai's 1M-Context AI Model</a></li>
<li><a href="https://huggingface.co/zai-org/GLM-5.2">zai-org/GLM-5.2 · Hugging Face</a></li>
<li><a href="https://github.com/ggml-org/llama.cpp/discussions/6235">GGML types IQ1_M and IQ2_M? · ggml-org/llama.cpp · Discussion #6235</a></li>

</ul>
</details>

**Discussion**: The Reddit post received high engagement (score 8.0/10) with users praising the detailed benchmarks and practical insights. Commenters agreed that the finding about IQ1_M not being faster is counterintuitive but well-explained by CPU compute limits. Some discussed alternative hardware configurations and the potential of using multiple x1 slots for sidecar models.

**Tags**: `#Local LLM`, `#MoE`, `#Inference Optimization`, `#Quantization`, `#Hardware Benchmark`

---

<a id="item-15"></a>
## [Open-Source Models Overtake Proprietary in Market Share](https://www.reddit.com/r/LocalLLaMA/comments/1u96545/oss_models_decisively_overtook_proprietary_models/) ⭐️ 8.0/10

Based on the last three months of OpenRouter data, open-source models have decisively overtaken proprietary models in market share for the first time. This milestone signals a major shift in the AI industry, as open-source models become the preferred choice for developers and businesses, potentially accelerating innovation and reducing costs. OpenRouter is a unified API marketplace providing access to over 300 AI models from 50+ providers, and its data reflects real-world usage patterns across the ecosystem.

reddit · r/LocalLLaMA · /u/Comfortable-Rock-498 · Jun 18, 13:21

**Background**: OpenRouter aggregates usage data from multiple AI model providers, offering a transparent view of market share trends. The rise of open-source models like Llama and Mistral has been fueled by their accessibility, customizability, and competitive performance.

<details><summary>References</summary>
<ul>
<li><a href="https://openrouter.ai/">OpenRouter</a></li>
<li><a href="https://openrouter.ai/collections/free-models">Free AI Models on OpenRouter | OpenRouter</a></li>
<li><a href="https://lzwjava.github.io/notes/2025-08-20-ai-model-marketplace-guide-en">OpenRouter AI Model Marketplace Guide</a></li>

</ul>
</details>

**Discussion**: The Reddit discussion is active, with many users celebrating the trend as a win for democratization, while some caution that the data may be skewed by free-tier usage or specific model popularity.

**Tags**: `#open-source`, `#AI models`, `#market share`, `#OpenRouter`, `#LLMs`

---

<a id="item-16"></a>
## [Ubiquiti Launches Enterprise NAS with ZFS and 25GbE](https://blog.ui.com/article/introducing-enterprise-nas) ⭐️ 7.0/10

Ubiquiti announced the Enterprise NAS (ENAS), a 16-bay rack-mount storage appliance built on the ZFS file system, featuring dual 25 Gbps SFP28 ports and redundant power supplies. This marks Ubiquiti's entry into the enterprise NAS market, offering a tightly integrated storage solution for its existing networking ecosystem, potentially challenging established vendors like Synology and QNAP. The ENAS includes 16 SATA bays (3.5/2.5-inch), M.2 NVMe slots for caching, dual 25GbE SFP28 and 10GbE RJ45 ports, and is priced at $3,999. It uses ZFS for data integrity, snapshots, and compression.

hackernews · ksec · Jun 18, 14:24 · [Discussion](https://news.ycombinator.com/item?id=48585866)

**Background**: ZFS is an advanced file system and volume manager known for data integrity via checksums, snapshots, and built-in RAID. Ubiquiti is primarily known for networking hardware like UniFi access points and switches. The ENAS integrates with Ubiquiti's UniFi ecosystem for centralized management.

<details><summary>References</summary>
<ul>
<li><a href="https://store.ui.com/us/en/products/enas">Enterprise NAS - Ubiquiti Store</a></li>
<li><a href="https://nascompares.com/news/unifi-enterprise-nas-enas-review-16-bays-zfs-25gbe-iscsi/">UniFi Enterprise NAS ENAS Review – 16 Bays, ZFS... - NAS Compares</a></li>
<li><a href="https://news.ycombinator.com/item?id=48585866">Ubiquiti : Enterprise NAS , Built on ZFS | Hacker News</a></li>

</ul>
</details>

**Discussion**: Community comments express excitement about Ubiquiti entering the NAS space but raise concerns about software reliability, citing past security incidents. Some question whether spinning drives can saturate 25GbE links, and others appreciate the lack of recurring fees.

**Tags**: `#Ubiquiti`, `#NAS`, `#ZFS`, `#enterprise storage`, `#networking`

---

<a id="item-17"></a>
## [Cornell CS 6120 Advanced Compilers Self-Guided Online](https://www.cs.cornell.edu/courses/cs6120/2025fa/self-guided/) ⭐️ 7.0/10

Cornell's CS 6120 advanced compilers course is now available as a self-guided online resource, providing free access to lectures and assignments on compiler optimization and dynamic compilation. This resource makes high-quality compiler education accessible to a global audience, benefiting students, researchers, and practitioners interested in compiler design and optimization. The course covers topics like dead code elimination, data flow analysis, dominator analysis, SSA form, and includes a section on dynamic compilation focused on trace compilation.

hackernews · ibobev · Jun 18, 11:04 · [Discussion](https://news.ycombinator.com/item?id=48583606)

**Background**: Compiler courses typically teach front-end parsing and basic optimization, while advanced courses delve into deeper optimization techniques and runtime systems. CS 6120 is designed for students who have already taken an introductory compilers course.

**Discussion**: Community comments note that the dynamic compilation section focuses on trace compilation, which some consider a dead end, and that many topics are standard for a first compiler course. The course is well-received overall, with multiple previous posts on Hacker News.

**Tags**: `#compilers`, `#education`, `#programming languages`, `#systems`

---

<a id="item-18"></a>
## [New Tool Probes LLM Recognition of Individuals](https://www.intheweights.com/) ⭐️ 7.0/10

A new website, intheweights.com, allows users to check how well various large language models (LLMs) recognize their name by querying multiple models in parallel and clustering responses. The tool reveals model biases and hallucination patterns in real-time. This tool provides a novel way to probe LLM behavior regarding individual recognition, highlighting issues of hallucination and bias that affect trust in AI systems. It also raises privacy concerns as users consider what traces they leave in model weights. The site queries frontier and small models in parallel, clusters responses, and assigns a recognition score. It can reveal hallucinations, such as attributing incorrect professions to users, and shows that smaller models like Haiku may have pruned knowledge.

hackernews · turtlesoup · Jun 18, 20:49 · [Discussion](https://news.ycombinator.com/item?id=48591348)

**Background**: Large language models (LLMs) can generate plausible but factually incorrect content, known as hallucinations. Model biases can also lead to unfair or inaccurate representations of individuals. This tool helps users understand how LLMs perceive them, based on the models' training data and architecture.

<details><summary>References</summary>
<ul>
<li><a href="https://arxiv.org/html/2512.02527v1">A Concise Review of Hallucinations in LLMs and their Mitigation</a></li>
<li><a href="https://arxiv.org/abs/2508.01781">[2508.01781] A comprehensive taxonomy of hallucinations in ... A Survey on Hallucination in Large Language Models ... Why language models hallucinate - OpenAI Detecting hallucinations in large language models using ... The rise of hallucination in large language models ... - Springer Frontiers | Survey and analysis of hallucinations in large ...</a></li>
<li><a href="https://arxiv.org/html/2411.10915v1">Bias in Large Language Models: Origin, Evaluation, and Mitigation</a></li>

</ul>
</details>

**Discussion**: Community comments express excitement about the tool but also caution about privacy, with many users refusing to use their real names. Users report varied results, including correct identifications, hallucinations (e.g., being labeled a soccer player), and model-specific quirks like Haiku claiming a person doesn't exist.

**Tags**: `#LLM`, `#AI`, `#privacy`, `#hallucination`, `#tool`

---

<a id="item-19"></a>
## [Datasette Apps: Host Sandboxed HTML/JS Apps with SQL Queries](https://simonwillison.net/2026/Jun/18/datasette-apps/#atom-everything) ⭐️ 7.0/10

Simon Willison released the datasette-apps plugin, which allows hosting custom HTML+JavaScript applications inside a sandboxed iframe that can execute read-only and configured write SQL queries against Datasette data. This plugin transforms Datasette from a data publishing tool into a platform for building interactive, custom web applications directly on top of SQLite databases, expanding its utility for developers and data analysts. Apps run in an iframe with sandbox="allow-scripts allow-forms" and an injected CSP header that blocks outbound HTTP requests, preventing data exfiltration. They can use JavaScript to query Datasette's API, and write queries require pre-configured stored queries.

rss · Simon Willison · Jun 18, 23:58

**Background**: Datasette is an open-source tool for exploring and publishing SQLite databases, with a plugin system that extends its functionality. The datasette-apps plugin builds on Datasette's JSON API and the concept of sandboxed iframes, inspired by Claude Artifacts and the author's earlier experiments with vibe-coded HTML tools.

<details><summary>References</summary>
<ul>
<li><a href="https://datasette.io/plugins">Datasette Plugins</a></li>
<li><a href="https://docs.datasette.io/en/stable/plugins.html">Plugins - Datasette documentation</a></li>
<li><a href="https://www.w3schools.com/tags/att_iframe_sandbox.asp">HTML iframe sandbox Attribute - W3Schools</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#plugin`, `#sql`, `#web-applications`, `#sandbox`

---

<a id="item-20"></a>
## [MolmoMotion: Language-Guided 3D Motion Forecasting](https://huggingface.co/blog/allenai/molmomotion) ⭐️ 7.0/10

Allen AI has released MolmoMotion, a 4-billion-parameter vision-language model that forecasts 3D point trajectories of objects based on natural-language action instructions. This enables more intuitive human-robot interaction by allowing users to command robots with natural language, and it advances motion prediction for robotics, video generation, and autonomous systems. MolmoMotion represents motion as object-attached 3D points in world space, which is class-agnostic, view-stable, and compact. The model is open-source and includes a benchmark dataset, MolmoMotion-1M, and an evaluation suite, PointMotionBench.

rss · Hugging Face Blog · Jun 17, 15:26

**Background**: 3D motion forecasting predicts how objects will move over time, which is critical for robotics and autonomous driving. Traditional methods often rely on class-specific or view-dependent representations, limiting generalization. Language-guided models like MolmoMotion combine natural language understanding with spatial reasoning to enable more flexible and intuitive control.

<details><summary>References</summary>
<ul>
<li><a href="https://allenai.org/blog/molmo-motion">MolmoMotion: Language-guided 3D motion forecasting | Ai2</a></li>
<li><a href="https://huggingface.co/blog/allenai/molmomotion">MolmoMotion: Language-guided 3D motion forecasting - Hugging Face</a></li>

</ul>
</details>

**Tags**: `#3D motion forecasting`, `#language-guided AI`, `#robotics`, `#Hugging Face`

---

<a id="item-21"></a>
## [North Mini Code Gets 4-bit Quant, Ollama & OpenRouter Support](https://www.reddit.com/r/LocalLLaMA/comments/1u9dqlm/updates_on_north_mini_code_4_bit_quant_ollama/) ⭐️ 7.0/10

North Mini Code is now available as a 4-bit quantized model on Hugging Face, requiring only about 20 GB of RAM, and is supported on Ollama and other llama.cpp-based runtimes, as well as via the OpenRouter API. This update significantly lowers the hardware barrier for running North Mini Code locally, enabling more developers to experiment with and deploy the model on consumer-grade hardware like Macs, while also providing cloud API access via OpenRouter for scalable usage. The 4-bit quantized model requires approximately 20 GB of RAM, making it feasible to run on many modern laptops. Ollama integration allows seamless local deployment, while OpenRouter provides a unified API endpoint for accessing the model without local hardware.

reddit · r/LocalLLaMA · /u/nick_frosst · Jun 18, 18:09

**Background**: 4-bit quantization reduces the precision of model weights from 32-bit floating point to 4-bit integers, drastically cutting memory usage and enabling larger models to run on limited hardware. Ollama is a popular open-source tool for running LLMs locally with minimal setup, while OpenRouter offers a multi-model API gateway that simplifies access to various AI models.

<details><summary>References</summary>
<ul>
<li><a href="https://medium.com/data-science/democratizing-llms-4-bit-quantization-for-optimal-llm-inference-be30cf4e0e34">Democratizing LLMs: 4 - bit Quantization for Optimal LLM ... | Medium</a></li>
<li><a href="https://tech-insider.org/ollama-tutorial-run-llm-locally-2026/">How to Run LLMs Locally with Ollama in 11 Steps [2026]</a></li>
<li><a href="https://openrouter.ai/docs/api/reference/overview">OpenRouter API Reference | Complete API Documentation</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#quantization`, `#Ollama`, `#local deployment`, `#OpenRouter`

---

<a id="item-22"></a>
## [Local Qwen vs Cloud Opus: Different Tools, Not Inferior](https://www.reddit.com/r/LocalLLaMA/comments/1u9fxmb/local_qwen_isnt_a_worse_opus_its_a_different_tool/) ⭐️ 7.0/10

A Reddit discussion argues that local Qwen models should not be viewed as inferior to Anthropic's Claude Opus, but rather as tools optimized for different use cases such as privacy, offline access, and customization. This perspective helps clarify the trade-offs between local and cloud-based LLMs, guiding users to choose the right model for their specific needs rather than assuming cloud models are always superior. The discussion highlights that Qwen models, especially the 8B version, offer strong performance on diverse datasets while running locally, whereas Opus excels in agentic reasoning and complex cloud-based tasks.

reddit · r/LocalLLaMA · /u/cafedude · Jun 18, 19:30

**Background**: Qwen is a series of open-source language models developed by Alibaba, designed to run locally on consumer hardware. Claude Opus is Anthropic's flagship cloud-based model, known for advanced reasoning and safety features. Local models prioritize privacy and offline use, while cloud models offer greater computational resources and integration.

<details><summary>References</summary>
<ul>
<li><a href="https://grokipedia.com/page/Qwen_language_model">Qwen (language model)</a></li>
<li><a href="https://www.anthropic.com/news/claude-opus-4-8">Introducing Claude Opus 4.8 \ Anthropic</a></li>
<li><a href="https://huggingface.co/Qwen">Qwen (Qwen) - Hugging Face</a></li>

</ul>
</details>

**Discussion**: Commenters generally agree with the nuanced view, noting that Qwen is better for sensitive data and customization, while Opus is unmatched for complex reasoning tasks. Some debate the exact performance gap, but most emphasize use-case-driven selection.

**Tags**: `#local LLMs`, `#Qwen`, `#model comparison`, `#AI deployment`

---

<a id="item-23"></a>
## [SupraLabs Releases SupraVL-Nano-900k, a Tiny VLM Built from Scratch](https://www.reddit.com/r/LocalLLaMA/comments/1u9q6m2/new_model_supralabs_just_released_supravlnano900k/) ⭐️ 7.0/10

SupraLabs has released SupraVL-Nano-900k, a vision-language model with only 900k parameters, trained entirely from scratch on the Flickr8k dataset. The entire architecture, including a CNN visual encoder, GPT-2-style decoder, and BPE tokenizer, is documented in a single Jupyter notebook. This model serves as an educational blueprint, making the inner workings of vision-language models transparent and accessible to learners. It demystifies complex components like prefix concatenation fusion and adaptive average pooling, which are often hidden in larger black-box models. The model uses a 4×4 spatial grid from AdaptiveAvgPool to produce 16 visual tokens, which are prepended to 48 text tokens via prefix concatenation fusion. It has 3 transformer decoder layers with 128-dimensional embeddings and 4 attention heads, and uses weight tying between token embedding and LM head.

reddit · r/LocalLLaMA · /u/Dangerous_Try3619 · Jun 19, 02:53

**Background**: Vision-language models (VLMs) typically combine a visual encoder (like CLIP) with a large language model (LLM) via fusion layers, making them complex and hard to understand. SupraVL-Nano-900k simplifies this by using a small CNN encoder and a GPT-2-style decoder, with a straightforward prefix concatenation fusion strategy. The model is trained on Flickr8k, a small dataset of 8,000 images with captions, making it feasible to train on free hardware like Google Colab.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/gokayfem/Awesome-VLM-Architectures/blob/main/README.md">awesome-vlm-architectures/README.md at main - GitHub</a></li>
<li><a href="https://arxiv.org/html/2511.17793v1">Attention Guided Alignment in Efficient Vision-Language Models - arXiv</a></li>

</ul>
</details>

**Tags**: `#Vision-Language Model`, `#Educational`, `#Open Source`, `#Transformer`, `#CNN`

---

<a id="item-24"></a>
## [DeusData/codebase-memory-mcp: Fast Code Knowledge Graph](https://github.com/DeusData/codebase-memory-mcp) ⭐️ 7.0/10

A new open-source MCP server called codebase-memory-mcp indexes entire codebases into a persistent knowledge graph, enabling sub-millisecond queries and claiming 99% fewer tokens compared to traditional file-scanning approaches. This tool significantly reduces token usage and latency for AI coding assistants, making code understanding more efficient and cost-effective for developers working with large codebases. It supports 158 programming languages, runs as a single static binary with zero dependencies, and is written in C for high performance. The knowledge graph is persistent, meaning it does not need to be rebuilt on every query.

ossinsight · DeusData · Jun 19, 05:33

**Background**: MCP (Model Context Protocol) is a protocol that allows AI models to interact with external tools and data sources. Knowledge graphs for codebases store relationships between symbols, functions, and files, enabling faster retrieval than scanning files line by line. Similar projects like CodeGraph and Graphify also aim to provide pre-indexed code knowledge for AI agents.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/colbymchenry/codegraph">GitHub - colbymchenry/codegraph: Pre-indexed code knowledge ...</a></li>
<li><a href="https://graphify.net/">Graphify — Open-Source Knowledge Graph Skill for AI Coding ...</a></li>

</ul>
</details>

**Tags**: `#code intelligence`, `#knowledge graph`, `#MCP`, `#developer tools`, `#C`

---

<a id="item-25"></a>
## [uv 0.11.22 Released with Enhancements and Preview Features](https://github.com/astral-sh/uv/releases/tag/0.11.22) ⭐️ 6.0/10

uv 0.11.22, released on June 18, 2026, introduces enhancements such as publishing wheels before sdists in uv publish and new environment variables (TY and RUFF) for specifying binaries used by uv format and uv check. It also adds preview features including configurable preview settings in uv.toml and pyproject.toml, and SARIF support for uv audit output. This release improves the developer experience for Python package management by streamlining publishing workflows and offering more flexible configuration. The preview features, especially SARIF audit output, pave the way for better integration with security and compliance tools. The new TY and RUFF environment variables allow users to specify custom paths for the formatter and linter binaries. The SARIF output for uv audit enables standardized security audit reporting that can be consumed by CI/CD systems and code review platforms.

github · github-actions[bot] · Jun 18, 23:05

**Background**: uv is a fast Python package and project manager written in Rust, developed by Astral. It aims to replace tools like pip, pip-tools, and virtualenv with a single, high-performance binary. Preview features in uv are experimental capabilities that can be enabled via configuration or command-line flags, allowing users to test upcoming functionality before it becomes stable.

<details><summary>References</summary>
<ul>
<li><a href="https://docs.astral.sh/uv/concepts/preview/">Preview features | uv</a></li>
<li><a href="https://docs.astral.sh/uv/reference/cli/">Commands | uv - Astral</a></li>
<li><a href="https://github.com/astral-sh/uv/releases">Releases: astral-sh/uv - GitHub</a></li>

</ul>
</details>

**Tags**: `#python`, `#package-manager`, `#release`, `#uv`

---

<a id="item-26"></a>
## [Beyond .gitignore: Alternative Git Ignore Methods](https://nelson.cloud/.gitignore-isnt-the-only-way-to-ignore-files-in-git/) ⭐️ 6.0/10

A recent article highlights that Git offers multiple ways to ignore files beyond the common .gitignore, including the per-repository .git/info/exclude file and a global exclude file configured via git config. Understanding these alternatives helps developers keep .gitignore clean of personal or environment-specific entries, improving collaboration and reducing accidental commits across projects. The .git/info/exclude file is local to a repository and not committed, while the global exclude file (often ~/.config/git/ignore) applies to all repositories on the system.

hackernews · FergusArgyll · Jun 18, 10:29 · [Discussion](https://news.ycombinator.com/item?id=48583356)

**Background**: Git uses pattern-matching rules to decide which files to ignore. The most common method is a .gitignore file in the repository, which is shared with all contributors. However, Git also supports local ignore rules that are not shared, useful for personal preferences like IDE files or temporary notes.

<details><summary>References</summary>
<ul>
<li><a href="https://stackoverflow.com/questions/43593697/how-do-i-create-add-to-a-git-info-exclude-file-to-ignore-files-locally">How do I create/ add to a .git/info/exclude file to ignore ...</a></li>
<li><a href="https://git-scm.com/docs/gitignore">Git - gitignore Documentation</a></li>
<li><a href="https://docs.github.com/en/get-started/git-basics/ignoring-files">Ignoring files - GitHub Docs</a></li>

</ul>
</details>

**Discussion**: Commenters praised the global exclude feature for avoiding clutter in project .gitignore files, and one user suggested using .gitattributes to ignore diffs for files like package-lock.json. Another recommended using ~/.config/git/ignore as the standard location for global ignores.

**Tags**: `#Git`, `#Version Control`, `#Developer Tools`, `#Best Practices`

---

<a id="item-27"></a>
## [datasette-acl 0.6a0 expands to general resource-sharing](https://simonwillison.net/2026/Jun/18/datasette-acl/#atom-everything) ⭐️ 6.0/10

Datasette-acl 0.6a0 has been released, expanding from table-only permissions to a general resource-sharing system for multi-user Datasette instances. This release enables finer-grained access control across various resources in Datasette, making it more suitable for collaborative data platforms. The plugin is under active development and previously only supported table-level permissions like insert-row; this release lays groundwork for broader resource management.

rss · Simon Willison · Jun 18, 19:03

**Background**: Datasette is an open-source tool for exploring and publishing data. The datasette-acl plugin provides access control lists for multi-user Datasette instances, allowing administrators to manage who can access specific resources.

<details><summary>References</summary>
<ul>
<li><a href="https://pypi.org/project/datasette-acl/">datasette - acl · PyPI</a></li>
<li><a href="https://simonwillison.net/2026/Jun/18/datasette-acl/">Release: datasette - acl 0.6a0 | Simon Willison’s Weblog</a></li>
<li><a href="https://datasette.io/">Datasette : An open source multi-tool for exploring and publishing data</a></li>

</ul>
</details>

**Tags**: `#datasette`, `#access-control`, `#plugin`, `#permissions`

---

<a id="item-28"></a>
## [GLM Founder Hints at New Model 'GLM-fable'](https://www.reddit.com/r/LocalLLaMA/comments/1u96jof/glms_founder_says_glmfable_before_the_end_of_the/) ⭐️ 6.0/10

The founder of GLM (Zhipu AI) hinted at a new model called GLM-fable, suggesting it may be released before the end of the year. This announcement signals Zhipu AI's continued push in the competitive LLM space, potentially offering a new open-weight model that could rival existing frontier models. No technical details or benchmarks have been provided yet; the name 'fable' may imply a focus on storytelling or reasoning capabilities.

reddit · r/LocalLLaMA · /u/Charuru · Jun 18, 13:38

**Background**: GLM is a series of large language models developed by Zhipu AI, a Chinese AI company. Their latest open-source model, GLM-4.5, features 355B parameters with MoE architecture and strong agentic capabilities. The company also offers GLM-5.2 and GLM-5-Turbo for coding tasks.

<details><summary>References</summary>
<ul>
<li><a href="https://z.ai/blog/glm-4.5">GLM-4.5: Reasoning, Coding, and Agentic Abililties - z.ai</a></li>
<li><a href="https://glm45.org/">GLM-4.5 - by Zhipu AI</a></li>

</ul>
</details>

**Discussion**: The Reddit community is largely speculative, with some users expressing excitement about a potential new open-weight model, while others remain skeptical due to the lack of concrete details.

**Tags**: `#AI`, `#LLM`, `#GLM`, `#announcement`

---

<a id="item-29"></a>
## [GLM-5.2 Runs on CPU at 4-5.5 tok/s with MTP Drafting](https://www.reddit.com/r/LocalLLaMA/comments/1u9jbd4/giving_glm52_a_spin_locally_on_cpu_only_poor_mans/) ⭐️ 6.0/10

A user successfully ran the GLM-5.2 model (UD-Q2_K_XL quant) on a dual Xeon 6248R CPU system with 768GB RAM using ik_llama.cpp, achieving 4-5.5 tok/s generation speed with Multi-Token Prediction (MTP) drafting enabled. This demonstrates that frontier-level models like GLM-5.2 can be run locally on CPU-only hardware, making large model inference accessible to users without expensive GPUs and highlighting the importance of optimization techniques like MTP and NUMA isolation. The user isolated the model to a single NUMA node (24 cores, 384GB RAM) to avoid cross-socket memory latency, and used ik_llama.cpp, a fork of llama.cpp with CPU inference improvements. Performance degrades to ~3 tok/s as context grows, especially during coding tasks.

reddit · r/LocalLLaMA · /u/_TheWolfOfWalmart_ · Jun 18, 21:40

**Background**: GLM-5.2 is a large language model from the GLM series, known for strong performance. Multi-Token Prediction (MTP) is a speculative decoding technique where a draft model predicts multiple tokens at once, speeding up inference. NUMA (Non-Uniform Memory Access) is a server architecture where memory access latency varies depending on which CPU socket the memory is attached to; cross-socket access incurs higher latency.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/ikawrakow/ik_llama.cpp/">GitHub - ikawrakow/ik_llama.cpp: llama.cpp fork with ...</a></li>
<li><a href="https://arxiv.org/abs/2509.18362">[2509.18362] FastMTP: Accelerating LLM Inference with ... Multi-token-prediction in Gemma 4 - The Keyword Gemma 4 MTP Drafter: Get 3x Faster Inference (2026 Guide) Multi-Token Prediction MTP in llama.cpp How It Works and How ... GitHub - Tencent-BAC/FastMTP Multi-Token Prediction Tutorial: How To Speed Up LLMs</a></li>
<li><a href="https://medium.com/@amerather_9719/exploring-numa-3e8b4556456d">Exploring NUMA . In Symmetric Multiprocessor (SMP) | Medium</a></li>

</ul>
</details>

**Discussion**: The Reddit post received a comment from a user asking for advice on repurposing an idle GPU node (8x Quadro RTX 6000, 192GB VRAM) for local inference, indicating interest in running large models on available hardware.

**Tags**: `#GLM-5.2`, `#CPU inference`, `#llama.cpp`, `#NUMA`, `#local LLM`

---

<a id="item-30"></a>
## [Headroom: Compress LLM Inputs by 60-95% Without Losing Accuracy](https://github.com/chopratejas/headroom) ⭐️ 6.0/10

Headroom, a new open-source Python tool, compresses tool outputs, logs, files, and RAG chunks before sending them to LLMs, reducing token usage by 60-95% while preserving answer quality. This tool directly addresses the high cost of LLM token usage, making AI agents and workflows more economical and efficient for developers and enterprises. Headroom can be used as a library, a proxy, or an MCP server, and it demonstrated a live reduction from 10,144 to 1,260 tokens while still correctly identifying a fatal error.

ossinsight · chopratejas · Jun 19, 05:33

**Background**: LLMs charge based on the number of tokens (words or subwords) in the input. Large contexts from tool outputs, logs, or RAG chunks can quickly inflate costs. Headroom compresses this context intelligently, stripping redundant information while keeping essential content, thus reducing token count without altering the LLM's answers.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/chopratejas/headroom">GitHub - chopratejas/ headroom : Compress tool outputs, logs, files...</a></li>
<li><a href="https://www.hostinger.com/applications/headroom">Headroom AI Proxy VPS | One-Click Token Compression</a></li>
<li><a href="https://www.buildthisnow.com/blog/tools/extensions/headroom-token-compression">Headroom : Cut AI Agent Token Costs by Compressing Context</a></li>

</ul>
</details>

**Tags**: `#LLM`, `#token compression`, `#Python`, `#RAG`, `#open source`

---

<a id="item-31"></a>
## [CodeGraph Pre-Indexes Codebases into Knowledge Graphs for AI Assistants](https://github.com/colbymchenry/codegraph) ⭐️ 6.0/10

CodeGraph is a new open-source tool that pre-indexes codebases into a local knowledge graph, reducing token usage and tool calls for AI coding assistants like Claude Code, Cursor, and Codex. This approach can significantly lower costs and latency for AI-assisted coding by replacing file scanning with graph queries, making it more efficient for developers using multiple AI agents. CodeGraph supports eight AI coding agents, runs 100% locally with no data leaving the machine, and claims up to 94% fewer tool calls. It is written in TypeScript and bundles its own runtime.

ossinsight · colbymchenry · Jun 19, 05:33

**Background**: AI coding assistants typically scan entire files to understand code context, which consumes many tokens and tool calls. A knowledge graph pre-indexes relationships like symbol dependencies and call graphs, allowing agents to query only relevant parts. This is similar to how search engines index web pages for faster retrieval.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/colbymchenry/codegraph">GitHub - colbymchenry/codegraph: Pre-indexed code knowledge ...</a></li>
<li><a href="https://codegraph.codes/">CodeGraph — Code Knowledge Graph for Claude Code & Cursor</a></li>
<li><a href="https://pyshine.com/CodeGraph-Pre-Indexed-Code-Knowledge-Graph-AI-Coding-Agents/">CodeGraph : Pre - Indexed Code Knowledge Graph for AI ... | PyShine</a></li>

</ul>
</details>

**Tags**: `#knowledge-graph`, `#code-assistant`, `#TypeScript`, `#LLM`, `#developer-tools`

---

<a id="item-32"></a>
## [Omnigent: A Meta-Harness for AI Agents](https://github.com/omnigent-ai/omnigent) ⭐️ 6.0/10

Omnigent, an open-source meta-harness for AI agents, has been released on GitHub, gaining 12 stars in the past 24 hours. It provides a unified layer over Claude Code, Codex, Pi, and custom agents, enabling swapping, policy enforcement, sandboxing, and real-time collaboration. This project addresses the fragmentation of AI agent tools by offering a single interface to manage multiple harnesses, which could streamline workflows for developers and teams. Its policy and sandboxing features also enhance safety and governance in agent deployment. Omnigent is written in Python and supports real-time collaboration from any device via WebSocket sync. It allows users to combine or swap harnesses like Claude Code, Codex, and Pi without rewriting code.

ossinsight · omnigent-ai · Jun 19, 05:33

**Background**: AI agent harnesses are tools that enable large language models to interact with codebases and execute tasks. Popular harnesses like Claude Code and Codex each have their own interfaces and limitations, making it cumbersome to switch between them. Omnigent acts as a meta-harness that sits above these tools, providing a common orchestration layer.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/omnigent-ai/omnigent">GitHub - omnigent-ai/omnigent: Omnigent is an open-source AI ...</a></li>
<li><a href="https://omnigent.ai/">Omnigent — a meta-harness for building and running AI agents</a></li>
<li><a href="https://www.databricks.com/blog/introducing-omnigent-meta-harness-combine-control-and-share-your-agents">Introducing Omnigent: A Meta-Harness to Combine, Control and ...</a></li>

</ul>
</details>

**Tags**: `#AI agents`, `#Python`, `#developer tools`, `#meta-harness`

---