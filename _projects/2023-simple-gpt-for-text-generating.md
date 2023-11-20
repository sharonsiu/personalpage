---
title: "Simple GPT for text generating"
collection: projects
permalink: /projects/2023-simple-gpt-for-text-generating
duration: March 2023
---



About the project:
  - individual project
  - in Msc Year 1 Sem B
  - aims: generate similar text as the data text

Software:
  - coding: Colab
  - train data: Lambda labs

Model:
  - Attention is all you need ---  Ashish Vaswani et al
  - attention (encoder & decoder) (task: perform language translation)
  - only decoder (task: generate similar text as the data text)
  - purpose: generate a sequence of the probability of tokens

Model detail:
  - Let's build GPT: from scratch, in code, spelled out. --- Andrej Karpathy
    1. Generate the embedding layer
    2. Do positional encoding
    3. Addition of embedding layer and positional encoding
    4. Output from Step 3 continues entering the first block with two main layers. One is the normalization layer, and the other is the masked multi-head attention while running a residual connection.
    5. Outputs from Step 5 continues entering the third block with two main layers. One is the normalization layer, and the other is a feed-forward layer while running a residual connection.
    6. Run the loss function
    7. Perform softmax
    8. Generate output sequence by sampling from the distribution
   
[Code link] (https://colab.research.google.com/drive/11BOZ3m-4XbmRWbAJcT6ro4szKV7xOlyC?usp=sharing)

