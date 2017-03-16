# Sublime

### Gosublime (Golang plugin collection)
- https://github.com/DisposaBoy/GoSublime

# jump to definition
    - use [buaazp/godef](https://github.com/buaazp/Godef) package
    - setup key binding
```
[
    { "keys": ["super+.", "super+g"], "command": "gohelper_godef" },
	{ "keys": ["super+option+h"], "command": "godef" },
	{ "keys": ["super+option+k"], "command": "jump_forward"},
	{ "keys": ["super+option+j"], "command": "jump_back"}
]
```
