# TextLabs

## Simulation-based Natural Language Understanding for Scientific Procedural Texts

# About

We are a group of researchers at [Hebrew University of Jerusalem](https://en.huji.ac.il/en), [Georgia Tech](https://www.gatech.edu/), the [Allen Institute for Artificial Intelligence](https://allenai.org/) & [Ohio State University](https://www.osu.edu/). 

The TextLabs project targets natural language understanding (NLU) of complex scientific procedural texts ("recipes" for performing experiments). This page hosts project resources, such as links to publications, models, code and data.

On the NLU side, experimental procedures typically feature dense, technical and under-specified language, making them a particularly tough nut to crack for current state-of-the-art-systems. 

On the application side, there is [rapidly growing interest](https://www.youtube.com/watch?v=L1UgdoP2aeg) in [automated execution of experimental protocols](https://science.sciencemag.org/content/370/6512/101), to address serious reproduceability issues across many fields, such as chemistry, biology and materials science.

Current procedural datasets serve primarily for text-mining applications, and do not provide enough detail to support execution. To begin bridging the gap towards execution, we re-framed procedural text understanding as a text-to-code setting, and developed a novel process-level representation called a Process Execution Graph (PEG). Natural language protocols can be parsed into PEGs which can later be converted into actual instructions for automated, executable workflows. 

![TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Webp.net-gifmaker.gif](TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Webp.net-gifmaker.gif)

In practice, we enriched a sub-set of the existing [Wet Labs Protocols dataset](https://www.aclweb.org/anthology/N18-2016/) to our PEG format. The current version features:

- eXecutable Wet Labs Protocols (X-WLP): a new dataset containing process level PEG annotations for 279 protocols.
- An interactive text-based game annotation interface which handles visualization, input validation and state tracking ([demo video](https://www.youtube.com/watch?v=3NqYKMzolQ4)).
- Modelling experiments on X-WLP using a [SciBERT](https://www.aclweb.org/anthology/D19-1371/) pipeline and a multi-task approach based on the [DyGIE++](https://www.aclweb.org/anthology/N19-1308/) method.

In the future, we look forward to making use of the underlying text-based game environment, by leveraging recent advances in text-based reinforcement learning (RL) agents and adapting them to our data.

---

# Explore the data

(Coming soon)

---

# Publications

- **Process-Level Representation of Scientific Protocols with Interactive Annotation**

    *Ronen Tamari, Fan Bai, Alan Ritter and Gabriel Stanovsky*

    EACL 2021

    (paper)

    (code and data coming soon)

---

# Team

![TextLabs%206eeadb05c4584b979baa1f96fce6e81d/profile.jpeg](TextLabs%206eeadb05c4584b979baa1f96fce6e81d/profile.jpeg)

[Ronen Tamari](https://ronentk.github.io/)

![TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled.png](TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled.png)

[Fan Bai](https://bflashcp3f.github.io/)

![TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled%201.png](TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled%201.png)

[Alan Ritter](http://aritter.github.io/)

![TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled%202.png](TextLabs%206eeadb05c4584b979baa1f96fce6e81d/Untitled%202.png)

[Gabriel Stanovsky](https://gabrielstanovsky.github.io/index.html)
