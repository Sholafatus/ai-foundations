# Foundations of AI and Mathematical Thinking
### A 52-Week Self-Directed Curriculum

**Student:** Shola Fatimoju
**Cadence:** 6 to 8 hours per week
**Format:** Self-paced, public, build-driven

---

## 1. Course Description

A first-principles tour of the mathematics that powers modern artificial intelligence, structured so every concept is applied immediately to a buildable project. The curriculum draws on five canonical courses (MIT 18.06, Harvard Stat 110, Stanford CS229, Stanford EE364A, and Karpathy's *Neural Networks: Zero to Hero*) and one canonical text (MacKay's *Information Theory, Inference, and Learning Algorithms*). It is designed for a working professional who wants genuine fluency, not certificates.

The emphasis is on transfer. Each major concept is taught with at least one application outside finance, because the same matrix that ranks web pages also ranks species in a food web and finds latent factors in equity returns. Recognizing that pattern across domains is the actual point of the course.

## 2. Learning Objectives

By the end of 52 weeks, the student will be able to:

1. Derive and implement core ML algorithms (regression, classification, neural networks, transformers) from scratch using only NumPy and Python.
2. Read modern AI research papers and identify the linear algebra, probability, and optimization underneath the notation.
3. Apply the same mathematical tools across at least four distinct domains (language, vision, networks, dynamical systems).
4. Ship a public artifact (code, notebook, or writeup) every two weeks.
5. Produce one original capstone paper applying probability, optimization, and information theory to a question of personal interest.

## 3. Prerequisites

High-school algebra. Comfort installing Python and running Jupyter notebooks. Everything else is built up from first principles.

## 4. Time Commitment

Six to eight hours per week, sustained for 52 weeks. Roughly three hours of lectures or reading, three to four hours of building. One scheduled skip-week every six weeks, baked into the calendar.

## 5. Ground Rules

1. **Ship every two weeks.** A public GitHub commit, a notebook, or a writeup. Late builds beat skipped builds. Skipped lectures are better than skipped builds.
2. **Build in public.** A single GitHub repo with a running README serves as the transcript. Pin it on the profile.
3. **One Substack post per phase.** Four short essays across the year, written for a non-technical reader. Forces synthesis.
4. **Pick your own builds.** The schedule below proposes a default build per checkpoint and offers a menu of alternatives in Appendix B. Substitute freely.
5. **Skip-weeks are scheduled, not earned.** Weeks 7, 18, 31, and 44 are deliberate maintenance weeks. Use them.
6. **Read arXiv every month, starting Week 14.** Three papers a month from areas that interest you. One read carefully. A 300-word summary posted to Substack. This habit, sustained, is worth more than any single course in this syllabus.

## 6. Required Materials

All free.

| # | Resource | Author / Institution | Format |
|---|----------|---------------------|--------|
| 1 | *Essence of Linear Algebra* | 3Blue1Brown | YouTube, 15 videos |
| 2 | *Linear Algebra (18.06)* | Gilbert Strang, MIT | MIT OCW lectures + textbook |
| 3 | *Statistics 110: Probability* | Joe Blitzstein, Harvard | YouTube + Blitzstein & Hwang textbook |
| 4 | *CS229: Machine Learning* | Andrew Ng, Stanford | YouTube lectures |
| 5 | *EE364A: Convex Optimization* | Stephen Boyd, Stanford | YouTube + Boyd & Vandenberghe textbook (free PDF) |
| 6 | *Information Theory, Inference, and Learning Algorithms* | David MacKay | Free PDF |
| 7 | *Neural Networks: Zero to Hero* | Andrej Karpathy | YouTube, 7 videos |
| 8 | *Elements of Statistical Learning* (reference) | Hastie, Tibshirani, Friedman | Free PDF; read ch. 1 to 4 and 7 to 8 during Phase 2 |

## 7. Assessment

There are no grades. There are ships.

Each phase has two or three checkpoint builds and one short Substack post. Phase 4 concludes with a capstone paper of 10 to 15 pages. The GitHub repo is the transcript.

---

## 8. Schedule

### Phase 1 | Linear Algebra and AI from Scratch
**Weeks 1 to 13**

> **Lectures and reading:** 3Blue1Brown LA series; Strang 18.06 lectures 1 to 26; Karpathy videos 1 to 3.
>
> **Concepts:** Vectors, matrices, linear transformations, the four fundamental subspaces, orthogonality, eigenvalues and eigenvectors, the singular value decomposition, neural networks, backpropagation.

| Week | Topic | Material | Build / Activity | Done |
|:----:|-------|----------|------------------|:----:|
| 1 | Setup and intuition | 3B1B videos 1 to 8 | Python, Jupyter, GitHub repo live | [ ] |
| 2 | Geometric intuition | 3B1B videos 9 to 15 | Notebook: deform a cat photo with 2x2 matrices | [ ] |
| 3 | Vectors and Ax=b | Strang L1 to L4 | Problem set | [ ] |
| 4 | Vector spaces | Strang L5 to L8 | Problem set | [ ] |
| 5 | Four subspaces | Strang L9 to L11 | Problem set | [ ] |
| 6 | Orthogonality | Strang L12 to L14 | **Checkpoint 1:** PageRank from scratch | [ ] |
| 7 | *Skip week* | Catch up or rest | Optional: write up Checkpoint 1 | [ ] |
| 8 | Determinants | Strang L18 to L20 | Problem set | [ ] |
| 9 | Eigenvalues | Strang L21 to L23 | Problem set | [ ] |
| 10 | SVD and change of basis | Strang L24 to L26 | **Checkpoint 2:** image compression and eigenfaces | [ ] |
| 11 | Backprop, autograd | Karpathy video 1 (micrograd) | Code along | [ ] |
| 12 | Character-level LM | Karpathy video 2 (makemore) | Code along; swap in your own dataset | [ ] |
| 13 | MLPs and embeddings | Karpathy video 3 | **Checkpoint 3:** makemore on a corpus you choose | [ ] |

**Phase 1 deliverables.** Three pinned GitHub repos (PageRank, eigenfaces, makemore). One Substack post: *Three Things That Are Secretly the Same Matrix*.

---

### Phase 2 | Probability and Classical Machine Learning
**Weeks 14 to 26**

> **Lectures and reading:** Blitzstein Stat 110, lectures 1 to 30; CS229 lectures 1 to 8; Blitzstein & Hwang textbook in parallel. *ESL* chapters 1 to 4 and 7 to 8 as practitioner reference alongside CS229.
>
> **Concepts:** Sample spaces and counting, conditional probability and Bayes, random variables, expectation and variance, joint distributions, Markov chains, maximum likelihood, linear and logistic regression, generative models, kernel methods.

| Week | Topic | Material | Build / Activity | Done |
|:----:|-------|----------|------------------|:----:|
| 14 | Probability basics | Stat 110 L1 to L3 | Simulate Monty Hall and Birthday problem | [ ] |
| 15 | Conditional probability | Stat 110 L4 to L6 | Bayes calculator notebook | [ ] |
| 16 | Discrete distributions | Stat 110 L7 to L10 | Problem set | [ ] |
| 17 | Continuous distributions | Stat 110 L11 to L14 | **Checkpoint 4:** Bayesian A/B test dashboard | [ ] |
| 18 | *Skip week* | Catch up | | [ ] |
| 19 | Joint distributions | Stat 110 L15 to L18 | Problem set | [ ] |
| 20 | Markov chains | Stat 110 L19 to L22 | **Checkpoint 5:** Markov text generator on a corpus you love | [ ] |
| 21 | MLE and regression | CS229 L1 to L3 | Implement linear regression three ways (closed form, GD, SGD) | [ ] |
| 22 | Logistic regression | CS229 L4 to L5 | Implement from scratch | [ ] |
| 23 | Generative models | CS229 L6 to L7 | Naive Bayes classifier | [ ] |
| 24 | Kernels and SVMs | CS229 L8 | Notebook | [ ] |
| 25 | Inference puzzles | Stat 110 L23 to L26 | **Checkpoint 6:** pick from build menu (Appendix B) | [ ] |
| 26 | Synthesis | Stat 110 L27 to L30 | Substack post drafted | [ ] |

**Phase 2 deliverables.** At least three new GitHub artifacts. One Substack post on Bayes' rule applied to a real decision.

---

### Phase 3 | Optimization
**Weeks 27 to 39**

> **Lectures and reading:** Boyd EE364A lectures 1 to 18; Boyd & Vandenberghe textbook in parallel.
>
> **Concepts:** Convex sets, convex functions, convex problems, duality, gradient descent, Newton's method, interior-point methods, linear and quadratic programming, semidefinite programming, stochastic and distributed optimization.

| Week | Topic | Material | Build / Activity | Done |
|:----:|-------|----------|------------------|:----:|
| 27 | Convex sets | Boyd L1 to L2 | Visualize convex sets in 2D | [ ] |
| 28 | Convex functions | Boyd L3 to L4 | Problem set | [ ] |
| 29 | Convex problems | Boyd L5 to L6 | Problem set | [ ] |
| 30 | Duality | Boyd L7 to L8 | **Checkpoint 7:** GD, Newton, IPM on toy problems | [ ] |
| 31 | *Skip week* | Catch up | | [ ] |
| 32 | LP and QP | Boyd L9 to L10 | CVXPY tutorial notebook | [ ] |
| 33 | Applications | Boyd L11 to L12 | **Checkpoint 8:** pick from build menu | [ ] |
| 34 | Algorithms | Boyd L13 to L14 | Problem set | [ ] |
| 35 | SDP and conic | Boyd L15 | Problem set | [ ] |
| 36 | Stochastic optimization | Boyd L16 | Notebook | [ ] |
| 37 | Distributed and ADMM | Boyd L17 to L18 | Notebook | [ ] |
| 38 | Build week | None | **Checkpoint 9:** capstone-quality optimization artifact | [ ] |
| 39 | Writeup | None | Substack post drafted | [ ] |

**Phase 3 deliverables.** At least two GitHub repos, one of capstone quality. One Substack post.

---

### Phase 4 | Information Theory and Capstone
**Weeks 40 to 52**

> **Lectures and reading:** MacKay chapters 1 to 12; Karpathy videos 4 to 7 (building a small transformer).
>
> **Concepts:** Entropy, mutual information, source coding, channel coding, Bayesian inference, sampling and MCMC, neural networks as approximate inference, attention and transformers.

| Week | Topic | Material | Build / Activity | Done |
|:----:|-------|----------|------------------|:----:|
| 40 | Entropy and information | MacKay ch 1 to 3 | Compute entropy of three languages | [ ] |
| 41 | Source coding | MacKay ch 4 to 6 | Implement Huffman coding from scratch | [ ] |
| 42 | Noisy channels | MacKay ch 7 to 9 | Notebook | [ ] |
| 43 | Bayesian inference | MacKay ch 10 to 12 | **Checkpoint 10:** MCMC sampler from scratch | [ ] |
| 44 | *Skip week* | Capstone scoping | Capstone proposal drafted | [ ] |
| 45 | Capstone | Karpathy video 4 | Capstone in progress | [ ] |
| 46 | Capstone | Karpathy video 5 | Capstone in progress | [ ] |
| 47 | Capstone | Karpathy video 6 | Capstone in progress | [ ] |
| 48 | Capstone | Karpathy video 7 (mini-GPT) | Capstone draft v1 | [ ] |
| 49 | Capstone | None | Draft v2 | [ ] |
| 50 | Capstone | None | Draft v3 | [ ] |
| 51 | Polish | None | **Capstone submission** | [ ] |
| 52 | Retrospective | None | Final Substack post, retrospective | [ ] |

**Phase 4 deliverables.** A working transformer implementation. An original capstone paper (10 to 15 pages). A retrospective Substack post.

---

## Appendix A: Cross-Domain Transfer Map

The same mathematics shows up in many places. Use this map whenever the work feels narrow.

**The dominant eigenvector of a matrix is:**
- Google PageRank (web search)
- Eigenfaces (computer vision, 1991)
- Principal components (factor models, neuroscience PCA on neural firing)
- Markov chain stationary distribution (chemistry, queueing theory, NLP)
- Vibrational modes of a building or molecule (engineering, chemistry)
- Centrality in social networks (sociology)

**Maximum likelihood estimation is:**
- Logistic regression (ML)
- Kalman filtering (aerospace, GPS, robotics)
- Maximum entropy models (computational linguistics)
- Generalized linear models (epidemiology, biostatistics)
- The EM algorithm (population genetics, mixture models)
- Hidden Markov models (speech recognition, bioinformatics)

**Gradient descent is:**
- Backpropagation (deep learning)
- Portfolio optimization (finance)
- Inverse kinematics (robotics)
- Protein folding (computational biology)
- Beam shaping (optics)
- Adversarial training and self-play (game AI)

**Information entropy is:**
- Data compression (gzip, JPEG, MP3)
- Channel capacity (wireless, fiber optic)
- Decision trees and random forests (ML)
- Statistical mechanics (physics)
- Linguistic redundancy (Shannon's original work)
- Mutual information for feature selection (bioinformatics)

---

## Appendix B: Build Menu

Pick whatever excites you in the moment. The defaults in the schedule are suggestions; substitute freely.

### Linear Algebra builds
- PageRank on Wikipedia, NFL teams, academic papers, or food webs.
- Image compression via SVD; eigenfaces; recommender systems via matrix factorization.
- Latent semantic analysis on a text corpus.
- Spectral clustering on a graph (friends, songs, words).
- 3D rotations and quaternions: build a simple renderer.
- *Kaggle option:* a tabular regression competition using only linear regression and ridge with hand-built features; constrain yourself to NumPy.

### Probability builds
- Bayesian A/B testing dashboard.
- Markov text generator on a corpus you love (Yoruba folktales, Obama speeches, jazz chord changes).
- Hidden Markov model for part-of-speech tagging in an under-resourced language.
- Naive Bayes classifier for AI-generated vs human text.
- Monte Carlo simulation of a real decision (poker hand, sports outcome, election).
- The German tank problem: estimating production from serial numbers.
- *Kaggle option:* a classification competition (Titanic, credit default, or any active one); build a logistic regression and a Naive Bayes baseline from scratch before reaching for sklearn.

### Optimization builds
- Shortest path: flights, subways, supply chains, board games.
- Diet problem (Stigler 1945) with modern nutrition data.
- Image denoising via total variation regularization.
- Gerrymandering detection on real district maps.
- Recommender system via matrix completion.
- Optimal control of a dynamical system (cart-pole, lunar lander).
- *Kaggle option:* a structured-prediction competition where you treat the model as a constrained optimization problem; write up the dual.

### Information theory and capstone builds
- Train a small transformer on an under-represented language corpus.
- Information-theoretic analysis of a domain you know.
- Disease spread on a contact graph using real outbreak data.
- Reinforcement learning agent for a game of your choice.
- Compression of human speech: native vs non-native, measured.
- Bayesian model of a real-world process (climate, traffic, language change).
- *Kaggle option:* an NLP or vision competition where you fine-tune a small transformer; write up what your eval metric is actually measuring in information-theoretic terms.

---

## Appendix C: Weekly Log Template

Keep a `LOG.md` file in the repo. Every Sunday, write three lines.

```
## Week NN, [dates]
1. Shipped this week:
2. Surprised me this week:
3. Shipping next week:
```

Fifty-two of those entries is the most honest record of progress that exists.

---

*Repo: TBD | Started: TBD | Last updated: TBD*
