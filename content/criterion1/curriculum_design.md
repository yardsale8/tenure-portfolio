---
title: Curriculum Design
linktitle: Curriculum Design
toc: true
type: docs
date: "2021-01-15"
draft: false
menu:
  crit1:
    parent: Teaching Effectiveness
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

Upon joining Winona State, I was very excited to learn about and contribute
to the curriculum of the data science program. Over the last four years, I
have had a substantial impact on this curriculum.

In her [letter of support](/testimonial/hooks_letter_of_support.pdf),
Dr. Hooks stressed these contributions.

> Our data science program has significantly improved since Todd joined our
> faculty. He created two new courses on his own to fill gaping holes in the
> curriculum, which is a daunting and time-demanding task. Furthermore, he also
> worked with other faculty members to improve existing data science courses.
> His expertise is valued by us all, and we often seek out his advice. Todd is
> always willing to offer ideas and opinions to his colleagues - even for
> courses he is not currently teaching - no matter how busy he is with his own
> teaching assignment. He is committed to making our courses better, regardless
> of whether he is the one teaching them or not, and his efforts have had a
> positive impact. 
> 
> In my opinion, the contributions he has made to our data
> science program alone along with the work he’s done to share his ideas with
> the larger data science/statistics community are enough to warrant tenure and
> promotion, but Todd has gone above and beyond to also improve our statistics program. 

As alluded to in Dr. Hook's comments, I have also made contributions to the
statistics curriculum, evidenced by the learning applications discussed in
one of the sections for [criterion 2]({{<ref "/criterion2/software.md">}}),
the STAT 310 project discussed in the section on [instructional
innovation]({{<ref "/criterion1/instructional_innovation.md">}}), as well as my work
aligning the curriculum of STAT 110 and STAT 210 discussed below.

In informal conversations, Dr. Chris Malone has indicated that he hoped I
would improve the data science curriculum in general and programming skills
of our students in particular. By the end of this section, you will have seen
evidence of my contributions in both of these areas; as well as examples of
contributions to the statistics program.

## Curriculum Development for Data Science

First, I will discuss my primary contributions to the data science
curriculum, which comes in the form of two new courses and a revamped
curriculum for the introductory data science course. Finally discussing my
efforts to improve the programming skills of our students throughout these three
courses.

### DSCI 330 – The Management of Unstructured Data

{{< figure src="/img/330_project.png" title="**Figure 1.** Benjamin and Tyler teach the class about background subtraction using Python and the OpenCV library.  The final project in DSCI 330 requires groups of students to explore and present on a new topic in image and video processing.">}}

**Course Description.** This course will give students an overview of the
issues related to the management of unstructured data, that is any data that
is not stored in a table or database. Sources of unstructured data include
bodies of text, social media applications, images, and audio. In the process
of exploring various forms of unstructured data, students will be exposed to
new programming languages and tools that are useful for managing this type of
data (e.g. Python and bash). Other topics covered in the course include web
scraping, natural language processing, and manipulating images/videos/audio
files.

**Rationale.** This course fills a void in the previous curriculum.
It's estimated that between 50% and 80% of all new data is unstructured (see
[Unstructured Data and the 80%
Rule](http://breakthroughanalysis.com/2008/08/01/unstructured-data-and-the-80-percent-rule/)).
Current and future data scientists will rely on the skills needed to gain
insight from these data sources. Before adding these courses, the program had
several offerings that provided students with experience working with
structured data, but there was little exposure to unstructured data.

This course was designed to expose students to the methods and techniques
necessary to work with unstructured data. Upon completion of this course,
students learn to process various types of unstructured data: text, data from
the web, audio, images, and video.

My colleague Dr. Silas Bergen sat in on DSCI 330 this fall and had
the following comments in his [letter of
support](/testimonial/bergen_letter_of_support.pdf).

> Dr. Iverson has also developed two entirely new, upper-level courses to our
> curriculum (DSCI 330: Management of Unstructured Data and DSCI 430: Data at
> Scale). I was able to sit in on DSCI 330 last semester and learned a lot
> about the challenges students will face with messy data in the workplace and
> the Python coding tools they can use to tackle those challenges. These are
> both very strong courses and stellar additions to our Data Science
> curriculum. Suffice to say, Dr. Iverson has been a boon for our Data Science
> program.

All course material is available on [the DSCI 330 GitHub
organization](https://github.com/wsu-DSCI330).

### DSCI 430 – Data Science at Scale

{{< figure src="/img/lew_presents.png" title="**Figure 1.** Daniel demonstrates a dashboard created as part of his capstone project illustrating what he learned in about processing data in Python and PySpark in DSCI 430.">}}

**Course Description.** The focus of this course is on exposing students to
processing data on a large scale using a distributed platform. First,
students will learn the functional approach to processing large data sets.
Along the way, we will encounter many of the techniques that are employed in
large distributed data-processing systems, such as using common higher-order
functions, employing lazy evaluation, and relying on immutable data
structures. By the end of the course students will be familiar with
processing large amounts of data in one or more high-level languages (e.g.
Python and/or Scala) and working with several frameworks for distributed
computation (e.g. Hadoop/MapReduce/Spark).

**Rationale.** This course filled a second void in the previous DSCI curriculum,
which lacked coverage of working with data on a large scale--that is data
that is too large to process on a single machine. This is a deficiency
in most data science programs, which became apparent when judging data
analytics competitions such as MUDAC and MinneMUDAC. I aimed to correct
this problem with this course.

Students in this course work with data at three different scales. First, they
process data on a relatively small data (i.e. fits in RAM) using the standard
Python tools of Pandas and the dfply libraries. Next, students work with data
that is too large to hold in RAM using SQL. Finally, students work with
PySpark, which can process massive amounts of data--data so large it must be
distributed across many machines.

In the process of working with these three different platforms, we reinforce
an idea introduced in DSCI 210--that data management involves translating the
same general processes to different platforms. While I am in the processes of
updating the material for this semesters class, the materials from the last
iteration of the course is available on the [DSCI 430 GitHub
page](https://github.com/yardsale8/DSCI430).

### Teaching Students to Write Better Code

Strong programming skills are a requirement for data scientists and a
secondary aim of these courses improving programming skills. Trends in data
science tend to move quickly. I believe that future data scientists should
be exposed to several programming languages and develop the ability to learn
new languages or platforms. Furthermore, developing the ability to write
clean, correct, and well-documented code will make students more efficient
and valuable members of a team.

Consequently, I have supplemented the course material in DSCI 330 and DSCI
430 with lectures on writing better code. Topics include selecting good
names, writing unit tests, proper documentation, and refactoring code.
Students are introduced to state-of-the-art technologies such as git, GitHub,
Jupyter notebooks, and Docker. I am pleased to say that I have had multiple
students thank me for improving their programming skills. For example,
here is an email from Shane Will, who graduated with a double major in
computer science and data science, sent shortly after taking my course.

> Good Evening Dr. Iverson,

> I just wanted to thank you for pushing me in the Python course this past
> spring. I have realized that my programming skills have really improved after
> being pushed to write in a functional style. I know that if it was not for
> that class and your pushing me I would not have improved my development
> style. Thanks again and I hope that your summer has been going well

> Shane Will

In her [letter of support](/testimonial/quam_letter_of_support.pdf), Mariah
Quam had this to say about the experience of taking three of my programming
course.

> There are specifically three coding classes I took with Professor Iverson
> that allowed me to accrue exponential growth in my coding ability. Through
> these classes, he showed his ability to make what should have been boring and
> tough lecture topics into engaging and thought provoking class periods by
> using his great sense of humor and interactive approaches. On top of being a
> great professor in the classroom, he shined through his office hours just as
> much as he did in the classroom. I commend him for the amount of patience I
> have witnessed him to have first hand with me and also with other students.
> One thing I love about Professor Iverson is he truly cares about his
> students' learning. He is not one to just give a student the answer to get
> them out of his face or to leave them high and dry with no help. He is the
> definition of going the extra mile when it comes to teaching students the
> process of coding.

I presented some of these ideas at SDSS 2019, which is discussed
[elsewhere]({{<ref "criterion2/presentations.md">}}).

### Implementation of a Project-Based and Concept-Driven Curriculum for DSCI 210

Developing the two new DSCI courses and advising and judging with students in
data analytics competitions had the added benefit of clarifying what data
science is all about. These experiences have allowed me to formalize a set of
beliefs on data science curriculum and pedagogy. A summary of these beliefs follows.

**Software-agnostic data management.** Many books and courses on data science
focus on teaching specific technologies or platforms. Instead, we should
provide students with a general abstract vocabulary for solving data
management and visualization tasks. This language can subsequently translated to
several specific technologies throughout the curriculum. DSCI 210 now incorporates this approach by teaching
data management verbs, then translating these verbs to JMP, OpenRefine, and
R.

**Honoring the 80%.** It has been noted that a data scientist will
spend 80% of their time managing data, with the other 20% devoted to
analyzing the data. While many courses devote much of their time to teaching
the tools for the final analyses, I believe that data curriculum should
*honor the 80%*, that is, provide substantial and focused training that
prepares students for 80% of their work life. While DSCI 210 still provides
an introduction to data visualization and statistical learning, much of
the curriculum is now devoted to data management.

**Project-based learning.** Finally, I believe student learning is
reinforced by tackling complicated problems. To facilitate this form of
learning, DSCI 210 now includes multiple projects that allow students to
apply what they have learned to real-world scenarios, as well as practice
presenting their findings.

After polishing this new curriculum over two semesters, I handed the course
off to my colleague Dr. Silas Bergen, who had this to say about the results.

> I will specifically speak to my own personal experience teaching DSCI 210,
> our introductory Data Science course, for the first time in Fall 2019. When
> we first offered this course prior to Dr. Iverson’s arrival at Winona State,
> we were very much “feeling around in the dark” with the course. Data Science
> was a very new field in general, and there was little in the way of
> established curriculum upon which to base the course. However, by the time I
> taught the course, after Dr. Iverson had taught it several times, it had
> developed into a very impressive course. Its conceptual flow was strong and
> the assignments were high-quality, effectively reinforcing class concepts.
> Dr. Iverson had discovered an important data cleaning tool, OpenRefine, and
> introduced it to the course. Students glommed onto this tool and used it in
> subsequent data analytics competitions. OpenRefine is now a mainstay of the
> course. But Dr. Iverson’s most important contributions to this course, and to
> the Data Science curriculum as a whole, is a “software agnostic” philosophy.
> “Data Science” is not the learning of tools, or a pedagogy centered around
> e.g. “learning how to code in Python” (though these tools are definitely
> important). Rather Dr. Iverson has helped us as a department realize that
> Data Science has theoretical and conceptual foundations that transcend any
> one tool, and advocated for a curricular approach that exposes students to a
> variety of tools with the idea that they should use the right tool for the
> job. This has greatly strengthened our program and this philosophy touches
> all aspects of our curriculum, from management of structured data to data
> visualization.

Last semester, I had the opportunity to teach DSCI 210 again. This time I was
able to take advantage of the excellent additions added by Dr. Bergen and
I have found that DSCI 210 is in an excellent place, as evidenced by the following
student evaluation comments.

* *"I really enjoyed this class and ending up adding Data Science to be my second major. I thought you did a wonderful job teaching and I feel like I learned so many useful tools to apply to my other studies in this class. Thank you so much!"*
* *"This course made me consider getting a major in DSCI. I HIGHLY HIGHLY recommend this course to other students."*


## Curriculum Development for Statistics

Finally, I would like to highlight some of the curricula I developed for the
statistics program. In addition to the project developed for STAT 310 in the
section on [instructional innovation]({{<ref
"/criterion1/instructional_innovation.md">}}), I also spent some time
aligning the curriculum between my STAT 110 and STAT 210 courses in an
attempt to understand issues with substituting one course for another.

### Creating a Bridge Between STAT 110 and STAT 210 Curriculum

I am always looking to improve efficiency when implementing my classes. One
semester, I had two sections of STAT 210 on the same day as a single STAT 110
section. I wanted to streamline the delivery of both courses. 

Before the semester, I mapped out the semester for both courses, lining up
the material on as many days as possible. I determined that these courses
shared about 80% of the same content. I adjusted the sequencing of topics to
keep the courses on the same schedule. I implemented the added material
in STAT 210 using out-of-class activities that incorporated online videos
and additional practice activities.

I constructed written assessments in the same vein. Each written
assignment shared 4 questions, while the STAT 210 assignments had a
5th question that covered the additional material not covered in STAT
110. Both courses used the same set of practice and regular quizzes.

This approach was a success in two ways. First, I (almost) made it through
that semester with my sanity intact. There is another advantage to going
through the process of aligning these courses. Students that change to a
major that requires STAT 210 have a problem if they have previously completed
STAT 110: You cannot count both toward graduation.

In the past, the statistic faculty had a process for converting a STAT 110 to
STAT 210 (a test), but that mechanism is lost to time. After aligning these
two courses, I piloted using the supplementary material developed for STAT
210 as a mechanism for satisfying a STAT 210 requirement, where students
complete the additional activities and assessments designed for STAT 210 and
can receive a course substitution upon completion. 

## Summary

In this section, you have seen evidence of substantial and meaningful
contributions to the curriculum of both the data science and statistics
programs, as well as evidence of efforts to improve the coding skills of
students.
