# Remove Branch Locally:
Switch to a Different Branch:
Before deleting a branch, ensure you are not currently on the branch you want to delete. If you are on the branch you want to delete, switch to a different branch:
 ```git checkout <another_branch> ```
Replace <another_branch> with the name of an existing branch.
# Delete the Local Branch:
Delete the branch locally using the following command:
 ```git branch -d <branch_to_delete> ```
If the branch has unmerged changes, use -D instead of -d to force the deletion:
``` git branch -D <branch_to_delete> ```
Replace <branch_to_delete> with the name of the branch you want to remove.

# Remove Branch Remotely (on GitHub):
Delete the Remote Branch Locally:
Use the following command to delete the remote branch locally:
 ```git push origin --delete <branch_to_delete> ```
Replace <branch_to_delete> with the name of the branch you want to delete on the remote repository.

Push Changes to GitHub:
Push the changes to the remote repository on GitHub:
 ```git push origin --delete <branch_to_delete> ```

# How to list tags locally
 git tag 
Running this command in the terminal or command prompt, within the directory of your Git repository, will display a list of all the tags in that repository. If no tags exist, the output will be empty.

If you want to see additional information, such as the commit hash associated with each tag, you can use the following command:
```git show-ref --tags```

#How to delete tag locally and remotely.
Delete Locally:
 ``` git tag -d <tag_name> ```
Replace <tag_name> with the name of the tag you want to delete.

Delete Remotely:
 ```git push origin --delete <tag_name> ```




