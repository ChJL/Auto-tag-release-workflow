# Auto-tag-release-workflow
A workflow that contains two seperate actions calling reusable workflows.

* [caller.yml](https://github.com/ChJL/Auto-tag-release-workflow/blob/main/.github/workflows/caller.yml): main workflow that call the reusable workflows
* [git_tag.yml](https://github.com/ChJL/Auto-tag-release-workflow/blob/main/.github/workflows/git_tag.yml): auto tagging by git commit message (reusable)
* [git_release.yml](https://github.com/ChJL/Auto-tag-release-workflow/blob/main/.github/workflows/git_release.yml): auto releasing using input tag and changelog (reusable)
