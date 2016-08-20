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
<p>After pushing your changes to github, if you want to revert the changes, use command</p><br/>
<b>git revert HEAD</b>
<p>Then push the previous commit to master, this will remove the new changes and revert back the previous one.</p><br/>

<b>git diff</b>
<p>Checking the difference of file in local and remote</p><br/>

<b>Fetch and Merge</b>
<p>git fetch</p><br/>
<p>git merge origin/master</p><br/>

<b></b>
<p></p><br/>

<b></b>
<p></p><br/>

<b></b>
<p></p><br/>
