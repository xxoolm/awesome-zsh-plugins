# Contributing

First and foremost, thanks for the help, I appreciate all of the contributions, and the awesome-zsh-plugins list wouldn't be nearly as complete without them. You may add to the list by submitting a pull request or adding a link in an issue.

I want to be clear that real, useful PRs are always welcome. _But_ if you came here just to make a useless PR because you watched that idiot CodeWithHarry's youtube video, _I will report it to DigitalOcean_, you will be disqualified from Hacktoberfest and you won't get the free stuff you're trying for._

## Entry Guidelines

### General

- Please make sure all new framework, plugin, themes or completions entries have a license file. Some users are particular about the code they use and want to be sure they are compliant with licensing, so please make sure it's easy for them to determine what the license is. I am aware that there are existing entries without licenses, they were added before I instituted the license policy.

- Please make sure new entries have a readme. While obviously it's good to read the source code for things we're adding to our environment, it's even better if users can get an overall idea of what a plugin does so they know if it is even potentially useful to them first.

- Descriptions should be clear, concise, and non-promotional.

- The list is split into sections for frameworks, plugins, themes and completions, please add your entries to the appropriate section(s). If an entry is a plugin that provides both plugin functionality and tab completions, add it to the plugins section. If an entry is a plugin that provides both plugin functionality and a theme, please add it to the theme section. The completions section is meant for projects that only provide extra tab completions.

- Descriptions should follow the link, on the same line, with capitalization consistent with the other entries in the section.

- Each entry should be a single line that ends in a period. This makes keeping the sections sorted easier.

- Plugin, theme and completions entries _must_ be a single line and be added in alphabetical order in their respective sections of the list. We let GitHub's markdown formatter handle adding any required line breaks rather than embedding line breaks in the entries ourselves, this also allows us to work correctly with any browser window width.

- For consistency, please use all caps for ZSH in all entry descriptions.

- Each entry should be limited to one link, and that link should be the first part of the line. It is ok to submit more than one entry in a PR.

- Please make sure all framework, plugin, themes or completions list entries are sorted _alphabetically_.
- The link should be named the name of the package or project. Please remove any leading or trailing `zsh-plugin`, `zsh-theme` from the visible portion of the link.

- Your PR should pass the Github Action checks. If the checks show an error that you didn't add (a previous plugin entry has gone 404, for example) you don't _have_ to fix those errors, though I'll certainly appreciate the help if you do, or if you create an issue documenting the problem so I can fix it.

### Themes

- If you're submitting a theme, please make sure that the theme repo has a screen shot so that list users can tell what it looks like before installing it.

- It is fine to have multiple new entries in a single PR. Just make sure they all have readmes and licenses, and screenshots for theme entries.

- No need to squash commits. It is fine to have multiple commits in a PR.

## To remove an entry

Open an issue to discuss why the entry should be removed, and optionally create a PR.

Entries that have gone 404 do not require an issue to remove - just make a PR.
