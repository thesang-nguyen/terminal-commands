# git commands:

## STATUS:
shows the tracked and untracked files, committed and uncommitted changes etc. 

	git status

## ADD:
adds a file to be tracked

	git add <file_name>

## COMMIT:
add files as a commit, i.e. version

	git commit -m "<commit message>"

conventional commit messages: 

```
"<type>(optional scope): <description>"
types: fix, feat, BREAKING CHANGE, refactor, test
more: https://www.conventionalcommits.org/en/v1.0.0/
```

## PUSH:
uploads the commits to the remote 

	git push

## SWITCH branches:
	git switch <branch_name>

## DELETE branch locally:
	git branch -d <local_branch_name>

Remark: switch to a different branch first before deletion

## DELETE branch remotely:
	git push origin --delete <remote_branch_name>

## CREATE repo from existing folder
1. In terminal:

```
git init
git add .  # or alternatively all the filenames instead of the dot
git commit -m "initial commit"
```

2. Create repo on github.com with the same name as the folder:
Follow all the steps there.

## CONFIG:
	git config -l
	git config --global user.name "<username>"
	git config --global user.email "<email address>"

	git config --global credential.helper cache
	git config --global --unset credential.helper
