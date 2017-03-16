# Sublime

### Gosublime (Golang plugin collection)
- https://github.com/DisposaBoy/GoSublime

### Jump to definition
- use [buaazp/godef](https://github.com/buaazp/Godef) package
- setup key binding
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