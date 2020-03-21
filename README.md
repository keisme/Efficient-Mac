# Efficient-Mac
Make mac more efficient

## 目录
- [Softwares](#Softwares)
- [Mac Shortcuts](#Mac-Shortcuts)
- [Xcode Shortcuts](#Xcode-Shortcuts)
- [Git Config](#Git-Config)
- [Vim Config](#Vim-Config)
- [Xcode](#Xcode)

## Softwares

- [Typora](https://www.typora.io/)：MarkDown 编辑器（主题：[Lostkeys](https://theme.typora.io/theme/Lostkeys/)）
- [Charles](https://www.charlesproxy.com/)：网络抓包
- [Dash](https://kapeli.com/dash)：查阅 API 文档和同步代码片段
- [Google Drive](https://www.google.com/drive/)：云端同步与存储
- [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) + [solarized](https://github.com/altercation/solarized)：终端[配置](https://keisme.cn/Mac-%E7%BB%88%E7%AB%AF%E9%85%8D%E7%BD%AE%EF%BC%9Aoh-my-zsh-Solarized-%E9%85%8D%E8%89%B2%E6%96%B9%E6%A1%88.html)
- [GIPHY Capture](https://giphy.com/apps/giphycapture)：制作 gif/mp4
- [CheetSheet](https://www.mediaatelier.com/CheatSheet/)：快速查看任意应用的快捷键
- [iStat Menus](https://bjango.com/mac/istatmenus/)：系统监测
- [PaintCode](https://www.paintcodeapp.com/)：将设计图直接转换成代码
- [IINA](https://lhc70000.github.io/iina/zh-cn/)：视频播放器
- [Downie](https://software.charliemonroe.net/downie.php)：下载视频网站的视频
- [The Unarchiver](https://theunarchiver.com/)：解压工具
- [Network Link Conditioner](https://developer.apple.com/download/more/?q=Additional%20Tools)：网速模拟工具
- [Commitizen](https://github.com/commitizen/cz-cli)：使 git commit 提交更规范
- [Homebrew](https://brew.sh/index_zh-cn)：方便的包管理工具

## Mac Shortcuts

## [Xcode Shortcuts](https://kapeli.com/cheat_sheets/Xcode_Shortcuts.docset/Contents/Resources/Documents/index)

## Git Config

### .gitconfig

```markdown
[alias]
	lg = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'

[core]
	excludesfile = ~/.gitignore_global
	
[user]
	name = <name>
	email = <email>
```

### .gitignore_global

```markdown
# .gitignore_global

.DS_Store
.DS_Store?
*.DS_Store
*/.DS_Store

*/.xcuserstate
*.xcuserstate
```

### .gitignore
[Swift.gitignore](https://github.com/github/gitignore/blob/master/Swift.gitignore)

### 指定项目 author

在项目文件`.git/config`中按照上 面的全局配置重写`[user]`即可。

## Vim Config

路径：

```
~/vimrc
```

配置：

```
syntax on
set number
set ruler
set shiftwidth=4
set softtabstop=4
set tabstop=4
set cursorline
hi CursorLine   cterm=NONE ctermbg=blue ctermfg=white guibg=blue guifg=white
set hlsearch
```



## Xcode

### Theme Path

```
~/Library/Developer/Xcode/UserData
```







