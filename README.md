My own Git cheat sheet

## Commands

### Text
- `ci"` to change between quotes. Works with ", ', `, < etc.
- `cit` to change between tags
- Works with `d` as well	
- `*` to search for word under cursor

#### Case

Append a movement (`e`, `$`, etc) to each of these commands

- `g~` to toggle case
- `gU` to go uppercase
- `gu` to go lowercase

### Misc.

- `cd %:p:h` to cd across session
- `lcd %:p:h` to cd for current window


### Splits

- `vsplit` or `vs` for vertical split
- `split` `sp` for horizontal split

- Prefix with a number, e.g. `10sp` to specify width/height


## netrw (file explorer)

Open netrw in cwd

	:edit.
    :e.

Open netrw in dir of current file
	
	:Explore. 
    :E.

Up one level while in netrw

    -
    
Split and open netrw 

- `:Sex` open netrw in horisontal split
- `:Vex` open netrw in vertical split
- `%` New file
- `d` New directory
- `R` Rename
- `s` Change sort

See [vinegar](https://github.com/tpope/vim-vinegar)-spesific shortcuts.




## Plugins

### "Currently" used
- [vinegar](https://github.com/tpope/vim-vinegar)

### To try out

- vim airline
- fugitive
- syntastic (incl. syntastic-react)
- ctrl+p or similar
- matchtagalways
- vim matchit
- vim autoclose
- closetag
- NERDCommenter

## resources

- [tilvim](http://tilvim.com/)
- [vimcasts](http://vimcasts.org/)
- [vimawesome](http://vimawesome.com/)
