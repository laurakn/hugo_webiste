---
title: "What You See May Not Be What You Get: UCB Bandit Algorithms Robust to epsilon-Contamination"
date: 2020-01-01
publishDate: 2020-07-15T21:48:22.122303Z
authors: ["Laura Niss", "Ambuj Tewari"]
publication_types: ["2"]
#abstract: "Motivated by applications of bandit algorithms in education, we consider a stochastic multi-armed bandit problem with $varepsilon$-contaminated rewards. We allow an adversary to give arbitrary unbounded contaminated rewards with full knowledge of the past and future. We impose the constraint that for each time $t$ the proportion of contaminated rewards for any action is less than or equal to $varepsilon$. We derive concentration inequalities for two robust mean estimators for sub-Gaussian distributions in the $varepsilon$-contamination context. We define the $varepsilon$-contaminated stochastic bandit problem and use our robust mean estimators to give two variants of a robust Upper Confidence Bound (UCB) algorithm, crUCB. Using regret derived from only the underlying stochastic rewards, both variants of crUCB achieve $mathcalO (sqrtKTlog T)$ regret for small enough contamination proportions. Our simulations assume small horizons, reflecting the newly explored setting of bandits in education. We show that in certain adversarial regimes crUCB not only outperforms algorithms designed for stochastic (UCB1) and adversarial (EXP3) bandits but also those that have \"best of both worlds\" guarantees (EXP3++ and TsallisInf) even when our constraint on the proportion of contaminated rewards is broken."
featured: false
publication: ""
tags: ["Computer Science - Machine Learning", "Statistics - Machine Learning"]
url_pdf: "http://arxiv.org/abs/1910.05625"
---
