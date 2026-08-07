# BroadFire AI

**Open research in spatial intelligence, neurosymbolic reasoning, mechanistic interpretability, and embodied AI.**

---

We are a small, independent research group working on foundational problems at the intersection of 3D spatial understanding, world models, and structured reasoning. Our work is guided by the belief that the next generation of intelligent systems must move beyond flat pattern matching toward compositional, physically grounded understanding of the world.

## Research Directions

### Spatial Intelligence & World Models

We develop methods for real-time 3D scene understanding — monocular depth estimation, Gaussian splatting, and spatiotemporal representations that capture how environments evolve over time. Our interest extends to world models: learned simulators of environment dynamics that enable agents to predict, plan, and act within physical spaces before committing to action.

> **Inspiration** — [Google DeepMind](https://github.com/google-deepmind) | [Meta FAIR](https://github.com/facebookresearch) (JEPA) | [Google AI Studio](https://aistudio.google.com/) | [Overworld](https://over.world/) (diffusion world models)
>
> **Researchers** — [Danijar Hafner](https://danijar.com/) (Google DeepMind; Dreamer, PlaNet) | [Hazel Heejeong Nam](https://hazel-heejeong-nam.github.io/) (Brown; Causal-JEPA, world models + causality) | [Ruiqi Gao](https://ruiqigao.github.io/) (Google DeepMind; diffusion and multimodal generation) | [Kelly Yutong He](https://kellyyutonghe.github.io/) (CMU; guided diffusion, SDEdit) | [Ying Wang](https://yingwangg.github.io/) (NYU CILVR; latent planning, AdaJEPA) | [Ray Wang](https://raywang4.github.io/) (UC Berkeley; Equilibrium Matching, generative vision)
>
> **Companies** — [Overworld](https://over.world/) | [Odyssey](https://odyssey.ml/) | [Black Forest Labs](https://bfl.ai/) | [World Labs](https://www.worldlabs.ai/) | [Runway](https://runwayml.com/) | [Skywork AI](https://skywork.ai/)
>
> **Readings** — [Energy-Based Models (MIT, Yilun Du & Shuang Li)](https://energy-based-model.github.io/Energy-based-Model-MIT/) | [ICLR 2026 Workshop on World Models](https://iclr.cc/virtual/2026/workshop/10000799) | [World Models Explained (Pebblous)](https://blog.pebblous.ai/project/AgenticAI/world-model-rise/en/)

### Neurosymbolic & Hierarchical Reinforcement Learning

We design architectures that combine neural perception with symbolic program induction — enabling agents to discover compositional task structure, learn transferable hierarchical policies, and generalise to novel environments zero-shot. The goal is agents that reason, not just react.

> **Inspiration** — [Symbolica](https://github.com/ExtensityAI/symbolicai) | [Sakana AI](https://github.com/SakanaAI) | [DeepMind](https://github.com/google-deepmind) | [Peking university](https://github.com/pku-ml-group/pku-ml-group.github.io/)
>
> **Researchers** — [Jiayuan Mao](https://jiayuanm.com/) (UPenn / Amazon FAR; Neuro-Symbolic Concept Learner, Neural Logic Machines) | [Silvia Sapora](https://silviasapora.github.io/) (Google DeepMind / Oxford; explainable inverse RL, meta-learning)
>
> **Companies** — [Symbolica](https://symbolica.ai/) | [Logical Intelligence](https://logicalintelligence.com/) | [Symbolic Mind](https://symbolicmind.ai/) | [Sapient Intelligence](https://sapient.inc/) | [Agentic Learning AI Lab](https://agenticlearning.ai/) | [PlantingSpace](https://planting.space/) | [EquiLibre Technologies](https://www.equilibretechnologies.com/) | [AMI Labs](https://amilabs.xyz/) | [Ndea](https://ndea.com/) | [Laude Institute](https://www.laude.org/) | [ARC Prize Foundation](https://arcprize.org/) | [Axiom Math](https://axiommath.ai/)
>
> **Readings** — [Centaur AI Institute](https://www.centaurinstitute.org/) | [IBM Research: Neuro-Symbolic AI](https://research.ibm.com/topics/neuro-symbolic-ai) | [Turing Institute Neuro-Symbolic AI Interest Group](https://www.turing.ac.uk/research/interest-groups/neuro-symbolic-ai)

### Mechanistic Interpretability

We study the internal representations of neural networks to understand *how* and *why* models behave as they do. Our interpretability work informs the design of more transparent, steerable AI systems.

> **Inspiration** — [Neel Nanda / MATS](https://www.matsprogram.org/) | [GoodFire](https://github.com/goodfire-ai) | [SPAR AI](https://sparai.org/) | [Sakana AI](https://github.com/SakanaAI)
>
> **Companies** — [Goodfire](https://www.goodfire.ai/) | [Martian](https://withmartian.com/) | [WhiteBox Research](https://www.whiteboxresearch.org/) | [Sakana AI](https://sakana.ai/) | [Nous Research](https://nousresearch.com/) | [J-Space Research](https://jspace.com/) (AI safety)
>
> **Readings** — [An Extremely Opinionated Annotated List of My Favourite Mechanistic Interpretability Papers v2 (Neel Nanda)](https://www.alignmentforum.org/posts/NfFST5Mio7BCAQHPA/an-extremely-opinionated-annotated-list-of-my-favourite-1)

### Efficiency

We pursue research into inference-time and training-time efficiency — speculative decoding, block diffusion, quantisation, and kernel-level optimisation for making large models fast and accessible on constrained hardware.

> **Inspiration** — [Z Lab](https://z-lab.ai/) ([DFlash](https://github.com/z-lab/dflash), ParoQuant, SparseLoRA) | [Tri Dao / FlashAttention](https://github.com/Dao-AILab) | [DeepMind](https://github.com/google-deepmind)
>
> **Researchers** — [Hiroki Naganuma](https://hiroki11x.github.io/) (NVIDIA / Mila; large-scale optimization, distributed training) | Fuli Luo (Xiaomi; DeepSeek-V2, VECO) | [Xiuyu Li](https://sheriyuo.github.io/) (StepFun; RL post-training, test-time scaling) | [Xiuyu Li](https://xiuyuli.com/) (ex-xAI / BAIR; SqueezeLLM, Q-Diffusion) | [Siyuan Han](https://hsyodyssey.com/) (Binance; learned indexes, ML for systems)
>
> **Companies** — [Inception Labs](https://www.inceptionlabs.ai/) | [Google DeepMind](https://deepmind.google/) (Diffusion Gemma) | [Cartesia](https://cartesia.ai/) | [Liquid AI](https://www.liquid.ai/)
>
> **Readings** — [Frontier Model Training Methodologies (Alex Wa)](https://djdumpling.github.io/2026/01/31/frontier_training.html)

### Scientific Machine Learning

We contribute to the Julia and Python scientific computing ecosystems, particularly in medical imaging, volumetric segmentation, and differentiable scientific computing through the [JuliaHealth](https://github.com/JuliaHealth) and [SciML](https://github.com/SciML) organisations.

> **Inspiration** — [SciML](https://github.com/SciML) | [JuliaHealth](https://github.com/JuliaHealth) | [Aalto ASCI](https://www.aalto.fi/en/aalto-science-institute-asci) | [Pumas AI](https://pumas.ai)
>
> **Companies** — [Cell Bauhaus](https://cellbauhaus.com/) | [Prima Mente](https://www.primamente.com/) | [CZI Virtual Cells Platform](https://virtualcellmodels.cziscience.com/) | [Boltz](https://boltz.bio/) | [Pumas AI](https://pumas.ai) | [Aeolus](https://aeolus.earth/) | [Godela](https://godela.ai/) | [Lazy Dynamics](https://lazydynamics.com/)

### Human Centered AI & Mixed Reality

We explore the intersection of human-centered design, immersive computing, and AI-driven interaction in mixed reality environments - spatial user interfaces, embodied interaction in XR, AI-assisted content creation for virtual worlds,
and real-time 3D rendering pipelines for accessible immersive experiences.

> **Inspiration** - [Georgia Tech Polo Data Science Lab](https://poloclub.github.io/) | [Cocolinux](https://github.com/cocolinux) | [Hash3D](https://github.com/nickhui97) | [Neurosama](https://virtualyoutuber.fandom.com/wiki/Neuro-sama) | [LukeRoss VR](https://www.realvr.com/)
>
> **Researchers** - [Judith E. Fan](https://cogtoolslab.github.io/) (Stanford; cognitive tools, sketches as representations of thought) | [Paul Liang](https://pliang279.github.io/) (MIT Media Lab; multisensory AI, MultiBench)
>
> **Companies** - [Hume AI](https://www.hume.ai/) | [Humans&](https://humansand.ai/) | [Infold Games](https://www.infoldgames.com/en/home) | [Game Science](https://www.gamesci.com.cn/) | [Ubisoft](https://www.ubisoft.com/) | [Scopely](https://www.scopely.com/) | [CodeWeavers](https://www.codeweavers.com/)

### Embodied AI

We investigate agents that act in the physical world - dexterous manipulation, vision-language-action models, and embodied foundation models that close the loop between perception, reasoning, and control.

> **Researchers** - [Yixiao Ge](https://geyixiao.com/) (XPENG Robotics; embodied foundation models, SEED) | [Hao Tang](https://ha0tang.github.io/) (Peking University; VLA models, generative embodied AI) | [Sarvesh Patil](https://servo97.github.io/) (CMU Robotics Institute; dexterous manipulation)
>
> **Companies** - [XPENG Robotics](https://www.xpeng.com/) | [1X](https://www.1x.tech/) | [Figure](https://www.figure.ai/) | [Physical Intelligence](https://www.physicalintelligence.company/) | [Waymo](https://waymo.com/) | [Menlo Research](https://menlo.ai/) (ASIMOV) | [Sharpa](https://www.sharpa.com/) | [Halter](https://www.halterhq.com/) | [Anduril](https://www.anduril.com/) | [Palantir](https://www.palantir.com/) | [Northwood Space](https://www.northwoodspace.io/) | [P-1 AI](https://p-1.ai/)

### AI Scientists & Agentic Evaluation

We track systems where LLM agents carry out scientific workflows - hypothesis generation, experimentation, and synthesis - together with the evaluation machinery (LLM-as-judge, fine-grained benchmarks) needed to trust autonomous research.

> **Researchers** - [Seungone Kim](https://seungonekim.github.io/) (CMU LTI; Prometheus 2, BiGGen Bench, AI for science)
>
> **Companies** - [Andon Labs](https://andonlabs.com/) | [Phylo](https://phylo.bio/) | [MiroFish](https://mirofish.ai/)
>
> **Readings** - [Alex L. Zhang's blog](https://alexzhang13.github.io/blog/) (Recursive Language Models, harnesses, scaffolds)

### Quantum Computing & Quantum Matter

We follow quantum algorithms, quantum learning theory, and quantum matter - tracking where quantum information science genuinely changes the computational landscape, and where classical methods catch up.

> **Researchers** - [Ewin Tang](https://ewintang.com/) (UC Berkeley, Princeton from Fall 2026; dequantization, quantum learning theory) | [Weiguang Cao](https://tolight.github.io/) (SDU, HKUST from June 2026; non-invertible symmetries, quantum lattice models)
---

## Ecosystem Watchlist

Cross-cutting organisations we track that span multiple research directions.

**Frontier & Open Model Labs** - [Thinking Machines Lab](https://thinkingmachines.ai/) | [Safe Superintelligence](https://ssi.inc/) | [Meta AI](https://ai.meta.com/) | [DeepSeek](https://www.deepseek.com/) | [Moonshot AI](https://www.moonshot.ai/) | [MiniMax](https://www.minimax.io/) | [Meituan LongCat](https://longcat.ai/) | [ByteDance Seed](https://seed.bytedance.com/en/) | [StepFun](https://www.stepfun.com/) | [Poolside](https://poolside.ai/) | [Allen Institute for AI](https://allenai.org/) | [Prometheus](https://www.prometheus.ai/) | [Flapping Airplanes](https://flappingairplanes.com/)

**NeuroAI & Unconventional Computing** - [Numenta](https://www.numenta.com/) | [Stanhope AI](https://www.stanhopeai.com/) | [Astera Institute](https://astera.org/) | [NeuroDX](https://www.neurodx.ai/) | Translucent AI | [Cortical Labs](https://corticallabs.com/) | [Extropic](https://extropic.ai/) | [Osmo](https://www.osmo.ai/)

**Compute Infrastructure** - [SF Compute](https://sfcompute.com/) | [Cast AI](https://cast.ai/) | [Prime Intellect](https://www.primeintellect.ai/)

**Benchmarks & Research Trackers** - [RoboDojo](https://robodojo-benchmark.com/leaderboard) (sim-and-real benchmark for generalist robot manipulation) | [Real Deep Research](https://realdeepresearch.github.io/) (research trend surveys across AI and robotics) | [XPENG Robotics Research](https://xpeng-robotics.github.io/) (multimodal team blog: Si0, Fe0, DIAL)

**Learning Resources** - [Centaur AI Institute](https://www.centaurinstitute.org/) | [Active Inference Institute](https://www.activeinference.institute/) ([learning resources](https://activeinference.institute/resources/#learning)) | [PaperLens](https://paperlens.io/) | [ML Job Interviews: The Ultimate Guide (Silvia Sapora)](https://silviasapora.github.io/blog/ml-interviews.html) | [foorilla](https://foorilla.com/) (tech jobs and media hub) | [FMHY](https://fmhy.net/) (free resources index)

---

## Target Venues

**Conferences** — ECCV, CVPR, NeurIPS, ICML, JuliaCon, [AGI Conference](https://agi-conference.org/) (Annual Conference on Artificial General Intelligence)

---

## Repositories

| Project | Description |
|---------|-------------|
| [**BroadFire**](https://github.com/BroadFireAI/BroadFire) | Research lab landing page — WebGL shaders, Three.js interactive 3D, and custom GLSL for spatial visualisation |

*More research repositories coming soon.*

---

## Technical Stack

**Languages** — Julia, C++, Python, TypeScript, Rust
**Domains** — CUDA, distributed computing, GPU kernels, WebGL/GLSL, differentiable programming
**Frameworks** — Three.js, React, PyTorch, Flux.jl, SciML

---

## Links

- [**Website**](https://broadfire.onrender.com/) — Research blog, experiments, and technical writing
- [**Founder**](https://github.com/divital-coder) — Divyansh

---

<sub>BroadFire AI — igniting research at the frontier of spatial intelligence and neurosymbolic reasoning.</sub>
