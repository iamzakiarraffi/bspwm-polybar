# bspwm-polybar
this version isn't vanilla of bspwm this repo is full of mods and other script that i had work for last two month.
feel free to mods my project, to make your own version of bspwm/sxhkd
right now i'm currently working for building my own version of Qtile which is 100% written in python language.
*bspwm is a tiling window manager that represents windows as the leaves of a full binary tree.
*URL selecting/launching in browser similiar to vimperator's mark mode and the urxvt script.
My only problem with this is that in order for the lock screen to be effective, I need to quit sxhkd to prevent people from simply closing the window containing cmatrix/vlock. I have added pkill sxhkd to the chain of commands and that works. The broken part is starting sxhkd back up again. Simply tacking sxhkd on to the end doesn't work as the terminal window won't close until sxhkd finishes, which is never. In addition, if the terminal window is closed, sxhkd stops because it was running in it.
However, this can be done by a simple shortcut in dwm/or any dynamics tilling windows managers, which will launch your plumber on the current select buffer. St has easy select through double-click.

 **Cloning**
 
Execute these commands:

	git clone <a href="https://github.com/baskerville/bspwm.git" rel="nofollow">https://github.com/baskerville/bspwm.git</a>
	git clone <a href="https://github.com/baskerville/sxhkd.git" rel="nofollow">https://github.com/baskerville/sxhkd.git</a>

cd to directory

And the Compile eithin each directory

	sudo make && clean install
	
Copy Config Files

First we will make a directory to copy the base configuration files for bspwm and sxhkd.

To make the directory:

	mkdir /home/$USER/.config/bspwm
	
To copy the files:

	mv /bspwm/examples/bspwmrc /home/(your username here)/.config/bspwm/bspwmrc

chmod the config

	chmod +x /home/(your user name here)/.config/bspwm/bspwmrc
	
Do the same with sxhkd.

**Keybindings**

Now to properly use bspwm, you will need to modify the keybindings to your liking.
for editing the _sxhkdrc_. To access this file, open the file using your chosen editor.

*nano/vim/vim/kate/vscode

	vim /home/$USER/.config/sxhkd/sxhkdrc


###
dunst      https://github.com/dunst-project/dunst
polybar    https://github.com/polybar/polybar
sxhkd      https://github.com/baskerville/sxhkd
bspwm      https://github.com/baskerville/bspwm
st         https://st.suckless.org/
###
