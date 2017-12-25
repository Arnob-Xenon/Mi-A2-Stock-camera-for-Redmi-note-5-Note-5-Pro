# Magisk Repo Submissions
This is the place for developers to submit their Magisk Module to the [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo).

## Instructions:
1. Please read the [full documentation](https://github.com/topjohnwu/Magisk/blob/master/docs/module_repo.md). You are expected to have decent knowledge to both Magisk and `git` in order to do a submission
2. Create a new Github repository in your personal account, and push your module files to the repo. If you do not want to start from scratch, start with forking the [magisk-module-template](https://github.com/topjohnwu/magisk-module-template) and add your files there
3. **Only the `master` branch will be visible to the user!** If you are using the module template, you have to manually create the `master` branch. **Submissions with no `master` branch will not be accepted!**
4. File a request by [creating an issue](https://github.com/topjohnwu/Magisk_Repo_Submissions/issues/new). The rules and format are detailed in the next section.
5. A collaboration invitation will be sent to your email, please accept it so you have permissions to update your repo. **You should update your module directly to the repo on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo), NOT your personal repo!** Once your repo is cloned to the online repo, you can delete your personal repo, since it will not be used anymore.

## Format of Requests
All requests are done through issues and handled automatically by a small server (the code is available in this repo). Currently you have two actions availible:

#### Submission:
Create a new issue and start the title with **`[Submission]`**, then provide a link to **your module's repository**. Below is an example:
![](./images/submission.png)

#### Removal:
If you decide to remove a module from the online repo, create a new issue and start the title with **`[Removal]`**, then provide the link to **your repository on [Magisk-Modules-Repo](https://github.com/Magisk-Modules-Repo)**. Below is an example:
![](./images/removal.png)