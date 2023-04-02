# Prompt Engineering Guide

Prompt engineering is a relatively new discipline for developing & optimizing prompts to efficiently use language models (LMs) for a wide variety of applications and research topics. Prompt engineering skills help to better understand the capabilities and limitations of large language models (LLMs). Researchers use prompt engineering to improve the capacity of LLMs on a wide range of common and complex tasks such as question answering and arithmetic reasoning. Developers use prompt engineering to design robust and effective prompting techniques that interface with LLMs and other tools.

Motivated by the high interest in developing with LLMs, we have created this new prompt engineering guide that contains all the latest papers, learning guides, lectures, references, and tools related to prompt engineering. 

Happy Prompting!

---
## Announcements / Updates

- 🎓 Partnered with Sphere to deliver a new course on [Prompt Engineering for LLMs](https://www.getsphere.com/cohorts/prompt-engineering-for-llms?source=github)
- 💬 New ChatGPT prompt engineering guide coming soon!
- 🔥 We reached #1 on Hacker News on 21 Feb 2023
- 🎉 The Prompt Engineering Lecture went live [here](https://youtu.be/dOxUroR57xs)
- 🎓 We're creating a set of comprehensive guides [here](#guides)

[Join our Discord](https://discord.gg/SKgkVT8BGJ)

[Follow us on Twitter](https://twitter.com/dair_ai)

[Subscribe to our Newsletter](https://nlpnews.substack.com/)

---

## Table of Contents

- [Lecture](#lecture)
- [Guides](#guides)
- [Papers](#papers)
- [Tools & Libraries](#tools--libraries)
- [Datasets](#datasets)
- [Blog, Guides, Tutorials and Other Readings](#blog-guides-tutorials-and-other-readings)

---
## Lecture

We have published a 1 hour lecture that provides a comprehensive overview of prompting techniques, applications, and tools.
- [Video Lecture](https://youtu.be/dOxUroR57xs)
- [Notebook with code](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/notebooks/pe-lecture.ipynb)
- [Slides](https://github.com/dair-ai/Prompt-Engineering-Guide/blob/main/lecture/Prompt-Engineering-Lecture-Elvis.pdf)

---

## Guides
The following are a set of guides on prompt engineering developed by us. Guides are work in progress.  

- [Prompt Engineering - Introduction](/guides/prompts-intro.md)
- [Prompt Engineering - Basic Prompting](/guides/prompts-basic-usage.md)
- [Prompt Engineering - Advanced Prompting](/guides/prompts-advanced-usage.md)
- [Prompt Engineering - Applications](/guides/prompts-applications.md)
- [Prompt Engineering - ChatGPT](/guides/prompts-chatgpt.md)
- [Prompt Engineering - Adversarial Prompting](/guides/prompts-adversarial.md)
- [Prompt Engineering - Reliability](/guides/prompts-reliability.md)
- [Prompt Engineering - Miscellaneous Topics](/guides/prompts-miscellaneous.md)

---
## Papers

The following are the latest papers (sorted by release date) on prompt engineering. We update this on a daily basis and new papers come in. We incorporate summaries of these papers to the guides above every week.

- Surveys / Overviews:

  - [Augmented Language Models: a Survey](https://arxiv.org/abs/2302.07842) (Feb 2023)
  - [A Survey for In-context Learning](https://arxiv.org/abs/2301.00234) (Dec 2022)
  - [Towards Reasoning in Large Language Models: A Survey](https://arxiv.org/abs/2212.10403) (Dec 2022)
  - [Reasoning with Language Model Prompting: A Survey](https://arxiv.org/abs/2212.09597) (Dec 2022)
  - [Emergent Abilities of Large Language Models](https://arxiv.org/abs/2206.07682) (Jun 2022)
  - [A Taxonomy of Prompt Modifiers for Text-To-Image Generation](https://arxiv.org/abs/2204.13988) (Apr 2022)
  - [Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing](https://arxiv.org/abs/2107.13586) (Jul 2021)
- Approaches/Techniques:
  
  - [Structure Pretraining and Prompt Tuning for Knowledge Graph Transfer](https://arxiv.org/abs/2303.03922) (March 2023)
  - [CoTEVer: Chain of Thought Prompting Annotation Toolkit for Explanation Verification](https://arxiv.org/abs/2303.03628) (March 2023)
  - [Larger language models do in-context learning differently](https://arxiv.org/abs/2303.03846) (March 2023)
  - [OpenICL: An Open-Source Framework for In-context Learning](https://arxiv.org/abs/2303.02913) (March 2023)
  - [Dynamic Prompting: A Unified Framework for Prompt Tuning](https://arxiv.org/abs/2303.02909) (March 2023)
  - [Multitask Prompt Tuning Enables Parameter-Efficient Transfer Learning](https://arxiv.org/abs/2303.02861) (March 2023)
  - [Effectiveness of Data Augmentation for Prefix Tuning with Limited Data](https://arxiv.org/abs/2303.02577) (March 2023)
  - [Mixture of Soft Prompts for Controllable Data Generation](https://arxiv.org/abs/2303.01580) (March 2023)
  - [Prompt, Generate, then Cache: Cascade of Foundation Models makes Strong Few-shot Learners](https://arxiv.org/abs/2303.02151) (March 2023)
  - [How Robust is GPT-3.5 to Predecessors? A Comprehensive Study on Language Understanding Tasks](https://arxiv.org/abs/2303.00293) (March 2023)
  - [Can ChatGPT Understand Too? A Comparative Study on ChatGPT and Fine-tuned BERT](https://arxiv.org/pdf/2302.10198.pdf) (Feb 2023)
  - [EvoPrompting: Language Models for Code-Level Neural Architecture Search](https://arxiv.org/abs/2302.14838) (Feb 2023)
  - [In-Context Instruction Learning](https://arxiv.org/abs/2302.14691) (Feb 2023)
  - [Chain of Hindsight Aligns Language Models with Feedback](https://arxiv.org/abs/2302.02676) (Feb 2023)
  - [Language Is Not All You Need: Aligning Perception with Language Models](https://arxiv.org/abs/2302.14045) (Feb 2023)
  - [Automatic Prompt Augmentation and Selection with Chain-of-Thought from Labeled Data](https://arxiv.org/abs/2302.12822) (Feb 2023)
  - [Active Prompting with Chain-of-Thought for Large Language Models](https://arxiv.org/abs/2302.12246) (Feb 2023)
  - [More than you've asked for: A Comprehensive Analysis of Novel Prompt Injection Threats to Application-Integrated Large Language Models](https://arxiv.org/abs/2302.12173) (Feb 2023)
  - [A Prompt Pattern Catalog to Enhance Prompt Engineering with ChatGPT](https://arxiv.org/abs/2302.11382) (Feb 2023)
  - [Guiding Large Language Models via Directional Stimulus Prompting](https://arxiv.org/abs/2302.11520) (Feb 2023)
  - [How Does In-Context Learning Help Prompt Tuning?](https://arxiv.org/abs/2302.11521) (Feb 2023)
  - [Scalable Prompt Generation for Semi-supervised Learning with Language Models](https://arxiv.org/abs/2302.09236) (Feb 2023)
  - [Bounding the Capabilities of Large Language Models in Open Text Generation with Prompt Constraints](https://arxiv.org/abs/2302.09185) (Feb 2023)
  - [À-la-carte Prompt Tuning (APT): Combining Distinct Data Via Composable Prompting](https://arxiv.org/abs/2302.07994) (Feb 2023)
  - [GraphPrompt: Unifying Pre-Training and Downstream Tasks for Graph Neural Networks](https://arxiv.org/abs/2302.08043) (Feb 2023)
  - [The Capacity for Moral Self-Correction in Large Language Models](https://arxiv.org/abs/2302.07459) (Feb 2023)
  - [SwitchPrompt: Learning Domain-Specific Gated Soft Prompts for Classification in Low-Resource Domains](https://arxiv.org/abs/2302.06868) (Feb 2023)
  - [Evaluating the Robustness of Discrete Prompts](https://arxiv.org/abs/2302.05619) (Feb 2023)
  - [Compositional Exemplars for In-context Learning](https://arxiv.org/abs/2302.05698) (Feb 2023)
  - [Hard Prompts Made Easy: Gradient-Based Discrete Optimization for Prompt Tuning and Discovery](https://arxiv.org/abs/2302.03668) (Feb 2023)
  - [Multimodal Chain-of-Thought Reasoning in Language Models](https://arxiv.org/abs/2302.00923) (Feb 2023)
  - [Large Language Models Can Be Easily Distracted by Irrelevant Context](https://arxiv.org/abs/2302.00093) (Feb 2023)
  - [Synthetic Prompting: Generating Chain-of-Thought Demonstrations for Large Language Models](https://arxiv.org/abs/2302.00618) (Feb 2023)
  - [Progressive Prompts: Continual Learning for Language Models](https://arxiv.org/abs/2301.12314) (Jan 2023)
  - [Batch Prompting: Efficient Inference with LLM APIs](https://arxiv.org/abs/2301.08721) (Jan 2023)
  - [Demonstrate-Search-Predict: Composing retrieval and language models for knowledge-intensive NLP](https://arxiv.org/abs/2212.14024) (Dec 2022)
  - [On Second Thought, Let's Not Think Step by Step! Bias and Toxicity in Zero-Shot Reasoning](https://arxiv.org/abs/2212.08061) (Dec 2022)
  - [Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/abs/2212.08073) (Dec 2022)
  - [Successive Prompting for Decomposing Complex Questions](https://arxiv.org/abs/2212.04092) (Dec 2022)
  - [Large Language Models are reasoners with Self-Verification](https://arxiv.org/abs/2212.09561v1) (Dec 2022)
  - [Discovering Language Model Behaviors with Model-Written Evaluations](https://arxiv.org/abs/2212.09251) (Dec 2022)
  - [Structured Prompting: Scaling In-Context Learning to 1,000 Examples](https://arxiv.org/abs/2212.06713) (Dec 2022)
  - [PAL: Program-aided Language Models](https://arxiv.org/abs/2211.10435) (Nov 2022)
  - [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/abs/2211.01910) (Nov 2022)
  - [Ignore Previous Prompt: Attack Techniques For Language Models](https://arxiv.org/abs/2211.09527) (Nov 2022)
  - [Machine Generated Text: A Comprehensive Survey of Threat Models and Detection Methods](https://arxiv.org/abs/2210.07321) (Nov 2022)
  - [Teaching Algorithmic Reasoning via In-context Learning](https://arxiv.org/abs/2211.09066) (Nov 2022)
  - [Enhancing Self-Consistency and Performance of Pre-Trained Language Models through Natural Language Inference](https://arxiv.org/abs/2211.11875) (Nov 2022)
  - [Ask Me Anything: A simple strategy for prompting language models](https://paperswithcode.com/paper/ask-me-anything-a-simple-strategy-for) (Oct 2022)
  - [Recitation-Augmented Language Models](https://arxiv.org/abs/2210.01296) (Oct 2022)
  - [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) (Oct 2022)
  - [Prompting GPT-3 To Be Reliable](https://arxiv.org/abs/2210.09150) (Oct 2022)
  - [Decomposed Prompting: A Modular Approach for Solving Complex Tasks](https://arxiv.org/abs/2210.02406) (Oct 2022)
  - [Language Models Are Greedy Reasoners: A Systematic Formal Analysis of Chain-of-Thought](https://arxiv.org/abs/2210.01240v3) (Oct 2022)
  - [Evaluating the Susceptibility of Pre-Trained Language Models via Handcrafted Adversarial Examples](https://arxiv.org/abs/2209.02128) (Sep 2022)
  - [Dynamic Prompt Learning via Policy Gradient for Semi-structured Mathematical Reasoning](https://arxiv.org/abs/2209.14610) (Sep 2022)
  - [Promptagator: Few-shot Dense Retrieval From 8 Examples](https://arxiv.org/abs/2209.11755) (Sep 2022)
  - [Atlas: Few-shot Learning with Retrieval Augmented Language Models](https://arxiv.org/abs/2208.03299) (Nov 2022)
  - [DocPrompting: Generating Code by Retrieving the Docs](https://arxiv.org/abs/2207.05987) (July 2022)
  - [On the Advance of Making Language Models Better Reasoners](https://arxiv.org/abs/2206.02336) (June 2022)
  - [Large Language Models are Zero-Shot Reasoners](https://arxiv.org/abs/2205.11916) (May 2022)
  - [Maieutic Prompting: Logically Consistent Reasoning with Recursive Explanations](https://arxiv.org/abs/2205.11822) (May 2022)
  - [MRKL Systems: A modular, neuro-symbolic architecture that combines large language models, external knowledge sources and discrete reasoning](https://arxiv.org/abs/2205.00445) (May 2022)
  - [PPT: Pre-trained Prompt Tuning for Few-shot Learning](https://aclanthology.org/2022.acl-long.576/) (Mqy 2022)
  - [Toxicity Detection with Generative Prompt-based Inference](https://arxiv.org/abs/2205.12390) (May 2022)
  - [Learning to Transfer Prompts for Text Generation](https://arxiv.org/abs/2205.01543) (May 2022)
  - [The Unreliability of Explanations in Few-shot Prompting for Textual Reasoning](https://arxiv.org/abs/2205.03401) (May 2022)
  - [A Taxonomy of Prompt Modifiers for Text-To-Image Generation](https://arxiv.org/abs/2204.13988) (Apr 2022)
  - [PromptChainer: Chaining Large Language Model Prompts through Visual Programming](https://arxiv.org/abs/2203.06566) (Mar 2022)
  - [Self-Consistency Improves Chain of Thought Reasoning in Language Models](https://arxiv.org/abs/2203.11171) (March 2022)
  - [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)
  - [Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/abs/2202.12837) (Feb 2022)
  - [Chain of Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903) (Jan 2022)
  - [Show Your Work: Scratchpads for Intermediate Computation with Language Models](https://arxiv.org/abs/2112.00114) (Nov 2021)
  - [AI Chains: Transparent and Controllable Human-AI Interaction by Chaining Large Language Model Prompts](https://arxiv.org/abs/2110.01691) (Oct 2021)
  - [Generated Knowledge Prompting for Commonsense Reasoning](https://arxiv.org/abs/2110.08387) (Oct 2021)
  - [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207) (Oct 2021)
  - [Reframing Instructional Prompts to GPTk's Language](https://arxiv.org/abs/2109.07830) (Sep 2021)
  - [Design Guidelines for Prompt Engineering Text-to-Image Generative Models](https://arxiv.org/abs/2109.06977) (Sep 2021)
  - [Making Pre-trained Language Models Better Few-shot Learners](https://aclanthology.org/2021.acl-long.295) (Aug 2021)
  - [Fantastically Ordered Prompts and Where to Find Them: Overcoming Few-Shot Prompt Order Sensitivity](https://arxiv.org/abs/2104.08786) (April 2021)
  - [BERTese: Learning to Speak to BERT](https://aclanthology.org/2021.eacl-main.316) (April 2021)
  - [The Power of Scale for Parameter-Efficient Prompt Tuning](https://arxiv.org/abs/2104.08691) (April 2021)
  - [Prompt Programming for Large Language Models: Beyond the Few-Shot Paradigm](https://arxiv.org/abs/2102.07350) (Feb 2021)
  - [Calibrate Before Use: Improving Few-Shot Performance of Language Models](https://arxiv.org/abs/2102.09690) (Feb 2021)
  - [Prefix-Tuning: Optimizing Continuous Prompts for Generation](https://arxiv.org/abs/2101.00190) (Jan 2021)
  - [Making Pre-trained Language Models Better Few-shot Learners](https://arxiv.org/abs/2012.15723) (Dec 2020)
  - [AutoPrompt: Eliciting Knowledge from Language Models with Automatically Generated Prompts](https://arxiv.org/abs/2010.15980) (Oct 2020)
  - [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165) (May 2020)
  - [How Can We Know What Language Models Know?](https://direct.mit.edu/tacl/article/doi/10.1162/tacl_a_00324/96460/How-Can-We-Know-What-Language-Models-Know) (July 2020)
- Applications:
  
  - [Choice Over Control: How Users Write with Large Language Models using Diegetic and Non-Diegetic Prompting](https://arxiv.org/abs/2303.03199) (March 2023)
  - [Prompting Large Language Models with Answer Heuristics for Knowledge-based Visual Question Answering](https://arxiv.org/abs/2303.01903) (March 2023)
  - [Soft Prompt Guided Joint Learning for Cross-Domain Sentiment Analysis](https://arxiv.org/abs/2303.00815) (March 2023)
  - [SpeechPrompt v2: Prompt Tuning for Speech Classification Tasks](https://arxiv.org/abs/2303.00733) (March 2023)
  - [Goal Driven Discovery of Distributional Differences via Language Descriptions](https://arxiv.org/abs/2302.14233) (Feb 2023)
  - [Navigating the Grey Area: Expressions of Overconfidence and Uncertainty in Language Models](https://arxiv.org/abs/2302.13439) (Feb 2023)
  - [TabGenie: A Toolkit for Table-to-Text Generation](https://arxiv.org/abs/2302.14169) (Feb 2023)
  - [SGL-PT: A Strong Graph Learner with Graph Prompt Tuning](https://arxiv.org/abs/2302.12449) (Feb 2023)
  - [Few-Shot Table-to-Text Generation with Prompt-based Adapter](https://arxiv.org/abs/2302.12468) (Feb 2023)
  - [Language Models Are Few-shot Learners for Prognostic Prediction](https://arxiv.org/abs/2302.12692) (Feb 2023)
  - [STA: Self-controlled Text Augmentation for Improving Text Classifications](https://arxiv.org/abs/2302.12784) (Feb 2023)
  - [Check Your Facts and Try Again: Improving Large Language Models with External Knowledge and Automated Feedback](https://arxiv.org/abs/2302.12813) (Feb 2023)
  - [How Generative AI models such as ChatGPT can be (Mis)Used in SPC Practice, Education, and Research? An Exploratory Study](https://arxiv.org/abs/2302.10916) (Feb 2023) 
  - [Grimm in Wonderland: Prompt Engineering with Midjourney to Illustrate Fairytales](https://arxiv.org/abs/2302.08961) (Feb 2023)
  - [LabelPrompt: Effective Prompt-based Learning for Relation Classification](https://arxiv.org/abs/2302.08068) (Feb 2023)
  - [Language Model Crossover: Variation through Few-Shot Prompting](https://arxiv.org/abs/2302.09236) (Feb 2023)
  - [Prompt Tuning of Deep Neural Networks for Speaker-adaptive Visual Speech Recognition](https://arxiv.org/abs/2302.08102) (Feb 2023)
  - [The Capacity for Moral Self-Correction in Large Language Models](https://arxiv.org/abs/2302.07459) (Feb 2023)
  - [Prompting for Multimodal Hateful Meme Classification](https://arxiv.org/abs/2302.04156) (Feb 2023)
  - [PLACES: Prompting Language Models for Social Conversation Synthesis](https://arxiv.org/abs/2302.03269) (Feb 2023)
  - [Commonsense-Aware Prompting for Controllable Empathetic Dialogue Generation](https://arxiv.org/abs/2302.01441) (Feb 2023)
  - [Crawling the Internal Knowledge-Base of Language Models](https://arxiv.org/abs/2301.12810) (Jan 2023)
  - [Legal Prompt Engineering for Multilingual Legal Judgement Prediction](https://arxiv.org/abs/2212.02199) (Dec 2022)
  - [Investigating Prompt Engineering in Diffusion Models](https://arxiv.org/abs/2211.15462) (Nov 2022)
  - [Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering](https://arxiv.org/abs/2209.09513v2) (Sep 2022)
  - [Conversing with Copilot: Exploring Prompt Engineering for Solving CS1 Problems Using Natural Language](https://arxiv.org/abs/2210.15157) (Oct 2022)
  - [Piloting Copilot and Codex: Hot Temperature, Cold Prompts, or Black Magic?](https://arxiv.org/abs/2210.14699) (Oct 2022)
  - [Plot Writing From Scratch Pre-Trained Language Models](https://aclanthology.org/2022.inlg-main.5) (July 2022)
- Collections:

  - [Chain-of-ThoughtsPapers](https://github.com/Timothyxxx/Chain-of-ThoughtsPapers)
  - [Papers with Code](https://paperswithcode.com/task/prompt-engineering)
  - [Prompt Papers](https://github.com/thunlp/PromptPapers#papers)

---
## Tools & Libraries
#### (Sorted by Name)

- [AI Test Kitchen](https://aitestkitchen.withgoogle.com)
- [betterprompt](https://github.com/krrishdholakia/betterprompt)
- [ClickPrompt](https://github.com/prompt-engineering/click-prompt)
- [DreamStudio](https://beta.dreamstudio.ai)
- [DUST](https://dust.tt)
- [Dyno](https://trydyno.com)
- [EmergentMind](https://www.emergentmind.com)
- [EveryPrompt](https://www.everyprompt.com)
- [GPT Index](https://github.com/jerryjliu/gpt_index)
- [GPTTools](https://gpttools.com/comparisontool)
- [hwchase17/adversarial-prompts](https://github.com/hwchase17/adversarial-prompts)
- [Interactive Composition Explorer](https://github.com/oughtinc/ice)
- [LangChain](https://github.com/hwchase17/langchain)
- [Lexica](https://lexica.art)
- [loom](https://github.com/socketteer/loom)
- [Metaprompt](https://metaprompt.vercel.app/?task=gpt)
- [OpenAI Playground](https://beta.openai.com/playground)
- [OpenICL](https://github.com/Shark-NLP/OpenICL)
- [OpenPrompt](https://github.com/thunlp/OpenPrompt)
- [OpenPlayground](https://nat.dev/)
- [Playground](https://playgroundai.com)
- [Prodia](https://app.prodia.com/#/)
- [Prompt Base](https://promptbase.com)
- [Prompt Engine](https://github.com/microsoft/prompt-engine)
- [Prompt Generator for OpenAI's DALL-E 2](http://dalle2-prompt-generator.s3-website-us-west-2.amazonaws.com)
- [Promptable](https://promptable.ai)
- [PromptInject](https://github.com/agencyenterprise/PromptInject)
- [Prompts.ai](https://github.com/sevazhidkov/prompts-ai)
- [PromptPerfect](https://promptperfect.jina.ai/)
- [Promptly](https://trypromptly.com/)
- [PromptSource](https://github.com/bigscience-workshop/promptsource)
- [Promptist](https://promptist.herokuapp.com/)
- [Scale SpellBook](https://scale.com/spellbook)
- [sharegpt](https://sharegpt.com)
- [ThoughtSource](https://github.com/OpenBioLink/ThoughtSource)
- [Visual Prompt Builder](https://tools.saxifrage.xyz/prompt)

---
## Datasets
#### (Sorted by Name)

- [Anthropic's Red Team dataset](https://github.com/anthropics/hh-rlhf/tree/master/red-team-attempts), [(paper)](https://arxiv.org/abs/2209.07858)
- [Awesome ChatGPT Prompts](https://huggingface.co/datasets/fka/awesome-chatgpt-prompts)
- [DiffusionDB](https://github.com/poloclub/diffusiondb)
- [Midjourney Prompts](https://huggingface.co/datasets/succinctly/midjourney-prompts)
- [P3 - Public Pool of Prompts](https://huggingface.co/datasets/bigscience/P3)
- [PartiPrompts](https://parti.research.google)
- [Real Toxicity Prompts](https://allenai.org/data/real-toxicity-prompts)
- [Stable Diffusion Dataset](https://huggingface.co/datasets/Gustavosta/Stable-Diffusion-Prompts)
- [WritingPrompts](https://www.reddit.com/r/WritingPrompts)

---
## Blog, Guides, Tutorials and Other Readings
#### (Sorted by Name)

- [3 Principles for prompt engineering with GPT-3](https://www.linkedin.com/pulse/3-principles-prompt-engineering-gpt-3-ben-whately)
- [A beginner-friendly guide to generative language models - LaMBDA guide](https://aitestkitchen.withgoogle.com/how-lamda-works)
- [A Complete Introduction to Prompt Engineering for Large Language Models](https://www.mihaileric.com/posts/a-complete-introduction-to-prompt-engineering)
- [A Generic Framework for ChatGPT Prompt Engineering](https://medium.com/@thorbjoern.heise/a-generic-framework-for-chatgpt-prompt-engineering-7097f6513a0b)
- [An SEO’s guide to ChatGPT prompts](https://searchengineland.com/chatgpt-prompts-seo-393523)
- [AI Content Generation](https://www.jonstokes.com/p/ai-content-generation-part-1-machine)
- [AI's rise generates new job title: Prompt engineer](https://www.axios.com/2023/02/22/chatgpt-prompt-engineers-ai-job)
- [Awesome ChatGPT Prompts](https://github.com/f/awesome-chatgpt-prompts)
- [Best 100+ Stable Diffusion Prompts](https://mpost.io/best-100-stable-diffusion-prompts-the-most-beautiful-ai-text-to-image-prompts)
- [Best practices for prompt engineering with OpenAI API](https://help.openai.com/en/articles/6654000-best-practices-for-prompt-engineering-with-openai-api)
- [Building GPT-3 applications — beyond the prompt](https://medium.com/data-science-at-microsoft/building-gpt-3-applications-beyond-the-prompt-504140835560)
- [Can AI really be protected from text-based attacks?](https://techcrunch.com/2023/02/24/can-language-models-really-be-protected-from-text-based-attacks/)
- [ChatGPT, AI and GPT-3 Apps and use cases](https://gpt3demo.com)
- [CMU Advanced NLP 2022: Prompting](https://youtube.com/watch?v=5ef83Wljm-M&feature=shares)
- [Common Sense as Dark Matter - Yejin Choi | Stanford MLSys #78](https://youtube.com/live/n4HakBqoCVg?feature=shares)
- [Curtis64's set of prompt gists](https://gist.github.com/Curtis-64)
- [DALL·E 2 Prompt Engineering Guide](https://docs.google.com/document/d/11WlzjBT0xRpQhP9tFMtxzd0q6ANIdHPUBkMV-YB043U/edit#)
- [DALL·E 2 Preview - Risks and Limitations](https://github.com/openai/dalle-2-preview/blob/main/system-card.md)
- [DALLE Prompt Book](https://dallery.gallery/the-dalle-2-prompt-book)
- [DALL-E, Make Me Another Picasso, Please](https://www.newyorker.com/magazine/2022/07/11/dall-e-make-me-another-picasso-please?)
- [Diffusion Models: A Practical Guide](https://scale.com/guides/diffusion-models-guide)
- [Exploiting GPT-3 Prompts](https://twitter.com/goodside/status/1569128808308957185)
- [Exploring Prompt Injection Attacks](https://research.nccgroup.com/2022/12/05/exploring-prompt-injection-attacks)
- [Extrapolating to Unnatural Language Processing with GPT-3's In-context Learning: The Good, the Bad, and the Mysterious](http://ai.stanford.edu/blog/in-context-learning)
- [Generative AI with Cohere: Part 1 - Model Prompting](https://txt.cohere.ai/generative-ai-part-1)
- [Giving GPT-3 a Turing Test](https://lacker.io/ai/2020/07/06/giving-gpt-3-a-turing-test.html)
- [GPT-3 & Beyond](https://youtube.com/watch?v=-lnHHWRCDGk)
- [GPT3 and Prompts: A quick primer](https://buildspace.so/notes/intro-to-gpt3-prompts)
- [Hands-on with Bing’s new ChatGPT-like features](https://techcrunch.com/2023/02/08/hands-on-with-the-new-bing/)
- [How to Draw Anything](https://andys.page/posts/how-to-draw)
- [How to get images that don't suck](https://www.reddit.com/r/StableDiffusion/comments/x41n87/how_to_get_images_that_dont_suck_a)
- [How to make LLMs say true things](https://evanjconrad.com/posts/world-models)
- [How to perfect your prompt writing for AI generators](https://www.sydney.edu.au/news-opinion/news/2023/02/28/how-to-perfect-your-prompt-writing-for-ai-generators.html)
- [How to write good prompts](https://andymatuschak.org/prompts)
- [If I Was Starting Prompt Engineering in 2023: My 8 Insider Tips](https://youtube.com/watch?v=SirW7feTjh0&feature=shares)
- [Indirect Prompt Injection on Bing Chat](https://greshake.github.io/)
- [Interactive guide to GPT-3 prompt parameters](https://sevazhidkov.com/interactive-guide-to-gpt-3-prompt-parameters)
- [Introduction to Reinforcement Learning with Human Feedback](https://www.surgehq.ai/blog/introduction-to-reinforcement-learning-with-human-feedback-rlhf-series-part-1)
- [In defense of prompt engineering](https://simonwillison.net/2023/Feb/21/in-defense-of-prompt-engineering/)
- [Language Models and Prompt Engineering: Systematic Survey of Prompting Methods in NLP](https://youtube.com/watch?v=OsbUfL8w-mo&feature=shares)
- [Learn Prompting](https://learnprompting.org)
- [Methods of prompt programming](https://generative.ink/posts/methods-of-prompt-programming)
- [Mysteries of mode collapse](https://www.lesswrong.com/posts/t9svvNPNmFf5Qa3TA/mysteries-of-mode-collapse)
- [NLP for Text-to-Image Generators: Prompt Analysis](https://heartbeat.comet.ml/nlp-for-text-to-image-generators-prompt-analysis-part-1-5076a44d8365)
- [NLP with Deep Learning CS224N/Ling284 - Lecture 11: Promting, Instruction Tuning, and RLHF](http://web.stanford.edu/class/cs224n/slides/cs224n-2023-lecture11-prompting-rlhf.pdf)
- [Notes for Prompt Engineering by sw-yx](https://github.com/sw-yx/ai-notes)
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook)
- [OpenAI Prompt Examples for several applications](https://platform.openai.com/examples)
- [Pretrain, Prompt, Predict -  A New Paradigm for NLP](http://pretrain.nlpedia.ai)
- [Prompt Engineer: Tech's hottest job title?](https://www.peoplematters.in/article/talent-management/is-prompt-engineering-the-hottest-job-in-ai-today-37036)
- [Prompt Engineering 101 - Introduction and resources](https://www.linkedin.com/pulse/prompt-engineering-101-introduction-resources-amatriain)
- [Prompt Engineering 101: Autocomplete, Zero-shot, One-shot, and Few-shot prompting](https://youtube.com/watch?v=v2gD8BHOaX4&feature=shares)
- [Prompt Engineering 101](https://humanloop.com/blog/prompt-engineering-101)
- [Prompt Engineering - A new profession ?](https://www.youtube.com/watch?v=w102J3_9Bcs&ab_channel=PatrickDebois)
- [Prompt Engineering by co:here](https://docs.cohere.ai/docs/prompt-engineering)
- [Prompt Engineering by Microsoft](https://microsoft.github.io/prompt-engineering)
- [Prompt Engineering: The Career of Future](https://shubhamsaboo111.medium.com/prompt-engineering-the-career-of-future-2fb93f90f117)
- [Prompt engineering davinci-003 on our own docs for automated support (Part I)](https://www.patterns.app/blog/2022/12/21/finetune-llm-tech-support)
- [Prompt Engineering Guide: How to Engineer the Perfect Prompts](https://richardbatt.co.uk/prompt-engineering-guide-how-to-engineer-the-perfect-prompts)
- [Prompt Engineering in GPT-3](https://www.analyticsvidhya.com/blog/2022/05/prompt-engineering-in-gpt-3)
- [Prompt Engineering Template](https://docs.google.com/spreadsheets/d/1-snKDn38-KypoYCk9XLPg799bHcNFSBAVu2HVvFEAkA/edit#gid=0)
- [Prompt Engineering Topic by GitHub](https://github.com/topics/prompt-engineering)
- [Prompt Engineering: The Ultimate Guide 2023 [GPT-3 & ChatGPT]](https://businessolution.org/prompt-engineering/)
- [Prompt Engineering: From Words to Art](https://www.saxifrage.xyz/post/prompt-engineering)
- [Prompt Engineering with OpenAI's GPT-3 and other LLMs](https://youtube.com/watch?v=BP9fi_0XTlw&feature=shares)
- [Prompt injection attacks against GPT-3](https://simonwillison.net/2022/Sep/12/prompt-injection)
- [Prompt injection to read out the secret OpenAI API key](https://twitter.com/ludwig_stumpp/status/1619701277419794435?s=20&t=GtoMlmYCSt-UmvjqJVbBSA)
- [Prompting: Better Ways of Using Language Models for NLP Tasks](https://thegradient.pub/prompting/)
- [Prompting for Few-shot Learning](https://www.cs.princeton.edu/courses/archive/fall22/cos597G/lectures/lec05.pdf)
- [Prompting in NLP: Prompt-based zero-shot learning](https://savasy-22028.medium.com/prompting-in-nlp-prompt-based-zero-shot-learning-3f34bfdb2b72)
- [Prompting Methods with Language Models and Their Applications to Weak Supervision](https://snorkel.ai/prompting-methods-with-language-models-nlp)
- [Prompts as Programming by Gwern](https://www.gwern.net/GPT-3#prompts-as-programming)
- [Reverse Prompt Engineering for Fun and (no) Profit](https://lspace.swyx.io/p/reverse-prompt-eng)
- [So you want to be a prompt engineer: Critical careers of the future](https://venturebeat.com/ai/so-you-want-to-be-a-prompt-engineer-critical-careers-of-the-future/)
- [Simulators](https://www.lesswrong.com/posts/vJFdjigzmcXMhNTsx/simulators)
- [Start with an Instruction](https://beta.openai.com/docs/quickstart/start-with-an-instruction)
- [Talking to machines: prompt engineering & injection](https://artifact-research.com/artificial-intelligence/talking-to-machines-prompt-engineering-injection)
- [Tech’s hottest new job: AI whisperer. No coding required](https://www.washingtonpost.com/technology/2023/02/25/prompt-engineers-techs-next-big-job/)
- [The Book - Fed Honeypot](https://fedhoneypot.notion.site/25fdbdb69e9e44c6877d79e18336fe05?v=1d2bf4143680451986fd2836a04afbf4)
- [The ChatGPT Prompt Book](https://docs.google.com/presentation/d/17b_ocq-GL5lhV_bYSShzUgxL02mtWDoiw9xEroJ5m3Q/edit#slide=id.gc6f83aa91_0_79)
- [The Most Important Job Skill of This Century](https://www.theatlantic.com/technology/archive/2023/02/openai-text-models-google-search-engine-bard-chatbot-chatgpt-prompt-writing/672991/)
- [The Mirror of Language](https://deepfates.com/the-mirror-of-language)
- [The Waluigi Effect (mega-post)](https://www.lesswrong.com/posts/D7PumeYTDPfBTp3i7/the-waluigi-effect-mega-post)
- [Thoughts and impressions of AI-assisted search from Bing](https://simonwillison.net/2023/Feb/24/impressions-of-bing/)
- [Unleash Your Creativity with Generative AI: Learn How to Build Innovative Products!](https://youtube.com/watch?v=jqTkMpziGBU&feature=shares)
- [Using GPT-Eliezer against ChatGPT Jailbreaking](https://www.alignmentforum.org/posts/pNcFYZnPdXyL2RfgA/using-gpt-eliezer-against-chatgpt-jailbreaking)
- [What Is ChatGPT Doing … and Why Does It Work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
- [Why is ChatGPT so good?](https://scale.com/blog/chatgpt-reinforcement-learning)

---
If you are using the guide for your work, please cite us as follows:

```
@article{Saravia_Prompt_Engineering_Guide_2022,
author = {Saravia, Elvis},
journal = {https://github.com/dair-ai/Prompt-Engineering-Guide},
month = {12},
title = {{Prompt Engineering Guide}},
year = {2022}
}
```

Feel free to open a PR if you think something is missing here. Always welcome feedback and suggestions. Just open an issue!
