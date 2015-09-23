![Hoa](http://static.hoa-project.net/Image/Hoa_small.png)

Hoa is a **modular**, **extensible** and **structured** set of PHP libraries.
Moreover, Hoa aims at being a bridge between industrial and research worlds.

# Contributions/Vim/Pp

This repository contains Vim tools for the PP grammar description language from
[the PHP `Hoa\Compiler`
library](http://central.hoa-project.net/Resource/Library/Compiler):

  * File type plugin,
  * File type detection,
  * File syntax and,
  * Color scheme.

## Installation

With [Vundle](https://github.com/gmarik/Vundle.vim), to include this plugin into
your Vim plugins, you need to require
[`hoaproject/Contributions-Vim-Pp`](http://vimawesome.com/plugin/pp) (in your
plugin list file):

```vim
Plugin 'hoaproject/Contributions-Vim-Pp'
```

Then, in the Vim command mode (press Esc):

```vim
:source %
:PluginInstall
```

## Quick usage

Just open a PP file in Vim, nothing special to do! For instance, try the
[`hoa://Library/Compiler/Llk/Llk.pp`](http://central.hoa-project.net/Resource/Library/Compiler/Llk/Llk.pp)
file:

![The plugin in action](http://central.hoa-project.net/Resource/Contributions/Vim/Pp/doc/image/screenshot.png?format=raw)

## Documentation

Different documentations can be found on the website:
[http://hoa-project.net/](http://hoa-project.net/).

## License

Hoa is under the New BSD License (BSD-3-Clause). Please, see
[`LICENSE`](http://hoa-project.net/LICENSE).
