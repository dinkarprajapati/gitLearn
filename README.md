# gitLearn

<b>git init</b><br/>
<p>This initializes an empty folder to be a git repository</p>
<br/>
<b>git remote add origin https://..</b>
<p>This will create a link for our folder in the remote address where we will be uploading all our changes.</p><br/>

<b>Undoing a Staged Change</b>
<p>git reset Head {filename}</p><br/>

<b>Undoing a Committed Change</b>
<p>git reset --soft HEAD~1</p>
<p>This command will move the commit to one previous step or the previously committed change will be cancelled. But to change the file we need to undo the staged change as well, which can be done by following command.</p>
<p> git reset HEAD {filename}</p>
<br/>

<b>Undoing a Pushed Change</b>
<p>After pushing your changes to github, if you want to revert the changes, use command</p>
<b>git revert HEAD</b><br/>

<b>git diff</b>
<p>Checking the difference of file in local and remote</p><br/>

<b>Fetch and Merge</b>
<p>git fetch</p>
<p>git merge origin/master</p><br/>

<b>Pull</b>
<p>Instead of using fetch and merge, we can use pull command.</p>
<p>git pull origin master</p>
<p>It is always a good practice to pull from remote repo before pushing it to remote repo. Pull command will try to pull all the changes made by other person before pushing your own changes.</p><br/>


<b>Learn Branch</b>
<p>git branch -a</p>
<p>Lists out all the branches in the repo</p>
<p>git branch {newBranchName}</p>
<p>This will create a new branch with the name mentioned</p>
<p>git checkout {newBranchName}</p>
<p>This will switch to the new branch</p>
<p>git checkout -b {newBranchName}</p>
<p>This command will create a new branch and switch to it as well. This is a one line solution for creating and switching to branch.</p>
<p>git branch -m {oldbranchname} {newbranchname}</p>
<p>This command is used to rename a branch</p>
<p>git branch -d {branchname}</p>
<p>This command deletes the branch, just make sure you checkout to another branch before deleting</p><br/>


<b>git Rebase</b>
<p>Similar to merge but removes history.</p><br/>


<b>git clone</b>
<p>Clones the project into your local.</p><br/>


<b>git Fork</b>
<p>Forking allows you to copy other peoples project into your own github account.</p><br/>

<b>git Pull</b>
<p>Pulling allows you to propose changes to someone else's project.</p><br/>

<b></b>
<p></p><br/>
