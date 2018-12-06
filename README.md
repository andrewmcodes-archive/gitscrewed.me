# gitscrewed.me

## Change last commit

### Docs

- [Change commit message](https://help.github.com/articles/changing-a-commit-message/)

### Message

```bash
git commit --amend
# follow prompts
```

## Rebase

### Docs

- [Keep fork up to date](https://robots.thoughtbot.com/keeping-a-github-fork-updated)

### The things

#### Long form

```bash
git checkout master
git pull
git checkout my-branch
git pull --rebase
```

#### With ZSH alias

```bash
gco master
gl
gco -
gup origin master
```

## Branch

### Docs

- [New branch](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)

### New

#### Long form

```bash
git checkout -b new-branch-name
```

#### With ZSH alias

```bash
gcb new-branch-name
```

### Remote

#### Docs

- [Adding a remote](https://help.github.com/articles/adding-a-remote/)

#### Long form

```bash
git remote add upstream https://github.com/user/repo.git
```

#### With ZSH alias

```bash
gra upstream https://github.com/user/repo.git
```
