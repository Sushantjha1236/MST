# MST
4. The task
You again live in your own branch, this time we will be doing a bit of juggling with branches, to show how lightweight branches are in git. Hint: git switch will make you switch from one branch to another.
1.	Use git branch to see the two branches that are relevant for this exercise.
   - git branch --all
3.	What branch are you on?
   - main  
5.	Use git branch mybranch to create a new branch called mybranch
  ![Screenshot 2024-03-13 110339](https://github.com/Sushantjha1236/MST/assets/113833084/a28052c8-c312-45f4-86aa-3b310cc20c07)
6.	Use git branch again to see the new branch created.
7.	Use git switch mybranch to switch to your new branch.
![Screenshot 2024-03-13 110451](https://github.com/Sushantjha1236/MST/assets/113833084/5c18d67e-03b9-402b-a5ca-b49ca8bc1e7e)
8.	How does the output from git status change when you switch between the master and the new branch that you have created?
9.	How does the workspace change when you change between the two branches?
![Screenshot 2024-03-13 110540](https://github.com/Sushantjha1236/MST/assets/113833084/8066b1d6-8cb3-4b90-935e-0773a13ac44d)
10.	Make sure you are on your mybranch branch before you continue.
11.	Create a file called file1.txt with your name.
12.	Add the file and commit with this change.
![Screenshot 2024-03-13 110628](https://github.com/Sushantjha1236/MST/assets/113833084/ade248e9-bf81-41cb-a59d-8a88063bd5b7)
13.	Use git log --oneline --graph to see your branch pointing to the new commit.
![Screenshot 2024-03-13 110710](https://github.com/Sushantjha1236/MST/assets/113833084/4875a226-f219-47dc-9cc7-6654ca05702f)

14.	Switch back to the branch called master.
15.	Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.
16.	Make a new file called file2.txt and commit that file.
17.	Use git log --oneline --graph --all to see your branch pointing to the new commit, and that the two branches now have different commits on them.
18.	Switch to your branch mybranch.
19.	What happened to your working directory? Can you see your file2.txt?
20.	Use git diff mybranch master to see the difference between the two branches.
![Screenshot 2024-03-13 110801](https://github.com/Sushantjha1236/MST/assets/113833084/d7e6810c-148b-47da-9ea8-e09b0659bfdb)



### Answers
![Screenshot 2024-03-13 110154](https://github.com/Sushantjha1236/MST/assets/113833084/15424e56-bb83-44ca-bacb-e17c4b7ced76)
![Screenshot 2024-03-13 110124](https://github.com/Sushantjha1236/MST/assets/113833084/33c7ba63-31b7-46e7-a9ba-c8762c1e3d1d)
