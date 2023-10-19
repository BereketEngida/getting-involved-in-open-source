# Git

git it is a version control system that allows you to track changes, collaborate with others, undo mistakes and manage code history.

## Common Git Operations

[Staging] -> [Commit] -> [Push]

**Staging**
preparing our changes to be committed. The "." is to specify to stage the whole directory.

```sh
git add
```

**Committing**
we're committing the changes we made to the git history. the `-m "init"` is to specify a commit message.

```sh
git commit -m "init"
```

**Push**
we're pushing the changes to remote repository.

> repository is a directory that's hosted in places like github.

```sh
git push
```

## Git Ignore

It's a file that tells git to ignore some files form the version control system.
