## The GitFlow Workflow
The GitFlow workflow is an organizational method for Git branches created by Vincent Driessen. It features parallel branches containing seperate features and development that are eventually merged for release. 

![A diagram of GitFlow](https://datasift.github.io/gitflow/GitFlowHotfixBranch.png)

There are 5 branches in the model. First, new developments are added to feature branches, separate from the development branch. Finished features are then moved to the development branch. Once a version is ready for release, content is moved to the release branch, where features can be tweaked and bugs can be fixed. Once bugs are fixed, the version is moved to the master branch for public release. If bugs are found after release, hotfixes are made on the hotfix branch and then merged back into the master branch for an updated release. 
