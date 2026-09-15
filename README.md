# DebOps GitHub Pages

This repository serves the `https://debops.github.io/` page, the GitHub
organization site for [DebOps](https://debops.org/).

## Purpose

The page has two jobs:

1. **Mastodon verification.** The `rel="me"` links in the page head let
   Mastodon verify the account: the *GitHub* field on the
   [@debops@fosstodon.org](https://fosstodon.org/@debops) profile points at
   `https://debops.github.io/`, and the page links back to that profile
   (`<link rel="me" href="https://fosstodon.org/@debops">`). A green
   checkmark is shown once the link is verified.

2. **Redirect.** Visitors are redirected (via a meta refresh, the only
   redirect available on GitHub Pages) to the main repository at
   <https://github.com/debops/debops>.

## Logo attribution

The favicon is the DebOps logo, designed by
[Tasos Alvas](https://qwertyuiopia.com) in 2020 and incorporating the
[Debian Open Use Logo](https://www.debian.org/logos/). It is Copyright
(c) 2020 DebOps.org and Tasos Alvas, released under GPL-3.0-or-later or,
at your option, CC BY-SA 4.0. Source files live in
[`lib/images/`](https://github.com/debops/debops/tree/master/lib/images) in
the `debops/debops` repository.

## License

The page itself is GPL-3.0-or-later, matching the DebOps project.
