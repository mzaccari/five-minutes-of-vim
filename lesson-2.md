## Start a config file

```
mkdir -p ~/.config/vim
ln -sf ~/.config/vim/vimrc ~/.vimrc
vim ~/.config/vim/vimrc
```

## Turn on line numbering

Go to insert mode and add:

```
set number
```

Go to normal mode and save the file, then exit and restart vim.

## Navigate to a specific line

Open the vimrc file and go to insert mode.  Add a bunch of lines with
the enter key.  Go to normal mode, choose a line number far from the
cursor, say 52, and do:

```
52G
```

## Navigate to a specific position on a line

Go to the line which says "set number". Then "find" the letter "e" with:

```
fe
```

## Find the next instance of the same letter on a line

```
;
```

## Find backward on a line

```
Fe
```

## Find again in the same direction

```
;
```

## Go to the beginning of a line

```
0
```

## Go to the end of a line

```
$
```
