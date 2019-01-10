## Commit # between tags

```bash
git rev-list v1.0.0..v1.1.0 --count
```

## Show Remotes

```bash
git remote -v
```

## Squash N commits

```bash
#
git rebase -i HEAD~N
```

## Git log

```bash
git log master             # branch
git log origin/master      # branch, remote
git log v1.0.0             # tag
git log --oneline          # shorthand for --pretty=oneline --abbrev-commit together
git log --oneline -N --author andrewmcodes --before "Thu Mar 1 2018"
git shortlog               # groups commits by user, howing just the subject line for concision
git log --stat branch1 --not branch2 # show what is in one branch and not the other
git log --graph --all
```

## Revert

### Return to last committed state

```bash
git reset --hard
```

### Revert last commit

```bash
git revert HEAD
```

### Revert commit

```bash
git revert sha
```

## Diff

### Diff tracked files

```bash
git diff
```

### Diff specific commits

```bash
git diff sha1 sha2
```

## Blame

```bash
git blame filename
```

## Tag

### Tag a version

```bash
git tag v1.0.0
```

## Bisect

```bash
git bisect start # start bisect
git bisect good sha # last working commit
git bisect bad sha # broken commit
git bisect good/bad # mark commit as working or broken
git bisect reset # end bisect
```

## Branch

### Show last commit on each branch

```bash
git branch -v
```

## Cherrypick

### Cherrypick single commit

```bash
git cherry-pick sha
```

### Cherrypick multiple commits

```bash
git cherry-pick sha1 sha2
```

### Cherrypick merge

```bash
git cherry-pick -m 1 <hash>
```
