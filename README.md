## System Overview

The system consists of a teaching platform that maintains information about courses, their classes and students, as well as a forum for questions and answers about course content. System actors can be students and teachers. There are also administrator users, who are the only ones authorized to register courses and classes.</br>
A course is made up of several “resources”, which are groups of content. These resources can be learning paths, bonuses, external links, and the course Q&A forum itself. Each resource can contain sections, and these sections in turn will contain the lessons, which can be video and/or text content, or tasks to be delivered by students.</br>
A task can have a weight, a due date, a number of questions and the minimum amount of correct answers needed to be accepted. When a student deliver a taks to a teacher, it waits for feedback the feedback, and it can be accepted or rejected.</br>
Each new class of the course corresponds to an offer or edition of this course, which has a start and end date. Different offers of the same course may have slight variations in content, depending on the need for customization for each class.</br>
Users (students and teachers) must receive notifications.</br>

As for the Q&A forum, this consists of a collection of threads (with a title and description of the question), and each thread can have multiple replies.

The general forum requirements are:</br>
List topics, with the following filter options:</br>
By resource/section/class</br>
By text (topic title and/or body)</br>
Questions asked only by logged-in user</br>
Create topic: title, body</br>
Reply topic</br>
Mark/unmark upvote on question (cannot be the author) </br>
Mark/unmark upvote on reply (cannot be the author)</br>
Mark/unmark best answer (topic author and instructor only) </br>

## Run requirements:
Maven </br>
Java 17 >

## Instructions:
1° Clone project </br>
2° Open terminal </br>
3° $ cd /backend </br>
4° $ mvn spring-boot:run </br>

Postman Collection: (https://github.com/AndOliver46/dslearn/files/11239641/BDS.3.0.DSLearn.Cap.4.postman_collection.zip)

## Conceptual model of system:

![modelo-conceitual-com-forum](https://user-images.githubusercontent.com/101358552/224450828-cc797150-92a8-4315-9371-492bf712d396.png)
