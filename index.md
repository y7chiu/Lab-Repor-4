# CSE15L Lab Report 4

## Timing Tasks

- Type ```<ssh cse15lsp23xx@ieng6.ucsd.edu>``` to login into ```ieng6```.

We do not have to type the password after we ```<ssh>``` to enter the ```ieng6``` acount since the github had already have the memory of the key that in the last lab we authorized our terminal connect to the ```github``` account. Therefore, this is why we don not have to type the password when signing in to the ```ieng6``` acount.

<img width="762" alt="截圖 2023-05-21 15 00 47" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/249e3365-db2c-42cd-a8c2-99cd7d015163">

- ```<ls>``` and ```<cd>``` into lab7, we will see ListExample.java

<img width="540" alt="截圖 2023-05-21 15 05 16" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/eae0a108-9c28-49f0-86fb-70080480a3bf">

- Testing to see if it is failed or succeed. We can see the testing is failed.
To test, use 

```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

<img width="970" alt="截圖 2023-05-21 16 11 18" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/18f761c7-362b-4c52-a62d-dd60244afb43">

- The failing test displays that the error is in ListExamples.merge. To edit the file, use vim command line with the specific file the user want to edit.

<img width="404" alt="截圖 2023-05-21 15 09 10" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/e8e33267-3bc6-435b-8a16-da5fe149e988">

- And we will go into the place like this

<img width="524" alt="截圖 2023-05-21 15 12 06" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/39dfe6e9-b069-4c8d-a657-1ac47b32283b">

- We have to edit the index 1 to inndex 2 to make the code correct. First press ```<k>``` *6, ```<l>``` *7, press ```<x>``` to delete 1 and press ```<i>``` to acces insert mode so that the user can change 1 to 2. After that, press ```<esc>``` button, and then type ```:wq``` to save and quit from the file.

k: go up.

l: go left.

x: delete the character.

i: go into the insert mode.

esc: exit from the current mode.

:w : save.

:q : quit.

:wq: save and quit.

- After editing, test if the coding is failed or succeed! The result seems like the testing is succeed!
To test, use 

```
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

<img width="995" alt="截圖 2023-05-21 16 08 59" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/dccc18ed-7934-433e-a785-437028e2cdeb">


- After testing, we are going to commit the file. first type in git commit and we will see this.

<img width="518" alt="截圖 2023-05-21 15 34 59" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/9c4ffaf5-368d-43b6-a299-82ca906bf56d">

- To access this, we can use git add <File> to success the commit.
  
<img width="441" alt="截圖 2023-05-21 15 37 13" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/47191eb3-5456-409c-bfcf-63b849ab013d">

- To check if the file is committed sucessfully, type git status to see the status
  
<img width="528" alt="截圖 2023-05-21 15 38 08" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/58917727-e19a-4ddb-aac6-12ba10b3a29d">

- Let's push the commit! However, I don't know why I could not push the commit. The message is as below:
  
<img width="1254" alt="截圖 2023-05-21 15 55 44" src="https://github.com/y7chiu/Lab-Repor-4/assets/130111605/9b4795c5-ae86-43df-b892-95440a111876">
  
I will try my best to find out the problem!

Could someone give me the hint to get some idea for this problem? Thank you so much!

This is my Lab report 4. Thanks for watching!
  
<Lab Report 4 Ended>









