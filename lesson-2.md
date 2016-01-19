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

Go to normal mode and save the file, then restart vim.

## Navigate to a specific line

Open vimrc file and go to insert mode.  Add a bunch of lines with the
enter key.  Go to normal mode, choose a line number far from the cursor,
say 52, and do:

```
52G
```

## Navigate to a specific position on a line

Go to the top of the file where the "set number" command is.  Go to the
beginning of the line, then go to the letter "e" with:

```
fe
```

## Navigate to the next instance of the same letter on a line

```
;
```

## Navigate backward on a line

```
Fe
```

## Navigate again in the same direction

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
