Glossary and instructions.

Branch: Branching allows teams of developers to easily collaborate inside of one central code base. When a developer creates a branch, the version control system creates a copy of the code base at that point in time. Changes to the branch don't affect other developers on the team.
Clone: You can clone a repository that you want to contribute to directly from WebStorm and create a new project based on it. 
1.	From the main menu, choose VCS | Get from Version Control.
2.	In the Get from Version Control dialog, choose GitHub on the left.
3.	Specify the URL of the repository that you want to clone. You can select a repository from the list of all GitHub projects associated with your account and the organization that your account belongs to.
4.	In the Directory field, enter the path to the folder where your local Git repository will be created.
5.	Click Clone. If you want to create a project based on these sources, click Yes in the confirmation dialog. 

Commit: As your changes are ready to be committed, select the corresponding files or a change list. If you press Ctrl+K , the entire active change list will be selected. Or press Ctrl+K

Fetch: If you have several projects roots or want to fetch changes from all branches each time you sync with the remote repository, you may find updating your project a more convenient option. When you perform the update operation, WebStorm fetches changes from all project roots and branches, and merges the tracked remote branches into your local working copy (equivalent to pull).
1.	From the main menu, choose VCS | Update Project or press Ctrl+T. The Update Project dialog opens.
2.	Select the update type (this strategy will be applied to all roots that are under Git version control):
-Merge the incoming changes into the current branch: select this option to perform merge during the update. This is equivalent to running git fetch and then git merge, or git pull --no-rebase. Rebase the current branch on top of the incoming changes: select this option to perform rebase during the update. This is equivalent to running git fetch and then git rebase, or git pull --rebase (all local commits will be put on top of the updated upstream head).

•	GIT: Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.

•	Github: is an American multinational corporation that provides hosting for software development and version control using Git. It offers the distributed version control and source code management (SCM) functionality of Git, plus its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

•	Merge: Merge is the process of combining the various versions of a file or folder. This feature is typically found in version control software as a fundamental operation that is responsible for reconciliation of changes of data in a file. Merging software is able to combine changes in files placed in two different systems or used by different users.

•	Merge Conflict: When you work in a team, you may come across a situation when somebody commits changes to a file you are currently working on. If these changes do not overlap (that is, changes were made to different lines of code), the conflicting files are merged automatically. How to fix it. 
1.	Click Merge in the Conflicts dialog, the Resolve link in the Local Changes view, or select the conflicting file in the editor and choose VCS | <your_VCS> | Resolve Conflicts from the main menu.
2.	To automatically merge all non-conflicting changes, click   (Apply All Non-Conflicting Changes) on the toolbar. You can also use the   (Apply Non-Conflicting Changes from the Left Side) and   (Apply Non-Conflicting Changes from the Right Side) to merge non-conflicting changes from the left/right parts of the dialog respectively.
3.	To resolve a conflict, you need to select which action to apply (accept   or ignore  ) to the left (local) and the right (repository) version, and check the resulting code in the central pane:
4.	Review merge results in the central pane and click Apply.
•	Push: A push is the action of the server supplying message information to a service worker; a notification is the action of the service worker sending the information to a user. Push messaging lets developers engage users by providing timely and customized content outside the context of the web page. 
1.	To push changes from the current branch press Ctrl+Shift+K or choose VCS | Git | Push from the main menu.

•	Pull: Refreshing a local Mercurial repository with the changes from the remote repository (Pull) involves retrieving changes and applying them to the local data. The Mercurial integration with WebStorm provides interface for specifying the mandatory Pull settings and for customizing the Pull procedure. How to do it:
1.	From the context menu, choose VCS | Mercurial | Pull Changesets. The Pull dialog opens.
2.	Specify the required URL address of the source remote repository.
•	Remote: In WebStorm, any server with the document root outside the current project is called remote. This server may be running on a physically remote host or on your machine. For example, if your project is in C:/WebStormProjects/MyProject and the web server document root is C:/XAMPP/htdocs, for WebStorm this web server is remote.

•	Repository: Generically refers to a central place where data is stored and maintained. A repository can be a place where multiple databases or files are located for distribution over a network, or a repository can be a location that is directly accessible to the user without having to travel across a network. 
1.	Open the project that you want to put under Git.
2.	From the main menu, choose VCS | Import into Version Control | Create Git Repository.
3.	In the dialog that opens, specify the directory where a new Git repository will be created.  Git does not support external paths, so if you choose a directory that is outside your project root, make sure that the folder where the repository is going to be created also contains the project root.
4.	If you are creating multiple Git repositories inside the project structure, repeat the previous steps for each directory.



References

A step by step guide to setting up Webstorm for front-end development
https://www.suneco.nl/blogs/a-step-by-step-guide-to-setting-up-webstorm-for-front-end-development#:~:text=%20It%E2%80%99s%20installed%20like%20this%3A%20%201%20Download,the%20plugin%20close%20the%20plugin%20window%20More%20 

Creating Repository in GitHub
https://www.geeksforgeeks.org/creating-repository-in-github/
https://www.jetbrains.com/help/webstorm/set-up-a-git-repository.html



