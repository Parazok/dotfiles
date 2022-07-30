### first clone this project
### then make links from here to your folder or simply copy pase:

ln -s ~/w/projects/dotfiles/i3/i3blocks ./i3blocks
ln -s ~/w/projects/dotfiles/i3/i3 ./i3

### then install thease packages:
sudo apt install i3blocks nitrogen lm-sensors go maim -y

### then run this command for jalali date
go get -u -v github.com/NightMachinary/jalalicli

### then restart i3 using this command:
i3-msg restart


#### if bad touchbar use this command to find properties then override i3/config
synclient -l

#### if you want to update blocks for your i3block you can use this repository to update them:
https://github.com/vivien/i3blocks-contrib.git
