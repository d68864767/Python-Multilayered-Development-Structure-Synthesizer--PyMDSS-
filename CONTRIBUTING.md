# Contributing to Python Multilayered Development Structure Synthesizer (PyMDSS)

First off, thank you for considering contributing to PyMDSS. It's people like you that make PyMDSS such a great tool.

## Where do I go from here?

If you've noticed a bug or have a feature request, make sure to open an Issue about it! We can't fix what we don't know about.

## Fork & create a branch

If this is something you think you can fix, then fork PyMDSS and create a branch with a descriptive name.

A good branch name would be (where issue #325 is the ticket you're working on):

```bash
git checkout -b 325-add-japanese-localisation
```

## Implement your fix or feature

At this point, you're ready to make your changes! Feel free to ask for help; everyone is a beginner at first.

## Get the code

The first thing you'll need to do is get our code onto your local machine. The easiest way to do this is to fork the repository and then clone your fork:

```bash
git clone https://github.com/your-username/PyMDSS.git
```

## Make a Pull Request

At this point, you should switch back to your master branch and make sure it's up to date with the latest PyMDSS master branch:

```bash
git remote add upstream https://github.com/original-owner-username/PyMDSS.git
git checkout master
git pull upstream master
```

Then update your feature branch from your local copy of master, and push it!

```bash
git checkout 325-add-japanese-localisation
git rebase master
git push --set-upstream origin 325-add-japanese-localisation
```

Finally, go to GitHub and [make a Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request) :D

## Keeping your Pull Request updated

If a maintainer asks you to "rebase" your PR, they're saying that a lot of code has changed, and that you need to update your branch so it's easier to merge.

To learn more about rebasing in Git, there are a lot of [good](https://git-scm.com/book/en/v2/Git-Branching-Rebasing) [resources](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase) but here's the suggested workflow:

```bash
git checkout 325-add-japanese-localisation
git pull --rebase upstream master
git push --force-with-lease origin 325-add-japanese-localisation
```

## What if my Pull Request gets rejected?

Don't despair! The great part about contributing to open source projects is that there are always more ways to contribute. Try to find another issue you can help with and give it another go.

## Thank you for your contributions!

We're really glad you're reading this, because we need volunteer developers to help this project come to fruition. Thank you for all your help!
