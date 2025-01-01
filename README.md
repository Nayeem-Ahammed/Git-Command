# Git-Command



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git Cheat Sheet</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1, h2 {
            color: #2E3A59;
        }
        pre {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 5px;
        }
        ul {
            list-style-type: none;
            padding-left: 0;
        }
        li {
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h1>Git Cheat Sheet</h1>

    <h2>Configuration</h2>
    <ul>
        <li><pre>git config --global user.name "Your Name"</pre>: Set the name that will be attached to your commits.</li>
        <li><pre>git config --global user.email "your.email@example.com"</pre>: Set the email that will be attached to your commits.</li>
        <li><pre>git config --list</pre>: List all configuration settings.</li>
    </ul>

    <h2>Creating Repositories</h2>
    <ul>
        <li><pre>git init</pre>: Initialize a new Git repository.</li>
        <li><pre>git clone &lt;repository&gt;</pre>: Clone an existing repository.</li>
    </ul>

    <h2>Basic Snapshotting</h2>
    <ul>
        <li><pre>git add &lt;file&gt;</pre>: Add a file to the staging area.</li>
        <li><pre>git add .</pre>: Add all files to the staging area.</li>
        <li><pre>git commit -m "commit message"</pre>: Commit the staged changes with a message.</li>
        <li><pre>git status</pre>: Show the status of the working directory and staging area.</li>
        <li><pre>git log</pre>: Show the commit history.</li>
    </ul>

    <h2>Branching and Merging</h2>
    <ul>
        <li><pre>git branch</pre>: List all branches.</li>
        <li><pre>git branch &lt;branch-name&gt;</pre>: Create a new branch.</li>
        <li><pre>git checkout &lt;branch-name&gt;</pre>: Switch to a branch.</li>
        <li><pre>git merge &lt;branch-name&gt;</pre>: Merge a branch into the current branch.</li>
        <li><pre>git branch -d &lt;branch-name&gt;</pre>: Delete a branch.</li>
    </ul>

    <h2>Remote Repositories</h2>
    <ul>
        <li><pre>git remote -v</pre>: List all configured remote repositories.</li>
        <li><pre>git remote add &lt;name&gt; &lt;url&gt;</pre>: Add a new remote repository.</li>
        <li><pre>git fetch &lt;remote&gt;</pre>: Fetch changes from a remote repository.</li>
        <li><pre>git pull &lt;remote&gt; &lt;branch&gt;</pre>: Pull changes from a remote repository.</li>
        <li><pre>git push &lt;remote&gt; &lt;branch&gt;</pre>: Push changes to a remote repository.</li>
    </ul>

    <h2>Undoing Changes</h2>
    <ul>
        <li><pre>git reset &lt;file&gt;</pre>: Unstage a file.</li>
        <li><pre>git reset --hard</pre>: Reset the working directory and staging area to the last commit.</li>
        <li><pre>git revert &lt;commit&gt;</pre>: Create a new commit that undoes the changes from a previous commit.</li>
    </ul>

    <h2>Stashing</h2>
    <ul>
        <li><pre>git stash</pre>: Stash the current changes in the working directory.</li>
        <li><pre>git stash apply</pre>: Apply the stashed changes.</li>
        <li><pre>git stash list</pre>: List all stashes.</li>
    </ul>

    <h2>Viewing Changes</h2>
    <ul>
        <li><pre>git diff</pre>: Show changes between the working directory and the staging area.</li>
        <li><pre>git diff &lt;commit&gt;</pre>: Show changes between a commit and the working directory.</li>
        <li><pre>git diff &lt;commit1&gt; &lt;commit2&gt;</pre>: Show changes between two commits.</li>
    </ul>

    <h2>Tagging</h2>
    <ul>
        <li><pre>git tag</pre>: List all tags.</li>
        <li><pre>git tag &lt;tag-name&gt;</pre>: Create a new tag.</li>
        <li><pre>git push &lt;remote&gt; &lt;tag-name&gt;</pre>: Push a tag to a remote repository.</li>
    </ul>

    <h2>Miscellaneous</h2>
    <ul>
        <li><pre>git help &lt;command&gt;</pre>: Show help for a specific Git command.</li>
    </ul>
</body>
</html>
