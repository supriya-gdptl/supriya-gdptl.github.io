---
title: "Projects"
permalink: /projects/
author_profile: true
---


-   ### The 2nd YouTube-8M Video Understanding Challenge:
    -  Designing a machine learning model with size constrained of 1GB to predict video labels. Experimented with three different architectures. 
    -  Our team could achieve the **Global Average Precision (GAP) score of 0.82853** with final **rank of 186** among the participated 394 teams across the different countries.
    -  \[code\], \[ [Kaggle Challenge Link](https://www.kaggle.com/c/youtube8m-2018)\]

-   ### Using Generative Adversarial Network (GAN) for Image Completion:
    -  Goal is to use GANs for completion of face images, important in many applications such as surveillance.
    -  Implemented in TensorFlow. Completed as a course project for Deep Learning for Vision course. 
    -  Mentor: [Dr. Vineeth N Balasubramanian](https://www.iith.ac.in/~vineethnb/)
    -  [Project Report](https://drive.google.com/file/d/1W7NhIt8XP5HToKYoKbhTCMHokylXQDYx/view?usp=sharing)

-  ### Inverse Search:
   -  The goal is, given a set of documents, find the most probable query that might have generated these documents. Used ensemble of 3 algorithms:TF-IDF based, LDA based and TextRank.
   -  Implemented using Python NLTK, Java MALLET. Completed as a course project for Information Retrieval course.
   -  Mentor: [Dr. Maunendra Desarkar](http://www.iith.ac.in/~maunendra/)

-  ### Time-table Generation Using Genetic Algorithm:
   -  Every semester the university needs to generate the class time-table that satisfies certain hard-constraint and soft-constraints. **Generating optimal time-table** manually is laborious and challenging task. Hence, we designed an algorithm that makes this process automatic. 
   -  We considered six factors: department, class, course, weekday, time and room. We constructed a string of integer numbers indicating factors that are allocated. This **string indicates the chromosome**. Based on whether this allocation satisfies constraints the fitness score for this chromosome is calculated. We then use **two-point crossover and mutation** to find optimal chromosome (i.e. time-table).
   -  This project was part of my **B.Tech Thesis** and completed during final year of B.Tech at [VIT](http://www.vit.edu/index.php)

- ### Exam-scheduling Using Graph Coloring Algorithm:
   -  In university, the courses are offered to students from different departments. Hence, while scheduling an exam for such courses, examination authorities need to take care that exam time-slot should not clash with other courses for which students have already registered.
   -  To solve this problem, we constructed a **graph with courses as nodes** and edge indicates that there exist at least one student who has registered for both courses (represented by two end nodes of an edge).
   -  This formulation has **simplified the problem of exam scheduling to graph coloring**, where color of the node represents the time-slot of alloted for the course. As per the graph coloring algorithm, we need to assign colors to nodes such a way that no two adjacent nodes can have same colors.
   -  This project was completed during my **third year of B.Tech**
   
