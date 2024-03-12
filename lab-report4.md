# labreport4
## step 4
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/2b4e623b-811a-4d2d-bc34-9a816a6a45d3)

First I copied the login using `<crtl> + <c>`,putting in the normal `ssh dsotogarcia@ieng6.ucsd.edu` using `<crtl> + <v>` and hit `<enter>`. Once entered, the server then asked for my access key(I have it set to a key word) and typed it in with `<enter>` once again for step 4.

## step 5
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/23df86bf-1600-4a1e-81b4-c4cb5270c489)

Afterwards I entered `git clone` and used `<crtl> + <c>` to copy in `<git@github.com:dsoto0125/lab7.git>` using `<crtl> + <V>` in order to clone the forked repository from github(I had done it earlier by accident in order to test my key) by hitting `<enter>` afterwards.

## step 6
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/45f1de40-54e4-433b-879e-473b48905bf6)

From there on, I needed to locate the file and run the tests for *ListExamples.java*. I do this by typing `ls` and hitting `<enter>` which gets me to type `cd l` finishing with `<tab>` to get lab7/ and doing `<enter>`,in order to change directories and then I run the file by typing `bash t` and then use `<tab>` and `<enter>` in order to finish step 6.

## step 7
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/b0e0d96b-8c24-4d19-83e4-125810d49f3b)
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/b95d8cbc-bcaa-4709-9c7c-2dd5932b8e0c)

Now step 7 is to use Vim in order to fix *ListExamples.java* in order to have the tests run properly. I start by typing `vim L` then use `<tab>` and type `E` followed by `<tab>` and finally one last `<tab>` after typing a period in order to efficiently access ListExamples.java. After hitting `<enter>` to see the java file in vim, I locate the problem and use around 40 `<j>`'s to get down to the line with `index1 += 1` and press `<l>` about 6 times in order to move right to finally press `<x>` and delete 1. Then by pressing `<i>` to enter insert mode with vim, I promptly type in `2` to make it `index2` and fix the problem. Finally to exit out of vim with changes saved, I press `<esc>` followed by `<shift> + <;>` in order to put a colon and follow it up with `wq` which saves our changes and allows us to exit vim. 

## step 8
![image](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/0effc1d7-8beb-4787-8dab-200f93a69c72)

Step 8 has us following the same steps as step 6, typing `bash t` and then use `<tab>` and `<enter>` that gives us the expected result of the 2 tests running correctly.

## step 9
![Screenshot 2024-02-27 231839](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/d8f62df3-5570-4f22-870a-dec30fff723e)
![Screenshot 2024-02-27 231913](https://github.com/dsoto0125/cse15l-lab-reports/assets/156368824/607912bf-f413-4e0d-b70e-896d4df3c299)

Finally in step 9, we begin to commit our saved file. We begin by typing in `git commit -m "commit message"` we are able to commit our saved changes to the file. Normally we would get a vim window but for our purposes -m will allow us to simply put `"commit message"` and because I am lazy(lol). Now using `git push` we are able to push the commited changes to origin (aka the fork of our repository on github) and we finish our changes through vim. I was able to do `git commit -m "commit message"` with `git add`(it got lost because I was figuring out how to git commit) and added the changes to then commit them on the original. 




