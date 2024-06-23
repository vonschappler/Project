
## What is PROJECT?

!['P' Branding in black circle with tag, "for organized success."](https://github.com/vonschappler/Project/wiki/logo.png)

The 'Project' tutorial by von Schappler is designed to guide users in organizing a multi-phase GitHub project using submodules. It explains setting up individual repositories for different parts of a project (assets, backend, frontend) and linking them through a central repository for better management and clarity. The tutorial assumes users have basic knowledge of Git, GitHub, and CLI. It outlines the problem of disorganized repositories and proposes a solution using Git submodules, providing a structured method to maintain and reference related repositories efficiently.

## [Introduction](https://github.com/vonschappler/Project/wiki/Introduction)

This section provides an overview of a common problem that we, as developers have to deal with in our daily work - how to setup and organize properly a git project, both on the "cloud" - using Github as the online repository provider - and on your local environment.

## [Applying the Solution](https://github.com/vonschappler/Project/wiki/Appling-the-Solution)

This section details the initial setup required for organizing a project using Git submodules. It covers creating a main project repository and separate repositories for different components (e.g., Assets, Backend, Frontend). The steps include creating and initializing these repositories on GitHub, cloning them locally, and then adding them as submodules to the main project. The setup process involves running commands like git submodule add to link the submodules and configuring the .gitmodules file to manage their paths and URLs. This organizational structure ensures that each component is independently version-controlled, making the project easier to manage and update.

## [Working with PROJECT's structure](https://github.com/vonschappler/Project/wiki/Working-with-this-structure)

This section explains working within the established project structure, focusing on editing submodules and updating the main repository. It provides a walkthrough of editing a file (e.g., README.md in the Assets folder), committing changes, and pushing them to the submodule's repository. The next steps involve updating the main repository to reflect these changes and ensuring the references are current. The section also covers removing submodules by editing the .gitmodules and .git/config files and updating the main repository accordingly. It concludes with instructions on re-adding submodules if needed, highlighting the flexibility and control provided by this structure.

## [External Resources](https://github.com/vonschappler/Project/wiki/External-Resources)

This section contains a small set of useful resource links used as reference for this tutorial.
