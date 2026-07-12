# just-obsidian-docs

In hindsight, I should've used [Quartz](https://quartz.jzhao.xyz/) (and you should probably do so as well, it's most likely the solution you're looking for), but since I've already gone down this rabbit hole of making Jekyll and just-the-docs work with Obsidian Vaults, I might as well make a template repository and so other people don't need to stumble as deep into this thing.

This repository includes opinionated CSS changes to just-the-docs in the [`_sass` directory](https://github.com/just-obsidian-docs/just-obsidian-docs/tree/main/_sass). However, some of the other things I think are quite useful if you want a wider breadth of the Markdown Obsidian supports to render properly when you deploy with Jekyll and just-the-docs.

This template repository is mainly for those who want to have their Obsidian vaults become a viewable webpage, using Github Actions and Jekyll with just-the-docs as their deployment stack.

Mind you, all of this is not perfect, there are much more things to be added and improved. Some include the list below:

- Sticky Headers
- Full Wikilink Support (only some patterns are converted right now)
- Support for GFM note, warning, tip, important, and caution blockquotes
- Markdown highlight support
- And a whole lot more

I'm also not an Obsidian expert or just-the-docs expert, I definitely haven't tried everything it has to offer. But anyhow, hope this helps! I will be syncing the improvements I've made hosting [`cs-notes`](https://ngivanyh.github.com/cs-notes) over here periodically.