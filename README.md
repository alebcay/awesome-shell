```
 █████╗ ██╗    ██╗███████╗███████╗ ██████╗ ███╗   ███╗███████╗
██╔══██╗██║    ██║██╔════╝██╔════╝██╔═══██╗████╗ ████║██╔════╝
███████║██║ █╗ ██║█████╗  ███████╗██║   ██║██╔████╔██║█████╗
██╔══██║██║███╗██║██╔══╝  ╚════██║██║   ██║██║╚██╔╝██║██╔══╝
██║  ██║╚███╔███╔╝███████╗███████║╚██████╔╝██║ ╚═╝ ██║███████╗
╚═╝  ╚═╝ ╚══╝╚══╝ ╚══════╝╚══════╝ ╚═════╝ ╚═╝     ╚═╝╚══════╝
███████╗██╗  ██╗███████╗██╗     ██╗
██╔════╝██║  ██║██╔════╝██║     ██║
███████╗███████║█████╗  ██║     ██║
╚════██║██╔══██║██╔══╝  ██║     ██║
███████║██║  ██║███████╗███████╗███████╗
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

A curated list of awesome command-line frameworks, toolkits, guides and gizmos. Inspired by awesome-php. This awesome collection is also available on [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu).
- [Shells](#shells)
- [Command-Line Productivity](#command-line-productivity)
  - [Directory Navigation](#directory-navigation)
- [Customization](#customization)
- [For Developers](#for-developers)
- [System Utilities](#system-utilities)
- [Downloading and Serving](#downloading-and-serving)
- [Multimedia and File Formats](#multimedia-and-file-formats)
- [Applications](#applications)
- [Games](#games)
- [Shell Package Management](#shell-package-management)
- [Shell Script Development](#shell-script-development)
- [Guides](#guides)
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [Other Awesome Lists](#other-awesome-lists)

## Shells

*Choose your base shell.*

* [bash](https://www.gnu.org/software/bash/) - GNU Project's shell (Bourne Again SHell)
* [elvish](https://elv.sh/) - Friendly, expressive shell features like anonymous functions and data structures
* [es](https://wryun.github.io/es-shell/) - The extensible shell, based on Plan 9's [rc](https://github.com/rakitzis/rc) shell
* [fish](https://fishshell.com) - Smart and user-friendly command line shell
* [ion](https://github.com/redox-os/ion) - A modern system shell that features a simple, yet powerful, syntax. It is written entirely in Rust.
* [ksh93](https://github.com/att/ast) - Korn Shell
* [mksh](https://github.com/MirBSD/mksh) - MirBSD Korn Shell
* [nushell](https://github.com/nushell/nushell) - A modern shell written in Rust
* [oksh](https://github.com/ibara/oksh) - Portable OpenBSD ksh
* [osh](https://www.oilshell.org) - Bash compatible, with new/modern Unix shell language called Oil
* [pdksh](https://cvsweb.openbsd.org/cgi-bin/cvsweb/src/bin/ksh/) - Public domain Korn shell
* [shell++](https://github.com/alexst07/shell-plus-plus) - Friendly and modern functional and object oriented shell script language
* [shenv](https://github.com/shenv/shenv) - Simple shell version management
* [tcsh](https://www.tcsh.org/) - C shell with file name completion and command line editing
* [xonsh](https://xon.sh) - Python-ish, BASHwards-looking shell language and command prompt
* [yash](https://yash.osdn.jp/) - A POSIX-compliant command line shell with built-in support for completion and prediction based on command history
* [zsh](https://www.zsh.org) - Powerful shell with scripting language

## Command-Line Productivity

*Search, bookmarks, multiplexing, and other tools that make your terminal experience more productive.*

* [AdvancedNewFile](https://github.com/tanrax/terminal-AdvancedNewFile) - Fast creation of files and directories in a recursive way. Inspired by the Vim plugin.
* [ag](https://github.com/ggreer/the_silver_searcher) - Super fast string search through a directory hierarchy
* [aliases](https://github.com/sebglazebrook/aliases) - Contextual, dynamic, organized aliases for bash
* [autoenv](https://github.com/inishchith/autoenv) - Directory-based environments
* [bashhub](https://github.com/rcaloras/bashhub-client) - :cloud: Bash history in the cloud. Indexed and searchable.
* [boilr](https://github.com/tmrts/boilr) - A blazingly fast CLI tool for creating projects from boilerplate templates.
* [boom](https://github.com/holman/boom) - Store links and snippets in the command line
* [borg](https://github.com/ok-borg/borg) - A terminal based search engine for bash commands
* [browsh](https://github.com/browsh-org/browsh) - The modern text-based browser
* [Buku](https://github.com/jarun/Buku) - Powerful command-line bookmark manager
* [byobu](https://www.byobu.org) - Text-based window manager and terminal multiplexer
* [cod](https://github.com/dim-an/cod) — A completion daemon for shell that learns when you invoke `--help` commands
* [CloudClip](https://github.com/skywind3000/CloudClip) - Your own clipboard in the cloud, copy and paste text with gist between different systems
* [ddgr](https://github.com/jarun/ddgr) - DuckDuckGo from the terminal
* [desk](https://github.com/jamesob/desk) - A lightweight workspace manager for the shell
* [direnv](https://github.com/direnv/direnv) - An environment switcher for the shell, compare with autoenv
* [dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync and web interface
* [eureka](https://github.com/simeg/eureka/) - :bulb: CLI tool to input and store your ideas without leaving the terminal
* [fasd](https://github.com/clvv/fasd) - Command-line productivity booster, offers quick access to files and directories
* [fd](https://github.com/sharkdp/fd) - A simple, fast and user-friendly alternative to find.
* [foxy](https://github.com/s-p-k/foxy) - Plain text bookmarks for Firefox and surf browsers.
* [fselect](https://github.com/jhspetersson/fselect) - Find files with SQL-like queries.
* [funky](https://github.com/bbugyi200/funky) - Extends functionality of shell functions making them more powerful and flexible.
* [fz](https://github.com/changyuheng/fz) - Seamless fuzzy tab completion for z
* [fzf](https://github.com/junegunn/fzf) - A command-line fuzzy finder
* [gitmux](https://github.com/arl/gitmux) - Show Git status in Tmux status bar
* [googler](https://github.com/jarun/googler) - Google Search, Google Site Search, Google News from the terminal
* [googlr](https://github.com/Astranno/googlr) - Command line tool that lets you search Google from your terminal.
* [has](https://github.com/kdabir/has) - `has` helps you check presence of various command line tools and their versions on path
* [how2](https://github.com/santinic/how2) - `how2` finds the simplest way to do something in a unix shell. It's like `man`, but you can query it in natural language.
* [navi](https://github.com/denisidoro/navi) - An interactive cheatsheet tool for the command-line
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - Colorize words in a command output
* [hr](https://github.com/LuRsT/hr) - `<hr />` for your terminal
* [hss](https://github.com/six-ddc/hss) - An interactive parallel ssh client featuring autocomplete and asynchronous execution
* [hstr](https://github.com/dvorka/hstr) - Bash History Suggest Box
* [k](https://github.com/supercrabtree/k) - k is a Zsh script to make directory listings more readable, adding Git status, fileweight colors and rotting dates
* [k alias](https://github.com/lingtalfi/k) - get kool aliases (and more) working with a simple one-liner
* [lf.sh](https://github.com/suewonjp/lf.sh) - Quickly search files with fewer typings and do many more (grepping, copying path to clipboard, etc)
* [Lmod](https://lmod.readthedocs.io/en/latest/) - Lua-based Environment Modules that enhances Tcl-based modules while being backward compatible (compare to modules)
* [loop](https://github.com/Miserlou/Loop) - Write and control complex loops with as one-liners
* [marker](https://github.com/pindexis/marker) - Bookmark your shell commands
* [mackup](https://github.com/lra/mackup/) - Keep your application settings in sync (OS X/Linux)
* [mcfly](https://github.com/cantino/mcfly) - Fly through your shell history. Great Scot!
* [modules](http://modules.sourceforge.net/) - Classical Tcl-based Environment Modules managing the shell environment (compare to Lmod, direnv, and autoenv)
* [nnn](https://github.com/jarun/nnn) - File browser and disk usage analyzer with excellent desktop integration
* [parallel](https://www.gnu.org/software/parallel/) - Build and execute shell command lines from standard input in parallel
* [pathpicker](https://github.com/facebook/PathPicker) - Accepts inputs like grep, searches, git etc; allows selecting files from the result of the input, which you can then open or provide as argument to a command.
* [pdd](https://github.com/jarun/pdd) - Tiny date, time diff calculator with timers
* [percol](https://github.com/mooz/percol) - Adds flavor of interactive filtering to the traditional pipe concept of UNIX shell
* [q](https://github.com/cal2195/q) - Vim like macro registers for your Bash and Zsh Shell
* [qfc](https://github.com/pindexis/qfc) - File-completion widget for Bash and Zsh
* [resh](https://github.com/curusarn/resh) - Contextual shell history for Zsh and Bash
* [rg](https://github.com/BurntSushi/ripgrep) - ripgrep is a line oriented search tool that combines the usability of The Silver Searcher with the raw speed of GNU grep
* [screen](https://www.gnu.org/software/screen/) - GNU terminal multiplexer
* [shell-history](https://github.com/pawamoy/shell-history) - Visualize your shell usage with Highcharts
* [SHML](https://github.com/odb/shml) - Style framework for the terminal (Shell Markup Language)
* [slugify](https://github.com/benlinton/slugify) - Command that converts filenames and directories to a web friendly format
* [sman](https://github.com/tokozedg/sman) - :bug: A command-line snippet manager
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ in your shell
* [spark.fish](https://github.com/jorgebucaran/spark.fish) - ▁▂▃▅ Sparkline Generator
* [sheet](https://github.com/oscardelben/sheet) -  Text snippets for the command line
* [spot](https://github.com/rauchg/spot) - Tiny file search utility
- [snips](https://github.com/srijanshetty/snips) - Command line tool to manage snippets of code.
* [sqlline](https://github.com/julianhyde/sqlline) - Shell for issuing SQL to relational databases via JDBC (multiline, completion, highlighting, dialect support)
* [sshfs](https://github.com/osxfuse/sshfs) - A tool for mounting remote file systems over SSH
* [sudocabulary](https://github.com/badarsh2/Sudocabulary) - Learn English Vocabulary from your terminal
* [surfraw](https://gitlab.com/surfraw/Surfraw) - browse specific site and search the web from your terminal without browser.
* [task-manager](https://github.com/lingtalfi/task-manager) - Execute all your scripts with just two or three keystrokes.
* [td-cli](https://github.com/darrikonn/td-cli) - A todo command line manager to organize and manage your todos across multiple projects.
* [thefuck](https://github.com/nvbn/thefuck) - Fix common shell mistakes by using an easy to remember command
* [tldr](https://github.com/raylee/tldr-sh-client) - A fully-functional bash client for tldr, simplified and community-driven man pages
* [tmux](https://tmux.github.io/) - Amazing terminal multiplexer
* [undollar](https://github.com/xtyrrell/undollar) - undollar bites the dollar sign off the tip of the command you just pasted into your terminal
* [v](https://github.com/rupa/v) - z for vim.
* [wemux](https://github.com/zolrath/wemux) - Multi-User Tmux Made Easy
* [xiki](https://xiki.org) - Makes the shell console more friendly and powerful
* [xsv](https://github.com/BurntSushi/xsv) - a fast CSV command line toolkit written in Rust
* [xxh](https://github.com/xxh/xxh) - Bring your favorite shell wherever you go through the SSH.

### Directory Navigation

* [aliasme](https://github.com/Jintin/aliasme) - alias helper to change directory quickly
* [autojump](https://github.com/wting/autojump) - A cd command that learns - easily navigate directories from the command line
* [bashmarks](https://github.com/huyng/bashmarks) - Directory bookmarks for the shell
* [bd](https://github.com/vigneshwaranr/bd) - Quickly go back to a parent directory
* [commacd](https://github.com/shyiko/commacd) - A faster way to move around in Bash
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: A next-generation cd command with an interactive filter
* [goto](https://github.com/iridakos/goto) - A shell utility for navigation to aliased directories supporting auto-completion
* [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate your file system faster by learning your habits.
* [lazy-cd](https://github.com/pedramamini/lazy-cd) - Simple bash commands for bookmarked navigation of the file system, complete with bash-completion.
* [up](https://github.com/shannonmoeller/up) - Ascend directories by name or count; for bash, zsh, and fish.
* [z](https://github.com/rupa/z) - z is the new j, yo
* [z.lua](https://github.com/skywind3000/z.lua) - A new cd command that helps you navigate faster by learning your habits
* [zoxide](https://github.com/ajeetdsouza/zoxide) - A faster way to navigate your filesystem, written in Rust
* [zpyi](https://github.com/sakshamsharma/zpyi) - Python in Zsh - Easy python scripting in shell

## Customization

*Custom prompts, color themes, etc.*

* [base16-builder](https://github.com/base16-builder/base16-builder) - Base16-Builder
* [bash-full-of-colors](https://github.com/slomkowski/bash-full-of-colors) - Powerful prompt with screen, tmux, git support and many more
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - An informative and fancy Bash prompt for Git users
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline-style Bash prompt in pure Bash script
* [bashstrap](https://github.com/barryclark/bashstrap) - A quick way to spruce up OSX terminal
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train.zsh) - :bullettrain_side: An oh-my-zsh shell theme based on the Powerline Vim plugin
* [emojify](https://github.com/mrowa44/emojify) Emoji on the command line :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - Nicer colors for terminal
* [geometry](https://github.com/geometry-zsh/geometry) - A minimal ZSH theme where any function can be added to the left prompt or (async) right prompt on the fly.
* [git-prompt](https://github.com/lvv/git-prompt) - Bash prompt with Git, SVN and HG modules
* [gittify](https://github.com/momeni/gittify) - A colorful Bash prompt + customized Git aliases
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - Color Scheme for Gnome Terminal
* [liquidprompt](https://github.com/nojhan/liquidprompt) - A full-featured & carefully designed adaptive prompt for Bash & Zsh
* [mysql-colorize](https://github.com/zpm-zsh/mysql-colorize) -  Colorization for mysql comand-line client
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - An opinionated git prompt for bash and zsh
* [polyglot](https://github.com/agkozak/polyglot) - An informative Git prompt that works in bash, zsh, ksh, mksh, pdksh, dash, and busybox sh
* [powerlevel10k](https://github.com/romkatv/powerlevel10k) - Super flexible awesome powerline ZSH theme
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - Bash prompt with colors, Git statuses, and Git branches
* [synth-shell](https://github.com/andresgongora/synth-shell) - Greeter with a customizable status report and a fancy bash prompt

## For Developers

*Command-line development, version control, and deployment.*

* [ack](https://beyondgrep.com/) - A grep-like search tool optimized for source code.
* [add-gitignore](https://github.com/TejasQ/add-gitignore) - Interactive CLI that generates a .gitignore for your project based on your needs.
* [bcal](https://github.com/jarun/bcal) - Byte CALculator for storage conversions and calculations
* [bitwise](https://github.com/mellowcandle/bitwise) - Terminal based interactive bit manipulator in curses.
* [bocker](https://github.com/p8952/bocker) - Docker implemented in 100 lines of bash
* [cloc](https://github.com/AlDanial/cloc) - Count Lines of Code
* [doclt](https://github.com/omgimanerd/doclt) - A command line interface to Digital Ocean
* [dokku](https://github.com/dokku/dokku) - Docker powered mini-Heroku. The smallest PaaS implementation you've ever seen.
* [getopts.fish](https://github.com/jorgebucaran/getopts.fish) - CLI parser for fish
* [forgit](https://github.com/wfxr/forgit) - Utility tool for `git` taking advantage of fuzzy finder fzf.
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - Many Git extra utilities. Churn, cut-branch, improved-merge and many more.
* [git-extras](https://github.com/tj/git-extras) - Git utilities -- repo summary, repl, changelog population, author commit percentages and more
* [git-open](https://github.com/paulirish/git-open) - Type `git open` to open the GitHub page or website for a repository in your browser
* [git-quick-stats](https://github.com/arzzen/git-quick-stats) - Git quick statistics is a simple and efficient way to access various statistics in git repository.
* [git-semver](https://github.com/markchalloner/git-semver) - Git plugin for easing semantic versioning and changelog validation
* [git-sh](https://github.com/rtomayko/git-sh) - A customized Bash environment suitable for Git work
* [hub](https://github.com/github/hub) - hub helps you win at git.
* [licins](https://github.com/dogoncouch/licins) - Insert commented software licenses into source code.
* [mkdkr](https://github.com/rosineygp/mkdkr) - Makefile + Docker = CI Pipeline
* [mr](https://myrepos.branchable.com) - Multiple Repository management tool
* [overcommit](https://github.com/sds/overcommit) - A fully configurable and extendable Git hook manager
* [pre-commit](https://pre-commit.com) - A framework for managing and maintaining multi-language pre-commit hooks
* [rebound](https://github.com/shobrook/rebound) - Instantly browse Stack Overflow results in your terminal when you get a compiler error
* [repren](https://github.com/jlevy/repren) - Command-line search-and-replace and file-renaming swiss army knife
* [slap](https://github.com/slap-editor/slap) - Sublime-like terminal-based text editor that runs on Node.js
* [shipit](https://github.com/sapegin/shipit) - Minimalistic SSH deployment
* [starring](https://github.com/ritz078/starring) - Automatically star the npm-packages that you are using on GitHub.
* [tag](https://github.com/aykamko/tag) - Instantly jump to your ag matches.
* [wipe-modules](https://github.com/bntzio/wipe-modules) - A little agent that removes the node_modules folder of non-active projects

## System Utilities

*OS-related tools, including system administration, system debugging, and file and process management.*

* [atop](https://www.atoptool.nl) - ASCII full-screen performance monitor that is capable of reporting the activity of all processes
* [bat](https://github.com/sharkdp/bat) - A `cat` clone with wings
* [bmon](https://github.com/tgraf/bmon) - Real-time network bandwidth monitor and rate estimator with human-friendly visual output
* [catcli](https://github.com/deadc0de6/catcli) -  The command line catalog tool for your offline data
* [ccat](https://github.com/owenthereal/ccat) - ccat is the colorizing cat. It works similar to cat but displays content with syntax highlighting.
* [exa](https://github.com/ogham/exa) - A modern version of `ls`.
* [progress](https://github.com/Xfennec/progress) - Linux tool to show progress for `cp`, `rm`, `dd`, and more...
* [stronghold](https://github.com/alichtman/stronghold) - Easily configure MacOS security settings from the terminal.
* [glances](https://github.com/nicolargo/glances) - Glances an Eye on your system
* [goaccess](https://github.com/allinurl/goaccess) - GoAccess is a real-time web log analyzer and interactive viewer that runs in a terminal in \*nix systems.
* [hblock](https://github.com/hectorm/hblock) - Hosts-file based adblocker
* [histstat](https://github.com/vesche/histstat) - History for netstat
* [htop](https://github.com/hishamhm/htop) - A ncurses based interactive process viewer which aims to be a better `top`
* [lnav](https://lnav.org) - An advanced log file viewer for the small-scale
* [logdissect](https://github.com/dogoncouch/logdissect) - CLI utility and Python API for analyzing log files and other data.
* [ls++](https://github.com/trapd00r/ls--) - Colorized ls on steroids
* [lsp](https://github.com/dborzov/lsp) - An improved `ls`, with file descriptions in plain language and intelligent file grouping
* [maza](https://github.com/tanrax/maza-ad-blocking) - Local ad blocker. Like Pi-hole but local and using your operating system.
* [mtr](https://github.com/traviscross/mtr) - The functionality of the 'traceroute' and 'ping' programs in a single network diagnostic tool.
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses Disk Usage
* [nmtui](https://github.com/NetworkManager/NetworkManager) - Text User Interface for controlling NetworkManager
* [powertop](https://github.com/fenrus75/powertop) - Battery/Power usage and device stats monitoring command-line tool, with tune-up options.
* [procdog](https://github.com/jlevy/procdog) - Lightweight command-line control of long-lived processes like servers
* [quick-secure](https://github.com/marshyski/quick-secure) - Quickly secure and harden UNIX/Linux systems
* [rng](https://github.com/nickolasburr/rng) - Copy range of lines from file or stdin to stdout.
* [wifi-wand](https://github.com/keithrbennett/wifiwand) - a Ruby command line application for managing WiFi on MacOS (install by `gem install wifi-wand`)
* [xiringuito](https://github.com/ivanilves/xiringuito) - SSH-based "VPN for poors"

## Downloading and Serving

*Self-hosted, lightweight servers and networking tools written in shell scripts.*

* [aria2](https://github.com/aria2/aria2) - aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, BitTorrent and Metalink
* [balls](https://github.com/jneen/balls) - Bash on Balls
* [bashttpd](https://github.com/avleen/bashttpd) - A web server written in Bash
* [bashhub-server](https://github.com/nicksherron/bashhub-server) - Private cloud shell history. Open source server for bashhub
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" or "2-way directory (r)sync with proper deletion"
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader is a Bash script which can be used to upload, download, list or delete files from Dropbox
* [httpie](https://github.com/httpie/httpie) - HTTPie is a command line HTTP client, a user-friendly cURL replacement
* [HTTPLab](https://github.com/gchaincl/httplab) - The interactive web server, let you inspect HTTP requests and forge responses.
* [ngincat](https://github.com/jaburns/ngincat) - Tiny Bash HTTP server using netcat
* [resty](https://github.com/micha/resty) - Little command line REST client that you can use in pipelines
* [shell2http](https://github.com/msoap/shell2http) - HTTP-server to execute shell commands. Designed for development, prototyping or remote control
* [vesper](https://github.com/chris-rock/vesper) - 🍸Vesper is a HTTP framework for Bash/Unix Shell
* [youtube-dl](https://yt-dl.org/) - Small command-line program to download videos from YouTube.com and other video sites

## Multimedia and File Formats

*Tools for handling video and audio files.*

* [adb-export](https://github.com/sromku/adb-export) - Export Android content providers to CSV format
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - A text-based kitchen for Android ROM customization. Uses shell scripts and works with Cygwin/OS X/Linux
* [Beets](https://github.com/beetbox/beets) - Music library manager and MusicBrainz tagger
* [cmus](https://github.com/cmus/cmus) - Cross-platform cli audio player.
* [fx](https://github.com/antonmedv/fx) - Command-line JSON processing tool by anononymus JavaScript functions
* [gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding
* [image-scraper](https://github.com/sananth12/ImageScraper) - A cool command line image scraper with a lot of features.
* [imgp](https://github.com/jarun/imgp) - Blazing fast batch image resizer and rotator
* [jo](https://github.com/jpmens/jo) - A small utility to create JSON objects from command-line arguments.
* [jq](https://github.com/stedolan/jq) - Sed for json data. You can use it to slice and filter and map and transform structured data
* [korkut](https://github.com/oguzhaninan/korkut) - Quick and simple image processing at the command line.
* [mpv](https://mpv.io/) - Lets you play most audio and video formats (using ASCII characters) in the shell as well as in a GUI.
* [nehm](https://github.com/bogem/nehm) - Console tool, which downloads, sets IDv3 tags and adds to your iTunes (if you use it) your SoundCloud likes in convenient way
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST turns your $35 Raspberry Pi in to a Chromecast like Device
* [sejda](https://github.com/torakiki/sejda/) - Command line manipulation of PDF documents (split, merge, rotate, convert to jpg, extract text, etc)
* [visidata](https://github.com/saulpw/visidata) - A terminal spreadsheet multitool for exploring and arranging data (csv/json/xml/xls/yaml/etc)
* [xidel](https://github.com/benibela/xidel/) - Cli tool to filter, map and create HTML/XML/JSON data with (Turing-complete) XPath and XQuery.
* [xmlstarlet](http://xmlstar.sourceforge.net/) - Old but powerful tool for command-line XML formatting, filtering, and manipulation.

## Applications

*Command line-based applications or command line access to existing services.*

* [ansiweather](https://github.com/fcambus/ansiweather) - Weather in your terminal, with ANSI colors and Unicode symbols
* [awless](https://github.com/wallix/awless) - A powerful, innovative and small surface CLI to manage AWS.
* [bashblog](https://github.com/cfenollosa/bashblog) - A Bash script that handles blog posting
* [carbon-now-cli](https://github.com/mixn/carbon-now-cli) - 🎨 Beautiful images of your code — from right inside your terminal.
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - Choose an OSS license from the comfort of your terminal
* [cointop](https://github.com/miguelmota/cointop) - The fastest and most interactive terminal based UI application for tracking cryptocurrencies
* [dstask](https://github.com/naggie/dstask) - Single binary terminal-based TODO manager with git-based sync + markdown notes per task
* [facebook-cli](https://github.com/specious/facebook-cli) - Facebook command line tool
* [fanyi](https://github.com/afc163/fanyi) - Translate English to Chinese in terminal
* [gcalcli](https://github.com/insanum/gcalcli) - Google Calendar command line interface
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - Command line evernote client
* [haxor-news](https://github.com/donnemartin/haxor-news) - Browse Hacker News like a haxor
* [hn-cli](https://github.com/rafaelrinaldi/hn-cli) - Browse Hacker News from the comfort of your Terminal
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - Draw point on world map using ip address
* [isitup](https://github.com/lord63/isitup) - Check whether a website is up or down
* [jrnl](https://github.com/jrnl-org/jrnl) - A simple command line journal application that stores your journal in a plain text file
* [kanban.bash](https://github.com/coderofsalvation/kanban.bash) - commandline asciii kanban board for minimalist productivity bash hackers (csv-based)
* [ledger](https://github.com/ledger/ledger) - Command line accounting
* [licen](https://github.com/lord63/licen) - Generate your license. Yet another lice, but implement with Jinja2 and docopt
* [md2png](https://github.com/weaming/md2png) - Convert markdown to PNG image
* [moviemon](https://github.com/iCHAIT/moviemon) - Everything about your movies within the command line.
* [nomino](https://github.com/yaa110/nomino) - Batch rename utility using regex, sort and map file options.
* [pockyt](https://github.com/achembarpu/pockyt) - Read, Manage, and Automate your [Pocket](https://getpocket.com) collection.
* [pushblast](https://github.com/alebcay/pushblast) - Get PushBullet notifications when a shell program exits
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - Bash interface to the PushBullet API
* [ranger](https://github.com/ranger/ranger) - A console file manager with VI key bindings.
* [Reddit Terminal Viewer](https://github.com/michael-lazar/rtv) - Browse Reddit from your terminal
* [SAWS](https://github.com/donnemartin/saws) - A Supercharged AWS CLI
* [taskbook](https://github.com/klaussinani/taskbook) - Tasks, boards & notes for the command-line habitat
* [taskwarrior](https://taskwarrior.org/) - A command-line TODO list manager
* [terjira](https://github.com/keepcosmos/terjira) - Command line power tool for Jira
* [transfer.sh](https://transfer.sh/) — Quickly upload and share files from your shell
* [vl](https://github.com/ellisonleao/vl) - URL link checker on text documents
* [wego](https://github.com/schachmat/wego) - Weather app for the terminal
* [whales](https://github.com/Gueils/whales) - A tool to automatically dockerize your applications
* [whereami](https://github.com/rafaelrinaldi/whereami) - Get your geolocation information from the CLI
* [wttr.in](https://github.com/chubin/wttr.in) - :partly_sunny: The right way to check the weather (curl wttr.in)

## Games

*All work and no play is a cruddy way to spend your day.*

* [bash2048](https://github.com/mydzor/bash2048) - Bash implementation of 2048 game
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - Bash implementation of minesweeper
* [nudoku](https://github.com/jubalh/nudoku) - ncurses based sudoku game written in C
* [piu-piu](https://github.com/vaniacer/piu-piu-SH) - Horizontal scroller game in bash with multiplayer mode!
* [sedtris](https://github.com/uuner/sedtris) - Tetris in sed
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - Arkanoid and Sokoban written using sed
* [SHTAP](https://notimetoplay.org/engines/shtap/) - Reusable text adventure engine for Bash 4
* [tty-solitaire](https://github.com/mpereira/tty-solitaire) - Play solitaire in your terminal!

## Shell Package Management

*Tools for managing multiple shell configurations. For zsh-specific tools, see the Zsh section.*

* [bash-it](https://github.com/Bash-it/bash-it) - A community Bash framework
* [basher](https://github.com/basherpm/basher) - A package manager for shell scripts
* [bashing](https://github.com/xsc/bashing) - Smashing Bash into Pieces
* [bpkg](https://www.bpkg.sh/) - JavaScript has npm, Ruby has Gems, Python has pip and now Shell has bpkg
* [dotdrop](https://github.com/deadc0de6/dotdrop) - Save your dotfiles once, deploy them everywhere
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – Shell agnostic git based dotfiles package manager, written in Python.
* [fresh](https://github.com/freshshell/fresh) - Keep your dotfiles fresh
* [homeshick](https://github.com/andsens/homeshick) - Git dotfile synchronizer written in Bash
* [shallow-backup](https://github.com/alichtman/shallow-backup) - Easily create lightweight documentation of installed packages, dotfiles, and more
* [shundle](https://github.com/javier-lopez/shundle) - Plugin manager for shell scripts
* [vcsh](https://github.com/RichiH/vcsh) - Config manager based on Git
* [yadm](https://yadm.io/) - Git-based dotfiles manager supporting encryption, alternates, and bootstrapping

## Shell Script Development

*Tools for writing, improving, or organizing Bash or other shell scripts*

* [ansi](https://github.com/fidian/ansi) - ANSI escape codes in pure bash - change text color, position the cursor, much more
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash unit testing framework
* [bashful](https://github.com/jmcantrell/bashful) - A collection of libraries to simplify writing Bash scripts
* [Bashlets](https://github.com/reale/bashlets) - A modular extensible toolbox for Bash
* [bashmanager](https://github.com/lingtalfi/bashmanager) - mini bash framework for creating command line tools
* [bashwithnails](https://github.com/mindaugasbarysas/bashwithnails) - a Bash framework written just for fun with testing, dependency management & packaging
* [bash-language-server](https://github.com/bash-lsp/bash-language-server) - [LSP](https://microsoft.github.io/language-server-protocol/)-based Bash language server
* [bats](https://github.com/bats-core/bats-core) - Bash Automated Testing System
* [crash](https://github.com/molovo/crash) - Proper error handling, exceptions and try/catch for ZSH
* [critic.sh](https://github.com/Checksum/critic.sh) - Dead simple testing framework for Bash with coverage reporting
* [esh](https://github.com/jirutka/esh) - A simple templating engine based on shell, implemented in ~290 lines of POSIX shell and awk.
* [Fishtape](https://github.com/jorgebucaran/fishtape) - TAP producer and test harness for fish
* [composure](https://github.com/erichs/composure) - Compose, document, version and organize your shell functions
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - A command line argument parser in 50 lines of portable shell script.
* [is.sh](https://github.com/qzb/is.sh) - An alternative for builtin test command, it will make your "if" statements pretty
* [lumberjack](https://github.com/molovo/lumberjack) - A logging interface for shell scripts
* [mo](https://github.com/tests-always-included/mo) - Mustache templates in pure bash
* [optparse](https://github.com/nk412/optparse) - A BASH wrapper for getopts, for simple command line arguments.
* [rerun](https://github.com/rerun/rerun) - A modular shell automation framework to organize your keeper scripts
* [revolver](https://github.com/molovo/revolver) - A reusable progress spinner for shell scripts
* [phases](https://github.com/sorokine/phases) - Minimally invasive bash preprocessor, select sections of your script to run
* [powscript](https://github.com/coderofsalvation/powscript) - bash transpiler written in bash (coffeescript for bash)
* [semver_bash](https://github.com/cloudflare/semver_bash) - Semantic Versioning in Bash
* [sh-semver](https://github.com/qzb/sh-semver) - Semver tool for bash - finds versions matching to specified rules
* [shellcheck](https://github.com/koalaman/shellcheck) - Static analysis tool for shell scripts
* [shellfire](https://github.com/shellfire-dev/shellfire) -  A repository of namespaced, composable shell (bash, sh and dash) function libraries
* [shellspec](https://github.com/shellspec/shellspec) - A full-featured BDD unit testing framework for dash, bash, ksh, zsh and all POSIX shells
* [shpec](https://github.com/rylnd/shpec) - A shell testing framework
* [shutit](https://ianmiell.github.io/shutit/) - Automation framework based on bash and pexpect
* [sub](https://github.com/basecamp/sub) - A delicious way to organize programs
* [ts](https://github.com/thinkerbot/ts) - A shell test script
* [urchin](https://github.com/tlevine/urchin) - An idiomatic shell testing framework that uses only shell commands
* [shunit2](https://github.com/kward/shunit2) - A unit test framework for Bash scripts with a flavour of JUnit/PyUnit.
* [rebash](https://github.com/jandob/rebash) - Scripting library/framework. Features: imports, exceptions, doc-tests ...
* [zunit](https://github.com/zunit-zsh/zunit) - A powerful unit testing framework for ZSH

# Guides

* [Bash Official Reference Manual](https://www.gnu.org/savannah-checkouts/gnu/bash/manual/bash.html)
* [Bash Hackers Wiki](https://wiki.bash-hackers.org/)
* [Greg Wooledge's (aka "greycat") wiki](https://mywiki.wooledge.org).
  Specifically [Bash Guide](https://mywiki.wooledge.org/BashGuide), [Bash FAQ](https://mywiki.wooledge.org/BashFAQ) and [Bash Pitfalls](https://mywiki.wooledge.org/BashPitfalls)
* [Google's Shell Style Guide](https://google.github.io/styleguide/shell.xml)
* [The Linux Documentation Project: Bash Programming - Intro/How-to](https://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html)
* [The Linux Documentation Project: Advanced Bash Scripting Guide](https://tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell Scripting](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [Use the Unofficial Bash Strict Mode (Unless You Looove Debugging)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line)
* [Learn Enough Command Line to Be Dangerous](https://www.learnenough.com/command-line-tutorial/basics)
* [A guide to learn bash](https://github.com/Idnan/bash-guide)

# Other Awesome Lists

Other amazingly awesome lists can be found in [awesome-awesome](https://github.com/emijrp/awesome-awesome) and [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness).

### See also

* [awesome-cli-apps](https://github.com/agarrharr/awesome-cli-apps)
* [awesome-fish][awesome-fish]
* [awesome-zsh][awesome-zsh]
* [terminals-are-sexy](https://github.com/k4m4/terminals-are-sexy)

[awesome-badge]: https://raw.githubusercontent.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-fish]: https://github.com/jorgebucaran/awsm.fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
