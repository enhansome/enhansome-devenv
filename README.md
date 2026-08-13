# Awesome Dev Env with stars

A curated list of awesome tools, resources and workflow tips making an awesome development environment.

Inspired by [awesome-go](https://github.com/avelino/awesome-go) ⭐ 180,955 | 🐛 209 | 🌐 Go | 📅 2026-08-13, which was in turn inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 313,728 | 🐛 26 | 🌐 Python | 📅 2026-08-05.

### Contributing

[Guidelines](https://github.com/jondot/awesome-devenv/blob/master/CONTRIBUTING.md) ⭐ 3,328 | 🐛 39 | 📅 2024-07-29 tweaked and adapted from `awesome-go` - thanks!

But in short:

* List is alphabetically sorted
* If you think an item shouldn't be here [open an issue](https://github.com/jondot/awesome-devenv/issues/new) ⭐ 3,328 | 🐛 39 | 📅 2024-07-29

Many thanks to everyone on the [contributor list](https://github.com/jondot/awesome-devenv/graphs/contributors) ⭐ 3,328 | 🐛 39 | 📅 2024-07-29 :)

# Content

*Note: for an OS specific tool, please do your best to mark with `OSX/WIN/*NIX/LIN`*

* [Admins](#admins)
* [Benchmarking](#benchmarking)
* [Data](#data)
* [Diagnostics](#diagnostics)
* [Desktop](#desktop)
* [Documentation](#documentation)
* [Dotfiles](#dotfiles)
* [Editors](#editors)
  * [Atom](#atom)
  * [Sublime Text](#sublime-text-3)
  * [Vim](#vim)
  * [IntelliJ](#intellij)
  * [VSCode](#visual-studio-code)
* [Git](#git)
* [Misc](#misc)
* [Notifications](#notifications)
* [Orchestration](#orchestration)
* [Presentation](#presentation)
* [Shell](#shell)
* [Text](#text)
* [Terminal](#terminal)
* [Workflow](#workflow)

## Admins

*Tools to manage databases, permissions, etc.*

* [MongoHub](https://github.com/fotonauts/MongoHub-Mac/releases) ⭐ 2,416 | 🐛 87 | 🌐 Objective-C | 📅 2021-05-04 - Native OSx client for mongo
* [hss](https://github.com/six-ddc/hss) ⭐ 381 | 🐛 9 | 🌐 C | 📅 2025-10-17 - Never type the annoying ssh commands again.
* [Robomongo](http://robomongo.org/) - a cross platform Admin for MongoDB

## Benchmarking

*Tools to benchmark your code or services*

* [wrk](https://github.com/wg/wrk) ⭐ 40,387 | 🐛 203 | 🌐 C | 📅 2023-12-30
* [Vegeta](https://github.com/tsenart/vegeta) ⭐ 25,144 | 🐛 121 | 🌐 Go | 📅 2026-02-16
* [boom](https://github.com/rakyll/boom) ⚠️ Archived
* [phantomas](https://github.com/macbre/phantomas) ⭐ 2,260 | 🐛 65 | 🌐 JavaScript | 📅 2026-08-07 - website perf evaluation tool
* [redis-faina](https://github.com/Instagram/redis-faina) ⚠️ Archived Instagram's Redis counter/timing stats based on the MONITOR command
* [apachebench (ab)](http://httpd.apache.org/docs/2.2/programs/ab.html)
* [httperf](http://www.hpl.hp.com/research/linux/httperf/)
* [siege](http://www.joedog.org/siege-home/)

## Data

*Tools for handling online and offline data*

* [s3cmd](https://github.com/s3tools/s3cmd) ⭐ 4,899 | 🐛 311 | 🌐 Python | 📅 2025-10-22 - the S3 CLI tool for Amazon

## Diagnostics

*Tools for checking diagnosing your system while you work*

* [glances](https://github.com/nicolargo/glances) ⭐ 33,339 | 🐛 106 | 🌐 Python | 📅 2026-08-08
* [gtop](https://github.com/aksakalli/gtop) ⭐ 9,924 | 🐛 42 | 🌐 JavaScript | 📅 2025-11-06
* [nmon](http://nmon.sourceforge.net/pmwiki.php)

## Desktop

*Tools for improving and hacking around with your vanilla desktop*

* [hydra](https://github.com/sdegutis/hydra) ⭐ 5,217 | 🐛 0 | 🌐 C | 📅 2021-03-14 - script your desktop
  `/OSX/`
* [Keycastr](https://github.com/sdeken/keycastr) ⭐ 476 | 🐛 2 | 🌐 Objective-C | 📅 2021-04-03 - show your keys while
  presenting/casting `/OSX/`
* [Alfred](http://www.alfredapp.com/) - OSX productivity app `/OSX/`

## Documentation

*Tools to document your project*

* [Log4brains](https://github.com/thomvaill/log4brains) ⭐ 1,559 | 🐛 57 | 🌐 TypeScript | 📅 2024-12-17 - Docs-as-code knowledge base to manage Architecture Decision Records (ADR) for your project and publish them automatically as a static website.

## Dotfiles

* [Mathias Bynens's](https://github.com/mathiasbynens/dotfiles) ⭐ 31,449 | 🐛 186 | 🌐 Shell | 📅 2024-08-05 - .files, including \~/.osx — sensible hacker defaults for OS X
* [Thoughtbot's](https://github.com/thoughtbot/dotfiles) ⭐ 8,167 | 🐛 13 | 🌐 Shell | 📅 2026-08-11 - A set of vim, zsh, git, and tmux configuration files
* [Zach Holman's](https://github.com/holman/dotfiles) ⭐ 7,753 | 🐛 33 | 🌐 Shell | 📅 2026-06-25 - oh-my-zsh, osx, Zsh, vi, Ruby, Git, and more
* [Paul Miller's](https://github.com/paulmillr/dotfiles) ⭐ 1,239 | 🐛 2 | 🌐 Shell | 📅 2026-08-09 - Colourful & robust OS X configuration files and utilities
* [dotfiles.github.io](https://dotfiles.github.io/) - Collected dotfile resources. Has sections with dotfile bootstraps and lists of frameworks for various shells and editors.

## Editors

*Only awesome tools and addons for your favorite editor*

### Atom

* [atom-beautify](https://github.com/Glavin001/atom-beautify) ⭐ 1,503 | 🐛 402 | 🌐 CoffeeScript | 📅 2026-02-14 - Beautify HTML (including Handlebars), CSS (including Sass and Less), JavaScript, and much more in Atom.
* [file-icons](https://github.com/DanBrooker/file-icons) ⭐ 1,373 | 🐛 28 | 🌐 JavaScript | 📅 2025-12-28 - Adds file specific icons to atom for improved visual grepping.
* [minimap](https://github.com/atom-minimap/minimap) ⭐ 641 | 🐛 53 | 🌐 JavaScript | 📅 2024-12-08 - A graphical map (preview) of the full source code.
* [atom-pigments](https://github.com/abe33/atom-pigments) ⭐ 518 | 🐛 101 | 🌐 CoffeeScript | 📅 2023-01-10 - An Atom package to display colors in project and files.
* [atom-project-manager](https://github.com/danielbrodin/atom-project-manager) ⚠️ Archived - Get easy access to all your projects and manage them with project specific settings and options.
* [highlight-selected](https://github.com/richrace/highlight-selected) ⭐ 248 | 🐛 52 | 🌐 JavaScript | 📅 2023-01-03 - Double click on a word to highlight it throughout the open file.
* [minimap-highlight-selected](https://github.com/atom-minimap/minimap-highlight-selected) ⭐ 41 | 🐛 7 | 🌐 JavaScript | 📅 2023-03-06 - A minimap binding for the highlight-selected package.
* [atom-tree-view-git-status](https://github.com/subesokun/atom-tree-view-git-status) ⚠️ Archived - Show the Git repository status in the Atom tree-view.
* [minimap-git-diff](https://github.com/atom-minimap/minimap-git-diff) ⭐ 21 | 🐛 11 | 🌐 JavaScript | 📅 2023-03-06 - A minimap binding for the Atom git-diff package.

### Vim

* [Powerline](https://github.com/Lokaltog/powerline) ⭐ 14,801 | 🐛 242 | 🌐 Python | 📅 2026-03-11 - improved status bar for your buffers.
* [snipmate](https://github.com/garbas/vim-snipmate) ⭐ 2,019 | 🐛 17 | 🌐 Vim Script | 📅 2025-05-14 - textual snippets compatiable with Textmate snippets.
* [Completor](https://github.com/maralla/completor.vim) ⭐ 1,318 | 🐛 74 | 🌐 Python | 📅 2026-03-27 - async autocomplete with support for omni and semantic completion.
* [The Ultimate Vim Distribution](http://vim.spf13.com/) - spf13-vim is a distribution of vim plugins and resources for Vim, GVim and MacVim.

### Sublime Text 3

* [Emmet](https://github.com/sergeche/emmet-sublime) ⭐ 5,216 | 🐛 194 | 🌐 JavaScript | 📅 2023-06-28
* [Git Gutter](https://github.com/jisaacks/GitGutter) ⭐ 3,880 | 🐛 9 | 🌐 Python | 📅 2026-03-21 - display changed/added lines in the margin of the editor window.
* [MarkdownEditing](https://github.com/SublimeText-Markdown/MarkdownEditing) ⭐ 3,315 | 🐛 46 | 🌐 Python | 📅 2026-07-04 - Markdown syntax understanding and good color schemes.
* [Sublime Git](https://github.com/kemayo/sublime-text-git) ⭐ 2,816 | 🐛 208 | 🌐 Python | 📅 2024-06-13 - Git Integration for Sublime.
* [Side Bar Enhancments](https://github.com/titoBouzout/SideBarEnhancements) ⭐ 2,221 | 🐛 8 | 🌐 Python | 📅 2026-07-17 - Enhancements to Sublime Text sidebar. Files and folders.
* [Sublime Linter](https://github.com/SublimeLinter/SublimeLinter3/) ⭐ 2,038 | 🐛 19 | 🌐 Python | 📅 2026-01-23 - Interactive code linting.
* [jsFormat](https://github.com/jdc0589/JsFormat) ⭐ 1,421 | 🐛 11 | 🌐 Python | 📅 2022-04-05 - Javascript formatting.
* [TrailingSpaces](https://github.com/SublimeText/TrailingSpaces) ⭐ 890 | 🐛 12 | 🌐 Python | 📅 2023-06-24 - Highlight trailing spaces and delete them in a flash.
* [AdvancedNewFile](https://github.com/skuroda/Sublime-AdvancedNewFile) ⭐ 833 | 🐛 28 | 🌐 Python | 📅 2024-04-07 - File creation plugin.
* [RubyTest](https://github.com/maltize/sublime-text-2-ruby-tests) ⭐ 715 | 🐛 57 | 🌐 Python | 📅 2017-08-22 - Plugin for running Ruby tests.
* [LiveReload](https://github.com/dz0ny/LiveReload-sublimetext2) - LiveReload plugin.
* [Package Control](https://sublime.wbond.net/installation) - The Sublime Text package manager.

### Intellij

* [keymap](https://github.com/jondot/keymaps/) ⭐ 10 | 🐛 0 | 🌐 Shell | 📅 2014-08-03 - a hybrid Vim/ReSharper/Intellij keymap

### Visual Studio Code

* [Dev Git Repo](https://github.com/Microsoft/vscode) ⭐ 188,652 | 🐛 19,808 | 🌐 TypeScript | 📅 2026-08-13 - Github code repository for VS Code
* [Monaco Editor Git Repo](https://github.com/microsoft/monaco-editor) ⭐ 46,548 | 🐛 847 | 🌐 JavaScript | 📅 2026-08-07 - Github code repository for underlying browser-based editor

#### Extensions

* [VS Code Extension Marketplace](https://marketplace.visualstudio.com/search?target=VSCode\&category=All%20categories) - Official website for extensions
* [Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python) - Official Python extension
* [Sync settings](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) - Excellent extension for settings and extension sync of your VS code setup

## Git

*Tools and addons for making an awesome Git experience*

* [git-extras](https://github.com/visionmedia/git-extras) ⭐ 18,096 | 🐛 99 | 🌐 Shell | 📅 2026-08-12 - GIT utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-secret](https://github.com/sobolevn/git-secret) ⭐ 4,035 | 🐛 245 | 🌐 Shell | 📅 2026-08-11 - A bash-tool to store your private data inside a git repository.
* [git-sweep](https://github.com/arc90/git-sweep) ⭐ 2,703 | 🐛 45 | 🌐 Python | 📅 2023-10-01 - safely removes branches that have been merged into the master
* [git-up](https://github.com/aanand/git-up) ⭐ 2,586 | 🐛 36 | 🌐 Ruby | 📅 2017-11-07 - a better 'git pull'
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) ⭐ 1,169 | 🐛 2 | 🌐 Shell | 📅 2026-08-10 - collected git helper scripts
* [gh](https://github.com/jingweno/gh) ⭐ 717 | 🐛 15 | 🌐 Go | 📅 2022-10-07 - Fast GitHub command line client (hub port to Go)
* [awesome-github](https://github.com/fffaraz/awesome-github) ⭐ 541 | 🐛 7 | 📅 2026-03-20 - Faraz Fallahi maintains a curated list of GitHub & Git resources.
* [git-semver](https://github.com/markchalloner/git-semver) ⭐ 395 | 🐛 12 | 🌐 Shell | 📅 2020-01-21 - A git plugin to make Semantic Versioning 2.0.0 and Change Log management easier.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) ⭐ 117 | 🐛 19 | 🌐 Shell | 📅 2023-01-06 - ZSH plugin, adds a gitit command that opens the current directory on github in your current branch
* [scm\_breeze](https://github.com/ndbroadbent/scm_breeze) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-01-28 Streamline your git workflow
* [hub](https://hub.github.com/) - git CLI wrapper which makes working with GitHub easier
* [tig](http://jonas.nitro.dk/tig/) - an ncurses-based text-mode interface for git

## Misc

*Useful tools that cannot find a home in other categories*

* [Fenix Web Server](https://fenixwebserver.com) - A multi-host local static web server with push-button sharing (desktop app).
* [ML Workspace](hhttps://github.com/ml-tooling/ml-workspace) ⭐ 3,543 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-07-26 - All-in-one web-based development environment for machine learning and data science.
* [Mockoon](https://mockoon.com) - an API / HTTP REST mocking desktop application
* [HTTP Toolkit](https://httptoolkit.tech) - an HTTP inspection & debugging desktop application

## Notifications

*Tools that notify developers about changes in their work environment*

* [CatLight](https://catlight.io) - status notifier for developers. Checks the status of continuous delivery builds and shows desktop notifications.

## Orchestration

*Tools for orchestrating awesome development environments*

* [Nanobox](https://github.com/nanobox-io/nanobox) ⭐ 1,632 | 🐛 76 | 🌐 Go | 📅 2019-10-21 - A micro-PaaS (μPaaS) for creating consistent, isolated, development environments deployable anywhere <https://nanobox.io>.
* [azk](https://github.com/azukiapp/azk) ⚠️ Archived - a lightweight open source engine to orchestrate development environments

## Presentation

*Tools for presenting your work*

* [reveal.js](https://github.com/hakimel/reveal.js/) ⭐ 72,114 | 🐛 913 | 🌐 JavaScript | 📅 2026-05-21 - markdown based presentation on your browser
* [impress.js](https://github.com/impress/impress.js) ⭐ 38,191 | 🐛 59 | 🌐 JavaScript | 📅 2026-07-23 - presentation framework based on the power of CSS3 transforms and transitions
* [remark](https://github.com/gnab/remark) ⭐ 13,001 | 🐛 182 | 🌐 JavaScript | 📅 2024-06-19 - markdown based presentation on your browser
* [WebSlides](https://github.com/jlantunez/webslides) ⭐ 6,322 | 🐛 78 | 🌐 JavaScript | 📅 2022-12-10 - Making HTML presentations easy
* [deck.js](https://github.com/imakewebthings/deck.js) ⭐ 5,421 | 🐛 42 | 🌐 JavaScript | 📅 2019-01-28 - markdown based presentation on your browser
* [bespoke.js](https://github.com/markdalgleish/bespoke.js) ⭐ 4,799 | 🐛 6 | 🌐 JavaScript | 📅 2020-09-08 - DIY Presentation Micro-Framework
* [vimdeck](https://github.com/tybenz/vimdeck) ⭐ 1,407 | 🐛 11 | 🌐 Ruby | 📅 2021-01-11 - present inside your Vim
* [hacker-slides](https://github.com/msoedov/hacker-slides) ⚠️ Archived - Reveal.js based presentation tool
* [mithril-slides](https://github.com/wulab/mithril-slides) ⭐ 24 | 🐛 5 | 🌐 HTML | 📅 2018-08-26 - A Keynote-inspired presentation app written with Mithril

## Shell

*Tools for having an awesome shell environment*

* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) ⭐ 189,151 | 🐛 579 | 🌐 Shell | 📅 2026-08-11 - A community driven framework for managing zsh configuration.
* [shellcheck](https://github.com/koalaman/shellcheck) ⭐ 39,863 | 🐛 1,135 | 🌐 Haskell | 📅 2026-08-04 - Lint for shell. Will find deprecated and/or dangerous usage in shell scripts
* [fish-shell](https://github.com/fish-shell/fish-shell) ⭐ 34,014 | 🐛 576 | 🌐 Rust | 📅 2026-08-13 - The user-friendly command line shell
* [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) ⭐ 17,913 | 🐛 6 | 🌐 Shell | 📅 2026-08-08 - List of zsh plugins usable with [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,527 | 🐛 41 | 🌐 Shell | 📅 2021-07-21 and other [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/) ⭐ 189,151 | 🐛 579 | 🌐 Shell | 📅 2026-08-11 compatible zsh frameworks
* [oh-my-fish](https://github.com/oh-my-fish/oh-my-fish) ⭐ 11,374 | 🐛 0 | 🌐 Shell | 📅 2026-05-19 - Framework for managing your fish shell configuration inspired by oh-my-zsh.
* [zgen](https://github.com/tarjoilija/zgen) ⭐ 1,527 | 🐛 41 | 🌐 Shell | 📅 2021-07-21 - Faster framework for managing your zsh configuration, backward compatible with oh-my-zsh plugins
* [zsh quickstart kit](https://github.com/unixorn/zsh-quickstart-kit) ⭐ 907 | 🐛 16 | 🌐 Shell | 📅 2026-07-22 - Quick intro for getting set up with zsh and zgen
* [hss](https://github.com/six-ddc/hss) ⭐ 381 | 🐛 9 | 🌐 C | 📅 2025-10-17 - Never type the annoying ssh commands again.
* [zsh](http://www.zsh.org/) - A shell designed for interactive use, although it is also a powerful scripting language.

## Text

*Tools for working with text files - search, replace, processing*

* [ripgrep](https://github.com/BurntSushi/ripgrep) ⭐ 67,289 | 🐛 175 | 🌐 Rust | 📅 2026-08-04 - Faster than grep, written in Rust
* [ag](https://github.com/ggreer/the_silver_searcher) ⭐ 27,107 | 🐛 564 | 🌐 C | 📅 2024-06-16 - A C based code-searching tool similar to ack, but faster
* [peco](https://github.com/peco/peco) ⭐ 7,906 | 🐛 10 | 🌐 Go | 📅 2026-08-01 - interactive filtering, like interactive Grep
* [ack](https://github.com/petdance/ack2) ⭐ 1,466 | 🐛 9 | 🌐 Perl | 📅 2019-03-19 - the Perl based
  better-than-grep tool.

## Terminal

*Tools and addons for terminal and terminal work*

* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) ⭐ 189,151 | 🐛 579 | 🌐 Shell | 📅 2026-08-11 - the
  incredible ZSH addon.
* [zoxide](https://github.com/ajeetdsouza/zoxide) ⭐ 38,632 | 🐛 135 | 🌐 Rust | 📅 2026-08-10 - A better way to navigate your filesystem. Written in Rust, cross-shell, and much faster than other autojumpers.
* [autojump](https://github.com/joelthelion/autojump) ⭐ 16,958 | 🐛 231 | 🌐 Python | 📅 2025-02-27 - remembers your
  folders and jump to them based on partial recall (e.g. `j proj` will jump
  to `/home/Users/yourself/projects`.
* [fasd](https://github.com/clvv/fasd) ⚠️ Archived Command-line productivity booster, offers quick access to files and directories.
* [hss](https://github.com/six-ddc/hss) ⭐ 381 | 🐛 9 | 🌐 C | 📅 2025-10-17 - Never type the annoying ssh commands again.
* [freshenv](https://github.com/raiyanyahya/freshenv) ⭐ 177 | 🐛 5 | 🌐 Python | 📅 2024-09-30 - Provision, share, manage local and cloud developer environments.
* [homebrew](http://brew.sh) - Makes it easy to install open source packages on an `OS X` system with a single command.
* [httpie](http://httpie.org/) A command line HTTP client, a user-friendly cURL replacement.
* [iTerm2](http://www.iterm2.com/) - a great terminal replacement `/OSX/`
* [jq](https://stedolan.github.io/jq/) - a lightweight and flexible command-line JSON processor
* [Pipe Viewer](http://www.ivarch.com/programs/pv.shtml) - a tool for monitoring the progress of data through a pipeline
* [tmux](https://tmux.github.io/) the awesome terminal multiplexer.

## Workflow

*Tools and addons which improve your daily workflow with code*

* [watchman](https://github.com/facebook/watchman) ⭐ 13,671 | 🐛 253 | 🌐 C++ | 📅 2026-08-12 - Facebook's better
  `watch` - note it works as a service.
* [guard](https://github.com/guard/guard) ⭐ 6,457 | 🐛 67 | 🌐 Ruby | 📅 2026-07-16 - FS watch tool with a huge ecosystem of plugins
* [fswatch](https://github.com/alandipert/fswatch) ⭐ 5,579 | 🐛 45 | 🌐 C++ | 📅 2026-07-22 - a watch tool which
  will emit FS events and you can run commands on demand with. Note -
  `fswatch-run` too.
* [ergo](https://github.com/cristianoliveira/ergo) ⭐ 651 | 🐛 8 | 🌐 Go | 📅 2025-02-02 - The management of multiple local services running over different ports made easy.
* [Gebug](https://github.com/moshebe/gebug) ⭐ 631 | 🐛 21 | 🌐 Go | 📅 2026-07-03 - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
* [Zappr](https://github.com/zalando/zappr) ⚠️ Archived - GitHub integration built to enhance your project workflow via enable/disable pull request approval checks.
* [Prodmodel](https://github.com/prodmodel/prodmodel) ⭐ 60 | 🐛 8 | 🌐 Python | 📅 2026-04-13 - Build tool for data science pipelines.
* [just](https://github/casey/just) - A task runner for conveniently saving and running project-specific commands. Similar to make, but much nicer
* [LiveReload](http://livereload.com/) - FS watch and preprocessor as a desktop app for `/OSX/` and `/WIN/` with complementary browser extensions
  * [guard-livereload](https://github.com/guard/guard-livereload) ⭐ 2,110 | 🐛 34 | 🌐 JavaScript | 📅 2022-11-07 - Guard plugin compatible with LiveReload's browser extensions
  * [simplehttp](https://github.com/snwfdhmp/simplehttp) ⭐ 76 | 🐛 1 | 🌐 Go | 📅 2023-03-06 Fastest and simplest way to start serving a local directory over http.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
