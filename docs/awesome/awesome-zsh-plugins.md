<div class="github-widget" data-repo="unixorn/awesome-zsh-plugins"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## awesome-zsh-plugins

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Status

[![License](https://img.shields.io/github/license/unixorn/awesome-zsh-plugins.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Build Status](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Funixorn%2Fawesome-zsh-plugins%2Fbadge&style=flat)](https://actions-badge.atrox.dev/unixorn/awesome-zsh-plugins/goto)
[![Join the chat at https://gitter.im/unixorn/awesome-zsh-plugins](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/unixorn/awesome-zsh-plugins?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![GitHub stars](https://img.shields.io/github/stars/unixorn/awesome-zsh-plugins.svg)](https://github.com/unixorn/awesome-zsh-plugins/stargazers)
[![Code Climate](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/gpa.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![Issue Count](https://codeclimate.com/github/unixorn/awesome-zsh-plugins/badges/issue_count.svg)](https://codeclimate.com/github/unixorn/awesome-zsh-plugins)
[![GitHub last commit (branch)](https://img.shields.io/github/last-commit/unixorn/awesome-zsh-plugins/main.svg)](https://github.com/unixorn/awesome-zsh-plugins)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/unixorn/awesome-zsh-plugins/)

A collection of ZSH frameworks, plugins, tutorials & themes inspired by the various awesome list collections out there.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


<!-- END doctoc generated TOC please keep comment here to allow auto update -->

*Please read the [Contributing Guidelines](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Contributing.md) before contributing.*

## Frameworks

These frameworks make customizing your ZSH setup easier.

You can find some interesting performance timing comparisons of various frameworks in the following locations.

* [zdharma/pm-perf-test](https://github.com/zdharma/pm-perf-test)
* [rossmacarthur/zsh-plugin-manager-benchmark](https://github.com/rossmacarthur/zsh-plugin-manager-benchmark)

### [alf](https://github.com/psyrendust/alf)

**Alf** is an out of this world super fast and configurable framework for ZSH; it's modeled after Prezto and Antigen while utilizing Oh-My-Zsh under the covers; and offers standard defaults, aliases, functions, auto completion, automated updates and installable prompt themes and plugins.

### [ansible-role-zsh](https://github.com/viasite-ansible/ansible-role-zsh)

**ansible-role-zsh** is an ansible role with zero-knowledge installation. It uses antigen to manage bundles and oh-my-zsh. Can load bundles conditionally. By default it includes powerlevel9k theme, autosuggestions, syntax-highlighting and [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) and [fzf-marks](https://github.com/urbainvaes/fzf-marks). Fully customizable.

### [ant-zsh](https://github.com/anthraxx/ant-zsh)

**Ant-zsh** is a tiny and lightweight ZSH configuration environment for special customization needs. It includes plugins, themes and a basic convenient setup.

### [antibody](https://github.com/getantibody/antibody)

**Antibody** is a faster and simpler antigen written in Golang. More details at [http://getantibody.github.io/](http://getantibody.github.io/).

### [antigen-hs](https://github.com/Tarrasch/antigen-hs)

**antigen-hs** is a replacement for antigen optimized for a low overhead when starting up the shell. It will automatically clone plugins for you.

### [antigen](https://github.com/zsh-users/antigen)

**Antigen** is a small set of functions that help you easily manage your shell (ZSH) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to ZSH, what Vundle is to vim. Antigen can load oh-my-zsh themes and plugins and will automatically clone them for you.

### [ax-zsh](https://github.com/alexbarton/ax-zsh)

**Ax-ZSH** is a modular configuration system for ZSH. It provides sane defaults and is extendable by plugins.

### [dotzsh](https://github.com/dotphiles/dotzsh)

**Dotzsh** strives to be platform and version independent. Some functionality may be lost when running under older versions of ZSH, but it should degrade cleanly and allow you to use the same setup on multiple machines of differing OSes without problems.

### [fresh](https://github.com/freshshell/fresh)

**fresh** is a tool to source shell configuration (aliases, functions, etc) from others into your own configuration files. We also support files such as ackrc and gitconfig. Think of it as Bundler for your dot files.

### [miniplug](https://sr.ht/~yerinalexey/miniplug)

**miniplug** is a minimalistic plugin manager for ZSH.

* No crashes or double plugin loading when re-sourcing .zshrc
* Unlike other frameworks, Miniplug does not pollute your $PATH
* Only does the bare minimum for managing plugins

### [mzpm](https://github.com/Insert-Creative-Name-Here/mzpm)

**mzpm** is a minimalist plugin manager for ZSH.

### [oh-my-zsh](https://ohmyz.sh/)

**oh-my-zsh** is a community-driven framework for managing your ZSH configuration. Includes 120+ optional plugins (rails, git, macOS, hub, capistrano, brew, ant, macports, etc), over 120 themes to spice up your morning, and an auto-update tool that makes it easy to keep up with the latest updates from the community.

### [PMS](https://github.com/JoshuaEstes/pms)

PMS allows you to manage your shell in a way to that helps decrease setup time and increases your productivity. It has support for themes (change the way your shell looks), plugins (adds functionality to your shell), and dotfile management.

The PMS framework also allows you to use the same framework in different shells. Use ZSH on your personal laptop, and use bash on remote servers. Wanna try fish? Go ahead, try out different shells.

### [prezto](https://github.com/sorin-ionescu/prezto)

**Prezto** enriches the ZSH command line interface environment with sane defaults, aliases, functions, auto completion, and prompt themes. There are some prezto-specific plugins at [https://github.com/belak/prezto-contrib](https://github.com/belak/prezto-contrib).

### [pumice](https://github.com/ryutamaki/pumice)

**Pumice** is a lightweight plugin manager for ZSH.

### [pz](https://github.com/mattmc3/pz)

A plugin manager for ZSH doesn't have to be complicated to be powerful. PZ doesn't try to be clever when it can be smart. PZ is a full featured, fast, and easy to understand plugin manager encapsulated in a single file with about 200 lines of clean ZSH.

PZ does just enough to manage your Zsh plugins really well, and then gets out of your way. And it's unit tested too to make sure it works as expected!
### [sheldon](https://github.com/rossmacarthur/sheldon)

A fast, configurable, shell plugin manager.

* Can manage
  * Any `git` repository.
    * Branch/tag/commit support.
    * Extra support for GitHub repositories.
    * Extra support for Gists.
  * Arbitrary remote files, simply specify the URL.
  * Local plugins, simply specify the directory path.
* Highly configurable install methods using [handlebars](http://handlebarsjs.com/) templating.
* Super-fast parallel installation.
* Configuration file using [TOML](https://github.com/toml-lang/toml) syntax.
* Uses a lock file for much faster loading of plugins.

### [Toasty](https://github.com/5paceToast/toasty-zsh)

**Toasty** is a ZSH framework made to facilitate management, not dictate it.

### [tzpm](https://github.com/notusknot/tzpm)

The tiniest ZSH plugin manager. Still under development.

### [uz](https://github.com/maxrodrigo/uz)

A ZSH micro plugin manager.

### [yazt](https://github.com/bashelled/yazt)

Yazt is a simple zsh theme manager in maintence that is compatible with nearly everything. You can use prompts in plugins, mix 'n' match two themes, with a few modifications, you can even use it in bash.

### [zapack](https://github.com/aiya000/zsh-zapack)

zapack is a basic fast minimal ZSH plugin loader.

### [zeesh](https://github.com/zeekay/zeesh)

**Zeesh** is a cross-platform ZSH framework. It's similar to, but incompatible with, [oh-my-zsh](http://ohmyz.sh/). It has a modular plugin architecture making it easy to extend. It has a rich set of defaults, but is designed to be as lightweight as possible.

### [zgem](https://github.com/qoomon/zgem)

**Zgem** is a plugin manager for ZSH that supports loading and updating plugins and themes from git, http and local files.

### [zgen](https://github.com/tarjoilija/zgen)

**Zgen** is a lightweight plugin manager for ZSH inspired by Antigen. The goal is to have minimal overhead when starting up the shell because nobody likes waiting. It is currently not being actively maintained and I recommend you use the [zgenom](https://github.com/jandamm/zgenom) fork instead, which is.

### [zgenom](https://github.com/jandamm/zgenom)

A lightweight plugin manager for ZSH that is a fork that extends the brilliant [zgen](https://github.com/tarjoilija/zgen) and provides more features and bugfixes while being fully backwards compatible.

To keep loading fast during new terminal sessions, `zgenom` generates a static `init.zsh` file which does nothing but source your plugins and append them to your `fpath`.

This minimizes startup time by not having to execute time consuming logic (plugin checking, updates, etc) during startup. The downside is that you have to refresh the init script manually with `zgenom reset` whenever you update your plugin list in your `.zshrc`.

Zgenom can load [oh-my-zsh](http://ohmyz.sh/)-compatible and [prezto](https://github.com/sorin-ionescu/prezto)-compatible plugins and themes, and will automagically `git` clone plugins for you when you add them to your plugin list.

### [zilsh](https://github.com/zilsh/zilsh)

**zilsh** is a ZSH config system that aims to appeal more to power-users and follow the simplistic approach of vim-pathogen.

### [zim](https://github.com/zimfw/zimfw)

**Zim** is a ZSH configuration framework with blazing speed and modular extensions.

### [Zinit](https://github.com/zdharma/zinit)

**Zinit** is an innovative and probably (because of the Turbo) the [fastest](https://github.com/zdharma/pm-perf-test) plugin manager with support for:

- Turbo mode – 80% faster Zsh startup! for example: instead of 200 ms, it'll be 40 ms,
- completion management (selectively disable and enable completions),
- snippets (↔ regular files downloaded via-URL, e.g.: scripts) and through them Oh My Zsh and Prezto plugins support (→ low overhead),
- annexes (↔ Zinit extensions),
- reports (from the plugin loads – plugins are no longer black boxes),
- plugin unloading (allows e.g.: dynamic theme switching),
- `bindkey` capturing and remapping,
- [packages](https://github.com/Zsh-Packages),
- clean `fpath` (the array `$fpath` is not being used to add completions and autoload functions, hence it stays concise, not bloated),
- [services](https://github.com/zservices) ↔ a single-instance, background plugins,
- also, in general: all the mechanisms from the Zsh Plugin Standard – Zinit is a reference implementation of the standard.

Bonus: you can use [zinit-console](https://github.com/zinit-zsh/zinit-console) to view and change the state of the ZSH session (e.g.: list and unload plugins) and to delete the plugins and snippets from the disk.

The project is very active – currently > 3100 commits.

### [zit](https://github.com/thiagokokada/zit)

**zit** is a plugin manager for ZSH. It is minimal because it implements the bare minimum to be qualified as a plugin manager: it allows the user to install plugins from Git repositories (and Git repositories only, them why the name), source plugins and update them. It does not implement fancy functions like cleanup of removed plugins, automatic compilation of installed plugins, alias for oh-my-zsh/prezto/other ZSH frameworks, building binaries, PATH manipulation and others.

### [znap](https://github.com/marlonrichert/zsh-snap)

**:zap:Znap** is a light-weight plugin manager & Git repo manager for ZSH that's easy to grok. While tailored for ZSH plugins specifically, Znap also functions as a general-pupose utility for managing Git repos.

Znap

Znap can:

- Make any prompt appear instantly. Reduce your startup time from ~200ms to ~40ms with just one command.
- Asynchronously compile your plugins and functions.
- Cache those expensive `eval $(commands)`.
- Clone or pull multiple repos in parallel.
- Re-clone all your repos without you having to re-enter them.
- Multi-repo management
- Automatic `compinit` and `bashinit` - you no longer need them in your `.zshrc`, znap will do them automatically as needed.

### [zoppo](https://github.com/zoppo/zoppo)

**Zoppo** is the crippled configuration framework for ZSH. As an Italian saying goes: "chi va con lo zoppo, impara a zoppicare", we realized we were walking with a cripple and are now going to become crippled ourselves.

### [zpacker](https://github.com/happyslowly/zpacker)

**Zpacker** is a lightweight ZSH plugin & theme management framework.

### [zpico](https://github.com/thornjad/zpico)

The minuscule ZSH package manager. No frills, no bloat, just 2 kB of 100% ZSH code, providing complete package management for your ZSH environment.

### [zplug](https://github.com/zplug/zplug)

**:hibiscus: Zplug** is a next-generation ZSH plugin manager.

- Can manage everything
  - Zsh plugins/UNIX commands on [GitHub](https://github.com) and [Bitbucket](https://bitbucket.org)
  - Gist files ([gist.github.com](https://gist.github.com/discover))
  - Externally managed plugins e.g., [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and [prezto](https://github.com/sorin-ionescu/prezto) plugins/themes
  - Binary artifacts on [GitHub Releases](https://help.github.com/articles/about-releases/)
  - Local plugins
  - etc. (you can add your [own sources](https://github.com/zplug/zplug/blob/master/doc/guide/External-Sources.md)!)
- Super-fast parallel installation/update
- Support for lazy-loading
- Branch/tag/commit support
- Post-update, post-load hooks
- Dependencies between packages
- Unlike [antigen](https://github.com/zsh-users/antigen), no ZSH plugin file (`*.plugin.zsh`) required
- Interactive interface ([fzf](https://github.com/junegunn/fzf), [peco](https://github.com/peco/peco), [zaw](https://github.com/zsh-users/zaw), and so on)
- Cache mechanism for reducing [the startup time](https://github.com/zplug/zplug#vs)

### [zpm](https://github.com/zpm-zsh/zpm)

**zpm** ( ZSH Plugin Manager ) is a plugin manager for [ZSH](http://www.zsh.org/) who combines the imperative and declarative approach. At first run, zpm will do complex logic and generate cache, after that will be used cache only, so it makes this framework to be very fast.

* Fastest plugin manager (Really, after the first run, zpm will not be used at all)
* Support for async loading
* Dependencies between packages
* zpm runs on Linux, macOS, FreeBSD and Android.
* zpm plugins are compatible with [oh-my-zsh](http://ohmyz.sh/).

### [zr](https://github.com/jedahan/zr)

**zr** is a quick, simple ZSH plugin manager written in Rust and easily installable with `cargo install zr`.

### [zshing](https://github.com/zakariaGatter/zshing)

**zshing** is a ZSH plugin manager similar to Vundle/Vim and allows you to...

* keep track of and configure your plugins right in the `.zshrc`
* Install ZSH plugins
* Update ZSH plugins
* Search by name all available ZSH Plugins
* Clean unused plugins up
* run the above actions in a *single command*
* manages the __Source Plugins__ of your installed Plugins

### [ztanesh](https://github.com/miohtama/ztanesh)

**Ztanesh** aims to improve your UNIX command line experience and productivity with the the configuration provided by the ztanesh project: the tools will make your shell more powerful and easier to use.

### [ztheme](https://github.com/SkyyySi/ztheme)

ztheme is a small and fast theme engine for ZSH.

### [ztupide](https://github.com/mpostaire/ztupide)

A simple and fast ZSH plugin manager. It uses zcompile and async loading to speed up your shell startup time.

### [zulu](https://github.com/zulu-zsh/zulu)

**Zulu** is a environment manager for ZSH 5+, which aims to make it easy to manage your shell without writing any code.

* Easily manage your shell environment without editing files.
* Create aliases, functions and environment variables, and have them available to you at the next shell startup.
* Add and remove directories from `$path`, `$fpath` and `$cdpath` with simple commands.
* Install packages, plugins and themes easily, and have them available to you immediately.

## Setups

This section is for full setup dropins - they aren't frameworks, but they're not simple plugins/themes either.

### zgenom

* [zsh-quickstart-kit](https://github.com/unixorn/zsh-quickstart-kit) - A simple quickstart for using ZSH with [zgenom](https://github.com/jandamm/zgenom). This includes a curated collection of plugins, automatically configures ZSH to use [zgenom](https://github.com/jandamm/zgenom) to load them and periodically automatically update itself, the plugins, and the quickstart kit itself.

### zinit

* [ZPWR](https://github.com/MenkeTechnologies/zpwr) - An extremely powerful custom terminal environment built on top of [Zinit](https://github.com/zdharma/zinit) for maximum speed.  A full terminal configuration framework including zsh, tmux, fzf, vim and spacemacs configurations.  It includes:

- 11.5k+ tab completions
- 1.9k+ aliases
- 330+ git aliases
- 350+ zpwr subcommands
- 2.1k functions
- 150+ zpwr environment variables
- 170+ perl, python, bash, zsh scripts
- 2.8k line README.md
- 46k+ LOC
- 1 line install

## Tutorials

### Generic ZSH

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience/) - Tutorial using a combination of [iTerm 2](https://www.iterm2.com/#/section/home), [ZSH](https://en.wikipedia.org/wiki/Z_shell), [Prezto](https://github.com/sorin-ionescu/prezto), [Tmux](https://tmux.github.io), and [Tmuxinator](https://github.com/tmuxinator/tmuxinator) to make for an extremely productive developer workflow.
* [Arch Linux's ZSH introduction](https://wiki.archlinux.org/index.php/zsh) -  Not actually Arch or Linux-specific.
* [GH](https://github.com/gustavohellwig/gh-zsh) - Setup ZSH on debian/Ubuntu-based linuxes. Installs [Powerlevel10k](https://github.com/romkatv/powerlevel10k), [zsh-completions](https://github.com/zsh-users/zsh-completions), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions), [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting/), and more.
* [How To Make an Awesome Custom Shell with ZSH](https://linuxstans.com/how-to-make-an-awesome-custom-shell-with-zsh/) - A beginner-friendly tutorial on how to install and configure a ZSH shell.
* [commandlinepoweruser.com](https://commandlinepoweruser.com/) - Wes Bos' videos introducing ZSH and oh-my-zsh.
* [Outrageously Useful Tips To Master Your Z Shell](http://reasoniamhere.com/2014/01/11/outrageously-useful-tips-to-master-your-z-shell/) covers some of the features that ZSH has that Bash doesn't, and using oh-my-zsh.
* [rs-example](https://github.com/al-jshen/zshplug-rs-example) - An example plugin showing how a Rust program can listen to and process commands from ZSH.
* [Why ZSH is Cooler than your Shell](https://www.slideshare.net/jaguardesignstudio/why-zsh-is-cooler-than-your-shell-16194692) - slideshare presentation.
* [xVanjaZ](https://github.com/xVanjaZ/xVanjaZ-ZSH-Theme) - wrote a quick setup document for oh-my-zsh beginners showing how to use the [spaceship](https://github.com/denysdovhan/spaceship-prompt.git) prompt, syntax highlighting at the prompt, autosuggestion and a custom iTerm 2 theme.
* [ZSH for Humans](https://github.com/romkatv/zsh4humans) - A turnkey configuration for ZSH that aims to work really well out of the box. It combines a curated set of ZSH plugins into a coherent whole that feels like a finished product rather than a DIY starter kit.
* [ZSH Pony](https://github.com/mika/zsh-pony) - Covers customizing ZSH without a framework.
* [ZSH tips by Christian Schneider](http://strcat.de/zsh/#tipps) - An exhaustive list of ZSH tips by Christian Schneider.

### Antigen

* [belak/zsh-utils](https://github.com/belak/zsh-utils) - A minimal set of ZSH plugins designed to be low-friction and low-complexity.
* [Frictionless zsh And oh-my-zsh Management With Antigen](https://thorsten-hans.com/frictionless-zsh-and-oh-my-zsh-management-with-antigen) - Guides you through the setup process and demonstrates how to manage plugins and themes with Antigen to tailor your ZSH experience.
* [mgdm.net/weblog/zsh-antigen/](https://mgdm.net/weblog/zsh-antigen/) - Michael Maclean's article about switching from oh-my-zsh to antigen.
* [Oh-my-zsh is the Disease and Antigen is the Vaccine](https://joshldavis.com/2014/07/26/oh-my-zsh-is-a-disease-antigen-is-the-vaccine/) - Josh Davis' introduction to Antigen.

### Oh-My-Zsh

* [Getting started with oh-my-zsh](https://medium.com/@dienbui/using-oh-my-zsh-f65be6460d3f) - A beginners guide to oh-my-zsh by Dien Bui
* [Learn Zsh in 80 Minutes macOS](https://www.youtube.com/watch?v=MSPu-lYF-A8) - A beginners guide to using Oh My Zsh on macOS by Karl Hadwen
* [Oh-My-Zsh! A Work of CLI Magic](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb) - Michiel Mulders installation guide for Ubuntu
* [ZSH Gem 24](https://www.refining-linux.org/archives/59-ZSH-Gem-24-ZSH-frameworks.html) - Part of the 2011 ZSH Advent Calendar. Covers oh-my-zsh and zshuery.

### Prezto

* [A Beautifully Productive Terminal Experience](https://mikebuss.com/2014/02/02/a-beautiful-productive-terminal-experience) - Mike Buss' blog post about using Prezto, [Tmux](https://tmux.github.io) & Tmuxinator.
* [Migrate from Oh-My-Zsh to Prezto](http://jeromedalbert.com/migrate-from-oh-my-zsh-to-prezto/) - Jerome Dalbert's blog post on migrating to Prezto.

### Zgen

* [rad-shell](https://github.com/brandon-fryslie/rad-shell) - A fantastically feature rich, lightning-fast shell setup, powered by [ZSH](http://www.zsh.org/), [Prezto](https://github.com/sorin-ionescu/prezto), and [Zgen](https://github.com/tarjoilija/zgen).

### Zinit (née zplugin)

* [BlaCk-Void-Zsh](https://github.com/black7375/BlaCk-Void-Zsh) - :crystal_ball: Awesome, Customable Zsh Starter Kit :stars::stars:. Includes powerline, fzf integration, Weather and image viewing in some terminals.
* [zinit-configs](https://github.com/zdharma/zinit-configs) - Real-world configuration files (basically a collection of `.zshrc` files) holding Zinit invocations.

### ZSH on Windows

* [superconsole](https://github.com/alexchmykhalo/superconsole) - Windows-only.

  * ConEmu/zsh out-of-the-box configured to restore previously opened tabs and shell working directories after ConEmu restart
  * Choose between clean and inherited environment when starting new SuperConsole sessions
  * Custom colorful scheme, colorful output for various commands
  * MSYS2 included, `zsh` and necessary software preinstalled, uses zsh-grml-config
  * Uses Antigen for ZSH theme and config management
  * Enabled number of ZSH plugins to activate completion, highlighting and history for most comfortable use
  * Git-for-Windows repo with proper `git` and git lfs support for MSYS2 environment is configured, `git` client already installed.
  * `ssh-agent` for `git` works out-of-box, add your keys to `ConEmu/msys64/ConEmu/msys64/home/user/.ssh` dir
  * Non-blocking ZSH prompt status updates thanks to agkozak-zsh-prompt
  * Customized for MSYS2 command-not-found handler suggests what package to install
  * Sets up `nano` as main editor, enables `nano` syntax highlighting
  * Custom helper scripts added to `ConEmu/msys64/3rdparty`

## Plugins

* [1999](https://github.com/DTan13/zsh1999) - Powerline-esque theme. Includes `git` status decorations, network and battery status.
* [256color](https://github.com/chrissicool/zsh-256color) - Enhances the terminal environment with 256 colors. It looks at the chosen `TERM` environment variable and sees if there is respective ncurses' terminfo with 256 colors available. The result is a multicolor terminal, if available.
* [abbr (olets)](https://github.com/olets/zsh-abbr) - Manages auto-expanding abbreviations that expand inline when you hit space, inspired by fish shell.
* [abbr-path](https://github.com/felixgravila/zsh-abbr-path) - Adds functionality of the `theme_title_use_abbreviated_path` parameter from some oh-my-fish themes.
* [abbrev-alias](https://github.com/momo-lab/zsh-abbrev-alias) - Provides functionality similar to `vim`'s abbreviation expansion.
* [accurev](https://github.com/dalefukami/accurev-zsh) - ZSH plugin for [accurev](https://www.microfocus.com/en-us/products/accurev/overview).
* [actiona](https://github.com/matthieusb/act) - Make it easier to call [actiona](https://github.com/Jmgr/actiona) scripts from your command line. Includes tab completions.
* [alehouse](https://github.com/sticklerm3/alehouse) - Contains short aliases for [brew](https://brew.sh) commands, inspired by [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin).
* [alias-tips](https://github.com/djui/alias-tips) - An oh-my-zsh plugin to help remembering those aliases you defined once.
* [allergen](https://github.com/stanislas/allergen) - A collection of custom ZSH plugins to use with Antigen.
* [almostontop](https://github.com/Valiev/almostontop) - Clears previous command output every time before new command executed in shell. Inspired by the [alwaysontop](https://github.com/swirepe/alwaysontop) plugin for `bash`.
* [alt-and-select](https://github.com/raisty/alt-and-select) - Binds the alt-c (copy), alt-v (paste), alt-x (cut) keyboard shortcut to a commands: copy-region-as-kill, yank, kill-region. Remaps the execute command to Alt-Shift-X.
* [ansible](https://github.com/sparsick/ansible-zsh) - A plugin for [Ansible](https://www.ansible.com/).
* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols.
* [antigen-git-rebase](https://github.com/smallhadroncollider/antigen-git-rebase) - Antigen/ZSH script to aid with `git` rebasing.
* [anyframe](https://github.com/mollifier/anyframe) - A peco/percol/fzf wrapper plugin for ZSH.
* [apache2](https://github.com/voronkovich/apache2.plugin.zsh) - Adds aliases and functions for managing Apache2.
* [apple-touchbar](https://github.com/zsh-users/zsh-apple-touchbar) - Adds MacBook Pro touchbar support in [iTerm 2](https://iterm2.com).
* [appup](https://github.com/Cloudstek/zsh-plugin-appup) - Adds `start`, `stop`, `up` and `down` commands when it detects a `docker-compose.yml` or `Vagrantfile` in the current directory (e.g. your application). Just run `up` and get coding!
* [arc](https://github.com/anton-rudeshko/zsh-arc) - Adds aliases for Yandex version control system.
* [arduino](https://github.com/raghur/zsh-arduino) - Adds scripts to build, upload and monitor arduino sketches from a command line. Requires [`jq`](https://stedolan.github.io/jq/).
* [artisan](https://github.com/jessarcher/zsh-artisan) - Laravel `artisan` plugin for ZSH to help you to run `artisan` from anywhere in the project tree, with tab completion!
* [asciidoctor](https://github.com/sparsick/asciidoctor-zsh) - A plugin for AsciiDoctor.
* [asdf-direnv](https://github.com/redxtech/zsh-asdf-direnv) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf) and [direnv](https://github.com/asdf-community/asdf-direnv).
* [asdf](https://github.com/kiurchv/asdf.plugin.zsh) - Integration and completions for [asdf](https://github.com/asdf-vm/asdf), the extendable version manager, with support for Ruby, Node.js, Elixir, Erlang and more.
* [assume-role](https://github.com/weizard/assume-role) - ZSH plugin to allow you to assume AWS IAM roles easily. Includes completions.
* [async](https://github.com/mafredri/zsh-async) - Library for running asynchronous tasks in ZSH without requiring any external tools. Allows you to run multiple asynchronous jobs, enforce unique jobs (multiple instances of the same job will not run), flush all currently running jobs and create multiple workers (each with their own jobs).
* [atom-plugin](https://github.com/CorradoRossi/oh-my-zsh-atom-plugin) - Based on the [Sublime](https://github.com/valentinocossar/sublime) plugin, lets you launch a file or folder in [Atom](https://atom.io) from [iTerm 2](https://iterm2.com).
* [atuin](https://github.com/ellie/atuin) - Replaces your existing shell history with a SQLite database, and records additional context for your commands. Additionally, it provides optional and fully encrypted synchronisation of your history between machines, via an Atuin server.
* [auto-color-ls](https://github.com/gretzky/auto-color-ls) - Automatically list directories with `colorls`.
* [auto-fortune-cowsay](https://github.com/babasbot/auto-fortune-cowsay-zsh) - Prints out an ASCII picture of a cow saying a random epigram on every zsh start.
* [auto-fu.zsh](https://github.com/hchbaw/auto-fu.zsh) - Automatic complete-word and list-choices. Originally incr-0.2.zsh by y.fujii <y-fujii at mimosa-pudica.net>.
* [auto-ls (commanda-panda)](https://github.com/commanda-panda/zsh-auto-ls) - Automatically runs `ls` or `color-ls` if available on `cd`.
* [auto-ls (desyncr)](https://github.com/desyncr/auto-ls) - Automatically `ls` when cding to a new directory.
* [auto-notify](https://github.com/MichaelAquilina/zsh-auto-notify) - Automatically sends out a notification when a long running task has completed.
* [auto-nvm](https://github.com/manlao/zsh-auto-nvm) - Automatically switches to the node version specified in a given directory.
* [autocomplete](https://github.com/marlonrichert/zsh-autocomplete) - Automatically lists completions as you type and provides intuitive keybindings for selecting and inserting them.
* [autodotenv](https://github.com/nocttuam/autodotenv) - Will prompt you to load variables when you `cd` into a directory containing a `.env` file.
* [autoenv-extended](https://github.com/zpm-zsh/autoenv) - Extended version of the [zsh-autoenv](https://github.com/Tarrasch/zsh-autoenv) plugin.
* [autoenv](https://github.com/Tarrasch/zsh-autoenv) - If a directory contains a `.env` file, it will automatically be executed when you `cd` into it.
* [autojump](https://github.com/wting/autojump) - A `cd` command that learns - easily navigate directories from the command line. Install autojump-zsh for best results.
* [autopair](https://github.com/hlissner/zsh-autopair) - A ZSH plugin for auto-closing, deleting and skipping over matching delimiters. Only tested on ZSH 5.0.2 or later.
* [autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) - [Fish](https://fishshell.com/)-like fast/unobtrusive autosuggestions for ZSH.
* [autoswitch-virtualenv](https://github.com/MichaelAquilina/zsh-autoswitch-virtualenv) - ZSH plugin to automatically switch python virtualenvs and pipenvs when traversing directories. Automatically detects pipenv and poetry projects.
* [autoupdate-antigen](https://github.com/unixorn/autoupdate-antigen.zshplugin) - Antigen doesn't do automatic updates like oh-my-zsh. This plugin adds auto updating for antigen, both of antigen and the bundles loaded in your configuration.
* [autoupdate-oh-my-zsh-plugins](https://github.com/TamCore/autoupdate-oh-my-zsh-plugins) - oh-my-zsh doesn't automatically update non-core plugins, this adds plugin autoupdating to oh-my-zsh.
* [aws-cli-mfa](https://github.com/joepjoosten/aws-cli-mfa-oh-my-zsh) - AWS CLI MFA plugin based on sweharris' [aws-cli-mfa](https://github.com/sweharris/aws-cli-mfa). Supports specifying mfa_device in profile.
* [aws-mfa](https://github.com/FreebirdRides/oh-my-zsh-aws-mfa) - Plugin for AWS MFA.
* [aws-plugin](https://github.com/pookey/zsh-aws-plugin) - Adds helper functions for `aws` command. Includes mfa and assume-role helpers.
* [aws-upload](https://github.com/borracciaBlu/aws-upload-zsh) - Boost your productivity with `aws-upload`.
* [aws-vault (blimmer)](https://github.com/blimmer/zsh-aws-vault) - Plugin for [aws-vault](https://github.com/99designs/aws-vault). Includes tab completions.
* [aws-vault (reegnz)](https://github.com/reegnz/aws-vault-zsh-plugin) - Makes it easier to use [aws-vault](https://github.com/99designs/aws-vault) in your environment.
* [aws2](https://github.com/drgr33n/oh-my-zsh_aws2-plugin) - Provides completion support for version 2 of the [awscli](https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html) and a few utilities to manage AWS profiles and display them in the prompt.
* [awsume](https://github.com/Sordie/AWSume) - Plugin that enables showing the current [awsume](https://github.com/trek10inc/awsume) profile.
* [azcli](https://github.com/dmakeienko/azcli) - Helper for using the azure cli tools.
* [background](https://github.com/zpm-zsh/background) - ZSH plugin which executes functions in the background.
* [base16](https://github.com/chriskempson/base16-shell) - Adds script to allow you to change your shell's default ANSI colors but most importantly, colors 17 to 21 of your shell's 256 colorspace (if supported by your terminal). This script makes it possible to honor the original bright colors of your shell (e.g. bright green is still green and so on) while providing additional base16 colors to applications such as [Vim](https://www.vim.org).
* [baseballfunfacts](https://github.com/richardmoyer/baseballfunfacts) - Print random baseball related "fun facts" in your shell. Depends on `fortune` and `cowsay` being installed.
* [basex](https://github.com/dirkk/zsh-basex) - Adds several [BaseX](http://basex.org/) aliases for simplified usage.
* [bash-quote](https://github.com/jtprog/bash-quote) - Get random quote from Bash.im.
* [bash](https://github.com/chrissicool/zsh-bash) - Makes ZSH more Bash compatible. It redefines the source command to act more like `bash` does. It also enables `bash` completions.
* [battery_state](https://github.com/Jactry/zsh_battery_state) - Show battery state in right-prompt.
* [bd](https://github.com/Tarrasch/zsh-bd) - Jump back to a specific directory, without doing `cd ../../..`.
* [bepoptimist](https://github.com/sheoak/zsh-bepoptimist) - Remap ZSH `vi`-mode for French [bépo keyboard](http://bepo.fr/wiki/Accueil).
* [betterbrew](https://github.com/timothyrowan/betterbrew-zsh-plugin) - Add more command aliases for `brew`
* [bitbucket-git-helpers](https://github.com/unixorn/bitbucket-git-helpers.plugin.zsh) - Adds helper scripts to allow you to create bitbucket PRs or open a directory in the current branch.
* [blackbox](https://github.com/StackExchange/blackbox) - [Stack Exchange](https://stackexchange.com)'s toolkit for storing keys/credentials securely in a `git` repository.
* [bofh](https://github.com/fundor333/bofh) - Adds functions to display random bofh fortunes.
* [bol](https://github.com/ikhurramraza/bol) - Prints a random quote when you open a terminal window.
* [boss-docker](https://github.com/bossjones/boss-docker-zsh-plugin) - Manages `docker` on OSX.
* [boss-git](https://github.com/bossjones/boss-git-zsh-plugin) - Adds some convenience aliases for `git`.
* [branch-manager](https://github.com/elstgav/branch-manager) - A plugin for managing `git` branches.
* [brew (rhuang2014)](https://github.com/rhuang2014/brew) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [brew (wolffaxn)](https://github.com/wolffaxn/brew-zsh-plugin) - Standalone plugin for the [Homebrew](https://brew.sh/) Package Manager.
* [browse-commit](https://github.com/adolfoabegg/browse-commit) - A plugin that lets you open any commit in your browser from the command line.
* [bruse](https://github.com/aubreypwd/zsh-plugin-bruse) - Makes it easy to `brew link` different versions of packages.
* [bumblebee](https://github.com/Niverton/zsh-bumblebee-plugin) - A plugin to toggle optirun in the command line.
* [c](https://github.com/sebastiangraz/c) - Adds some `git` shortcuts.
* [calc](https://github.com/arzzen/calc.plugin.zsh) - A calculator for ZSH.
* [calibre-zaw-source](https://github.com/junkblocker/calibre-zaw-source) - [Calibre - E-book management](https://calibre-ebook.com/) source for [zaw](https://github.com/zsh-users/zaw)
* [caniuse](https://github.com/walesmd/caniuse.plugin.zsh) - Add [Can I Use...](https://caniuse.com) support to ZSH.
* [careful_rm](https://github.com/MikeDacre/careful_rm) - A wrapper for `rm` that adds trash/recycling and useful warnings.
* [case](https://github.com/rtuin/zsh-case) - A ZSH plugin that adds two aliases `tolower` and `toupper` to switch output case.
* [cd-gitroot](https://github.com/mollifier/cd-gitroot) - A ZSH plugin to `cd` to the `git` repository root directory.
* [cd-reminder](https://github.com/bartboy011/cd-reminder) - Display reminders when `cd`-ing into specified directories.
* [cd-reporoot](https://github.com/P4Cu/cd-reporoot) - A ZSH plugin to `cd` to the current repository checkout's root directory.
* [cd-ssh](https://github.com/jeffwalter/zsh-plugin-cd-ssh) - `ssh` to a server when you accidentally `cd` to it.
* [cdbk](https://github.com/MikeDacre/cdbk) - A ZSH plugin to allow easy named directory creation - shortcuts to any directory you want.
* [cdc](https://github.com/evanthegrayt/cdc) - Makes it easier to change directories to directories that are subdirs of a user-defined list of directories. Includes tab-completion, session history and `pushd`, `popd` and `dirs` equivalents.
* [cdr](https://github.com/willghatch/zsh-cdr) - Easy setup of cdr for ZSH.
* [change-case](https://github.com/mtxr/zsh-change-case) - Plugin for fast swap between upper and lower case in your command line. :sunglasses:
* [cheatsheet](https://github.com/0b10/cheatsheet) - Plugin to easily view, create, and edit cheatsheets.
* [check-deps](https://github.com/zpm-zsh/check-deps) - Helper for ZSH plugins that allows them to show how to install any missing dependencies. Works on Debian (and derivatives like Ubuntu), Arch and its derivatives, Nodejs and ZSH plugins if you are using the [zpm](https://github.com/zpm-zsh/zpm) framework.
* [chgo](https://github.com/sbfaulkner/chgo-plugin-zsh) - Clone of chruby modified to make it easy to switch between multiple Go versions.
* [clean-project](https://github.com/wwilsman/zsh-clean-project) - Remove files from projects (automatically by default). Useful for keeping `.DS_Store` and `Thumbs.db` files from cluttering your directories.
* [clipboard](https://github.com/zpm-zsh/clipboard) - Adds a cross-platform helper function to access the system clipboard. Works on macOS, X11 (and Wayland) and Cygwin.
* [cmd-architect](https://github.com/psprint/zsh-cmd-architect) - Build commands from what's in history and at prompt, move, delete, add command segments and search history with multi-word queries.
* [cmd-status](https://github.com/BlaineEXE/zsh-cmd-status) - Reports the status of commands including return code and duration.
* [cmdtime](https://github.com/tom-auger/cmdtime) - Displays the duration of a command to the terminal forked from the [timer](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/timer) plugin.
* [code-review](https://github.com/xorkevin/code-review-zsh) - Launches `git difftool` on `git merge-base target_branch base_branch` and `target_branch`.
* [code-stats](https://gitlab.com/code-stats/code-stats-zsh) - Counts keypresses and logs stats to [Code::Stats](https://codestats.net/).
* [colored-man-pages-mod](https://github.com/zuxfoucault/colored-man-pages_mod) - Forked from [ohmyzsh/ohmyzsh/plugins/colored-man-pages](https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/colored-man-pages/colored-man-pages.plugin.zsh). Colorizes `man` output.
* [colored-man-pages](https://github.com/ael-code/zsh-colored-man-pages) - Colorize `man` pages.
* [colorize](https://github.com/zpm-zsh/colorize) - Colorize the output of various programs.
* [colorls](https://github.com/Kallahan23/zsh-colorls) - Defines a few helpful shortcuts to some colorls functions.
* [colors (Tarrasch)](https://github.com/Tarrasch/zsh-colors) - Makes it easier to colorize text from the CLI. `red foo` just works.
* [colors (zpm-zsh)](https://github.com/zpm-zsh/colors) - Enhanced colors for ZSH.
* [command-execution-timer](https://github.com/olets/command-execution-timer) - Displays the time an interactive shell command takes to execute.
* [command-not-found](https://github.com/Tarrasch/zsh-command-not-found) - A mirror of the oh-my-zsh command-not-found plugin so you don't have to include all of oh-my-zsh.
* [command-note](https://github.com/KKRainbow/zsh-command-note.plugin) - Record complex commands and comment on them.
* [command-time](https://github.com/popstas/zsh-command-time) - Show execution time for long commands in ZSH and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Similar to `REPORTTIME` builtin, but only outputs when user + system time >= `REPORTTIME`.
* [compe](https://github.com/tamago324/compe-zsh) - Add completion for [nvim-compe](https://github.com/hrsh7th/nvim-compe).
* [completion-generator](https://github.com/RobSis/zsh-completion-generator) - This plugin tries to read the list of options from the help text of programs and generate a completion function automatically. Note that this doesn't do it automatically, you have to explicitly call the generator to create a completion script.
* [copy-pasta](https://github.com/ChrisPenner/copy-pasta) - Copy and paste files in your terminal like you would in a GUI.
* [copyzshell](https://github.com/rutchkiwi/copyzshell) - A ZSH plugin to copy your shell configuration to another machine over `ssh`.
* [crash](https://github.com/molovo/crash) - Adds proper error handling, exceptions and try/catch for ZSH.
* [crayon-syntax](https://github.com/gsemet/crayon-syntax-zsh) - ZSH syntax highlighting for the Crayon Plugin for Wordpress.
* [cros-auto-notify](https://github.com/D3STY/cros-auto-notify-zsh) - Automatically sends out a notification when a long running task has completed. Works with macOS and linux (if `hterm-notify` is installed).
* [crypto-prices](https://github.com/vincentdnl/zsh-crypto-prices) - Add a [powerlevel9k](https://github.com/bhilburn/powerlevel9k) segment with the current bitcoin price.
* [crystal](https://github.com/veelenga/crystal-zsh) - A plugin for [Crystal](https://github.com/crystal-lang/crystal).
* [czhttpd](https://github.com/jsks/czhttpd) - A simple http server written in 99.9% pure ZSH.
* [declare-zsh](https://github.com/zdharma/declare-zsh) - A command-line parser for Zinit commands in `zshrc`.
* [deepx](https://github.com/GetAmbush/deepx-zsh-plugin) - Collection of useful and fun commands to improve workflow and quality of life.
* [deer](https://github.com/Vifon/deer) - A file navigator for ZSH heavily inspired by [ranger](https://ranger.github.io/).
* [depot-tools](https://github.com/kuoe0/zsh-depot-tools) - Simple oh-my-zsh plugin for installing the chromium depot_tools. Installing this plugin will put all of the chromium depot_tools in your path automatically.
* [dev](https://github.com/sbfaulkner/dev-plugin-zsh) - Provides a lightweight version of [Shopify's internal dev tool](https://devproductivity.io/dev-shopifys-all-purpose-development-tool/index.html)
* [diff-so-fancy](https://github.com/zdharma/zsh-diff-so-fancy) - Simplify installing the `diff-so-fancy` project into your user account.
* [diractions](https://github.com/AdrieanKhisbe/diractions) - Allow you to map a short logical/mnemonic name to directories to quickly access them, or perform actions in them.
* [dircolors-solarized (joel-porquet)](https://github.com/joel-porquet/zsh-dircolors-solarized) - Solarized dircolors plugin, with options for dark or light terminal backgrounds.
* [dircolors-solarized (pinelibg)](https://github.com/pinelibg/dircolors-solarized-zsh) - Enables [Solarized Color Theme for GNU ls](https://github.com/seebi/dircolors-solarized).
* [dircycle](https://github.com/michaelxmcbride/zsh-dircycle) - Cycle through the directory stack.
* [directory-history](https://github.com/tymm/zsh-directory-history) - A per directory history for ZSH which implements forward/backward navigation as well as substring search in a directory sensitive manner.
* [direnv](https://github.com/ptavares/zsh-direnv) - A plugin for installing and loading [direnv](https://github.com/direnv/direnv.git). Inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv).
* [dirrc](https://github.com/gmatheu/shell-plugins) - Executes `.dirc` when present in a directory you `cd` into.
* [dirstack](https://github.com/gepoch/oh-my-zsh-dirstack) - Plugin for displaying dirstack info on a single line.
* [doas](https://github.com/anatolykopyl/doas-zsh-plugin) - Easily prefix your current or previous commands with `doas` by pressing `esc` twice.
* [docker-aliases](https://github.com/webyneter/docker-aliases) Docker aliases for everyday use.
* [docker-compose](https://github.com/sroze/docker-compose-zsh-plugin) Show docker container status in your prompt.
* [docker-helpers](https://github.com/unixorn/docker-helpers.zshplugin) - A collection of docker helper scripts.
* [docker-machine](https://github.com/asuran/zsh-docker-machine) - A docker-machine plugin for ZSH.
* [docker-run](https://github.com/rawkode/zsh-docker-run) - Go back to running your commands "naturally", we'll handle the container.
* [dogesh](https://github.com/keithhamilton/oh-my-dogesh) - Dogification plugin.
* [dotbare](https://github.com/kazhala/dotbare) - Interactive dotfile management with the help of `fzf`.
* [dotfiles](https://github.com/vladmyr/dotfiles-plugin) - Keep your dotfiles in sync across multiple machines using `git`.
* [dotpyvenv](https://github.com/jeanpantoja/dotpyvenv) - Automagically switch to a python virtual environment located (that you previously have created with virtualenv program) in a directory named `.pyvenv` when you `cd` into a directory.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for ZSH that provides `dropbox-cli` and `dropbox-uploader` commands.
* [dune-quotes](https://github.com/brokendisk/dune-quotes) - Random Dune quote generator plugin.
* [duration](https://github.com/rtakasuke/zsh-duration) - Displays command duration if it exceeds a user-settable run time.
* [dwim](https://github.com/oknowton/zsh-dwim) - Attempts to predict what you will want to do next. It provides a key binding (control-u) that will replace the current (or previous) command line with the command you will want to run next.
* [easy-motion](https://github.com/IngoHeimbach/zsh-easy-motion) - A port of [vim-easymotion](https://github.com/easymotion/vim-easymotion) for ZSH.
* [ec2ssh](https://github.com/h3poteto/zsh-ec2ssh) - List EC2 instances and `ssh` login to the instances easily.
* [editing-workbench](https://github.com/psprint/zsh-editing-workbench) - Adds sane, complex command line editing (e.g. incremental history _word_ completion).
* [edward cli](https://github.com/matthieusb/zsh-edward) - Adds smart completions and alises for [edward CLI micro-service launcher](https://github.com/yext/edward).
* [elixir](https://github.com/gusaiani/elixir-oh-my-zsh) - Adds shortcuts for Elixir, IEX, Mix, Kiex and Phoenix.
* [emacs (cowboyd)](https://github.com/cowboyd/zsh-emacs) - Make Emacs the default for CLI operations like editing git commit messages; set up handy aliases.
* [emacs (flinner)](https://github.com/Flinner/zsh-emacs) - Uses the Emacs daemon capability, allowing the user to quickly open frames, whether they are opened in a terminal via a ssh connection, or X frames opened on the same host.
* [emoji-cli](https://github.com/b4b4r07/emoji-cli) - :scream: Emoji completion on the command line.
* [emoji-fzf](https://github.com/pschmitt/emoji-fzf.zsh) - Configurable ZSH plugin for the excellent [emoji-fzf](https://github.com/noahp/emoji-fzf). It is heavily inspired by [emoji-cli](https://github.com/b4b4r07/emoji-cli).
* [emojis](https://github.com/MichaelAquilina/zsh-emojis) - Adds numerous ascii art emojis to your environment in convenient variables.
* [enhancd](https://github.com/b4b4r07/enhancd) - A simple tool that provides an enhanced `cd` command by memorizing all directories visited by a user and use it for the pathname resolution.
* [envrc](https://github.com/fabiogibson/envrc-zsh-plugin) - Automatically loads and unloads environment variables if a `.envrc` file is found in a directory.
* [escape-backtick](https://github.com/bezhermoso/zsh-escape-backtick) - Quickly insert escaped backticks when double-tapping "`".
* [evalcache](https://github.com/mroth/evalcache) - Cache the output of a binary initialization command, to help lower shell startup time.
* [evil-registers](https://github.com/zsh-vi-more/evil-registers) - Extends ZLE vi commands to remotely access named registers of the vim and nvim editors, and system selection and clipboard.
* [exa (DarrinTisdale)](https://github.com/DarrinTisdale/zsh-aliases-exa) - Enables a number of aliases extending [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (hermitmaster)](https://github.com/hermitmaster/zsh-exa-plugin) - Adds some aliases for [exa](https://the.exa.website), the modern replacement for `ls`.
* [exa (mohamedelashri)](https://github.com/MohamedElashri/exa-zsh) - Adds aliases for [exa](https://the.exa.website), a modern replacement for `ls`.
* [exa (ptavares)](https://github.com/ptavares/zsh-exa) - Installs and loads [exa](https://github.com/ogham/exa.git).
* [exa (ritchies)](https://github.com/RitchieS/zsh-exa/) - Adds aliases to make using [exa](https://github.com/ogham/exa.git) easier.
* [exercism](https://github.com/fabiokiatkowski/exercism.plugin.zsh) - A plugin for [exercism.io](http://exercism.io/).
* [expand-ealias](https://github.com/zigius/expand-ealias.plugin.zsh) - Expand specific aliases with space.
* [expand](https://github.com/MenkeTechnologies/zsh-expand) - Expands regular aliases, global aliases, incorrect spellings and phrases, globs, history expansion and $parameters with the spacebar key.
* [explain-shell](https://github.com/gmatheu/shell-plugins) - Opens commands on [explainshell.com](https://explainshell.com).
* [extend-history](https://github.com/xav-b/zsh-extend-history) - Extends command history by adding exit code for each command in the history.
* [f-shortcuts](https://github.com/zpm-zsh/f-shortcuts) - Makes a shortcuts toolbar using F1 to F12 keys.
* [fancy-ctrl-z](https://github.com/mdumitru/fancy-ctrl-z) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [fast-alias-tips](https://github.com/sei40kr/zsh-fast-alias-tips) - Helps remember the aliases you defined and forgot about. Ported from [djui/alias-tips](https://github.com/djui/alias-tips).
* [fast-syntax-highlighting](https://github.com/zdharma/fast-syntax-highlighting) - Optimized and improved `zsh-users/zsh-syntax-highlighting` – better response times, switchable highlight themes.
* [fav](https://github.com/ddnexus/fav) - ZSH/[fzf](https://github.com/junegunn/fzf) plugin that makes it really easy to add and recall named favorites of your important directories.
* [favorite-directories](https://github.com/seletskiy/zsh-favorite-directories) - Fast jumps to your favorite directories.
* [figures](https://github.com/zpm-zsh/figures) - Unicode symbols for ZSH.
* [firebase (Seqi)](https://github.com/Seqi/firebase-zsh) - Display the current working project or project alias when in a Firebase project directory or subdirectory.
* [firebase (rmrs)](https://github.com/rmrs/firebase-zsh) - Add an indicator in the prompt that you're in a directory with a `firebase.json` file (aka "firebase project").
* [fixnumpad-osx](https://github.com/zackintosh/fixnumpad-osx.plugin.zsh/blob/master/fixnumpad-osx.plugin.zsh) - Enables numpad keys of Apple keyboards to be recognized in ZSH.
* [flow-plugin](https://github.com/sandstorm/oh-my-zsh-flow-plugin) - This plugin makes the `flow` command available inside every subdirectory of the TYPO3 Flow distribution.
* [fnm](https://github.com/dominik-schwabe/zsh-fnm) - Installs and loads the [Fast Node Manager (fnm)](https://github.com/Schniz/fnm) if it is missing.
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` which takes advantage of fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [functional](https://github.com/Tarrasch/zsh-functional) - ZSH higher order functions.
* [fuzzy-search-and-edit](https://github.com/seletskiy/zsh-fuzzy-search-and-edit) - ZSH plugin for fuzzy searching files and instantly opening a matched file on matched line.
* [fz](https://github.com/changyuheng/fz) - Seamlessly adds fuzzy search to [z](https://github.com/rupa/z)'s tab completion and lets you easily jump around among directories in your history.
* [fzf (unixorn)](https://github.com/unixorn/fzf-zsh-plugin/tree/master) - Enables [fzf](https://github.com/junegunn/fzf) history and file searches.
* [fzf-fasd](https://github.com/wookayin/fzf-fasd) - Integrates [fzf](https://github.com/junegunn/fzf) and [fasd](https://github.com/clvv/fasd) --- tab completion of `z` with fzf's fuzzy search!
* [fzf-finder](https://github.com/leophys/zsh-plugin-fzf-finder) - Plugin to have a cool search keybinding with [fzf](https://github.com/junegunn/fzf) and (optionally) [bat](https://github.com/sharkdp/bat). Searches in the local tree of subdirectories for files.
* [fzf-history-search](https://github.com/joshskidmore/zsh-fzf-history-search) - Replaces `Ctrl+R` with an [fzf](https://github.com/junegunn/fzf)-driven history search that includes date/times.
* [fzf-it](https://github.com/micakce/fzf-it) - Make any command interactive wrapping it with FZF functionality.
* [fzf-marks](https://github.com/urbainvaes/fzf-marks) - Little script to create, navigate and delete bookmarks in `bash` and `zsh`, using the fuzzy finder [fzf](https://github.com/junegunn/fzf).
* [fzf-pass](https://github.com/smeagol74/zsh-fzf-pass) - Better handling of passwords using [fzf](https://github.com/junegunn/fzf).
* [fzf-prezto](https://github.com/lildude/fzf-prezto) - Prezto plugin that finds where [fzf](https://github.com/junegunn/fzf) has been installed and enables its auto-completion and key-bindings.
* [fzf-tab](https://github.com/Aloxaf/fzf-tab) - Replace ZSH's default completion selection menu with [fzf](https://github.com/junegunn/fzf).
* [fzf-utils](https://github.com/redxtech/zsh-fzf-utils) - Provides functions to kill proceses and find in path with [fzf](https://github.com/junegunn/fzf).
* [fzf-widgets](https://github.com/ytet5uy4/fzf-widgets) - Adds some ZLE widgets for [fzf](https://github.com/junegunn/fzf).
* [fzf-z](https://github.com/andrewferrier/fzf-z) - Brings together the *z* plugin and *fzf* to allow you to easily browse recently used directories at any point on the command line.
* [fzy](https://github.com/aperezdc/zsh-fzy) - Plugin that uses [fzy](https://github.com/jhawthorn/fzy) for certain fuzzy matching operations.
* [gcloud-project](https://github.com/avivl/gcloud-project) - Easy selection of Google Cloud Projects.
* [geeknote](https://github.com/s7anley/zsh-geeknote) - [Geeknote](https://geeknote.me) plugin for ZSH.
* [gentoo](https://github.com/MattiaG-afk/gentoo-ohmyzsh) - Adds some aliases and functions to work with Gentoo Linux.
* [geometry-datetime](https://github.com/desyncr/geometry-datetime) - [Geometry](https://github.com/geometry-zsh/geometry) datetime plugin. Shows datetime (`date` unix command) in your prompt.
* [geometry-hydrate](https://github.com/jedahan/geometry-hydrate) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to remind you to hydrate.
* [geometry-npm-package-version](https://github.com/drager/geometry-npm-package-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's npm package version.
* [geometry-rust-version](https://github.com/drager/geometry-rust-version) - [Geometry](https://github.com/geometry-zsh/geometry) plugin to display the current folder's Rust version when either a `.rs` or `Cargo.toml` is present.
* [get-jquery](https://github.com/voronkovich/get-jquery.plugin.zsh) - Plugin for fast downloading jQuery library from [https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com](https://github.com/unixorn/awesome-zsh-plugins/blob/master/code.jquery.com).
* [ghost-zeus](https://github.com/fontno/ghost_zeus) - Lets you use [zeus](https://github.com/burke/zeus) with normal rails commands.
* [gimme](https://github.com/folixg/gimme-ohmyzsh-plugin) - Manage Go installations with gimme.
* [git-acp](https://github.com/MenkeTechnologies/zsh-git-acp) - Take the current command line as the commit message and then run git pull, add, commit and push with one keystroke.
* [git-add-remote](https://github.com/caarlos0/git-add-remote) - Easily add the upstream remote to your `git` fork.
* [git-aliases (mdumitru)](https://github.com/mdumitru/git-aliases) - Broken out version of the version in [oh-my-zsh](http://ohmyz.sh/) so users of other frameworks don't have to import all of oh-my-zsh.
* [git-aliases.zsh](https://github.com/peterhurford/git-aliases.zsh) - Creates a lot of useful aliases for combinations of commonly used `git` commands.
* [git-branches](https://github.com/Schroefdop/git-branches) - Makes a menu of `git` branches you can switch to without having to type long branch names.
* [git-complete-urls](https://github.com/rapgenic/zsh-git-complete-urls) - Enhance `git` completion to include in the remotes completion (e.g. from `git clone`) any URL in the clipboard.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Extra `git` helper scripts packaged as a plugin.
* [git-flow-avh](https://github.com/nekofar/zsh-git-flow-avh) - Adds short aliases for the `git-flow` commands.
* [git-fuzzy](https://github.com/bigH/git-fuzzy) - A CLI interface to `git` that relies heavily on [`fzf`](https://github.com/junegunn/fzf).
* [git-ignore](https://github.com/laggardkernel/git-ignore) - Generates `.gitignore` files from gitignore.io **offline**. `fzf`, completion, preview integrated.
* [git-it-on](https://github.com/peterhurford/git-it-on.zsh) - Adds ability to open a folder in your current branch on GitHub.
* [git-lfs](https://github.com/nekofar/zsh-git-lfs) - Adds short aliases for the git-lfs commands.
* [git-plugin](https://github.com/rcruzper/zsh-git-plugin) - Adds some functions for `git`.
* [git-prompt-useremail](https://github.com/mroth/git-prompt-useremail) - Adds prompt reminders for `git` user.email.
* [git-prune (diazod)](https://github.com/diazod/git-prune) - Allows you to delete all branches that are already merged in your local repository and/or that were merged in your remote origin repository.
* [git-prune (seinh)](https://github.com/Seinh/git-prune) - Plugin that simplifies deleting merged branches.
* [git-scripts](https://github.com/packruler/zsh-git-scripts) - Adds `git-squash-branch` and `git-remove-merged` commands.
* [git-secret](https://github.com/sobolevn/git-secret) - A bash-tool to store your private data inside a `git` repository.
* [git-smart-commands](https://github.com/seletskiy/zsh-git-smart-commands) - Adds extra `git` commands to make some common `git` usages more efficient.
* [git-sync](https://github.com/caarlos0/zsh-git-sync) - A ZSH plugin to sync `git` repositories and clean them up.
* [git](https://github.com/davidde/git) - Replacement for the stock oh-my-zsh git plugin. Provides quite a few useful aliases and functions. The motivation to replace the default plugin stems from the fact that it comes with some inconsistencies that make a few popular commands rather unintuitive, so this plugin makes the aliases consistent.
* [gitcd (SukkaW)](https://github.com/SukkaW/zsh-gitcd) - Adds command to `git clone` a repository and `cd` into the resulting directory.
* [gitcd (viko16)](https://github.com/viko16/gitcd.plugin.zsh) - Automatically `cd` to a `git` working directory after cloning it.
* [gitfast](https://github.com/tevren/gitfast-zsh-plugin) - Updated fork of oh-my-zsh gitfast plugin.
* [gitgo](https://github.com/ltj/gitgo) - Open a Github/Gitlab repository in your browser from the command line (macOS only).
* [github-issues](https://github.com/zdharma/zsh-github-issues) - Subscribe to projects on Github and receive within shell (under prompt) notifications about new issues.
* [gitignore](https://github.com/voronkovich/gitignore.plugin.zsh) - Plugin for creating `.gitignore` files.
* [gitio](https://github.com/denysdovhan/gitio-zsh) - A ZSH plugin for generating a GitHub short URL using [git.io](https://git.io).
* [gitstatus](https://github.com/Insert-Creative-Name-Here/gitstatus.zsh) -  Makes it easy to show your `git` status in your prompt.
* [gitsync](https://github.com/washtubs/gitsync) - ZSH plugin to improve workflows for one person developing on the same repository on multiple machines.
* [goenv (CDA0)](https://github.com/CDA0/zsh-goenv/blob/master/zsh-goenv.plugin.zsh) - Plugin for installing, updating and loading goenv.
* [goenv (bbenne10)](https://github.com/bbenne10/goenv) - Manage `$GOPATH` similarly to Python's virtualenvwrapper.
* [going_places](https://github.com/or17191/going_places) - A plugin that helps to use, create and maintain a list of shell locations.
* [gpg-agent](https://github.com/axtl/gpg-agent.zsh) - Plugin that tries to do the right thing when it comes to setting up the GPG agent to act as an SSH agent as well on macOS.
* [gpg-crypt](https://github.com/Czocher/gpg-crypt) - ZSH plugin to encrypt and decrypt files or directories in place.
* [grep2awk](https://github.com/joepvd/grep2awk) - ZLE widget to transform `grep` command into `awk` command.
* [grunt-plugin](https://github.com/clauswitt/zsh-grunt-plugin) - Add autocompletion for `grunt`.
* [gsh](https://github.com/cjayross/gsh) - Collection of helper functions for `git`
* [gtm-terminal-plugin](https://github.com/git-time-metric/gtm-terminal-plugin) - terminal plugin for [git time metrics](https://github.com/git-time-metric/gtm/blob/master/README.md).
* [gtr](https://github.com/Zocker1999NET/zsh-gtr) - Allows fast tagging of a release in git using the tag name **release-YYYY-MM-DD-HH-MM** and headline **Release YYYY-MM-DD HH:MM**.
* [guish](https://github.com/gcarrarom/oh-my-guish) - Collection of utility functions and aliases.
* [gumsible](https://github.com/Lowess/gumsible-oh-my-zsh-plugin) - Wrapper plugin for [Molecule](https://molecule.readthedocs.io/en/latest/index.html).
* [gunstage](https://github.com/LucasLarson/gunstage) - There are at least eight ways to unstage files in a `git` repository. This is a command-line shell plugin for undoing `git add`.
* [gvm (dgnest)](https://github.com/dgnest/zsh-gvm-plugin) - A gvm (Go version manager) plugin for ZSH.
* [gvm (yerinle)](https://github.com/yerinle/zsh-gvm) - Provides autocompletion for `gvm` (Groovy enVironment Manager).
* [hab](https://github.com/alexdesousa/hab) - Automatically loads OS environment variables defined in the file `.envrc` if it's found when changing to a new directory.
* [hacker-quotes](https://github.com/oldratlee/hacker-quotes) - Outputs a hacker quote randomly when you open a terminal.
* [hadoop-plugin](https://github.com/valek/zsh-hadoop-plugin) - Adds some convenience aliases for hadoop functions.
* [hanami](https://github.com/davydovanton/hanami-zsh) - ZSH plugin for [hanami](http://hanamirb.org) projects.
* [hangul](https://github.com/gomjellie/zsh-hangul) - Auto correct hangul(한글, korean) to english when it was supposed to be typed english. 영어를 타이핑 해야되는데 한글로 타이핑된경우 자동으로 수정합니다.
* [hbt](https://github.com/lzambarda/hbt) - Heuristic ZSH suggestion system based on past command usage.
* [hints](https://github.com/joepvd/zsh-hints) - Display glob and parameter flags and other non completable info right under your editing buffer.
* [hipchat](https://github.com/robertzk/hipchat.zsh) - Send hipchat messages from the shell.
* [hist](https://github.com/marlonrichert/zsh-hist) - Edit your history in ZSH, without ever leaving the command line.
* [histdb](https://github.com/larkery/zsh-histdb) - Stores your history in an SQLite database. Can be integrated with [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions).
* [history-enquirer](https://github.com/zthxxx/zsh-history-enquirer) - Enhances history search with more interaction and a multiline selection menu. Requires nodejs.
* [history-filter](https://github.com/MichaelAquilina/zsh-history-filter) - Allows you to specify patterns that will automatically exclude commands from being inserted into your permanent history. Particularly useful for preventing secrets being written.
* [history-here](https://github.com/leonjza/history-here) - Binds `^G` to quickly toggle the current shell history file location.
* [history-popup](https://github.com/lcrespom/oh-my-zsh-history-popup) - Captures the PageUp key and uses `dialog` to open a popup menu with the history, so the user can interactively navigate through it and pick the history line to bring back to the prompt.
* [history-search-multi-word](https://github.com/zdharma/history-search-multi-word) - A syntax highlighted, multi-word history searcher for ZSH, bound to Ctrl-R, with advanced functions (e.g. bump of history entry to top of history).
* [history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - Needs to be loaded after `zsh-syntax-highlighting`, or they'll both break. You'll also need to bind keys to its functions, details are in the README.md.
* [history-sync](https://github.com/wulfgarpro/history-sync) - An Oh My Zsh plugin for GPG encrypted, Internet synchronized ZSH history using `git`.
* [history](https://github.com/b4b4r07/zsh-history) - Extend history so that it can be queried by SQL.
* [hitokoto](https://github.com/derry96/hitokoto) - Displays a random quote from [hitokoto.cn](https://hitokoto.cn/).
* [homeassistant-cli](https://github.com/frosit/zsh-plugin-homeassistant-cli) - Provides completion and (configuration) helpers for the [Home Assistant Command-line interface (hass-cli)](https://github.com/home-assistant/home-assistant-cli). and allows command line interaction with [Home Assistant](https://home-assistant.io/) instances.
* [homebrew](https://github.com/digitalraven/omz-homebrew) - Plugin for [homebrew](https://brew.sh) that supplements the one built into oh-my-zsh.
* [hooks](https://github.com/willghatch/zsh-hooks) - Add missing hooks - for plugins and personal use.
* [host-switch](https://github.com/LockonS/host-switch) - Make it easier to switch in different `/etc/hosts` files during development.
* [hub-ci-zsh-plugin](https://github.com/raymondjcox/hub-ci-zsh-plugin) - A simple plugin for adding `hub` ci-status to your ZSH theme.
* [hub](https://github.com/soraliu/zsh-hub) - ZSH plugin for forking model.
* [igit](https://github.com/ytakahashi/igit) - Interactive `git` commands using [fzf](https://github.com/junegunn/fzf).
* [ing](https://github.com/rummik/zsh-ing) - Streamlined `ping` output.
* [instant-repl](https://github.com/jandamm/instant-repl.zsh) - Activate a REPL for any command in your current ZSH session.
* [interactive-cd](https://github.com/changyuheng/zsh-interactive-cd) - Fish-like interactive tab completion for `cd`.
* [iosctl](https://github.com/obayer/iosctl) - Quickly access App, Data, and Log of the running simulator.
* [ipip](https://github.com/SukkaW/zsh-ipip) - Plugin for [IPIP](https://en.ipip.net).
* [iterm-tab-color](https://github.com/bernardop/iterm-tab-color-oh-my-zsh) - Adds function to set the tab color in iTerm2 and can automatically change color based on cwd or command being executed.
* [iterm-tab-colors](https://github.com/tysonwolker/iterm-tab-colors) - Automatically changes iTerm 2 tab color based on the current working directory.
* [iterm-touchbar](https://github.com/iam4x/zsh-iterm-touchbar) - Display iTerm2 feedback in the MacbookPro TouchBar (Current directory, git branch & status).
* [iterm2-colors](https://github.com/shayneholmes/zsh-iterm2colors) - Manage your iTerm 2's color scheme from the command line.
* [iterm2-tabs](https://github.com/gimbo/iterm2-tabs.zsh) - Set colors and titles of iTerm 2 tabs.
* [iterm2-utilities](https://github.com/decayofmind/zsh-iterm2-utilities) - Helps download various iTerm2 utilities and lets you omit cloning of the whole iterm2-website repository or relying on other repos which may be out of sync.
* [iterm2](https://github.com/laggardkernel/zsh-iterm2) - Packs iTerm's ZSH integration scripts into a ZSH plugin to avoid polluting your $HOME directory, with a negligible time increase of only 2ms.
* [jabba](https://github.com/2m/zsh-jabba) - Adds shell integration code and completions for the [jabba](https://github.com/shyiko/jabba) Java version manager.
* [java-zsh-plugin](https://github.com/Xetius/java-zsh-plugin) - Adds a `setjdk` command so you can switch easily between different versions of the jdk.
* [javaVersions](https://github.com/miguefl/javaVersions) - Change between different java versions with a single command.
* [jdk-switch](https://github.com/LockonS/jdk-switch) - A macOS-only plugin for switching between jdk versions.
* [jenkins](https://github.com/tomplex/jenkins-zsh) - A jenkins plugin for ZSH, heavily inspired by the excellent jira plugin.
* [jenv-lazy](https://github.com/shihyuho/zsh-jenv-lazy) - A ZSH plugin for lazy loading of jEnv.
* [jhipster](https://github.com/jhipster/jhipster-oh-my-zsh-plugin) - Adds commands for [jHipster](https://www.jhipster.tech/).
* [jira-plus](https://github.com/gerges/oh-my-zsh-jira-plus) - Create JIRA tickets from the command line.
* [jq](https://github.com/reegnz/jq-zsh-plugin) jq-repl with line editor functionality.
* [jvm](https://github.com/mgryszko/jvm) - Allows selection of JDK on macOS.
* [k](https://github.com/supercrabtree/k) - Directory listings for ZSH with `git` status decorations.
* [kctl](https://github.com/yzdann/kctl) - Add helper aliases for `kubectl`.
* [kill-node](https://github.com/vmattos/kill-node) - ZSH plugin for murdering `node` process families.
* [kitsunebook](https://github.com/d12frosted/kitsunebook.plugin.zsh) - KitsuneBook plugin for oh-my-zsh.
* [konsole-theme-changer](https://github.com/rocknrollMarc/zsh-konsole-theme-changer) - Toggle konsole theme from ZSH.
* [kube-aliases](https://github.com/Dbz/kube-aliases) - Adds functions and aliases to make working with `kubectl` more pleasant.
* [kube-ps1](https://github.com/jonmosco/kube-ps1) - ZSH plugin for `kubectl` that adds current context and namespace.
* [kubecolor (devopstales)](https://github.com/devopstales/kubecolor-zsh) - Adds aliases for the `kubecolor` command.
* [kubecolor (droctothorpe)](https://github.com/droctothorpe/kubecolor) - Simplify and colorize the output of `kubectl get events -w`
* [kubectl](https://github.com/mattbangert/kubectl-zsh-plugin) - ZSH plugin for managing `kubectl`.
* [kubectx (ptavares)](https://github.com/ptavares/zsh-kubectx) - Installs and loads [kubectx](https://github.com/ahmetb/kubectx).
* [kubectx (unixorn)](https://github.com/unixorn/kubectx-zshplugin) - Automatically installs [kubectx](https://github.com/ahmetb/kubectx) and `kubens`.
* [kubernetes](https://github.com/Dbz/zsh-kubernetes) - Add [kubernetes](https://kubernetes.io) helper functions and aliases.
* [lando (joshuabedford)](https://github.com/JoshuaBedford/lando-zsh) - A collection of alias functions to enable the use of the CLIs within [Lando](https://docs.lando.dev) without having to type lando to access them.
* [lando (mannuel)](https://github.com/mannuel/lando-alias-zsh) - Adds aliases for various [Lando](https://docs.lando.dev/basics/usage.html#default-commands/) commands.
* [laradock-workspace](https://github.com/rluders/laradock-workspace-zsh) - Provides an interface to [Laradock](http://laradock.io/)'s workspace.
* [laravel-au](https://github.com/Saleh7/laravel-au-zsh-plugin) - Adds aliases for Laravel 6.
* [laravel-sail](https://github.com/ariaieboy/laravel-sail) - Adds shortcuts for `sail` commands.
* [laravel](https://github.com/crazybooot/laravel-zsh-plugin) - Add shortcuts for Laravel 5, 5.1, 5.2 & 5.3.
* [laravelx](https://github.com/rsthegeek/oh-my-zsh-laravelx) - Adds some aliases for common [Laravel](https://laravel.com/docs) commands.
* [last-working-dir-tmux](https://github.com/Curly-Mo/last-working-dir-tmux) - Keeps track of the last used working directory globally and per tmux session and automatically jumps into it for new shells.
* [last-working-directory (mdumitru)](https://github.com/mdumitru/last-working-dir) - Broken out copy of the version in [oh-my-zsh](http://ohmyz.sh/). Keeps track of the last used working directory and automatically jumps into it for new shells.
* [lazyload](https://github.com/qoomon/zsh-lazyload) - Lazy load commands and speed up start up time of ZSH.
* [learn](https://github.com/MenkeTechnologies/zsh-learn) - Learning collection in MySQL/MariadB to save, query and quiz everything you learn.
* [lesaint-git](https://github.com/lesaint/lesaint-git) - Replacement `git` plugin for Oh-My-Zsh-compatible frameworks.
* [lesaint-mvn](https://github.com/lesaint/lesaint-mvn) - Maven plugins for oh-my-zsh.
* [liferay](https://github.com/david-gutierrez-mesa/liferay-zsh) - Adds scripts for [liferay](https://github.com/liferay/liferay-portal) development.
* [linkfile](https://github.com/JaumeRF/linkfile-zsh) - Add shortcuts to your favorite directories.
* [linus-rants](https://github.com/bhayward93/Linus-rants-ZSH) - Outputs a random Linus Torvalds rant when opening a terminal.
* [listbox](https://github.com/gko/listbox) - Listbox element for shell.
* [locate-sublime-projects-cli](https://github.com/david-treblig/locate-sublime-projects-cli) - Allows searching for [Sublime Text](https://www.sublimetext.com) projects and opens them in Sublime.
* [loremipsum](https://github.com/pfahlr/zsh_plugin_loremipsum) - Generate lorem ipsum text on the command line. Gets its data from [lipsum.com](https://www.lipsum.com).
* [ls](https://github.com/zpm-zsh/ls) - Colorizes the output of `ls`.
* [lumberjack](https://github.com/molovo/lumberjack) - Lumberjack is a logging interface for shell scripts.
* [lux](https://github.com/pndurette/zsh-lux) - ZSH plugin to toggle the light & dark modes of macOS and other items and applications via the `lux` command. Highly customizable: included items can be configured by defining variables. Highly extensible: items can be added by defining functions. Includes `macos_is_dark` helper function to determine if the macOS dark mode is active for use in theming.
* [mac-packaging](https://github.com/Temikus/mac-packaging) - A set of common functions used for enterprise Mac packaging with [Munki](https://www.munki.org/munki/).
* [macos](https://github.com/joow/macos) - A ZSH plugin for macOS.
* [mage2docker](https://github.com/lukaszolszewski/mage2docker) - Makes it easy to work with Docker and Magento 2. Speeds up and simplifies common commands like clean cache, setup upgrade, compile di and much more in Magento 2 on containers.
* [magento-2](https://github.com/dambrogia/oh-my-zsh-plugin-magento-2) - Adds `m2` function to run magento binary, adds tab completions.
* [manydots-magic](https://github.com/knu/zsh-manydots-magic) - A zle tweak for emulating `...'==`../..' etc.
* [markedit](https://github.com/zakariaGatter/MarkEdit) - Mark files and edit them with autocompletion for existing marks.
* [markgate](https://github.com/zakariaGatter/MarkGate) - Allows you to mark directories so you can jump directly to them.
* [maven-plugin](https://github.com/KyleChamberlin/zsh_maven_plugin) - A fork of the oh-my-zsh maven plugin.
* [mercurial](https://github.com/hcgraf/zsh-mercurial) - Extracted from oh-my-zsh so you can use it without oh-my-zsh.
* [mfunc](https://github.com/hlohm/mfunc) - Allows you to define persistent functions on-the-fly, without the need to add them to your config files. These functions are permanently available until you delete them.
* [mode-switch.CLI](https://github.com/Gyumeijie/mode-switch.CLI) - A ZSH plugin for switching command line between normal mode and `vi` mode.
* [monorepo-plugin](https://github.com/zilongqiu/monorepo-zsh-plugin) - ZSH plugin for monorepo management.
* [monthrename](https://github.com/NotTheDr01ds/zsh-plugin-monthrename) - Renames month names to numbers in filenames.
* [morpho](https://github.com/psprint/zsh-morpho) - Terminal screen savers written in pure ZSH, and also screen saver framework.
* [mouse-status](https://github.com/gryffyn/mouse-status) - Changes mouse color based on status code, uses libratbag.
* [msf](https://github.com/sathish09/zsh_plugins/tree/master/msf) - Metasploit handler plugin for starting handlers easily.
* [mvn-contexts](https://github.com/artemy/zsh-mvn-contexts) - Allows fast switching between maven configurations.
* [mylocation](https://github.com/fALKENdk/mylocation) - A plugin to show your current location based on your IP address.
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) - Adds color for mysql tables.
* [mysql](https://github.com/voronkovich/mysql.plugin.zsh) - Adds some functions for dealing with mysql.
* [n](https://github.com/gretzky/n.zsh) - Auto-switches node versions based on project environment using [n](https://github.com/tj/n).
* [navi](https://github.com/icatalina/zsh-navi-plugin/) - Plugin for [navi](https://github.com/denisidoro/navi).
* [navigation-tools](https://github.com/psprint/zsh-navigation-tools) - Adds `htop`-like `kill`, directory bookmarks browser, multi-word incremental history searcher and more.
* [new-file-from-template](https://github.com/zpm-zsh/new-file-from-template) -  Generates file from template.
* [nice-exit-code](https://github.com/bric3/nice-exit-code) - Maps exit status code to human readable string.
* [nix-shell](https://github.com/chisui/zsh-nix-shell) - Plugin that lets you use ZSH as the default shell in a `nix-shell` environment.
* [nnvm](https://github.com/torifat/nnvm) - auto-switches node versions based on `.nvmrc`. Requires [n](https://github.com/tj/n).
* [node-env-installer](https://github.com/shiro-saber/node-env-installer) - Uses `nvm` to install new versions and modules for the current project.
* [node-path](https://github.com/andyrichardson/zsh-node-path) - Automatically adds the "npm bin" of your current directory to your path.
* [node](https://github.com/srijanshetty/node.plugin.zsh) - Srijan Shetty's nodejs plugin for ZSH with caching of `nvm` completions and autoloading of `nvm` if present.
* [nodenv (c-uo)](https://github.com/C-uo/zsh-nodenv) - Looks for nodenv in your working directory and loads it when found.
* [nodenv (jsahlen)](https://github.com/jsahlen/nodenv.plugin.zsh) - Auto-load `nodenv` and its completions into the shell.
* [nodenv (mattberther)](https://github.com/unixorn/awesome-zsh-plugins/blob/master/mattberther/zsh-nodenv) - Installs, updates and loads `nodenv`. Inspired by zsh-rbenv.
* [nohup](https://github.com/micrenda/zsh-nohup) - Add `nohup` to the current command pressing `Ctrl-H`.
* [noreallyjustfuckingstopalready](https://github.com/eventi/noreallyjustfuckingstopalready) - macOS users know the pain of trying to figure out what command actually flushes the DNS cache on their version of macOS, and this plugin makes that annoyance go away.
* [notes (aperezdc)](https://github.com/aperezdc/zsh-notes) - Inspired by [terminal_velocity](https://www.seanh.cc/terminal_velocity/), it provides a fast interface to create and access a set of [Markdown](https://en.wikipedia.org/wiki/Markdown) text files inside a directory.
* [notes (chipsenkbeil)](https://github.com/chipsenkbeil/zsh-notes) - Provides a quick notes editing experience in ZSH.
* [notify (luismayta)](https://github.com/luismayta/zsh-notify) - Notifications for ZSH with auto installation of dependencies and r2d2 sounds.
* [notify (marzocchi)](https://github.com/marzocchi/zsh-notify) - A plugin for ZSH (on macOS and Linux) that posts desktop notifications when a command terminates with a non-zero exit status or when it took more than 30 seconds to complete, if the terminal application is in the background (or the command's terminal tab is inactive).
* [npm (igoradamenko)](https://github.com/igoradamenko/npm.plugin.zsh) - Add `npm` aliases & command completion. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npm (trystan2k)](https://github.com/trystan2k/zsh-npm-plugin) - Adds `npm` aliases. Based on the Oh-My-Zsh [npm](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/npm) plugin.
* [npms](https://github.com/torifat/npms) - Utility powered by `fzf` for using npm scripts interactively. Requires [fzf](https://github.com/junegunn/fzf) and [jq](https://stedolan.github.io/jq/).
* [nvm-auto-use](https://github.com/tomsquest/nvm-auto-use.zsh) - Calls `nvm use` automatically whenever you enter a directory that contains an `.nvmrc` file with a string telling `nvm` which node to use.
* [nvm-auto](https://github.com/dijitalmunky/nvm-auto) - Aims to alleviate needing to type `nvm use` as much as possible, especially if you often switch between versions of node.js and use `.nvmrc` files in your project to manage what version of node your project needs.
* [nvm-lazy](https://github.com/davidparsson/zsh-nvm-lazy) - Plugin for lazy loading of oh-my-zsh's **nvm** plugin. It supports lazy-loading `nvm` for more than one binary/entrypoint, with the defaults being `nvm`, `node` and `npm`.
* [nvm](https://github.com/lukechilds/zsh-nvm) - ZSH plugin for installing, updating and loading `nvm`.
* [oath](https://github.com/alexdesousa/oath) - Manages 2FA authentication 6 digit tokens. It was highly inspired by this article about [using oathtool for 2 step verification](https://www.cyberciti.biz/faq/use-oathtool-linux-command-line-for-2-step-verification-2fa/).
* [oclif completion generator](https://github.com/MunifTanjim/oclif-plugin-completion) - Generates shell completions for commands lacking them.
* [oh-my-matrix](https://github.com/amstrad/oh-my-matrix) - Turn your terminal into the matrix.
* [open-create-projects](https://github.com/marcossegovia/open-create-projects) - Open/Create projects in Jetbrains.
* [open-pr](https://github.com/caarlos0/zsh-open-pr) - A ZSH plugin to open pull requests from command line.
* [openshift-origin](https://github.com/ryanswart/openshift-origin-zsh-plugin) - Add a few shortcuts to common openshift origin (oc) actions.
* [opera-git-plugin](https://github.com/aswitalski/oh-my-zsh-opera-git-plugin) - `git` aliases.
* [operator](https://github.com/nivv/operator-theme) - Clean and simple theme, works best with Menlo for Powerline.
* [opp](https://github.com/hchbaw/opp.zsh) - Vim's text-objects-ish for ZSH.
* [opt-path](https://github.com/jreese/zsh-opt-path) - Automatically add `~/opt` subpaths to your `$PATH`.
* [osx-autoproxy](https://github.com/SukkaW/zsh-osx-autoproxy) - Configures proxy environment variables based on macOS's system preferences.
* [osx-dev](https://github.com/marshallmick007/osx-dev-zsh-plugin) - This plugin adds some commands for maintaining various server programs on a macOS install.
* [osx](https://github.com/mwilliammyers/plugin-osx) - Add some common macOS related aliases and functions.
* [p10k-promptconfig](https://github.com/doctormemes/p10k-promptconfig) - adds the ability to easily switch between Powerlevel10k prompt theme config files by defining the `P10K_PROMPT` variable in your `.zshrc` file.
* [paci](https://github.com/iloginow/zsh-paci) - Plugin for archlinux package managers.
* [pantheon-terminal-notify](https://github.com/deyvisonrocha/pantheon-terminal-notify-zsh-plugin) - Background notifications for long running commands. Supports Elementary OS Freya.
* [passwordless-history](https://github.com/jgogstad/passwordless-history) - Keeps passwords from entering your command line history.
* [path-ethic](https://github.com/sha1n/path-ethic) - Helps manage your `$PATH` quickly and easily. Doesn't touch your existing `.zshrc`, `.zprofile`, but adds on top of your existing environment instead.
* [pctl](https://github.com/ytet5uy4/pctl) - Toggle the environment variables for proxying.
* [peco-history](https://github.com/jimeh/zsh-peco-history) - Search shell history with Peco when pressing ctrl+R.
* [pentest](https://github.com/jhwohlgemuth/oh-my-zsh-pentest-plugin) - Aliases and functions for the lazy penetration tester.
* [per-directory-history](https://github.com/jimhester/per-directory-history) - Per directory history for ZSH, as well as global history, and the ability to toggle between them with `^G`.
* [percol](https://github.com/robturtle/percol.plugin.zsh) - Interactively and incrementally search history/resume background jobs using [percol](https://github.com/mooz/percol).
* [perlbrew](https://github.com/tfiala/zsh-perlbrew/) - Installs [perlbrew](https://perlbrew.pl/) if not already installed and initializes it for your shell.
* [pew](https://github.com/shosca/zsh-pew) - Sets up and manages Python virtualenvs using [pew](https://github.com/berdario/pew), automatically switches virtualenvs as you move directories.
* [pg](https://github.com/caarlos0-graveyard/zsh-pg) - Adds utility functions to work with [PostgreSQL](https://www.postgresql.org/).
* [ph-marks](https://github.com/lainiwa/ph-marks) - Bookmark pornhub videos from your terminal.
* [php-version-rcfile-switcher](https://github.com/xellos866/php-version_rcfile-switcher) - Automatically switch between php versions using [php-version](https://github.com/wilmoore/php-version) if an rc-file is present in a directory.
* [phpcs](https://github.com/voronkovich/phpcs.plugin.zsh) - Plugin for [PHP code sniffer](https://github.com/squizlabs/PHP_CodeSniffer).
* [phpenv](https://github.com/sptndc/phpenv.plugin.zsh) - Auto-load [phpenv](https://github.com/sptndc/phpenv) and its completions.
* [phpunit](https://github.com/voronkovich/phpunit.plugin.zsh) - Plugin for [PHPUnit](https://phpunit.de/).
* [pip-app](https://github.com/sharat87/pip-app) - Makes it easy to install python applications into distinct Python virtualenvs so they don't conflict with any other python requirements on your system.
* [pip-env](https://github.com/iboyperson/zsh-pipenv) - Automatic [pipenv](https://pipenv.readthedocs.io/en/latest/) activation upon entry into a pipenv project.
* [pipx](https://github.com/thuandt/zsh-pipx) - Autocompletions for [pipx](https://github.com/pypa/pipx).
* [pkenv](https://github.com/ptavares/zsh-pkenv) - Installs and loads [pkenv](https://github.com/iamhsa/pkenv.git)
* [plugin-ibtool](https://github.com/rgalite/zsh-plugin-ibtool) - Adds ibtool shortcuts to generate localized XIB files.
* [plugin-rails](https://github.com/paraqles/zsh-plugin-rails) - ZSH plugin for Rails.
* [plugin-vscode](https://github.com/wuotr/zsh-plugin-vscode) - Plugin for Visual Studio Code, a text editor for macOS, Windows, and Linux.
* [plugin](https://github.com/darrenbutcher/plugin) - Creates custom oh-my-zsh plugins from a boilerplate template. Very oh-my-zsh centric, the generated plugins will need editing to work with other frameworks.
* [pnpm](https://github.com/ntnyq/omz-plugin-pnpm) - Adds useful aliases for common Pnpm commands.
* [poetry (darvid)](https://github.com/darvid/zsh-poetry) - Automatically activates and deactivates [Poetry](https://poetry.eustace.io/)-created python virtualenvs.
* [poetry (sudosabin)](https://github.com/sudosubin/zsh-poetry) - Enables poetry `$PATH` and autocompletions.
* [posh-git-bash](https://github.com/lyze/posh-git-sh) - Adds `git` status in your prompt.
* [ppsmon](https://github.com/mzpqnxow/ppsmon) - Reads `/sys/class/net/$interface/` to keep track of packet transmission rates. It stores the current rate to a file in the RAM backed filesystem where it can be easily accessed for display in a shell-prompt. Linux-only due to use of `/sys`.
* [pr-cwd](https://github.com/zpm-zsh/pr-cwd) - Creates a global variable with current working directory. Plugin has integration with [jocelynmallon/zshmarks](https://github.com/jocelynmallon/zshmarks).
* [pr-eol](https://github.com/zpm-zsh/pr-eol) - Displays an EOL symbol which can be embedded in the prompt.
* [pr-exec-time](https://github.com/zpm-zsh/pr-exec-time) - Adds a variable you can use to display the execution time of the last command run.
* [pr-git](https://github.com/zpm-zsh/pr-git) - Creates a global variable with `git` status information that can be displayed in prompts.
* [pr-is-root](https://github.com/zpm-zsh/pr-is-root) - Sets an environment variable you can use in a custom prompt when running as root.
* [pr-jobs](https://github.com/zpm-zsh/pr-jobs) - Creates an environment variable which can be used to display background job information in a custom prompt.
* [pr-node](https://github.com/zpm-zsh/pr-node) - Sets an environment variable which can be used to display nodeJS information in a custom prompt.
* [pr-return](https://github.com/zpm-zsh/pr-return) - Plugin for ZSH who displays the exit status of the last command run.
* [presenter-mode](https://github.com/idadzie/zsh-presenter-mode) - Expands aliases during presentations. It also increases the terminal window's contrast to enhance visibility.
* [pretty-time (sindresorhus)](https://github.com/sindresorhus/pretty-time-zsh) - Convert seconds to a human readable string: 165392 → 1d 21h 56m 32s.
* [pretty-time (zpm-zsh)](https://github.com/zpm-zsh/pretty-time) - Converts raw seconds into human-readable strings.
* [print-alias](https://github.com/brymck/print-alias) - Prints commands with aliases expanded whenever you use an alias at the command line.
* [printc](https://github.com/philFernandez/printc) - Allows you to print in any color in the RGB space via a simple `printc` call.
* [profile-secrets](https://github.com/gmatheu/shell-plugins) - Securely keep sensitive variables (api tokens, passwords, etc) as part of your terminal init files. Uses gpg to encrypt/decrypt the file with your secrets.
* [project (gko)](https://github.com/gko/project) - Create node/python/ruby project both locally and on github(private or public repository).
* [project (voronkovich)](https://github.com/voronkovich/project.plugin.zsh) - Plugin for managing projects.
* [prompt-generator](https://github.com/the10thWiz/zsh-prompt-generator) - Generates custom themes. Some generated themes require powerline-compatible fonts.
* [proxy-plugin](https://github.com/escalate/oh-my-zsh-proxy-plugin) - Quickly enable and disable proxy shell environment settings.
* [proxy](https://github.com/SukkaW/zsh-proxy) - Configure proxy settings for some package managers and software.
* [pyenv-lazy-load](https://github.com/erikced/zsh-pyenv-lazy-load) - Plugin for lazy-loading `pyenv` in ZSH.
* [pyenv-lazy](https://github.com/davidparsson/zsh-pyenv-lazy) - Lazy load pyenv. The initial `eval "$(pyenv init -)"` is executed the first time `pyenv` is called.
* [pyenv](https://github.com/mattberther/zsh-pyenv) - Inspired by zsh-rbenv. Installs, updates or loads `pyenv`, and adds extra functionality.
* [q (cal2195)](https://github.com/cal2195/q) - Add `vim`-like macro registers to your ZSH shell.
* [q (tomsquest)](https://github.com/tomsquest/q.plugin.zsh) - Tail/remove the temp file for [Q](https://github.com/y0ssar1an/q), the Dirty Debugging Tool.
* [qiime2](https://github.com/misialq/zsh-qiime2) - Adds functions and aliases to make working with [Quiime 2](https://qiime2.org/) easier.
* [quoter](https://github.com/pxgamer/quoter-zsh) - Display a random quote when opening a new terminal session.
* [quotify](https://github.com/damofthemoon/zsh-quotify) - Displays inspiring coding quotes from our pairs when starting up.
* [randeme](https://github.com/ex-surreal/randeme) - Chooses a random theme for each session. If you not like the chosen theme you can run `randeme_rm` to never show that theme again.
* [random-quotes](https://github.com/vkolagotla/zsh-random-quotes) - Displays random quotes or facts.
* [razer-status-code](https://github.com/michaelmcallister/razer-status-code) - Change the colour of your [Razer Mouse](https://openrazer.github.io/) based on the status of the last executed command. Requires [OpenRazer](https://openrazer.github.io) linux drivers.
* [rbenv (ELLIOTTCABLE)](https://github.com/ELLIOTTCABLE/rbenv.plugin.zsh) - A faster fork of the rbenv plugin from oh-my-zsh.
* [rbenv (Meroje)](https://github.com/Meroje/zsh-rbenv) - Inspired by [https://github.com/lukechilds/zsh-nvm/](https://github.com/lukechilds/zsh-nvm/), makes it easier to work with ruby rbenvs.
* [rbenv (jsahlen)](https://github.com/jsahlen/rbenv.plugin.zsh) - Variant based on the original oh-my-zsh rbenv plugin.
* [rc-files](https://github.com/0b10/rc-files) - Adds shortcut functions for editing various rc files.
* [recall](https://github.com/mango-tree/zsh-recall) - Makes using command history easier.
* [redis](https://github.com/zservices/redis) - Will run `redis-server` pointing it to the `redis.conf` configuration file. This can be used with the [zdharma/zredis](https://github.com/zdharma/zredis) plugin to share variables between shells.
* [reentry-hook](https://github.com/RobSis/zsh-reentry-hook) - Plugin that re-enters working directory if it has been removed and re-created.
* [reload](https://github.com/aubreypwd/zsh-plugin-reload) - Adds function to quickly reload your `.zshrc`.
* [reminder](https://github.com/AlexisBRENON/oh-my-zsh-reminder) - A plugin which displays reminders above every prompt.
* [replace-multiple-dots](https://github.com/momo-lab/zsh-replace-multiple-dots) - Converts `...` to `../..`
* [revolver](https://github.com/molovo/revolver) - A progress spinner for ZSH scripts.
* [riddle-me](https://github.com/vkolagotla/zsh-riddle-me) - Displays random riddles.
* [ripz](https://github.com/jedahan/ripz) - Reminds you of your aliases, so you use them more. Depends on [ripgrep](https://github.com/BurntSushi/ripgrep).
* [robo](https://github.com/shengyou/robo-zsh-plugin) - A ZSH plugin for [Robo](https://robo.li/).
* [rockz](https://github.com/aperezdc/rockz) - Lua + LuaRocks virtual environment manager based upon VirtualZ.
* [rust](https://github.com/cowboyd/zsh-rust) - Configure your rust toolchain, installing [rustup](https://rustup.rs) if it is not currently installed already.
* [rvm](https://github.com/johnhamelink/rvm-zsh) - Initiates RVM and adds rubygem binaries (like compass) accessible in the user's `$PATH`.
* [safe-kubectl](https://github.com/benjefferies/safe-kubectl) - Add some safety when running `kubectl` by warning what context you're in after a definable number of seconds since the last `kubectl` command.
* [safe-paste](https://github.com/oz/safe-paste) - A safe-paste plugin. See Conrad Irwin's [bracketed-paste](https://cirw.in/blog/bracketed-paste) blog post.
* [safe-rm](https://github.com/mattmc3/zsh-safe-rm) - Add safe-rm functionality so that `rm` will put files in your OS's trash instead of permanently deleting them.
* [saml2aws-auto](https://github.com/devndive/zsh-saml2aws-auto) - When using multiple AWS profiles, e.g. different accounts for your stages (development, pre-prod, prod), can be used to determine which profile is currently exported and if the token is still valid.
* [saml2aws](https://github.com/onyxraven/zsh-saml2aws) - Add support for [saml2aws](https://github.com/Versent/saml2aws).
* [sandboxd](https://github.com/benvan/sandboxd) - Speed up your `.zshrc` & shell startup with lazy-loading by only running setup commands (e.g. `eval "$(rbenv init -)"`, etc) when you need them.
* [saneopt](https://github.com/willghatch/zsh-saneopt) - Sane defaults for ZSH options, in the spirit of vim-sensible.
* [schroot](https://github.com/fshp/schroot.plugin.zsh) - Show current `chroot` name in your prompt.
* [search-directory-history](https://github.com/cmaahs/search-directory-history) - Allows complex search of per-directory history created using the [per-directory-history](https://github.com/jimhester/per-directory-history) plugin.
* [sed-sub](https://github.com/MenkeTechnologies/zsh-sed-sub) - Adds keybindings to do global search and replace on current command line.
* [select](https://github.com/psprint/zsh-select) - Multi-term searched selection list with approximate matching and uniq mode.
* [send](https://github.com/robertzk/send.zsh) - Single command to `git add`, `git commit`, and `git push` for much faster `git` workflow.
* [sensei-git](https://github.com/aswitalski/oh-my-zsh-sensei-git-plugin) - Adds many `git` aliases and helper shell functions.
* [session-sauce](https://github.com/ChrisPenner/session-sauce) - An fzf interface for tmux session creation and management for all your projects.
* [setenv](https://github.com/kalpakrg/setenv) - Runs a script when you change directories.
* [shelf](https://github.com/ecmma/shelf) -Utility which can be used to bookmark and access directly any file using mnemonics.
* [show-path](https://github.com/redxtech/zsh-show-path) - Provides a function shows the `$PATH` line by line.
* [simpleserver](https://github.com/sathish09/zsh_plugins/tree/master/simpleserver) - Plugin to easily start python `SimpleHTTPServer` and `SimpleHTTPSServer`.
* [skim](https://github.com/hackerchai/skim-zsh) - Adds support for [skim](https://github.com/lotabout/skim)
* [slugify](https://github.com/lashoun/slugify) - Converts filenames and directories to a web friendly format.
* [smart-cd](https://github.com/dbkaplun/smart-cd) - Runs `ls` and `git status` after chpwd.
* [smartinput](https://github.com/momo-lab/zsh-smartinput) - When you type brackets or quotes, the corresponding end brackets/quotes are automatically added.
* [smile](https://github.com/fundor333/smile) - Adds function to display random smileys.
* [snippets](https://github.com/willghatch/zsh-snippets) - Command line snippet expansion.
* [solarized-man](https://github.com/zlsun/solarized-man) - A modified version of oh-my-zsh's plugin colored-man-pages, optimized for the [solarized dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) theme in the terminal.
* [ssh-connect](https://github.com/gko/ssh-connect) - A simple `ssh` manager.
* [ssh-plugin](https://github.com/paraqles/zsh-plugin-ssh) - Plugin for `ssh`.
* [sshukh](https://github.com/anatolykopyl/sshukh-zsh-plugin) - Will update your `known_hosts` file when you `ssh` into a server.
* [startup-timer](https://github.com/paulmelnikow/zsh-startup-timer) - Print the time it takes for the shell to start up.
* [stashy](https://github.com/MisterRios/stashy) - Plugin that simplifies using `git stash`.
* [statify](https://github.com/vladmrnv/statify) - Plugin that does basic statistical analysis.
* [sublime](https://github.com/valentinocossar/sublime) - Same as the official Sublime plugin for Oh My Zsh, but this opens files in the current Sublime window, if there is one already open.
* [sudo](https://github.com/hcgraf/zsh-sudo) - The `sudo` plugin from oh-my-zsh, extracted to a standalone. Toggles `sudo` before the current/previous command by pressing *ESC-ESC* in emacs-mode or vi-command mode.
* [suffix-alias](https://github.com/srijanshetty/zsh-suffix-alias) - Directly open files in the shell using ZSH's suffix aliases.
* [svn-n-zsh](https://github.com/khrt/svn-n-zsh-plugin) - Rewrite of the stock oh-my-zsh svn plugin.
* [switch-git](https://github.com/robin-mbg/switch-git) - Easy switching between `git` repositories. Just type `sgr <some part of you repo's name>`, press enter and you're there.
* [symfony (voronkovich)](https://github.com/voronkovich/symfony.plugin.zsh) - ZSH plugin for Symfony 2 and 3.
* [syntax-highlighting-filetypes](https://github.com/trapd00r/zsh-syntax-highlighting-filetypes) - ZSH syntax highlighting with dircolors in realtime.
* [syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - Add syntax highlighting to your ZSH. Make sure you load this _before_ zsh-users/zsh-history-substring-search or they will both break.
* [sys-diver](https://github.com/ToruIwashita/sys-diver-zsh) - A ZSH plugin for directory change or editor startup with only key operations using widgets without typing commands.
* [sysadmin-util](https://github.com/skx/sysadmin-util) - Steve Kemp's collection of tool scripts for sysadmins.
* [system-clipboard](https://github.com/kutsan/zsh-system-clipboard) - Adds key bindings support for ZLE (Zsh Line Editor) clipboard operations for vi emulation keymaps. It works under Linux, macOS and Android (via Termux).
* [systemd](https://github.com/le0me55i/zsh-systemd) - Adds many aliases for `systemd`.
* [t32](https://github.com/chrissicool/zsh-t32) - Plugin for the Lauterbach Trace32 toolset. It automatically registers fonts and sets all necessary environment variables to run the t32 toolset.
* [tab-title](https://github.com/trystan2k/zsh-tab-title) - Set the terminal tab title according to current directory or running process. Forked from [termsupport.zsh](https://github.com/ohmyzsh/ohmyzsh/blob/master/lib/termsupport.zsh)
* [tailf](https://github.com/rummik/zsh-tailf) - Adds `tailf` function with prefixed newlines instead of trailing newlines.
* [taskbook](https://github.com/mastern2k3/taskbook-zsh-plugin) - Auto-completes task numbers for taskbook.
* [terminal-app](https://github.com/the8/terminal-app.zsh) - A plugin for integrating with the new El Capitan Terminal.app features.
* [terminal-title](https://github.com/AnimiVulpis/zsh-terminal-title) - Adds a `set-term-title` function you can use to title terminal windows.
* [terminal-workload-report](https://github.com/LockonS/terminal-workload-report) - A plugin that calculates and displays how many commands have been run via terminal.
* [termux](https://github.com/zpm-zsh/termux) - Adds compatibility for [Termux](https://termux.com/)
* [terraform (hanjunlee)](https://github.com/hanjunlee/terraform-oh-my-zsh-plugin) - Add terraform workspace to prompt.
* [terraform (jsporna)](https://github.com/jsporna/terraform-zsh-plugin) - Extends the original oh-my-zsh plugin with aliases and tab completions. Adds workspace (when not default) to prompt.
* [terraform (macunha1)](https://github.com/macunha1/zsh-terraform) - Add convenience aliases for [terraform](https://terraform.io/), tab completions and helper function to add your terraform workspace in the prompt.
* [terraform (pbar1)](https://github.com/pbar1/zsh-terraform) - Terraform convenience functions and aliases for ZSH.
* [terraform (thuandt)](https://github.com/thuandt/zsh-terraform) - Adds convenience aliases for `terraform`, along with completions for `terraform` and `terragrunt`.
* [terragrunt](https://github.com/hanjunlee/terragrunt-oh-my-zsh-plugin) - Plugin for [Terragrunt](https://github.com/gruntwork-io/terragrunt), a thin wrapper for [Terraform](https://terraform.io/) that provides extra tools.
* [tfenv](https://github.com/CDA0/zsh-tfenv) - Installs, updates, and loads tfenv inspired by [zsh-pyenv](https://github.com/mattberther/zsh-pyenv)
* [tfswitch](https://github.com/ptavares/zsh-tfswitch) - installs and loads [tfswitch](https://github.com/warrensbox/terraform-switcher).
* [thefuck](https://github.com/laggardkernel/thefuck) - Loads [thefuck](https://github.com/nvbn/thefuck) (a tool which corrects your previous command) with cache support, which reduces the loading time dramatically.
* [theia-dev-tools](https://github.com/taPublic/zsh-theia-dev-tools) - Convenience functions for working with [theia-ide](https://github.com/theia-ide/theia).
* [tig](https://github.com/zdharma/zsh-tig-plugin) - Adds a few advanced bindings and also provides a ZSH-rewritten function and/or script `tig-pick`.
* [timewarrior](https://github.com/svenXY/timewarrior) - Adds support for [timewarrior](https://timewarrior.net/), a time-tracking application.
* [tipz](https://github.com/molovo/tipz) - Displays your alias if you have an alias for the command you just ran, similarly to [alias-tips](https://github.com/djui/alias-tips).
* [title](https://github.com/zpm-zsh/title) - Allows you to set a terminal window title.
* [titles](https://github.com/jreese/zsh-titles) - Automatic window and tab titles for [tmux](https://tmux.github.io) and xterm-compatible terminals.
* [tm](https://github.com/kjhaber/tm.zsh) - Simplifies creating new [tmux](https://tmux.github.io) sessions, attaching to existing sessions, switching between sessions, and listing active sessions.
* [tmux-auto-title](https://github.com/mbenford/zsh-tmux-auto-title) - Automatically sets the title of windows/panes as the current foreground command.
* [tmux-multisession](https://github.com/nichus/zsh-tmux-multisession) - Plugin for [tmux](https://tmux.github.io) to support multiple sessions on a single server process.
* [tmux-rename](https://github.com/sei40kr/zsh-tmux-rename) - Rename [tmux](https://tmux.github.io) windows automatically.
* [tmux-simple](https://github.com/TBSliver/zsh-plugin-tmux-simple) - Simple plugin for using [tmux](https://tmux.github.io) with ZSH.
* [tmux-vim-integration](https://github.com/jsahlen/tmux-vim-integration.plugin.zsh) - Open files in a running `vim` (or NeoVim) session, from an adjacent [tmux](https://tmux.github.io) pane.
* [tmux-zsh-vim-titles](https://github.com/MikeDacre/tmux-zsh-vim-titles) - Create unified terminal titles for `tmux`, ZSH, and Vim/NVIM, modular.
* [tmux](https://github.com/zpm-zsh/tmux) - Plugin for [tmux](https://tmux.github.io).
* [tmuxrepl](https://github.com/csurfer/tmuxrepl) - Simple ZSH plugin to have a R-EP-L [tmux](https://tmux.github.io) session.
* [toggl](https://github.com/natterstefan/toggl-zsh-plugin) - Adds a `toggl-week` command to display the total working hours tracked on [toggl.com](https://toggl.com)
* [toggle-command-prefix](https://github.com/xPMo/zsh-toggle-command-prefix) - Add a widget to toggle a prefix to a command. Binds Alt+s to prefix a command with `sudo` by default.
* [traista](https://github.com/odgon/traista) - Includes `git` status decorations and color-coded exit status of the last command run. Better with dark terminal themes.
* [travis](https://github.com/denolfe/zsh-travis) - Opens the Travis CI page for the current repo if one exists.
* [tre](https://github.com/redxtech/zsh-tre) - Makes using [tre](https://github.com/dduan/tre#editor-aliasing) easier.
* [tsm](https://github.com/RobertAudi/tsm) - Adds a [tmux](https://tmux.github.io) Session Manager.
* [tumult](https://github.com/unixorn/tumult.plugin.zsh) - Adds tools for macOS.
* [ubuntualiases](https://github.com/GuilleDF/zsh-ubuntualiases) - Ubuntu 16 aliases.
* [ugit](https://github.com/Bhupesh-V/ugit) - Lets you undo your last `git` operation.
* [undollar](https://github.com/zpm-zsh/undollar) - Strips the dollar sign from the beginning of the terminal prompt.
* [up (cjayross)](https://github.com/cjayross/up) - A simple way to navigate up through directories.
* [up (peterhurford)](https://github.com/peterhurford/up.zsh) - Adds an up command to `cd` multiple levels up.
* [update-zsh](https://github.com/AndrewHaluza/zsh-update-plugin) - Updates custom oh-my-zsh plugins. Only works with the oh-my-zsh framework.
* [url-highlighter](https://github.com/ascii-soup/zsh-url-highlighter) - A plugin for the ZSH syntax highlighter that turns URLs green if they respond with a "good" status, and red otherwise. Useful for checking URL typos.
* [uvenv](https://github.com/vincentto13/uvenv.plugin.zsh) - Extends the functionality of the original oh-my-zsh venv module.
* [vagrant-box-wrapper](https://github.com/evanthegrayt/vagrant-box-wrapper) - A wrapper plugin for [vagrant](https://www.vagrantup.com/) that allows for calling `vagrant` commands from outside of the box directory. The plugin also ships with a few extra commands that help to manage more than one box, along with custom tab-completion.
* [vanilli.sh](https://github.com/yous/vanilli.sh) - A lightweight start point of shell configuration.
* [vapor](https://github.com/notf0und/zsh-vapor) - Laravel vapor plugin for zsh to help you to run vapor from anywhere in the project tree, with auto-completion!
* [vcshr](https://github.com/aubreypwd/zsh-plugin-vcshr) - Help vcsh users require Github repositories using `vcsh` for auto-installation in `~/.zshrc`, etc.
* [velocity](https://github.com/rahulsalvi/velocity-python) - Powerline-based theme elements for ZSH and [tmux](https://tmux.github.io).
* [venv-lite](https://github.com/gimbo/venv-lite.zsh) - A super-lightweight sort-of-clone of [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/); it pretty much expects you to be using [pyenv](https://github.com/pyenv/pyenv) (though you don't *have* to), and because it's based on the [`venv` module](https://docs.python.org/3/library/venv.html), (creation) only works for python >= 3.3.
* [venv-wrapper](https://github.com/glostis/venv-wrapper) - Provides ZSH functions to ease the management of your virtual environments using `venv`.
* [vi-increment](https://github.com/zsh-vi-more/vi-increment) - Add `vim`-like increment/decrement operations.
* [vi-mode (jeffreytse)](https://github.com/jeffreytse/zsh-vi-mode) - 💻 A better and friendly vi(vim) mode plugin for ZSH.
* [vi-mode (nyquase)](https://github.com/Nyquase/vi-mode) Add extra `vi`-like functionality.
* [vi-mode (sinetoami)](https://github.com/sinetoami/vi-mode) - Add more `vi`-like functionality to ZSH.
* [vi-motions](https://github.com/zsh-vi-more/vi-motions) - Add new motions and text objects including quoted/bracketed text and commands.
* [vi-quote](https://github.com/zsh-vi-more/vi-quote) - Add an operation which quotes or unquotes a motion.
* [viexchange](https://github.com/okapia/zsh-viexchange) - A `vi` mode plugin for easily swapping text between two places in the buffer, like vim-exchange.
* [vim-mode](https://github.com/softmoth/zsh-vim-mode) - Friendly `vi`-mode bindings, adding basic Emacs keys, incremental search, mode indicators and more.
* [vim-plugin](https://github.com/nviennot/zsh-vim-plugin) - Allows you to do `vim filename:123` to open a file with the cursor at a specific line.
* [vimman](https://github.com/yonchu/vimman) - View `vim` plugin manuals (help) like `man` in ZSH.
* [vimto](https://github.com/laurenkt/zsh-vimto) - Improved ZSH `vi` mode (bindkey -v) plugin.
* [virtualenv-mod](https://github.com/mattcl/virtualenv-mod) - A modified virtualenv ZSH plugin for oh-my-zsh.
* [virtualenv-prompt](https://github.com/tonyseek/oh-my-zsh-virtualenv-prompt) - A fork of the virtualenv plugin from upstream. Adds support for customizing the virtualenv prompt in oh-my-zsh themes.
* [virtualz](https://github.com/aperezdc/virtualz) - Python [virtualenv](https://virtualenv.pypa.io/en/latest/) manager inspired by Adam Brenecki's [Virtualfish](https://github.com/adambrenecki/virtualfish) for the [Fish shell](http://fishshell.com/), replaces virtualenvwrapper.
* [virtuozzo-plugin](https://github.com/TamCore/virtuozzo-zsh-plugin) - An oh-my-zsh plugin for the [virtuozzo](https://docs.virtuozzo.com/master/index.html) bare-metal virtualization system.
* [visit](https://github.com/justinpchang/visit) - Custom plugin for faster navigation.
* [volta (cowboyd)](https://github.com/cowboyd/zsh-volta) - Seamlessly install and configure the [Volta](https://volta.sh) NodeJS toolchain manager.
* [volta](https://github.com/ri7nz/zsh-volta) - Installs and loads [ Volta: JS Toolchains as Code](https://github.com/volta-cli/volta).
* [vox](https://github.com/andrewbonnington/vox.plugin.zsh) - An oh-my-zsh plugin to control [VOX](https://vox.rocks/), a lightweight full-featured audio player for macOS that can play a variety of formats including FLAC and Ogg Vorbis.
* [vsc](https://github.com/davidtong/vsc.plugin.zsh) - Plugin for Visual Studio Code on macOS.
* [vscode (kasperhesthaven)](https://github.com/kasperhesthaven/vscode) - Simple plugin to open VS code a little easily across systems.
* [vscode (qianxinfeng)](https://github.com/qianxinfeng/zsh-vscode) - Plugin for [Visual Studio Code](https://code.visualstudio.com/).
* [vterm](https://github.com/randomphrase/vterm-zsh-plugin) - Lets you run emacs commands directly from [vterm](https://github.com/vterm/vterm) shell sessions.
* [wakatime (sobolevn)](https://github.com/sobolevn/wakatime-zsh-plugin) - Track how much [time](https://wakatime.com/) you have spent in your terminal. Has per project stats.
* [wakatime (wbingli)](https://github.com/wbingli/zsh-wakatime) - Automatic time tracking for commands in ZSH using [wakatime](https://wakatime.com/).
* [warhol](https://github.com/unixorn/warhol.plugin.zsh) - Configures colorization with [grc](https://github.com/garabik/grc).
* [watch](https://github.com/enrico9034/zsh-watch-plugin) - Easily prefix your current or previous commands with watch by pressing `CTRL + W`.
* [watson.zsh](https://github.com/bcho/Watson.zsh) - A plugin for the [watson](https://github.com/TailorDev/Watson) time management system.
* [wd](https://github.com/mfaerevaag/wd) - Warp directory lets you jump to custom directories in ZSH, without using `cd`. Why? Because `cd` seems inefficient when the folder is frequently visited or has a long path.
* [web-search](https://github.com/sinetoami/web-search) - Add commands to run bing, google, yahoo, & duckduckgo searches directly from the CLI.
* [whobrokemycode](https://github.com/cameronbroe/whobrokemycode) - Highlight where a particular line was last changed in a file using `git blame`.
* [windows-title](https://github.com/mdarocha/zsh-windows-title/issues) - Dynamically updates terminal window title with current directory and the last command run.
* [workon](https://github.com/bryanculver/workon.plugin.zsh) - Simple utility for jumping between projects.
* [worktree](https://github.com/jspears/worktree) - Adds functions that wrap `git worktree`.
* [xxh-plugin-zsh-zshrc](https://github.com/roman-geraskin/xxh-plugin-zsh-zshrc) - plugin for [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh) that copies your `~/.zshrc` to a remote host and sources it with [xxh-shell-zsh](https://github.com/xxh/xxh-shell-zsh).
* [yadm](https://github.com/juanrgon/yadm-zsh) - Displays a warning if there are local yadm configuration changes.
* [yapipenv](https://github.com/AnonGuy/yapipenv.zsh) - Automatically activate a directory's pip environment if `pipenv` detects the presence of one.
* [yeoman](https://github.com/edouard-lopez/yeoman-zsh-plugin) - Edouard Lopez's Yeoman plugin for oh-my-zsh, compatible with yeoman version ≥1.0 (includes options and command auto-completion).
* [you-should-use](https://github.com/MichaelAquilina/zsh-you-should-use) - ZSH plugin that reminds you to use those aliases you defined.
* [youtube-dl-aliases](https://github.com/katrinleinweber/oh-my-zsh-youtube-dl-aliases) - Adds `yt` aliases to download videos from YouTube.
* [youtube-dl](https://github.com/joow/youtube-dl) - Simple plugin for [youtube-dl](https://youtube-dl.org/).
* [yup](https://github.com/redxtech/zsh-yup) - Adds helper function to upgrade all the dependencies in a yarn/npm project.
* [z-a-bin-gem-node](https://github.com/zinit-zsh/z-a-bin-gem-node) - [Zinit](https://github.com/zdharma/zinit) extension that exposes binaries without altering `$PATH`, installs Ruby gems and Node modules and easily exposes their binaries, and updates the gems and modules when the associated plugin or snippet is updated.
* [z-a-man](https://github.com/zinit-zsh/z-a-man) - [Zinit](https://github.com/zdharma/zinit) extension that generates man pages for all plugins and snippets.
* [z-a-meta-plugins](https://github.com/zinit-zsh/z-a-meta-plugins) - Install groups of plugins with a single label ([Zinit](https://github.com/zdharma/zinit) only).
* [z-a-patch-dl](https://github.com/zinit-zsh/z-a-patch-dl) - [Zinit](https://github.com/zdharma/zinit) extension that downloads files and applies patches through the provided `dl''` and `patch''` ices.
* [z-a-rust](https://github.com/zinit-zsh/z-a-rust) - [Zinit](https://github.com/zdharma/zinit) extension that that installs rust and cargo packages inside plugin directories.
* [z-a-submods](https://github.com/zinit-zsh/z-a-submods) - [Zinit](https://github.com/zdharma/zinit) extenstion allows installing and managing additional submodules within a plugin or snippet.
* [z-a-test](https://github.com/zinit-zsh/z-a-test) - [Zinit](https://github.com/zdharma/zinit) extension that runs tests (via `make test`, for example) – if it finds any of them – after installing and updating a plugin or snippet.
* [z-a-unscope](https://github.com/zinit-zsh/z-a-unscope) - Allows installing plugins for [Zinit](https://github.com/zdharma/zinit) without specifying the user name by querying the Github API.
* [z.lua](https://github.com/skywind3000/z.lua) - A command line tool which helps you navigate faster by learning your habits. An alternative to [z.sh](https://github.com/rupa/z) with Windows and posix shells support and various improvements. 10x faster than fasd and autojump, 3x faster than [z.sh](https://github.com/rupa/z).
* [zabb](https://github.com/Mellbourn/zabb) - `zabb` is a command that tries to figure out the shortest memorable abbreviation of a directory that is usable by [z](https://github.com/ajeetdsouza/zoxide) to unambiguously jump to that directory.
* [zabrze](https://github.com/Ryooooooga/zabrze) - A ZSH abbreviation expansion plugin.
* [zaw](https://github.com/zsh-users/zaw) - ZSH anything.el-like widget. 
* [zce](https://github.com/hchbaw/zce.zsh) - Vim’s EasyMotion / Emacs’s ace-jump-mode for ZSH.
* [zcolors](https://github.com/marlonrichert/zcolors) - Uses your `$LS_COLORS` to generate a coherent theme for Git and your Zsh prompt, completions and [ZSH syntax highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [zconvey](https://github.com/zdharma/zconvey) - Adds ability to send commands to other ZSH sessions, you can use this to `cd $PWD` on all active Z shell sessions, for example.
* [zed](https://github.com/eendroroy/zed-zsh) - A simple wrapper for [z](https://github.com/rupa/z) to install it via a ZSH plugin.
* [zeit](https://github.com/zeit/zeit.zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [zeno](https://github.com/yuki-yano/zeno.zsh) - Fuzzy completion and utility plugin powered by [Deno](https://deno.land/).
* [zero](https://github.com/arlimus/zero.zsh) - Zero is both a plugin and a theme. See the github page for installation details.
* [zflai](https://github.com/zdharma/zflai) - A fast logging framework for ZSH.
* [zfzf](https://github.com/b0o/zfzf) - A fzf-powered file picker for ZSH which allows you to quickly navigate the directory hierarchy.
* [zgdbm](https://github.com/zdharma/zgdbm) - Adds GDBM as a plugin.
* [zgen-compinit-tweak](https://github.com/seletskiy/zsh-zgen-compinit-tweak) - Make compinit run only once after all loading is done by [zgen](https://github.com/tarjoilija/zgen).
* [zimfw-extras](https://github.com/PatTheMav/zimfw-extras) - Custom extras for zimfw, packaged into a zimfw plugin.
* [zinfo_line](https://github.com/kmhjs/zinfo_line) - Makes more information available to ZSH themes.
* [zinit-console](https://github.com/zinit-zsh/zinit-console) – A semigraphical (curses) consolette for [zinit](#zinit) plugin manager.
* [zinsults](https://github.com/ahmubashshir/zinsults) - Prints insults if a command fails.
* [zjump](https://github.com/qoomon/zjump) - Simplify ZSH directory navigation; jump to already visited, parent or sub folders.
* [zlong_alert](https://github.com/kevinywlui/zlong_alert.zsh) - Uses notify-send and ring a bell to alert you when a command that has taken a long time (default: 15 seconds) has completed.
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A fast alternative to `cd` that learns your habits.
* [zredis](https://github.com/zdharma/zredis) - Adds Redis database support, with `database_key` <-> `shell_variable` binding. Supports all data types.
* [zsh-in-docker](https://github.com/deluan/zsh-in-docker) - Automates ZSH + Oh-My-ZSH installation into development containers. Works with Alpine, Ubuntu, Debian, CentOS or Amazon Linux.
* [zsh-not-vim](https://github.com/redxtech/zsh-not-vim) - Provides a function that automatically shames the user for forgetting they weren't in vim.
* [zsh-z (agkozak)](https://github.com/agkozak/zsh-z) - Jump quickly to directories that you have visited "frecently." A native ZSH port of `z.sh` - without `awk`, `sed`, `sort`, or `date`.
* [zsh-z (ptavares)](https://github.com/ptavares/zsh-z) - Installs and loads [z](https://github.com/rupa/z.git).
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - A port of Bashmarks (by Todd Werth), a simple command line bookmarking plugin, for oh-my-zsh.
* [zshrc](https://github.com/freak2geek/zshrc) - Load local `.zshrc` files from your project scopes.
* [zsnapac](https://github.com/johnramsden/zsh-zsnapac) - Plugin for taking ZFS pre/post upgrade snapshots on Arch Linux.
* [zsnapshot](https://github.com/psprint/zsnapshot) - Adds command to dump the current ZSH state into a file, for later restoration by sourcing the snapshot file.
* [zui](https://github.com/zdharma/zui/) - ZSH User Interface library – CGI+DHTML-like rapid TUI application development with ZSH.

## Completions

These plugins add tab completions without adding extra functions or aliases.

* [_url-httplink](https://github.com/Valodim/zsh-_url-httplink) - Extends ZSH's \_urls completion, allowing it to complete urls from html pages.
* [aliyun](https://github.com/thuandt/zsh-aliyun) - Add completions for the [Aliyun CLI](https://github.com/aliyun/aliyun-cli).
* [ansible-server](https://github.com/viasite-ansible/zsh-ansible-server) - Completions for viasite-ansible/ansible-server.
* [antibody-completion](https://github.com/sinetoami/antibody-completion) - This plugin provides completion for [Antibody](https://github.com/getantibody/antibody) plugin manager.
* [appspec](https://github.com/perlpunk/App-AppSpec-p5) - Generating completions for Bash and ZSH from YAML specs
* [autopkg-zsh-completion](https://github.com/fuzzylogiq/autopkg-zsh-completion) - Completions for autopkg.
* [aws-completions](https://github.com/eastokes/aws-plugin-zsh) - Adds completion support for `awscli` to manage AWS profiles/regions and display them in the prompt.
* [aws_manager completions](https://github.com/EslamElHusseiny/aws_manager_plugin) - Add completions for the aws_manager CLI.
* [bash-completions-fallback](https://github.com/3v1n0/zsh-bash-completions-fallback) - Support `bash` completions for commands when no native ZSH one is available.
* [batect](https://github.com/batect/batect-zsh-completion/) - Adds tab completions for [batect](https://batect.dev/) build system.
* [berkshelf-completions](https://github.com/berkshelf/berkshelf-zsh-plugin) - Adds tab completion for berkshelf.
* [better-npm-completion](https://github.com/lukechilds/zsh-better-npm-completion) - Better tab completion for `npm`.
* [bosh-zsh-autocompletion](https://github.com/krujos/bosh-zsh-autocompletion) - Adds BOSH autocompletion.
* [brew-services](https://github.com/vasyharan/zsh-brew-services) - Completion plugin for homebrew services.
* [buidler](https://github.com/gonzalobellino/buidler-zsh) - Adds completion and useful aliases for NomicLabs Buidler tool [buidler.dev](https://buidler.dev).
* [bw](https://github.com/CupricReki/zsh-bw-completion) - Adds completion for [Bitwarden](https://bitwarden.com/).
* [cabal-completion](https://github.com/ehamberg/zsh-cabal-completion) - Add tab completion for cabal.
* [cabal](https://github.com/d12frosted/cabal.plugin.zsh) - Adds autocompletion for cabal.
* [carapace](https://github.com/rsteube/carapace) - Completion generator for Bash, Elvish, Fish, Oil, Powershell, Xonsh and ZSH. Note - not dynamic, you have to explicitly run it to generate completions for a command.
* [cargo](https://github.com/MenkeTechnologies/zsh-cargo-completion) - All the functionality of the original OMZ cargo completion, with additional support for remote crates via `cargo search` in `cargo add`.
* [carthage](https://github.com/squarefrog/zsh-carthage) - Provides completions and aliases for use with [Carthage](https://github.com/Carthage/Carthage).
* [cf-zsh-autocomplete](https://github.com/norman-abramovitz/cf-zsh-autocomplete-plugin) - Adds autocomplete for all [Cloud Foundry CLI](https://docs.cloudfoundry.org/cf-cli/) commands.
* [cod](https://github.com/dim-an/cod) - A completion demon for bash/fish/ZSH which creates completion functions on the fly when it sees you run something with `--help`.
* [codeception](https://github.com/shengyou/codeception-zsh-plugin) - Adds command completion for the Codeception Testing Framework.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Displays git info, whether you're logged in via `ssh`, return code of last command.
* [comonicon](https://github.com/Roger-luo/ComoniconZSHCompletion.jl) - Tab completions for [comonicon](https://github.com/Roger-luo/Comonicon.jl).
* [completions](https://github.com/zsh-users/zsh-completions) - A collection of extra completions for ZSH.
* [conda](https://github.com/esc/conda-zsh-completion) - ZSH tab completion for conda.
* [cpan](https://github.com/MenkeTechnologies/zsh-cpan-completion) - Adds `cpan install word<tab>` and `cpanm install <tab>` to complete remote CPAN package names.
* [ctop](https://github.com/gantsign/zsh-plugins/tree/master/ctop) - Tab completions for [ctop](https://github.com/bcicen/ctop).
* [dbic](https://github.com/lejeunerenard/dbic-migration-env) - Automatically sets up Environment variables for DBIx::Class::Migration's script and Dancer.
* [docker (chr-fritz)](https://github.com/chr-fritz/docker-completion.zshplugin) - Loads `docker` ZSH tab completions directly from **Docker for Mac**.
* [docker (felixr)](https://github.com/felixr/docker-zsh-completion) - Add tab completions for `docker`.
* [docker (greymd)](https://github.com/greymd/docker-zsh-completion) - Add tab completions for `docker` and `docker-compose`.
* [docker-enter-completion](https://github.com/primait/docker-enter-completion) - Command completion for [docker-enter](https://github.com/jpetazzo/nsenter).
* [dotnet](https://github.com/MenkeTechnologies/zsh-dotnet-completion) - Dotnet tab completion.
* [dropbox](https://github.com/zpm-zsh/dropbox) - A dropbox plugin for Zsh that provides `dropbox-cli` and `dropbox-uploader` commands.
* [drush_zsh_completion](https://github.com/webflo/drush_zsh_completion) - Drush autocomplete awesomeness for ZSH.
* [duell](https://github.com/jcxavier/oh-my-zsh-duell) - A ZSH plugin for [duell](https://github.com/gameduell/duell).
* [etcdctl](https://github.com/sheax0r/etcdctl-zsh) - Adds etcdctl tab completions.
* [extract (le0me55i)](https://github.com/le0me55i/zsh-extract) - Defines a function called extract that extracts the archive file you pass it, and supports a wide variety of archive filetypes.
* [extract (thetic)](https://github.com/thetic/extract) - Fork of the oh-my-zsh extract plugin.
* [flowr](https://github.com/oubasan/flowr) - Completion support for [git-flow](http://github.com/nvie/gitflow).
* [fly-zsh-autocomplete](https://github.com/Sbodiu-pivotal/fly-zsh-autocomplete-plugin) - Adds autocompletion options for all [Concourse CLI](https://www.concourse.ci/fly-cli.html) commands.
* [fzf-gcloud](https://github.com/mbhynes/fzf-gcloud) - Fuzzy completion to navigate and preview all Google Cloud SDK `gcloud` CLI commands
* [fzf-tab-completion](https://github.com/lincheney/fzf-tab-completion) - Add tab completion for ZSH, bash & applications using GNU Readline.
* [fzf-zsh-completions](https://github.com/chitoku-k/fzf-zsh-completions) - Fuzzy completions for [fzf](https://github.com/junegunn/fzf) and [ZSH](https://www.zsh.org/) that can be triggered by a trigger sequence that defaults to `**`.
* [gcloud](https://github.com/littleq0903/gcloud-zsh-completion) - Add completions for the Google Cloud SDK.
* [gentoo](https://github.com/gentoo/gentoo-zsh-completions) - providing ZSH completion support to various Gentoo tools that lack completion scripts upstream.
* [git-annex](https://github.com/Schnouki/git-annex-zsh-completion) - Allows tab completion for most git-annex commands.
* [git-flow](https://github.com/bobthecow/git-flow-completion) - ZSH completion support for [git-flow](http://github.com/nvie/gitflow).
* [github-cli](https://github.com/sudosubin/zsh-github-cli) - Tab completions for the github cli.
* [gitlab-runner](https://github.com/pseyfert/zsh-gitlab-runner-completion) - ZSH completions for gitlab-ci-multi-runner.
* [gradle-completion (gradle)](https://github.com/gradle/gradle-completion) - Bash and ZSH completion support for gradle.
* [gradle-completion (ninrod)](https://github.com/ninrod/gradle-zsh-completion) - ZSH completion support for gradle.
* [grid5000](https://github.com/pmorillon/grid5000-zsh-plugin) - Grid 5000 plugin - adds theme, autocompletions.
* [gulp (akoenig)](https://github.com/akoenig/gulp.plugin.zsh) - Autocompletion for your gulp.js tasks in the Z-Shell (ZSH).
* [gulp (srijanshetty)](https://github.com/srijanshetty/gulp-autocompletion-zsh) - Autocompletion for gulp.
* [hashlink](https://github.com/tong/zsh.plugin.hashlink) - Completions for [https://hashlink.haxe.org/](https://hashlink.haxe.org/).
* [haskell](https://github.com/coot/zsh-haskell) - Adds completions for `cabal`, `ghc` and `ghc-pkgs` commands.
* [haxelib](https://github.com/tong/zsh.plugin.haxelib) - Completions for haxelib.
* [helmfile](https://github.com/Downager/zsh-helmfile) - Adds autocompletion for `helm`.
* [inspr](https://github.com/ptcar2009/insprzsh) - Completions for [inspr](https://github.com/inspr/inspr)
* [ipfs](https://github.com/hellounicorn/zsh-ipfs) - Completions for the [Interplanetary File System](https://ipfs.io).
* [joe](https://github.com/corvofeng/joe-completion) - Adds completions for [joe](https://github.com/karan/joe) gitignore editor.
* [jtool-completion](https://github.com/beaugalbraith/jtool-completion) - ZSH completions for jtool.
* [jumpstorm-completion](https://github.com/netresearch/jumpstorm-zsh-plugin) - Adds autocompletion for [jumpstorm](https://github.com/netresearch/jumpstorm)
* [kafka](https://github.com/Dabz/kafka-zsh-completions) - Completions for Apache [kafka](https://kafka.apache.org).
* [keybase](https://github.com/rbirnie/oh-my-zsh-keybase) - Completions for [keybase](https://keybase.io/docs/command_line).
* [kitty](https://github.com/redxtech/zsh-kitty) - Completions for [kitty](https://sw.kovidgoyal.net/kitty/) terminal emulator.
* [kompose](https://github.com/gantsign/zsh-plugins/tree/master/kompose) - Add tab completions for [Kompose](http://kompose.io/).
* [kubeadm](https://github.com/gantsign/zsh-plugins/tree/master/kubeadm) - Add tab completions for [kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/).
* [kubectl-fzf](https://github.com/bonnefoa/kubectl-fzf) - Fast and powerful [`fzf`](https://github.com/junegunn/fzf)-powered autocompletion for `kubectl`.
* [lets](https://github.com/lets-cli/lets-zsh-plugin) - Add autocompletion for [lets](https://github.com/lets-cli/lets) cli task runner.
* [mooseX-App](https://github.com/perlpunk/MooseX-App-Plugin-ZshCompletion) - completion generator for Perl module `MooseX::App`.
* [more-completions](https://github.com/MenkeTechnologies/zsh-more-completions) - 10500 zsh compsys completions!
* [msfvenom](https://github.com/Green-m/msfvenom-zsh-completion) - Tab completions for Metasploit.
* [mx-honey](https://github.com/mukel/mx-honey) - Provides completions for [mx](https://github.com/graalvm/mx); a command-line tool used for the development of Graal projects. It's meant to improve the usual workflow `build unittest benchmark ...` ease discovery and provide handy aliases.
* [newman](https://github.com/selop/newman-autocomplete) - Provides autocompletion for the [Newman CLI](https://github.com/postmanlabs/newman).
* [nix](https://github.com/spwhitt/nix-zsh-completions) - Completions for [nix](https://nixos.org/nix/), [NixOS](https://nixos.org/), and [NixOps](https://nixos.org/nixops/).
* [node-ace](https://github.com/romch007/node-ace-zsh-completion) - Completions for `node ace`.
* [nova](https://github.com/rbirnie/oh-my-zsh-nova) - Provides auto-complete for nova.
* [npm-run](https://github.com/akoenig/npm-run.plugin.zsh) - Autocompletion support for `npm run`.
* [nx](https://github.com/jscutlery/nx-completion) - Completions for nx. Requires [`jq`](https://stedolan.github.io/jq/).
* [okta](https://github.com/sirhc/okta.plugin.zsh) - provides command line completions for the [`aws-okta`](https://github.com/segmentio/aws-okta) command.
* [op](https://github.com/sirhc/op.plugin.zsh) - Tab completions for [1Password](https://1password.com/)'s [op](https://1password.com/downloads/command-line/) command line tool.
* [packer](https://github.com/wakeful/zsh-packer) - Adds tab completion for [packer](https://packer.io).
* [pandoc-completion](https://github.com/srijanshetty/zsh-pandoc-completion) - Pandoc completion plugin.
* [parallels](https://github.com/benclark/parallels-zsh-plugin) - Add completions for Parallels desktop.
* [pass-zsh-completion](https://github.com/ninrod/pass-zsh-completion) - convenience repo to easily obtain [pass](https://www.passwordstore.org/) command completion for ZSH.
* [pip-completion](https://github.com/srijanshetty/zsh-pip-completion) - Autocompletion plugin for pip.
* [pipenv (AlexGascon)](https://github.com/AlexGascon/pipenv-oh-my-zsh) - Enables aliases for the most common pipenv commands.
* [pipenv (gangleri)](https://github.com/gangleri/pipenv) - Completions for `pipenv`.
* [pipenv (owenstranathan)](https://github.com/owenstranathan/pipenv.zsh) - automatically activates a **pipenv** when entering a directory if there is Pipfile in that directory. Includes `pipenv` completions.
* [pks-autocomplete](https://github.com/tybritten/pks-zsh-autocomplete-plugin) - Adds completions for Pivotal's [PKS CLI](https://network.pivotal.io/products/pivotal-container-service)
* [pmy](https://github.com/relastle/pmy) - General purpose context-aware ZSH completion engine powered by [fzf](https://github.com/junegunn/fzf).
* [quickjump](https://github.com/fikovnik/zsh-quickjump) - Adds tab completion support for [skim](https://github.com/lotabout/skim) for recent files and directories using [fasd](https://github.com/whjvenyl/fasd).
* [racket completion](https://github.com/racket/shell-completion) - Completion for [Racket](http://racket-lang.org).
* [rake-completion](https://github.com/unixorn/rake-completion.zshplugin) - Add fast tab completion for rakefile targets.
* [rancher-zsh-completion](https://github.com/go/rancher-zsh-completion) - Add completions for the Rancher CLI.
* [razor_plugin](https://github.com/dalang/oh-my-zsh_razor_plugin) - Provides autocomplete for [Razor](https://github.com/puppetlabs/Razor).
* [rustup](https://github.com/pkulev/zsh-rustup-completion) - Tab completions for Rustup.
* [s3cmd](https://github.com/FFKL/s3cmd-zsh-plugin) - Adds tab completions for [s3cmd](https://s3tools.org/s3cmd).
* [salesforce-cli](https://github.com/wadewegner/salesforce-cli-zsh-completion) - ZSH command completion for the Salesforce CLI. Requires [jq](https://stedolan.github.io/jq/).
* [sfdx-autocomplete](https://github.com/jayree/sfdx-autocomplete-plugin) - autocomplete plugin for sfdx.
* [spring-boot-plugin](https://github.com/linux-china/oh-my-zsh-spring-boot-plugin) - Adds autocompletions for [spring-boot](http://projects.spring.io/spring-boot/) commands.
* [ssh-agent (bobsoppe)](https://github.com/bobsoppe/zsh-ssh-agent) - Manage `ssh-agent`.
* [ssh-agent (hkupty)](https://github.com/hkupty/ssh-agent) - Automatically starts `ssh-agent` to set up and load whichever credentials you want for `ssh` connections.
* [ssh](https://github.com/zpm-zsh/ssh) - Add host completion for `ssh`.
* [startify](https://github.com/zdharma/zsh-startify) - vim-startify -like plugin for ZSH.
* [surf](https://github.com/beardcoder/surf.plugin.zsh) - Add completions for surf.
* [symphony (TheGrowingPlant)](https://github.com/TheGrowingPlant/symfony.plugin.zsh) - Autocompletion for Symfony 3 and 4 commands.
* [test-kitchen-zsh-plugin](https://github.com/pelletiermaxime/test-kitchen-zsh-plugin) - Add completions for [Test Kitchen](https://github.com/test-kitchen/test-kitchen)).
* [tinygo](https://github.com/sago35/tinygo-autocmpl) - Add tab completions for tinygo.
* [tmux pane words](https://gist.github.com/blueyed/6856354) - Key bindings to complete words from your [tmux](https://tmux.github.io) pane.
* [tugboat](https://github.com/DimitriSteyaert/Zsh-tugboat) - Adds autocompletion for [tugboat](https://github.com/petems/tugboat) command.
* [umake](https://github.com/zlsun/umake) - Tab completion for Ubuntu umake.
* [vert.x](https://github.com/davidafsilva/vert.x-omz-plugin) - Provides autocomplete features for the [vertx](https://vertx.io/) command.
* [web-open](https://github.com/AndrewHaluza/zsh-web-open) - Adds alias to open web pages. Only works with Ubuntu 20.
* [yabai](https://github.com/Amar1729/yabai-zsh-completions) - Add completions for macOS [yabai](https://github.com/koekeishiya/yabai/) tiling window manager.
* [yarn](https://github.com/g-plane/zsh-yarn-autocompletions) - Add autocompletions for `yarn add`, `yarn remove`, `yarn upgrade`, `yarn why` and `yarn run`.

## Themes

If you're using [Antigen](https://github.com/zsh-users/antigen), you can test these themes in a running ZSH with `antigen theme githubuser/repo`. If you're using [zgen](https://github.com/tarjoilija/zgen), add them to your `init.zsh` with `zgen load githubuser/reponame`.

* [000](https://github.com/Abid-Ahmad/oh-my-zsh-000-theme) - Multiline prompt with username, hostname, full path, return status and `git` decorations.
* [0i0](https://github.com/0i0/0i0.zsh-theme) - Optimized for dark terminal windows, uses nerdfont `git` status decorations.
* [14degree](https://github.com/saims0n/14degree-zsh-theme/) - Includes `git`, `virtualenv` and `rvm` status decorations.
* [4den](https://github.com/RunThem/zsh-theme-4den) - Minimalist. Includes `git` and `hg` status decorations.
* [aaron](https://github.com/aaronjamesyoung/aaron-zsh-theme) - Based on the Sorin theme.
* [abbr (theme)](https://github.com/PhilsLab/abbr-zsh-theme) - Displays an abbreviated version of the current directory path, shows the Python virtualenv, Rust version, `git` status, and the exit code of last command. Works well on dark backgrounds by default but colors can be easily customized.
* [absolute](https://github.com/NelsonBrandao/absolute) - Very clean looking theme with git status, node version and the exit code from the last command.
* [adamdodev](https://github.com/adamdodev/adamdodev-zsh-theme) - Includes `git` status decorations, name of your AWS profile, name of your Azure Service Principal, kubernetes context, terraform workspace, command status and current working directory.
* [adlee](https://github.com/adlee-was-taken/oh-my-zsh-osx/blob/master/adlee.zsh-theme) - macOS theme, requires a Powerline-compatible font.
* [af-magic-dynamic](https://github.com/rslavin/af-magic-dynamic) - Modified version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme) with dynamic path shortening.
* [aflah-bhari](https://github.com/AflahB/aflah-bhari-zsh-theme) - Modified version of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme in oh-my-zsh.
* [aftermath](https://github.com/schanur/aftermath) - Get a nice summary line after each command you run in your shell.
* [agitnoster](https://github.com/dbestevez/agitnoster-theme) - Based on [agnoster](https://gist.github.com/3712874) theme included in [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) and [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt). Shows detailed information about `git` status.
* [agkozak](https://github.com/agkozak/agkozak-zsh-prompt) - Uses three asynchronous methods to keep the ZSH prompt responsive while displaying the `git` status and indicators of SSH connection, exit codes, and `vi` mode, along with an abbreviated, `PROMPT_DIRTRIM`-style path. Very customizable. Asynchronous even on Cygwin and MSYS2.
* [agnoster-fcamblor](https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor) - Solarized [Agnoster](https://gist.github.com/agnoster/3712874) variant with `git` status information. Requires a unicode font and works best with a [solarized](https://github.com/altercation/solarized) terminal.
* [agnoster-fseguin](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [agnoster](https://gist.github.com/agnoster/3712874) variant with a right prompt.
* [agnoster-gentoo](https://github.com/r7l/agnoster-gentoo-zsh-theme) - A Gentoo flavored version of the [Agnoster ZSH Theme](https://github.com/agnoster/agnoster-zsh-theme) that includes user@hostname and `git` status decorations. Works better with a unicode font.
* [agnoster-j](https://github.com/apjanke/agnosterj-zsh-theme) - Optimized for [solarized](https://ethanschoonover.com/solarized/) color scheme, `git` or other VCS tools, and unicode-compatible fonts. Includes status of last command run, user@hostname, `git` status decorations, working directory, whether running as root, whether background jobs are running, and other information.
* [agnoster-mod](https://github.com/fsegouin/oh-my-zsh-agnoster-mod-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with a right-prompt.
* [agnoster-plus](https://github.com/jiahut/agnoster-plus.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant optimized for use with [Solarized Dark](https://github.com/altercation/solarized/blob/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors) terminal color scheme. Includes `git` status.
* [agnoster-refresh](https://github.com/fusion94/Agnoster-refresh) - [Agnoster](https://gist.github.com/agnoster/3712874) variant, includes battery and online status.
* [agnoster-repopath](https://github.com/ivanfurlan/agnoster-repopath-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) themes. Includes `git` and `mercurial` status, current time and time the last command took decorations in the prompt.
* [agnoster-timestamp-newline](https://github.com/DylanDelobel/agnoster-timestamp-newline-zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with timestamp and newline added.
* [agnosterAfro](https://github.com/afrozalm/agnosterAfro) - Based on [Powerline](https://github.com/Lokaltog/vim-powerline) and [Agnoster](https://gist.github.com/agnoster/3712874) themes and inspired by the [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme).
* [agnoster](https://gist.github.com/agnoster/3712874) - Optimized for solarized terminal color schemes, shows `git` decorations, user@host, working directory, the previous command's exit status and whether you are running with root privileges. Requires a Powerline-compatible font.
* [agnosterzak](https://github.com/zakaziko99/agnosterzak-ohmyzsh-theme) - Based on [Agnoster](https://gist.github.com/agnoster/3712874), shows battery life, date & time, `git` status, current directory and user & host information.
* [akzsh](https://github.com/awkimball/akzsh) - Works best with a dark terminal theme, includes `git` decorations.
* [alarangeiras](https://github.com/alarangeiras/alarangeiras-zsh-theme/) - Minimalist theme with `git` status decorations.
* [ale](https://github.com/alepimentel/ale-zsh) - Based on the fino theme. Includes `git`, `virtualenv` and `node` status decorations.
* [alien-minimal](https://github.com/eendroroy/alien-minimal) - Minimalist ZSH theme with `git` status displayed.
* [alien](https://github.com/eendroroy/alien) - Powerline-esque ZSH theme that shows `git` decorations and the exit code of the last command. Faster than many other prompts because it determines the `git` decorations asynchronously in a background process.
* [alpharized](https://github.com/NicoSantangelo/Alpharized) - Optimized to work with [solarized](http://ethanschoonover.com/solarized) dark terminals. It's a modified version of the [avit theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme).
* [amoyly](https://github.com/Br1an6/amoyly.zsh-theme) - An elegant and comfortable-reading theme based on [Agnoster](https://gist.github.com/agnoster/3712874).
* [andy](https://github.com/andymcguinness/andys-theme) - Modified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme with better `git` support.
* [angry fly](https://github.com/russjohnson/angry-fly-zsh) - Shows `git` information in the right hand prompt.
* [antsy](https://github.com/jeffmhubbard/antsy-zsh-theme) - Shows `git` branch and status decorations, virtualenv, exit status, jobs count, and vi-mode indicator.
* [aperiodic](https://github.com/piccobit/aperiodic-zsh-theme) - Shows `git` decorations, user, host, whether root, active Python virtual environment, current Ruby interpreter, visual and numeric status of the last command, power management status and time and date.
* [aphrodite](https://github.com/win0err/aphrodite-terminal-theme) - Minimalistic theme without visual noise. Displays only the necessary information: current user, hostname, working directory, `git` branch if one exists. Looks great both with dark and white terminals.
* [aplos](https://github.com/sunquan1991/aplos) - Minimal ZSH prompt with working directory, `git` local info, `git` remote info, time and exit code.
* [apollo](https://github.com/mjrafferty/apollo-zsh-theme) - A heavily customizable, compatible and performant ZSH theme that uses modules to enable features.
* [apple](https://github.com/bjrowlett2/apple-zsh-theme) - Minimalist theme with `git` status decorations.
* [arael](https://github.com/aknackd/zsh-themes) - Fork of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [archie](https://github.com/dcavalcante/archie) - Arch Linux inspired ZSH theme. Based on the [norm](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/norm.zsh-theme) theme.
* [arity](https://github.com/hybras/Arity-Zsh-Theme) - Arity is a simple theme designed for readability and to give an overview at a glance. Includes path and `git` decorations.
* [aronhoyer](https://github.com/aronhoyer/zsh-theme) - Minimalist theme with right-side `git` status decorations.
* [arrow-minimal](https://github.com/maxim-usikov/arrow-minimal.zsh-theme) - A minimal ZSH theme with `git` decorations.
* [asciigit](https://github.com/cemsbr/asciigit) - An ASCII-only theme for `git` users who don't want to use fonts with extra glyphs.
* [asq](https://github.com/AugustoQueiroz/asq-theme) - Based on [theunraveler](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#theunraveler).
* [astral](https://github.com/xwmx/astral) - Theme for dark backgrounds with zen mode. Works well with the zsh-users [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) plugin.
* [astro](https://github.com/iplaces/astro-zsh-theme/blob/master/README.md) - Based on the [`ys`](http://blog.ysmood.org/my-ys-terminal-theme/) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [async](https://github.com/mje-nz/zsh-themes) - Shows current directory, `git` state, return value of last command if it had an error code, number of background jobs, execution time of long-running commands, current python virtualenv.
* [aterminal](https://github.com/guiferpa/aterminal) - Displays Nodejs, NPM, Docker, Go, Python, Elixir and Ruby information in the prompt.
* [avil](https://github.com/avil13/avil-zsh-theme) - Minimalist theme with `git` decorations.
* [avit-d2k](https://github.com/fdaciuk/avit-da2k) - Based on the oh-my-zsh [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme, with small changes.
* [avit-mod](https://github.com/zlsun/avit-mod) - Modified version of oh-my-zsh's [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme) theme.
* [banana](https://github.com/sorcererxw/banana-zsh-theme) - Includes `git` status decorations and current directory.
* [bandit](https://github.com/Holger-Will/zsh_bandit) - Another Powerline variant.
* [bar (anki-code)](https://github.com/anki-code/bar-theme) - Minimalist settings for [p10k](https://github.com/romkatv/powerlevel10k).
* [bar (xp-bar)](https://github.com/xp-bar/zsh-bar-theme) - Includes username, host, pwd, `git` status decorations and  3x hour reminders to drink water.
* [bash](https://github.com/starseekist/bash-zsh-theme) - Looks like the default `bash` prompt.
* [bashi](https://github.com/eli-oat/bashi) - Optimized for Ahmet Sülek's [Flat UI Terminal](https://github.com/ahmetsulek/flat-terminal) theme and Pasquale D'Silva's [Saturn Terminal](https://github.com/psql/saturn-colors) theme.
* [bastard](https://github.com/jsundqvist/bastard.zsh-theme) - Modified version of [gitster](https://github.com/zimfw/gitster) theme for [ZIM](https://github.com/zimfw/zimfw).
* [bearable](https://github.com/JanmanX/bearable-zsh) - Works well with dark terminal backgrounds.
* [bedbugs](https://github.com/justino/zsh-theme-bedbugs) - Inspired by [Agnoster](https://gist.github.com/agnoster/3712874), this multiline prompt includes `git` status information, background job count, working directory, user and hostname, Python virtualenv when present, colored return value of last command and root/user sigil.
* [beer](https://github.com/tcnksm/oh-my-zsh-beer-theme) - Inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme), but with beer icons.
* [bender](https://github.com/specious/bender) - Fancy two-line prompt with git integration.
* [bgnoster](https://github.com/vvvvv/bgnoster.zsh-theme) - [Agnoster](https://gist.github.com/agnoster/3712874) variant with unicode symbols baked in.
* [biradate](https://github.com/vemonet/zsh-theme-biradate) - Based on the [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) theme, but displays the date instead of the username in the prompt.
* [birame](https://github.com/maniat1k/birame) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [birav2](https://github.com/shahid64/birav2-theme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme). Includes `git`, `rvm` and `virtualenv` status decorations.
* [bklyn](https://github.com/gporrata/bklyn-zsh) - Variant of [Powerlevel9k](https://github.com/bhilburn/powerlevel9k) with customizations applied.
* [black-Void](https://github.com/black7375/BlaCk-Void-Zsh) - Includes account info, root user, using ssh, directory lotation, write permission, vcs info decorations.
* [blackrain](https://github.com/ginfuru/zsh-blackrain) - Another `git`-aware theme.
* [blazux](https://github.com/blazux/omz-theme) - Includes `git` status decoration and a smiley/sad face indicator of the last command's exit status.
* [blinks (max13ft)](https://github.com/max13fr/blinks.zsh-theme) - Adds mercurial support to oh-my-zsh's [blink](https://github.com/max13fr/blinks.zsh-theme) theme.
* [blinks-xfan](https://github.com/ixfan/blinks-xfan) - Based on the existing theme [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme).
* [bliss](https://github.com/joshjon/bliss-zsh) - A delicate theme that injects color without overwhelming your workspace. Designed to be used with the [bliss iTerm](https://github.com/joshjon/bliss-iterm) color scheme and [bliss dircolors](https://github.com/joshjon/bliss-dircolors). Includes `git` status decorations.
* [blokkzh](https://github.com/KorvinSilver/blokkzh) - Theme based on oh-my-zsh's built in [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) theme. Requires a font with unicode support.
* [blox](https://github.com/yardnsm/blox-zsh-theme) - A minimal and fast ZSH theme that shows you what you need. It consists of blocks: each block is shown inside a pair of \[square brackets\], and you can add blocks by simply creating a function.
* [bluehigh](https://github.com/hiroppy/bluehigh.zsh-theme) - Minimal theme, displays `git` information.
* [bluelines](https://github.com/apbarrero/bluelines) - Clear and blue theme.
* [bogo](https://github.com/cubasepp/zsh-bogo-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme). Includes `git` and ruby version decorations.
* [boom](https://github.com/the0neWhoKnocks/zsh-theme-boom) - Multiline theme, best on dark backgrounds.
* [bougenville](https://github.com/bougenville/zsh-theme) - Variant of [dallas](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dallas.zsh-theme).
* [bronze](https://github.com/reujab/bronze) - A cross-shell customizable powerline-like prompt with icons written in go. Requires [nerd-fonts](https://github.com/ryanoasis/nerd-fonts).
* [brs](https://github.com/evenhold/brs-zsh-theme) - Displays the current song in the prompt with `audtool`.
* [bruh](https://github.com/haze/bruh) - Includes `git` status decorations.
* [brunty](https://github.com/Brunty/omz-brunty) - Brunty theme.
* [bryce-robbyrussell](https://github.com/Bryan-Cee/bryce-robbyrussell) - Inspired by the [powerline](https://github.com/Lokaltog/vim-powerline) and [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) themes.
* [bttf-color](https://github.com/yasuhiroki/bttf-color-zsh) - BTTF color theme.
* [bubblegum](https://github.com/ice-bear-forever/bubblegum-zsh) - Minimalist bright pink theme with a triangular glyph and your working directory, nothing else—leaving you with the cleanest shell possible.
* [bubblified (hohmannr)](https://github.com/hohmannr/bubblified) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme). Works best with [nerdfonts](https://github.com/ryanoasis/nerd-fonts).
* [bubblified (varaki)](https://github.com/varaki/bubblified-varaki.zsh-theme) - Based on [bubblified (hohmannr)](https://github.com/hohmannr/bubblified). Changes color when root.
* [bullet-train](https://github.com/caiogondim/bullet-train.zsh) - Inspired by the Powerline Vim plugin. It aims for simplicity, showing information only when it's relevant.
* [bunnyruni.min](https://github.com/mikeumus/bunnyruni.min) - [@jopcode's](https://github.com/jopcode) [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) ZSH theme, modified to just display time and directory.
* [bunnyruni](https://github.com/jopcode/oh-my-zsh-bunnyruni-theme) - Simple, clean, and beautiful theme.
* [bureau-env](https://github.com/angus-lherrou/bureau-env) - Modification of the Oh-My-Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the `git` block.
* [bureau-parrot](https://github.com/BenjaminGuzman/bureau-parrot) - Based on [bureau](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/bureau.zsh-theme). Includes `git` decorations.
* [bureau](https://github.com/isqua/bureau) - A clear and informative two-lined prompt. Includes git status optimized for large repositories.
* [buster](https://github.com/grantbuster/buster_zsh_theme) - Plays well with WSL2. Based loosely on Fox and Jonathan themes from oh-my-zsh.
* [cactus](https://github.com/welksonramos/cactus) - Minimalist theme with `git` status decorations.
* [candy-light](https://github.com/NicolaiRuckel/oh-my-zsh-candy-light) - Light version of the candy theme.
* [cayun](https://github.com/comeacrossyun/ys-cayun.zsh-theme) - Shows active Python version and `git` decorations in the prompt.
* [celestialorb](https://github.com/celestialorb/zsh-theme) - Powerline-inspired theme by @celestialorb. Includes `git` status decorations, Kubernetes cluster information (if any), current AWS profile and region, and  active virtualenv.
* [cf-ps1](https://github.com/mdan16/cf-ps1) - Displays the current foundation and organization and space of [Cloud Foundry](https://www.cloudfoundry.org/) in your prompt.
* [ch4rli3](https://github.com/ch4rli3kop/ch4rli3.zsh-theme) - Lean and simple theme.
* [chaffee](https://github.com/jasonchaffee/chaffee.zsh-theme) - Based on sorin. Shows the current active versions of Java, Scala, Go, Node, Python and Ruby.
* [chaotic-beef](https://github.com/ARtoriouSs/chaotic-beef-zsh-theme) - A tiny and beautiful theme for Oh-My-Zsh without anything superfluous. Includes `git` status decorations.
* [charged](https://github.com/robwierzbowski/charged-zsh-theme) - A ZSH prompt optimized for the [solarized](https://github.com/altercation/solarized) dark terminal theme.
* [chello](https://github.com/Abdalla981/chello) - Works well on dark backgrounds. Depends on [autojump](https://github.com/wting/autojump), [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) and [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting).
* [chi](https://github.com/akinjide/chi) - A ZSH theme optimized for iTerm 2 users on macOS.
* [chrisandrew.cl](https://github.com/chrisandrewcl/chrisandrew.cl.zsh-theme) - Includes `git` decorations. Requires powerline-compatible terminal font.
* [cinnabar](https://github.com/nvillapiano/zsh-theme---cinnabar) - Shows timestamp, large line breaks, git branch and status.
* [clarity](https://github.com/nbitmage/clarity.zsh) - Designed for for simpleness and extensibility.
* [classyTouchName](https://github.com/dylanroman03/classyTouchName) - Oh-my-zsh theme inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh). Works better with dark backgrounds. Includes `git` status decorations.
* [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) - Minimal, clean theme with `git` support.
* [clean (akz92)](https://github.com/akz92/clean) - Minimalist ZSH theme.
* [clean (brandonRoehl)](https://github.com/BrandonRoehl/zsh-clean) - A minimalist variant of [pure](https://github.com/sindresorhus/pure). Pure is not clean, clean is not pure.
* [clean (patr1ot)](https://github.com/Patr1ot/clean.zsh-theme) - Fork of the upstream [clean](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#clean) with host information added.
* [cleansh](https://github.com/diegoos/cleansh) - Minimalist, includes `git`, Ruby, node and Python version status decorations. Works with standard fonts.
* [clearance](https://github.com/H00N24/clearance-theme-oh-my-zsh) - minimalist theme with `git`, nix-shell and virtualenv status decorations.
* [cloudy](https://github.com/Huvik/Cloudy) - Minimal cloudy ZSH theme.
* [clover](https://github.com/tzing/clover.zsh-theme) - Inspired by [zeta](https://github.com/skylerlee/zeta-zsh-theme) and [pure](https://github.com/sindresorhus/pure).
* [cmder-wsl](https://github.com/szyminson/cmder-wsl-zsh) - Configuration file for [cmder](http://cmder.net/) configured to work in quake mode with ZSH and a modified [Agnoster](https://gist.github.com/agnoster/3712874) theme.
* [cmder](https://github.com/potasiyam/cmder-zsh-theme) - A ZSH theme that matches the theme of Cmder, a popular terminal emulator for windows.
* [cobalt2](https://github.com/wesbos/Cobalt2-iterm) - Wes Bos' Cobalt 2 theme for ZSH and iTerm 2.
* [cobalt2git](https://github.com/alexeimun/cobalt2git) - Cobalt 2 theme with `git` extensions.
* [codemachine](https://github.com/CodeMonkeyMike/ZshTheme-CodeMachine) - Codemachine theme.
* [codemonkey-on-fire](https://github.com/babette-landmesser/codemonkey-on-fire.zsh-theme) - Inspired by [bashi](https://github.com/eli-oat/bashi), includes a monkey and `git` information in your prompt.
* [coffeenostor](https://github.com/CoffeeVector/coffeenostor-zsh-theme) - Based on agnoster, but has a right-prompt for vi-mode that displays `--INSERT--` and `--NORMAL--`, in a powerline look.
* [coldark](https://github.com/ArmandPhilippot/coldark-zsh-theme) - A blue-grey theme designed for reading comfort. Includes `git` decorations.
* [collon](https://github.com/lambdalisue/collon.zsh) - Lightweight theme with `git` status decorations, cwd, time, host, exit status of last command. Does not require special fonts.
* [colorbira](https://github.com/CristianCantoro/colorbira-zsh-theme) - Allows per-host prompt coloring, displays `rvm`, `virtualenv` and `git` information.
* [common](https://github.com/jackharrisonsherlock/common) - A simple, clean and minimal prompt, displays current working directory, hostname, AWS vault role, background jobs, current SHA, exit code of last command, and `git` branch and status.
* [comxtohr](https://github.com/comxtohr/comxtohr-zsh-iterm-theme) - Brightly colored theme optimized for dark backgrounds.
* [cordial](https://github.com/stevelacy/cordial-zsh-theme) - Clean and effective ZSH theme with git and npm support.
* [cramin](https://github.com/FelipeCRamos/craminzsh) - Minimal interface with support for github plugins, based on [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [cryo](https://github.com/cryocaustik/cryo-zsh-theme) - A standalone clone of the original oh-my-zsh theme with date and time added.
* [crème fraîche](https://github.com/koenwoortman/creme-fraiche-zsh-theme) - Works best with light terminal backgrounds, includes `git` and `vi`-mode status decorations.
* [cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - A macOS oh-my-zsh shell theme with Cute emoji based on the Powerline Vim plugin.
* [cxzh](https://github.com/MakeWorkSimple/cxzh.zsh-theme) - Works well on dark background, has `git` status decorations.
* [cypher-ruby](https://github.com/ston1x/cypher-ruby) - Similar to [cypher](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cypher.zsh-theme) but includes the active Ruby version.
* [czsh](https://github.com/Cellophan/czsh) - [ZSH](https://en.wikipedia.org/wiki/Z_shell) with [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh) and the [agnoster](https://github.com/agnoster/agnoster-zsh-theme) theme in a container.
* [daily](https://github.com/ghlin/zsh-theme-daily) - Includes `git` and `ssh` status decorations.
* [damino](https://github.com/njdom24/Damino-Zsh-Theme) - Minimal powerline-esque theme with `git` decorations.
* [dangerroom](https://github.com/abbreviatedman/dangerroom) - Informative, minimal, and, above all, X-Men themed.
* [daniloheraclio](https://github.com/daniloheraclio/daniloheraclio-zsh-theme) Inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme. Has `git` and last command exit status decorations. Requires a nerdfont to render properly.
* [darkblood-modular](https://github.com/InAnimaTe/darkblood-modular) - This version of the popular [darkblood](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/darkblood.zsh-theme) theme has been enhanced with a near complete rewrite enabling modularity and a few new features.
* [darksoku](https://github.com/TooSchoolForCool/darksoku-zsh-theme) - Darksoku theme is based on the [ys](http://blog.ysmood.org/my-ys-terminal-theme/) and [astro](https://github.com/iplaces/astro-zsh-theme) themes.
* [dbern](https://github.com/dbernhard-0x7CD/zsh-dbern-theme) - Includes battery status and load average decorations.
* [delta (asavoy)](https://github.com/asavoy/delta-zsh-theme) - Minimal ZSH theme to reduce distractions. Includes an iTerm color settings file.
* [delta (dongri)](https://github.com/dongri/delta-zsh-theme) - Another minimal theme with embedded `git` status.
* [delta-prompt](https://github.com/cusxio/delta-prompt) - A minimal ZSH prompt.
* [dexter](https://github.com/shvenkat/zsh-theme-dexter) - A theme with an emphasis on the right side (hence the name) of the terminal.
* [dino](https://github.com/OdilonDamasceno/dino-zsh-theme) - Includes decorations for node, golang, flutter, lua, python & java, also includes `git` decorations. Requires nerdfonts.
* [dissonance](https://github.com/RyanScottLewis/theme-dissonance-zsh) - Comes with custom LSCOLORS and LS_COLORS settings files, works with both dark and light terminal themes.
* [diy-ys](https://github.com/aprilnops/zsh-theme) - Variant of [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) without hostname or time.
* [dkniffin](https://github.com/dkniffin/zsh-theme) - Includes `ruby` version and `git` status.
* [dmx](https://github.com/domix/dmx.zsh-theme) - Optimized for dark terminal windows.
* [doodleshell](https://github.com/cdodd/doodleshell-zsh-theme) - Minimalist theme, includes `git`, `terraform` and `aws` status decorations.
* [dp](https://github.com/davidparsson/zsh-dp-theme) - Low contrast theme that shows current git branch, if the repository is dirty and the value of `$PYENV_VERSION`.
* [dr4kk0nnys_v2](https://github.com/Dr4kk0nnys/Dr4kk0nnys_theme_ohmyzsh_v2/) - Works well on dark backgrounds, includes `git` status decorations.
* [dracula](https://github.com/dracula/zsh) - A dark theme for Atom, Alfred, Chrome DevTools, iTerm 2, Sublime Text, Textmate, Terminal.app, Vim, Xcode, and ZSH.
* [dragon](https://github.com/sabertazimi/dragon-zsh-theme) - Minimalistic, includes `git` status information.
* [droolscar](https://github.com/isuke/droolscar) - [Powerline](https://github.com/powerline/powerline) variant.
* [dtheme](https://github.com/OlukaDenis/DTheme) - Optimized for people using a solarized terminal color scheme and `git`. Works best with a unicode font.
* [duckster](https://github.com/ducky/duckster) - A fork of Gitster ZSH theme that's more ducky fresh.
* [ducula](https://github.com/janjoswig/Ducula) - Inspired by Dracula project. Includes `git` status decorations, username and hostname abbreviations, virtual environment, current working directory, return status of last command and the time.
* [dustmod](https://github.com/bmihaila/dustmod) - Derived from the [dst](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/dst.zsh-theme) theme in oh-my-zsh.
* [dzhi](https://github.com/pentago/dzhi-zsh-theme) - Optimized for people using [Nord](https://www.nordtheme.com/). Includes `git` status decorations.
* [eckig](https://github.com/fouladi/eckig) - Minimalist theme with utf-8 icons. Includes `git` status decorations and a clock.
* [eggshausted](https://github.com/inutano/eggshausted) - A `git`-aware theme for people who are tired of getting errors.
* [eleastic](https://github.com/jinseobhong/eleastic-zsh-theme) - Inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for solarized terminal theme, includes `git` status decorations. Requires powerline-compatible font.
* [elessar](https://github.com/fjpalacios/elessar-theme) - A `git`-aware theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme). Requires a Powerline-compatible font.
* [elsa](https://github.com/faycito/elsa) - Includes root status, pwd and `git` status decorations.
* [emojeer](https://github.com/lxynox/emojeer-ohmyzsh) - Emoji flavored [oh-my-zsh](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ohmyzsh/ohmyzsh) theme.
* [emoji](https://github.com/masaakifuruki/emoji.zsh-theme) - Based on  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme with the `git` prompt symbols replaced with emoji for better clarity.
* [emojirussell](https://github.com/Bergiu/emojirussell) - Based on  [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) oh-my-zsh theme, with status decorations for current working directory, last command exit status, `git` branch and status.
* [endless-dog](https://github.com/qwelyt/endless-dog) - oh-my-zsh-compatible theme that mimics grml-zsh-config.
* [enormous](https://github.com/leighmcculloch/zsh-theme-enormous) - Takes up an enormous amount of space in the terminal.
* [erfan](https://github.com/ekm507/erfan-zsh-theme) - Combination of the of [af-magic](https://github.com/andyfleming/oh-my-zsh) and [macovsky](https://github.com/championswimmer/oh-my-zsh/blob/master/themes/macovsky.zsh-theme) themes. Includes `git` and `virtualenv` status decorations.
* [eriner](https://github.com/zimfw/eriner) - A Zim fork of the Powerline-inspired [agnoster](https://github.com/agnoster/agnoster-zsh-theme) prompt theme. Includes `git` status decorations.
* [eubw](https://github.com/eptaccio/eubw-oh-my-zsh-theme) - A simple theme with `git` information.
* [eucalyptus](https://github.com/relastle/eucalyptus) - Simple one-line theme for minimalist vi-mode users inspired by [agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status indicator, `vi`-mode indicator, current directory and current path.
* [excess](https://github.com/davydovanton/excess.zsh-theme) - Simple ZSH color theme.
* [ez-pz](https://github.com/mangosmoothie/ez-pz) - Minimalist theme with `git` status decorations, inspired by [bureau](https://github.com/isqua/bureau).
* [fall](https://github.com/jottenlips/seasonal-zshthemes) - Minimalist theme with fall icons. Includes `git` status decorations.
* [fattyarrow](https://github.com/sohnryang/fattyarrow) - Minimal ZSH prompt that works better on dark backgrounds.
* [fdT2K](https://github.com/FDT2k/FDT2K-theme)- Based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme), preset to include virtualenv, last command status, `nvm`, `docker machine` and `git`, `hg` and `bzr` status decorations.
* [feder](https://github.com/samfeder/mac-themes/blob/master/feder.zsh-theme) - Clean, simple, compatible and meaningful. Tested on Linux, Unix and Windows under ANSI colors.
* [filthy](https://github.com/molovo/filthy) - A disgustingly clean ZSH prompt.
* [fish](https://github.com/Raniconduh/zshfish) - ZSH theme reminiscent of the default fish shell theme. Includes `git` status decorations.
* [fishy-lite](https://github.com/sudorook/fishy-lite) - Fork of the original [fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy) theme in oh-my-zsh with much of the extraneous stuff cut out to improve load speeds. Includes a battery gauge and `git` status display that can be enabled on the right-hand side of the prompt.
* [fishy2](https://github.com/akinjide/fishy2) - ZSH theme inspired by [original fishy](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#fishy).
* [fizzy](https://github.com/Brokenhammer72/fizzy) - Minimalist prompt, includes `git` status decorations.
* [fluent-git](https://github.com/RobertKozak/fluent-git) - Displays time of last command execution, error code, hostname, username, `git` status, kubernetes cluster and namespace, path and ssh connection status.
* [forerunner](https://github.com/OpenReplyDE/zsh-forerunner) - Custom setup for [powerlevel9k](https://github.com/bhilburn/powerlevel9k). Includes `git` status decorations.
* [fortuity](https://github.com/VGamezz19/oh-my-zsh-fortuity-theme) - Includes status of last command, `git` information and current directory.
* [frank](https://github.com/ronmackley/frank-theme) - Frank keeps to the point, displaying information compactly but readably on a single line. Frank keeps to the facts and only tells you extra things when they are important.
* [friendly-fiesta](https://github.com/bruino/friendly-fiesta) - Fork of [terminal-party](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/terminalparty.zsh-theme) theme.
* [frisk-arrow](https://github.com/BakeRolls/frisk-arrow) - A theme based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh-theme.
* [frisk-red](https://github.com/aishsingh/zsh/tree/master/frisk-red) - Red version of the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) theme from oh-my-zsh.
* [fritz](https://github.com/fritzccc/fritz-zsh-theme) - Works well on dark backgrounds. Includes `git` status decorations.
* [frlo](https://github.com/fiorillo/frlo) - Uses your computer's hostname to come up with a (hopefully) unique three-color theme to display in your prompt, so you know at a glance which machine you're logged into.
* [funkyberlin](https://github.com/Ottootto2010/funkyberlin-zsh-theme) - A colorful two-line theme with support for `git` and `svn`.
* [furio](https://github.com/hectorpalmatellez/furio-theme) - Fork of the [Cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme) oh-my-zsh theme. with different colors and emojis.
* [furry-umbrella](https://github.com/kb10uy/zsh-theme-furry-umbrella) - Colorful theme, works better on a dark background.
* [gaia](https://github.com/gcaracuel/gaia.zsh-theme) - Originally a fork of [Bureau](https://github.com/isqua/bureau) adds new virtual environments info to the prompt: Kubernetess, virtualenv, rbenv and Java versions. Includes git status integration.
* [gal](https://github.com/slowstab/gal) - gal is based on [gallois](https://github.com/ohmyzsh/ohmyzsh/commits/master/themes/gallois.zsh-theme).
* [garden](https://github.com/fecat233/garden) - Works better with a dark terminal background, includes `git` status decorations.
* [garrett](https://github.com/chauncey-garrett/zsh-prompt-garrett) - Prezto prompt with the information you need the moment you need it.
* [gawaine](https://github.com/nicolaracco/gawaine.zsh-theme) - Nicola Racco's theme. Requires `rvm` & `git` plugins.
* [gbt](https://github.com/jtyr/gbt) - Go Bullet Train is a very customizable prompt builder inspired by Bullet Train that runs much faster. Includes many different status cars.
* [gentoo](https://github.com/ikelos/gentoo-zsh-theme) - Breaks out the oh-my-zsh gentoo theme into a separate repo for non-omz users.
* [geometryHostInfo](https://github.com/Fuzen-py/GeometryHostInfo) - Adds host info to the [geometry](https://github.com/geometry-zsh/geometry) theme.
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [ghoti](https://github.com/lonr/ghoti) - Mimics the `fish-shell` default prompt. Includes `git` decorations.
* [gideon](https://github.com/userhiren/oh-my-zsh-gideon-theme) - Inspired by [avit](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/avit.zsh-theme), includes `git` decorations, IP address, host and path.
* [gimbo](https://github.com/gimbo/gimbo.zsh-theme) - A variant of [purepower](https://github.com/romkatv/dotfiles-public/blob/master/.purepower) with more features, a little eye candy and context-sensitive extra lines. Includes `git` status decorations, history number, username/hostname context, directory status, status of last command if it failed, and the Python virtualenv name if present.
* [gimme](https://github.com/nralbrecht/gimmezsh) - A simplistic theme for ZSH with `git` integration. Inspired by the [gitsome](https://github.com/mtully/gitsome) theme.
* [girazz](https://github.com/mdentremont/girazz) - A modification to the gnzh theme which adds `vi` mode to the right prompt.
* [git-prompt (olivierverdier)](https://github.com/olivierverdier/zsh-git-prompt) - Displays information about the current `git` repository. In particular the branch name, difference with remote branch, number of files staged or changed, etc.
* [git-prompt (woefe)](https://github.com/woefe/git-prompt.zsh) - A fast, customizable, pure-shell, asynchronous Git prompt for ZSH heavily inspired by Olivier Verdier's [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) and very similar to the "Informative VCS" prompt of fish shell.
* [git-simple](https://github.com/ZakharEl/git-simple-theme) - Simple theme that includes detailed `git` status decorations.
* [gitsome](https://github.com/mtully/gitsome) - Super simple prompt with `git` info, optimized for the [Flat Terminal](https://github.com/ahmetsulek/flat-terminal) color scheme.
* [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme) - Shows command and `git` status decorations.
* [gitster (shashankmehta)](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) - When in a `git` repo, it shows the location from the `git` repository root folder. When not in a `git` repo, it shows the path relative to home, `~`.
* [gitster (zimfw)](https://github.com/zimfw/gitster) - Zim fork of shashankmehta's [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) prompt theme
* [gitsterv2](https://github.com/xakraz/gisterv2-zsh-theme) - Forked from the original [gitster](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#gitster) theme.
* [glimmer](https://github.com/martnu/glimmer) - Includes `git` branch, time and user@host.
* [gndx](https://github.com/gndx/gndx-zsh-theme) - Includes `git` status, hostname, directory and last command exit status decorations.
* [gnrnzh](https://github.com/PaoloneM/gnrnzh-zsh-theme) - Customization of [gnzh.zsh-theme](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme) from oh-my-zsh.
* [gocilla](https://github.com/goranvasic/gocilla-iterm-zsh) - Theme for iTerm 2 and ZSH, includes `git` decorations, user@host, path and date.
* [grayt](https://github.com/evanthegrayt/grayt-zsh-theme) - Simple yet informative theme that includes `git` decorations and the return status of the last command.
* [griffin](https://github.com/GriffinLedingham/griffin.zsh-theme) - Minimalist, includes `git` status decorations.
* [grs](https://github.com/gersontpc/zsh-theme-grs) - Includes `git` status decorations, user id and working directory.
* [gruvbox](https://github.com/sbugzu/gruvbox-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874), uses the same colors from the [gruvbox](https://github.com/morhetz/gruvbox) `vim` plugin.
* [guezwhoz](https://github.com/guesswhozzz/guezwhoz-zshell) - Minimalist, includes `git` status decorations.
* [guri](https://github.com/victorfsf/guri) - A Simple and fast Oh-My-Zsh theme, based on [Pure](https://github.com/sindresorhus/pure)'s design.
* [hackersaurus](https://github.com/bhilburn/hackersaurus) - A theme with `git` status and exit code of last command run embedded in the prompt. Related to [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [halfeld](https://github.com/IgorHalfeld/halfeld-zsh-theme) - Minimalist theme with `git` decorations.
* [halil](https://github.com/5m0k3r/zsh-themes) - Fork of oh-my-zsh's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme) theme.
* [hana-matcha](https://github.com/arturoalviar/hana-matcha-zsh-theme) - A simple theme with the first character being 花(hana), the kanji for flower. This theme was inspired by a keycap set called DSA Hana. This pairs well with the [hana atom](https://github.com/arturoalviar/hana-matcha-syntax) theme. Includes `git` status decorations.
* [handy](https://github.com/HanleyLee/Handy) - Light-weight prompt with `git` decorations.
* [hanpen](https://github.com/kojole/hanpen.zsh-theme) - Shows `git` branch and status, last command exit code, last command execution time if more than `ZSH_THEME_HANPEN_CMD_MAX_EXEC_TIME`.
* [hapin](https://github.com/hanamiyuna/hapin-zsh-theme/blob/master/hapin.zsh-theme) - Based on oxide, includes `git` status decorations and current user/host information.
* [haribo](https://github.com/haribo/omz-haribo-theme) - Simple `git` status + timestamp in prompt.
* [hcompact](https://github.com/fusion809/zsh-theme) - Displays time, OS (including distro if on Linux), directory and whether running as root.
* [heart](https://github.com/gko/heart) - Heart themed prompt for light backgrounds.
* [hedgehog](https://gist.github.com/hedgehog1029/dfbb7e66511e2c399157) - Simple, no-nonsense and clean, with support for `git` and return codes.
* [hedroed-bureau](https://github.com/Hedroed/hedroed-bureau.zsh-theme) - Based on [bureau](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bureau), with added `git` status decorations and `npm` status.
* [helb](https://github.com/helb/helb.zshtheme) - Loosely based on Gentoo's old `bash` theme. Includes `git` information, return value of last command, and uses different username color and prompt char for users (`$`) and root (`#`).
* [hematite](https://github.com/bigdave/hematite) - Minimalist promot that tries to show only the status decorations that are actively useful at a given time.
* [hexagon](https://github.com/diogoazevedos/hexagon) - Minimalist zsh theme based on [geometry](https://github.com/geometry-zsh/geometry).
* [hfulldate](https://github.com/fusion809/zsh-theme) - Displays time, date, OS (including distro if on Linux), directory and whether running as root.
* [hhktony](https://github.com/hhktony/hhktony.zsh-theme) - Inspired by robbyrussell theme + ssh connection status prompt.
* [hina](https://github.com/ucpr/hina) - Written in `golang`, includes `git` status decoration and kubernetes context.
* [hip-fellow](https://github.com/haitaim/hip-fellow) - Includes `git` status decorations and works with standard fonts.
* [hipstersmoothie-p9x](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - A variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [honukai-iterm](https://github.com/oskarkrawczyk/honukai-iterm-zsh) - Honukai theme and colors for oh-my-zsh and iTerm 2.
* [horizontal](https://github.com/nuimk/horizontal) - Two line prompt with a horizontal separator.
* [hornix](https://github.com/fusion809/zsh-theme) - Displays time & date, OS (including distro if on Linux), directory and whether running as root.
* [horse-sh](https://github.com/emileswarts/horse-sh) - A very minimal brown/red ZSH theme.
* [hub](https://gist.github.com/hub23/c226b1c77446e099f7684b0d21c6b22a) - Simple and clean, includes the return code of the last command executed.
* [hug](https://github.com/xxninjabunnyxx/hug-zsh) - When you're working and need a hug. Includes `git` status.
* [humbled](https://github.com/saravanabalagi/zsh-theme-humbled) - A clean and humble theme with support for `condaenv`, `virtualenv` and `git` status decorations left aligned with the working directory in bold.
* [hyper](https://github.com/willmendesneto/hyper-oh-my-zsh) - Designed to work with the hyper terminal theme, includes `git` status decorations.
* [hyperzsh](https://github.com/tylerreckart/hyperzsh) - Gives you a comprehensive overview of the branch you're working on and the status of your repository without cluttering your terminal.
* [iGeek](https://github.com/KalebHawkins/ohmyzsh-IGeek-OSX) - Modified iGeek theme. Works with macOS out-of the box, includes `git` status decorations.
* [iamskok](https://github.com/iamskok/iamskok.zsh-theme) - Works well on a dark background.
* [ice](https://github.com/Lenart12/ice.zsh-theme) - Very lightly modified [bureau](https://github.com/isqua/bureau) theme combined with [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme).
* [icicle](https://github.com/JamesConlan96/Icicle) - Includes `git` status decorations, and whether running as root.
* [iggy](https://github.com/eugenk/zsh-prompt-iggy) - A super happy awesome Powerline-style, `git`-aware **prezto only** theme.
* [igorsilva](https://github.com/igor9silva/zsh-theme) - Shows current directory, customizable delimiter, current branch, `git` status.
* [iguanidae](https://github.com/btd1337/iguanidae-zsh-theme) - Includes `git`, `nvm` and `venv` decorations.
* [illuvia-gitster](https://github.com/lopezator/lluvia-gitster) - Fork of [ergenekonyigit/lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) with spacing improvements and an updated icon. Includes `git` status information.
* [imp](https://github.com/igormp/Imp) - Based on [zork](https://github.com/Bash-it/bash-it/wiki/Themes#zork) and optimized for dark backgrounds.
* [infernus](https://github.com/jshiell/infernus-zsh-theme) - Minimalist theme, better on dark backgrounds.
* [infoline](https://github.com/hevi9/infoline-zsh-theme) - Clean theme that shows `git` status, background jobs, remote host, and other information.
* [intheloop-powerline](https://github.com/zyphrus/intheloop-powerline) - An extension of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme to use powerline fonts.
* [itg](https://github.com/itsthatguy/itg.zsh-theme) - itsthatguy's theme.
* [jacobin](https://github.com/Jsharkc/jacobin-zsh-theme) - Based on refined and ys themes, includes `git` status decorations. Includes an optional iterm2 color scheme.
* [jake](https://github.com/JakeHuneau/Jake.zsh-theme) - Shows the time, the current directory, and `git` branch information including the branch name and a red + if the branch has un-pushed changes.
* [jam](https://github.com/jesusangelm/Jam-Zsh-Theme) - Optimized for dark backgrounds, includes `git` status and `rvm` status.
* [jc](https://github.com/jclementex/jc-zsh-theme) - For dark terminal backgrounds, includes `git` status information.
* [jcl](https://github.com/jasonlewis/jcl-zsh-theme) - Loosely based on the ys theme.
* [jerome](https://github.com/jeromescuggs/jerome-theme) - Colorful theme based on the [dieter](https://github.com/jeromescuggs/jerome-theme) theme, but with a yellow hostname. Includes `git` decorations.
* [jhleeeme](https://github.com/JHLeeeMe/JHLeeeMe-Zsh-Theme) - Includes `git` and python virtualenv status decorations, user, pwd,time and system name.
* [jon](https://github.com/Jon-Schneider/jon.zsh-theme) - A simplified [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme) with the colors of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme).
* [jose](https://github.com/tmjoseantonio/shrug-zsh-theme) - Inspired by [beer-theme](https://github.com/tcnksm/oh-my-zsh-beer-theme), includes `git` status.
* [jovial](https://github.com/zthxxx/jovial) - Shows host, user, path, development environment, `git` branch, which python venv is active.
* [jpegleg](https://github.com/jpegleg/zshrc) - Similar to dark blood theme, includes timestamp and `git` decorations.
* [judgedim](https://github.com/judgedim/oh-my-zsh-judgedim-theme) - Minimalist prompt.
* [just-another](https://github.com/supertassu/another-theme) - Just another theme, with hostname when you're sshed to another machine.
* [jwalter](https://github.com/jeffwalter/zsh-jwalter) - Powerline-style theme with `git`, `svn`, `npm`, `rvm` and network awareness. Requires Powerline-compatible terminal font.
* [jyumpp](https://github.com/Jyumpp/jyumpp-zsh-theme) - Configuration file and installer for Powerlevel 10K.
* [kali](https://github.com/h4ck3r0/kali-theme) - Includes `git` decorations.
* [karu](https://github.com/zaari/karu) - Minimalist single line ZSH prompt.
* [keloran](https://github.com/Keloran/keloran.zsh-theme) - Theme that includes a few features from other themes.
* [kenton](https://github.com/notnek/zsh-theme) - Optimized for dark backgrounds, includes `git` status information.
* [kevin](https://github.com/KevinParnell/Kevin-zsh) - Colorful theme, includes iTerm 2 color schemes.
* [kgzsh](https://github.com/Kashugoyal/kgzsh) - Includes `git` status deorations, works well on darker backgrounds.
* [kido](https://github.com/KidoThunder/kido-zsh-theme) - Based on `ys` and `robbyrussell` themes. Includes decorators for the exit code of the last command run, python virtualenv and VCS status.
* [kimwz](https://github.com/kimwz/kimwz-oh-my-zsh-theme) - Minimal theme.
* [kinda-fishy](https://github.com/folixg/kinda-fishy-theme) - Based on Fishy theme, but shows full paths instead of abbreviated directories and only shows user@machine in `ssh` sessions and docker containers.
* [kirkdawson](https://github.com/kdawson133/KirkDawson) - Powerline-inspired. Includes prompt decorations for `git` status, last command exit status, user@hostname, working directory and whether the user is running as root.
* [kiss](https://github.com/rileytwo/kiss) - Simple theme for oh-my-zsh, VSCode, iTerm2, Neovim, and RStudio. Includes `git` status decorations.
* [kketcham](https://github.com/prototype27/kketcham) - Theme with nifty colors on the `git` info.
* [klassiker](https://github.com/mrdotx/zsh-theme) - Very minimal theme with `git` decorations.
* [klendathu](https://github.com/kegonomics/klendathu) - Uses Powerline iconsolas.
* [kote](https://github.com/wendygaoyuan/kote-zsh-theme) - Best for dark backgrounds. Includes `git` status decorations.
* [kotterstep](https://github.com/sorenvonsarvort/kotterstep-zsh-theme) - Two line theme designed for dark terminals, has `git` decorations.
* [krak3n](https://github.com/krak3n/zsh-theme) - Shows golang version and the current `git` branch.
* [kraken](https://github.com/KrakenTheme/kraken-zsh) - A dark theme for ZSH.
* [kube](https://github.com/tigerjz32/kube-zsh-theme) - Based on [macos-terminal](https://github.com/ohmyzsh/ohmyzsh/wiki/External-themes#macos-terminal), includes `kubectl` context. Has time, directory, and `git` status decorations.
* [kumavis](https://github.com/kumavis/kumavis-zsh-theme) - Agnoster fork optimized for solarized terminals. Requires powerline-compatible font.
* [kw](https://github.com/Kwpolska/kw.zsh-theme) - Colorful theme with `git` and `hg` status information, ability to add host-specific colors to hostname.
* [kyuu](https://github.com/arturoalviar/kyuu-zsh-theme) - A simple theme with the first character being 九(kyuu), the number 9. The primary color is blue with a magenta accent. Includes `git` status decorations.
* [lagune](https://github.com/noplay/lagune) - A minimal ZSH theme.
* [lambda (cdimascio)](https://github.com/cdimascio/lambda-zsh-theme) -  Inspired by the robbyrussell [lambda](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lambda.zsh-theme) theme. Includes `git` status decorations.
* [lambda (halfo)](https://github.com/halfo/lambda-mod-zsh-theme/) - A ZSH theme optimized for `git` users who use unicode-compatible fonts and terminal applications.
* [lambda-blazinggit](https://github.com/zalefin/lambda-blazinggit) - Includes blazing fast, detailed `git` information. Requires Nerd Fonts and the [gitstatus](https://github.com/romkatv/gitstatus) plugin.
* [lambda-gitster](https://github.com/ergenekonyigit/lambda-gitster) - Minimalist prompt that includes `git` information.
* [lambda-minimal](https://github.com/sohnryang/lambda-minimal-theme) - Simple theme based on lambda with `git` status and virtualenv information.
* [lambda-mod](https://github.com/halfo/lambda-mod-zsh-theme) - A simple ZSH theme, optimized for `git` usage.
* [lambda-p](https://github.com/paimanbandi/lambda-p) - Inspired by the [lambda mod](https://github.com/halfo/lambda-mod-zsh-theme) and [Lambda V](https://github.com/vkaracic/lambdav-zsh-theme) themes. Includes `git` status decorations.
* [lambda-pure](https://github.com/marszall87/lambda-pure) - A minimal ZSH theme, based on Pure, with added NodeJS version.
* [lambda-v](https://github.com/vkaracic/lambdav-zsh-theme) - A combination of the Lambda and Fishy themes, includes `git` status decorations.
* [lambda-zen](https://github.com/seamile/lambda-zen) - inspired by [lambda mod theme](https://github.com/halfo/lambda-mod-zsh-theme) with graphical `git` status decorations.
* [lambder](https://github.com/avillen/zsh-theme-lambder) - Includes `git` status decorations, works best with a dark terminal theme.
* [lazyprodigy](https://github.com/drewlustro/lazyprodigy-zsh-theme) - Optimized for dark terminals, has variants for local and remote systems.
* [leafia](https://github.com/Ghostrick/leafia-prompt) - Leafy prezto theme that shows `git` status information.
* [lean](https://github.com/miekg/lean) - Inspired by [pure](https://github.com/sindresorhus/pure). Includes `git` status and background job decorations.
* [lemon](https://github.com/carlosvitr/lemon_zsh) - Many beautiful colors for you to enjoy. done with care and patience. Includes `git` status and ruby version decorations.
* [leverage](https://github.com/gschnall/leverage) - Based on [minimal](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/minimal.zsh-theme), uses colors, and an extra `¬` character, to better distinguish the command line prompt from your output.
* [lewis](https://github.com/lewisflude/oh-my-lewis) - Black, white and red theme. Shows `git` status information.
* [lightbulb](https://github.com/lightbulb703/lightbulb-zsh-theme) - Includes decorations for kernel, OS version, uptime and `git`.
* [lighthaus](https://github.com/lighthaus-theme/zsh) - A prompt that compliments the [Lighthaus](https://github.com/lighthaus-theme/lighthaus) theme. Shows `git` information, github/gitlab logo and shows changes as and when they occur.
* [lila](https://github.com/raphaelivan/lila-zsh-theme) - Minimalist theme, best on a dark terminal background.
* [lilith](https://github.com/aknackd/zsh-themes) - Modification of [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme) and [hyperzsh](https://github.com/tylerreckart/hyperzsh).
* [lime](https://github.com/yous/lime) - Simple and easily customizable ZSH theme.
* [limpide](https://github.com/shooteram/limpide) - Modified version of [miloshadzic](https://github.com/ohmyzsh/ohmyzsh/wiki/themes#miloshadzic) theme which displays parent and current directory.
* [linuxer](https://github.com/patrick330602/linuxer) - Inspired by Yaris Alex Gutierrez's [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh), Yad Smood's ys, and the [Bureau](https://github.com/isqua/bureau) theme.
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt with useful information when you need it. It shows you what you need when you need it. You will notice what changes when it changes, saving time and frustration.
* [lish](https://github.com/bashelled/lish) - A casual theme. No roughness, just smooth. Includes `git`, user@host, last command exit status, current directory, current time and root status decorators.
* [llama](https://github.com/PsychoLlama/llama.zsh-theme) - Minimalist theme used by discerning llamas.
* [logico](https://github.com/logico/logico-zsh-theme) - Has `git` decorations. Shows remote status and indicator for vi-mode.
* [lone-star](https://github.com/designfrontier/lonestar-zsh-theme/blob/master/lone-star.zsh-theme) - Texas-themed theme based on Sindre Sorhus' pure theme.
* [longsilvern](https://github.com/long263/longsilvern-zsh-theme) - Includes `git` and compact `pwd` decorations.
* [lorond](https://github.com/lorond/zsh-lorond/) - Compact version of [af-magic](https://github.com/andyfleming/oh-my-zsh/blob/master/themes/af-magic.zsh-theme). Includes `git` status, works with standard fonts.
* [ludwigws](https://github.com/LudwigWS/my-zsh-theme) - Variant of lambda-mod theme. Has `git` decorations, requires a powerline-compatible terminal font.
* [luke](https://github.com/xueguangl23/luke_zsh_theme) - Includes `git` decorations. Based on the [frisk](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/frisk.zsh-theme) oh-my-zsh theme.
* [lukerandall-extended](https://github.com/mpyw/oh-my-zsh-lukerandall-extended) - Extended version of the [lukerandall](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/lukerandall.zsh-theme) theme. Includes decorations for `git` status and the status of the last command run.
* [lunachar](https://github.com/r-mohammadi1/lunachar) - Minimalist theme, includes `git` status decorations.
* [macos](https://github.com/alejandromume/macos-zsh-theme) - Includes `git` status decorations.
* [mad](https://github.com/MartinWie/ohmyzsh-theme-mad) - Includes `git` status decorations.
* [magicmace](https://github.com/zimfw/magicmace) - Inspired by xero's ZSH prompt and [eriner's prompt](https://github.com/zimfw/eriner). Includes status codes for active python `venv`, exit status of last command, shortened working directory, `git` status decorations.
* [magico](https://github.com/IOsonoTAN/magico) - IOsonoTAN's magico theme.
* [maivana](https://github.com/nylo-andry/zsh-themes) - Includes `kubectl` context, `git` status decorations.
* [materialshell](https://github.com/carloscuesta/materialshell) - A [material design](https://material.io/guidelines/style/color.html) theme for your shell with a good contrast and color pops at the important parts. Designed to be easy on the eyes.
* [matrix](https://github.com/pot-code/matrix-zsh-theme) - Variant of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) styled to look like something in the Matrix movie trilogy. Includes `git` status decorations.
* [matter](https://github.com/mrobillard/matter-zsh-theme) - Shows `git` status, AWS vault role, background jobs, exit code of last command & hostname.
* [mau](https://github.com/vichargrave/mau) - A ZSH theme with a cat twist. Includes `git` status decorations. Based on the [kphoen](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kphoen.zsh-theme) and [smt](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/smt.zsh-theme) themes.
* [mbolis](https://github.com/mbolis/mbolis-zsh-theme) - Includes `git` decorations, changes prompt color if root user, active jobs, and [jenv](https://github.com/jenv/jenv) integration.
* [mdmini](https://github.com/MarioDena/MDmini) - Includes `git` and `ssh` status decorations.
* [megaprompt](https://github.com/willghatch/zsh-megaprompt) - A maximalist prompt including keyboard mode, ownership info, and other contextual info, with λ as the prompt character. Requires the [hooks](https://github.com/willghatch/zsh-hooks) plugin.
* [metalmajor](https://github.com/deblauwetom/metalmajor-zsh-theme) - Includes `git` status decorations, shows exit code of last command if nonzero.
* [mexassi](https://github.com/Mexassi/mexassi-zsh-theme) - Checks the `/sys/class/power_supply` folders to determine if the system is installed on a laptop or desktop machine. Reads the battery percentage grepping acpi command and displays it in the prompt. Includes `git` decorations.
* [mh-fzj](https://github.com/mh-firouzjaah/mh-fzj-oh-my-zsh-theme-v1) - Includes `rvm` and `git` status decorations.
* [michaelpass](https://github.com/michaelpass/michaelpass.zsh-theme) - POSIX-friendly cross-platform [alanpeabody](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/alanpeabody.zsh-theme) mod w/ convenient timestamps and full git/ruby support.
* [midin](https://github.com/xlshiz/midin) - Works well on dark terminal background, includes `git` status decorations.
* [mike-was-here](https://github.com/leguim-repo/mike-was-here-theme/issues/1#issuecomment-763040593) - Minimalist, includes `git` status decorations.
* [milight](https://github.com/frodoslaw/milight-zsh) - Minimal ZSH prompt with `git` status display, works best with dark terminal backgrounds.
* [min](https://github.com/andrepolischuk/min) - A minimalistic ZSH prompt.
* [mindful-space](https://github.com/syndbg/mindful-space-zsh-theme) - ZSH theme with space in mind.
* [mini-simple](https://github.com/ysl2/mini-simple-zsh-prompt) - Minimalist. Includes `vcs` status decorations.
* [minima (Brolly0204)](https://github.com/Brolly0204/zsh-minima) - Includes `git`, `node`, `golang`, `yarn`, `php`, `docker` and `python` status decorations.
* [minima (eduardnikolenko)](https://github.com/eduardnikolenko/minima) - A minimal ZSH theme with `git`, `docker`, `go`, `node`, `npm`, `python` and other indicators. Uses unicode characters for some markers.
* [minimal (5amu)](https://github.com/5amu/minimal-prompt) - Minimal prompt, uses nerdfonts. Includes `git` and `vpn` status decorations.
* [minimal (casalinovalerio)](https://github.com/casalinovalerio/minimal-prompt) - Minimal prompt, includes `git` and vpn status decorations.
* [minimal (glsorre)](https://github.com/glsorre/minimal/) - minimal asynchronous ZSH theme optimized for use with the [Fira Code](https://github.com/tonsky/FiraCode) font and the [Solarized Light](https://ethanschoonover.com/solarized) terminal theme.
* [minimal (subnixr)](https://github.com/subnixr/minimal) - Minimal yet feature-rich theme.
* [minimal-improved](https://github.com/gdsrosa/minimal_improved) - Theme for dark terminals, includes `git` decorations in the right-side prompt.
* [minimal2](https://github.com/PatTheMav/minimal2) - A minimal and extensible ZSH theme. Forked from [subnixr's original](https://github.com/subnixr/minimal) and adapted for [Zimfw](https://github.com/zimfw/zimfw).
* [minimalx](https://github.com/lknix/zsh-theme-minimalx) - Inspired by kolo theme from oh-my-zsh.
* [mira](https://github.com/mbStavola/mira) - A modified [bira](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#bira) with time info and a simplified start prompt.
* [miramare](https://github.com/franbach/oh-my-deepin-miramare) - Includes `git` status decorations. Works best with [Deepin Terminal](https://www.deepin.org/en/original/deepin-terminal/).
* [misa](https://github.com/misalabs/misa.zsh-theme) - Misalabs' ZSH theme.
* [mixed](https://github.com/dekermendzhy/mixed-zsh-theme) - Optimized for dark backgrounds.
* [mnml](https://github.com/mnml-theme/prompt) - Minimal theme with `git` status decorations.
* [mochi2](https://github.com/mochidaz/zsh-themes) - Minimalist theme. Includes `git` and `hg` status decorations.
* [mochi](https://github.com/mochidaz/zsh-themes) - Simple theme, designed to resemble rust main function. Includes `git` and `hg` status decorations.
* [moderno](https://github.com/obrassard/moderno-zsh) - A simple and modern ZSH theme inspired by the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme from Oh-My-ZSH. Includes `git` status decorations.
* [modesty](https://github.com/saravanabalagi/zsh-theme-modesty) - A clean and modest zsh theme with `condaenv`, `virtualenv` and `git` status decorations displayed neatly right aligned.
* [molokai-powerline](https://github.com/prikhi/molokai-powerline-zsh) - Based on [agnoster](https://gist.github.com/agnoster/3712874).
* [momoyo](https://github.com/momoyo-droid/momoyo-zsh-theme) - Reminiscent of powerline. Includes decorations for `git` status, username, and working directory.
* [moonline](https://github.com/kagamilove0707/moonline.zsh) - Minimal but easily extensible prompt.
* [moux](https://github.com/gagbo/moux) - Works well with a dark terminal background, includes `git` decorations in `RPROMPT`.
* [multi-shell-repo-prompt](https://github.com/dotcode/multi-shell-repo-prompt) - Provides useful information (in your prompt) about the repository that you are in. It currently works for [Git](https://git-scm.com/) and [Mercurial](https://www.mercurial-scm.org/), under [ZSH](https://en.wikipedia.org/wiki/Zsh) as well as [bash](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29).
* [multiline](https://github.com/jan-auer/zsh-multiline) - Powerline-esque theme based on [agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [muslim](https://github.com/nksoff/muslim) - A simple minimal ZSH prompt theme.
* [musy](https://github.com/THaGKI9/musy-zsh-theme) - Inspured by muse theme. Includes `git` status decorations.
* [my-hl2](https://github.com/liamm91/my-hl2) - Includes virtualenv, `git` status and directory decorations. Based on omz's [half-life](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/half-life.zsh-theme) theme.
* [myzsh](https://github.com/MaxUlysse/myzsh) - Maxime Garcia's myzsh theme.
* [nanofish](https://github.com/tweekmonster/nanofish) - Adds fish-style directory prompt to nanotech theme.
* [narren](https://github.com/narrensingh/zsh-custom-theme-narren) - Includes emojii `git` status decorations, exit status emoji and node version.
* [nbrylevv](https://github.com/nbrylevv/nbrylevv-zsh-theme) - Minimalist theme with text `git` status decorations.
* [nctu](https://github.com/leovincentseles/nctu.zsh-theme) - Lightweight theme with an emphasis on speed. Includes `git` status decorations.
* [neewbie](https://github.com/neewbee/neewbee.zsh-theme) - Minimal theme with `git` decorations. Based on [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell).
* [neon-potato](https://github.com/algosuna/neon-potato) - Colorful and minimalist theme. Includes `git` decorations.
* [neon](https://github.com/sahariko/neon) - A pretty and minimal ZSH theme with `git` decorations.
* [nerdish](https://gitlab.com/nyarla/zsh-theme-nerdish) - A prompt theme for ZSH with Nerd Fonts.
* [nescalante](https://github.com/nescalante/zsh-theme) - Optimized for dark terminal backgrounds, includes `git` decorations.
* [neurosimple](https://github.com/davidsierradz/neurosimple-oh-my-zsh-theme) - Includes `git` decorations and `vi`-mode indicator.
* [newt](https://github.com/softmoth/zsh-prompt-newt) - Fat & fast theme – beautiful inside and out, styled segments done right. Extremely customizable, includes `git`, username, execution time, directory, background jobs and edit mode decorations.
* [newton](https://github.com/sebastienfilion/zsh.newton) - Includes `git` status and external IP address decorations.
* [nextbike](https://github.com/meierjan/nextbike-zsh-theme) - A very basic theme which just features an macOS bike icon.
* [nidoranarion](https://github.com/NicolaiRuckel/nidoranarion) - Colorful, shows `git` status decorations.
* [nikitakot](https://github.com/nikitakot/nikitakot-oh-my-zsh-theme) - Small and simple oh-my-zsh theme. Shows current directory and 2 directories behind, `git` and `nodejs` status decorations.
* [ningxia](https://github.com/wangyandong-ningxia/ningxia.zsh-theme) - Based on af-magic.
* [nknu](https://github.com/aanc/oh-my-zsh-nknu-theme) - A simple oh-my-zsh theme.
* [nmaxcom](https://github.com/nmaxcom/nmaxcom-zsh-theme) - Minimalist ZSH theme with `git` status decorations.
* [node](https://github.com/skuridin/oh-my-zsh-node-theme) - oh-my-zsh's node theme, broken out to make it easier to use with other plugin managers.
* [nodeys](https://github.com/marszall87/nodeys-zsh-theme) - Based on the ys theme, with added NodeJS version (from NVM plugin).
* [noon](https://github.com/silky/noon.zsh-theme) - Has light and dark variants, shows `git` information.
* [nord](https://github.com/TyWR/Nord-zsh) - Includes `git` status decorations and displays the active conda environment.
* [nothing](https://github.com/eendroroy/nothing) - Lightning fast and really simple because it has almost nothing in it.
* [nox](https://github.com/kbrsh/nox) - Dark theme, displays the current working directory and git status.
* [nt9](https://github.com/lenguyenthanh/nt9-oh-my-zsh-theme) - A clean, distraction free and `git` focused development theme. Shows path relative to `git` root (or ~ when outside `git` repo), time since last commit, current SHA, branch and branch state.
* [nunorc](https://github.com/nunorc/nunorc.zsh-theme) - Minimalist theme, works well on dark backgrounds. Includes `git`, `mercurial` and `svn` satus decorations.
* [nuqlezsh](https://github.com/Nuqlear/nuqlezsh.zsh-theme) - A simple theme for prezto and oh-my-zsh.
* [nuts](https://github.com/rafaelsq/nuts.zsh-theme) - Minimalist theme, includes `git` status decorations and time.
* [oblong](https://github.com/Ansimorph/oblong) - Simple `bash`-inspired theme based on [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [basher](https://gitlab.com/Spriithy/basher). Includes status decorations to show if user is root, the exit status of last command run, `git` branch and its clean/dirty status.
* [odin](https://github.com/tylerreckart/odin) - Odin is a `git`-flavored ZSH theme.
* [oh-flowers](https://github.com/Flower7C3/oh-flowers-zsh-theme) - Multiline theme with `git` decorations.
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated prompt for bash and ZSH.
* [oh-my-posh](https://ohmyposh.dev/) - Not ZSH-specific, but very nice and works with ZSH. Allows you to use the same configuration for prompts in all shells.
* [oh-my-via](https://github.com/badouralix/oh-my-via) - Theme for ZSH which mainly forks the historical theme used on VIA servers.
* [ohmypc](https://github.com/joselpadronc/OhMyPC) - Works well with dark terminal windows. Includes `git` decorations.
* [om](https://github.com/sirshikher/zsh-om) - Minimal theme, works with dark backgrounds, includes `git` status decorations.
* [omuse](https://github.com/ouuan/omuse-zsh-theme) - Based on Oh-My-ZSH's [amuse](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/amuse.zsh-theme). Has decorations for `git` status, time, absolute pwd, RAM usage, time used by last command, and last command exit status.
* [owiewestside](https://github.com/owenstranathan/owiewestside.zsh-theme) - Includes `git` status and virtualenv information.
* [oxide](https://github.com/dikiaap/dotfiles/blob/master/.oh-my-zsh/themes/oxide.zsh-theme) - A Minimalistic and Dark ZSH theme.
* [ozono](https://github.com/sfabrizio/ozono-zsh-theme) 🌏 OZ0NO - Let's Breathe a clean ZSH.
* [p9k-theme-pastel](https://github.com/iboyperson/p9k-theme-pastel) - A theme for the [powerlevel10k](https://github.com/romkatv/powerlevel10k) prompt that puts an emphasis on simplcity while still getting important information across.
* [pad](https://github.com/eproxus/pad.zsh-theme) - A concise and colorful oh-my-zsh theme.
* [page](https://github.com/SLIB53/page-zsh-theme) - A simple theme with VCS support. The prompt shows 1 level of the current working directory, branch, and a color coded curved fat arrow.
* [palenight (jenssegers)](https://github.com/jenssegers/palenight.zsh-theme) - Allows display of host information, includes `git` branch decoration.
* [palenight (rhklite)](https://github.com/rhklite/palenight_zsh_theme) - Shows detailed `git` status information with icons in the prompt.
* [panda](https://github.com/davymai/oh-my-zsh-panda-theme) - Includes `git` and `root` status decorations. Best on a dark background.
* [papercolor](https://github.com/erikschreier/PaperColor-themes) - Color scheme for ZSH, `vim` and `tmux`. Includes `git` status decorations.
* [passion](https://github.com/ChesterYue/ohmyzsh-theme-passion) - Includes `git` status decorations, command run time in milliseconds. Requires coreutils on macOS.
* [pastel](https://github.com/iboyperson/pastel) - A ZSH theme inspired by [sugar-free](https://github.com/cbrock/sugar-free). Includes `git` decorations.
* [pentesters](https://github.com/sdcampbell/lpha3cho-Oh-My-Zsh-theme-for-pentesters) - Modified version of the [intheloop](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/intheloop.zsh-theme) theme for pentesters which includes the date, time, and IP address for pentest logging.
* [persi](https://github.com/persiliao/persi-zsh-theme) - Includes `git` decorations. Works with both light and dark backgrounds.
* [phalanx](https://github.com/d-danilov/phalanx-zsh-theme) - Minimal theme in the spirit of the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and Pure Shell themes.
* [phantomk](https://github.com/phantomk/phantomk.zsh-theme) - Colorful theme, includes go version, node version and `git` status.
* [phi φ](https://github.com/LasaleFamine/phi-zsh-theme) - A clean and simple theme for ZSH inspired and forked from the [Lambda (Mod) ZSH](https://github.com/halfo/lambda-mod-zsh-theme) theme.
* [pi](https://github.com/tobyjamesthomas/pi) - A minimalist theme with `git` status decorations.
* [plain-ui](https://github.com/purveshpatel511/plain-ui) - Minimalist, but includes `git` status decorations.
* [plain](https://github.com/jimeh/plain.zsh-theme) - A plain and simple theme for ZSH which shows basic `git` information.
* [planet](https://github.com/borb/planet-zsh) - A slimmed down version of [steef](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) from [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [plankton](https://github.com/tobiaseichert/plankton-zsh-theme) - Simple, no-frills theme.
* [plantyhoe](https://github.com/totoroot/plantyhoe.zsh-theme) - Minimalist theme based on a love of plants and apples. Includes `git` status decorations.
* [platypus](https://github.com/fdv/platypus) - Platypus is a simple and convenient theme for oh-my-zsh used by Frédéric de Villamil.
* [pointer](https://github.com/gpinkard/pointer-zsh-theme) - Shows working directory, the return status of the last command, and `git` current branch.
* [poncho](https://github.com/RainyDayMedia/oh-my-zsh-poncho) - RDM's basic oh-my-zsh custom theme.
* [poor-programmer](https://github.com/vishaltelangre/poor-programmer.zsh-theme) - Programmer's theme with `git` status, ruby version and project path.
* [powerbash](https://github.com/erikschreier/powerbash-zsh) - Works well with dark terminal backgrounds, includes `git` status decorations.
* [powerless](https://github.com/martinrotter/powerless) - Tiny & simple pure ZSH prompt inspired by powerline.
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - A fast reimplementation of [powerlevel9k](https://github.com/bhilburn/powerlevel9k) ZSH theme. Can be used as a drop-in replacement for powerlevel9k, when given the same configuration options it will generate the same prompt, only faster.
* [powerlevel9k](https://github.com/bhilburn/powerlevel9k) - Powerlevel9k is a theme for ZSH which uses [Powerline Fonts](https://github.com/powerline/fonts). It can be used with vanilla ZSH or ZSH frameworks such as [Oh-My-Zsh](https://github.com/ohmyzsh/ohmyzsh), [Prezto](https://github.com/sorin-ionescu/prezto), [Antigen](https://github.com/zsh-users/antigen), and [many others](https://github.com/bhilburn/powerlevel9k/wiki/Install-Instructions).
* [powerlevelHipstersmoothie](https://github.com/hipstersmoothie/PowerlevelHipstersmoothie) - Add-on for [powerlevel9k](https://github.com/bhilburn/powerlevel9k).
* [powerline (brucehsu)](https://github.com/brucehsu/oh-my-zsh-powerline-theme) - A two-line version of powerline: one for information, one for input.
* [powerline (jeremy)](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme) - Another take on a powerline theme. Nicely configurable, but requires at least a 256 color-capable terminal with a powerline-compatible terminal font.
* [powerline (syui)](https://github.com/syui/powerline.zsh) - A `git` aware powerline theme.
* [powerline-cute](https://github.com/dogrocker/oh-my-zsh-powerline-cute-theme) - Based on [bullet-train](https://github.com/caiogondim/bullet-train.zsh).
* [powerline-go](https://github.com/justjanne/powerline-go) - A beautiful and useful low-latency prompt, written in golang. Includes `git` and `hg` status decorations, exit status of the last command run, current Python virtualenv, whether you're in a [nix](https://nixos.org/) shell, and is easy to extend.
* [powerline-hs](https://github.com/rdnetto/powerline-hs) - A [Powerline](https://github.com/powerline/powerline) clone written in Haskell. It is significantly faster than the original implementation, and makes the shell noticeably more responsive.
* [powerline-pills](https://github.com/lucasqueiroz/powerline-pills-zsh) - Created in Ruby, uses powerline characters to simulate pills with useful information.
* [powerline-shell (b-ryan)](https://github.com/b-ryan/powerline-shell) - Beautiful and useful prompt generator for Bash, ZSH, Fish, and tcsh. Includes `git`, `svn`, `fossil` and `hg` decorations, Python virtualenv information, and last command exit status.
* [powerline-shell (banga)](https://github.com/b-ryan/powerline-shell) - A [powerline](https://github.com/Lokaltog/vim-powerline)-like prompt for Bash, ZSH and Fish. Shows important details about git/svn/hg/fossil branch and is easy to customize/extend.
* [powerline-train](https://github.com/sherubthakur/powerline-train) - A powerline variant.
* [powerline](https://github.com/carlcarl/powerline-zsh) - A [Powerline](https://github.com/Lokaltog/vim-powerline)-like prompt, based on [powerline-bash](https://github.com/milkbikis/powerline-bash). Displays virtualenv, `git` status information and the exit code of the last command run.
* [powerzeesh](https://github.com/sevaho/Powerzeesh) - A Powerline based ZSH theme. It aims for simplicity, showing information only when it's relevant, optimized for speed and look. Inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and [Powerline](https://github.com/jeremyFreeAgent/oh-my-zsh-powerline-theme).
* [pre](https://github.com/leandromatos/pre-theme) - A collection of themes for Sublime Text, Terminal, iTerm 2 and ZSH.
* [predawn-shell](https://github.com/jamiewilson/predawn-shell) - Theme optimized for dark terminal themes.
* [prezto-cloud-prompt](https://github.com/klaude/prezto-cloud-prompt) - Prezto port of oh-my-zsh's cloud prompt.
* [prezto-lambda](https://github.com/nixolas1/prezto-lambda) - Lambda theme (for prezto).
* [prezto_powerline](https://github.com/davidjrice/prezto_powerline) - Powerline for prezto. Shows git information, RVM version.
* [probe](https://github.com/probe2k/probe_zsh) - Includes `git` status decorations.
* [prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - A fairly heavyweight ZSH prompt, based on the powerline font from the popular eponymous `vim` plugin, which works well for a dark background.
* [prompt_j2](https://github.com/malinoskj2/prompt_j2) - Has a dynamic exit status indicator, can change to two lines dynamically to display context.
* [ps1.py](https://github.com/jwodder/ps1.py) - Has `git` status, truncated directory, `chroot` and `virtualenv` prompt decorations.
* [punctual](https://github.com/dannynimmo/punctual-zsh-theme) - Easily customizable, influenced by [spaceship](https://github.com/denysdovhan/spaceship-prompt).
* [pure-agnoster](https://github.com/yourfin/pure-agnoster) - Mashup of pure and agnoster. Has `git` decorations and works well with both dark and light terminal backgrounds.
* [pure](https://github.com/sindresorhus/pure) - A pretty, minimal and fast ZSH prompt. Includes `git` status decorations, prompt turns red if last command failed, username and host decorations when in a remote session or container, and current folder and command when a process is running.
* [purify (banminkyoz)](https://github.com/banminkyoz/purify) - A simple, fast & cool prompt.
* [purify (kyoz)](https://github.com/kyoz/purify) - A clean and vibrant theme, best on dark backgrounds. Includes `git` status decorations.
* [purity](https://github.com/petermbenjamin/purity) - Inspired by robbyrussell theme and the [pure](https://github.com/sindresorhus/pure) prompt.
* [purs](https://github.com/xcambar/purs) - A fast [pure](https://github.com/sindresorhus/pure)-inspired prompt written in [Rust](https://www.rust-lang.org/).
* [pustelto](https://github.com/Pustelto/shell_theme) - Colorful theme inspired by the [Spaceship](https://github.com/denysdovhan/spaceship-prompt) theme, includes `git` decorations.
* [qi3ber2](https://github.com/nichus/qi3ber2) - A dark multiline theme. Includes `git`, load average and exit code of last command decorators.
* [qoomon](https://github.com/qoomon/zsh-theme-qoomon) - Optimized for dark backgrounds, includes `git` information. Theme repo includes iTerm 2 and Terminal color settings.
* [quewui](https://github.com/kauefontes/oh-my-quewui) - Simple and clean theme optimized for dark terminal themes. Includes status decorations for the current time, user, directory and `git` status.
* [r3nic1e](https://github.com/r3nic1e/r3nic1e) - [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) variant with battery status, `git/hg` status, time, kubernetes context and namespace, non-zero exit code of last command and date decorations. Requires Powerline font.
* [racotecnic](https://github.com/elboletaire/zsh-theme-racotecnic) - Based on af-magic and posh-git.
* [radium](https://github.com/dimitardimitrov/radium) - Designed for dark terminals, (works best with [Solarized](https://github.com/altercation/solarized) iTerm 2 theme) (prezto).
* [rafiki](https://github.com/akabiru/rafiki-zsh) - Adds emojis to your ZSH terminal.
* [ramiel](https://github.com/aknackd/zsh-themes) - Fork of the [node](https://github.com/skuridin/oh-my-zsh-node-theme).
* [random-emoji-robbyrussell](https://github.com/parwat08/random-emoji-robbyrussell) - Based on [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) and `robbyrussell` themes.
* [random-emoji](https://gist.github.com/oshybystyi/2c30543cd48b2c9ecab0) - Random emoji.
* [raspberrysh](https://github.com/MaxMalinowski/raspberrysh) - Includes `git`, python, time, current host and path decorations.
* [raytek](https://github.com/Raytek/raytek-zsh-theme) - Simple and colorful theme with `git` status decorations.
* [raz](https://github.com/razman786/ohmyzsh-theme-raz) - Minimal prompt, includes `git` status decorations.
* [rb](https://github.com/rberenguel/rb-zsh-theme) - Powerline-styled ZSH theme based on [Agnoster](https://gist.github.com/agnoster/3712874), optimized for `git` and solarized terminals. Requires a Powerline-compatible font.
* [rbjorklin](https://github.com/rbjorklin/rbjorklin-zsh-theme) - Optimized for solarized terminal color schemes, includes `git` status decorations.
* [redline](https://github.com/DrissTM/redline.zsh-theme) - Minimalist theme. Includes `git` status, time, user.
* [reggae](https://github.com/nmercado1986/zsh-reggae-theme) - Compresses a lot of information into the prompt with color-coded status decorations.
* [rei](https://github.com/arturoalviar/rei-zsh-theme) - A simple theme with the first character being 零(rei), the number 0. Includes `git` status decorations.
* [remiii](https://github.com/Remiii/remiii.zsh-theme) - Based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), optimized for [solarized](https://github.com/altercation/solarized) terminal themes.
* [remolueoend](https://github.com/remolueoend/remolueoend.zsh-theme) - Prezto ZSH theme based on Sorin, using emojis for tracking GIT context.
* [rho](https://github.com/andrejreznik/rho-zsh-theme) - Minimalist theme.
* [river](https://github.com/revir/river-zsh-config) - Dark theme with `git` information.
* [robbyolivier](https://github.com/YuyeQingshan/robbyolivier) - Based on ideas from the the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme and the project [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt).
* [robbyrussell-WIP](https://github.com/ecbrodie/robbyrussell-WIP-theme) - Decorates the `robbyrussell` theme with output to indicate a **WIP** commit.
* [robbyrussell-fullpath](https://github.com/toytag/robbyrussell-fullpath.zsh-theme) - The original [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) with a fullpath in the prompt.
* [rocket](https://github.com/Alexandresl/rocket-zsh-theme) - Minimalist theme, includes `git` and `hg` status decoration.
* [rougarou](https://github.com/RougarouTheme/rougarou-zsh) - A dark theme.
* [roundy](https://github.com/nullxception/roundy) - fast, cute and roundy theme. Includes `git` decorations. Requires nerd fonts and a unicode-capable terminal application.
* [roz](https://github.com/rozNum/roz-zsh-theme) - Minimalist. Includes `git` status decorations, best on a darker background.
* [rs](https://github.com/rogeliosamuel621/rs-zsh-theme) - Includes `git` decorations. Requires unicode capable terminal.
* [rufus](https://github.com/runarsf/rufus-zsh-theme) - Optimized for dark backgrounds.
* [rummik](https://github.com/rummik/zsh-theme) - @rummik's theme. Supports [psmin](https://gitlab.com/zick.kim/zsh/zsh-psmin), and `git` status information in the prompt.
* [russtone](https://github.com/russtone/prompt-russtone) - Inspired by [pure](https://github.com/sindresorhus/pure) and [sorin](https://github.com/sorin-ionescu/prezto). Includes `git` status decorations.
* [ryner](https://github.com/DoctorRyner/ryner-zsh-theme) - Colorful theme, includes `git` decorations and the current directory.
* [rzh](https://github.com/patwhatev/rzh) - Theme with git states indicated by emojis.
* [s1ck94](https://github.com/zimfw/s1ck94) - Fork of the (first deprecated, now extinct) minimal prompt by S1cK94. Shows whether user is root, background job status, vi-mode, exit status of last command, and `git` status decorations.
* [s7c](https://github.com/Samega7Cattac/s7c.zsh-theme) - Works well with dark backgrounds. Includes `git` status decorations.
* [samshell](https://github.com/samuelb/samshell) - A minimalist zsh theme with `git`, kubernetes and python virtualenv decorations.
* [saraiva](https://github.com/ruisaraiva19/saraiva-theme) - Includes `git` status decorations, works well on a dark terminal background.
* [saturn](https://github.com/gantoreno/saturn-prompt) - A soft & minimalistic prompt for those who love space and want to have a bit of it on their terminal, featuring cool emojis & highly customizable prompt elements (such as icons, colors, time format, and more).
* [schminitz-v2](https://github.com/mashdots/schminitz-v2) - Shows `git` status decorations, user@host information, the exit status of last command, and whether running as root.
* [schminitz](https://gist.github.com/schminitz/9931af23bbb59e772eec) - Shows if `vim` is running in the background when using `:sh` command.
* [sdkman](https://github.com/matthieusb/zsh-sdkman) - Add tab completions for [sdkman](https://sdkman.io/).
* [seashell](https://github.com/jottenlips/seasonal-zshthemes) - Minimal theme with sea-inspired emoji decorations. Includes `git` status decorations.
* [seeker](https://github.com/tonyseek/oh-my-zsh-seeker-theme) - This theme uses many special unicode characters to be fancy, but it may cause some problems without well supported fonts.
* [seltzer](https://github.com/GrantSeltzer/seltzer.zsh-theme) - Inspired by the dieter theme, uses color-coding to provide information.
* [senpai](https://github.com/hiroru/senpai-zsh) - Clean prompt theme for Devops. Includes `git` status information, the kubernetes context, AWS profile, GCP project and Azure active cloud.
* [seppuku](https://github.com/Helianthella/seppuku) - Clean and minimal theme inspired by [cloud](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/cloud.zsh-theme).
* [sepshell](https://github.com/sepehr/sepshell) - Clean and minimal ZSH theme based on the old lost taybalt theme, with `git` bisecting/merging/rebasing modes and configurable prompt symbols.
* [serious](https://github.com/oliversandli/serious-zsh-theme) - Includes command exit status and `git` status decorations.
* [seti_UX](https://github.com/ginfuru/iTerm-Seti_UX) - A simple omz-compatible theme with a corresponding iTerm 2 color scheme.
* [sfz](https://github.com/mreinhardt/sfz-prompt.zsh) - An evolution of lean prompt which itself is a rewrite of pure.
* [shadow](https://github.com/agentshadow/shadow-zsh-theme) - Includes `git` status, directory, host name, username and time decorations.
* [shayan](https://github.com/shayanh/shayan-zsh-theme) - Simple theme with `git` status decorations.
* [shellder](https://github.com/simnalamburt/shellder) - Minimal theme with git branch display. Requires a Powerline-compatible font.
* [shichi](https://github.com/arturoalviar/shichi-zsh-theme) - A simple theme with the first character being 七(shichi/nana), the number 7. The primary color is red with a yellow accent. Includes `git` status decorations.
* [shini](https://github.com/bashelled/shini) - A tiny theme that just shouts out small. Includes directory, username, hostname, time and `git` decorations.
* [shirnschall](https://github.com/shirnschall/shirnschall-zsh-theme) - Includes `git` status and `user@hostname` decorations.
* [shocm](https://github.com/ericvanjohnson/shocm-zsh-themes) - Forked from [sixlive](https://github.com/sixlive/sixlive-zsh-theme). Has `git` decorations.
* [short-ys](https://github.com/OREOmini/short-ys-zsh-theme) - Based on the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme. Includes `git` and `hg` status decorations.
* [shprompt](https://github.com/duongdominhchau/shprompt) - Prompt written in Rust. Includes `git` status decorations.
* [shrikant](https://github.com/shr1k4nt/shrikant_zsh_theme) - Includes `git` decorations.
* [shrug](https://github.com/tmjoseantonio/shrug-zsh-theme) - Simple theme which displays current directory and git information.
* [shtr0m](https://github.com/kyle-pollock/shtr0m) - Includes `git` status decorations.
* [siegerts](https://github.com/siegerts/zsh-theme) - Includes `git` status decorations in right prompt.
* [silver](https://github.com/reujab/silver) - A cross-shell customizable powerline-like prompt heavily inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme). A faster rust port of [bronze](https://github.com/reujab/bronze). Requires [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts). Very configurable, includes `git` status decorations.
* [simpalt](https://github.com/m-lima/simpalt) - An information-rich small-footprint theme for ZSH based on [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).
* [simple (pavdmyt)](https://github.com/pavdmyt/simple-oh-my-zsh-theme) - Minimalist theme based on [robbyrussel](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes#robbyrussell) that embeds `git` status information in iTerm's window title bar instead of using space in the prompt.
* [simple (savecoders)](https://github.com/Savecoders/simpleTheme-zsh-theme) - Simple and minimalist theme with `git`, `username` and execution status decorations.
* [simple (yhiraki)](https://github.com/yhiraki/zsh-simple-prompt) - Minimal prompt, doesn't require special fonts.
* [simple-agnoster](https://github.com/iwat/simple-agnoster.zsh-theme) - Powerline-inspired simple theme with `git` decorations.
* [simple-git](https://github.com/BazaJayGee66/simple-git-theme) - Minimalist theme inspired by [gitstatus](https://github.com/kimyvgy/gitstatus-zsh-theme). Includes `git` decorations.
* [simple-yet-beautiful](https://github.com/mathiasmoeller/simple-yet-beautiful-zsh-theme) - Minimalist theme. Includes `git` status and `user@host` prompt decorations.
* [simplezsh](https://github.com/fr0zn/simplezsh) - Minimal theme with `git` info display.
* [sinon](https://github.com/k-kinzal/oh-my-zsh-sinon-theme) - k-kinzal's sinon theme. Includes `git` status decorations.
* [sit](https://github.com/svensen/sit.zsh-theme) - Minimalist theme with `git`, command exit status and path decorations.
* [sixlive](https://github.com/sixlive/sixlive-zsh-theme) - This theme has a unique directory listing. When inside a `git` project, the directory display is scoped to the current repository root.
* [sk9](https://github.com/skeiter9/sk9-zsh) - Skeiter9's ZSH theme.
* [skeletor-syntax](https://github.com/ramonmcros/skeletor-syntax) - Theme collection for Atom, Prism and ZSH inspired by Skeletor from He-Man and the Masters of the Universe.
* [skill](https://github.com/frontendmonster/oh-my-zsh-skill-theme) - Optimized for a dark terminal, displays `git` status decorations.
* [sleeplessmind](https://github.com/godbout/sleeplessmind-zsh-theme) - ZSH theme inspired by [gitster](https://github.com/shashankmehta/dotfiles/blob/master/thesetup/zsh/.oh-my-zsh/custom/themes/gitster.zsh-theme) and [odin](https://github.com/tylerreckart/odin).
* [slick](https://github.com/nbari/slick) - Inspired by the [pure](https://github.com/sindresorhus/pure), [purs](https://github.com/xcambar/purs) and [zsh-efgit-prompt](https://github.com/ericfreese/zsh-efgit-prompt). Requires `cargo` for installation.
* [slimline](https://github.com/mengelbrecht/slimline) - Minimal, fast and elegant ZSH prompt. Displays the right information at the right time.
* [sm](https://github.com/blyndusk/sm-theme) A **Simplist** & **Minimalist** theme for your **favorite** terminal. Includes `git` status decorations.
* [small-terminal-diy](https://github.com/Sokkam/small-terminal-diy-theme) - A variant of the [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme) theme in [oh-my-zsh](https://github.com/ohmyzsh/ohmyzsh).
* [smiley](https://github.com/gsamokovarov/smiley.zsh-theme) - A prompt with happy and sad faces.
* [sobole](https://github.com/sobolevn/sobole-zsh-theme) - A minimalistic ZSH theme inspired by the old-fashioned hobbies. No verbose gimmicks, no emoji, no fidget spinners, and no other visual noise. Has both light and dark modes.
* [solarized-powerline (KuoE0)](https://github.com/KuoE0/oh-my-zsh-solarized-powerline-theme) - Solarized powerline variant.
* [solarized-powerline (houjunchen)](https://github.com/houjunchen/solarized-powerline) - Solarized powerline-style theme for ZSH.
* [solarizsh](https://github.com/paddykontschak/Solarizsh) - Color fix for robbyrussell's oh-my-zsh theme to work with [solarized](https://github.com/altercation/solarized) terminals.
* [spaceship](https://github.com/denysdovhan/spaceship-prompt) - Theme with `git`, `nvm`, rvm/rbenv/chruby, python, `ssh` and other useful status indicators.
* [spowerline](https://mbauhardt.github.io/spowerline/) - Written in scala, inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), [tmux](https://tmux.github.io) powerline, vim powerline and the vim status plugin.
* [squanchy](https://github.com/gabrielecanepa/zsh-custom/tree/master/themes) - Minimalist theme. Includes `git`, `node` and `rbenv` status decorations.
* [staples](https://github.com/dersam/staples) - Based on bureau, displays user@host if connected through SSH.
* [starboy](https://github.com/prdpx7/Starboy) - A simple ZSH theme.
* [starship](https://github.com/starship/starship) - Minimal, fast, extremely customizable.
* [statusline](https://github.com/el1t/statusline) - A responsive ZSH theme that provides informational segments when you need them.
* [steef (danihodovic)](https://github.com/danihodovic/steeef) - ZSH steeef theme as a standalone repository. The purpose behind this repo is avoid having a dependency on oh-my-zsh when using the steeef theme. ZSH plugin managers such as Antibody can use the theme without having to use oh-my-zsh.
* [steef (zimfw)](https://github.com/zimfw/steeef) - A customizable version of [steeef's](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/steeef.zsh-theme) theme.
* [stellachar](https://github.com/r-mohammadi1/stellachar) - Minimal, pastels.
* [sublime](https://github.com/pjmp/sublime) - A sublime, clean, minimalistic ZSH theme with `git` status decorations.
* [sugar-free](https://github.com/cbrock/sugar-free) - Based on the [Pure](https://github.com/sindresorhus/pure) and [Candy](https://github.com/BinaryMuse/oh-my-zsh/blob/binarymuse/themes/candy.zsh-theme) themes.
* [sukeesh](https://github.com/sukeesh/sukeesh-zsh-theme) - Includes `git` status decorations. Works better on dark terminal backgrounds.
* [sulfurium](https://github.com/Sulfurium/zsh-theme) - The official ZSH theme of sulfuriumOS.
* [sunrise-ruby](https://github.com/ston1x/sunrise-ruby) - Similar to [sunrise](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/sunrise.zsh-theme) but includes the active Ruby version.
* [superkolo](https://github.com/Minipada/superkolo) - Add date and return status to the [kolo](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/kolo.zsh-theme) theme.
* [susi](https://github.com/carcruz/susi-zsh-iterm) - Includes `git` status decorations and an accompanying iTerm2 color scheme.
* [sy](https://github.com/ttttmr/sy-zsh-theme) - Based on [ys](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/ys.zsh-theme), includes `git` status decorations.
* [t2er](https://github.com/t2er/t2er-zsh-theme) - Minimalist theme with `git` decorations.
* [tabaf](https://github.com/bvc3at/tabaf-zsh-theme) - Minimal ZSH theme optimized for dark backgrounds.
* [tepig-ys](https://github.com/thingerpig/tepig-ys.zsh-theme) - Includes `git` status decorations and conda/virtualenv status.
* [termux](https://github.com/rooted-cyber/Termux-zsh-theme) - Minimalist theme.
* [termuxer](https://github.com/patrick330602/termuxer) - Theme inspired by [Agnoster](https://github.com/agnoster/agnoster-zsh-theme) and linuxer.
* [the-time-lord](https://github.com/jhwhite/the-time-lord) - A theme based on [gallifrey](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gallifrey.zsh-theme).
* [theme-line](https://github.com/yw9381/oh-my-zsh_theme_line) - Colorful theme with `git` status.
* [theta-async](https://github.com/jesec/zsh_theme_theta-async) - Async version of [theta](https://github.com/eendroroy/theta). Includes vcs status information.
* [theta](https://github.com/eendroroy/theta) - Includes `git` and `hg` status decorations. Also has java, python, ruby, node, go and elixir version information.
* [theto](https://github.com/heyvito/theto-zsh-theme) - Simplistic theme.  Needs [Nerd Fonts](https://nerdfonts.com/), includes `vi`-mode status and `git` decorations.
* [thetraveler](https://github.com/bassopenguin/thetraveler) - Inspired by theunraveler, uses symbols to display `git` status.
* [thnikk](https://github.com/thnikk/zsh-theme-thnikk) - A minimal version of the [spaceship](https://github.com/denysdovhan/spaceship-prompt) theme.
* [thyme (chenhao-ye)](https://github.com/chenhao-ye/thyme) - Based on [bira](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bira.zsh-theme), [gnzh](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/gnzh.zsh-theme), and [bullet-train](https://github.com/caiogondim/bullet-train.zsh/blob/master/bullet-train.zsh-theme).
* [thyme (kawamurakazushi)](https://github.com/kawamurakazushi/thyme) - Simple theme with `git` status decorations.
* [tonni4](https://github.com/AndreyPuzanov/tonni4-zsh-theme) - Includes time and `git` status decorators.
* [topan](https://github.com/fudyartanto/topan-theme-oh-my-zsh) - Includes `git` information; best on dark backgrounds.
* [tq](https://github.com/kitian616/tq-zsh-theme) - Displays `git` status, time, requires a Powerline font.
* [traffic](https://github.com/fcce/traffic-zsh-theme) - A dark theme for ZSH.
* [trajan](https://github.com/denisinla/trajan-zsh-theme) - A dark theme for ZSH.
* [trinity](https://github.com/de-luca/Trinity) - A simple theme based on [geometry](https://github.com/geometry-zsh/geometry). Includes `git` decorations.
* [tron](https://github.com/iDoTron/tron-zsh-theme) - Includes `git` status, working directory, time, user@host and return status of last command decorations.
* [tsotra](https://github.com/nylo-andry/zsh-themes) - Minimalist theme, includes `git` status decorations, k8s context, and `rvm` status.
* [turs](https://github.com/eikendev/turs) - Fast, minimal [Purs](https://github.com/xcambar/purs)-inspired prompt.
* [tvline](https://github.com/thvitt/tvline) - Derived from the [agnoster](https://gist.github.com/agnoster/3712874) theme, adds powerline font enhancements.
* [type0](https://github.com/MikereDD/type0_zsh-theme) - Inspired by [classyTouch](https://github.com/yarisgutierrez/classyTouch_oh-my-zsh) by yarisgutierrez. Includes `git` decorations.
* [typewritten](https://github.com/reobin/typewritten) - Minimal and informative theme that leaves room for what's important. Does asynchronous `git` decoration updates for speed.
* [ubunly](https://github.com/alejandromume/ubunly-zsh-theme) - Mimics the Kali Linux console. Note - this theme also rebinds a lot of keys and sets a bunch of ZSH options that themes should leave alone.
* [ubuntu-ish](https://github.com/Thesola10/zsh-ubuntu-ish) - Mimics the default Debian/Ubuntu `bash` prompt.
* [ubuntu-with-vitamins](https://github.com/ureesoriano/zsh-ubuntu-with-vitamins-zim-theme) - Mimics the default Ubuntu prompt, but with `git` decorations.
* [ubuntu](https://github.com/janstuemmel/zsh-ubuntu-theme) - Minimal theme, includes `git` status decorations.
* [ultimate](https://github.com/b4b4r07/ultimate) - Minimalist theme with `git` indicator, vim mode indicator and shortened path.
* [unicorn](https://github.com/juliuscaesar/unicorn) - Inspired by the [Wild Cherry](https://github.com/mashaal/wild-cherry) theme. Has emoji `git` status decorations.
* [unit-1](https://github.com/nerdbude/Unit-1) - Minimalist theme with ITWTB colors.
* [vanan](https://github.com/avano/vanan-zsh-theme) - Minimalist theme with `git` information for dark terminals.
* [vercel](https://github.com/vercel/zsh-theme) - Minimalist theme with `git` status decorations.
* [vertepommes](https://github.com/TheRojam/vertepommes-theme) - Based on ys. Includes vcs status, username and current directory decorations.
* [vinhnx](https://github.com/vinhnx/vinhnx.zsh-theme) - Modified from themes/mgutz.zsh-theme.Looks great when using with a [Solarized](https://github.com/altercation/solarized) color scheme.
* [vitesse](https://github.com/rafaeldellaquila/zsh-vitesse-theme/blob/master/img/preview.png) - Inspired by VS Code's [Vitesse](https://github.com/antfu/vscode-theme-vitesse) theme. Includes `git` status decorations.
* [vulcan](https://github.com/Bruceboy/vulcan-zsh-theme) - Minimal theme reminiscent of the default `bash` theme. Includes `git` decorations.
* [wade](https://github.com/wadehammes/wade.zsh-theme) - Mashup of the popular ZSH themes [Agnoster](https://gist.github.com/agnoster/3712874) and [Fishy](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/fishy.zsh-theme), with some visual tweaks.
* [wang-iterm](https://github.com/0532/wang-iterm-zsh) - Based on the 0532 theme.
* [whale](https://github.com/whalesea520/whale-zsh-theme) - Fast reimplementation of the whale theme.
* [whales](https://github.com/lbergelson/zsh_whales_theme) - Includes decorators for `git` status, java version, last command return status, and directory.
* [wild-cherry](https://github.com/mashaal/wild-cherry) - A fairy-tale inspired theme for ZSH, iTerm 2, Sublime, Atom, & Mou.
* [work-line](https://github.com/afnizarnur/work-line) - Theme with nice emojis.
* [workbench](https://github.com/u8slvn/oh-my-zsh-workbench-theme) - Includes `git` status decorations, working directory, exit status of last command and current `virtualenv`.
* [wynwyn](https://github.com/thaffenden/wynwyn.zsh-theme) - A theme that aims to show you the information you need when you need it. `wynwyn` takes inspiration from the default theme `avit` and the excellent [Spaceship prompt](https://github.com/denysdovhan/spaceship-prompt).
* [xlk-simple](https://github.com/xuelingkang/xlk-simple-zsh-theme) - Simple theme with `git` decorations.
* [xm](https://github.com/Shiaoming/xm) - Theme for dark terminals. Has `git` decorations.
* [xor](https://github.com/xor3n/xor-zsh-theme) - Self described as minimalistic and 'feature-poor', includes `git` decorations.
* [xremix](https://github.com/xremix/oh-my-zsh-xremix-theme) - An oh-my-zsh shell theme based on the Jreese theme plugin.
* [xris47](https://github.com/ivan-ristovic/xris47.zsh-theme) - Fast, simple and streamlined theme. Works best with [tmux](https://github.com/tmux/tmux/wiki) and [vim-airline](https://github.com/vim-airline/vim-airline).
* [xxf](https://gist.github.com/xfanwu/18fd7c24360c68bab884) - Shows the current git commit's shortened hash and message.
* [yairshefi](https://github.com/yaireclipse/yairshefi-ohmyzsh-theme) - Minimal theme with line separated prompts. Based on the [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) theme.
* [yazpt](https://github.com/jakshin/yazpt) - A clean, fast, good-looking ZSH prompt theme that thoughtfully incorporates Git/Subversion/TFVC status info, integrates with popular plugin managers like Oh My Zsh, and is straightforward to customize and extend.
* [yechen](https://github.com/liyechen/yechen.zsh-theme) - Minimalist theme with `git` status decorations.
* [yeet](https://github.com/jeetelongname/Yeet-theme) - Minimalist prompt with `git` status decorations.
* [ykmam](https://github.com/julienvanderkluft/ykmam-zsh-theme/blob/master/ykmam.zsh-theme) - Modified from [ys](https://github.com/cristiancavalli/ys-zsh-custom-theme) theme and optimized for a dark background.
* [ys (cristiancavalli)](https://github.com/cristiancavalli/ys-zsh-custom-theme) - Clean, simple, compatible and meaningful theme meant for dark backgrounds.
* [ys (tinyRatP)](https://github.com/tinyRatP/ys) - Variant of [ys](https://gist.github.com/ysmood/6110461).
* [ys-cluster](https://github.com/AndiH/oh-my-zsh-ys-cluster-theme) - [ys](http://ysmood.org/my-ys-terminal-theme/) variant with support for working with batch submission systems for large clusters. Supports Slurm, LSF / IBM Spectrum LSF, and PBS.
* [ysm](https://github.com/hanbinpro/ysm-zsh-theme) - Simple ZSH theme with `git` status information.
* [ysr](https://github.com/raykle/ysr-zsh-theme) - Based on [ys](http://blog.ysmood.org/my-ys-terminal-theme/). Includes `git` status decoration.
* [yuki](https://github.com/yuki-torii/yuki-zsh-theme) - A dark optimized ZSH theme.
* [yyl-ys](https://github.com/yunyuliu/yyl-ys.zsh-theme) - Includes conda and venv status.
* [yz50](https://github.com/lacanlale/yz50-zsh) - Colorful, based off of [robbyrussell](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/robbyrussell.zsh-theme) and [crunch](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/crunch.zsh-theme) themes. Includes `git` status decorations.
* [z4rr3t](https://github.com/inimicus/z4rr3t) - Based on sindresorhus' [pure](https://github.com/sindresorhus/pure) theme.
* [zelda](https://github.com/SuperKnerdBros/zelda.zsh-theme) Zelda-inspired theme. Includes `git` status decorations.
* [zemm-blinks](https://github.com/aranasaurus/zemm-blinks.zsh-theme) - Customized version of oh-my-zsh [blinks](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/blinks.zsh-theme) with mercurial support and other changes.
* [zemoji](https://github.com/therzka/zemoji) - Based on [wild-cherry](https://github.com/unixorn/awesome-zsh-plugins/blob/master/ https://github.com/mashaal/wild-cherry/tree/master/zsh). Includes exit status, `virtualenv`, `nvm`, `rvm` and `git` status decorations.
* [zero](https://github.com/arlimus/zero.zsh) - Zero's theme & plugin. Has variants for both light and dark terminal backgrounds.
* [zeroastro](https://github.com/zeroastro/zeroastro-zsh-theme) - Works best on dark backgrounds, includes `git` status decorations.
* [zerocake](https://github.com/ZeroPoke/ZeroCake.zsh-theme) - Works better on dark brackgrounds.
* [zeta](https://github.com/skylerlee/zeta-zsh-theme) - Shows username, `git` status information, machine name, the current working directory and success/fail status of last command.
* [zinc](https://gitlab.com/robobenklein/zinc) - A blazing-fast, pure ZSH, mixed asynchronous powerline prompt that's easily extensible and extremely configurable.
* [zlambda](https://github.com/wdhg/zlambda) - Minimalist, includes `git` decorations without special font requirements.
* [zqt](https://github.com/ladychili/zqt-zsh-theme) - Modified version of oh-my-zsh's [maran](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/maran.zsh-theme) theme.
* [zsh1999](https://github.com/DTan13/zsh1999) - Includes network connectivity, battery and `git` status decorations.
* [zsh2000](https://github.com/inspectahstack/zsh2000) - Powerline looking ZSH theme which includes the `rvm` prompt, `git` status and branch, current time, user, hostname, pwd, exit status, whether running as root and background job status.
* [zsh313](https://github.com/amirali313/zsh313-theme) - Minimal theme with `git` status decorations.
* [zshcomrade](https://github.com/landongn/zshcomrade) - A ZSH theme, comrade!
* [zshpower](https://github.com/snakypy/zshpower) - Optimized for python developers. Includes `git` and `pyenv` status decorations, username and host. Tries to install other plugins and fonts, so read its instructions before installing.
* [zshred](https://github.com/redxtech/zshred) - Shows current directory, `git` decorations, exit status of last command and time.
* [zwsh](https://github.com/naens/zwsh) - A Zpm3/Wordstar mode/theme for ZSH.
* [zys](https://github.com/ZYSzys/zys-zsh-theme) - Similar to [Agnoster](https://github.com/agnoster/agnoster-zsh-theme), designed to disclose information contextually, with a powerline aesthetic.
* [zzshell](https://github.com/thezzisu/zzshell) - Inspired by the default [Oh-My-Zsh](http://ohmyz.sh/) theme. Displays exit code and `git` status decorations. Doesn't require Powerline fonts.

## Fonts

Some of the themes listed here require Powerline-compatible fonts, here are a few:

* [Awesome Terminal Fonts](https://github.com/gabrielelana/awesome-terminal-fonts) - A family of fonts that includes some nice monospaced Icons.
* [Fantasque Awesome Font](https://github.com/ztomer/fantasque_awesome_powerline) - A nice monospaced font, patched with Font-Awesome, Octoicons and Powerline-Glyphs.
* [Fantasque-sans](https://github.com/belluzj/fantasque-sans) - Another Powerline-compatible font.
* [Hack](https://sourcefoundry.org/hack/) - Another Powerline-compatible font designed specifically for source code.
* [Input Mono](http://input.fontbureau.com/) - A family of fonts designed specifically for code. It offers both monospaced and proportional fonts and includes powerline glyphs.
* [Iosevka](https://github.com/be5invis/Iosevka) - Coders’ typeface, built from code. Highly customizable.
* [Monoid](https://larsenwork.com/monoid/) - Monoid is customizable and optimized for coding with bitmap-like sharpness at 15px line-height even on low res displays.
* [Nerd Fonts](https://github.com/ryanoasis/nerd-fonts) - Collection of over 20 patched fonts (over 2,000 variations) & FontForge font patcher python script for Powerline, Font Awesome, Octicons, Devicons, and Vim Devicons. Includes: Droid Sans, Meslo, Source Code, AnonymousPro, Hack, ProFont, Inconsolata, and many more.
* [Powerline patched font collection](https://github.com/powerline/fonts) - A collection of a dozen or so fonts patched to include powerline gylphs.
* [Terminus](http://files.ax86.net/terminus-ttf/) - TTF version of Terminus that includes powerline glyphs.

## Installation

### [Antigen](https://github.com/zsh-users/antigen)

Most of these plugins can be installed by adding `antigen bundle githubuser/reponame` to your .zshrc file. Antigen will handle cloning the plugin for you automatically the next time you start `zsh`. You can also add the plugin to a running ZSH with `antigen bundle githubuser/reponame` for testing before adding it to your `.zshrc`.

### [dotzsh](https://github.com/dotphiles/dotzsh)

1. Clone new plugins into `.zsh.local/modules`
2. Load the plugin module in `.zshrc`
3. Open a new ZSH terminal window or tab

### [Oh-My-Zsh](http://ohmyz.sh/)

1. `cd ~/.oh-my-zsh/custom/plugins`
2. `git clone repo`
3. Add the repo to your plugin list

### [Prezto](https://github.com/sorin-ionescu/prezto)

1. Clone the plugin into your prezto modules directory
2. Add the plugin to your `.zpreztorc` file
3. Open a new terminal window or tab

### [Zgen](https://github.com/tarjoilija/zgen)

Zgen is not being actively maintained. Consider switching to the [Zgenom](https://github.com/jandamm/zgenom) fork, which is.

Most of these plugins can be installed by adding `zgen load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgen load` calls in.

Zgen will automatically clone the plugin repositories for you when you do a `zgen save`.

### [Zgenom](https://github.com/jandamm/zgenom)

Most of these plugins can be installed by adding `zgenom load githubuser/reponame` to your .zshrc file in the same function you're doing your other `zgenom load` calls in.

Zgenom will automatically clone the plugin repositories for you when you do a `zgenom save`.

### [zplug](https://github.com/zplug/zplug)

Most of these plugins can be installed by adding `zplug "githubuser/reponame"` to your `.zshrc` file.

### [zpm](https://github.com/zpm-zsh/zpm)

Most of these plugins can be installed by adding `zpm load "githubuser/reponame"` to your `.zshrc` file.

## Writing New Plugins

I've documented some recommendations for writing a new plugin [here](https://github.com/unixorn/awesome-zsh-plugins/blob/master/Writing_Plugins.md).

## Other Resources

### ZSH Tools

* [ShellSpec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, ZSH and all POSIX shells.
* [zshdb](https://github.com/rocky/zshdb) - A ZSH debugger
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

### Other Useful Lists

* [awesome-devenv](https://github.com/jondot/awesome-devenv) - A curated list of awesome tools, resources and workflow tips making an awesome development environment
* [awesome-sysadmin](https://github.com/n1trux/awesome-sysadmin) - A curated list of awesome open source sysadmin resources
* [Terminals Are Sexy](https://github.com/k4m4/terminals-are-sexy) - A curated list for CLI lovers.

Find other useful awesome-* lists at the [awesome collection](https://github.com/sindresorhus/awesome)

### Other References

The [ZSH Reference Card](http://www.bash2zsh.com/zsh_refcard/refcard.pdf) and [zsh-lovers site](https://grml.org/zsh/zsh-lovers.html) are indispensable.