# Algorithms for speech and natural language processing (MVA 2023)

## NEWS

[//]: # "We are very sorry to announce that **this course will only be available remotely**. This year the only room that we were able to secure for the course (salle Henri Cartan, ENS) turned out to be 3 times too small, and its internet was not reliable enough to sustain a hybride mode. The course will then run through zoom in real time (there won't be video capture). The quizzes and Q&A sessions will also be online and in real time. The time is every Friday afternoons from 4pm to 7pm. "

For Friday 17th of February: M. Benoit Sagot is feeling sick and will not be able to teach Friday class. You will have to watch the class 'MVA SLP 2022 - Course 8 - NLP applications and challenges' that is available on youtube at:

https://www.youtube.com/playlist?list=PLoWKS7d8OzpVQ-HthtgmVPeYU7kx6KeDa (please watch the 5 videos)

Then, you'll have to answer the quizz, so please on Friday 17th connect at 6pm on the zoom: 

https://us02web.zoom.us/j/7760908306?pwd=WnpPL2NqdXIxMzNtSEMxZE5RZVZIZz09

Once everyone is connected, you will have some time to ask questions about the class and then we will let you answer the quizz.

Regarding the deadline for the project one-pager: we let you have one more week to write it and we will collect them on Friday 24th . 

## Course Organizers
Emmanuel Dupoux (EHESS & Meta), Benoît Sagot (INRIA), Robin Algayres (ENS), Neil Zeghidour (Google Brain)

## Contact information
For any question/request related to this course, please send an email to this address: mva.speech.language@gmail.com

# Course materials

## Course Objectives

Speech and natural language processing is a subfield of artificial intelligence used in an increasing number of applications; yet, while some aspects are on par with human performances, others are lagging behind. This course will present the full stack of speech and language technology, from automatic speech recognition to parsing and semantic processing. The course will present, at each level, the key principles, algorithms and mathematical principles behind the state of the art, and confront them with what is know about human speech and language processing. Students will acquire detailed knowledge of the scientific issues and computational techniques in automatic speech and language processing and will have hands on experience in implementing and evaluating the important algorithms.
 
Topics:
- speech features & signal processing
- hidden markov & finite state modeling
- probabilistic parsing
- continuous embeddings
- deep learning for language-related tasks (DNNs, RNNs)
- linguistics and psycholinguistics
- comparing human and machine performance

## Prerequisites
Basic linear algebra, calculus, probability theory

## Organization

### 9 courses 
The courses consist in 9 three-hours blocks, followed by an oral
project presentation on week 10. <del>This year, the course will take place in presence, 
every friday afternoons **from 4pm to 7pm** in salle **Henri Cartan**, [45 rue d'ULM](https://www.google.com/maps/place/45+Rue+d'Ulm,+75005+Paris/@48.8424688,2.3420222,17z/data=!4m5!3m4!1s0x47e671e9e9f3a327:0xb168d68bd2ea2060!8m2!3d48.8423135!4d2.3443182). </del> The course will be held online.

Each three hours block consists in two hours of course, followed by a quizz and Q&A.



### Validation
The validation is in two parts:

- **QUIZZ** (30% of the total grade). You'll be given a link to an on-line questionnaire (google form). You'll be given 30minutes to complete the questionnaire which will be activated exactly at 6:00pm and closed down at a time decided on-the-fly by the professors, generally 6:20pm. Any forms submitted after the deadline will be automatically rejected, and graded as zero. The QUIZZES will contain comprehension questions and the best <del>5</del> 4 grades out of the <del>6</del> 5 quizzes will be used for the average (the first quiz had too many issues and will be ignored). Between 6:30 and 7:00 there will be a Q&A period where you'll be able to ask questions about the course and QUIZZ using an on-line connection.

- **Project.**  (70% of the total grade). You'll work in small groups of 2-4 around a recent paper in speech or language processing which has already some existing code. Your task will be 1. to replicate the main result of the paper 2. run a  experiment testing a new question not tested in the paper. You'll present your plan in a one page document in week #3, and your results in a 4 pages documend and 10 minutes oral presentation + 5 minutes questions in week #10. 

the list of possible projects will be made available  here:
https://docs.google.com/spreadsheets/d/12hI1JfS2S9dKreXwdmdi1DAYx72ANA1KvlWorMMT0zY/edit#gid=0


ATTENTION: since there is no "exam", there is no possibility of "rattrapage" (ie, of compensating a bad mark by taking another exam). So, if the overall grade obtained in this course is less than 10/20, this course will not be considered validated by the MVA Master. 


### Schedule and links

- #1 Jan 27, 2023. Introduction (Sagot & Dupoux)

- #2 Feb 3, 2023. NLP1. NLP basics, Language Models for Text (Sagot, Algayres) [zoom link](https://us02web.zoom.us/j/7760908306?pwd=WnpPL2NqdXIxMzNtSEMxZE5RZVZIZz09) — [quiz link](https://forms.gle/RVqBN5j4ic8He2ns6)

- #3 Feb 10, 2023. NLP2. Representation learning for NLP (Sagot, Algayres) [zoom link](https://us02web.zoom.us/j/7760908306?pwd=WnpPL2NqdXIxMzNtSEMxZE5RZVZIZz09) — [quiz link](https://forms.gle/MqphGpnGMhS48biH9)

- #4 Feb 17, 2023. NLP3. Advanced topics in NLP (Sagot, Algayres). [prerecorded class](https://www.youtube.com/playlist?list=PLoWKS7d8OzpVQ-HthtgmVPeYU7kx6KeDa) — [zoom link (please connect at 6pm after watching the class)](https://us02web.zoom.us/j/7760908306?pwd=WnpPL2NqdXIxMzNtSEMxZE5RZVZIZz09)

[//]: # "— [quiz link (will be made available once everyone is connected on the zoom)]()"



**Attention: deadline for project proposal (one page: FEB 17, 2022; midnight)**
**Submit through email [HERE](mailto:mva.speech.language@gmail.com?subject=[MVA2023-1Page]). One
  email per group, CC all members of the group. You will receive an acknowledgment within 24 h.**


- #5 Feb 24, 2023. NLP4. Machine Translation (Schwenk) Same zoom link as above



- #6 March 3, 2023.  ASR1: Features and Acoustic Models (Zeghidour, Algayres) Same zoom link as above


- #7 March 10, 2023.  ASR2: Language Models for Speech (Dupoux) Same zoom link as above



- #8 March 17, 2023. ASR3: End-to-end models (Zeghidour, Algayres) Same zoom link as above



- #9 March 24, 2023. Hot topics in speech and language (Sagot, Dupoux) Same zoom link as above

    - chatbots
	- textless NLP

- #10 March 27-March 31. Oral defense (remote) 


## details for the QUIZZ

The QUIZZ will be composed of comprehension questions regarding the course you've just watched. You will have 15 minutes to complete the Google form which will be activated after the main part of the course and closed 15 minutes after. We will then briefly discuss the answers.

## details for the PROJECT
You will be given a list of papers to choose from.

Your first task (week #1-#3) is to select a paper of interest, and make up a group of 2-4 people to work on this paper. 

Your second task (week #3) will be to decide on a plan for the experiment you'd like to run and write a 1p document describing what you want to do and who will do what. Attention! any delay in submitting your paper will cost you points (1/24th of a point for each hour of delay after sunday midnight before the monday of week #4).

Your third task will be to conduct the work and prepare (1) a written document (4 p max) describing what you've done and the main results. You may differ from the 1p, but will have to explain how and why. The 4 p should also contain a statement of contribution (who did what), (2) and oral 10 minutes presentation. (there will be 5 minutes of question aferwards).


## Where:

All the courses will be delivered remotely. 

The course materials (PDFs, etc.) are listed in the subdirectories numbered #1 .. #9. 



### Q&A

_What happens if i get less than 10/20 on average? Can I take another exam? _


No, there is no possibility of 'rattrapage'; any obtained grade is final.


_What happens if i cannot be present to the course, and therefore cannot do the on-line QUIZZ?  _


Failure to submit the QUIZZ on time will result in a zero/20 for that QUIZZ, unless you can demonstrate that it was materially impossible for you to be present to the course. Such documented requestes should be sent to mva.speech.language@gmail.com together with the name and date of missed QUIZZ. The best 5 grades out of the 6 quizzes will be used for the average, giving you the possibility of one missing course.

