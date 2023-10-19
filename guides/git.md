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

**Remote**
We're adding a remote so we can push to that remote codebase so other can collaborate.

```sh
git remote add origin https://github.com/bekacru/getting-involved-in-open-source
```

we're doing this once so we can set our main local to track the remote main branch.

```sh
git branch --set-upstream-to=origin/main main
```

## Git Ignore

It's a file that tells git to ignore some files form the version control system.
