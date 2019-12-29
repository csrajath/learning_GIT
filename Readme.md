##### This markdown file contains the notes for the git classes that I took online.

### Git Status


Another way to check the status of files with b or to say to get the status in online, we can use:
```git
git status --short
```

### TREE
To see the contents or structure of your *.git* file, file that tracks the directories, use the below command.
```git
tree .git 
```
The output of the above command i.e the *.git* file structure would look something like below:
```git
├───hooks
├───info
├───logs
│   └───refs
│       ├───heads
│       └───remotes
│           └───origin
├───objects
│   ├───info
│   └───pack
└───refs
    ├───heads
    ├───remotes
    │   └───origin
    └───tags
```
- *objects* is a database, this the place where git stores everything about the project
https://www.youtube.com/watch?v=yI0BtEzdGtw&t=734s
## General Git Features
1. Each clone contains enitre history
1. Git is distributed, that is everybody has a version of the repository locally.
   1. Instead of just having one central repository that you send changes to, every committer has 
their own repository that has the entire commit history of the project.

## Handy Git Commands
- To get *status* in online
```git
1. git status --short 
```

