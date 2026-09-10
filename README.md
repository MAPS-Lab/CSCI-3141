# Foundations of Data Science

CSCI 3141 · R and Python · Dalhousie University

Taught by Prof. Gabriel Spadon

Welcome to the public materials for CSCI 3141. This course follows a data science
project from the first question to an analysis that someone else can understand,
check, and reproduce. You will work with data, make decisions about its quality,
explore patterns, build and evaluate models, and communicate what the evidence
supports.

The repository is a place to prepare for class, revisit a difficult example, and
return to methods after the course ends. Independent readers are welcome to use
the released materials too. You can read and download them without a GitHub
account.

This guide describes the whole course, including material awaiting publication.
The [download list](#available-materials) identifies the documents you can open
now. For an enrolled student, the [syllabus](assets/planning/syllabus.pdf) for
your offering is the authority on dates, meeting details, assessment requirements,
and policies. Check that it matches the offering identified by your instructor.

## Find your way

- [Start here](#start-here)
- [Available materials](#available-materials)
- [What you will learn](#what-you-will-learn)
- [The course week by week](#the-course-week-by-week)
- [How to work through a week](#how-to-work-through-a-week)
- [R, Python, and your working environment](#r-python-and-your-working-environment)
- [Labs, assignments, and examinations](#labs-assignments-and-examinations)
- [Your data science portfolio](#your-data-science-portfolio)
- [Collaboration and permitted tools](#collaboration-and-permitted-tools)
- [Readings and further study](#readings-and-further-study)
- [Questions, access, and support](#questions-access-and-support)
- [Sharing and attribution](#sharing-and-attribution)

## Start here

Read the syllabus first, then open the first class's slides and lecture notes
together. The slides give you the main ideas, diagrams, and examples. The notes
develop the reasoning and provide worked steps you can return to at your own
pace.

Choose either R or Python and prepare one local or cloud environment. Try a
small example from the lecture, save your work, and run it again from the
beginning. This gives you an early chance to resolve access or setup problems.

If you are enrolled, check your access to the course Microsoft Teams space and
follow the syllabus instructions for setting up your private assessment
repository. A GitHub account is needed for that portfolio workflow. Bring a
laptop to practical meetings, or contact the instructor early if computer access
is a barrier.

Students from any major are welcome. The syllabus lists no formal prerequisite
course, but expects preparation in calculus, statistics, basic computing, and
programming. You are not expected to arrive knowing every package or model used
later in the course. Guided examples introduce the tools before assessed use.

## Available materials

Released teaching documents are provided as PDFs. GitHub can preview them in
your browser, and you can download copies for annotation or offline reading.

- [Course syllabus](assets/planning/syllabus.pdf)
- Week 1, Class A, *Course Orientation and the Data Science Process*
  - [Lecture slides](week-01/Class%20A/class-01-slides.pdf)
  - [Lecture notes](week-01/Class%20A/class-01-notes.pdf)
- Week 1, Class B, *Data Summarization*
  - [Lecture slides](week-01/Class%20B/class-02-slides.pdf)
  - [Lecture notes](week-01/Class%20B/class-02-notes.pdf)
  - [Laboratory 1](week-01/Assessment/week-01-lab.pdf)

Week 1 Class B, practical activity handouts, and the materials for Weeks 2–12
are not yet published here. They appear in the course plan below so you can see
how the subjects fit together. Download links will be added as documents are
released.

The folders follow the teaching sequence. Within each `week-XX` folder,
`Class A` and `Class B` are the first and second class of that teaching week.
`Assessment` is the location for released lab and assignment handouts.
Course-wide documents are under `assets/planning`. A folder may exist before its
documents are available; an empty folder does not add a preparation or submission
requirement.

## What you will learn

The course starts with a table of observations and the question that brought you
to it. What does a row represent? Which variables were measured, and in what
units? What is missing? Before a model can be useful, you need a defensible
answer to those questions.

From that foundation, you will learn to import, clean, transform, and document
data; choose summaries and graphics that fit the variables; and explain the
patterns you find. Later, predictive methods use observed outcomes to learn how
to estimate an outcome for another case. Descriptive methods examine structure,
similarity, groups, and unusual observations without requiring a target outcome.

By the end of the course, you should be able to carry an analysis through these
decisions and explain why you made them. That includes comparing models using
appropriate evidence, acknowledging uncertainty and limitations, and preparing a
reproducible report in R Markdown or a Python notebook.

These steps are connected. An unexpected plot can reveal a cleaning problem; an
evaluation result can send you back to your choice of variables. The course
returns to the data science process as new methods become available, so the
methods remain connected to the question they are meant to answer.

## The course week by week

The following learning path follows the syllabus. Week numbers refer to teaching
weeks, so consult the syllabus for calendar dates, breaks, releases, and
deadlines. Pace and examples may be adjusted through course announcements.

### Weeks 1–4 · Understand, prepare, and communicate data

1. **Week 1 · Course orientation and summarizing data.** Class A introduces the
   data science process and the course workflow. Class B develops observational
   units, variable types, descriptive summaries, and plots. Lab 01 establishes a
   descriptive baseline and the private submission process. Models shown during
   orientation are previews; this lab does not require model fitting or
   significance tests.
2. **Week 2 · Data preprocessing.** Class A establishes the foundations of data
   preparation. Class B develops cleaning, transformation, and feature
   engineering, including how preparation decisions change the table used for
   analysis. The practical work builds on Week 1's understanding of variables
   and summaries.
3. **Week 3 · Preprocessing and visualization.** The classes connect prepared
   data to visual exploration, then examine visualization in more depth. You
   practise choosing a display for the question and reading what its scales,
   groups, and distributions actually show. Assignment 1 is released in this
   part of the course.
4. **Week 4 · Manipulation and reproducible reporting.** Class A brings together
   data manipulation and visualization in R and Python. Class B develops
   reporting in R Markdown and Python notebooks. The analysis, figures, and
   explanation become a document that can be rerun and checked.

### Weeks 5–8 · Predict outcomes and study model behaviour

5. **Week 5 · Predictive tasks and metrics.** Classification and regression
   introduce two different kinds of prediction problem. The classes examine
   their corresponding performance measures, building the vocabulary needed to
   judge a model's results.
6. **Week 6 · Predictive methods.** The data science process is revisited through
   predictive metrics, followed by k-nearest neighbours, linear regression, and
   linear discriminant analysis. Attention moves from describing a dataset to
   fitting a method and interpreting its predictions.
7. **Week 7 · Midterm and support vector machines.** The first meeting is the
   midterm examination. The second introduces support vector machines and
   continues the predictive modelling sequence. Assignment 2 is released in
   this part of the course.
8. **Week 8 · Decision trees.** The classes introduce decision trees and develop
   tree-based models and pruning. You examine how a tree partitions data and how
   its complexity affects the result.

### Weeks 9–12 · Evaluate evidence and discover structure

9. **Week 9 · Performance estimation.** Both classes focus on how model
   performance is estimated. The central question is how much confidence an
   evaluation gives you about performance beyond the data used to fit a model.
   Assignment 3 brings the predictive workflow together.
10. **Week 10 · Model complexity and descriptive analytics.** Bias, variance,
    overfitting, and regularization lead into descriptive analytics, similarity,
    and distance. The focus broadens from predicting a specified outcome to
    studying the structure within a dataset. Assignment 4 is released here.
11. **Week 11 · Clustering.** Distance and preparation choices lead into
    clustering algorithms and their evaluation. You examine how the definition
    of similarity affects the groups an analysis produces.
12. **Week 12 · Outliers and workflow synthesis.** Outlier detection is followed
    by cumulative review. The final class connects preparation, visualization,
    predictive and descriptive modelling, evaluation, and reporting into the
    complete workflow.

Some lectures include optional research examples or extensions. Their presence
in a slide deck does not make them a prerequisite for that week's assessed work.
Use the lab or assignment handout to identify the methods and evidence required.

## How to work through a week

Before a class, read its opening goals and review the ideas it carries forward
from the preceding meeting. During class, use the slides to follow the sequence
of questions, examples, and diagrams. Mark the points you want to revisit in the
notes rather than trying to transcribe every slide.

Afterwards, work through the corresponding explanation and examples in the
notes. Run the code yourself and compare the result with the stated
interpretation. If the outputs differ, first check the input data, selected rows,
variable types, and preparation steps. Keep a short record of the question you
were trying to answer and the decision each step supports.

Each week's second class begins an integrated lab. Use it to apply the methods
introduced so far, ask questions, and develop your own analysis. The lab handout
sets the approved data, required work, deliverables, and rubric. Keep it beside
the slides and notes while you work.

As reports become more substantial, practise restarting the R session or Python
kernel and running the analysis from beginning to end. A saved output should be
traceable to the code and data in the submitted version. Explain a result in
words as well as displaying it, including its units, relevant sample size, and
any limitation needed to interpret it fairly.

## R, Python, and your working environment

R is the primary teaching language, with full Python parity in materials,
demonstrations, practical work, and assessments. Choose one language for your
work. Both follow the same requirements and grading standards; you do not need
to submit an analysis twice in two languages.

You can use a local R or Python environment, or one of the cloud options listed
in the syllabus.

- [Posit Cloud](https://posit.cloud/) provides browser-based RStudio and Jupyter
  projects for R or Python work.
- [Kaggle Notebooks](https://www.kaggle.com/code) supports R and Python notebooks.
- [Google Colab](https://colab.research.google.com/) provides Python notebooks
  in the browser.

Another suitable free cloud notebook service is also acceptable. No paid
external service or public generative AI service is required. Cloud plans and
resource limits can change; consult the provider's guidance when choosing an
environment. Keep copies of the notebooks and supporting files in your private
assessment repository so the work is preserved beyond a running session.

Use the software and dataset guidance supplied with the relevant class or
activity. Record the data source and the steps needed to run your analysis.
Check a cloud notebook's sharing settings before putting assessed work in it.
Permission to use an editor or notebook service does not authorize its generative
AI features for assessed work; the rules below still apply.

## Labs, assignments, and examinations

The numerical grading structure in the published syllabus is shown below.
The syllabus contains the full assessment and passing requirements, approved
aids, late-work rules, and absence and accommodation procedures. Consult it
alongside the instructions for each assessment.

| Graded component | Course weight |
| --- | ---: |
| Integrated labs | 15% |
| Four individual assignments | 45% |
| Midterm examination | 15% |
| Cumulative final examination | 25% |

The best 10 of 12 individual lab results count toward the lab component.
Labs provide regular practice with the current methods. The four assignments
ask you to assemble a more complete analysis, with increasing responsibility
for preparation, methodological choices, interpretation, and reproducibility.

| Assignment | Primary focus | Course weight |
| --- | --- | ---: |
| 1 | Import and basic exploration | 7.5% |
| 2 | Preprocess and explore data | 7.5% |
| 3 | Predictive modelling solution | 15% |
| 4 | Descriptive modelling solution | 15% |

Use the released handout for the dataset, required files, format, rubric, and
authorized tools. Its required files must open and reproduce the analysis.
Submission dates belong to the syllabus and the instructions for your offering;
this course guide does not set a separate calendar.

The midterm is held in class, and the Registrar schedules the cumulative final
examination. Follow the examination's approved-aids instructions and the
syllabus when preparing for either.

## Your data science portfolio

Your labs and assignments become a portfolio of analyses you can discuss in
class and revisit later. A reader should be able to find the question, identify
the data, follow the analysis, and understand the conclusion without needing
you to explain every file in person.

The syllabus uses these locations in your own assessment repository.

```text
labs/
  lab-01/
  lab-02/
  ...
assignments/
  assignment-01/
  assignment-02/
  ...
```

Follow each handout for the files inside its folder. These directories belong
to your own work repository. Submit through the announced private channel;
course-repository issues and pull requests are not assessment submissions.

### Develop privately

Work in a private GitHub repository with instructor access. Commit regularly as
you work and push those commits to the private repository. Keep code, reports,
figures, outputs, cloud notebooks, and links that reveal answers private before
the deadline and until sharing is opened. A branch in a public repository is
public too.

### Submit a fixed version

By the deadline, submit the full commit SHA and its commit URL through the
announced private channel. The SHA identifies the exact version being assessed.
A branch link or movable tag is insufficient because its destination can change.
Keep the submitted commit reachable.

Preserve recorded assessment history permanently. Do not amend, rebase, squash,
delete, replace, or force-push those commits, move submitted tags, or fabricate
or backdate progress. Make corrections in new commits. If you accidentally
commit private information, contact the instructor for an approved correction.

Git records a version's contents; its author dates do not prove when you
submitted the work, and Git alone does not establish authorship or prevent
history changes. The submission receipt, recorded SHA, and instructor-retained
snapshot provide the independent assessment reference.

### Publish after release

After the submission deadline **and when the instructor opens sharing**, publish
the same submitted commit and its history in your public portfolio. Preserve
its SHA when merging from the private work repository. Present that version in
class, and label any later improvements separately so a reader can distinguish
the submission from subsequent work.

Grades and feedback remain private. Where accommodation, safety, privacy,
copyright, or licensing requires a private portfolio, the syllabus provides an
equivalent private repository option with the same evidence and rubric.

## Collaboration and permitted tools

Discussing concepts is encouraged. Assessed work must demonstrate your own
understanding. Do not share answers, code, analysis files, answer-producing
prompts, or solution steps unless written instructions authorize collaboration.
Keep questions about your own unreleased solution in a private channel.

The syllabus permits generative AI for private study planning and practice,
provided you check outputs against course sources and protect private or
copyrighted information. It also permits editing a student-written ungraded
note when the intellectual work is already the student's.

Generated code, prose, analysis, and figures cannot be submitted for integrated
lab credit. Generative AI is prohibited for assignments unless the instructions
expressly authorize a named use, and it is prohibited in examinations. An
authorized assignment use requires disclosure of the tool, purpose, interaction
summary, and changes made. Silence in the instructions is not permission.
Do not upload non-public course or student material to a generative AI service.

See the syllabus for the complete academic integrity policy and the scope of
any authorized use in an assessment's instructions.

## Readings and further study

There is no required paid textbook. The released slides, lecture notes, and
practical handouts are the starting point for learning the course material.
Use the reading and documentation links supplied with the corresponding class
when you need another explanation or more detail about a method.

Optional further reading is identified in the teaching materials. Those texts
and research examples extend the discussion; they do not create additional
assessment requirements. Start with the class explanation, then pursue the
references that address the question you are working on. Check
[Dalhousie Libraries](https://libraries.dal.ca/) for access before obtaining a
book.

When studying independently, follow the teaching order and run the examples in
your chosen language. For an early analysis, concentrate on the variables,
summaries, plots, and preparation steps introduced so far. Return to that
analysis as modelling and evaluation methods become available to you.

## Questions, access, and support

Use the course Microsoft Teams space for class-wide questions about concepts,
examples, or corrections. Include the document title and page or slide number.
For a code question, explain what you expected, what happened, and the smallest
example that shows the issue, while keeping assessed solutions private.

For individual concerns, contact Prof. Gabriel Spadon at
[spadon@dal.ca](mailto:spadon@dal.ca) from your Dalhousie email. Office hours are
by appointment through Microsoft Teams. Independent readers can also email
questions or corrections.

Contact the instructor early if computer access, a document format, or another
barrier affects participation. The syllabus links the Student Accessibility
Centre and other university support services and explains the processes for
absences and accommodations. Personal circumstances, grades, and feedback
should be discussed privately.

Enrolled students should check the course repository and their Dalhousie email
regularly, and follow the announcement channels identified for their offering.
Meeting locations, office-hour arrangements, and calendar dates should always
be checked against that offering's syllabus and announcements.

## Sharing and attribution

Unless the instructor explicitly marks material private or restricted, released
course materials may be shared with credit to the author and CSCI 3141.
For example, credit a reused course slide to “Gabriel Spadon, CSCI 3141,
Foundations of Data Science, Dalhousie University” and include a link to the
source document.

Preserve source links, third-party attributions, and applicable licence terms
for figures, datasets, code, and quotations. Copyright remains with the
respective owners. Permission to share course materials does not authorize
publishing another student's work, restricted data, grades, feedback, or
instructor-marked private information. Your own assessed work follows the
portfolio release process above.
