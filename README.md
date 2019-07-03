# Description
Personal fork of [slstatus](https://tools.suckless.org/slstatus/) for use with `dwm` and `st`

## Configuration

Add the following lines of code to your `.xinitrc`file:

```
while true; do
  slstatus
done &
exec dwm
```
