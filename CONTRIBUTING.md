
# Contributing

To get started, fork the repo to your account and then clone your fork:
```bash
git clone https://github.com/yourusername/Collections-C.git
```
Now you can start working on the project. 

* if you're planing to work on some major new feature, you might want to open an issue first so that it can discuss it.
* If you are writing code, you should follow the code [fomatting style](https://en.wikipedia.org/wiki/Indent_style#K.26R_style). 
* Major changes should go into the development branch.



After you're done with your work, you should make sure that the tests are passing with:
```bash
make check
```
Commit your work and push it to your fork.

You can then open a [pull request](https://help.github.com/articles/using-pull-requests/) from your fork to the upstream repository. After the pull request is made, we will comment / review it and might also suggest some changes. After all that is done, the pull request is merged.

## Synchronizing the fork with the upstream
You might have forked the repository a while ago, and in the meantime some changes were added to the upstream repository. Now if you want to send a Pull Request you might run into merge issues. To solve this issue make sure you have your fork synchronized with the upstream repository before you make any changes. 

To synchronize your fork, you first need to clone if you don't already have a local copy:
```bash
git clone https://github.com/yourusername/Collections-C.git
```
then add the upstream repository as a remote:
```bash
git remote add upstream https://github.com/srdja/Collections-C.git
```
finally pull from the upstream into your local master branch
```bash
git pull upstream master
```
In case you have already done some work you might want to `fetch` instead of `pull`
```bash
git fetch upstream
```
and once you sort out your current work, merge it into you master branch
```bash
git merge upstream/master
```

## Finding something to work on
There is always something to work on, be it fixing bugs, writing documentation or adding cool new features. You can start by looking through the [issues](https://github.com/srdja/Collections-C/issues) to find something intereseting.
If you have a cool new idea, or you've found a bug and there is no issue for it, go ahead and open a [new issue](https://github.com/srdja/Collections-C/issues/new) for it.

If you're just starting out, look for issues with a [low-hanging fruit](https://github.com/srdja/Collections-C/issues?q=is%3Aissue+is%3Aopen+label%3A%22low-hanging+fruit%22) tag. These issues should be fairly easy to fix, and they are also a good starting point for contributing.
