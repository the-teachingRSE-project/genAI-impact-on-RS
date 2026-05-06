# The impact on AI from the perspective of the teachingRSE project

Authors: Julian Dehne, Florian Goth, Magnus Hagdorn, Jan Linxweiler, Frank Löffler

## Abstract

The teachingRSE project represents an open group of individuals mostly from Germany that brings together experience of teaching research software engineering at research institutions.
We are a recognised special interest group of de-RSE e.V and of the German Computer Science Association (GI).
In our opinion, generative AI tools will have a substantial impact on the learners, the teachers, and the syllabus.
Research Software Development encompasses a variety of skills and competences that are related to programming such as algorithmic thinking,
and generally designing the software architecture according to the research needs. These can be the experiment or an analysis that is affected by an AI systems.
In the following, we detail our perspectives regarding the short- and mid-term impact of AI in RSE education.

## Looking Five Years Ahead

### New Competences

The trending dichotomy of cancelling programming education altogether versus stating that students need to learn this by hand might be oversimplified.
There is a growing need for a thorough investigation of detailed competences and how they relate to genAI-supported programming, and also mapping these to the specific set needed by research software engineers.
Looking further ahead, we also focus on which skills will be required in the future in order to generate software.
In the past, this skillset started with programming, but also included competences from the domain of software engineering,
such as the specification of requirements, different forms of testing and more.

### Transformative Changes in needed Competences

Some of those skills were important in the past (and still are) because of the limitation of humans writing software.
Programs need to be typed, read, and understood in detail.
Software refactoring was expensive because it involved all of the above.
Not a small part of software engineering tries to minimize those costs, but now AI might be able to do all of these a lot faster and cheaper as well.
But, if programming (on a lower level) and good software engineering (on a higher level) can be done by an AI, those skills do not need to be taught anymore, at least not aside from a small elite group.
However, results still need to be checked.
This involves the ability to specify requirements (to the AI) and how to test the results of the AI, skills that have to be added to the teaching-RSE portfolio.


## Looking Two Years Ahead
We first consider the impact on learning how to program.

### Current Problems in Classrooms

GenAI tools for programming are now widely available and many beginners are using these tools to solve their programming tasks.
Practices range from using GenAI to walk the student through the process to letting the AI solve the entire task by itself.
Especially, the latter does not encourage learning, besides how to use an AI.
Nevertheless, using AI as a coach can help the student explore the problem space, and fill any knowledge gaps they might have.
In any case, there is a risk that the AI user will take the results at face value and becomes reliant on the AI.
Many programming problems suitable for beginners are easily solved by genAI systems because they are well documented.
This reinforces the dangerous habit of trusting the results without checking them. 
As a consequence, teaching will have to put even more emphasis on skills like code comprehension, testing and test driven development.


#### Classroom Solutions for new Student Tasks

So far, teachers have relied on problems to introduce programming to students, mostly on a detailed, algorithmic level.
However, as noted above, these problems are documented and easily solved using genAI.
A possible solution to this problem is to ask students to solve bigger, more complex tasks from the start.
By doing so, we foster the efficient use of genAI - whether this is good or bad is up for debate.
As teachers, we need to rethink how and what we teach, and how we check what the students have learned.
As evidenced by this example, the notion of teaching people “algorithmic thinking”, the ability to analyse a problem
and decompose it into subproblems amenable to execution on a computer, will become far more important than the actual coding of the algorithm via a specific language.
Experience with any specific programming language will become a qualification necessary only for a small and specialised group.
Hence, the focus of teaching should shift from lower-level details to a higher conceptual level, meaning that instead of learning 
how to implement certain algorithms, it will be much more important to learn how to structure applications on a higher (architectural) level.
As a result, AI enables the handling of scientific problems at a higher level of abstraction, allowing even more complex problems to be addressed.
However, in order to be able to effectively communicate with the AI at a higher level, students need to learn the higher-level concepts, such as design and architectural patterns.

Still, to review results generated by an AI, the user needs to understand them, or at least test them sufficiently.
Also, we fear that by bypassing the simpler problems, the students miss the opportunity to gain the required skills and experience.

### Job Market
This shift in the use of entry level problems also manifests itself in the job market, where the tasks for junior people are now squeezed out in favour of AI systems.
This effectively means that these people never have the opportunity to mature into senior roles.
In the long term we expect that with the emergence of this new level of problems that are easy *with the help* of an AI system, also job interviews and beginner tasks will change,
but as of now, there is a great insecurity which skills are relevant.


#### The Importance of Code Review and the FAIR Principles
In order to be able to review results generated by an AI, the user needs to understand them.
The ability to critically review outputs of genAI systems will become far more important.
The speed with which new content can now be generated will pose a problem for the scientific community and the adherence to the FAIR principles.
With genAI systems it becomes very easy for researchers to just produce stuff and forget about its reproducibility afterwards.

#### Social Aspects

Programming as well as learning how to program is a social activity.
When learners interact predominantly with an AI, fellow learners are denied the opportunity to explain a problem which is critical to develop communication skills and enhanced understanding of best practices in coding and software engineering.
It will be interesting to see, if this will continue to be identified as a problem, or if a younger generation, raised on total digital communication sees this as a non-issue.


## Summary
AI will change our tasks and use-cases of RSEs in a fundamental manner.
Since a lot of our daily tasks will be done by AI systems, our works will shift to a more abstract thinking about problems
and the proper orchestration of AI systems. This will be refelected in classroom settings in what and how we teach.
