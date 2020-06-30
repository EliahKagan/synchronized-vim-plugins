# synchronized-vim-plugins - Vim 8+ (packadd) plugins I use on multiple systems

This repository is mainly a collection of submodules, each of which has its own
authorship and copyright information.

The small amount of data in this repository other than submodules, such as this
README file, is written by Eliah Kagan. This repository was first published in
2020. The following applies to those data, *not* to the contents of submodules:

*To the extent possible under law, the author(s) have dedicated all copyright
and related and neighboring rights to this software to the public domain
worldwide. This software is distributed without any warranty.*

*You should have received a copy of the CC0 Public Domain Dedication along with
this software. If not, see
<http://creativecommons.org/publicdomain/zero/1.0/>.*

This repository should be cloned with
[submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules). For example:

```sh
git clone --recurse-submodules https://github.com/EliahKagan/synchronized-vim-plugins
```

Or if you've cloned it without submodules:

```sh
cd synchronized-vim-plugins
git submodule init
git submodule update
```

**To use these files**, make a symlink to this repository's top-level
directory, `synchronized-vim-plugins` inside `~/.vim/pack`. For example, from
inside this directory, you could run:

```sh
ln -s "$(realpath .)" ~/.vim/pack/
```

That command presumes a Unix-like system and a Bourne-style shell. But these
plugins probably all work on other systems supported by Vim, such as Windows.
Adjust accordingly.

(Copying the directory would also work, if for some reason you wanted to do
that, such as on a Windows system that is configured not to allow unprivileged
users to create symbolic links.)
