Overview
==========
This site contains the course materials for  the ESSLLI 2023 course of `Formal techniques for neural-symbolic Modeling`. 

Schedule
==========

**Abstract**: This is intended to be an advanced course on current methods for combining symbolic logic and neural networks, with applications to problems in natural language processing (NLP) and language modeling. In particular, we focus on techniques that use symbolic knowledge and declarative constraints to train machine learning models by compiling the corresponding symbolic logic into a differentiable form, also known as the [logic as a loss](https://arxiv.org/abs/2108.11451) function family of approaches. Details of current approach in NLP (in particular, pre-trained transformers), as well as the formal and algorithmic techniques needed to doing this, will be covered in detail and drawn from the broader literature of neural-symbolic learning and reasoning.

### Technical Foundations: Logic and Transformers

- **Day 1** Course introduction and logical foundations. *topics*: propositional logic, SAT, [tractable representations and knowledge compilation](https://arxiv.org/abs/2202.02942). [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture1.pdf)
  
- **Day 2** Introduction to language modeling and transformers. *topics*: classical vs. modern LMs, contextual models and attention, model tuning. [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture2.pdf)

### Synthesis 

- **Day 3** Training models with symbolic logic via the [semantic loss function](https://proceedings.mlr.press/v80/xu18h.html). *topics*: logic as loss, weighted model counting (WMC), circuits [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture3.pdf)

- **Day 4**  Symbolic methods for reasoning over model predictions. *topics*: SAT methods and their semantics, different types of inference, circuits [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture4.pdf)

- **Day 5** Training models using multi-valued Logic *topics*: systems of fuzzy-logic, technical issues, applications to NLP.

Helpful Resources 
==========

Many examples thoughout the course taken from the work of the [UCLA Automated Reasoning Group](https://www.youtube.com/@UCLA.Reasoning) (*See link for many relevant lectures*). For a general survey of neural-symbolic methods, see [Marra et al. 2020](https://arxiv.org/abs/2108.11451)

