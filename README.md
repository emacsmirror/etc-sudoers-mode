# [etc-sudoers-mode](https://gitlab.com/mavit/etc-sudoers-mode/)

This [Emacs](https://www.gnu.org/software/emacs/) package provides syntax highlighting for the [Sudo](https://www.sudo.ws/) security policy file, `/etc/sudoers`.

If [Flycheck](https://www.flycheck.org/) is present, it also defines a Flycheck syntax checker using [`visudo`](https://www.sudo.ws/man/1.9.3/visudo.man.html).

Please don't edit `/etc/sudoers` directly.  It is easy to make a mistake and lock yourself out of root access.  Instead, don't be put off by the name: use `visudo`.  You can do that by [setting up `emacsclient`](https://www.gnu.org/software/emacs/manual/html_node/emacs/Emacs-Server.html#Emacs-Server), or by using the function `(etc-sudoers-mode-visudo)`.


[![MELPA Stable](https://stable.melpa.org/packages/etc-sudoers-mode-badge.svg)](https://stable.melpa.org/#/etc-sudoers-mode) [![MELPA](https://melpa.org/packages/etc-sudoers-mode-badge.svg)](https://melpa.org/#/etc-sudoers-mode)
    
## Copying

Copyright (C) 2020, Peter Oliver.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.
