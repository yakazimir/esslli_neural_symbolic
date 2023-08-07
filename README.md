Overview
==========
This site contains the course materials for  the [**ESSLLI 2023**](https://2023.esslli.eu/courses-workshops-accepted/course-information.html#1) course of **Formal techniques for neural-symbolic Modeling**. 

**course description**: This is intended to be an advanced course on current methods for combining symbolic logic and neural networks, with applications to problems in natural language processing (NLP) and language modeling. In particular, we focus on techniques that use symbolic knowledge and declarative constraints to train machine learning models by compiling the corresponding symbolic logic into a differentiable form, also known as the [logic as a loss](https://arxiv.org/abs/2108.11451) function family of approaches. Details of current approach in NLP (in particular, the basic of how pre-trained transformers work), as well as the formal and algorithmic techniques needed to doing this (e.g., SAT-based methods, tractable representations of logic), will be covered in detail and drawn from the broader literature of neural-symbolic learning and reasoning.

**lecturers**:  [**Kyle Richardson**](https://www.krichardson.me/) (Allen Institute for AI), [**Vivek Srikumar**](https://svivek.com/) (University of Utah). 

Schedule
==========

*Please see inside of the slides for more references, links and other pointers.* 

- **Day 1** Course introduction and logical foundations. *topics*: propositional logic, SAT, tractable representations and knowledge compilation. [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture1.pdf)
> **General background** *knowledge compilation and circuits* [[Darwiche and Marquis 2002]](https://www.jair.org/index.php/jair/article/view/10311) [[Darwiche, 2022]](https://arxiv.org/abs/2202.02942), [[Marquis, Pierre 2008]](https://www.cril.univ-artois.fr/~marquis/tutorialNotes-ECAI08-PMarquis.pdf) *general logic and SAT* [[Davis, Segal and Weyuker 1994, ch12]](https://www.lsm.cic.ipn.mx/wp-content/uploads/2019/11/Computability-Complexity-and-Languages-Fundamentals-of-Theoretical-Computer-Science.pdf), [[Kroening and Strichman 2016]](https://www.dcc.fc.up.pt/~nam/resources/VP22/Kroening-and-Strichman---2016---Decision-Procedures.pdf), [[Biere, A et al. 2021]](https://www.iospress.com/catalog/books/handbook-of-satisfiability-2)  

- **Day 2** Introduction to language modeling and transformers. *topics*: classical vs. modern LMs, contextual models and attention, model tuning. [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture2.pdf)
> **Key Reading** *classic transformer papers* [[Vaswani, Ashish et al. 2017]](https://proceedings.neurips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html), [[Radford, Alec et al. 2018]](https://www.mikecaptain.com/resources/pdf/GPT-1.pdf), [[Devlin, Jacob et al 2018]](https://arxiv.org/abs/1810.04805), [[Raffel, Colin et al. 2020]](https://www.jmlr.org/papers/volume21/20-074/20-074.pdf), [[Brown, Tom et al. 2020]](https://proceedings.neurips.cc/paper_files/paper/2020/hash/1457c0d6bfcb4967418bfb8ac142f64a-Abstract.html?utm_medium=email&utm_source=transaction). *general references* [[Jurafsky, Dan et al. 2023, Ch.3,7,11]](https://web.stanford.edu/~jurafsky/slp3/), [[Transformers from Scratch, Peter Bloem]](https://peterbloem.nl/blog/transformers), [[Daume III, Hal. 2017, Ch7,10]](http://ciml.info/), *math for ML* [[Kolter, Zico 2020]](https://cs229.stanford.edu/summer2020/cs229-linalg.pdf)

### Logic for Model Training

- **Day 3** Training models with symbolic logic via the [semantic loss function](https://proceedings.mlr.press/v80/xu18h.html). *topics*: logic as loss, weighted model counting (WMC), circuits [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture3.pdf)
> **Key Reading** [[Xu, Jingyi et al. 2018]](https://proceedings.mlr.press/v80/xu18h.html), [[Chiva, Mark et al. 2008]](https://www.sciencedirect.com/science/article/pii/S0004370207001889), [[Ahmed, Kareem et al. 2022]](https://arxiv.org/abs/2201.11250), [[Minervini, Pasquale et al 2018]](https://arxiv.org/abs/1808.08609), [[Li, Tao, et al 2019]](https://arxiv.org/abs/1909.00126), [[Darwiche, Adnan 2011]](https://ai.dmi.unibas.ch/research/reading_group/darwiche-ijcai2011.pdf), [[Asai, Akari et al. 2020]](https://arxiv.org/abs/2004.10157)

### Logic and Probabilistic Reasoning for Model Correction

- **Day 4**  Symbolic methods for reasoning over model predictions. *topics*: SAT methods and their semantics, different types of inference, circuits, NLP applications [[slides]](https://github.com/yakazimir/esslli_neural_symbolic/blob/main/slides/lecture4.pdf)
> **Key Reading** [[Park, James 2002]](https://cdn.aaai.org/AAAI/2002/AAAI02-102.pdf), [[Sang, Tian et al. 2007]](https://henrykautz.com/papers/ijcai07-mpe-maxsat.pdf), *related NLP work* [[Kassner, Nora et al. 2021]](https://arxiv.org/abs/2109.14723), [[Kassner, Nora etal 2023]](https://arxiv.org/abs/2305.14250),[[Mitchell, Eric et al. 2022]](https://arxiv.org/abs/2211.11875), [[Gu, Yuling et al. 2023]](https://arxiv.org/abs/2212.10029), [[Jung, Jaehun et al. 2022]](https://arxiv.org/abs/2205.11822), *statistical relational learning background* [[De Raedt, Luc et al. 2016]](https://link.springer.com/book/10.1007/978-3-031-01574-8)

### Fuzzy logic and applications

- **Day 5** Training models using multi-valued Logic *topics*: systems of fuzzy-logic, technical issues, applications to NLP.
> **Key Reading** *logical relaxations and related NLP* [[Li, Tao et al. 2019]](https://arxiv.org/abs/1906.06298), [[Li, Tao, et al 2019]](https://arxiv.org/abs/1909.00126), [[Grespan, Mattia et al. 2021]](https://arxiv.org/abs/2107.13646), [[Rocktaschel, Tim et al. 2015]](https://aclanthology.org/N15-1118.pdf), [[Grespan, Mattia et al. 2023]](https://aclanthology.org/2023.acl-long.654/), **fuzzy logic** [[Emilie van Krien et al 2022]](https://www.sciencedirect.com/science/article/pii/S0004370221001533)

Helpful Resources 
==========

Many examples thoughout the course taken from the work of the [UCLA Automated Reasoning Group](https://www.youtube.com/@UCLA.Reasoning) (*See link for many relevant lectures*). For a general survey of *neural-symbolic* methods, see [[Marra et al. 2020]](https://arxiv.org/abs/2108.11451), for *statistical relational learning* see [[De Raedt, L et al. 2016]](https://link.springer.com/book/10.1007/978-3-031-01574-8), for *logic and AI* see [[Darwiche, Ardnan 2020]](https://dl.acm.org/doi/abs/10.1145/3375395.3389131)

Below are some pointers to code resources: 
- **solvers** [[Z3 solver]](https://github.com/Z3Prover/z3), [[python-sat]](https://pysathq.github.io/), [[problog]](https://github.com/ML-KULeuven/problog)
- **NLP and general ML** [[transformers]](https://github.com/huggingface/transformers), [[PyTorch]](https://pytorch.org/), [[pylon-lib]](https://github.com/pylon-lib/pylon), [[hf datasets]](https://huggingface.co/docs/datasets/index)
- **knowledge compilation** [[pysdd]](https://github.com/wannesm/PySDD) 
- **other useful utilities** [[sympy]](https://www.sympy.org/en/index.html)
