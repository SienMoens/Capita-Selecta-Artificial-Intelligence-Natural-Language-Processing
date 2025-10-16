# Capita Selecta Computer Science: Artificial Intelligence - Natural Language Processing

This repository contains lectures and exercise sessions material corresponding to KU Leuven course [B-KUL-H05N0A](https://onderwijsaanbod.kuleuven.be/syllabi/e/H05N0AE.htm#activetab=doelstellingen_idm9925824).

## Teaching Team

### Instructor
<div align="center">
  <img src="teaching team/Marie-Francine Moens.png" alt="Marie-Francine Moens" width="150px">
  <p><a href="https://people.cs.kuleuven.be/~sien.moens/">Marie-Francine Moens</a></p>
</div>

### Teaching Assistants
<div align="center">
  <div style="display: flex; justify-content: space-around; align-items: center;">
    <div>
      <img src="teaching team/Jonathan Tonglet.png" alt="Jonathan Tonglet" width="150px">
      <p><a href="https://jtonglet.github.io/">Jonathan Tonglet</a></p>
    </div>
    <div>
      <img src="teaching team/Ruben Cartuyvels.png" alt="Ruben Cartuyvels" width="150px">
      <p><a href="https://scholar.google.com/citations?user=Z5EfdIAAAAAJ&hl=en">Ruben Cartuyvels</a></p>
    </div>
    <div>
      <img src="teaching team/Nathan Cornille.png" alt="Nathan Cornille" width="150px">
      <p><a href="https://nathancornille.github.io/">Nathan Cornille</a></p>
    </div>
  </div>
</div>

## Table of Contents  
**Capita Selecta Computer Science: Natural Language Processing**

### Lectures  
**Marie-Francine Moens**

**Chapter 1: Introduction**
- Goals of the course  
- Challenges of NLP: ambiguity, uncertainty, incompleteness of language, long-tail distribution of linguistic patterns  
- Vector representations  
- Evaluation metrics  

**Chapter 2: Sequential Tagging: Part 1**
- Token versus sequence tagger  
- Generative tagger: Hidden Markov Model  
- Discriminative taggers: Maxent, Conditional Random Field  
- Gradient descent-based optimization  
- Decoding strategies  
- Illustration with POS tagging  

**Chapter 3: Sequential Tagging: Part 2**
- Neural encoder-decoder architecture  
- Autoregressive decoding  
- Recurrent neural network (RNN) and long short-term memory network (LSTM)  
- Multi-task learning  
- Illustrated with named entity recognition, entity linking, and entity-relation extraction  

**Chapter 4: Language Modeling and Attention**
- Cross-attention, self-attention, multi-head attention, and sparse attention  
- Transformer architecture  
- Tokenization  
- Positional encoding  
- Frequency-based n-gram language models, smoothing, discounting, interpolation  
- Recurrent neural network (RNN) language models  
- Transformer language models  

**Chapter 5: Foundation Models and Parameter-Efficient Fine-Tuning**
- Encoder-only models, decoder-only models, encoder-decoder models  
- Parameter-efficient fine-tuning, adapters, low-rank adaptation, feature routing  
- Prompting  

**Chapter 6: Recognition and Induction of Tree Structures**
- **Constituent Parsing:**
  - Probabilistic context free grammar  
  - Efficient decoding: CKY algorithm  
  - Tree recursive neural networks  
  - Self-supervised constituent grammar induction  
- **Dependency Parsing:**
  - Graph-based dependency parsing  
  - Transition-based dependency parsing  
- Illustrated with syntactic parsing of a sentence  

**Chapter 7: Recognition of Complex Graph Structures**
- Graph convolutional neural network  
- Graph transformer  
- Iterative inference  
- Illustrated with semantic role labeling, Abstract Meaning Representation (AMR) parsing, and AMR-to-text generation  

**Chapter 8: Semantic Parsing and Solving Math Word Problems**
- Learning to map to a semantic knowledge representation  
- Learning to directly map to a denotation  
- Neural sequence-to-sequence models  
- Neural sequence-to-tree models and tree-based decoding  
- Illustrated with solving math word problems  

**Chapter 9: Discourse Analysis, Constraint-Based Reasoning, and Reasoning with Common Sense**
- **Noun Phrase Coreference Resolution:**
  - Rule-based model (Hobbs algorithm)  
  - Span detection  
  - Mention pair and mention ranking models  
- Inference with integer linear programming  
- Neural end-to-end coreference resolution  
- Leveraging LLMs and reasoning with commonsense  

**Chapter 10: Spatial and Temporal Representation Learning and Reasoning**
- **Temporal Information Processing:**
  - Timex recognition and normalization  
  - Temporal relation extraction and integration of temporal reasoning  
  - Direct prediction of a timeline and its loss functions  
- **Spatial Information Processing:**
  - Spatial relation extraction and integration of spatial reasoning  
  - Direct prediction of spatial coordinates and its loss functions  

**Chapter 11: Machine Reading Comprehension**
- Representation learning of question and (con)text  
- Question-(con)text interaction  
- Memory networks  
- Linear RNNs: MAMBA architecture  
- Test time training layers  

**Chapter 12: Machine Translation and Multilingual Large Language Models**
- **Encoder-decoder models for machine translation:**
  - RNN-based architecture  
  - Transformer architecture  
  - Unsupervised machine translation  
- Decoder-only models for simultaneous translation  
- Advanced decoding strategies  
- Multilingual large language models  

**Chapter 13: Conversational Dialogue Systems and Chatbots**
- Dialogue modeling  
- Generative hierarchical neural networks  
- Reinforcement learning: Group Relative Policy Optimization  

---

### Exercises  
**Ruben Cartuyvels, Nathan Cornille, Quynh Do, Victor Milewski, Wei Sun, and Marie-Francine Moens**

- Exercises on language modeling and attention mechanisms  
- Exercises on sequential tagging, the recognition of graph structures, and semantic parsing  
- Exercises on structured learning and prediction, integrating integer linear programming constraints, and induction of latent structures  
- Exercises on machine translation and decoding  
- Exercises on iterative inference and machine reading comprehension  






