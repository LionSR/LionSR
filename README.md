# Hi, I’m Sirui Lu 👋

**I build agent harnesses for scientific discovery—and study how to make their reasoning verifiable.**

I work across agent systems, formal verification, and theoretical physics. My research asks how language-model agents can sustain a mathematical argument over long tasks, use computation and proof checking as feedback, and discover results beyond the examples they were given.

I’m a physics PhD candidate at the **Max Planck Institute of Quantum Optics and TU Munich**, advised by **J. Ignacio Cirac**. I build research software as well as develop the mathematics: from multi-agent orchestration and context management to quantum algorithms and the physics of generative models.

**I’m exploring research scientist and research engineer roles in reasoning, agents, and AI for science.** [Get in touch →](mailto:sirui.lu@mpq.mpg.de)

## 🤖 Building AI theorists

**[TeXRA](https://texra.ai) · Agent harness for theoretical research**  
I designed and built a system that coordinates specialist agents for derivation, computation, review, and Lean formalization. It connects language models to **Wolfram algebra and Lean proofs**, making tool feedback part of the research process. The engineering spans TypeScript, editor integrations, a terminal CLI, model-provider interfaces, and long-running research sessions.

**[FormalFlow / MIPStarRE](https://github.com/LionSR/MIPStarRE) · Long-horizon reasoning with formal verification**  
With collaborators, I developed a workflow of shared mathematical blueprints, agent proof development, and human supervision. We formalized the quantum soundness of the classical low individual-degree test, a core theorem underlying MIP\* = RE. The proof effort took **63 days**; the later study snapshot contains **126,367 lines of Lean**. A central challenge was **statement fidelity**: ensuring the agents proved the intended mathematics, not merely something that compiled. [Paper →](https://arxiv.org/abs/2609.19814)

**[Lean-verified quantum codes](https://github.com/LionSR/lean-qec-sslp) · Discovery with exact checks**  
A human-guided multi-agent workflow combined symbolic synthesis, search, and formal verification to produce a catalogue of **14,116 certified quantum error-correcting codes**. This connects open-ended candidate generation to independently checkable mathematical results. [Paper →](https://arxiv.org/abs/2510.20728)

## 🔬 Research foundations

- **Formalized physics:** [TNLean](https://github.com/LionSR/TNLean) develops tensor-network theory in Lean 4/Mathlib, including the fundamental theorem of matrix-product states; [QICLean](https://github.com/LionSR/QICLean) develops quantum-information foundations. [Autoformalization paper →](https://arxiv.org/abs/2607.07857)
- **Physics of generative AI:** co-author, with **Max Welling and Lars Holdijk**, of _[Generative AI and Stochastic Thermodynamics: A Tale of Free Energies](https://sirui-lu.com/projects/book)_ (Cambridge University Press, 2026), connecting generative models and nonequilibrium thermodynamics through free energy.
- **Quantum computation:** research on quantum cooling, finite-energy simulation, and neural and tensor-network representations. [Publications →](https://sirui-lu.com/publications)
- **Reproducible research:** co-author of the [Agentic Publication Protocol](https://github.com/LionSR/AgenticPublicationProtocol), packaging papers with code, data, and instructions that agents can use to reproduce and extend the work.

## 🧭 What I want to work on next

- **Long-horizon agents:** planning, memory, and coordination that hold up over sustained research tasks.
- **Verifiable reasoning:** using symbolic tools and formal proof to guide search and evaluate whether an agent solved the intended problem.
- **AI for scientific discovery:** systems that propose, test, and refine mathematical and physical ideas.

[Website](https://sirui-lu.com) · [Publications](https://sirui-lu.com/publications) · [Google Scholar](https://scholar.google.com/citations?user=8rdMKOYAAAAJ&hl=en) · [Email](mailto:sirui.lu@mpq.mpg.de)
