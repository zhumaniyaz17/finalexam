#How to prepare for the final exam

#####Fork this project on github and pull/clone it down to your local machine
* to clone enter ``git clone https://github.com/konsteacher/finalexam.git`` in the shell
* to pull from your fork on github to update your local master branch type ``git pull origin master``

#####Create 10 multiple-choice questions on the following topics and commit the changes and push them up to your fork
  * Computer system concepts (including OS concepts)
  * Linux System Concepts
    * Basic and not-so-basic commands
    * Files and filesystem
    * Users and permissions
    * Shell scripting and process environment
  * Linux system programming
    * Process creation and management
    * IPC mechanisms
    * Multithreading using pthreads
  * Git/Github Concepts

#####Sample question
Create question file for each question using ``mktemp question_XXXXX --sufix=.md`` command.
By doing so you will reduce the chances of collisions with your peers (hopefully)
while following a uniform format.


***
  How many processes including the parent will be created by the following code?
  ```C
  #include <unistd.h>
  int main(){
    if (!fork()){
      fork();
    }
  }
  ```
  * 2
  * 3
  * 4
  * 5
  * 8

***
#####Make pull request to the base project
#####Keep updated with the base project
