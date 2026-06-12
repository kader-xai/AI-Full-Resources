# AI Full Resources

### A complete, learning-ordered compilation of resources for **Mathematics, Machine Learning & Deep Learning**

> _"Knowledge Not Shared is wasted." — Clan Jacobs_

This repository is a curated path through the best free tutorials, courses, books, papers and videos for learning AI — **reorganized into the order you should actually learn them**, from absolute beginner to advanced specialization.

> 📌 **How to use this:** Work top-to-bottom. Each phase builds on the one before it. Don't jump to Transformers before you understand Neural Networks; don't start Neural Networks before you're comfortable with the math and Python basics. Pick **one** resource per topic, finish it, then move on.

Original compilation by **[Navaneeth Malingan](https://www.linkedin.com/in/nivu/)** ([Instagram](https://www.instagram.com/nivu.me/)) — this is a reorganized, learning-sequenced fork.

---

## 🗺️ Learning Roadmap (Table of Contents)

| Phase | Focus | Topics |
|-------|-------|--------|
| **0** | [Orientation](#phase-0--orientation-start-here) | Why AI · How to get started · Intro to ML · No-code ML |
| **1** | [Foundations](#phase-1--foundations-math--programming) | Math · Python · NumPy · Pandas |
| **2** | [Core Machine Learning](#phase-2--core-machine-learning) | ML fundamentals · Glossary · MOOCs · Algorithms · scikit-learn |
| **3** | [Deep Learning Foundations](#phase-3--deep-learning-foundations) | Neural Networks · Books · Papers · PyTorch · TensorFlow |
| **4** | [Specializations](#phase-4--specializations) | Computer Vision · NLP & Transformers · Reinforcement Learning |
| **5** | [Applied AI & Production](#phase-5--applied-ai--production) | Transfer Learning · Deployment · MLOps · Edge ML |
| **6** | [Practice, Reference & Community](#phase-6--practice-reference--community) | Competitions · University courses · Cheatsheets · Channels · Communities |

---

# Phase 0 — Orientation (Start Here)

### Why AI / Data Science and how to get started?

- [🖥️ HOW TO GET STARTED WITH MACHINE LEARNING!](https://www.youtube.com/watch?v=I74ymkoNTnw)
- [How to Build a Meaningful Career in Data Science](https://www.datacamp.com/community/blog/how-to-build-a-meaningful-career-in-data-science)
- [My Self-Created Artificial Intelligence Masters Degree](https://hackernoon.com/my-self-created-ai-masters-degree-ddc7aae92d0e)
- [5 Beginner Friendly Steps to Learn Machine Learning and Data Science with Python](https://www.mrdbourke.com/5-beginner-friendly-steps-to-learn-machine-learning/)
- [PyImageSearch — Start Here](https://www.pyimagesearch.com/start-here/)

### Intro to ML (gentle, no prerequisites)

- [Luis Serrano: A Friendly Introduction to Machine Learning](https://www.youtube.com/watch?v=IpGxLWOIZy4)
- [StatQuest: A Gentle Introduction to Machine Learning](https://www.youtube.com/watch?v=Gv9_4yMHFhI)
- [Machine Learning For Everyone](https://vas3k.com/blog/machine_learning/) _Summarizes ML algorithms and their applications in simple words with real-world examples._

### Anyone can do Machine Learning (no code)

- [Teachable Machine](https://teachablemachine.withgoogle.com/) _Train a computer to recognize your own images, sounds & poses — no expertise or coding required._

### Visual Explainers (build intuition early, revisit often)

- [MLU-EXPLAIN](https://mlu-explain.github.io/)
- [CNN Explainer](https://poloclub.github.io/cnn-explainer/)

---

# Phase 1 — Foundations (Math & Programming)

> You cannot skip this. The math and Python here are reused in every later phase.

### Math for Machine Learning

- [Mathematics for Machine Learning](https://nivu.me/posts/mathematics-for-machine-learning/) _Compiled MOOCs, YouTube lectures and books for the math you need._
- [Mathematics for Machine Learning — Book (free eBook)](https://mml-book.github.io/) _One great book for all things math for ML._
- **Highly recommended — 3Blue1Brown visual series:**
  - [Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) ▶️
  - [Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) ▶️
  - [Differential Equations](https://www.youtube.com/playlist?list=PLZHQObOWTQDNPOjrT6KVlfJuKtYTftqH6) ▶️
- [Gilbert Strang: Linear Algebra vs Calculus](https://www.youtube.com/watch?v=osEADxaIKIc) ▶️
- [Basics of Integral Calculus in Tamil](https://www.youtube.com/watch?v=yMQjCFvMFgA) ▶️
- [fast.ai: Computational Linear Algebra](https://www.fast.ai/2017/07/17/num-lin-alg/)
- [Linear Algebra (Deep Learning Book chapter)](http://www.deeplearningbook.org/contents/linear_algebra.html)

### Python

- [Python Programming Tutorials by Socratica](https://www.youtube.com/watch?v=bY6m6_IIN94&list=PLi01XoE8jYohWFPpC17Z-wWhPOSuh8Er-) ▶️
- [Python Tutorial by w3schools](https://www.w3schools.com/python/) 📙
- [Learning Python Programming (Scaler)](https://www.scaler.com/topics/python/) 📙

### NumPy

- [A Visual Intro to NumPy and Data Representation](https://jalammar.github.io/visual-numpy/)
- [CS231n: Python NumPy Tutorial](http://cs231n.github.io/python-numpy-tutorial/#numpy)
- [NumPy resources (End-to-End Machine Learning)](https://brohrer.github.io/numpy_resources.html)
- [Python NumPy Tutorial for Beginners](https://www.youtube.com/watch?v=QUT1VHiLmmI) ▶️ _Arrays, indexing, math, statistics, reshaping and more._
- [Sci-Py Lectures: NumPy](https://scipy-lectures.org/intro/numpy/index.html)
- [Numpy Tutorial – Introduction to ndarray](https://www.machinelearningplus.com/python/numpy-tutorial-part1-array-python-examples/)
- [Python NumPy Array Tutorial (DataCamp)](https://www.datacamp.com/community/tutorials/python-numpy-tutorial)
- [NumPy Tutorial: Data analysis with Python (Dataquest)](https://www.dataquest.io/blog/numpy-tutorial-python/)
- [Deep Learning Prerequisites: The NumPy Stack in Python](https://www.youtube.com/playlist?list=PLxgDUj5eygKmlhteKFiXIIhdqmdD2TwVM) ▶️
- **Practice:** [100 numpy exercises (with solutions)](https://github.com/rougier/numpy-100) · [101 NumPy Exercises for Data Analysis](https://www.machinelearningplus.com/python/101-numpy-exercises-python/)

### Pandas

- [A Gentle Visual Intro to Data Analysis in Python Using Pandas](https://jalammar.github.io/gentle-visual-intro-to-data-analysis-python-pandas/)
- [Data analysis in Python with pandas by Data School](https://www.youtube.com/watch?v=yzIMircGU5I&list=PL5-da3qGB5ICCsgW1MxlZ0Hq8LL5U3u9y) ▶️
- [Best practices with pandas by Data School](https://www.youtube.com/watch?v=hl-TGI4550M&list=PL5-da3qGB5IBITZj_dYSFqnd_15JgqwA6) ▶️
- [Python Pandas Tutorial: A Complete Introduction for Beginners](https://www.learndatasci.com/tutorials/python-pandas-tutorial-complete-introduction-for-beginners/)

---

# Phase 2 — Core Machine Learning

### ML Fundamentals (terms used in every algorithm below)

- [Bias and Variance](https://www.youtube.com/watch?v=EuBBz3bI-aA)
- [Cross Validation](https://www.youtube.com/watch?v=fSytzGwwBVw)
- [The Confusion Matrix](https://www.youtube.com/watch?v=Kdsp6soqA7o)
- [Sensitivity and Specificity](https://www.youtube.com/watch?v=sunUKFXMHGk)
- [ROC and AUC, Clearly Explained!](https://www.youtube.com/watch?v=4jRBRDbJemM)
- [R-squared, explained](https://www.youtube.com/watch?v=2AQKmw14mHM)
- [Regularization Part 1: Ridge Regression](https://www.youtube.com/watch?v=Q81RR3yKn30)
- [Regularization Part 2: Lasso Regression](https://www.youtube.com/watch?v=NGf0voTMlcs)
- [Maximum Likelihood](https://www.youtube.com/watch?v=XepXtl9YKwc)
- [Covariance and Correlation](https://www.youtube.com/watch?v=qtaqvPAeEJY)
- [The Mean, Variance and Standard Deviation](https://www.youtube.com/watch?v=SzZ6GpcfoQY)
- [Population Parameters](https://www.youtube.com/watch?v=vikkiwjQqfU)
- [Looking at R-Squared](https://medium.com/@erika.dauria/looking-at-r-squared-721252709098)

### Glossaries (keep these open as reference)

- [Google ML Glossary](https://developers.google.com/machine-learning/glossary)
- [Glossary: Statistics](https://github.com/nature-of-code/NOC-S17-2-Intelligence-Learning/wiki/Glossary:-Statistics)
- [Glossary: Machine Learning](https://github.com/nature-of-code/NOC-S17-2-Intelligence-Learning/wiki/Glossary:-Machine-Learning)

### MOOCs (pick one as your spine)

- [Machine Learning by Andrew Ng, Stanford](https://www.coursera.org/learn/machine-learning) _The classic starting course._
- [Intro to Machine Learning (Udacity)](https://classroom.udacity.com/courses/ud120) _Naive Bayes, SVM, Decision Trees, Regression, Clustering, PCA, Evaluation Metrics._
- [Introduction to Machine Learning for Coders! (fast.ai)](http://course18.fast.ai/ml)
- [End-to-End Machine Learning](https://end-to-end-machine-learning.teachable.com/courses/)
- [Datacamp: Data Engineer with Python](https://www.datacamp.com/tracks/data-engineer-with-python)

### ML YouTube Playlists (follow alongside)

- [StatQuest: Machine Learning](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) ▶️
- [CodeBasics: Machine Learning Tutorial Python](https://www.youtube.com/watch?v=gmvvaobm7eQ&list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw) ▶️
- [sentdex: Machine Learning with Python](https://www.youtube.com/playlist?list=PLQVvvaa0QuDfKTOs3Keq_kaG2P55YRn5v) ▶️
- [Simplilearn: Machine Learning Tutorial Videos](https://www.youtube.com/playlist?list=PLEiEAq2VkUULYYgj13YHUWmRePqiu8Ddy) ▶️
- [deeplizard: ML & DL Fundamentals](https://www.youtube.com/playlist?list=PLZbbT5o_s2xq7LwI2y8_QtvuXZedL6tQU) ▶️

## ML Algorithms — learn in this order

> _Below are the best lectures for each classic algorithm. This sequence moves from simplest to most involved._

### 1. Linear Regression

- [Linear Regression: A friendly introduction by Luis Serrano](https://www.youtube.com/watch?v=wYPUhge9w5c) ▶️
- [Statistics 101: Linear Regression, The Very Basics](https://www.youtube.com/watch?v=ZkjP5RJLQF4) ▶️
- [Regression Line Fitting Playground](https://phet.colorado.edu/sims/html/least-squares-regression/latest/least-squares-regression_en.html)
- [Regression Curve Fitting Playground](https://phet.colorado.edu/sims/html/curve-fitting/latest/curve-fitting_all.html)

### 2. Gradient Descent (the engine behind training)

**The Best**
- [Linear Regression using Gradient Descent](https://nivu.me/posts/linear-regression-using-gradient-descent) 📙
- [Gradient Descent, Step-by-Step](https://www.youtube.com/watch?v=sDv4f4s2SB8) ▶️
- [Stochastic Gradient Descent, Clearly Explained!!!](https://www.youtube.com/watch?v=vMh0zPT0tLI) ▶️
- [How Optimization Works](https://end-to-end-machine-learning.teachable.com/p/building-blocks-how-optimization-works)
- [Linear Regression using Gradient Descent](https://towardsdatascience.com/linear-regression-using-gradient-descent-97a6c8700931) · [Code](https://github.com/chasinginfinity/ml-from-scratch)
- [Polynomial Regression](https://towardsdatascience.com/polynomial-regression-bbe8b9d97491)
- [Gradient Descent in Linear Regression — Math](https://www.geeksforgeeks.org/gradient-descent-in-linear-regression/) 📙
- [Neural Network Backpropagation Basics For Dummies](https://www.youtube.com/watch?v=8d6jf7s6_Qs) ▶️

**Extra Good Ones (Coding Train — Intelligence and Learning)**
- [3.4: Linear Regression with Gradient Descent](https://www.youtube.com/watch?v=L-Lsfu4ab74) ▶️
- [3.5: Mathematics of Gradient Descent](https://www.youtube.com/watch?v=jc2IthslyzM) ▶️
- [3.5a: Calculus: Power Rule](https://www.youtube.com/watch?v=IKb_3FJtA1U) ▶️
- [3.5b: Calculus: Chain Rule](https://www.youtube.com/watch?v=cE6wr0_ad8Y) ▶️
- [3.5c: Calculus: Partial Derivative](https://www.youtube.com/watch?v=-WVBXXV81R4) ▶️

**Vanishing Gradient**
- [Vanishing Gradient Problem](https://www.youtube.com/watch?v=SKMpmAOUa2Q) ▶️
- [How to overcome Vanishing Gradient Problem](https://www.youtube.com/watch?v=puux7KZQfsE) ▶️

**Local Minima**
- [Does gradient descent always converge to an optimum?](https://datascience.stackexchange.com/questions/24534/does-gradient-descent-always-converge-to-an-optimum)
- [Does MLP always find local minimum?](https://datascience.stackexchange.com/questions/18802/does-mlp-always-find-local-minimum)
- [The problem of local optima (Coursera)](https://www.coursera.org/learn/deep-neural-network/lecture/RFANA/the-problem-of-local-optima)

### 3. Logistic Regression

- [Linear Regression vs Logistic Regression (Edureka)](https://www.youtube.com/watch?v=OCwZyYH14uw) ▶️
- [Logistic Regression and the Perceptron Algorithm by Luis Serrano](https://www.youtube.com/watch?v=jbluHIgBmBo) ▶️

### 4. Decision Tree

- [StatQuest: Decision Trees](https://www.youtube.com/watch?v=7VeUPuFGJHk) ▶️
- [StatQuest: Decision Trees, Part 2 — Feature Selection and Missing Data](https://www.youtube.com/watch?v=wpNl-JwwplA) ▶️
- [Decision Tree Introduction with example](https://www.geeksforgeeks.org/decision-tree-introduction-example/) 📙
- [Decision Tree](https://www.geeksforgeeks.org/decision-tree/) 📙
- [Decision Tree Regression using sklearn](https://www.geeksforgeeks.org/python-decision-tree-regression-using-sklearn/) 📙
- [Logistic Regression v/s Decision Tree Classification](https://www.geeksforgeeks.org/ml-logistic-regression-v-s-decision-tree-classification/) 📙

### 5. Random Forest

- [StatQuest: Random Forests Part 1 — Building, Using and Evaluating](https://www.youtube.com/watch?v=J4Wdy0Wc_xQ) ▶️
- [StatQuest: Random Forests Part 2 — Missing data and clustering](https://www.youtube.com/watch?v=nyxTdL_4Q-Q) ▶️
- [Random Forests for Complete Beginners](https://victorzhou.com/blog/intro-to-random-forests/) 📙

### 6. Boosting (AdaBoost, Gradient Boost, XGBoost)

- [Boosting Machine Learning Tutorial (Edureka)](https://www.youtube.com/watch?v=kho6oANGu_A) ▶️
- [AdaBoost, Clearly Explained](https://www.youtube.com/watch?v=LsK-xG1cLYA) ▶️
- [Gradient Boost Part 1: Regression Main Ideas](https://www.youtube.com/watch?v=3CC4N4z3GJc) ▶️
- [Gradient Boost Part 2: Regression Details](https://www.youtube.com/watch?v=2xudPOBz-vs) ▶️
- [Gradient Boost Part 3: Classification](https://www.youtube.com/watch?v=jxuNLH5dXCs) ▶️
- [Gradient Boost Part 4: Classification Details](https://www.youtube.com/watch?v=StWY5QWMXCw) ▶️
- [XGBoost Part 1: Trees for Regression](https://www.youtube.com/watch?v=OtD8wVaFm6E) ▶️
- [XGBoost Part 2: Trees For Classification](https://www.youtube.com/watch?v=8b1JEDvenQU) ▶️
- [Ensemble methods (scikit-learn)](https://scikit-learn.org/stable/modules/ensemble.html)

### 7. Support Vector Machines (SVM)

- [SVMs: A friendly introduction by Luis Serrano](https://www.youtube.com/watch?v=Lpr__X8zuE8) ▶️
- [SVMs, Clearly Explained!!! by StatQuest](https://www.youtube.com/watch?v=efR1C6CvhmE) ▶️
- [SVM Part 2: The Polynomial Kernel](https://www.youtube.com/watch?v=Toet3EiSFcM) ▶️
- [SVM Part 3: The Radial (RBF) Kernel](https://www.youtube.com/watch?v=Qc5IyLW_hns) ▶️
- [How SVMs work / How to open a black box](https://www.youtube.com/watch?v=-Z4aojJ-pdg) ▶️
- [SVM — The Math of Intelligence (Week 1)](https://www.youtube.com/watch?v=g8D5YL6cOSE) ▶️
- [Demystifying Support Vector Machines](https://towardsdatascience.com/demystifying-support-vector-machines-8453b39f7368) 📙
- [SVM — Fun and Easy Machine Learning](https://www.youtube.com/watch?v=Y6RRHw9uN9o) ▶️

### 8. Bayes Theorem & Naive Bayes

- [Bayes theorem, and making probability intuitive](https://www.youtube.com/watch?v=HZGCoVF3YvM) ▶️
- [A friendly introduction to Bayes Theorem and Hidden Markov Models](https://www.youtube.com/watch?v=kqSzLo9fenk) ▶️
- [The Bayesian Trap](https://www.youtube.com/watch?v=R13BD8qKeTg) ▶️
- [Naive Bayes classifier: A friendly approach](https://www.youtube.com/watch?v=Q8l0Vip5YUw) ▶️

### 9. K-Nearest Neighbors

- [KNN from Scratch](https://machinelearningmastery.com/tutorial-to-implement-k-nearest-neighbors-in-python-from-scratch/) 📙
- [ML Basics with the K-Nearest Neighbors Algorithm](https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761) 📙

### 10. K-Means Clustering

- [StatQuest: K-means clustering](https://www.youtube.com/watch?v=4b5d3muPQmA) ▶️
- [ML Tutorial Python — K Means Clustering](https://www.youtube.com/watch?v=EItlUEPCIzM) ▶️
- [K Means Clustering in Python (Edureka)](https://www.youtube.com/watch?v=1XqG0kaJVHY) ▶️

### 11. Principal Component Analysis (PCA)

- [StatQuest: PCA main ideas in only 5 minutes!!!](https://www.youtube.com/watch?v=HMOI_lkzW08) ▶️
- [StatQuest: PCA, Step-by-Step](https://www.youtube.com/watch?v=FgakZw6K1QQ) ▶️
- [PCA by Luis Serrano](https://www.youtube.com/watch?v=g-Hb26agBFg) ▶️

### 12. Probabilistic Graphical Models (advanced)

- [Probabilistic Graphical Models Specialization](https://www.coursera.org/specializations/probabilistic-graphical-models)

### Putting it together — scikit-learn

- [An introduction to machine learning with scikit-learn](https://scikit-learn.org/stable/tutorial/basic/tutorial.html) 📙
- [Python Machine Learning: Scikit-Learn Tutorial](https://www.datacamp.com/community/tutorials/machine-learning-python)

---

# Phase 3 — Deep Learning Foundations

### Start here

- [DEEP BLUEBERRY BOOK](https://mithi.github.io/deep-blueberry/) _A tiny, focused collection of links — a great place to start._
- [MIT 6.S191: Introduction to Deep Learning (course site)](http://introtodeeplearning.com/)
  - [Class Lectures (YouTube)](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)
  - [Labs](https://github.com/aamini/introtodeeplearning_labs)
- [Intro to TensorFlow for Deep Learning (Udacity) — best course for learning TF](https://classroom.udacity.com/courses/ud187)
- [Practical Deep Learning for Coders, v3 (fast.ai)](https://course.fast.ai/) · [fast.ai](https://www.fast.ai/)
- [NVIDIA Deep Learning Institute](https://www.nvidia.com/en-us/deep-learning-ai/education/)
- [MIT Deep Learning Basics: Introduction and Overview](https://www.youtube.com/watch?v=O5xeyoRL95U)
- [MIT Deep Learning by Lex Fridman](https://deeplearning.mit.edu/) · [Lectures (YouTube)](https://www.youtube.com/playlist?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)
- [Deep Learning in Tamil](https://www.youtube.com/channel/UC2YVnH6aMky1SMdmlo5S9-A)

### Neural Networks (build the mental model)

- [A friendly introduction to Deep Learning and Neural Networks](https://www.youtube.com/watch?v=BR9h47Jtqyw) ▶️
- [Neural Networks Series by 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi) ▶️ _The best visual intuition for NNs._
- [Machine Learning for Beginners: An Introduction to Neural Networks](https://victorzhou.com/blog/intro-to-neural-networks/) 📙 _Implement one from scratch in Python._
- [A Visual and Interactive Guide to the Basics of Neural Networks](https://jalammar.github.io/visual-interactive-guide-basics-neural-networks/) 📙
- [A Visual And Interactive Look at Basic Neural Network Math](https://jalammar.github.io/feedforward-neural-networks-visual-interactive/) 📙
- [Neural Network Architectures](https://www.youtube.com/watch?v=oJNHXPs0XDk) ▶️
- [Neural Networks Demystified by Welch Labs](https://www.youtube.com/playlist?list=PLiaHhY2iBX9hdHaRr6b7XevZtgZRa1PoU) ▶️ · [Code](https://github.com/stephencwelch/Neural-Networks-Demystified)

### Deep Learning Books

- [The Deep Learning Textbook — Goodfellow, Bengio & Courville](http://www.deeplearningbook.org/)
- [Neural Networks and Deep Learning — Michael Nielsen](http://neuralnetworksanddeeplearning.com/)
- [Grokking Deep Learning — Andrew Trask](https://www.manning.com/books/grokking-deep-learning)

### Deep Learning Papers (when you're ready)

- [Deep Learning Papers Reading Roadmap](https://github.com/floodsung/Deep-Learning-Papers-Reading-Roadmap)

## Frameworks — pick one and go deep

### PyTorch

- [Udacity: Deep Learning with PyTorch](https://classroom.udacity.com/courses/ud188) · [Code](https://github.com/udacity/deep-learning-v2-pytorch)
- [PyTorchZeroToAll (Sung Kim) — 14 videos](https://www.youtube.com/playlist?list=PLlMkM4tgfjnJ3I-dbhO9JTw7gNty6o_2m) · [Code](https://github.com/hunkim/PyTorchZeroToAll) · [Slides](https://drive.google.com/drive/folders/0B41Zbb4c8HVyUndGdGdJSXd5d3M)
- [TorchScript](https://pytorch.org/docs/stable/jit.html)
- [Udacity: Secure AI](https://classroom.udacity.com/courses/ud185)

### TensorFlow

- [Introduction to TensorFlow 2.0 (TF World '19)](https://www.youtube.com/watch?v=5ECD8J3dvDQ)
- [TensorFlow Lite: ML on-device (TF World '19)](https://www.youtube.com/watch?v=0SpZy7iouFU)
- [Machine Learning in JavaScript (TF Dev Summit 2018)](https://www.youtube.com/watch?v=YB-kfeNIPCE)
- [TensorFlow.js Quick Start](https://www.youtube.com/watch?v=Y_XM3Bu-4yc)
- [Keras vs. tf.keras: What's the difference in TF 2.0?](https://www.pyimagesearch.com/2019/10/21/keras-vs-tf-keras-whats-the-difference-in-tensorflow-2-0/)
- [Run TensorFlow Lite on Raspberry Pi for Object Detection](https://www.youtube.com/watch?v=aimSGOAUI8Y)
- **Courses:** [Intro to TF for Deep Learning](https://classroom.udacity.com/courses/ud187) · [TensorFlow in Practice (Coursera)](https://www.coursera.org/specializations/tensorflow-in-practice) · [TF: Data and Deployment (Coursera)](https://www.coursera.org/specializations/tensorflow-data-and-deployment)

### PyTorch vs TensorFlow

- [Why is PyTorch becoming so popular among ML engineers?](https://www.quora.com/Why-is-PyTorch-becoming-so-popular-among-machine-learning-engineers)

---

# Phase 4 — Specializations

> Choose a track based on your interest. You don't need all three. Each assumes you've completed Phases 1–3.

## 🖼️ Computer Vision

- [CS131 Computer Vision: Foundations and Applications](http://vision.stanford.edu/teaching/cs131_fall1920/index.html)
- [CS231A: Computer Vision, From 3D Reconstruction to Recognition](http://web.stanford.edu/class/cs231a/)
- [CS231n: Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/)
- [Computer Vision Notebooks](https://diegoinacio.github.io/computer-vision-notebooks-page/)

### CNN (Convolutional Neural Networks)

- [A friendly introduction to CNNs and Image Recognition](https://www.youtube.com/watch?v=2-Ol7ZB0MmU)
- [A Comprehensive Guide to CNNs — the ELI5 way](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53)
- [CS231n: CNNs for Visual Recognition (course)](http://cs231n.stanford.edu/) · [Notes](http://cs231n.github.io/)
- [TensorFlow CNN tutorial](https://www.tensorflow.org/tutorials/images/cnn)
- [Convolutional Networks (Deep Learning Book)](http://www.deeplearningbook.org/contents/convnets.html)
- [CNNs, Part 1: An Introduction to CNNs](https://victorzhou.com/blog/intro-to-cnns-part-1/)
- [CS231n Winter 2016 by Andrej Karpathy — 15 Videos](https://www.youtube.com/watch?v=NfnWJUyUJYU&list=PLkt2uSq6rBVctENoVBg1TpCC7OQi31AlC)
- [Intuitive understanding of 1D, 2D, and 3D Convolutions](https://stackoverflow.com/questions/42883547/intuitive-understanding-of-1d-2d-and-3d-convolutions-in-convolutional-neural-n)
- [CNN Explainer (interactive)](https://github.com/poloclub/cnn-explainer)

### Object Detection

[**Evolution Of Object Detection Networks by Cogneethi**](https://www.youtube.com/playlist?list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S) — _deep-dive from classical CV (HOG, SIFT) to modern CNN-based detectors (Overfeat, Faster RCNN, etc.)._

- [SIFT | Scale Invariant Feature Transform](https://www.youtube.com/watch?v=ttD3pvM6pEI&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=19)
- [HOG | Histogram of Oriented Gradients](https://www.youtube.com/watch?v=Qwc3a8cOKRU&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=20)
- [NMS | Non Max Suppression](https://www.youtube.com/watch?v=07jFApuhh4I&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=25)
- [Object Localization | Bounding Box Regression](https://www.youtube.com/watch?v=LZRfHkTNQqo&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=49)
- [Object Detection](https://www.youtube.com/watch?v=77XJeT-Z-uE&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=50)
- [RCNN](https://www.youtube.com/watch?v=dtIZVJAcLxE&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=60)
- [Spatial Pyramid Matching | SPM](https://www.youtube.com/watch?v=6MwuK2wHlOg&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=70)
- [SPPNet Object Detection](https://www.youtube.com/watch?v=M3lx8GHrEsg&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=72)
- [Fast RCNN Network](https://www.youtube.com/watch?v=ZBPQ7Hd46m4&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=77)
- [Faster RCNN](https://www.youtube.com/watch?v=po59qI5LJGU&list=PL1GQaVhO4f_jLxOokW7CS5kY_J1t1T17S&index=80)
- [YOLO v4 Object Detection — How it Works](https://www.youtube.com/watch?v=_JzOFWx1vZg)
- **Frameworks:** [Detectron2](https://github.com/facebookresearch/detectron2) · [MMDetection](https://github.com/open-mmlab/mmdetection) · [MediaPipe](https://github.com/google/mediapipe) · [YOLO](https://pjreddie.com/darknet/yolo/) · [TF Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection) · [Computer Vision Recipes](https://github.com/microsoft/computervision-recipes)
- **Labeling Tools:** [LabelImg](https://github.com/tzutalin/labelImg) · [Roboflow](https://roboflow.com/) · [Label Studio](https://labelstud.io/)
- **Code:** [YOLO-Object-Counting-API](https://github.com/tugot17/YOLO-Object-Counting-API)

**3D Object Detection**
- [Announcing the Objectron Dataset (Google AI)](https://ai.googleblog.com/2020/11/announcing-objectron-dataset.html)
- [MediaPipe Objectron (3D Object Detection)](https://google.github.io/mediapipe/solutions/objectron.html)

### Image Segmentation

- [A Step-by-Step Introduction to Image Segmentation Techniques](https://www.analyticsvidhya.com/blog/2019/04/introduction-image-segmentation-techniques-python/)

### GANs (Generative Adversarial Networks)

- [A Friendly Introduction to GANs by Luis Serrano](https://www.youtube.com/watch?v=8L11aMN5KY8)
- [GANs by Ahlad Kumar (playlist)](https://www.youtube.com/playlist?list=PLdxQ7SoCLQAMGgQAIAcyRevM8VvygTpCu)
- [Building our first simple GAN](https://www.youtube.com/watch?v=OljTVUVzPpM)
- [Face editing with GANs](https://www.youtube.com/watch?v=dCKbRCUyop8)
- [Variational Autoencoders](https://www.youtube.com/watch?v=9zKuYvjFFS8)
- [GANs in 50 lines of code (PyTorch)](https://medium.com/@devnag/generative-adversarial-networks-gans-in-50-lines-of-code-pytorch-e81b79659e3f)
- [Generative Models (OpenAI)](https://openai.com/blog/generative-models/)
- **Style Transfer:** [TensorFlow fast style transfer](https://github.com/lengstrom/fast-style-transfer)

## 💬 Natural Language Processing (NLP)

- [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)
- [The Illustrated Word2vec](https://jalammar.github.io/illustrated-word2vec/)
- [NLP and The Reformer](https://www.youtube.com/watch?v=rNG_hpSyZcE)

### RNN (Recurrent Neural Networks)

- [Illustrated Guide to Recurrent Neural Networks](https://www.youtube.com/watch?v=LHXXI4-IEns)
- [Anyone Can Learn To Code an LSTM-RNN in Python](https://iamtrask.github.io/2015/11/15/anyone-can-code-lstm/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- [An Introduction to RNNs for Beginners](https://victorzhou.com/blog/intro-to-rnns/)
- [Attention and Augmented Recurrent Neural Networks (Distill)](https://distill.pub/2016/augmented-rnns/)
- [Visualizing memorization in RNNs (Distill)](https://distill.pub/2019/memorization-in-rnns/)
- [Deep Learning for NLP: ANNs, RNNs and LSTMs explained!](https://www.kdnuggets.com/2019/08/deep-learning-nlp-explained.html)

### LSTM

- [Understanding LSTM Networks (colah)](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)
- [LSTM implementation explained](https://apaszke.github.io/lstm-explained.html)
- [A Gentle Introduction to LSTM Autoencoders](https://machinelearningmastery.com/lstm-autoencoders/)

### Transformers & Self-Attention

**Visual Guide to Transformer Neural Networks (Highly Recommended)**
- [Part 1 — Position Embeddings](https://www.youtube.com/watch?v=dichIcUZfOw)
- [Part 2 — Multi-Head & Self Attention](https://www.youtube.com/watch?v=mMa2PmYJlCo)
- [Part 3 — Decoder's Masked Attention](https://www.youtube.com/watch?v=gJ9kaJsE78k)

- [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- [The Annotated Transformer (Harvard)](https://nlp.seas.harvard.edu/2018/04/03/attention.html)
- [Transformers from Scratch](https://e2eml.school/transformers.html)
- [Transformers Paper and Code](https://nn.labml.ai/transformers/index.html)
- [NLP Transformers Attention Playlist](https://www.youtube.com/playlist?list=PLxI06TjqRkofnRuvD-Ks0Qef5g73yrMQ7)
- [Transformers, Explained (GPT-3, BERT, T5)](https://daleonai.com/transformers-explained)
- [A comprehensive overview of Transformer variants (paper)](https://arxiv.org/abs/2106.04554)
- [Transformers Notes (Notion)](https://www.notion.so/Transformers-969f4b27c48147778c1e2dbda0c83ce0)
- [How to become an NLP & Transformer Model Guru](https://www.linkedin.com/pulse/how-become-transformer-model-guru-denis-rothman/)
- [[MASTERCLASS] Transformers | Attention Models](https://youtu.be/N7u13zO8DPw)

### BERT

- [Explaining BERT Simply Using Sketches](https://mlwhiz.medium.com/explaining-bert-simply-using-sketches-ba30f6f0c8cb)
- [A Visual Guide to Using BERT for the First Time](https://jalammar.github.io/a-visual-guide-to-using-bert-for-the-first-time/)
- [The Illustrated BERT, ELMo, and co.](https://jalammar.github.io/illustrated-bert/)
- [BERT Explained: State of the art language model for NLP](https://towardsdatascience.com/bert-explained-state-of-the-art-language-model-for-nlp-f8b21a9b6270)
- [BioBERT (biomedical domain)](https://github.com/dmis-lab/biobert)

### GPT

- [The Illustrated GPT-2](https://jalammar.github.io/illustrated-gpt2/)

## 🎮 Reinforcement Learning

- [Deep Reinforcement Learning Course 🕹️](https://simoninithomas.github.io/Deep_reinforcement_learning_Course/) _Beginner to expert, free._
- [LECTURES: Introduction to Reinforcement Learning — David Silver](https://www.davidsilver.uk/teaching/)
- [COMP M050 Reinforcement Learning by David Silver (UCL)](https://www.youtube.com/watch?v=2pWv7GOvuf0)
- [Deep RL: Pong from Pixels by Andrej Karpathy](http://karpathy.github.io/2016/05/31/rl/)
- [A Beginner's Guide to Deep Reinforcement Learning](https://pathmind.com/wiki/deep-reinforcement-learning)
- [RL Algorithms (Sutton's book + David Silver's course) — Code](https://github.com/dennybritz/reinforcement-learning)
- [Deep RL Algorithms with PyTorch](https://github.com/p-christ/Deep-Reinforcement-Learning-Algorithms-with-PyTorch)
- [Unity ML-Agents Toolkit](https://github.com/Unity-Technologies/ml-agents) · [An Introduction to Unity ML-Agents](https://towardsdatascience.com/an-introduction-to-unity-ml-agents-6238452fcf4c)
- [🖥️ WRITING MY FIRST MACHINE LEARNING GAME! (1/4)](https://www.youtube.com/watch?v=ZX2Hyu5WoFg)
- **Books:** [Reinforcement Learning — Sutton & Barto](https://drive.google.com/open?id=1lsBhr8H_PVnyidewtqduvV4b8wcsnAiH) · [Deep RL Hands On — Maxim Lapan](https://drive.google.com/open?id=1YJUTUsDy2jQ_du-eoExQkk0miCT2NPRm)

---

# Phase 5 — Applied AI & Production

### Transfer Learning

- [Transfer Learning with Keras and Deep Learning](https://www.pyimagesearch.com/2019/05/20/transfer-learning-with-keras-and-deep-learning/)
- [A Comprehensive Hands-on Guide to Transfer Learning](https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a)
- [TensorFlow Core Tutorials](https://www.tensorflow.org/tutorials)

### Deploying Models

- [How to deploy a ML model (SurveyMonkey Engineer explains)](https://www.youtube.com/watch?v=XsD2u7hAwI8)
- [Deploy Machine Learning Models with Django](https://www.deploymachinelearning.com/)
- [MLflow — open source platform for the ML lifecycle](https://mlflow.org/)
- [TensorFlow: Data and Deployment Specialization](https://www.coursera.org/specializations/tensorflow-data-and-deployment)

### MLOps

- [MLOps Primer — 2021](https://elvissaravia.substack.com/p/mlops-primer-2021)
- [MLOps Tooling Landscape v2 (+84 new tools)](https://huyenchip.com/2020/12/30/mlops-v2.html)

### Edge ML Kits

- [Nvidia Jetson Nano Developer Kit](https://developer.nvidia.com/embedded/jetson-nano-developer-kit)
- [Intel® Neural Compute Stick 2](https://software.intel.com/en-us/neural-compute-stick)
- [Coral](https://coral.ai/)

---

# Phase 6 — Practice, Reference & Community

### Practice & Compete

- [Kaggle](https://www.kaggle.com/)
- [codebasics/py (code repo)](https://github.com/codebasics/py)
- [Google Codelabs](https://codelabs.developers.google.com/)

### Advanced — Courses from Top Universities

> Use these for depth once you have the fundamentals. Most are full lecture playlists.

**Stanford University**
- [CS221 — Artificial Intelligence: Principles and Techniques](https://www.youtube.com/playlist?list=PLoROMvodv4rOca_Ovz1DvdtWuz8BfSWL2)
- [CS229 — Machine Learning (Andrew Ng)](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU)
- [CS230 — Deep Learning (Andrew Ng)](https://www.youtube.com/playlist?list=PLoROMvodv4rOABXSygHTsbvUz4G_YQhOb)
- [CS231n — CNNs for Visual Recognition (Fei-Fei Li, Karpathy)](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv)
- [CS224n — NLP with Deep Learning (Christopher Manning)](https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ)
- [CS234 — Reinforcement Learning (Emma Brunskill)](https://www.youtube.com/playlist?list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u)
- [CS330 — Deep Multi-task and Meta Learning (Chelsea Finn)](https://www.youtube.com/playlist?list=PLoROMvodv4rNjRoawgt72BBNwL2V7doGI)
- [CS25 — Transformers United](https://www.youtube.com/playlist?list=PLoROMvodv4rNiJRchCzutFw5ItR_Z27CM)

**Carnegie Mellon University**
- [11-711: Advanced NLP (Graham Neubig)](https://www.youtube.com/playlist?list=PL8PYTP1V4I8D0UkqW2fEhgLrnlDW9QK7z)
- [11-747: Neural Networks for NLP (Graham Neubig)](https://www.youtube.com/playlist?list=PL8PYTP1V4I8AkaHEJ7lOOrlex-pcxS-XV)
- [11-737: Multilingual NLP (Graham Neubig)](https://www.youtube.com/playlist?list=PL8PYTP1V4I8BhCpzfdKKdd1OnTfLcyZr7)
- [11-777: Multimodal Machine Learning (Louis-Philippe Morency)](https://www.youtube.com/channel/UCqlHIJTGYhiwQpNuPU5e2gg/videos)
- [11-785: Introduction to Deep Learning (Bhiksha Raj, Rita Singh)](https://www.youtube.com/channel/UC8hYZGEkI2dDO8scT8C5UQA/playlists)
- [Low Resource NLP Bootcamp 2020 (Graham Neubig)](https://www.youtube.com/playlist?list=PL8PYTP1V4I8A1CpCzURXAUa6H4HO7PF2c)

**Massachusetts Institute of Technology**
- [6.S191 — Introduction to Deep Learning](https://www.youtube.com/playlist?list=PLtBw6njQRU-rwp5__7C0oIVt26ZgjG9NI)
- [6.S094 — Deep Learning (Lex Fridman)](https://www.youtube.com/playlist?list=PLrAXtmErZgOeiKm4sgNOknGvNjby9efdf)
- [6.S192 — Deep Learning for Art, Aesthetics, and Creativity (Ali Jahanian)](https://www.youtube.com/playlist?list=PLCpMvp7ftsnIbNwRnQJbDNRqO6qiN3EyH)

### Cheatsheets

- [Artificial Intelligence (Stanford CS221)](https://stanford.edu/~shervine/teaching/cs-221/)
- [Machine Learning (Stanford CS229)](https://stanford.edu/~shervine/teaching/cs-229/)
- [Deep Learning (Stanford CS230)](https://stanford.edu/~shervine/teaching/cs-230/)
- [ML tips and tricks](https://stanford.edu/~shervine/teaching/cs-229/cheatsheet-machine-learning-tips-and-tricks)
- [Data Science Tools](https://www.mit.edu/~amidi/teaching/data-science-tools/)
- [Machine Learning with R](https://www.mit.edu/~amidi/teaching/modeling/study-guide/machine-learning-with-r/)
- [Chris Albon — Cheat Sheets and Flash Cards](https://chrisalbon.com/)
- [Linear Algebra (Stanford CME-102)](https://stanford.edu/~shervine/teaching/cme-102/linear-algebra)
- [Ordinary Differential Equations for Engineers](https://stanford.edu/~shervine/teaching/cme-102/cheatsheet-first-ode)

### Essential Blogs to Follow

These authors created many of the best tutorials linked throughout this repo:

- [Andrej Karpathy](http://karpathy.github.io/)
- [Brandon Rohrer](https://e2eml.school/blog.html)
- [Andrew Trask](https://iamtrask.github.io/)
- [Jay Alammar](https://jalammar.github.io/)
- [Sebastian Ruder](https://ruder.io/)
- [Christopher Olah](https://colah.github.io/)
- [Distill](https://distill.pub/)

### Important YouTube Channels (AI / ML / RL / DS)

- [3Blue1Brown](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)
- [StatQuest with Josh Starmer](https://www.youtube.com/user/joshstarmer)
- [Sentdex](https://www.youtube.com/user/sentdex)
- [Luis Serrano](https://www.youtube.com/channel/UCgBncpylJ1kiVaPyP-PZauQ)
- [Brandon Rohrer](https://www.youtube.com/user/BrandonRohrer)
- [deeplizard](https://www.youtube.com/channel/UC4UJ26WkceqONNF5S26OiVw)
- [Tech With Tim](https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg)
- [Microsoft Research](https://www.youtube.com/user/MicrosoftResearch)
- [Corey Schafer](https://www.youtube.com/user/schafer5)
- [Data School](https://www.youtube.com/user/dataschool)
- [Two Minute Papers](https://www.youtube.com/user/keeroyz)
- [Welch Labs](https://www.youtube.com/user/Taylorns34)
- [Lex Fridman](https://www.youtube.com/channel/UCSHZKyawb77ixDdsGog4iWA)
- [Alexander Amini](https://www.youtube.com/user/Zan560)
- [The Coding Train](https://www.youtube.com/user/shiffman)
- [Jeff Heaton](https://www.youtube.com/user/HeatonResearch)
- [Abhishek Thakur](https://www.youtube.com/user/abhisheksvnit)
- [freeCodeCamp.org](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
- [edureka!](https://www.youtube.com/user/edurekaIN)
- [Simplilearn](https://www.youtube.com/user/Simplilearn)
- [Great Learning](https://www.youtube.com/user/beaconelearning)
- [TensorFlow](https://www.youtube.com/channel/UC0rqucBdTuFTjJiefW5t-IQ)
- [DeepLearning.AI](https://www.youtube.com/channel/UCcIXc5mJsHVYTZR1maL5l9w)

### Communities to Follow

- [AI Coimbatore](https://www.meetup.com/AICoimbatore/) — [Telegram](https://t.me/joinchat/MmtTDRUcEqIuAPpr6Ph0Jw) · [Facebook](https://www.facebook.com/groups/440187506472896/)
- [TensorFlow User Group Coimbatore](https://www.tensorflow.org/community/groups) — [Meetup](https://www.meetup.com/TFUGCbe/) · [Facebook](https://www.facebook.com/groups/2425901487658992/)

---

## 🙏 Credits

This is a **reorganized, learning-sequenced** version of the *"Ultimate Compilation of AI Resources for Mathematics, Machine Learning and Deep Learning"* originally created and maintained by **[Navaneeth Malingan](https://www.linkedin.com/in/nivu/)**. All original links and attribution are preserved — only the ordering has been restructured for a beginner-to-advanced learning journey.

> _"Knowledge Not Shared is wasted."_

⭐ If this helped you, star the repo and share it with a fellow learner.
