---
layout: page
title: Teaching
---

## MSc thesis supervision

I am supervising students who conduct research in *information retrieval*, *natural language processing* and *learning analytics* (basically data science applied to the learning domain). For information retrieval, ongoing benchmark competitions give you a good idea of hot-topic tasks and research directions: 

- [MediaEval 2019](http://www.multimediaeval.org/mediaeval2019/)
- [SemEval 2019](http://alt.qcri.org/semeval2019/)
- [CLEF 2019](http://clef2019.clef-initiative.eu/index.php?page=Pages/labs_info.html)
- [TREC](http://trec.nist.gov/)

Natural language processing has a lot of public benchmarks too, though they are typically not organized within a particular conference/workshop series. The [nlpprogress.com](http://nlpprogress.com/english/question_answering.html) website contains a good overview of tasks/datasets and current state-of-the-art. IR and NLP are not completely separate fields and naturally some of the NLP tasks are more relevant for IR than others. The following tasks are relevant to IR (the links lead to the particular section on the nlpprogress website):

- [question answering](http://nlpprogress.com/english/question_answering.html)
- [multi-task learning](http://nlpprogress.com/english/multi-task_learning.html)
- [named entity recognition](http://nlpprogress.com/english/named_entity_recognition.html)
- [summarization](http://nlpprogress.com/english/summarization.html)

If you are interested in learning analytics, have a look at the proceedings of different editions of the Learning At Scale conference ([2014](http://dl.acm.org/citation.cfm?id=2556325), [2015](http://dl.acm.org/citation.cfm?id=2724660), [2016](https://dl.acm.org/citation.cfm?id=2876034), [2017](https://dl.acm.org/citation.cfm?id=3051457), [2018](https://dl.acm.org/citation.cfm?id=3231644), [2019](https://dl.acm.org/citation.cfm?id=3330430)). I am particularly interested in approaches that require the implementation of tooling that is hypothesized to aid learning (either in a MOOC or in the classroom), which is then deployed in either a crowdsourcing study or an actual class.

## Courses
 
 Below are the resources I have developed for my courses (some are more up-to-date than others): 
 *Big Data Processing*, *Web and Database Technology* and *Information Retrieval*.

### Big Data Processing

Since 2013/2014 I have been teaching the second year Bachelor course *Big Data Processing* at TU Delft (with 2016/17 being the last time for now). The course covers a range of technologies in the Hadoop ecosystem after a short excursion into the streaming world; 
I created the material based on a number of great books, including [Mining of Massive Datasets](http://www.mmds.org/),
[Data-Intensive Text Processing with MapReduce](https://lintool.github.io/MapReduceAlgorithms/), 
[Hadoop: The Definite Guide](http://shop.oreilly.com/product/0636920033448.do), [Programming Pig](http://chimera.labs.oreilly.com/books/1234000001811/index.html)
and [ZooKeeper](http://shop.oreilly.com/product/0636920028901.do). 

#### Slides - 2016/17 Edition
- [Introduction](../documents/bdp/intro.pdf)
- [Streams I](../documents/bdp/streaming1.pdf)
- [Streams II](../documents/bdp/streaming2.pdf)
- [MapReduce](../documents/bdp/mapreduce.pdf)
- [HDFS/GFS](../documents/bdp/gfs.pdf)
- [Scheduling](../documents/bdp/hadoop-ctd.pdf)
- [Algorithm design for MapReduce](../documents/bdp/design_patterns_db.pdf)
- [Pig I](../documents/bdp/pig_intro.pdf)
- [Pig II](../documents/bdp/pig_advanced.pdf)
- [Graph algorithms](../documents/bdp/graph.pdf)
- [Giraph](../documents/bdp/graph_giraph.pdf)
- [ZooKeeper](../documents/bdp/coordination_zookeeper.pdf)
- 2 more lecture on Spark completed this course.

#### Assignments - 2016/17 edition
- [Assignment 1: Streaming](../documents/bdp/assignment1.pdf)
- [Assignment 2: Streaming and Hadoop](../documents/bdp/assignment2.pdf)
- [Assignment 3: Hadoop](../documents/bdp/assignment3.pdf)
- [Assignment 4: Pig](../documents/bdp/assignment4.pdf) [data](../documents/bdp/data-assignment4.zip)
- [Assignment 5: Pig](../documents/bdp/assignment5.pdf) [data](../documents/bdp/data-assignment5.zip)
- [Assignment 6: Giraph](../documents/bdp/assignment6.pdf)
- [Assignment 7: Spark](../documents/bdp/assignment7.pdf)

#### A Sample of Previous Exams
- [Resit 2013/14](../documents/bdp/exam-1.pdf)
- [Final 2014/15](../documents/bdp/exam-2.pdf)
- [Resit 2014/15](../documents/bdp/exam-3.pdf)
- [Final 2015/16](../documents/bdp/exam-4.pdf)
- [Final 2016/17](../documents/bdp/exam-5.pdf)
 
#### Interactive quizzes
- [24 questions on streaming](http://chauff.github.io/documents/bdp-quiz/streaming.html)
- [32 questions on MapReduce/Hadoop](http://chauff.github.io/documents/bdp-quiz/hadoop.html)
- [10 questions on graphs and Giraph](http://chauff.github.io/documents/bdp-quiz/graph.html)
- [12 questions on Pig/Pig Latin](http://chauff.github.io/documents/bdp-quiz/pig.html)


### Web (and Database) Technology
Since 2013/2014 I have also been teaching the first year Bachelor course *Web and Database Technology* (known as TI1506 or CSE1500) at TU Delft, together with
[Alessandro Bozzon](http://alessandrobozzon.com/). I teach the Web technology part, which turned out to be quite a challenge due to
the wide variety of skill sets our incoming students possess (some work as Web developers, others have never written a single line of HTML
before the start of this course). To level the playing field for the more than 300 (or 400, 500, 600,... it is increasing every year) students we have, we rely on the [Learning Web App Development](http://learningwebappdev.com/)
book, which introduces the modern Web stack in an accessible and practical manner. The lectures build on the material introduced
in the book.

#### Web Technology Transcripts, Demo code, etc.

In the 2018/19 edition, we have roughly 900 students taking the course and so I finally bit the bullet and made extensive lecture transcripts and demo code and wrote it up all in a GitHub repository: [https://github.com/chauff/Web-Teaching](https://github.com/chauff/Web-Teaching).

Feel free to use the materials (with acknowledgement)!

#### Web Technology Slides - 2017/18 Edition  
- HTTP: slide decks [1](../documents/webdb-2017-18/web-http.pdf) and [2](../documents/webdb-2017-18/web-http-continued.pdf)
- [HTML and Web app design](../documents/webdb-2017-18/web-html5.pdf)
- [Client-side JavaScript](../documents/webdb-2017-18/web-javascript.pdf)
- [Server-side JavaScript](../documents/webdb-2017-18/web-nodejs.pdf)
- [CSS](../documents/webdb-2017-18/web-css3.pdf)
- [Server-side JavaScript continued](../documents/webdb-2017-18/web-nodejs-continued.pdf)
- [Cookies and sessions](../documents/webdb-2017-18/web-cookies-sessions.pdf)
- [Securing your application](../documents/webdb-2017-18/web-security.pdf)

#### Lab Assignments - 2017/18 Edition
Note: this course has five assignments and at the end the students will have developed a fully functioning Web application (in this year a *habit tracker*) with a database backend. The assignments build on each other and are executed in groups of two students; interviews with TAs lead to a pass or fail of an assignment.
- [Lab 1](../documents/webdb-2017-18/Lab1.pdf) 
- [Lab 2](../documents/webdb-2017-18/Lab2.pdf)
- [Lab 3](../documents/webdb-2017-18/Lab3.pdf)
- [Lab 4](../documents/webdb-2017-18/Lab4.pdf)
- [Lab 5](../documents/webdb-2017-18/Lab5.pdf)


#### A Sample of Previous Exams
Note: the samples below include database questions, which are covered in the other half of the course
- [Midterm 2015/16](../documents/webdb-2017-18/midterm2.pdf)
- [Final 2015/16](../documents/webdb-2017-18/final2.pdf)
- [Midterm 2016/17](../documents/webdb-2017-18/midterm1.pdf)
- [Final 2016/117](../documents/webdb-2017-18/final1.pdf)


### Information Retrieval

#### Slides - 2017/18 Edition
After a few years of not teaching IR, I am back at it. This time, the *Information Retrieval* course covers core IR topics for half of the lectures and NLP topics (taught by Nava Tintarev) for the other half. 

- [IR evaluation](https://docs.google.com/presentation/d/e/2PACX-1vRUZW8Xz2ib8IlJwUIpKucYYFZ5pzUSuoP57UfjwWyQuJil7GDcts50rsOacvV5q3pzhV_HEa69vuSH/pub?start=false&loop=false&delayms=3000)
- [Retrieval models](https://docs.google.com/presentation/d/e/2PACX-1vQFLHSedV4X00-vLhTNbV0aX7zklIM0rosjsYRCyMnurfEOilb4MBVUrTCjpVu0A6yink3czArmBvNp/pub?start=false&loop=false&delayms=3000)
- [Indexing](https://docs.google.com/presentation/d/e/2PACX-1vTeCcr8yrh0Q0zMttx3WtO0zhLcpzQSr2piYUtMYkINVUruMUa-lO2a824Bt_sxxbQTV-Kl1N1TA4TI/pub?start=false&loop=false&delayms=3000)
- [Query refinement](https://docs.google.com/presentation/d/e/2PACX-1vT4OiTBDlFaUEvFwcyZITsiy9oBHr6NHZSbj2xo2Smw_MMR9owKpUjIguHdJBYPXZhI6lLPhNYIsD8R/pub?start=false&loop=false&delayms=3000)
- [Interactive IR](https://docs.google.com/presentation/d/e/2PACX-1vQj-MAdwO6pEyoAB4bMFqdsgldNNDQrqRZaf7tyOPsK62Px8688N_GHMlIc21WLM7W-u1VigSoRbOd8/pub?start=false&loop=false&delayms=3000)
- [Personalization in (Web) search](https://docs.google.com/presentation/d/e/2PACX-1vQ-sXMd4Ggt5YdAGHrZYh52p5ufZsxzqxKhlp_V1l60MUDRS8HfzEr5iAbNTh8ucTIC2x0q1UYeklk2/pub?start=false&loop=false&delayms=3000)
- [Neural models](https://docs.google.com/presentation/d/e/2PACX-1vRwuQ_a3Am7pyJWdqOGiWsCXqbfppRwQo2AM3nByclxanLvLAxe2s9zOWlXJ79zARP1Ke9KIpZefH-c/pub?start=false&loop=false&delayms=3000)
- [Learning to rank](https://docs.google.com/presentation/d/e/2PACX-1vTwo37wjtBJi7MBnEDA6wzgybymAvKagc28OoI94UFuwohAN3WBMmnSxAipoBdap44JhPbyUKiE9Y0L/pub?start=false&loop=false&delayms=3000)

I have also written a blog post about the [IR project setup](http://chauff.github.io/2018-04-24-ir/).


#### Slides - 2011/12 Edition
In 2011/12 I taught my core area of research in a Master course *Information Retrieval* at TU Delft. This course was my first excursion
into the use of Hadoop & Co as part of my teaching, thanks to a grant from Amazon and their (at the time) "AWS Education" scheme - $3500
to allow students to use a real Hadoop cluster for their experiments.  

The course material is quite old by now, but it may still be useful to some. It was also my first venture into the 
teaching of large classes, the structure and design of the course certainly reflects that.

- [Introduction](../documents/ir-2011_12/lecture1.pdf)
- [Big Data](../documents/ir-2011_12/lecture2.pdf)
- [Indexing and Boolean Retrieval](../documents/ir-2011_12/lecture3.pdf)
- [Index and Document Compression](../documents/ir-2011_12/lecture4.pdf)
- [Text Compression and Retrieval Models I](../documents/ir-2011_12/lecture5.pdf)
- [Retrieval Models II](../documents/ir-2011_12/lecture6.pdf)
- [Retrieval Models III and Evaluation](../documents/ir-2011_12/lecture7.pdf)
- [Semantics I](../documents/ir-2011_12/lecture8.pdf)
- [Semantics II](../documents/ir-2011_12/lecture9.pdf)
- [The Web I](../documents/ir-2011_12/lecture10.pdf)
- [The Web II](../documents/ir-2011_12/lecture11.pdf)
- [XML Retrieval and Interactive IR](../documents/ir-2011_12/lecture12.pdf)
