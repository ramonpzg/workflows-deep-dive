# Bridging the Gap Between DevOps and Data Professionals
==============================
## A Workshop Organised for PyCon South Africa 2022



Date: Wednesday, October 12th from 14:00 to 18:00 South African Standard Time


## Table of Contents
1. [Overview](#1.-Overview)
2. [Outline for the Session](#2.-Outline-for-the-Session)
3. [Prerequisites (P) and Good To Have's (GTH)](#3.-Prerequisites-(P)-and-Good-To-Have's-(GTH))
4. [Set Up](#4.-Set-Up)
5. [Resources](#5.-Resources)
6. [Feedback 😃](#6.-Feedback-😃)

Note: All files will be availble a day before the event so if you clone this repo beforehand (please do), you will want to do a `git pull` a day or so prior to the event.

## 1. Overview

Programmers, regardless of their level of experience, enjoy solving increasingly complex challenges within their domain of expertise, and one of the main reasons they can spend more time working through such challenges is because of the automation recipes they have built around their workflows. Data Analysts, Engineers and Scientists automate the initial steps of inspecting, cleaning, and analysing new data sets while DevOps Engineers automate everything from the filesystem to the infrastructure of software products. These groups of (data and engineering) professionals are not too foreign to each other as they all speak the same language, Python. That said, the goal of this workshop is to bring the automation recipes from the data world into the DevOps world and vice-versa. In other words, to bring all the slang and word abbreviations both groups use -- in code -- and create a dialect that welcomes both, newcomers and experts to either field.

In this workshop, we'll cover 4 major automation recipes from the Analytics and DevOps worlds to make you a more efficient and systematic programmer. Each section will last about 45-minutes, and the topics covered range from automating extract, transform, and load (ETL) pipelines to creating your own internal platform tools. By the end of the workshop, you will be able to speak some DevOps to your data professional colleagues, and some analytics to your engineering team (slang words included).

## 2. Outline for the Session

The time budgeted for this tutorial is 4 hours including breaks. We will follow, as best as possible, the following schedule.

1. **Introduction and Setup (~20 minutes)**
   - Flash instructors intro.
   - Motivation for the workshop.
   - Analytics vs Engineering.
   - Quick breakdown of the session.
2. **Data Recipe 1: Automating your data pipelines (~45 minutes)**
   - Intro to the datasets
   - Intro to the tools
   - Intro to Data Pipelines
   - Pipelines with pandas
   - Piepelines with Prefect
   - Exercise (7-min).
3. **10-minute break**
4. **DevOps Recipe 1: Testing (~45 minutes)**
   - Testing Code with,
       - `pytest`
       - `mypy`
   - Testing Data with `great_expectations`
   - Building your first CI Pipeline
   - Exercise (7-min).
5. **10-minute break**
6. **Data Recipe 2: Automating Your Analytics Pipeline (~45 minutes)**
   - Intro to the datasets
   - Descriptive Statistics Pipeline
   - Dashboard Pipeline
   - Exercise (7-min).
7. **10-minute break**
8. **DevOps Recipe 2: Continuous Automation (~45 minutes)**
   - Continuous Testing
   - Continuous Machine Learning
   - Exercise (7-min).


## 3. Prerequisites (P) and Good To Have's (GTH)

- **(P)** Attendees for this tutorial are expected to be familiar with Python (1 year of coding). 
- **(P)** Participants should be comfortable with loops, functions, lists comprehensions, and if-else statements.
- **(GTH)** While it is not necessary to have any knowledge of data analytics libraries, some experience with pandas, NumPy, matplotlib and scikit-learn, a bit of experience with these libraries would be very beneficial throughout this tutorial.
- **(P)** Participants should have at least 5 GB of free space in their computers.
- **(GTH)** While it is not required to have experience with integrated development environments like VS Code or Jupyter Lab, this would be very beneficial for the session.
- **(P)** You will need a GitHub account and you will also need to have git set up in your local computer. Here is a great [guide to get git setting it up](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup).


## 4. Setup

If you are on a Mac or Linux machine, the set up steps will be the same. If you are in a Windows machine, you can still follow along with the tutorial, but please bare in mind that your experience  will be a much better one if you were to download, install and use (preferrably) Windows Subsystem for Linux or Git Bash for the session.

You should first make sure you have [Anaconda](https://www.anaconda.com/products/individual#download-section) or, preferrably, [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed before following the next steps.

#### First Step

Open up your terminal and navigate to a directory of your choosing in your computer. Once there, run the following command to get the code for the session.

```sh
 git clone https://github.com/ramonpzg/pycon-za2022-analytics-devops.git
```

Conversely, you can click on the green `download` button at the top and donwload all files to your desired folder/directory. Once you download it, unzip it and move on to the second step.

#### Second Step

To get all dependancies, packages and everything else that would be useful in this tutorial, you can recreate the environment by first going into the directory for today.

```sh
cd pycon-za2022-analytics-devops
```

Then you will need to create an environment with all of the dependancies needed for the session by running the following command.

```sh
conda env create -f environment.yml
```

#### Third Step

Once that environment has been set up, the next step is to activate it using the following command.

```sh
conda activate pyconza-dad
```

#### Fourth Step

Open up Jupyter Lab and you should be ready to go.

```sh
jupyter lab
```

Great work! Now navigate to `notebooks/01_etl_pipes.ipynb` and open it.


## 5. Resources

Here are a few great resources to get started with the topics covered in this workshop.

- [Fundamentals of Data Engineering](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/) by Joe Reis and Matt Housley
- [Fundamentals of Data Visualisation](https://clauswilke.com/dataviz/) by Claus O. Wilke
- [The Big Book of Dashboards](http://bigbookofdashboards.com/) by Steve Wexler, Jeffrey Shaffer, and Andy Cotgreave
- [Python for DevOps](https://www.amazon.com/Python-DevOps-Ruthlessly-Effective-Automation/dp/149205769X) by Noah Gift, Kennedy Behrman, Alfredo Deza, and Grig Gheorghi
- [Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython](https://wesmckinney.com/book/) by Wes McKinney

## 6. Feedback 😃

If you liked this tutorial and would like to give us your feedback so that we can improve it, we would greatly appreciate that.

> # [Feedback Form](https://forms.gle/cuW4B5cdSL8DaLnR8)
