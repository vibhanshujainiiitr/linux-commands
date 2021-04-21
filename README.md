# LINUX COMMANDS
This is just a placeholder of my favorite linux commands.<br><br>

## Cloning a website
This command is used to clone a website in your local system with all it's files.<br>
``` wget -r -np -k https://vibhanshujainiiitr.github.io ```

## Compiling Markdown file
This command is used the view the .md file in the browser<br>
``` grip -b file.md ```

## Connecting to Wireguard VPN
This command is used to create connection using wireguard VPN to access INTRANET<br>
``` sudo wg-quick up wg0 ```
<br>
This command is used to close connection in wireguard VPN<br> 
```  sudo wg-quick down wg0 ```<br>

# Arch Linux

## Installing from .tar
``` sudo pacman -U name.tar.*```

## Adding ssh key to agent in Fish
``` eval 'ssh-agent -s'```
