## Steam Library Art

This repo exists to accomodate sharing of covers for the [New Steam Library](https://store.steampowered.com/libraryupdate).

Only high-quality covers in size 600x900 are accepted in here; covers for games missing official art is preferred.

### How do I use this?

You need to install `git` and `git-lfs` packages from your Linux distro, then:

    $ git lfs install
    $ git clone https://github.com/dreamer/steam-library-art.git
    $ cd steam-library-art
    $ ./link-steam-grid

That's it - after Steam restart all covers should be updated.

### New covers showed up in the repo! How can I update?

    $ cd steam-library-art
    $ cd git pull

And restart Steam - all new covers will be picked up automatically.

### How can I contribute my cover art?

GitHub's default pull-request workflow is broken when using [Git LFS](https://git-lfs.github.com/). We're figuring out the details - for now you can submit your covers on [#steam-library-art channel in Luxtorpeda Discord](https://discord.gg/dWTxE4S).
