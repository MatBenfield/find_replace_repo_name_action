# find and replace repo name action

A GitHub action to swap out a placeholder text in your documentation with the Repo name.

I found when creating new repositories I would default copy and past an existing repositories documentation files like contributing, code-of-conduct, issue templates and such any links within these would break and need updating.

I wanted to create a github action that would search the repo for markdown files and replace a placeholder e.g. `repo_url` with the actual repo url held within the `$github` namespace

As such this action will commit files in your repo on your behalf.
