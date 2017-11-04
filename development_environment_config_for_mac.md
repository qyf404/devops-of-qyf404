# mac开发环境设置

## 启用zsh

1. 先切换到 `/bin/zsh`

	```
	chsh -s /bin/zsh
	```
2. 默认的zsh配置不太友好，我们下载一个github上别人配置好的文件

	```
	git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
	```
	
3. 替换~/.zshrc

	```
	# 备份
	cp ~/.zshrc ~/.zshrc.orig
	# 替换
	cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
	```
4. 重启terminal
