# Basics

## What is AI?

### Demystifying AI

**AI**

- ANI (artificial narrow intelligence)
  - E.g., smart speaker, self-driving car, web search
- Generative AI (generative artificial intelligence)
  - E.g., ChatGPT, Bard, Midjourney
- AGI (artificial general intelligence)
  - Do anything a human can do

### Machine Learning

**Supervised Learning**

| Input (A)         | Output (B)             | Application         |
| ----------------- | ---------------------- | ------------------- |
| email             | spam? (0/1)            | spam filtering      |
| audio             | text transcripts       | speech recognition  |
| English           | Chinese                | machine translation |
| ad, user info     | click? (0/1)           | online advertising  |
| image, radar info | position of other cars | Self-driving car    |
| image of phone    | defect? (0/1)          | visual inspection   |
| sequence of words | the next word          | chatbot             |

**How large language models (LLMs) work**

LLMs are built by using supervised learning (A->B) to repeatedly predict the next word.

E.g. - My favourite drink is lychee bubble tea.

| Input (A)                           | Output (B) |
| ----------------------------------- | ---------- |
| My favourite drink                  | is         |
| My favourite drink is               | lychee     |
| My favourite drink is lychee        | bubble     |
| My favourite drink is lychee bubble | tea        |

When we train a very large AI system on a lot of data (hundreds of billions of words), we get a Large Language Model like ChatGPT.

### What is Data?

**Dataset**

| size of house (square foot) | # of bedrooms | price (1000$) |
| --------------------------- | ------------- | ------------- |
| 523                         | 1             | 115           |
| 645                         | 1             | 150           |
| 708                         | 2             | 210           |
| 1034                        | 3             | 280           |
| 2290                        | 4             | 355           |
| 2545                        | 4             | 440           |

- **A** (input) -> **B** (output)
- **A** can be size of the house and **B** can be the price.
- **A** can be a combination of size of house and number of bedrooms and **B** can be the price.
- **A** can be the price and **B** can be the size of house one can get.

**Acquiring Data**

- Manual Labeling
- Observing Data
