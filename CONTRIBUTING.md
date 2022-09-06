# Hi there 👋
We are overwhelmed to have you as a part of our community. Get started with contributing to this organization. You truly make a difference for us!  🎉

## Table of Contents
- [Hi there 👋](#hi-there-)
  - [Table of Contents](#table-of-contents)
  - [Quick intro with `git`](#quick-intro-with-git)
    - [Cloning a repository](#cloning-a-repository)
    - [Submitting changes](#submitting-changes)

<hr/>

## Quick intro with `git`
Here is a quick intro for GitHub users who are not familiar with git.

### Cloning a repository
for cloning repository `clone` option is used.
```bash
git clone <link>
```

> replace `<link>` with the URL of the repository

### Submitting changes

```bash
git pull -v
git add -A
git commit -v -m "Changes to repo"
git push
```

<details>
    <summary> Code Explanation </summary>

Here is a quick explanation of the above commands

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

`push` option will push the changes to the GitHub server.

</details>

> refer [GitHub HelloWorld docs](https://docs.github.com/en/get-started/quickstart/hello-world) for a quick intro with GitHub web
