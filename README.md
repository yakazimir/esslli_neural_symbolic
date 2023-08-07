Overview
==========
This site contains the course materials for  the ESSLLI 2023 course of `Formal techniques for neural-symbolic Modeling`. 

Schedule
==========

**Abstract**: This is intended to be an advanced course on current methods for combining symbolic logic and neural networks, with applications to problems in natural language processing (NLP) and language modeling. In particular, we focus on techniques that use symbolic knowledge and declarative constraints to train machine learning models by compiling the corresponding symbolic logic into a differentiable form, also known as the [logic as a loss](https://arxiv.org/abs/2108.11451) function family of approaches. Details of current approach in NLP (in particular, pre-trained transformers), as well as the formal and algorithmic techniques needed to doing this, will be covered in detail and drawn from the broader literature of neural-symbolic learning and reasoning.

### Technical Foundations: Logic and Transformers

*Please see inside of the slides for more references, links and other pointers.* 

- **Day 1** Course introduction and logical foundations. *topics*: propositional logic, SAT, tractable representations and knowledge compilation. [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture1.pdf)
> **General background** *knowledge compilation and circuits* [[Darwiche and Marquis 2002]](https://www.jair.org/index.php/jair/article/view/10311) [[Darwiche, 2022]](https://arxiv.org/abs/2202.02942), [[Marquis, Pierre 2008]](https://www.cril.univ-artois.fr/~marquis/tutorialNotes-ECAI08-PMarquis.pdf) *general logic and SAT* [[Davis, Segal and Weyuker 1994, ch12]](https://www.lsm.cic.ipn.mx/wp-content/uploads/2019/11/Computability-Complexity-and-Languages-Fundamentals-of-Theoretical-Computer-Science.pdf), [[Kroening and Strichman 2016]](https://www.dcc.fc.up.pt/~nam/resources/VP22/Kroening-and-Strichman---2016---Decision-Procedures.pdf), [[Biere, A et al. 2021]](https://www.iospress.com/catalog/books/handbook-of-satisfiability-2)  

- **Day 2** Introduction to language modeling and transformers. *topics*: classical vs. modern LMs, contextual models and attention, model tuning. [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture2.pdf)
> **Key Reading** *classic transformer papers* [[Vaswani, Ashish et al. 2017]](https://proceedings.neurips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html), [[Radford, Alec et al. 2018]](https://www.mikecaptain.com/resources/pdf/GPT-1.pdf), [[Devlin, Jacob et al 2018]](https://arxiv.org/abs/1810.04805), [[Raffel, Colin et al. 2020]](https://www.jmlr.org/papers/volume21/20-074/20-074.pdf), [[Brown, Tom et al. 2020]](https://proceedings.neurips.cc/paper_files/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html?utm_medium=email&utm_source=transaction). *general references* 

### Logic for Model Training

- **Day 3** Training models with symbolic logic via the [semantic loss function](https://proceedings.mlr.press/v80/xu18h.html). *topics*: logic as loss, weighted model counting (WMC), circuits [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture3.pdf)
> **Key Reading** [[Xu, Jingyi et al. 2018]](https://proceedings.mlr.press/v80/xu18h.html), [[M Chiva et al.]](https://www.sciencedirect.com/science/article/pii/S0004370207001889), [[Ahmed, Kareem et al.]](https://arxiv.org/abs/2201.11250), [[Minervini, Pasquale et al 2018]](https://arxiv.org/abs/1808.08609), [[Li, Tao, et al 2019]](https://arxiv.org/abs/1909.00126), [[Darwiche, Adnan 2011]](https://ai.dmi.unibas.ch/research/reading_group/darwiche-ijcai2011.pdf)

### Logic for Model Correction

- **Day 4**  Symbolic methods for reasoning over model predictions. *topics*: SAT methods and their semantics, different types of inference, circuits [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture4.pdf)

### Fuzzy logic and applications

- **Day 5** Training models using multi-valued Logic *topics*: systems of fuzzy-logic, technical issues, applications to NLP.

Helpful Resources 
==========

Many examples thoughout the course taken from the work of the [UCLA Automated Reasoning Group](https://www.youtube.com/@UCLA.Reasoning) (*See link for many relevant lectures*). For a general survey of *neural-symbolic* methods, see [[Marra et al. 2020]](https://arxiv.org/abs/2108.11451), for *statistical relational learning* see [[De Raedt, L et al. 2016]](https://link.springer.com/book/10.1007/978-3-031-01574-8).


