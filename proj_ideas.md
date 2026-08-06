---
layout: default
title: "Project Ideas"
permalink: /proj_ideas
---



<h1 align="center"> Project Ideas </h1>


The Daniel Kahneman Algorithm to moderate our intuitive predictions.


[Useful Slack patch](https://github.com/SharonBrizinov/slack-anti-delete/tree/main)


[Safe AI usage with Claude Caude](https://blog.emilburzo.com/2026/01/running-claude-code-dangerously-safely/)


[This with FHE ? Should I try ?](https://overreacted.io/a-social-filesystem/#a-social-filesystem)


Would be interested to test [Simile](https://www.simile.ai/) for mechanism design situations.


Study of overfitting in LLMs: given [training data size](https://geohot.github.io/blog/jekyll/update/2026/05/20/what-will-better-mean.html)(I trust this man) and current (May 2026) models size, to what extent can we say that LLMs tend to be huge lookup tables ? Signal in the training dataset is actually way larger than 20T tokens given interaction spaces (each token appears in multiple different situations) but still it would be interesting to look at simple DL models for which the number of weights is 10-20% of training dataset size. 



**Ambitious** (2026/07/17): A vault/database containing all content produced by humans, without any involvement from AI. A bit like the Svalbard Global Seed Vault in cold Norway. 


**Ambitious**: an open paltform for training and inference on FHE-encrypted data. Anyone could define a question that can be answered by a ML model (prediction tasks, causal inference), the data required and a minimal volumetry to reach (with potentially a space to discuss all that). Then people could upload their data, totally encrypted, and once the training dataset is consistent enough, the model could be train on the encrypted observations, and then be used to do inference or else. It could be used as a fun platform for curious people (a bit Polymarket vibe), but maybe also to help government do deal with public policy stuff (maybe ?). FHE would bring a far superior security than simple anonymity and secured server, and would make it possible for gathering extremely rich and detailed features, potentially very sensitive but totally encrypted end-to-end, with nothing plain text on the platform. However, several things need to be solved:
* Cryprography Technical: keys management is complicated, especially for the training step (distributed key generation, committee appointment) and potentially breaks a bit the project main vibe.
* ML Technical: FHE works today, but is still a bit limited, in term of model size and variety, but also regarding types you can encrypt (only small integer). For certain features it means finding a way to make them simpler in order to be encrypted.
* Social: In term of incentive, how to ensure people send true data and not random/malicious info in order to bias the model ?
