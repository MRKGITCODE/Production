# Production

## Content
* [Description](#description)
* [Learning Outcomes](#learning-outcomes)
* [Logistics](#logistics)
  + [Module Contacts](#module-contacts)
  + [Delivery of module](#delivery-of-module)
  + [How the Instructor will deliver](#how-the-instructor-will-deliver)
  + [Requirements](#requirements)
  + [Expectations](#expectations)
* [Module Schedule](#module-schedule)
* [Resources](#resources)
  + [Documents](#documents)
  + [Videos](#videos)
  + [How to get help](#how-to-get-help)
* [Folder Structure](#folder-structure)
* [Acknowledgement](#acknowledgement)


## Description

The module was created by the University of Toronto's Data Science Institute. The module provides an overview of the Design of Machine Learning Systems which are embedded within data-intensive products and applications. It covers the fundamental components of the infrastructure, systems, and methods necessary to implement and maintain Machine Learning (ML) models in production. In short, we will learn methods to build a factory of ML models. 

The module has two components: 

+ A discussion of the main issues and challenges faced in production, together with some approaches to address them.
+ A live lab with demonstrations of implementation techniques. 

The module covers the following areas:

+ Data engineering.
+ Feature engineering.
+ Hyperparameter tuning.
+ Model deployment.
+ Model explainability.
+ Logging, experiment tracking, and monitoring.

We will discuss the tools and techniques required to do the above in good order and at scale. However, we will not discuss the inner working of models, advantages, and so on. As well, we will not discuss the theoretical aspects of feature engineering or hyperparameter tuning. We will focus on tools and reproducibility.

## Learning Outcomes

By the end of this module, a student will be able to:

+ Describe the main components of a machine learning system.
+ Explain the infrastructure required to train and test models in production.
+ Implement an experiment tracking system and logging.
+ Contrast and evaluate different approaches of storing and manipulating data.
+ Design data flows and processes to automate the construction of ML models.


## Logistics

### Module Contacts

**Questions can be submitted to the #questions channel on Slack**

* Technical Facilitator: 
  * name and pronouns: `<Name>`, `<Pronouns>` 
  * email: `<first_name.last_name@mail.ca>`
* Learning Support Staff: 
  * name and pronouns: `<Name>`, `<Pronouns>` 
  * email: `<first_name.last_name@mail.ca>`

### Delivery of Module

The module will run sychronously three times a week on Zoom. The first three days are used as "lectures" and will last a maximum of 3 hours. During this time, the instructor will introduce the concepts for the week. The last two days are used for as optional, asychronous work periods. The work periods will also last for up to 3 hours. During these two days, an instructor or TA will be present on Zoom to assist learners reach the intended learning outcomes.

### How the Instructor will deliver
The instructors will introduce the concepts through a collaborative live coding session usiing the Python notebooks found under `/01_slides`. All instructors will also upload any live coding files to this repository for any learners to revisit under `/live_production`.
The instructors will introduce the concepts through a collaborative live coding session usiing the Python notebooks found under `/01_slides`. All instructors will also upload any live coding files to this repository for any learners to revisit under `/live_production`.

### Requirements

* Learners are not expected to have any coding experience, we designed the learning contents for beginners.
* Learners are encouraged to ask questions, and collaborate with others to enhance learning.
* Learners must have a computer and an internet connection to participate in online activities.
* Learners must have VSCode installed with the following extensions: 
    * [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
    * [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
* Learners must install Docker as this module implements a Docker backend that will run a PosgreSQL server. This is intended to mimic a production-like environment. Use SQLite if Docker is not an option.
* Learners must not use generative AI such as ChatGPT to generate code in order to complete assignments. It should be use as a supportive tool to seek out answers to questions you may have.
* We expect learners to have completed the [onboarding repo](https://github.com/UofT-DSI/onboarding/tree/main/onboarding_documents).
* Camera is optional although highly encouraged. We understand that not everyone may have the space at home to have the camera on.

### Expectations
Learners are encouraged to be active participants while coding and are encouraged to ask questions throughout the module. Learners are expected to follow along with the coding, creating files and folders to navigate and manipulate. Learners should be active participants while coding and are encouraged to ask questions throughout.

# Module Schedule

The schedule is tentative and may be modified as needed. Learners will be notified of schedule changes.

|Class|Date        |Topic                             |
|-----|------------|----------------------------------|
|  1  | TBD        | ML System Design                 |
|  2  | TBD        | Data Engineering Fundamentals    |
|  3  | TBD        | Working with Training Data       |
|  4  | TBD        | Feature Engineering              |
|  5  | TBD        | Model Development and Evaluation |
|  6  | TBD        | Deployment and Model Explanations|

## Assignment Due Dates

+ Assignment 1 due on TBD.
+ Assignment 2 due on TBD.
+ Assignment 3 due on TBD.

## Resources
Feel free to use the following as resources:

### Documents
- [Docker Installation](https://docs.docker.com/engine/install/)
- [Cheatsheet](https://docs.docker.com/get-started/docker_cheatsheet.pdf)

### Videos
- [What is Docker?](https://www.youtube.com/watch?v=Gjnup-PuquQ)
- [Docker Playlist](https://www.youtube.com/playlist?list=PLe4mIUXfbIqaYmsoFahYCbijPU4rjM38h)

### How to get help
![image](./steps_to_ask_for_help.png)

<hr>

## Folder Structure

```markdown
.
├── 01_slides
├── 02_notebooks
├── 03_assignments
├── 04_data
├── 05_src
├── 06_instructional_team
├── 07_logs
├── LICENSE
├── README.md
└── steps_to_ask_for_help.png
```

* **slides:** module slides as PDF
* **notebooks:** Interactive notebooks (.ipynb files)
* **assignments:** Graded assignments
* **data**: Contains all data associated with the module
* **src:** Contains credit experiment
* **instructors:** Instructions for the Instructor on what to teach
* README: This file!
* .gitignore: Files to exclude from this folder, specified by the instructor

## Acknowledgement

We wish to acknowledge this land on which the University of Toronto operates. For thousands of years, it has been the traditional land of the Huron-Wendat, the Seneca, and most recently, the Mississaugas of the Credit River. Today, this meeting place is still the home to many Indigenous people from across Turtle Island and we are grateful to have the opportunity to work on this land.