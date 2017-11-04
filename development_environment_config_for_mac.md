# mac开发环境设置

## 启用zsh

1. 先切换到 `/bin/zsh`

	```bash
	chsh -s /bin/zsh
	```
2. 默认的zsh配置不太友好，我们下载一个github上别人配置好的文件

	```bash
	git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
	```
	
3. 替换~/.zshrc

	```bash
	# 备份
	cp ~/.zshrc ~/.zshrc.orig
	# 替换
	cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
	```
4. 重启terminal

## 安装Homebrew

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

> 安装brew千万不要用sudo执行,不然文件权限都是root的,以后用起来也得加sudo执行.
