# Bash-Scripting
### To add this permission to a file with filename: script.sh
```bash
chmod +x script.sh
```
### The beginning of your script file should start with #!/bin/bash on its own line.
```bash
#!/bin/bash
```
# To ensure that scripts in ~/bin/ are available
```bash
PATH=~/bin:$PATH
```
### On Linux style shells, this is ~/.bashrc 
### On OSX, this is ~/.bash_profile.
### 在 macOS Catalina 之後，預設的 shell 已經從 bash 改為了 zsh
```bash
nano ~/.zshrc
```
### 加入到末行
```bash
export PATH=~/bin:$PATH
```
### 重新載入
```bash
source ~/.zshrc
```

