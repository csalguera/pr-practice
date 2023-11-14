# Pull Requests

### Fork Repo

1. Fork repo to contribute changes to.
2. Clone forked repo to machine.

```
git clone <repository>
```

---

### Add Upstream

1. Add an upstream to the repository that was forked.

```
git remote add upstream <repository>
```

---

### Work in Branches

1. Create a separate branch to work on.

```
git branch <branch-name>
```

2. Change to newly created branch.

```
git checkout <branch-name>
```

Alternatively, achieve both in single command:

```
git checkout -b <branch-name>
```

---

### Submit Pull Request

1. Navigate to forked repository in GitHub.
2. Compare & pull request
3. Create pull request

---

### Pull from Upstream

1. Change back to main branch.

```
git checkout main
```

2. After changes have been merged, pull changes from upstream.

```
git pull upstream main
```

3. Sync forked repository in GitHub to reflect the recent changes made.