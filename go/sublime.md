# Sublime

Use Sublime as the golang IDE. There are a little packages can be used to improve the efficiency of developing golang in Sublime.
### Gosublime (Golang plugin collection)
- Use [DisposaBoy/GoSublime](https://github.com/DisposaBoy/GoSublime) package

### Jump to definition
- Use [buaazp/godef](https://github.com/buaazp/Godef) package
- Setup key binding
    - use `cmd+option+h` to go to definition
    - use `cmd+option+j` and `cmd+option+k` to jump between the postions 

```
[
    { "keys": ["super+.", "super+g"], "command": "gohelper_godef" },
    { "keys": ["super+option+h"], "command": "godef" },
    { "keys": ["super+option+k"], "command": "jump_forward"},
    { "keys": ["super+option+j"], "command": "jump_back"}
]
```

### Build on save
- Use [slene/GoHelper](https://github.com/slene/GoHelper) package
- No need more things to do and just clone git repository
```
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/
git clone git@github.com:slene/GoHelper.git
```
- Double press `cmd+s` to trigger

### 