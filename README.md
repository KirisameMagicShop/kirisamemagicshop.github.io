# Kirisame Magic Shop

This repo contains the source code of the site [Kirisame Magic
Shop](https://kirisamemagicshop.github.io/), which currently serves as a
mirror and blog site for (mainly PLT and functional programming related)
technical articles.

## Submitting Articles

New articles should be added to `content/articles/<title-in-kebab-case>.md`.
They should contain a frontmatter like

```
+++
title = 'Post Title'
author = 'Your Name'
date = 2024-09-01T20:06:17+08:00 # Datetime in TOML format
+++
```

which can be generated with `hugo new content <path-to-content-md>`.

The body is in markdown format, supporting KaTeX inline and block math.

## Contributing

To test and contribute to the site, you need to have [hugo](https://gohugo.io/)
(>= v0.132.0) installed.

Clone the repo, and run

```sh
git submodule update --init --recursive
```

then test the site out with

```sh
hugo serve -D
```

Refer to [hugo](https://gohugo.io/documentation/) and
[PaperMod](https://adityatelange.github.io/hugo-PaperMod/)'s documentations on
how to enable features, extend templates and customize the look.

## License

Kirisame Magic Shop © 2024 is licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), unless stated
otherwise in individual blog posts.
