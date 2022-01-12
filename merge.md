### Making new Branches

Sometimes, it's useful to make a separate branch than your main one, if you want to test something out separately from the core code, rather than making many edits.

To make a separate branch, click the 'main' button above, type in the desired name of your new branch, 'merge' in the example before clicking 'Create branch: merge from 'main'.

![](https://user-images.githubusercontent.com/94135223/149171493-9b957183-3161-4866-ab40-5db3a1dba5e8.png)

This branch includes all the same files as the original, but is kept in a separate folder. The key difference between making a new branch and cloning is that a new branch is kept remotely in gitHub, whereas cloning involves saving the remote repository to a local source (i.e. from gitHub to your computer).
From this, you can have separate files and codes without changing anything in the original/main branch.

Creating a new branch can also be done when creating a new file. Before pressing commit, there is an option to commit to the branch you are working in, or by creating a new branch and starting a pull request.

![](https://user-images.githubusercontent.com/94135223/149172667-083e0c47-8e77-49dd-8f1c-465af7acbf67.png)

After using both of these methods, the intro_to_gitHub repository now has three branches - 'main', 'Merge' and 'merge_example'. As I created 'merge_example' while making this file, this file exists only in the 'merge_example' branch.


### Deleting Branches

Given that the 'main' and 'Merge' branches are identical, to tidy things up a bit, the 'Merge' branch can be deleted. To do this, click ![](https://user-images.githubusercontent.com/94135223/149174229-2e070686-ec8f-4e33-8615-ca68fe0b3278.jpg). This takes you to a page where all branches are shown. Click the ![](https://user-images.githubusercontent.com/94135223/149174453-dfc0f375-8852-48e3-8ae6-4a96b2087e1d.png) icon next to the 'Merge' branch, and poof! It has been deleted.


### Pull Requests

Now, we have this merge explanation (i.e. code) in the 'merge_example' branch. If I have decided that this code runs well and can be put to the main branch, then I can create a **Pull Request** to merge this 'merge_example' branch with the 'main' branch. To do this, go to the main branch homepage, and click the 'Compare and pull request' button, as shown below

![](https://user-images.githubusercontent.com/94135223/149175773-b3cd93d4-1c08-434b-849a-9212dfe903b9.png)

From this, you are taken to open a pull request. You can choose the branch you wish to merge this new piece of code with. In this case, the **base:** is where you wish to send the new piece of code, the **compare:** is the branch which contains the new code. 

![](https://user-images.githubusercontent.com/94135223/149176601-579785d8-9d79-40df-a580-df2ff0991ba3.png)

From this, you can add any comments, before pressing ![](https://user-images.githubusercontent.com/94135223/149176913-ac6ede89-290a-4582-bcb0-d7a94a14b384.png) in the bottom right. This opens a pull request. When there's multiple collaborators, this pull request (in this case, merging the 'merge_example' branch with the 'main' branch) is peer-reviewed before it is approved. However, since this exists for demonstrative purposes and I'm the only person involved in this repository at the time of writing, I can click ![](https://user-images.githubusercontent.com/94135223/149177359-01dcb2c7-0f54-4b20-ba03-6ffe96b69c93.png) to merge the two branches and thus approve the pull request.

After this, it pops up saying that the pull request is closed and that the 'merge_example' branch can be deleted. For sake of tidiness, I have done so, but in bigger/more collaborative projects and through using GitHub, it will become clearer whether to keep or delete specific branches.

