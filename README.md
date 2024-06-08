# hacker-lab

## Tools
- Threat Dragon
- Wire Shark
- Dot files
- UTM based on QEMU


## Tools on machine
- Obsidian
- VS code
- Oh my zsh
- Wireshark
- Air snort
- Object-See [project](https://objective-see.org/tools.html)
	- [Lulu](https://objective-see.org/) for firewall
- Threat Dragon

## Github personal access token renewal
Stackoverflow [explanation](https://stackoverflow.com/questions/67646383/authentication-to-github-using-personal-access-token-on-macos)

1. Go into Github and regenerate another token
2. Erase your old token
```text
git credential-osxkeychain erase
host=github.com
protocol=https
```
2. Do a push and enter your username and token for the password