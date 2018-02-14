# git-hooks

## update

This GIT hook checks commit messages while pushed to the server. We use refs and fixes keywords
in Redmine to link issues with commits.

The format should be `[refs|fix] #ID: message`

You have to specify **redmine_host** and **redmine_apikey** in the script, because it also checks
whether the issue exists.