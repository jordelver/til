---
date: "2022-05-06"
title: Something something
subtitle: Something
---
You can create a branch in git that shares not history at all.

    git checkout --orphan <name_you_choose_for_orphan_branch>

This is generally a weird thing to want to do, but can come in handy.
You can restrict a workflow in GitHub Actions to only apply to a certain branch,
I think most people are aware of that, but you can also make it only apply to
paths too.

  on:
    push:
      branches:
        - master
      paths:
        - 'include-me/**'
