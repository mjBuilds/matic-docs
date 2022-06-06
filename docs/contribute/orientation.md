---
id: orientation
title: Contributing to Polygon Docs
description: We believe one of the things that makes Polygon special is its coherent design and we seek to retain this defining characteristic.
keywords:
  - docs
  - matic
image: https://matic.network/banners/matic-network-16x9.png 
---

## **Why to Contribute to Polygon Docs?**

There are **numerous reasons** for this!
- **Develop Skill**: It solidifies your knowledge base if you are learning about Polygon, and Web3 in general.
- **Proof of Work**: Your contribution will be a proof of your work, skills, and knowledge to potential employers.
- **Sense of Achievement**: Identifying and resolving problems gives a great sense of accomplishment on a personal level.

## **What to Contribute?**
Any contribution, big or small, is appreciated! You can identify your area of contribution which may include, but not restricted to:
  - **Docs**:  
    - Grammar
    - Typos
    - Tone and clarity
    - Translation
  - **Design**:  
    - Content structure and layout
    - Intuitive designs to make docs more appealing

In addition to the above list, there are more ways to identify an area where you can contribute to Polygon:
  - The easiest is just to email one of the [Community Maintainers](/docs/contribute/community-maintainers) saying “I want to help!”. They’ll work with you to find an area for you to contribute
  - If you have a specific contribution in mind, confirm whether the contribution is appropriate first by reaching out in Polygon Telegram group or contacting one of the [Community Maintainers](/docs/contribute/community-maintainers) directly
  - If you do not have a specific contribution in mind, you can also browse the issues labelled as `help wanted` on the [Polygon GitHub repos](https://github.com/maticnetwork)
  - Issues that additionally have the `good first issue` label are considered ideal for first-timers

## **How to Contribute to Polygon Documentation?**
If you are new to GitHub and open-source contribution, do not worry! We will help you get started.
- **Step 1:** 
Read [How to Contribute to Polygon Docs](https://github.com/maticnetwork/matic-docs#how-to-contribute-to-polygon-wiki). It specifically guides you on how to contribute to Polygon Docs. 
:::info 
You can also refer to **[First Contribution](https://github.com/firstcontributions/first-contributions#first-contributions)** to understand how to contribute to open-source projects.
:::
- **Step 2:** 
If you need to add, or change anything in **Polygon** Documentation, raise a `PR` to the `master` branch.  
See [Sample PR](https://github.com/maticnetwork/matic-docs/pull/360) for your reference.

- **Step 3:** 
Polygon team will review the `PR`, or reach out accordingly.  
Link to the Polygon doc repository: https://github.com/maticnetwork/matic-docs
  > If you are adding a new document, it is recommended to just have a basic summary/introduction and a link to your github or documentation for more details.

## **Contribution Guidelines**

We believe one of the things that makes Polygon special is its coherent design and we seek to retain this defining characteristic. From the outset we defined some guidelines to ensure new contributions only ever enhance the project:

- **Quality**: Code in the Polygon project should meet the style guidelines, with sufficient test-cases, descriptive commit messages, evidence that the contribution does not break any compatibility commitments or cause adverse feature interactions, and evidence of high-quality peer-review
- **Size**: The Polygon project’s culture is one of small pull-requests, regularly submitted. The larger a pull-request, the more likely it is that you will be asked to resubmit as a series of self-contained and individually reviewable smaller PRs
- **Maintainability**: If the feature will require ongoing maintenance (eg support for a particular brand of database), we may ask you to accept responsibility for maintaining this feature

### Git Rules

We use `gitchangelog` for all of our repos for change logs. For that, we need to follow the following convention for commit message. There will be no merge if you are not following this convention.

**Commit Message Convention**

The following are suggestions to what might be useful to think about adding in your commit messages. You might want to separate roughly your commits into big sections:

- by intent (for example: new, fix, change ...)
- by object (for example: doc, packaging, code ...)
- by audience (for example: dev, tester, users ...)

Additionally, you could want to tag some commits:

- as “minor” commits that shouldn’t get output to your changelog (cosmetic changes, small typo in comments...)
- as “refactor” if you don’t really have any significative feature changes. Thus this should not also be part of the changelog displayed to final user for instance, but might be of some interest if you have a developer changelog.
- you could tag also with “api” to mark API changes or if it's a new API or similar

Try writing your commit message by targeting user functionality as often as you can.

**Example**

This is a standard git log `--oneline` to show how these information could be stored:

```
* 5a39f73 fix: encoding issues with non-ascii chars.
* a60d77a new: pkg: added ``.travis.yml`` for automated tests. 
* 57129ba new: much greater performance on big repository by issuing only one shell command for all the commits. (fixes #7)
* 6b4b267 chg: dev: refactored out the formatting characters from GIT.
* 197b069 new: dev: reverse ``natural`` order to get reverse chronological order by default. !refactor 
* 6b891bc new: add utf-8 encoding declaration !minor 
```

For more info, please refer to [What Are Some Good Ways to Manage a Changelog Using Git?](https://stackoverflow.com/questions/3523534/good-ways-to-manage-a-changelog-using-git/23047890#23047890)

For more details, see [How to Write a Git Commit Message?](https://chris.beams.io/posts/git-commit/)
