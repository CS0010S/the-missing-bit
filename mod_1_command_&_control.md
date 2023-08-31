# Unit 1 - Why Learn the Terminal?
- motivation: be able to command and control a computer
- experience at NUS
- 24 basic commands to learn about

# Unit 2 - Where am I?
- at NUS, where else?
- `pwd`, `ls`, `man`
- arguments (e.g. `ls -a`, `ls -la`)
- home directory `~`
- command history

# Unit 3 - Moving About
- hierarchical file systems still matter!
- `cd <path>`
- paths, absolute and relative
- `cd .`, `cd ..`, `cd ~`, `cd`
- tab auto complete
- `cp <path1> <path2>`, `mv <path1> <path2>`

# Unit 4 - Making Things
- touch me!
- `touch <path>`
- redirection (> overwrite or >> append) (e.g. `echo "hello" > <path>`, `echo "world" >> <path>`)
- `cat <path>`, `head <path>`, `tail <path>`
- interactive mode (e.g. `less <path>`)

# Unit 5 - Removing Things
- measure twice, cut once, or lose it all!
- `rm <path>`, `rmdir <path>`
- recursive operations
- `rm -Rf <path>`

# Unit 6 - Processing Text
- it's not VS Code, but it works in a pinch
- `nano <path>`
- patterns (e.g. `grep '^hell' <path>`, `grep 'hell*' <path>`, `grep 'hello' *`) 
- pipes (e.g. `grep 'hello' filename | wc -l`, `grep 'hello' * | wc -l`, `grep 'hello' . | wc -l`)
- `sort`, `uniq`

# Unit 7 - Far from ~
- take over the world!
- `ssh`, `scp`, `curl`, `wget`

# Unit 8 - Going further
- terminal customisation
- package manager
- coding with python, node, etc
