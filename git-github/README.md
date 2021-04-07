# Git and GitHub Workshop Syllabus

- [Git and GitHub Workshop Syllabus](#git-and-github-workshop-syllabus)
  - [Introduction](#introduction)
    - [Instructor](#instructor)
    - [Git](#git)
      - [Install](#install)
      - [Setup](#setup)
    - [GitHub](#github)
      - [Create Account](#create-account)
  - [Markdown](#markdown)
    - [Editor setup](#editor-setup)
      - [VS Code](#vs-code)
      - [Online](#online)
    - [First markdown file](#first-markdown-file)
    - [Common Syntaxes](#common-syntaxes)
  - [Git basic commands](#git-basic-commands)
  - [Your first GitHub repo](#your-first-github-repo)
  - [GitHub Developer Profile](#github-developer-profile)
  - [Collaborate on Friend's project](#collaborate-on-friends-project)
  - [Working on Open Source project](#working-on-open-source-project)

<hr>

## Introduction

[Git](https://git-scm.com/) is one of the powerful tool to manage your source code effectively and has been extensively used in many IT companies.

[GitHub](https://github.com) is one of the popular and free platform to host your project repositories.

In this hands-on workshop, you’ll learn from _building your GitHub developer portfolio_ to basic _Git commands_ and manage the project source code.


#### Install

- Open [Git Downloads](https://git-scm.com/downloads).
- Download the latest binary as per your Operating System(OS).
#### Setup

After downloading and installing Git, setup your local Git identity.

NOTE: Git commit uses this information in every commit.

```shell
$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.com
```

Other optional configurations are:

```shell
# Configure the Git text editor to Vim or other
# Else system's default text editor is used
$ git config --global core.editor vim
```

Consider checking your settings as:

```shell
$ git config --list
user.name=John Doe
user.email=johndoe@example.com
color.status=auto
color.branch=auto
color.interactive=auto
color.diff=auto
...
```

Or check specific configuration as:

```shell
$ git config user.name
John Doe
```

### GitHub

GitHub is a hosting provider for software development and version control using Git. It offers the _distributed version control and source code management (SCM)_ functionality of Git, plus its own features.
It provides _access control and several collaboration features such as bug tracking, feature requests, task management, continuous integration and wikis for every project._ Read more [here](https://en.wikipedia.org/wiki/GitHub).

#### Create Account

- Click on the [Join link](https://github.com/join).
- Enter the required details and solve puzzle.
- Click on `Create Account`.
## Markdown

Markdown is a lightweight markup language that we can use to add formatting elements to plaintext text documents. It is created by _John Gruber_ in 2004 and now one of the world’s most popular markup languages.

### Editor setup

To work effectively with Markdown, you can use various tools to quickly write markdown content.
#### VS Code

For VS Code, you can able to preview the markdown content by installing the extension `Markdown Preview Enhanced`.

Install the extension as follows:

- Click on extensions icon on leftmost panel or press shortcut keys `Shift + Ctrl (cmd) + P` and then click `Install Extensions`.
- Under the extensions panel, search for `Markdown Preview` by `Yiyi Wang`.
- Click and install it.
- Use `Ctrl + k, v` to see the preview of the markdown file.

#### Online

You can also use the online tool to write markdown content and view its preview - https://markdownlivepreview.com/.

### First markdown file

Create a file in VS Code with name `helloworld.md` and type the following content:

```md
# Hello World

This is the hello world markdown file.
```

You should be able to see following:

![Hello World](./images/helloworld.jpg)

### Common Syntaxes

Go through with following syntaxes:
- Headers
- Links
- Text formatting: emphasis, strong, strong-emphasis
- Unordered and ordered list
- Blockquote
- Inline and Code blocks
- Image
- HTML Code

Read more [here](https://www.markdownguide.org/basic-syntax).

## Git basic commands

Go through with following important git commands:

- `git status`
- `git add`
- `git commit`
- `git log`
- `git pull`
- `git push`
- or others as necessary
## Your first GitHub repo

Considering you are logged in your GitHub account, perform the following:

- Click on the plus icon before the profile pic at top right of the page. (or click [here](https://github.com/new))
- Give a valid repo name (__eg:__ give your `username` in the repository name)
- Add description of the repository.
- Make it public to available for all user or private for personal or team
- Choose adding `README`, `.gitignore` or `licencse` as necessary. [Optional]
## GitHub Developer Profile

- In your browser, under GitHub login, create a repo with username
- Choose `public` and then click on `Create Repository` button.
- In your VS Code or editor, create a folder with your GitHub username.
- Create a file `README.md` under the above folder.
- Type following in the `README.md`:

  ```md
  # Hi there :wave:

  My name is <add your name> and currently pursuing <degree name>.

  ## Area of interests are:
  - Web Development
  - Machine Learning
  - Cyber Security
  - ...

  ## Achievements
  - Foo hackathon winner
  - Best coder in the college
  - ...

  NOTE: Write your own version of introduction.
  ```

- Add the changes `git add .`
- Write commit as `GitHub profile initial commit`
- From browser, copy the code under section __"or push an existing repository from the command line"__ which looks like below:

  ```shell
  git remote add origin git@github.com:<your username>/<your username>.git
  git branch -M main
  git push -u origin main
  ```
- See your GitHub profile in your github account.
## Collaborate on Friend's project

- Importance of `.git/config` file.
- Importance of `.gitignore` file.
- Upstream-downstream concept
- Local or Remote concept
- Push to remote concept
## Working on Open Source project

Show the demo of working in Open Source project.
