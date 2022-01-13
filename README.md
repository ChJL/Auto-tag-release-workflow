# Auto-tag-release-workflow
A workflow that contains two seperate actions calling reusable workflows.

* caller.yml: main workflow that call the reusable workflows
* git_tag.yml: auto tagging by git commit message
* git_release.yml: auto releasing using input tag and changelog
