# chof64/dotfiles

dotfiles contains a bunch of configuration files used across different parts of
development.

## Disclaimer and License

Use these at your own risk without any warranty or guarantees. These configs
works for me, but doesn't necessarily mean that it might work on your setup
due to a lot of factors. Use with caution and always double check.

**chof64/dotfiles** is licensed under [MIT License](LICENSE).

## Usage

dotfiles is usually used by copy and pasting the configs. Another way of using
dotfiles is by cloning the repository and symlinking it to the location of the
project you're working on.

### Using dotfiles via symlinking

Create a symlink from dotfiles to your project location using the following
code:

```zsh
ln -s ~/source/dotfiles/dirs/... ~/path/to/project/...
```

If you need to update your symlink, you first need to delete the existing
symlink and recreate it:

```zsh
rm ~/path/to/project/...
ln -s ~/source/dotfiles/dir/... ~/path/to/project/...
```

### Using dotfiles by manually copy and pasting it

I think you need no explaination or instructions on how to copy and paste.

## Things in the plans

- Consider using as git submodules, but optionally pull it to prevent bloated
local codebase.
