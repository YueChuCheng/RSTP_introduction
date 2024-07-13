---
theme: seriph
background: images/bg.png
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
title: Welcome to Slidev
colorSchema: light
---

# Rapid Spanning Tree Protocol
## 鄭仴筑 Yue-Chu Cheng

---

# What is the network topology?
- Element of the network topology
- switch
    - connection between switch 
    - switch need to meet the requirement of reliability, performance, scalability -> so how switch will be implement to meet these requirement

---

# In the current network topology, what kind of issue will loop cuase?
- Broadcast storms
- Multiple Frame Transmission
- MAC Address Table Instability

---

# How To address the loop issue? -> handle loop by detecting and blocking redundant connections

...

actually the above concept is STP, but...


---

# Any other issue?
- Convergence is not fast enough
- 當網路架構需要快速切換的情境下，上面的作法就還有可以改進的地方
- handle loop by **quickly** detecting and blocking redundant connections






