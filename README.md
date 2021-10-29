Link to my blog : [Contribution to Open Source is EASY!](https://souvikrajsingh.hashnode.dev/contributing-to-open-source-is-easy)

This repository is for a hands-on practise of contributing to a open-source project. For your practise you can see I have added a text file (names.txt) 
where all you need to do is add your name, github username, twitter username.

### How to contribute

1. Fork the project
2. Make any changes in your forked repository
3. On this repo, click `Pull Requests` and raise a `Pull Request` selecting your fork on the right drop down


### How to clone repo and make changes locally

```
  click on the clone button (green in colour). This gives you a copy of the project. Its now yours to play around with
```

- Using git on your local machine. Do this to download the forked copy of this repo to your computer

```
  git clone https://github.com/souvikrajsingh/hashnode-patch1.git
```

- switch to the cloned folder. This can be done with Gitbash or the integrated terminal in the VSCode editor

```
  cd hashnode-patch1
```

- Make a new branch. Your name would make a good branch because it's unique

```
  git checkout -b <name of new branch>
```

- Make Required changes using the Tec-Stacks mentioned above

- Stage your changes

```
  git add <file-name>
```

or

```
  git add .
```

- Commit the changes

```
  git commit -m "Add <what changes you made>"
```

- Check the status of your repository

```
  git status
```

- Pushing your repository to github

```
  git push origin <name of your branch>
```

or

```
  git branch -M main
  git push -u origin main
  git push origin main --force
```

- Navigate to your fork, on the top of the files section you'll notice a new section containing, a contribute button!
- Click on the contribute button, it will open a drop down, click the pull request button on the drop down
  Note: A pull request allows your changes to be merged with the original project.

- Wait for your changes to be merged

Hurray! You successfully made a contribution! 🎉


