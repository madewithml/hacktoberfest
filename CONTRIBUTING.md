# Contribution Guide

**Please, follow these steps**

## Step 1: Forking this repo

​1. Fork the repo to your own github account. click the Fork button to
create your own repo copy under your GitHub account. Once forked, you're
responsible for keeping your repo copy up-to-date with the upstream
repo.

​2. Download a copy of your remote username/hacktoberfest repo to your
local machine. This is the working directory where you will make
changes:

```bash
$ git clone https://github.com/madewithml/hacktoberfest.git
```

3.  Install the requirments. You many use miniconda or conda as well.

```bash
$ pip install -r requirements.txt
```

## Step 2: Stay in Sync with the original (upstream) repo

1.  Set the upstream to sync with this repo. This will keep you in sync
    with hacktoberfest easily.

```bash
$ git remote add upstream https://github.com/madewithml/hacktoberfest.git
```

2.  Updating your local repo: Pull the upstream (original) repo.

```bash
$ git checkout master
$ git pull upstream master
```

## Step 3: Creating a new branch

```bash
$ git checkout -b feature-name
$ git branch
 master
 * feature_name:
```

## Step 4: Make changes, and commit your file changes

Edit files in your favorite editor.

```bash
# View changes
git status  # See which files have changed
git diff    # See changes within files

git add path/to/file
git commit -m "Your meaningful commit message for the change."
```

Add more commits, if necessary.

## Step 5: Submitting a Pull Request

Push your changes to MadewithML.

```bash
git push
```

After the push completes, a message may display a URL to automatically
submit a pull request to the upstream repo. If not, go to the
hacktoberfest main repo and GitHub will prompt you to create a pull
request.

## Step 6. Confirm PR was created:

Ensure your pr is listed
[here](https://github.com/madewithml/hacktoberfest/pulls)

-  Updating a PR:

Same as before, normally push changes to your branch and the PR will get
automatically updated.

```bash
git commit -m "updated the feature"
git push origin <enter-branch-name-same-as-before>
```

* * * * *

## Reviewing Your PR

Maintainers and other contributors will review your pull request. Please
participate in the discussion and make the requested changes. When your
pull request is approved, it will be merged into the upstream
hacktoberfest repo.

