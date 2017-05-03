# cheatsheet
# for a faster bundler performance with parallel gem install support:
`bundle config --global jobs 2`
# to make homebrew vim linked instead of system vim
Boot your mac* with CMD+R, then in terminal execute `csrutil disable` and then reboot.

Open terminal and execute `sudo mv /usr/bin/vim /usr/bin/vim74`, then again boot your mac* with CMD+R, then in terminal execute `csrutil enable`.
# make CMD+1 and CMD+2 works for tab switching in Terminal app
System Preferences >> Keyboard >> Shortcuts >> App Shortcuts >> +

`Show Previous Tab - CMD+1`

`Show Next Tab - CMD+2`
# change priority of paths
`sudo vim /etc/paths`
# SSH key generate and copy to clipboard
`ssh-keygen`

`pbcopy < ~/.ssh/id_rsa.pub`
# show number of lines
`nl hebe`
# du hast- sizes
du -h
