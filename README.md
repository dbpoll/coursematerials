# Teaching and Course Materials

This repository provides a sample of teaching and student supervision materials used during my time as a postdoctoral fellow and assistant professor. The examples are a mixture of applied mathematics projects that I have assigned, projection submission from students, and code I have used for demonstrations. 

<br/><br/>
## Quick Links

### College of Charleston

- [Numerical Analysis](#numerical-analysis)
- [Linear Algebra](#linear-algebra)
- [Mathematical Modeling](#mathematical-modeling)
- [Introductory and Multivariable Calculus](#introductory-and-multivariate-calculus)

### Northwestern University

- [Computational Neuroscience](#computational-neuroscience)
- [Differential Equations](#differential-equations)

### Previous and Potential Student Projects

- [Localized Plasticity Model](#localized-enhancement-of-synaptic-plasticity)
- [Root Turnover Model](#estimation-of-root-turnover)
- [Ballistic Search Strategies](#competitive-and-cooperative-ballistic-search)




<br/><br/>
## College of Charleston

### Numerical Analysis

This course sequence was cross-listed as a senior undergraduate course and a graduate-level course. The students were primarily graduate students. A sample syllabus from the first semester can be found [here](numeric_syllabus.pdf). Samples of notes, which were written in Jupyter notebooks, can be seen [here](numeric_lec7.ipynb) and [here](numeric_lec15.ipynb). Finally, students were required to complete a project as part of their assessment. Using techniques from class, students were requested to find and reproduce results in a peer-reviewed paper. A sample of one student's submission can be found [here](numeric_projectsample.pdf).

<br/>

### Linear Algebra

Another course I have taught while at the College of Charleston is Linear Algebra. This is a sophomore-level course that was taken by students planning to major in most STEM fields with some small exceptions. Students in my course primarily consisted of engineering, physics, data science, and mathematics students. As a result, the course focused on theory and techniques, but I included an optional coding component. The course followed a standard lecture and exam format with the additional of worksheet and project components. During lecture, I wrote snippets of code in MATLAB to demonstrate examples given in-class. An early lecture slide is viewable [here](linear_algebra_lecture02-gauss.pdf). 

The worksheets were assigned every few weeks. The worksheets were typically applications of lecture topics or additional topics students may not commonly see. For example, the first worksheet [here](linear_algebra_worksheet1.pdf) focused on applications of linear systems. This included traffic modeling, spline interpolation, and transformation of an exponential function. The last worksheet (viewable [here](linear_algebra_worksheet5.pdf)) provided a simple calculation of eigenvalues and eigenvectors. Then, discussed the derivation of the power method to approximate the largest eigenvalue.

The project (rubric viewable [here](linear_algebra_project_rubric.pdf)) was an assessment given at the end of the semester for students to utilize what they had learned during the course. The students were tasked with finding one (or more) peer-reviewed journals that used methods discussed in-class. The students were then asked to summarize the results and discuss how the methods from class were used to address questions within the paper. For ambitious students, I included a bonus to write their project in LaTeX. 

<br/>

### Mathematical Modeling

Previously, I ran an independent study for a mathematics and biology undergraduate who was interested in applying techniques learned from previous classes to biological models (syllabus [here](math_modeling__syllabus.pdf)). The student and I met approximately once a week to discuss relevant chapters from the assigned reading, discuss questions from previous homework and projects, or to address any coding errors. The course consisted of understanding dynamics and introductory stochastic processes. Homework (example [here](math_modeling_hw1.pdf)) and projects (example [here](math_modeling_project2.pdf)) were written based on the topics covered but framed using biological models from literature. The student has since moved on to a PhD program at UC Davis.


### Introductory and Multivariate Calculus

Although service courses focus on lecture and a set of required topics, I tend to assign additional questions during homework or projects that begin to touch on ways students may use some of the topics they are learning in the class. A sample syllabus that illustrates my course structure for calculus classes can be found [here](multicalc_syllabus.pdf). Two examples of homework assignments with some additional personally written problems can be found [here](multicalc_hw4.pdf) and [here](multicalc_hw9.pdf). A project discussing ways to use optimization can also be found [here](multicalc_project2.pdf).



## Northwestern University

I have unfortunately lost many of my digital materials from teaching at Northwestern. However, I will speak a bit about the topics and, time permitting, reproduce some old work.

### Computational Neuroscience

The course focused on the development of neuroscience models, primarily starting with a first-principles approach of membrane potential and showing that it can be thought of as a circuit. Then, more complicated models, such as Hodgkin-Huxley and the cable equation were introduced and simulated. Towards the end, some additional topics were discussed and explored, such as models of associative memory using Hopfield networks, continuum firing rate models such as bump attractors, and simulating ion channels using Markov chains.


### Differential Equations

The differential equations course at Northwestern was called Engineering Analysis 4 (EA4). It covered most topics seen in a typical standard differential equations class. However, since the course was geared towards engineers, it heavily emphasized numerics as part of the course. A snippet of a couple days of hand-written lecture notes can be found [here](ea4_notes.pdf).


## Previous and Potential Student Projects

### Localized Enhancement of Synaptic Plasticity

As part of my work at Northwestern, an undergraduate student helped develop a model of spatial localized plasticity. Voltage and calcium signals were modeled. Inputs that were localized along the dendritic branch and correlated in time caused the largest changes in synaptic plasticity. One such simulation can be seen as a video below:

https://github.com/user-attachments/assets/f026a3a3-eba4-499c-88e7-b8d07979a71a





  
### Estimation of Root Turnover 

In some recent projects, I worked with a graduate student to develop a model of root turnover based on carbon isotope data taken from the DUKE forest, starting with regression based approaches. We have since continued to develop the model and have discovered that regression alone isn't sufficient to accurately describe the data. In fact, the updated model predicts a biomodal behavior after around one-year, which explains the increased variance seen in the empirical data. This seems to be the critical period when older fine roots exist, but production of new fine roots has also began. Below is a pseudocolor plot for the model, along with other various fitting approaches, and the empirical variance as compared to the updated model, which is separated by root order:

![rootplot](https://github.com/user-attachments/assets/9eedb84e-b499-4812-99cb-4b723d1bdf2d)






### Competitive and Cooperative Ballistic Search

Some previous graduate work focused on a searcher making ballistic, linear trajectories around a domain to search for a target. Some extensions could be developed, such as including multiple searchers who use a competitive or cooperative strategy to find the target(s). A simple visualization of the search simulation is below:

https://github.com/user-attachments/assets/54b81c93-bea1-4d93-a445-d338953f8c89





