# Bash-Scripting setting
### To add this permission to a file with filename: script.sh
```bash
chmod +x script.sh
```
### The beginning of your script file should start with #!/bin/bash on its own line.
```bash
#!/bin/bash
```
### To ensure that scripts in ~/bin/ are available, you must add this directory to your PATH within your configuration file
```bash
PATH=~/bin:$PATH
```
### On Linux style shells, this is ~/.bashrc 
### On OSX, this is ~/.bash_profile.
### 在 macOS Catalina 之後，預設的 shell 已經從 bash 改為了 zsh
### 更改path
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
# 簡單指令
### 輸出文字
```bash
echo "Hello World!"
```
