# Contributing

Thank you for your interest in contributing to this project! There are a few
ways you can help it grow.

## Issues

### Bug reports

If you find a bug in the project that hasn't yet been reported, please open a
[bug report][bug], and I'll do my best to resolve it as quickly as I can.

### Feature requests

You're welcome to open a [feature request][feature] if you've got ideas how to
improve the project! As a lone developer, I can't always promise that I'll be
able to implement it, but I'll do my best to respond with my thoughts.

### Security advisories

If you have a security concern or are aware of a vulnerability affecting this
project, please report it by opening a [security advisory][advisory].

## Pull Requests

Pull requests are always appreciated! If you feeling up to it, I encourage you
to fix bugs and implement features yourself. I'm always open to code
contributions and am grateful for *your* help to make this project even better!

## Style

In order to maintain consistency within this project, I'd ask that you adhere to
the following style guidelines when contributing code. For a more detailed
project-specific style guide, check if this repository has a dedicated style
guide at [`STYLE.md`][style].

### Code

Please take care to ensure your contributions match the coding style of the
project. Where applicable, please use relevant linting and formatting tools as
configured by the project to help maintain consistent code quality.

- **Comment your code generously, but not redundantly.** Comments shouldn't be
  necessary when introducing common programming constructs (`// this is a
  variable`), but at the same time code is not always
  [self-documenting][selfdoc]. Clearly indicate how business logic works. I
  generally agree with Stack Overflow's [best practices for writing code
  comments][comments].
  - For readability, try to trim longer comments to an 80 characters-per-line
    limit. While I'm pretty sure no-one's contributing to this project using
    [punch cards][cards], keeping comment paragraphs limited makes it easier to
    prevent text wrapping horrors from occurring in split panes. (Yes, I know
    [this is controversial][lmkl].)
- **Prefer readable to clever-yet-obscure logic.** I get that it's fun to show
  off, but that doesn't help with ensuring a maintainable and future-proof code
  in the long run.
- **Avoid refactoring *alongside* other changes as part of your PR.** Good code
  architecture is challenging to get right, especially considering the evolving
  requirements of a project. If you have ideas for how to improve the existing
  code structure, feel free to implement that in a separate PR and/or [open an
  issue][issue] discussing the proposed changes.

### Git

In order to make it easier to review contributions, please adhere to best
practices when choosing your commit messages.

<i align="center">

  ![xkcd1296]

</i>

- **Commits should be atomic.** Each commit should encapsulate a single change.
  Altogether, the commits for each PR should fix a single bug or implement a
  single feature.
- **Commit messages should be informative.** (OR don't leave overly general
  commit messages.) While it's tempting to just [`git commit -m "hmm"`][hmm] and
  call it a day, please take the time to describe what changed in each commit.
- **Match the style of commits within the project.** In general, I try to use
  the [Conventional Commits][commits] specification for simple and clear commit
  messages. If more details are needed, use multiline commit messages as needed.
  - For readability, try to trim longer multiline commit messages to git's
    default 72 character limit.

## Credit

If we worked on it together, you deserve credit for it too! Please do proudly
take credit for your contributions. It's because of people like *you* that
open-source software is what it is today.

<!-- Reference-style links -->

[advisory]: /../../security/advisories/new
[bug]:      /../../issues/new?assignees=&labels=&projects=&template=bug_report.md&title=
[cards]:    https://softwareengineering.stackexchange.com/a/148729
[comments]: https://stackoverflow.blog/2021/12/23/best-practices-for-writing-code-comments/
[commits]:   https://www.conventionalcommits.org
[feature]:  /../../issues/new?assignees=&labels=&projects=&template=feature_request.md&title=
[hmm]:      https://www.redbubble.com/i/t-shirt/git-commit-m-hmm-by-errada222/127492509.NL9AC
[issue]:    /../../issues/new
[lmkl]:     https://lkml.org/lkml/2020/5/29/1038
[selfdoc]:  https://en.wikipedia.org/wiki/Self-documenting_code
[style]:    /STYLE.md
[xkcd1296]: https://imgs.xkcd.com/comics/git_commit.png
