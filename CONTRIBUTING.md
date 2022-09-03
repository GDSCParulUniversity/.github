# Hi there 👋
Thanks for taking the time to contribute to this org! 🎉. this page helps you get started with contributing to this org. 🚀

## Table of Contents
- [Hi there 👋](#hi-there-)
  - [Table of Contents](#table-of-contents)
  - [Quick intro with `git`](#quick-intro-with-git)
    - [Cloning a repository](#cloning-a-repository)
    - [Initializing repository](#initializing-repository)
    - [Submitting changes](#submitting-changes)

<hr/>

## Quick intro with `git`
Here is a quick intro for github users who are not familiar with git.

### Cloning a repository
To clone a repository, you need to copy the url of the repository and then run the following command:
```bash
git clone <link>
```

> replace `<link>` with the url of the repository

### Initializing repository
to initialize a folder or a workspace as a git repository, you can use the following command:
```bash
git init
```

> Make sure you are in the right folder before running this command.
> Only used when creating **new** repository

### Submitting changes
after making changes to file you can use this set this commands to push chages to GitHub server.

```bash
git pull -v
git add -A
git commit -v -m "Changes to repo"
git push
```

<details>
    <summary> Code Explanation </summary>

Here is a quick explanation of above commands

```bash
git pull -v
```

this option will `pull` the latest changes from the server and merge them with your local changes.

and option `-v` is optional and it will show you the changes that are being pulled.

```bash
git add -A
```

`add` option will add all the changes to the staging area and option `-A` is set to add all the changes.

```bash
git commit -v -m "Changes to repo"
```

`commit` option will commit the changes to the local repository and option `-v` is optional and it will show you the changes that are being committed.

and option `-m` is used to add a message to the commit.

> messages are important to a commit cause it explains what changes are being made.

```bash
git push
```

`push` option will push the changes to the github server.

</details>

> refer [GitHub HelloWorld docs](https://docs.github.com/en/get-started/quickstart/hello-world) for a quick intro with github web


