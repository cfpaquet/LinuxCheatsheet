# LinuxCheatsheet

### Wayland or X?

```
echo $XDG_SESSION_TYPE

loginctl show-session $(loginctl show-user $(whoami) -p Display --value) -p Type --value
```
