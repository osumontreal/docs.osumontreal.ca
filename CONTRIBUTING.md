# Contributing to Open Science UMontreal

Welcome to official Documentation repository of the Open Science UMontreal
(OSUM) community. We are excited you are here and want to contribute!

These guidelines are designed to make it as easy as possible to get involved. If
you have any questions that aren't discussed below, please let us know by
opening an [issue](https://github.com/osumontreal/docs.osumontreal.ca/issues)!

Before you start you'll need to set up a free [GitHub](https://github.com)
account and sign in. You can sign up
[through this link](https://github.com/join) and then _interact_ with our
repositories at
[https://github.com/OSUMontreal](https://github.com/OSUMontreal).

Already know what you're looking for in this guide? Jump to the following
sections:

- [Contributing to Open Science UMontreal](#contributing-to-open-science-umontreal)
  - [Don't know where to get started?](#dont-know-where-to-get-started)
  - [Joining the conversation](#joining-the-conversation)
  - [Contributing small documentation changes](#contributing-small-documentation-changes)
  - [Recommended workflow when contributing through GitHub](#recommended-workflow-when-contributing-through-github)
    - [1. Open a new issue or comment on an existing one](#1-open-a-new-issue-or-comment-on-an-existing-one)
    - [2. Fork the docs.osumontreal.ca repository](#2-fork-the-docsosumontrealca-repository)
    - [3. Work on your branch and Test it](#3-work-on-your-branch-and-test-it)
    - [4. Check list](#4-check-list)
    - [5. Submit and tag your pull request](#5-submit-and-tag-your-pull-request)
  - [Recognizing your contribution](#recognizing-your-contribution)
  - [Thank you!](#thank-you)

## Don't know where to get started?

Read [Joining the conversation](#joining-the-conversation) and pop into our
[Matrix Chat](https://chat.openscience.ca) to introduce yourself and tell us how
you would like to contribute in the OSUM community! Let us know what your
interests are and we will help you find an issue to contribute to. Thanks so
much!

## Joining the conversation

`OSUM` is a young communnity project maintained by a growing group of
enthusiastic early-career researchers, mainly student. We're excited to have you
join! Most of our discussions will take place on open [issues][link_issues]. We
also maintain a [Matrix Chat](https://chat.openscience.ca) for more informal
conversations and general updates.

There is significant cross-talk between these two spaces, and we look forward to
hearing from you in either venue! As a reminder, we expect all contributions to
`OSUM` to adhere to our [code of conduct](https://osumontreal.ca/en/coc).

## Contributing small documentation changes

If you are new to GitHub and just have a small documentation change
recommendation, you can submit it to
[our e-mail address](mailto:info@osumontreal.ca) and one of our developers will
add it to the documentation directly.

## Recommended workflow when contributing through GitHub

[Git](https://git-scm.com/) is a really useful tool for
[version control](https://en.wikipedia.org/wiki/Version_control).
[GitHub](https://github.com) sits on top of git and supports collaborative and
distributed working.

You'll use [Markdown][markdown] to discuss on GitHub. You can think of Markdown
as a few little symbols around your text that will allow GitHub to render the
text with a little bit of formatting. For example you can write words as
**bold** (`**bold**`), or in _italics_ (`*italics*`), or as a
[link](https://youtu.be/dQw4w9WgXcQ) (`[link](https://youtu.be/dQw4w9WgXcQ)`) to
another webpage.

GitHub has a helpful guide to
[get you started with writing and formatting Markdown](https://guides.github.com/features/mastering-markdown/).

We will be excited when you'll suggest a new PR to fix improve In order to make
this as fluid as possible we recommend to follow this workflow:

### 1. Open a new issue or comment on an existing one

Issues are individual pieces of work that need to be completed to move the
project forwards. Before starting to work on a new pull request we highly
recommend you open an issue to explain what you want to do and how it echoes a
specific demand from the community. If you have more an inquiry or suggestion to
make than a bug to report, we encourage you to come and chat with us in the
[#dev:openscience room](#dev:openscience.ca).

A general guideline: if you find yourself tempted to write a great big issue
that is difficult to describe as one unit of work, please consider splitting it
into two or more. Moreover, it will be interesting to see how others approach
your issue and give their opinion and maybe give you advice to find the best way
to code it. Finally, it will prevent you to start working on something that is
already in progress.

### 2. Fork the [docs.osumontreal.ca repository](https://github.com/osumontrea/docs.osumontreal.ca)

When you fork This way you'll be able to work on your own instance of
`docs.osumontreal.ca`. It will be a safe place where nothing can affect the main
repository.

Once you have your own fork, you can clone it on you local computer by clicking
the green Clone button to get your own URL:

```bash
git clone --recurse-submodules https://github.com/YOURUSERNAME/docs.osumontreal.ca.git

cd docs.osumontreal.ca
```

Make sure to always
[keep your fork up to date](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/syncing-a-fork)
with the upstream repository before and after making changes. You can follow
these command lines to help you.

The first time you try to sync your
[fork](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-forks),
you may have to set the
[upstream branch](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork)

```bash
git remote add upstream https://github.com/osumontrea/docs.osumontreal.ca
git remote -v # Verify the new upstream repo appears.
```

```bash
git checkout main
git fetch upstream main
git merge upstream/main
```

Then create a new branch for each issue. Using a new branch allows you to follow
the standard GitHub workflow when making changes.
[This guide](https://git-scm.com) provides a useful overview for this workflow.
Please keep the name of your branch short and self explanatory.

```bash
git checkout -b MYBRANCH
```

### 3. Work on your branch and Test it

1. To preview the website, you will need to
   [install Hugo](https://gohugo.io/getting-started/installing) on your
   computer. Once installed, you can run the `hugo server -D` command and open
   `http://localhost:1313/` in a browser.

2. Modify some content or code
3. Make sure Hugo can generate the whole website by building it with the `hugo`
   command.

### 4. Check list

Pull Request Checklist (For Fastest Review):

- [x] Check that all tests are passing ("All tests passsed")
- [x] Make sure you note any issues that will be closed by your PR
- [x] Add a clear description of the purpose of you PR

### 5. Submit and tag your pull request

When you submit a pull request we ask you to follow the tag specification. In
order to simplify reviewers work, we ask you to use at least one of the
following tags:

- **[BRK]** for changes which break existing builds or tests
- **[DOC]** for new or updated documentation
- **[ENH]** for enhancements
- **[FIX]** for bug fixes
- **[TST]** for new or updated tests
- **[REF]** for refactoring existing code
- **[MAINT]** for maintenance of code
- **[WIP]** for work in progress

You can also combine the tags above, for example if you are updating both a test
and the documentation: [TST, DOC].

## Recognizing your contribution

We welcome and recognize all kinds of contribution from reporting bugs,
improving the documentation, testing our tools to code development.

## Thank you!

You're amazing. :wave: :smiley:

_&mdash; Based on contributing guidelines from the
[tedana](https://github.com/ME-ICA/tedana/blob/main/CONTRIBUTING.md) and
[STEMM Role Models](https://github.com/KirstieJane/STEMMRoleModels) projects._
