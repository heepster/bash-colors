# Bash Colors

A bash script to export color variables.

I use this in my .bash_profile like so:

```
if [ -f ~/.bash-colors ]; then
  source ~/.bash-colors
fi

# Prompt with working directory in purple
PS1="${PURPLE}\W${NO_COLOR}"
```

$NO_COLOR is used to negate the previous color.
