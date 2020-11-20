# useful_git_info
Includes info and useful commands

> ### About Git:
> - Git is a **version control system** which helps us in tracking and managing the history of changes.
> - It can be used both locally and remotely.

***
> ### Git useful commands:
> - **git init** : Initializes the git directory.
> - **git add**  : addes modifications to the stagging directory.
>> - Until *git add* command is executed, the modified files will be in untracked bucket(meaing git is not tracking the changes).
> - **git status** : Gives overview of the branch like info about no of files in the stagging stage etc.
> - **git commit -m "Description"**: By executing this command,git takes the snapshot of the code(file).
>> ##### Guidelines For Commit Message:
>> - The first line is a short, approximately 50 character summary,followed by an empty line.
>> - The subsequent paragraphs arer jam-packed with descriptive information about the change.<br> This could include links to bugs and their descriptions.
> -  **git commit -a** :A shortcut to stage any changes to tracked files and commit them in one step.(Note:This won't work with new files)
> - **git log** : Displays history of commit messages.
> - **git log -p**: The p flag list down the patches(changes/deletions/additions) that are done in each commits.
> - **git log --stat** : stat flag gives the statistics of the commits.
***
> ### Useful Links:
