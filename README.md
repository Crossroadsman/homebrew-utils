homebrew-utils
==============

My personal tap.

For background on taps see <https://docs.brew.sh/Taps>

Installation
------------

Tap the repo using:

```console
$ brew tap crossroadsman/utils
```

Install formulae using:

```console
$ brew install <package>
```

If there is a name collision with homebrew core, you can explicitly reference the formula using:

```console
$ brew install crossroadsman/utils/<package>
```

To untap the repo:

```console
$ brew untap crossroadsman/utils
```

This will remove the repo from list of taps and cause homebrew to forget any associated formulae. It will not remove 
any installed packages. These can still be uninstalled using `brew uninstall <package>`.


Formula List
------------

- [`hiptext`](https://github.com/jart/hiptext) : image -> textfile. Formula copied 
  from <https://github.com/bfontaine/homebrew-utils>. Usage: `hiptext [options] [--xterm256unicode] <file>`. File can be an
  image or video. The optional `xterm256unicode` argument effectively doubles the resolution by using unicode half blocks. 
  hiptext autodetects the Terminal width. Alternatively you can override with the `width` or `height` options (e.g., 
  `-width 80` to force 80 columns (it's not clear what the UOM is for the `height` option).
