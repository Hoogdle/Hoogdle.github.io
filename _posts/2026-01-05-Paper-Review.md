---
layout: post
title:  "Latent Reasoning"
description: "Reviewing AI Research Papers by own myself, LLM and RL."
type: card-dated
date:   2025-01-07 09:01:21 -0000
categories: Dumabrton style
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
last-updated: 2025-01-07 09:01:21 -0000
categories: post
tag: AI, RL
author: Kim Taeyeong
card: card-2
---

Hi there, this post is for sharing the review of AI Research paper focused on Latent Reasoning.
This post is consist of serveral article and each article deals one research paper. You can easily go to the article by hyperlink table.


<ul style="color:blue">
  <a href="/post/2020/10/29/Paper-Review.html#latent-reasoning" style="color:navy; margin-bottom:0rem;"><strong>Latent Reasoning</strong></a>
  <li style="font-size : 15px">
    Training Large Language Models to Reason in a Continuous Latent Space
  </li>
</ul>


<hr>
<h5 id="latent-reasoning"><strong><mark>Latent Reasoning</mark></strong></h5>

Before jumping into Latent Reasoning, you should know about Chaing-of-Thought(CoT), of course how the LLM works. But don't worry! I will exaplain what they are in simple way in this article. If you want to know about it in more detail, please see another article.


<b>LLM Mechanism</b><br>
Most of Large Language Models(LLM) follow the transformer architecture. We can roughly classify transformer as two type, Encoder and Decoder. Encoder is for making high quality words or sentence representation as a vector. In contrast, decoder generates a sentence with auto-regressive way. It requires huge pages to deal all about it.. So let me focus only on the **Decoder Architecture**, which is the target model in Latent Reasoning.

<b>Decoder Architecture</b><br>
I think you have a experience using **generative AI model** such as Chat GPT, Gemini. Those model is based on the Transformer Decoder Architecture. To make you simply and clearly understand Decoder Architecture, I want you to remember two-keywords in Decoder Architecture.

<ul>
  <li><b>Self-Attention</b></li>
  <li><b>Auto-Regressive</b></li>
</ul>


<b>Chaing of Thought</b><br>

<hr>
