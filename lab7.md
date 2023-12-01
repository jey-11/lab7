**Step 4:** `ssh cs15lfa23fe@ieng6.ucsd.edu` \<enter> <br>
I just typed out the ssh command to login to my ieng6 account <br>
![Image](Lab7_S4.png)<br>

**Step 5** 'git clone git@github.com:ucsd-cse12-f23/cse12-pa7-BST.git'<enter> <br>
I just typed out the command to git clone the forked respository onto my account cloud. <br>
![Image](Lab7_S5.png)<br>

**Step 6:** running the tests<br>
cd lab7\<enter> <br>
I changed my directory so I would be in the lab7 folder. Enter caused the command to run. <br>
bash test.sh\<enter> <br>
I ran the shell script that is used to test the ListExamples.java file <br>
![Image](Lab7_S6.png)<br>

**Step 7** edit the ListExamples.java file 
vim ListExamples.java<enter> <br>
i (go into insert mode) <br>
\<down> x37 \<right> x12 <backspace> 2 (editing the file)<br>
\<esc> (get out of insert mode)<br>
:wq (saves and exits from vim) <br>
![Image](Lab7_S7_P1.png)
![Image](Lab7_S7_P2.png)

**Step 8** re run the tests <br>
\<up> x2 (this went up my command history to get to the bash test.sh command) <br>
![Image](Lab7_S8.png)

**Step 9:** commit and push to git hub account <br>
git add ListExamples.java \<enter> <br>
this moves the file to the staging area<br>
![Image](Lab7_S9_P1.png) <br>

git commit \<enter> <br>
this moves/commits the file into the github repository <br>
![Image](Lab7_S9_P4.png) <br>
and prompts for a commit message where I included changed index1 to index2 
![Image](Lab7_S9_P2.png) <br>
then I clicked \<esc> and :wq to exit insert mode and save and exit from vim respectively <br>
![Image](Lab7_S9_P3.png) <br>
