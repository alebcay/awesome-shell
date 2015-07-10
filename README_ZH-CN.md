# Awesome Shell

这是一份非常棒的命令行框架、工具包、指南、以及小玩意儿组织清单。由 awesome-php 获得灵感。该 awesome 收集在 [Unix-Shell.ZEEF.com](https://unix-shell.zeef.com/caleb.xu) 上也可用。
- [Awesome Bash](#awesome-bash)
    - [命令行效率](#命令行效率)
    - [定制](#定制)
    - [针对开发者](#针对开发者)
    - [系统工具](#系统工具)
    - [下载与服务](#下载与服务)
    - [多媒体与文件格式](#多媒体与文件格式)
    - [应用程序](#应用程序)
    - [游戏](#游戏)
    - [Shell 包管理](#shell-包管理)
    - [Shell 脚本开发](#shell-脚本开发)
    - [Zsh](#zsh)
- [指南](#指南)
- [其它 Awesome 清单](#其它-awesome-清单)


# Awesome Bash


## 命令行效率

*使你的终端体验更有效率的搜索、书签、多路复用、以及其它工具。*

* [ag](https://github.com/ggreer/the_silver_searcher) - 在层级目录中超快的搜索字符串
* [autoenv](https://github.com/kennethreitz/autoenv) - 基于目录的环境
* [autojump](https://github.com/joelthelion/autojump) - 自带学习功能的 cd 命令，从命令行轻易地导航目录
* [bash-slugify](https://github.com/benlinton/bash-slugify) - 将文件名及目录转换为 web 友好的格式
* [bashmarks](https://github.com/huyng/bashmarks) - 适用于 shell 的目录书签
* [boom](https://github.com/holman/boom) - 在命令行中存储链接及片断
* [byobu](http://byobu.co/) - 基于文本的窗口管理器及终端多路复用器
* [commacd](https://github.com/shyiko/commacd) - 在 Bash 中更快速的移动方式
* [fasd](https://github.com/clvv/fasd) - 命令行效率提升器，提供快速访问文件及目录
* [fzf](https://github.com/junegunn/fzf) - 命令行下的模糊搜索器
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - 在命令输出中给单词着色
* [hr](https://github.com/LuRsT/hr) - 适用于终端的 `<hr />`
* [hstr](https://github.com/dvorka/hstr) - Bash 历史建议框
* [k](https://github.com/supercrabtree/k) - k 是一个使目录列表更可读的 Zsh 脚本，它增添了 Git 状态、文件颜色、以及腐朽的日期
* [marker](https://github.com/pindexis/marker) - 将你的 shell 命令加到书签
* [parallel](http://www.gnu.org/software/parallel) - 以并行化方式从标准输入构造并执行 shell 命令行
* [percol](https://github.com/mooz/percol) - 为传统的 UNIX shell 管道添加交互式的过滤
* [SHML](https://github.com/MaxCDN/shml) - 适用于终端的样式框架 (Shell 标记语言)
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ 在你的 shell 中
* [spot](https://github.com/guille/spot) - 微型的文件搜索工具
* [snips](https://github.com/srijanshetty/snips) - 管理代码片断的命令行工具
* [sshfs](https://github.com/osxfuse/sshfs) - 通过 SSH 挂载远程文件系统的工具
* [sshrc](https://github.com/Russell91/sshrc) - SSH 时带上你的 .bashrc、.vimrc 等
* [thefuck](https://github.com/nvbn/thefuck) - 通过使用容易记住的命令修正常见的 shell 错误
* [tmux](http://tmux.github.io/) - 很棒的终端复用器
* [v](https://github.com/rupa/v) - 适用于 Vim 的 z
* [wemux](https://github.com/zolrath/wemux) - 多用户使用 Tmux 变得更容易
* [z](https://github.com/rupa/z) - z 是新的 j

## 定制

*定制提示符、颜色主题等。*

* [base16-shell](https://github.com/chriskempson/base16-shell) - 适用于 shell 的 Base16
* [bash-git-prompt](https://github.com/magicmonty/bash-git-prompt) - 针对 Git 用户的信息及梦幻提示符
* [bash-powerline](https://github.com/riobard/bash-powerline) - Powerline 风格的 Bash 提示符，纯 Bash 脚本
* [bashstrap](https://github.com/barryclark/bashstrap) - 美化 OS X 终端的快速方法
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - 很好的终端颜色主题
* [git-prompt](https://github.com/lvv/git-prompt) - 包含 Git、SVN 及 HG 模块的 Bash 提示符
* [gittify](https://github.com/momeni/gittify) - 彩色的 Bash 提示符及定制的 Git 别名
* [Gogh - Color Scheme](https://github.com/Mayccoll/Elementary-OS-Terminal-Colors) - 适用于 GNOME 终端的颜色主题
* [liquidprompt](https://github.com/nojhan/liquidprompt) - 针对 Bash 和 Zsh 的全功能及用心设计的自适应提示符
* [mysql-colorize](https://github.com/horosgrisa/mysql-colorize.bash) -  彩色的 MySQL 命令行客户端
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 针对 Bash 和 Zsh 的自用 Git 提示符
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - 包含颜色、Git 状态及 Git 分支的 Bash 提示符

## 针对开发者

*命令行开发、版本控制、以及部署。*

* [cloc](http://cloc.sourceforge.net) - 统计代码行数
* [dokku](https://github.com/progrium/dokku) - 百行 Bash 打造的 Docker 迷你 Heroku
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 很多 Git 扩展工具，包括 churn、cut-branch、improved-merge 等
* [git-extras](https://github.com/visionmedia/git-extras) - Git 工具，包括仓库摘要、repl、更改日志人数、作者提交百分比等
* [git-open](https://github.com/paulirish/git-open) - 输入 `git open` 在浏览器中打开 GitHub 页面或仓库网站
* [git-semver](https://github.com/markchalloner/git-semver) - 用来方便的语义化版本及更改日志验证的 Git 插件
* [git-sh](https://github.com/rtomayko/git-sh) - 适合 Git 工作的定制 Bash 环境
* [git-up](https://github.com/aanand/git-up) - 自动变基进来的更改代替合并，优雅！
* [mr](https://github.com/joeyh/myrepos) - 多仓库管理工具
* [overcommit](https://github.com/brigade/overcommit) - 完全可配置且可扩展的 Git hook 管理器
* [pre-commit](http://pre-commit.com) - 用于管理及维护多语言 pre-commit hooks 的框架
* [repren](https://github.com/jlevy/repren) - 命令行搜索与替换及文件重命名的瑞士军刀式工具
* [slap](https://github.com/slap-editor/slap) - 运行在 Node.js 上的基于终端的类 Sublime 文本编辑器
* [shipit](https://github.com/sapegin/shipit) - 极简 SSH 部署

## 系统工具

*操作系统相关工具，包括系统管理、系统调试、及文件和进程管理。*

* [cv](https://github.com/Xfennec/cv) - 显示 cp、rm、dd 等命令进度的 Linux 工具
* [htop](https://github.com/hishamhm/htop) - 基于 ncurses 的交互式进程查看器，其目标是比 `top` 更好
* [lsp](https://github.com/dborzov/lsp) - 改进的 `ls`，包含无格式语言的文件说明及智能的文件分组
* [ncdu](http://dev.yorhel.nl/ncdu) - NCurses 磁盘占用统计
* [powertop](https://github.com/fenrus75/powertop) - 电池/电源占用及设备状态监视命令行工具，包含调整选项
* [procdog](https://github.com/jlevy/procdog) - 轻量级的命令行控制类似服务器的长实时进程
* [quick-secure](https://github.com/marshyski/quick-secure) - 快速的安全并加固 UNIX/Linux 系统

## 下载与服务

*使用 shell 脚本编写的自架、轻量级服务器与网络工具。*

* [aria2](https://github.com/tatsuhiro-t/aria2) - aria2 是一款在命令行中操作的轻量级多协议、多来源、及跨平台下载工具，它支持 HTTP/HTTPS、FTP、BitTorrent 及 Metalink
* [balls](https://github.com/jneen/balls) - Bash on Balls，全功能的 web 平台
* [bashttpd](https://github.com/avleen/bashttpd) - 使用 Bash 编写的 web 服务器
* [bitpocket](https://github.com/sickill/bitpocket) - "DIY Dropbox" 或 "双向目录同步（含正确删除）"
* [Dropbox-Uploader](https://github.com/andreafabrizi/Dropbox-Uploader) - Dropbox Uploader 是用来从 Dropbox 上传、下载、列出或删除文件的 Bash 脚本
* [httpie](https://github.com/jakubroztocil/httpie) - HTTPie 是一个命令行 HTTP 客户端，用户友好的 cURL 替代品
* [ngincat](https://github.com/jaburns/ngincat) - 使用 netcat 的微型 Bash HTTP 服务器
* [resty](https://github.com/micha/resty) - 你可以在管道中使用的小型命令行 REST 客户端
* [youtube-dl](https://github.com/rg3/youtube-dl) - 从 YouTube.com 及其它视频站点下载视频的小命令行程序

## 多媒体与文件格式

*用于处理视频及音频文件的工具。*

* [adb-export](https://github.com/sromku/adb-export) - 导出 Android 内容提供商为 CSV 格式
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - 基于文本的 Android ROM 定制 kitchen，使用 shell 脚本并支持 Cygwin/OS X/Linux
* [Beets](https://github.com/sampsyo/beets) - 音乐库管理器及 MusicBrainz 标签工具
* [image-scraper](https://github.com/sananth12/ImageScraper) - 包含诸多特性的酷命令行图像 scraper
* [jq](https://github.com/stedolan/jq) - 针对 json 数据的 Sed，你可以使用它分片、过滤、映射及变换结构化数据
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST 将你的 35 刀 Raspberry Pi 变成类 Chromecast 设备
* [sejda](https://github.com/torakiki/sejda/) - 命令行下的 PDF 文档处理工具（分割、合并、旋转、转换为 jpg、提取文本等）
* [xmlstarlet](http://xmlstar.sourceforge.net/) - 古老而强大的命令行 XML 格式化、过滤及处理工具

## 应用程序

*基于命令行的应用程序或从命令行访问现有服务。*

* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气预报，包含 ANSI 颜色及 Unicode 符号
* [bashblog](https://github.com/cfenollosa/bashblog) - 处理 blog 投递的 Bash 脚本
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - 命令行的 Evernote 客户端
* [jrnl](https://github.com/maebert/jrnl) - 使用无格式文本文件存储日记的简单命令行程序
* [ledger](https://github.com/ledger/ledger) - 命令行记账
* [pushblast](https://github.com/alebcay/pushblast) - 当 shell 程序退出时获得 PushBullet 通知
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - PushBullet API 的 Bash 接口
* [transfer.sh](https://transfer.sh/) — 从 shell 快速上传并分享文件
* [wego](https://github.com/schachmat/wego) - 适用于终端的天气预报应用

## 游戏

*只顾工作而不玩玩是一种糟糕的度日方式。*

* [bash2048](https://github.com/mydzor/bash2048) - 2048 游戏的 Bash 实现
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - 扫雷的 Bash 实现
* [sedtris](https://github.com/uuner/sedtris) - 使用 sed 实现的俄罗斯方块
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - 使用 sed 编写的 Arkanoid 和 Sokoban

## Shell 包管理

*用于管理多个 shell 配置的工具。*

* [antigen-hs](https://github.com/Tarrasch/antigen-hs) - 针对启动 shell 时低开销进行优化的 antigen 替代品
* [antibody](https://github.com/caarlos0/antibody) - 使用 Go 编写的更快且更简单的 antigen 替代品
* [bash-it](https://github.com/revans/bash-it) - 社区化的 Bash 框架
* [basher](https://github.com/basherpm/basher) - 针对 shell 脚本的包管理器
* [bpkg](http://www.bpkg.io/) - JavaScript 有 npm、Ruby 有 Gems、Python 有 pip，现在 Shell 有 bpkg
* [fresh](https://github.com/freshshell/fresh) - 使你的 dotfiles 保持更新
* [homeshick](https://github.com/andsens/homeshick) - 使用 Bash 编写的 Git dotfile 同步器
* [oh-my-fish](https://github.com/bpinto/oh-my-fish) - 用于管理 Fish shell 配置的框架，由 Oh My Zsh 获得灵感
* [Wahoo](https://github.com/bucaran/wahoo) - 适用于 Fish shell 的全功能框架及去中心化包管理器
* [vcsh](https://github.com/RichiH/vcsh) - 基于 Git 的配置管理器

## Shell 脚本开发

*用于编写、改进、及管理 Bash 或其它 shell 脚本的工具。*

* [bashful](https://github.com/jmcantrell/bashful) - 简化编写 Bash 脚本的库收集
* [bats](https://github.com/sstephenson/bats) - Bash 自动化测试系统
* [composure](https://github.com/erichs/composure) - 撰写、文档、版本、及组织你的 shell 函数
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - 使用 50 行可移植 shell 脚本写成的命令行参数解析器
* [rerun](https://github.com/rerun/rerun) - 用来管理保留脚本的模块化 shell 自动化框架
* [semver_bash](https://github.com/cloudflare/semver_bash) - 使用 Bash 实现的语义化版本
* [shellcheck](https://github.com/koalaman/shellcheck) - 针对 shell 脚本的静态化分析工具
* [shpec](https://github.com/rylnd/shpec) - shell 测试框架
* [sub](https://github.com/basecamp/sub) - 以美味之道来管理程序
* [ts](https://github.com/thinkerbot/ts) - shell 测试脚本
* [shunit2](https://github.com/kward/shunit2) - 适用于 Bash 脚本的单元测试框架（具有 JUnit/PyUnit 风味）

## Zsh

*特别针对 Zsh 的工具及定制。*

* [awesome-zsh-plugins](https://github.com/unixorn/awesome-zsh-plugins) - 可用于 antigen、dotzsh、oh-my-zsh 及 prezto 的 Zsh 插件列表
* [antigen](https://github.com/zsh-users/antigen) - 适用于 Zsh 的插件管理器，由 oh-my-zsh 及 vundle 获得灵感
* [dotzsh](https://github.com/dotphiles/dotzsh) - dotzsh 力争变成平台和版本独立，在 Zsh 旧版本下运行时可能缺少某些功能，但它让你在多个不同的系统上使用相同的设置而没问题
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) - 管理 Zsh 配置的社区化框架
* [pretty-time-zsh](https://github.com/sindresorhus/pretty-time-zsh) - 将秒转换为人类可读的字符串: `165392` → `1d 21h 56m 32s`
* [powerline-zsh](https://github.com/carlcarl/powerline-zsh) - 适用于 Zsh 的 powerline
* [prezto](https://github.com/sorin-ionescu/prezto) - 针对 Zsh 的配置框架
* [pure](https://github.com/sindresorhus/pure) - 漂亮、极简、及快速的 Zsh 提示符
* [zgen](https://github.com/tarjoilija/zgen) - 适用于 Zsh 的轻量级插件管理器，由 antigen 获得灵感，但为启动新的 shell 时优化了速度，可载入 oh-my-zsh 兼容的插件和主题
* [zsh-autosuggestions](https://github.com/tarruda/zsh-autosuggestions) - 适用于 Zsh 的类 Fish 自动建议
* [zsh-dwim](https://github.com/oknowton/zsh-dwim) - Zsh 照我之意做
* [zsh-git-prompt](https://github.com/olivierverdier/zsh-git-prompt) - 针对 Zsh 的 Git 信息提示符
* [zsh-history-substring-search](https://github.com/zsh-users/zsh-history-substring-search) - 针对 Zsh 实现的 Fish shell 的历史搜索功能
* [zshmarks](https://github.com/jocelynmallon/zshmarks) - 针对 oh-my-zsh 的 Bashmarks 移植（由 Todd Werth 编写的简单书签插件）
* [zsh-notify](https://github.com/marzocchi/zsh-notify) - 适用于在 Zsh 中长时运行命令的桌面通知
* [zsh-prompt-powerline](https://github.com/Valodim/zsh-prompt-powerline) - 基于 powerline 字体（来自流行的 Vim 插件）的 Zsh 提示符
* [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) - 针对 Zsh 的类 Fish shell 语法着色功能


# 指南

* [Bash 黑客的维基](http://wiki.bash-hackers.org/)
* [Greg Wooledge 的 (又名 "greycat") 维基](http://mywiki.wooledge.org)：尤其是 [Bash 指南](http://mywiki.wooledge.org/BashGuide)、[Bash 疑难问答](http://mywiki.wooledge.org/BashFAQ) 及 [Bash 陷阱](http://mywiki.wooledge.org/BashPitfalls)
* [Google 的 Shell 风格指南](https://google-styleguide.googlecode.com/svn/trunk/shell.xml)
* [Linux 文档项目: Bash 编程 - 简介/如何做](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [Linux 文档项目: 高级 Bash 脚本指南](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell 脚本](http://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [使用非官方的 Bash 严格模式 (除非你爱调试)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [命令行的艺术](https://github.com/jlevy/the-art-of-command-line)


# 其它 Awesome 清单

其它很棒的 awesome 清单可在 [awesome-awesome](https://github.com/emijrp/awesome-awesome) 和 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 找到。
