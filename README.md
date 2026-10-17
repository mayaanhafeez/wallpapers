# wallpapers

Wallpapers grouped by theme. Each folder name matches a
[`set-theme`](https://github.com/mayaanhafeez/set-theme) theme, which picks a random
image from `~/Pictures/wallpapers/<theme>/` when the theme is applied. `unsorted/`
holds everything not yet assigned to a theme.

Checked out as a submodule of my dotfiles repo and symlinked into place:

```sh
ln -s ~/dotfiles/wallpapers ~/Pictures/wallpapers
```

The same image often appears in several theme folders. Git stores identical files
once, so the duplicates cost nothing in the repository.
