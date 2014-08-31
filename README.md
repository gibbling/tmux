Installation:
	
	mkdir ~/.tmux
	git clone https://github.com/gibbling666/tmux.git ~/.tmux
	ln -s ~/.tmux/tmux.conf ~/.tmux.conf

If on  osx this config with fail to execute tmux as its setup to utilize reattach-to-user-namespace.
It will need to be installed via

	brew install reattach-to-user-namespace
