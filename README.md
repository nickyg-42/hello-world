## Initial Setup
***
In order to contribute, you first have to **clone the repository**.

Extra Info: Cloning creates a local copy of the remote repository. You can edit your local copy, and push it back to remote.
Then, other people can pull from remote in order to updated their locals with your latest changes.
You can also pull from remote to get their latest changes

**IMPORTANT:** cloning is only done once. Once you have a repository cloned, you can simply run `git pull` to update it.

Steps:
- Click the green "clone" button on the main page of the repository
- Select "https" and copy the URL
- Open your terminal and type the command `git clone <url>`

After you complete this, you should now find the repository as a folder on your computer.

## Contributing
***
Once you have cloned the repository you can now make any desired changes and push them back to remote

- Navigate into the newly created folder using the `cd` command (i.e. `cd hello-world`)
- Open the file called "edit-me.txt" in any text editor (notepad, VS Code, etc.)
- Add anything to it
- Save it
- Run the following commands in order, one at a time (make sure you are running then from within the folder you cloned)
- `git add edit-me.txt`
- `git commit -m "updated the edit-me.txt file"`
- `git push origin main`

### Command Explenations
- `git add`: This essentially tells git which files you want to push back to remote
- `git commit`: This makes a "commit" which is a building block of git. a commit is essentially a snapshot of the repository at this state and time. You can add the "-m" flag in order to add a message. this message helps you know what the purpose of the commit is.
- `git push`: This updates the remote repository with your new changes. `origin main` corresponds to the branch name that you are pushing too. More on branches later.

