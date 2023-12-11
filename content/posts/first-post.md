+++
title = 'Essentials of Blogging with Hugo!'
date = 2023-11-29T16:48:14-05:00
+++
Here are few links and commands that will assist you in writing blog posts with hugo.

 [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet)

When setting up Hugo on a new machine, don't forget to run the below commands to init submodules.
```bash
git submodule init
git submodule update
```

Clean Serve Hugo:
```bash
hugo server --renderToDisk --gc --cleanDestinationDir
```
