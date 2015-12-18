#How to prepare for the final exam

#####Fork this project on Github and clone it down to your local machine
* to clone enter ``git clone https://github.com/konsteacher/finalexam.git`` in the shell

#####Compose 10 multiple-choice questions on the following topics, commit the changes, push them up to your fork.
* For each composed question you get **``1 point``** to the total grade.
* Create question file for each question using ``mktemp question_XXXXX --sufix=.md`` command. By doing so you will reduce the chances of collisions with your peers (hopefully) while following a uniform format.
* The questions fall into [these](./topics.md) topics.
* Each topics is under separate directory.
* Try to make questions on all the topics.

#####Make pull request to the base project until ~~``Dec 25``~~ ``Dec 23``.
* Give me ~~``2``~~ ``4`` days to add my own questions (that I haven't added yet), generate exam variants and print them out.

#####Keep updated with the base project
* one way is to make pull request to your fork from the base repo using Github website and then pull from your fork to update your local master branch  by typing ``git pull origin master``
* another way is to create a remote reference to the base repo by giving it a name, for example ``upstream``, by typing ``git remote add upstream https://github.com/konsteacher/finalexam.git`` and then pull down ``upstream/master`` to your local repo and push it up to your Github fork.
