<!-- =========================
Yunus Emre Vurgun / yunusemrejr
Elegant, “systems-first” README
========================= -->

<div align="center">

### dev ∎ // data flows from circuits ⇌ software , what a combo! // professional problem creator ↭ solver // ▓

**Reach:** <a href="mailto:yunus@yunusemrevurgun.com">yunus@yunusemrevurgun.com</a>

<br/>

<!-- Profile counters / quick signals -->
<img src="https://komarev.com/ghpvc/?username=yunusemrejr" alt="profile views"/>
<img src="https://img.shields.io/github/followers/yunusemrejr?label=followers&style=flat" alt="followers"/>
<img src="https://img.shields.io/github/stars/yunusemrejr?label=stars&style=flat" alt="stars"/>

<br/><br/>

<!-- Primary stats row -->
<img height="165" src="https://github-readme-stats.vercel.app/api?username=yunusemrejr&show_icons=true&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats"/>
<img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=yunusemrejr&hide_border=true" alt="GitHub streak"/>

<br/>

<!-- Languages + activity -->
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yunusemrejr&layout=compact&hide_border=true" alt="Top languages"/>

<br/><br/>

<!-- Optional “flair” that stays clean -->
<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=default" alt="quote"/>

</div>

---

## About (in plain terms)

Hey, I’m **Yunus Emre Vurgun** (call me **Yun**). I’m a developer + IT specialist based in **Istanbul, Türkiye**.

I design systems that keep data running end-to-end, and I architect solutions that turn abstract ideas into real, measurable outcomes. My focus sits where **Computational Intelligence** meets **Operational Technology** — at least that’s what I think I’m doing. :)

---

## How I think (and how I build)

I prioritize **architectural integrity** and **algorithmic theory** over trends.

I do not care about the “code” by itself — I care about what the system **generates** and **proves**:
- what it produces, how, why, when  
- what the constraints are  
- what the metrics say  
- whether it’s **mathematically sane**  
- whether it’s **robust**  
- whether the codebase is a dumpster fire or not

What I “like” in computing: time-resistant fundamentals and their theories, the genius math it is built upon, applying robust approaches to real-world cases and creating new ones. These are the crazy things in computing that amaze me.

---

## What I’ve built (examples)

I’ve worked on and created complex platforms — examples include an **industrial-grade resource planning system** for clients, a **visualization pipeline** that bridges graph data with interactive analytics, and even a **neural network classification engine** built from the ground up.

I continuously expand my understanding of **IT infrastructure**, **applied mathematics**, and **science** through online resources and academia.

On GitHub, I’ve published **100+ repositories**, including middleware solutions like a **KepServerEX REST API wrapper** and various system automation bundles to assist other engineers.

---

## Selected work

### 🐝 My Code
* 🧪 **[MATSIMU – A fast, accessible molecular dynamics engine in C++17 (materials modeling & simulation toolkit)](https://github.com/yunusemrejr/matsimu)**

- 🤖 [FinetuneYuno - CPU-only 1-8 B parameter offline LLM Finetuning App for standard computers + Web UI & Very easy to use](https://github.com/yunusemrejr/FinetuneYuno)
- 📊 [MrGraphy - The Graph Database Visualizer & Manager](https://github.com/yunusemrejr/MrGraphy/)
- 🛡️ [MemGuard - Small C Library for Enhanced Memory Management / Limiting & Tracking `malloc()` `free()`](https://github.com/yunusemrejr/memguard)
- 🤖 [Neural Network for Text Classification from Scatch in C++ Using only basic standard libs](https://github.com/yunusemrejr/cpp-neural-net-from-scratch/tree/main)
  - 🏭 [MacOS OT Data-stream Bundle](https://github.com/yunusemrejr/MacOS-OT-Data-Stream-Bundle)
- 🏭 [KepServerEX Full Web Client](https://github.com/yunusemrejr/KepServerEX-Full-Web-API-Client)
- 📊 [Anomaly Detection for Floating Point Values using Statistical Methods in C and C++](https://github.com/yunusemrejr/anomaly_detection_c_and_cpp)
- 🐉 [Email Dragon - Python Desktop App for Auto-inserting Email Details for a List of Recipients](https://github.com/yunusemrejr/emaildragon-py)

**[🔗 See My Other Code...](https://github.com/yunusemrejr/yunusemrejr/blob/main/MORE.md)**

---

## 🌎 Links

- Personal website: **https://www.yunusemrevurgun.com/**
- Favorite project: **https://itsfully.online**

---

## ✍️ Weird stuff I am trying to make sense of

[Assembly](https://github.com/yunusemrejr/Assembly),
[Physical Circuits](https://github.com/yunusemrejr/PhysicalCircuits),
[Digital Circuits](https://github.com/yunusemrejr/CircuitsWithDigitalWorks)

---

## A tiny mystery (Fortran)

Here is a crazy obfuscated Fortran code and I won't tell you what is does and I already forgot what it does:

```fortran
MODULE X1M0D IMPLICIT NONE CONTAINS SUBROUTINE S1(A, B, C) IMPLICIT NONE REAL, INTENT(IN) :: A(:,:), B(:) REAL, INTENT(OUT) :: C(SIZE(B)) INTEGER :: I1 C = 0.0 DO I1 = 1, SIZE(B) C(I1) = SUM(A(I1, :) * B(:)) END DO END SUBROUTINE S1 END MODULE X1M0D PROGRAM Z4 USE X1M0D IMPLICIT NONE REAL, DIMENSION(3,3) :: Q REAL, DIMENSION(3) :: P, W REAL :: E, F INTEGER :: J Q = RESHAPE([0.0, 0.5, 0.5,  & 0.33, 0.0, 0.67, & 0.33, 0.33, 0.34], SHAPE=[3, 3]) P = [1.0, 1.0, 1.0] E = 1.0E-5 DO CALL S1(Q, P, W) W = W / 3.0 F = SUM(ABS(W - P)) P = W IF (F <= E) EXIT END DO PRINT *, "Z:" PRINT *, P END PROGRAM Z4
