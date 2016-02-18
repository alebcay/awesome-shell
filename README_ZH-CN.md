# Awesome Shell [![Awesome][awesome-badge]][awesome-link]

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
- [**Awesome Zsh**][awesome-zsh]&nbsp; [![Awesome][awesome-badge]][awesome-zsh]
- [**Awesome Fish**][awesome-fish] [![Awesome][awesome-badge]][awesome-fish]
- [指南](#指南)
- [其它 Awesome 清单](#其它-awesome-清单)


# Awesome Bash


## 命令行效率

*使你的终端体验更有效率的搜索、书签、多路复用、以及其它工具。*

* [ag](https://github.com/ggreer/the_silver_searcher) - 在层级目录中超快的搜索字符串
* [autoenv](https://github.com/kennethreitz/autoenv) - 基于目录的环境
* [autojump](https://github.com/wting/autojump) - 自带学习功能的 cd 命令，从命令行轻易地导航目录
* [bashmarks](https://github.com/huyng/bashmarks) - 适用于 shell 的目录书签
* [bd](https://github.com/vigneshwaranr/bd) - 迅速回到父目录
* [boilr](https://github.com/tmrts/boilr) - 从 boilerplate 模板创建项目的超快命令行工具
* [boom](https://github.com/holman/boom) - 在命令行中存储链接及片断
* [byobu](http://byobu.co/) - 基于文本的窗口管理器及终端多路复用器
* [commacd](https://github.com/shyiko/commacd) - 在 Bash 中更快速的移动方式
* [desk](https://github.com/jamesob/desk) - 适用于 shell 的轻量级工作区管理器
* [direnv](https://github.com/direnv/direnv) - 针对 shell 的环境切换工具（利用 autoenv 比较）
* [enhancd](https://github.com/b4b4r07/enhancd) - :rocket: 具有交互式过滤功能的下一代 cd 命令
* [fasd](https://github.com/clvv/fasd) - 命令行效率提升器，提供快速访问文件及目录
* [fzf](https://github.com/junegunn/fzf) - 命令行下的模糊搜索器
* [hhighlighter](https://github.com/paoloantinori/hhighlighter) - 在命令输出中给单词着色
* [hr](https://github.com/LuRsT/hr) - 适用于终端的 `<hr />`
* [hstr](https://github.com/dvorka/hstr) - Bash 历史建议框
* [k](https://github.com/supercrabtree/k) - k 是一个使目录列表更可读的 Zsh 脚本，它增添了 Git 状态、文件颜色、以及腐朽的日期
* [marker](https://github.com/pindexis/marker) - 将你的 shell 命令加到书签
* [parallel](http://www.gnu.org/software/parallel/) - 以并行化方式从标准输入构造并执行 shell 命令行
* [pathpicker](https://github.com/facebook/PathPicker) - 允许将 grep、搜索、git 等的输出结果作为输入，并提供友好的选择界面，以便打开或作为命令的参数
* [percol](https://github.com/mooz/percol) - 为传统的 UNIX shell 管道添加交互式的过滤
* [qfc](https://github.com/pindexis/qfc) - 针对 Bash 和 Zsh 的文件补全 widget
* [SHML](https://github.com/MaxCDN/shml) - 适用于终端的样式框架 (Shell 标记语言)
* [slugify](https://github.com/benlinton/slugify) - 将文件名及目录转换为 web 友好的格式
* [spark](https://github.com/holman/spark) - ▁▂▃▅▂▇ 在你的 shell 中
* [spot](https://github.com/rauchg/spot) - 微型的文件搜索工具
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
* [bullet-train-oh-my-zsh-theme](https://github.com/caiogondim/bullet-train-oh-my-zsh-theme) - :bullettrain_side: 基于 Powerline Vim 插件的 oh-my-zsh shell 主题
* [emojify](https://github.com/mrowa44/emojify) - 适用于命令行的表情 :scream:
* [flatui-terminal-theme](https://dribbble.com/shots/1021755-Flat-UI-Terminal-Theme) - 很好的终端颜色主题
* [git-prompt](https://github.com/lvv/git-prompt) - 包含 Git、SVN 及 HG 模块的 Bash 提示符
* [gittify](https://github.com/momeni/gittify) - 彩色的 Bash 提示符及定制的 Git 别名
* [Gogh - Color Scheme](https://github.com/Mayccoll/Gogh) - 适用于 GNOME 终端的颜色主题
* [liquidprompt](https://github.com/nojhan/liquidprompt) - 针对 Bash 和 Zsh 的全功能及用心设计的自适应提示符
* [mysql-colorize](https://github.com/horosgrisa/mysql-colorize.bash) -  彩色的 MySQL 命令行客户端
* [oh-my-git](https://github.com/arialdomartini/oh-my-git) - 针对 Bash 和 Zsh 的自用 Git 提示符
* [sexy-bash-prompt](https://github.com/twolfson/sexy-bash-prompt) - 包含颜色、Git 状态及 Git 分支的 Bash 提示符

## 针对开发者

*命令行开发、版本控制、以及部署。*

* [bocker](https://github.com/p8952/bocker) - 使用百行 bash 实现的 Docker
* [cloc](https://github.com/AlDanial/cloc) - 统计代码行数
* [dokku](https://github.com/dokku/dokku) - 百行 Bash 打造的 Docker 迷你 Heroku
* [dokku-alt](https://github.com/dokku-alt/dokku-alt) - dokku 的 fork 版本，它利用覆盖最稳定的使用案例及测试良好的插件来提供完整的解决文案
* [git-extra-commands](https://github.com/unixorn/git-extra-commands) - 很多 Git 扩展工具，包括 churn、cut-branch、improved-merge 等
* [git-extras](https://github.com/tj/git-extras) - Git 工具，包括仓库摘要、repl、更改日志人数、作者提交百分比等
* [git-open](https://github.com/paulirish/git-open) - 输入 `git open` 在浏览器中打开 GitHub 页面或仓库网站
* [git-semver](https://github.com/markchalloner/git-semver) - 用来方便的语义化版本及更改日志验证的 Git 插件
* [git-sh](https://github.com/rtomayko/git-sh) - 适合 Git 工作的定制 Bash 环境
* [git-up](https://github.com/aanand/git-up) - 自动变基进来的更改代替合并，优雅！
* [hub](https://github.com/github/hub) - 更易使用 GitHub 的命令行工具
* [mr](https://github.com/joeyh/myrepos) - 多仓库管理工具
* [overcommit](https://github.com/brigade/overcommit) - 完全可配置且可扩展的 Git hook 管理器
* [pre-commit](http://pre-commit.com) - 用于管理及维护多语言 pre-commit hooks 的框架
* [repren](https://github.com/jlevy/repren) - 命令行搜索与替换及文件重命名的瑞士军刀式工具
* [slap](https://github.com/slap-editor/slap) - 运行在 Node.js 上的基于终端的类 Sublime 文本编辑器
* [shipit](https://github.com/sapegin/shipit) - 极简 SSH 部署

## 系统工具

*操作系统相关工具，包括系统管理、系统调试、及文件和进程管理。*

* [atop](http://www.atoptool.nl) - 能够报告所有进程活动的 ASCII 全屏性能监视器
* [cv](https://github.com/Xfennec/progress) - 显示 cp、rm、dd 等命令进度的 Linux 工具
* [glances](https://github.com/nicolargo/glances) - 系统监视之眼
* [goaccess](https://github.com/allinurl/goaccess) - 运行于 \*nix 系统终端中的实时 web 日志分析器及交互式查看器
* [htop](https://github.com/hishamhm/htop) - 基于 ncurses 的交互式进程查看器，其目标是比 `top` 更好
* [lnav](http://lnav.org) - 小型的高级日志文件查看器
* [lsp](https://github.com/dborzov/lsp) - 改进的 `ls`，包含无格式语言的文件说明及智能的文件分组
* [mtr](https://github.com/traviscross/mtr) - traceroute 和 ping 功能合二为一的网络诊断工具
* [ncdu](https://dev.yorhel.nl/ncdu) - NCurses 磁盘占用统计
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
* [httpie](https://github.com/jkbrzt/httpie) - HTTPie 是一个命令行 HTTP 客户端，用户友好的 cURL 替代品
* [ngincat](https://github.com/jaburns/ngincat) - 使用 netcat 的微型 Bash HTTP 服务器
* [resty](https://github.com/micha/resty) - 你可以在管道中使用的小型命令行 REST 客户端
* [youtube-dl](https://github.com/rg3/youtube-dl) - 从 YouTube.com 及其它视频站点下载视频的小命令行程序

## 多媒体与文件格式

*用于处理视频及音频文件的工具。*

* [adb-export](https://github.com/sromku/adb-export) - 导出 Android 内容提供商为 CSV 格式
* [Android-Kitchen](https://github.com/dsixda/Android-Kitchen) - 基于文本的 Android ROM 定制 kitchen，使用 shell 脚本并支持 Cygwin/OS X/Linux
* [Beets](https://github.com/beetbox/beets) - 音乐库管理器及 MusicBrainz 标签工具
* [cmus](https://github.com/cmus/cmus) - 跨平台的命令行音乐播放器
* [image-scraper](https://github.com/sananth12/ImageScraper) - 包含诸多特性的酷命令行图像 scraper
* [jq](https://github.com/stedolan/jq) - 针对 json 数据的 Sed，你可以使用它分片、过滤、映射及变换结构化数据
* [mplayer](http://www.mplayerhq.hu/design7/news.html) - 让你在 shell 中播放主流的音频及视频格式（使用 ASCII 字符）
* [PiCAST](https://github.com/lanceseidman/PiCAST) - PiCAST 将你的 35 刀 Raspberry Pi 变成类 Chromecast 设备
* [sejda](https://github.com/torakiki/sejda/) - 命令行下的 PDF 文档处理工具（分割、合并、旋转、转换为 jpg、提取文本等）
* [xmlstarlet](http://xmlstar.sourceforge.net/) - 古老而强大的命令行 XML 格式化、过滤及处理工具

## 应用程序

*基于命令行的应用程序或从命令行访问现有服务。*

* [ansiweather](https://github.com/fcambus/ansiweather) - 终端中的天气预报，包含 ANSI 颜色及 Unicode 符号
* [bashblog](https://github.com/cfenollosa/bashblog) - 处理 blog 投递的 Bash 脚本
* [choosealicense-cli](https://github.com/lord63/choosealicense-cli) - 把 http://choosealicense.com 带到你的终端
* [facy](https://github.com/huydx/facy) - 命令行下的 Facebook 客户端
* [geeknote](https://github.com/VitaliyRodnenko/geeknote) - 命令行的 Evernote 客户端
* [iponmap](https://github.com/nogizhopaboroda/iponmap) - 利用 IP 地址在世界地图上绘点
* [isitup](https://github.com/lord63/isitup) - 检查一个网站是否正常上线
* [jrnl](https://github.com/maebert/jrnl) - 使用无格式文本文件存储日记的简单命令行程序
* [ledger](https://github.com/ledger/ledger) - 命令行记账
* [licen](https://github.com/lord63/licen) - 生成项目 license
* [pushblast](https://github.com/alebcay/pushblast) - 当 shell 程序退出时获得 PushBullet 通知
* [pushbullet-bash](https://github.com/Red5d/pushbullet-bash) - PushBullet API 的 Bash 接口
* [SAWS](https://github.com/donnemartin/saws) - 超强的 AWS 命令行界面
* [transfer.sh](https://transfer.sh/) — 从 shell 快速上传并分享文件
* [wego](https://github.com/schachmat/wego) - 适用于终端的天气预报应用
* [fanyi](https://github.com/afc163/fanyi) - 翻译英文为中文的命令行工具

## 游戏

*只顾工作而不玩玩是一种糟糕的度日方式。*

* [bash2048](https://github.com/mydzor/bash2048) - 2048 游戏的 Bash 实现
* [minesweeper](https://github.com/feherke/Bash-script/tree/master/minesweeper) - 扫雷的 Bash 实现
* [sedtris](https://github.com/uuner/sedtris) - 使用 sed 实现的俄罗斯方块
* [sed-scripts](https://github.com/aureliojargas/sed-scripts) - 使用 sed 编写的 Arkanoid 和 Sokoban

## Shell 包管理

*用于管理多个 shell 配置的工具。对于特定的 zsh 工具，参阅 Zsh 节。*

* [bash-it](https://github.com/Bash-it/bash-it) - 社区化的 Bash 框架
* [basher](https://github.com/basherpm/basher) - 针对 shell 脚本的包管理器
* [bpkg](http://www.bpkg.io/) - JavaScript 有 npm、Ruby 有 Gems、Python 有 pip，现在 Shell 有 bpkg
* [dotfiler](https://github.com/svetlyak40wt/dotfiler) – 使用 Python 编写的基于 Git 的 Shell dotfiles 管理器
* [fresh](https://github.com/freshshell/fresh) - 使你的 dotfiles 保持更新
* [homeshick](https://github.com/andsens/homeshick) - 使用 Bash 编写的 Git dotfile 同步器
* [vcsh](https://github.com/RichiH/vcsh) - 基于 Git 的配置管理器

## Shell 脚本开发

*用于编写、改进、及管理 Bash 或其它 shell 脚本的工具。*

* [ansi](https://github.com/fidian/ansi) - 使用纯 Bash 实现的 ANSI 转义码，包括更改文本颜色、定位光标等等
* [assert.sh](https://github.com/lehmannro/assert.sh) - Bash 单元测试框架
* [bashful](https://github.com/jmcantrell/bashful) - 简化编写 Bash 脚本的库收集
* [bashmanager](https://github.com/lingtalfi/bashmanager) - 用来创建命令行工具的微型 Bash 框架
* [bats](https://github.com/sstephenson/bats) - Bash 自动化测试系统
* [composure](https://github.com/erichs/composure) - 撰写、文档、版本、及组织你的 shell 函数
* [dispatch](https://github.com/Mosai/workshop/blob/master/doc/dispatch.md) - 使用 50 行可移植 shell 脚本写成的命令行参数解析器
* [mo](https://github.com/tests-always-included/mo) - 使用纯 Bash 实现的 Mustache 模板
* [rerun](https://github.com/rerun/rerun) - 用来管理保留脚本的模块化 shell 自动化框架
* [semver_bash](https://github.com/cloudflare/semver_bash) - 使用 Bash 实现的语义化版本
* [shellcheck](https://github.com/koalaman/shellcheck) - 针对 shell 脚本的静态化分析工具
* [shpec](https://github.com/rylnd/shpec) - shell 测试框架
* [sub](https://github.com/basecamp/sub) - 以美味之道来管理程序
* [ts](https://github.com/thinkerbot/ts) - shell 测试脚本
* [shunit2](https://github.com/kward/shunit2) - 适用于 Bash 脚本的单元测试框架（具有 JUnit/PyUnit 风味）


# 指南

* [Bash 黑客的维基](http://wiki.bash-hackers.org/)
* [Greg Wooledge 的 (又名 "greycat") 维基](http://mywiki.wooledge.org)：尤其是 [Bash 指南](http://mywiki.wooledge.org/BashGuide)、[Bash 疑难问答](http://mywiki.wooledge.org/BashFAQ) 及 [Bash 陷阱](http://mywiki.wooledge.org/BashPitfalls)
* [Google 的 Shell 风格指南](https://google-styleguide.googlecode.com/svn/trunk/shell.xml)
* [Linux 文档项目: Bash 编程 - 简介/如何做](http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc)
* [Linux 文档项目: 高级 Bash 脚本指南](http://www.tldp.org/LDP/abs/html/)
* [WikiBooks: Bash Shell 脚本](https://en.wikibooks.org/wiki/Bash_Shell_Scripting)
* [使用非官方的 Bash 严格模式 (除非你爱调试)](http://redsymbol.net/articles/unofficial-bash-strict-mode/)
* [命令行的艺术](https://github.com/jlevy/the-art-of-command-line)


# 其它 Awesome 清单

其它很棒的 awesome 清单可在 [awesome-awesome](https://github.com/emijrp/awesome-awesome) 和 [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) 找到。


[awesome-zsh]: https://github.com/unixorn/awesome-zsh-plugins
[awesome-fish]: https://github.com/bucaran/awesome-fish
[awesome-link]: https://github.com/sindresorhus/awesome
[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
