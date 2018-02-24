# CS492 Probabilistic Programming, Spring 2018, KAIST 

This is a webpage of the course "CS492 Probabilistic Programming", which is offered at the KAIST CS department in the spring of 2018. The webpage will contain links to lecture slides and other course-related materials.

Probabilistic programming refers to the idea of developing a programming language for writing and reasoning about probabilistic models from machine learning and statistics. Such a language comes with the implementation of several generic inference algorithms that answer various queries about the models written in the language, such as posterior inference and marginalisation. By providing these algorithms, a probabilistic programming language enables data scientists to focus on designing good models based on their domain knowledge, instead of building effective inference engines for their models, a task that typically requires expertise in machine learning, statistics and systems. Even experts in machine learning and statistics may get benefitted from such a probabilistic programming system because using the system they can easily explore highly advanced models.

This course has two goals. The first is to help students to be a good user of an expressive probabilistic programming language.  Throughout the course, we will use a particular language, called [Anglican](http://www.robots.ox.ac.uk/~fwood/anglican/), but we will emphasise general principles that apply to a wide range of existing probabilistic programming systems. The second goal is to expose the students to recent exciting results in probabilistic programming, which come from machine learning, statistics, programming languages, and probability theory.  

## 1. Important Announcements

## 2. Logistics

#### Evaluation

* Final exam (40%). Project (40%). Homework (20%).

#### Teaching Staffs

* Lecturer: [Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok.yang@kaist.ac.kr, office hour: 6:00pm - 7:00pm on Tuesday at the room 3403 in the E3-1 building)
* TA: Kwonsoo Chae (email: kwonsoo.chae@gmail.com)

#### Place and Time

* Place: room 111 in the N1 building
* Time: 10:30am - 11:45am on Tuesday and Thursday from February 27 2018 until June 14 2018.
* Final Exam: 9:00am - 11:00am on June 14 2018 (Thursday) at the room 111 in the N1 building.


#### Online Discussion

* We will use KLMS. 

## 3. Tentative Plan

* 02/26 (Tue) - Introduction. 
* __**03/01 (Thu) - NO LECTURE.**__
* 03/06 (Tue) - Basics of Clojure and Tiny Bit of Anglican.
* 03/08 (Thu) - Posterior Inference, Basics of Anglican, and Importance Sampling. 
* 03/13 (Tue) - Posterior Inference, Basics of Anglican, and Importance Sampling. 
* 03/15 (Thu) - Generative Modelling with Anglican. 
* 03/20 (Tue) - Generative Modelling with Anglican. 
* 03/22 (Thu) - Generative Modelling with Anglican. 
* 03/27 (Tue) - Markov Chain Monte Carlo. 
* 03/29 (Thu) - Markov Chain Monte Carlo. 
* 04/03 (Tue) - Markov Chain Monte Carlo. 
* 04/05 (Thu) - Implementing Inference Algorithms for Probabilistic Programs. 
* 04/10 (Tue) - Implementing Inference Algorithms for Probabilistic Programs. 
* 04/12 (Thu) - Implementing Inference Algorithms for Probabilistic Programs. 
* __**04/17 (Tue), 04/19 (Thu) - NO LECTURES.**__
* 04/24 (Tue) - Denotational Semantics of Probabilistic Programs. 
* 04/26 (Thu) - Denotational Semantics of Probabilistic Programs. 
* 05/01 (Tue) - Denotational Semantics of Probabilistic Programs. 
* 05/03 (Thu) - Denotational Semantics of Probabilistic Programs. 
* 05/08 (Tue) - Amortised Inference. 
* 05/10 (Thu) - Amortised Inference. 
* 05/15 (Tue) - TBD
* 05/17 (Thu) - TBD
* __**05/22 (Tue) - NO LECTURE.**__
* 05/24 (Thu) - TBD
* 05/29 (Tue) - TBD
* 05/31 (Thu) - TBD
* 06/05 (Tue) - Student Presentation
* 06/07 (Thu) - Student Presentation
* __**06/12 (Tue), 06/14 (Thu) - NO LECTURES.**__

## 4. Studying Materials

1. [Anglican website](http://www.robots.ox.ac.uk/~fwood/anglican/). In particular, students will learn a lot by trying examples in the site.
2. Goodman and Stuhlmuller's book "[The Design and Implementation of Probabilistic Programming Languages](http://dippl.org/)" This web-based book describes the implementation of WebPPL, a probabilistic programming language on top of JavaScript. Many techniques in the book are general and apply to other probabilistic programming languages.
3. [Forestdb.org](http://forestdb.org/) is a great source of interesting probabilistic programs. 
4. The online book "[Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)" describes Bayesian Machine Learning using a probabilistic programming system called PyMC.  Hongseok found this book easy to follow and good at explaining basics and intuitions. A more standard reference on machine learning is Bishop's book "Pattern Recognition and Machine Learning".
