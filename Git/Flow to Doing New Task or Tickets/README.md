 Flow to Doing New Task or Tickets

1.	git checkout master

2.	git pull origin master

3.	git checkout -b “newtask/feature-branchname”

4.	git add -A

5.	git commit -m “message”

6.	git push origin branchname

7.	create pr from GitHub branch name to master

8.	check is there any conflicts if so point 9

9.	git pull origin master

10.	open vs code - resolve conflicts

11.	git add -A

12.	git commit -m “conflicts resolved”

13.	git push origin branchname

14.	check PR it should be fixed now

15.	merge from PR
	
 	For Next Feature or Task Repeat All Steps


	——— If Ticktet Already Created or Branch ——

Flow to Doing Already in Progress Task or Tickets

1.	git fetch

2.	git checkout branch name

3.	do some work

4.	git add -A

5.	git commit -m “some message”

6.	git push origin branch name

7.	check if PR already create or not
