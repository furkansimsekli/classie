# classie
Sometimes I become a miserable person while looking for the meeting url on the endless www, especially if I just woke up

## How To
0. Download the repository
1. Give executing permission to classie with `chmod +x classie`
2. Initialize the config file (meetings) at the `.config/classie` with `./classie --init`
3. Run with `./classie <meeting name>`

Example .meetings file
```
cs101 https://us04web.zoom.us/j/691438
math102 https://us06web.zoom.us/j/15191618525
phys201 https://us04web.zoom.us/j/811815124
chem153 https://meet.google.com/se-inf-eld
hist147 https://teams.microsoft.com/l/meetup-join/somecrappyteamsurlidk
```

There is an also pre-written .meetings file for Hacettepe CS 2022 Spring classes.
1. Decode the file with `./classie --hucs`
2. Run with `./classie bbm202`

## Suggestion
If you prefer to use classie more conveniently, you can place the script in a directory that is in the path, such as `~/.local/bin`, and then use it by simply typing `classie cs101`.
