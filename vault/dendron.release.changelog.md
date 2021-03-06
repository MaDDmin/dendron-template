---
id: 9bc92432-a24c-492b-b831-4d5378c1692b
title: Changelog
desc: ''
updated: 1601508213606
created: 1601508213606
stub: false
---

# Changelog

## [0.12.6](https://github.com/dendronhq/dendron/compare/v0.12.5...v0.12.6) (2020-10-07)

### Features

#### Default Snippets

Dendron now initializes your workspace with common default snippets

((ref: [[dendron.topic.snippets]]#default snippets,1:#*))

#### Latex Support on Published Site

((ref: [[dendron.related.dendron-jekyll.topic.math]]#math,1:#*))

#### Introduce siteRepoDir Customization

((ref: [[dendron.topic.publishing.configuration]]#siterepodir,1:#*))

### Bug Fixes

- trying to publish the `dendron-template` no longer results in a missing links report
- issue with schemas not showing up under lookup

### Progress

This section tracks our progress against the milestones in our [[public roadmap|dendron.roadmap]]

- [x] [[Seeds v0|dendron.roadmap.project.n.2020.seeds]]
- [ ] Server migration, progress: 70/100
    - below is a summary of our progress. we are currently about half way done
    - aiming to have a workable version using the Dendron server by next week
((ref: [[dendron.roadmap.project.n.2020.server-migration]]#tasks,1:#*))

### Other 

#### Seeds
- We launched two [[seeds|dendron.topic.seeds]]. A seed is a dendron site that tries to be be a all encompassing reference for a particular vertical. Dendron provides specific libraries and CLIs that make it easy for users to create seeds from existing open source content as well as personal notes.

Current Seeds:
    - open PKM catalogue
    - open AWS catalogue

((ref: [[dendron.showcase]]#open pkm catalogue,1:#*))
((ref: [[dendron.showcase]]#open aws catalogue,1:#*))

#### Alternatives

this announcement also comes with an ask. Dendron is now in [AlternativesTo](https://alternativeto.net/), a crowdsourced catalogue for software recommendations. If you like Dendron and want to help us spread the word 🌱, please leave us a review [here](https://alternativeto.net/software/dendron/reviews/) 🙏


## [0.12.4](https://github.com/dendronhq/dendron/compare/v0.12.4-alpha.11...v0.12.4) (2020-09-30)


### Features

- **schemas:** live schema updates ([868a125](https://github.com/dendronhq/dendron/commit/868a125a0f07dcbfb5cbeb5dd04d05ab7556e12b))
    - schema changes are now updated in realtime. no more `Reload Index`
    - NOTE: this doesn't yet apply to `Show Schema Graph`. you'll still need to run `Reload Index` to see the changes in the graph

### Enhancements

- **lookup:** special notes are now created via lookup ([da825a9](https://github.com/dendronhq/dendron/commit/da825a9d2b1ec10a3f9d3eac20db06448fe5344b))
    - instead of being a separate command, journal and scratch notes are now created using the regular lookup interface
    - new keybindings have been introduced to [map old commands to new style lookups](https://dendron.so/notes/a7c3a810-28c8-4b47-96a6-8156b1524af3.html#passing-arguments-to-lookup)
    - `Create Journal Note` and `Create Scratch Note` still exist as commands but will be deprecated in the next minor release 

- **lookup:** support lookups opening with a new split ([da825a9](https://github.com/dendronhq/dendron/commit/da825a9d2b1ec10a3f9d3eac20db06448fe5344b))

((ref: [[dendron.topic.lookup]]#split toggle))

- **refs:** easier note ref selection([114ff87](https://github.com/dendronhq/dendron/commit/114ff87be04f8d746b0be28f7627ba0d1ec9b504))

Dendron will now recognize a header selection if you have any part of the header highlighted (vs needing to highlight the entire line)

((ref: [[dendron.topic.commands]]#copy note ref:#*))

### Documentation
- we published our public roadmap

((ref: [[dendron.roadmap]]))

- changelog moved to dedicated [page](https://dendron.so/notes/9bc92432-a24c-492b-b831-4d5378c1692b.html)
- lookup menu docs
((ref: [[dendron.topic.lookup]]#lookup menu:#*))

### Community Highlights

- a new planter has appeared 🌲
((ref: [[dendron.showcase]]#luke's second brain))