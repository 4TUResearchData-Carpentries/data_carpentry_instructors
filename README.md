# Data Carpentry Instructors

Instructor resources for Data Carpentry workshops

This repository is intended to hold resources for instructors in the LDEV data carpentry workshops, including:

- Presentation slides
- Curriculum notes
- Notes on good practice / special situations

The goal is to build up a shared library of resources for both current and future instructors, and minimise the "resource sprawl" that can occur.
So please deposit your files and notes here, in the **BRANCH CORRESPONDING TO EACH RUN OF THE COURSE**

## Instructions for using this repo:

1. **BEFORE** the course
  - **HOST** to create a branch (from *main*) named according to the official Carpentries slug format eg 2025-02-13-TUD
  - **HOST** to ceare a corresponding branch from the data_carpentry_learner repository and update its README file with the correct branch name and location of the google doc.
  - Distribute the URL of this branch to instructors
  - **INSTRUCTORS** Make sure you can access the repo; add any class resources you plan to use in the relevant directory. Ensure you can commit, and engage with host if there are permissions problems
  - Ensure that you can access the corresponding learners'  ([repository](https://github.com/4TUResearchData-Carpentries/data_carpentry_learners)) and set up any learners' resources, set up and test gitautopush etc.
  - **UPDATE LINKS** in the learners repository to resources like the shared Google Docs, course website, daily schedule etc.
2. **DURING** the course
  - Keep resources up to date both here and in the learners' repo.
  - Periodically check whether gitautopush is actually pushing into the learners' repo
  - At the end of each session, do any organising / editing of autopushed contents that you feel would help students reviewing the material,
3. **AFTER** the course
  - At the course review meeting, assess whether any of the materials (eg. changed curriculum notes, slide decks, cheat sheets etc.) should be merged into *main*
  - **HOST** to coordinate merging these materials into *main* so that they become automatically available in future branches.
  - After any final updates or material reorganisation, the working branch for the course is to be **frozen** so that it can be viewed but not altered.

 ## Further notes for instructors

 It is often helpful to use *gitautopush* in order to generate an automated log for course participants of what has been done in the class, both for
 situations in which they may fall behind a bit during the class, and for later review.

 Detailed instructions for gitautopush can be [found in the workshop_notes repository](https://github.com/4TUResearchData-Carpentries/workshop_notes) that was created
 for Software Carpentries courses at TU Delft. Please note that for Data Carpentries courses, the following target repository details apply:

 - **Target repository:** data_carpentry_learner
 - **Target repository URL:** [https://github.com/4TUResearchData-Carpentries/data_carpentry_learners/tree-2024-09-30-ldev-delft](https://github.com/4TUResearchData-Carpentries/data_carpentry_learners/tree/2024-09-30-ldev-delft)
 - **Branch name**: Same as you are using in this repository (2024-09-30-ldev-delft)
 - **Files to update**:  Depends on the particular module you are teaching, but we suggest using the empty log files that have been created in the template repository, or else creating ones with a similar naming scheme if relevant to your teaching.

## Other uses for the Learner repository

Please feel free to add other resources to the Learner repository.  We have "seeded" the template with some of the Posit
cheat sheets for R, R Markdown and dplyr.  But by all means add other resources you think are useful, and consider in the *post-mortem* meeting whether these should be merged into main for future use.
