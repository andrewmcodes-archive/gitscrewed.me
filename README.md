# gitscrewed.me

## Change last commit

### Message

```bash
git commit --amend
# follow prompts
```

## Rebase

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

### New

#### Long form

```bash
git checkout -b new-branch-name
```

#### With ZSH alias

```bash
gcb new-branch-name
```
