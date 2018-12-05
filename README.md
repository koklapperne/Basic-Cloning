# Basic-Cloning
Tutorial to demonstrate basic cloning in git. This will demonstrate how you can work on a project from two different computers or how to work together with others in a very simple way. This workflow requires a remote repository on GitHub.

## New empty folder on the local computer
Go to the local repository.
```
Git Command:
$ cd "/H/Udvikling/Git/Tutorial/Basic cloning"
This will change to the local repository
```
It is important to realize that you can use an arbitrary folder name, but is good practice to use the same folder name on both computeres.

Clone in to the new empty folder.
```
Git Command:
$ clone https://github.com/koklapperne/Basic-Cloning
This will download the remote to the local folder and create a local repository
```
## Existing local repository
This workflow is relevant if you work on the same project on two different local computers or if another person has to contribute to the project in a simple way.

Get the updated remote repository from GitHub
```
Git Command:
$ cd "/H/Udvikling/Git/Tutorial/Basic cloning"
This will change to the local repository
$ git Pull
This will download the updated repository from GitHub AND merge it with it with the local repository. It is important to realize that Git Pull is a Git Fetch command followed by a Git Merge command.
```
