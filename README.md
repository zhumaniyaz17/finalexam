#How to prepare for the final exam

#####Fork this project on github and pull/clone it down to your local machine
* to clone enter ``git clone https://github.com/konsteacher/finalexam.git`` in the shell
* to pull from your fork on github to update your local master branch type ``git pull origin master``

#####Create 10 multiple-choice questions on the following topics, commit the changes, push them up to your fork.
* Create question file for each question using ``mktemp question_XXXXX --sufix=.md`` command. By doing so you will reduce the chances of collisions with your peers (hopefully) while following a uniform format.
* The questions fall into [these](./topics.md) topics.
* Each topics is under separate directory.
* Try to make questions on all the topics.

#####Make pull request to the base project until ~~``Dec 25``~~ ``Dec 23``.
* Give me ~~``2``~~ ``4`` days to add my own questions (that I haven't added yet), generate exam variants and print them out.

#####Keep updated with the base project
* There are several ways how to keep up to date with the base repository:
 * one way is to make pull request to your fork from the base repo using Github website
 * another way is to create a remote reference to the base repo by giving it a name, for example ``upstream``, and then pull down ``upstream/master`` to your local repo and push it up to your Github fork.

##### All question added so far
* [general] (./general/)
* [linux](./linux/)
* [syspro](./syspro/)
* [git](./git/)

