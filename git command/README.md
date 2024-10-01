<body>
    <h2><u>Git</u></h2>
    <p><b>What is Git:-</b>free and open source version control system. and it is tools that help to tracks changes in code.</p>
    <p><B>what is Github:-</B>Github is a platform where we host repositories online.</p>
    <h2>Some useful Git command</h2>
    <p><b><u>configuring Git</u></b></p>
--> Git config --global username "name of user/uday"<br>
--> git config --global user_email "email of user/uday@gmail.com"<br>
--> git config --list <b>(show name and username)</b><br>
    <p><b><u>cloning:-</u></b>cloning basically used to access all all repositories and project in local system is called cloning.</p>
    cmd:- <b>git clone links</b>
    <p><b><u>Status:-</u></b>display the status of the code.</p>
    cmd:- <b>git status</b>
    <p><u><b>Add:-</b></u>adds new or changed files in your working directory to the git staging area.</p>
    cmd:-<b>git add filename </b>(it is used to add particular files)
    <br>or<br>
    cmd:- <b>git add .</b>(it is used for add all files)
    <p><b><u>commit:-</u></b>it is the record of change</p>
    cmd:- <b>git commit -m "some message"</b>
    <p><b><u>push:-</u></b>upload local repo content to remote repo.</p>
    cmd :- <b>git push origin main</b>
    <br>or<br>
    you can also use<br>
    cmd :- <b>git push -u origin main</b> (you can write at once after that  you can use)<br>
    cmd:- <b>git push</b>
    <p><b><u>git pull:-</u></b>any changes to come github to local git.</p>
    cmd:- <b>git pull origin main</b>
    <h2><u>init</u></h2>
    <p><b><u>init:</u>-</b>used to create a new repository.</p>
    cmd:- <b>git init</b>
    <br>cmd:-<b>git remote add origin ...links...</b><br>
    cmd:-<b>git remote -v</b>(to verify remote).
    <h2><u>Branch commands</u></h2>
    cmd:- <b>git branch </b>(to check branch).<br>
    cmd:- <b>git branch -m main</b>(to rename branch)<br>
    cmd:- <b>git checkout branchname</b>(to navigate).<br>
    cmd:- <b>git checkout -b (new branch name)</b>(create new branch and change).<br>
    cmd:- <b>git branch -d branchname</b>(to delete branch).
    <br>
    <br><b><u>merge and differentiate</u></b><br><br>
    cmd:- <b>git diff branchname </b>(to compare commits, branches , and files and more).<br>
    cmd:- <b>git merge branchname</b>(to merge two branches).
    <p><b><u>merge conflicts</u></b>:- an event that takes place when git is unable to automatically resolve difference in code between two commits.</p>
    if you have occur conflicts , first you resolve your code then you can follow these steps.<br>
    1. <b>add</b><br>
    2. <b>commit</b><br>
    3. <b>push</b><br>
    <h3><u>show all commits</u></h3>
    cmd:- <b>git log </b> (to show all commit)
    <h2><u>fixing mistake</u></h2>
    <b>case 1. staged changes (git add .)</b>
    <br>
    cmd:- git reset (for all file)<br>
    cmd:- git reset filename(for single file).<br>
    <br>
    <b>case 2. committed changes (git commit -m " message ")</b>
    <br>
    cmd:- git reset HEAD~1 (for one commit).
    cmd:- git reset commithash<br>
    cmd:- git reset --hard commithash
    <h3><u>forking</u></h3>
    <p><b>what is forking:-</b>A fork is a new repository that shares code and visibility salting with the original "upstream" repository.<br>Fork is a rough copy</p>
</body>