dev ∎ // from circuits ⇌ software // professional problem creator ↭ solver // ▓

__Hi! I'm Yunus Emre Vurgun, a software developer specializing in web and industrial IT systems.__

___With a background in computer science and a passion for hardware and AI, I develop custom applications to enhance industrial processes, including API clients, internal scripting solutions, and web-based license management systems. I'm an active contributor to open-source culture on GitHub and create content on software and hardware topics, which you can find on my website at yunusemrevurgun.com, YouTube, Instagram, and other social media platforms.__*

||My formal education includes a degree in Computer Programming from Beykoz University, and I am currently pursuing IT studies at Illinois Institute of Technology. I also continuously expand my knowledge through various professional courses in software development and AI.||

**Reach me at:** yunus@yunusemrevurgun.com

Fun fact: I play the guitar (`), enjoy working with graphics, and love books. I speak native Turkish and fluent English.

Here is a Fortran code and I won't tell you what is does as I forgot what it does:

     
    MODULE ConfusionMod IMPLICIT NONE CONTAINS SUBROUTINE mv(A_in, X_in, Y_out) IMPLICIT NONE REAL, INTENT(IN) :: A_in(:,:), X_in(:) REAL, INTENT(OUT) :: Y_out(SIZE(X_in)) INTEGER :: LoopVar1 Y_out = 0.0 DO LoopVar1 = 1, SIZE(X_in) Y_out(LoopVar1) = SUM(A_in(LoopVar1, :) * X_in(:)) END DO END SUBROUTINE mv END MODULE ConfusionMod PROGRAM PRCalc USE ConfusionMod IMPLICIT NONE REAL, DIMENSION(3,3) :: M_Matrix REAL, DIMENSION(3) :: Vec_R, Vec_Rnew REAL :: Tol_Err, Sum_Difference INTEGER :: IterIndex M_Matrix = RESHAPE( & [0.0, 0.5, 0.5,  & 0.33, 0.0, 0.67, & 0.33, 0.33, 0.34], SHAPE=[3, 3]) Vec_R = [1.0, 1.0, 1.0] Tol_Err = 1.0E-5 DO CALL mv(M_Matrix, Vec_R, Vec_Rnew) Vec_Rnew = Vec_Rnew / 3.0  ! Normalize step Sum_Difference = SUM(ABS(Vec_Rnew - Vec_R)) Vec_R = Vec_Rnew IF (Sum_Difference <= Tol_Err) EXIT END DO PRINT *, "PageRank Computation Complete:" PRINT *, Vec_R END PROGRAM PRCalc


  
    
 

# 🐝 My Code:
- 🏭 [KepServerEX Full Web Client](https://github.com/yunusemrejr/KepServerEX-Full-Web-API-Client)
- 📆 [Hypothetical Factory Engine Calendar System Web App as an Express.js Server](https://github.com/yunusemrejr/pineapple_jet_engine_test_scheduler)
- 📊 [Anomaly Detection for Floating Point Values using Statistical Methods in C and C++](https://github.com/yunusemrejr/anomaly_detection_c_and_cpp)
- 🐉 [Email Dragon - Python Desktop App for Auto-inserting Email Details for a List of Recipients](https://github.com/yunusemrejr/emaildragon-py)
- 🛡️ [MemGuard - Small C Library for Enhanced Memory Management / Limiting & Tracking `malloc()` `free()`](https://github.com/yunusemrejr/memguard)



[🔗 See My Other Code...](https://github.com/yunusemrejr/yunusemrejr/blob/main/MORE.md)

<br> <br> 
![](https://komarev.com/ghpvc/?username=yunusemrejr)<br>
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yunusemrejr&show_icons=true&theme=default) [![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=yunusemrejr)](https://git.io/streak-stats) 
<br>
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yunusemrejr&layout=compact) 
 ![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=default)
<br> <br> 
 
# 🐬 Socials:

- 🐦 [Twitter @yunusemrevrgn](https://twitter.com/yunusemrevrgn)
- 💼 [LinkedIn](https://www.linkedin.com/in/yunus-emre-vurgun-49ba9a177)
- 📸 [Instagram](https://www.instagram.com/yunus_emrevurgun/)
- 📹 [YouTube](https://www.youtube.com/channel/UC1lBm9ipV1au7VIcbALV2HA)

---------------------

# 🏫 Education

- 🎓 [Illinois Institute of Technology - Information Technology (Bachelor's) - 2023 - ongoing](#)
- 🎓 [Beykoz University - Computer Programming (A.S. Degree 2020-23)](https://beykoz.edu.tr/)
- 📜 [My Certificates](https://github.com/yunusemrejr/Certificates)

---------------------

# 🧑‍💼 Working at

- 🏢 [ASP OTOMASYON A.Ş.](https://opcturkey.com/) | Role: Software Developer & IT Administrator

---------------------


# 🌎 Personal Website

[https://www.yunusemrevurgun.com/](https://www.yunusemrevurgun.com/)

--------------------

# 🌎 Websites

[javandscript.com](#) / ([WebArchive](https://web.archive.org/web/*/https://www.javandscript.com/)) *Offline

[urlatlas.org](#) / ([WebArchive](https://web.archive.org/web/*/https://www.urlatlas.org/)) *Offline

[earthquakehelpers.gor.bio](https://earthquakehelpers.gor.bio/)  *Offline

[https://www.urlatlas.gor.bio](https://www.urlatlas.gor.bio)  *Offline

https://www.gor.bio/ *multiple web projects, *Online

[https://panopticpen.space/](https://panopticpen.space/)  *Online

[https://www.editvirtuoso.com/](https://www.editvirtuoso.com/)  *Online

[https://www.rabbithole42.blog/](https://www.rabbithole42.blog/)  *Online

[quizboys.com](https://www.quizboys.com)  *Online
[tapas.ink](https://tapas.ink)  *Online
[HeadsetHub.org](https://headsethub.org)  *Online


--------------------

# ✍️ Weird stuff I am trying to make sense of

[Assembly](https://github.com/yunusemrejr/Assembly),
[Physical Circuits](https://github.com/yunusemrejr/PhysicalCircuits),
[Digital Circuits](https://github.com/yunusemrejr/CircuitsWithDigitalWorks)

--------------------
<h3 align="left">Support Me:</h3>
<p><a href="https://www.buymeacoffee.com/yunusemrevrgn"> <img align="left" src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="yunusemrevrgn" /></a></p>
 
