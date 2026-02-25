<!-- ========================================= -->
<!-- Yunus Emre Vurgun — Systems Architect     -->
<!-- ========================================= -->

<div align="center">

# Yunus Emre Vurgun

computational intelligence ∎ operational technology ∎ systems architecture

I design systems that generate measurable, durable outcomes.

📬 yunus@yunusemrevurgun.com

<br/>

<!-- Executive Summary -->
<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=yunusemrejr&theme=github_dark" />

<br/>

<!-- Achievements -->
<img src="https://github-profile-trophy.vercel.app/?username=yunusemrejr&theme=darkhub&no-frame=true&row=1&column=6" />

<br/><br/>

<!-- Core Metrics -->
<img height="170" src="https://github-readme-stats.vercel.app/api?username=yunusemrejr&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=transparent" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=yunusemrejr&layout=compact&hide_border=true&theme=transparent" />

<br/>

<img src="https://komarev.com/ghpvc/?username=yunusemrejr&style=flat-square" />

</div>

---

## Philosophy

I prioritize architectural integrity and algorithmic theory over trends.

I do not care about code in isolation.

I care about:

- System behavior  
- Measurable output  
- Mathematical coherence  
- Structural robustness  
- Long-term survivability  

If the architecture survives time, the implementation follows.

---

## Selected Systems

### Core Engines

**MATSIMU**  
Molecular dynamics engine in C++17  
https://github.com/yunusemrejr/matsimu

**FinetuneYuno**  
CPU-only offline LLM finetuning application  
https://github.com/yunusemrejr/FinetuneYuno

**Neural Network (from scratch)**  
C++ implementation using standard libraries only  
https://github.com/yunusemrejr/cpp-neural-net-from-scratch

---

### Infrastructure & Tooling

**MrGraphy** – Graph database visualizer  
https://github.com/yunusemrejr/MrGraphy

**MemGuard** – Memory tracking & control library (C)  
https://github.com/yunusemrejr/memguard

**KepServerEX Full Web Client**  
https://github.com/yunusemrejr/KepServerEX-Full-Web-API-Client

**Statistical Anomaly Detection (C/C++)**  
https://github.com/yunusemrejr/anomaly_detection_c_and_cpp

---

### Experimental Curiosity

Assembly  
https://github.com/yunusemrejr/Assembly

Physical Circuits  
https://github.com/yunusemrejr/PhysicalCircuits

Digital Circuits  
https://github.com/yunusemrejr/CircuitsWithDigitalWorks

---

## External

Website  
https://www.yunusemrevurgun.com

itsfully.online  
https://itsfully.online

---

## A Tiny Mystery (Fortran)

```fortran
MODULE X1M0D IMPLICIT NONE CONTAINS SUBROUTINE S1(A, B, C) IMPLICIT NONE REAL, INTENT(IN) :: A(:,:), B(:) REAL, INTENT(OUT) :: C(SIZE(B)) INTEGER :: I1 C = 0.0 DO I1 = 1, SIZE(B) C(I1) = SUM(A(I1, :) * B(:)) END DO END SUBROUTINE S1 END MODULE X1M0D PROGRAM Z4 USE X1M0D IMPLICIT NONE REAL, DIMENSION(3,3) :: Q REAL, DIMENSION(3) :: P, W REAL :: E, F INTEGER :: J Q = RESHAPE([0.0, 0.5, 0.5,  & 0.33, 0.0, 0.67, & 0.33, 0.33, 0.34], SHAPE=[3, 3]) P = [1.0, 1.0, 1.0] E = 1.0E-5 DO CALL S1(Q, P, W) W = W / 3.0 F = SUM(ABS(W - P)) P = W IF (F <= E) EXIT END DO PRINT *, "Z:" PRINT *, P END PROGRAM Z4
