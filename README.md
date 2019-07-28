# Linux-commands
Most usefull Linux commands in day to day work

## List all open ports

### bash
``` lsof -i | grep LISTEN ```
### powershell
`netstat -an | select-string -pattern "listening"`



