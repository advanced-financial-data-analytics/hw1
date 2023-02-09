## Homework 1

The goal of this homework assignment is to introduce you to R, Posit, Git, and GitHub, which you'll be using throughout the course both to learn the data science concepts discussed in the course and to analyze real data and come to informed conclusions.

# Getting started

## Prerequisites

This assignment assumes that you have reviewed the lectures titled "02-Meet the toolkit". If you haven't yet done so, please pause and complete the following before continuing.

## Terminology

We've already thrown around a few new terms, so let's define them before we proceed.

-   **R:** Name of the programming language we will be using throughout the course.

-   **Posit:** An integrated development environment for R. In other words, a convenient interface for writing and running R code.

-   **Git:** A version control system.

-   **GitHub:** A web platform for hosting version controlled files and facilitating collaboration among users.

-   **Repository:** A Git repository contains all of your project's files and stores each file's revision history. It's common to refer to a repository as a repo.

    -   In this course, each assignment you work on will be contained in a Git repo.
    -   For individual assignments, only you will have access to the repo. For team assignments, all team members will have access to a single repo where they work collaboratively.
    -   All repos associated with this course are housed in the course GitHub organization. The organization is set up such that students can only see repos they have access to, but the course staff can see all of them.

## Starting slow

As the course progresses, you are encouraged to explore beyond what the assignments dictate; a willingness to experiment will make you a much better analyst! Before we get to that stage, however, you need to build some basic fluency in R. First, we will explore the fundamental building blocks of all of these tools.

Before you can get started with the analysis, you need to make sure you:

-   have a GitHub account (use your QUB email to register) 

-   are a member of the course GitHub organization (share your username and email with lecturer using this [google sheet](https://docs.google.com/spreadsheets/d/1-K29Kr4ly8EpQpXWN5zkuVQMbF0BWfPrK1mnYDJjqrU/edit?usp=sharing))

-   are a member of the course Posit Cloud space (See Canvas Announcements for details)

If you failed to confirm any of these, it means you have not yet completed the prerequisites for this assignment. Please go back to [Prerequisites] and complete them before continuing the assignment.

# Workflow for future homeworks

<iframe> src='https://www.loom.com/share/e8c02eda86e2491a815401ba6d260738' </iframe>

**IMPORTANT:** If there is no GitHub repo created for you for this assignment, it means I didn't have your GitHub username as of when I assigned the homework. Please let me know your GitHub username asap, and I can create your repo.

For each assignment in this course you will start with a GitHub repo that I created for you and that contains the starter documents you will build upon when working on your assignment. The first step is always to bring these files into Posit so that you can edit them, run them, view your results, and interpret them. This action is called **cloning**.

Then you will work in Posit on the data analysis, making **commits** along the way (snapshots of your changes) and finally **push** all your work back to GitHub.

The next few steps will walk you through the process of getting information of the repo to be cloned, cloning your repo in a new Posit Cloud project, and getting started with the analysis.
