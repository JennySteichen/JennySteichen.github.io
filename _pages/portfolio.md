---
permalink: /
layout: archive
title: "Portfolio"
excerpt: "Portfolio"
author_profile: true

redirect_from: 
  - /portfolio/
  - /portfolio.html
---

Generating Music with an LSTM
-----
<img height="100" src="/images/drum_kit.jpg">

We develop a model to improvise  percussion music ([code download](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/ImprovisePercussionMusic.ipynb) or [display notebook without output](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/ImprovisePercussionMusicWithoutOutput.ipynb). The entire file is too large to display on Github).  Since music is sequential, we use a specialized Recurrent Neural Network (RNN) called a [LSTM model](https://en.wikipedia.org/wiki/Long_short-term_memory) (Long short-term Memory) Model to learn the patterns of musical sequences.  We then use these learned patterns to generate new music. 

The type of music depends on a collection of music files in [MIDI format](https://en.wikipedia.org/wiki/MIDI).  Each MIDI file corresponds to a musical piece, which is a series of notes over time.  In this example, we use the [Groove Dataset](https://www.tensorflow.org/datasets/catalog/groove) from TensorFlow.  However, in the appendix, we show how to import files from a url.

Titanic Kaggle Competition
----

<img height="100" src="/images/titanic_feature_elimination.png">

[Ranked in the top 7%](https://www.kaggle.com/competitions/titanic/leaderboard) of the Kaggle Competition for prediction which passengers survived the Titanic.  My submission included data imputation for missing data, creating new features, comparing different models, and creating ensemble models.  An [outline of my submission](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/TitanicPredictionNotebook.ipynb) gives an idea of my thinking process.

Homeschooling Data Visualization
----

<img height="100" src="/images/homeschooling_reasons.png">

[Data Visualization](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/HomeschoolingExploration.html) using R and RStudio ([code](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/HomeschoolingExploration.Rmd)).  A variety of graphs illustrate different aspects of homeschooling families.

Prompt Engineering Example -- ChatGPT and Mad Libs
------

<img height="100" src="/images/MadLibGenerated.png">

Demonstrated the difference a prompt can make with ChatGPT.  Used the example of generating [Mad Libs with different prompts](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/ChatGPT_MadLib_Generator.ipynb).

NLP Word Embeddings
------

<img height="100" src="/images/word_analogies.png">

In Natural Language Processing (NLP),  [Word Embeddings](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/WordEmbeddings.ipynb) represent words with real-valued vectors in sucha way that word embedding vectors that are close correspond to words that are similar in meaning. In this project, we use Linear Algebra to 
- Solve Word Analogies
- Discover bias in the word embeddings
- Neutralize bias in words like "receptionist"
- Apply equalization to pairs of words like "actor" and "actress" on either side of a bias to make them reflections over the bias vector.

Student Dashboard
------

<img height="100" src="/images/student_dashboard.png">

My homeschooling students used [student dashboards](https://github.com/JennySteichen/JennySteichen.github.io/blob/master/_portfolio/Student%20Dashboard.xlsx) to measure their quarterly progress.

