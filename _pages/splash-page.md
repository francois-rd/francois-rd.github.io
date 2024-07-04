---
title: "Hi, I'm Francois!"
layout: splash
permalink: /
date: 2024-06-27T11:59:59-04:00
header:
  overlay_filter: linear-gradient(rgba(64, 0, 0, 0.5), rgba(0, 64, 64, 0.5))
  overlay_image: /assets/images/splash-banner.jpg
  og_image: /assets/images/bio-photo.jpg
  actions:
    - label: 'Learn More About Me&nbsp;&nbsp;&nbsp;<i class="fas fa-fw fa-arrow-right"></i>'
      url: "/about/"
  caption: "Photo: [<b>Sebastian Kanczok</b>](https://unsplash.com/photos/round-orange-light-effects-q_lEm5iDLYQ)"
excerpt: >
  <img src="/assets/images/bio-photo.jpg" alt="Francois Roewer-Despres" style="margin-bottom: 10px; max-width: 150px; border-radius: 50%; border: 5px solid rgb(242, 243, 243);"><br>I'm a PhD candidate at the University of Toronto researching ***reasoning***, ***grounding***, and ***safety*** in large language models.
feature_row6:
  - image_path: /assets/images/cardio-og.jpg
    image_caption: "Photo: [<b>National Cancer Institute</b>](https://unsplash.com/photos/person-sitting-while-using-laptop-computer-and-green-stethoscope-near-NFvdKIhxYlU)"
    alt: "Cardiovascular patient readmission risk assessment tool"
    title: "Predicting Cardiovascular Readmission Risk from Doctor-Patient Conversation"
    excerpt: |
      In this project, we seek to predict outcomes of clinical interest, such as 30-day readmission risk or death, from transcripts of recorded doctor-patient interviews and associated structured electronic medical record data using state-of-the-art large language models.

      The key goals of the project are to:
       * Build AI-based prediction models for each outcome of interest.
       * Validate the accuracy and effectiveness of the built models, and compare them against more traditional methods.
       * Present a framework for the implementation and deployment of the models in a clinical setting as a means of providing clinical decision support.
    url: "/cardio/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row5:
  - image_path: /assets/images/accord-logo.png
    alt: "ACCORD Logo"
    title: "<i>ACCORD</i>: Closing the Commonsense Measurability Gap"
    excerpt: |
      *ACCORD* is a scalable framework and benchmark suite for disentangling the commonsense grounding and reasoning abilities of **large language models** (LLMs) through controlled, multi-hop counterfactuals.

      Uniquely, *ACCORD* can automatically generate benchmarks of arbitrary reasoning complexity, and so it **scales with LLM capabilities**.

      State-of-the-art LLMs &mdash; GPT-4o, Mixtral-8x22B, Llama-3-70B &mdash; perform no better than random chance on *ACCORD* after only moderate scaling, indicating a need for substantial improvement in LLMs' commonsense reasoning ability.
      
      [<i class="fab fa-fw fa-github"></i>](https://github.com/francois-rd/accord/)
      [<i class="fa-solid fa-book"></i>](https://arxiv.org/abs/2406.02804)
      [<i class="fas fa-download"></i>](https://www.codabench.org/competitions/3160/)
    url: "/accord/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/coma-logo.png
    alt: "Coma Logo"
    title: "<code>coma</code>: Configurable command management for humans"
    excerpt: |
      `coma` is a Python library for rapidly building configurable command-based programs.

      Configurations leverage [omegaconf](https://github.com/omry/omegaconf/)'s extremely rich and powerful configuration management features. Command selection abstracts away the `argparse` boilerplate, while [hooks](https://en.wikipedia.org/wiki/Hooking) enable plug-and-play flexibility.

      I developed `coma` to **rapidly prototype and iterate my deep learning research projects**. I use `coma` commands to split my workflow into discrete steps. This separation of concerns enables me to focus of producing impactful research, instead of getting bogged down in the minutiae of implementation details.

      [<i class="fab fa-fw fa-github"></i>](https://github.com/francois-rd/coma/)
      [<i class="fa-solid fa-book"></i>](https://coma.readthedocs.io/)
    url: "/coma/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/phonemic-splash.png
    alt: "Confusion-Mitigation Framework and LSTM Architecture"
    title: "Towards Detection and Remediation of Phonemic Confusion"
    excerpt: |
      Reducing communication breakdown (where two speakers are confused about what the other is saying) is critical to success in **interactive NLP applications, such as chatbots**. To this end, we proposed a confusion-mitigation framework to detect and avoid communication breakdown.

      As a first step towards implementing this framework, we focus on detecting phonemic sources of confusion. As a proof-of-concept, we evaluate two neural architectures in predicting the probability that a listener will misunderstand phonemes in an utterance.

      We show that both neural models outperform a weighted *n*-gram baseline, showing early promise for the broader framework. 

      [<i class="fab fa-fw fa-github"></i>](https://github.com/francois-rd/phonemic-confusion/)
      [<i class="fa-solid fa-book"></i>](https://aclanthology.org/2021.sigmorphon-1.1.pdf)
    url: "/phonemic/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/fem-splash.png
    alt: "Probabilistic Finite-Element Model Simulation Using Deep Learning"
    title: "Towards finite element simulation using deep learning"
    excerpt: |
      Finite-element modeling (FEM) is commonly used to simulate soft-tissue biomechanics, but is too computationally burdensome for use in real-time applications.

      We found that **deep learning models** consistently produced lower reconstruction error than equivalently-sized traditional dimensionality reduction models, while simultaneously running in real time.

      These results are a preliminary step towards simulating complete biomechanical soft-tissue models in real time with high fidelity.

      [<i class="fa-solid fa-book"></i>](https://cmbbe2018.tecnico.ulisboa.pt/pen_cmbbe2018/pdf/WEB_PAPERS/CMBBE2018_paper_89.pdf)
    url: "/fem/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row1:
  - image_path: /assets/images/speaking-splash.png
    alt: "Virtual Electropalatography for 3D biomechanical simulations."
    title: "Speaking Tongues Are Actively Braced"
    excerpt: |
      Previous studies of the human vocal tract have tended to describe bracing of the tongue against the teeth or palate only in terms of incidental contact (rather than mechanical support), and only in limited phonetic contexts. As such, bracing is seen as an occasional state, peculiar to specific sounds or sound combinations.

      Using a more holistic context, we demonstrate that tongue bracing is both pervasive and effortful in continuous English speech passages using Electropalatography (EPG) and **3D biomechanical simulations**.

      Our biomechanical simulations show that lateral bracing is an active posture requiring dedicated muscle activation. Hence, our use of the term "bracing" (rather than merely "contact").

      [<i class="fa-solid fa-book"></i>](https://d1wqtxts1xzle7.cloudfront.net/69525671/80d094d5d10fd9ff8bea952a3338e7b9c6af-libre.pdf?1631705646=&response-content-disposition=inline%3B+filename%3DSpeaking_Tongues_Are_Actively_Braced.pdf&Expires=1719774868&Signature=ZhlY1JZM~b14aQHq4ZmZIIBoK~gHTeu8iY93TGxEkdQpk57xtbttTv~MEm~sRM8Kiq2Wal7dtIPT-tcG4BhIw-9odYf8hyq8VE0mzaAQyapqkZldS8kZOuKApZ4YzYM9w-ASTnZc9aQek7TtKRiolb4Uuau1HgMc-ZLU~O9ygxJ573g07LL08vhPC8hQha6i92vmi4mAYtMtjQFuKjGUfjj8d8J9VAPGCyPjaCZ18Tz1lJIIyHqv8zLCa8zSCOKd69JVCFvEY7GHQoriNuK9yX0WsprGqeO23OVw34mK~BqYJA~uDJhUw8C8TtDQEDiec9TiPr4PSuSkhW5mvzKlPw__&Key-Pair-Id=APKAJLOHF5GGSLRBV4ZA)
    url: "/speaking/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

# Selected Research and Projects
<hr style="margin-bottom: 2em;">

{% include feature_row id="feature_row6" type="left" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row4" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row1" type="left" %}

# [About Me](/about/)
# [Publications](https://scholar.google.com/citations?user=uiA5W-YAAAAJ&hl=en)
# [Resume and CV](/francois-rd-cv.pdf)
