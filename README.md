<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Andrew Shilman: fullstack / systems / AI / databases"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/andrew-shilman"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:Andrew.Shilman@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://andrewshilman.dev"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>


<p align="center">
  <img src="./assets/terminal.svg" width="58%" alt="terminal: whoami, what I'm working on, and a joke training run"/>
  <img src="./assets/gradient-descent.svg" width="40%" alt="ASCII 3D loss landscape with momentum SGD rolling into the minimum"/>
  <br/>
  <sub>a 3D loss surface rendered in ASCII, with momentum SGD finding the minimum (pure SVG + CSS, no JS)</sub>
</p>


## Featured work
 
- **ShilmanDB**: a relational database engine in C++ built from scratch (SQL parser, B+ tree index, Volcano-style executor, buffer pool). Its learned join-order optimizer hits 94.1% exact-match accuracy, and a learned eviction policy beats LRU by 3.64% hit rate.
- **text2sql-router** *(in progress)*: small LLMs are cheap but often write wrong SQL. Every question goes to the small model first, and a fast check decides whether to trust it or escalate to a big model, aiming for big-model accuracy while only paying for it on the hard questions.
- **NN-Steiner reproduction** *(in progress)*: reproducing an AAAI 2024 paper where a neural network guides rectilinear Steiner tree construction for chip wire routing. Found the fix that makes the authors' model match the paper (2.65% above optimal), and now closing the gap on our own retrained model.
- **LLM agents in production**: agent pipelines processing 20k+ signals a week, every prompt change gated by an eval harness (golden-file regression tests plus an LLM-as-judge at 92% agreement), with 66% lower cost per run from prompt caching and token budgets.
