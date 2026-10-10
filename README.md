---
title: README
---

# just-obsidian-docs

> [!TIP] 
> The vast majority of people who've stumbled upon this repository or plan on using it should check out [Quartz](https://quartz.jzhao.xyz/), it's arguably more suitable for the job and you should be quite happy with how it looks by default as well.

Originally, when I was browsing for ways to turn my Obsidian vault into a webpage, I wanted to use Github Pages and Github Actions since I had already synced by vault onto Github. Therefore I started looking into Jekyll and used the Just the Docs theme since I thought it looked nice originally. In the midst of setting up things, and looking at the result, I realized just how many things were not showing up properly on the webpage. So it became my mission to fill in some of the gaps as best as I can, and now I've decided to make it a template repository for everyone to use.

This repository includes opinionated CSS changes to Just the Docs in the [`_sass` directory](https://github.com/just-obsidian-docs/just-obsidian-docs/tree/main/_sass). However, some of the other things I think are quite useful if you want a wider breadth of the Markdown Obsidian supports to render properly when you deploy with Jekyll and Just the Docs.

This template repository is mainly for those who want to have their Obsidian vaults become a viewable webpage, using Github Actions and Jekyll with Just the Docs as their deployment stack.

Mind you, all of this is not perfect, there are much more things to be added and improved. Some include the list below:

- Full Wikilink Support (only some patterns are converted right now)
- Support for GFM note, warning, tip, important, and caution callouts
- And a whole lot more

I'm also not an Obsidian expert or Just the Docs expert, I definitely haven't tried everything it has to offer. But anyhow, hope this helps! I will be syncing the improvements I've made hosting [`cs-notes`](https://ngivanyh.github.com/cs-notes) over here periodically.

## Configuring

For more details, check out [Jekyll](https://jekyllrb.com/docs/) and [Just the Docs'](https://just-the-docs.com/) official documentation.

The `_config.yaml` as it currently stands expects your Obsidian vault to be in the root directory of the project, which means your files and `.obsidian/` will live alongside `_config.yaml`, `_sass/`, `_includes`, and any other directory used for the compilation of the webpage.

If you don't want to mix such files with your vault, change the `source` key to point to some other directory.

There are some guides to configuring certain things in this repo, you can take a look. But for the authoritative and correct answer, consult the *official* guidelines.
