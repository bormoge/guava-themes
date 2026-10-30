[![MELPA](https://melpa.org/packages/guava-themes-badge.svg)](https://melpa.org/#/guava-themes)
[![MELPA Stable](https://stable.melpa.org/packages/guava-themes-badge.svg)](https://stable.melpa.org/#/guava-themes)
[![License](https://img.shields.io/github/license/bormoge/guava-themes)](https://github.com/bormoge/guava-themes)

# guava-themes
A few Emacs themes inspired by guavas (and other plants).

<!-- <img src="https://lh3.googleusercontent.com/d/1ZKZnxku77rHpd4gtwaHQrRSyxvEigEYD=s2000?authuser=0" width="300" height="300" alt="guava-drawing"> -->
<!-- ![guava-drawing](./img/guava-flower-drawing-2.png) -->

<!-- ### Table of Contents -->
<!-- - [Introduction](#introduction) -->
<!-- - [Installation](#installation) -->
<!-- - [Screenshots](#screenshots) -->
<!-- - [Contributions](#contributions) -->
<!-- - [Image Attributions](#image-attributions) -->
<!-- - [License](#license) -->

<div style="display: flex; align-items: center;">
<img src="https://lh3.googleusercontent.com/d/1ZKZnxku77rHpd4gtwaHQrRSyxvEigEYD=s2000?authuser=0" width="300" height="300" alt="guava-drawing" style="margin-right: 20px;">
<div>
<h3>Table of Contents</h3>
<ul>
<li><a href="#introduction">Introduction</a></li>
<li><a href="#installation">Installation</a></li>
<li><a href="#screenshots">Screenshots</a></li>
<li><a href="#contributions">Contributions</a></li>
<li><a href="#image-attributions">Image Attributions</a></li>
<li><a href="#license">License</a></li>
</ul>
</div>
</div>

## Introduction
This package began as an specific idea: *what if I could create an Emacs theme based on my favorite fruit? And what if it was a light theme, but not **too light**?*  
So here it is. My first Emacs package / pack of themes.  
Originally conceived as a tribute to the [guava fruit](https://en.wikipedia.org/wiki/Guava), this pack of themes ended up being inspired by different types of plants I found eye-catching.  
And so, the package name became an Artifact Title, as is known in the tropes community.  

## Installation
You can install **guava-themes** from [MELPA](https://melpa.org/#/getting-started) using **one** of the following methods: 

<details>
<summary><b>use-package</b></summary>

```elisp
(use-package guava-themes
  :ensure t
  :custom
  (guava-themes-visible-bell-duration 0.15)
  (guava-themes-visible-bell-idle-delay 0.0)
  (guava-themes-boxed-mode-line nil)
  (ring-bell-function #'guava-themes-change-visible-bell)
  (visible-bell t)
  :config
  (load-theme 'guava-themes-psidium t)
  )
```

</details>

<details>
<summary><b>package-install</b></summary>

```elisp
(unless (package-installed-p 'guava-themes)
  (package-install 'guava-themes))

(require 'guava-themes)

(setopt guava-themes-visible-bell-duration 0.15)
(setopt guava-themes-visible-bell-idle-delay 0.0)
(setopt guava-themes-boxed-mode-line nil)
(setopt ring-bell-function #'guava-themes-change-visible-bell)
(setopt visible-bell t)

(load-theme 'guava-themes-psidium t)
```

</details>

## Screenshots

<details>
<summary><b>Guava Psidium Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1HwKslzk3qdFVKukiSoqFi46R7ioTn663=s2000?authuser=0" width="750" height="400" alt="guava-psidium-screenshot">

</details>

<details>
<summary><b>Guava Jacaranda Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/16MBqRjX5BrZTScW8jl8ESOK3whA3LiBa=s2000?authuser=0" width="750" height="400" alt="guava-jacaranda-screenshot">

</details>

<details>
<summary><b>Guava Prunus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/16e-TQTUgE5UuH2NR1IocsoCIIMZnZEM0=s2000?authuser=0" width="750" height="400" alt="guava-prunus-screenshot">

</details>

<details>
<summary><b>Guava Dracaena Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1X0U_WplmrT5GSC9RbdWEr4eNyaXaMwYD=s2000?authuser=0" width="750" height="400" alt="guava-dracaena-screenshot">

</details>

<details>
<summary><b>Guava Acer Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1zXa6R7uJr5j7BX2U7Da6jisb2F_DPL9T=s2000?authuser=0" width="750" height="400" alt="guava-acer-screenshot">

</details>

<details>
<summary><b>Guava Cordyline Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1r-SISsE3T1dGEPTlPlgAoEosWDOoop80=s2000?authuser=0" width="750" height="400" alt="guava-cordyline-screenshot">

</details>

<details>
<summary><b>Guava Rhododendron Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1bZV-RHCFdBenz-N2iavYP9jU17gk_26i=s2000?authuser=0" width="750" height="400" alt="guava-rhododendron-screenshot">

</details>

<details>
<summary><b>Guava Ceiba Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1GAYVitdjkOmiqTLq-oWEfCwCkbL5de0G=s2000?authuser=0" width="750" height="400" alt="guava-ceiba-screenshot">

</details>

<details>
<summary><b>Guava Citrus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/11tkWDpTO0TY9t4LCqT9pZK0FxgEu3WqL=s2000?authuser=0" width="750" height="400" alt="guava-citrus-screenshot">

</details>

<details>
<summary><b>Guava Solanum Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1KhIEiBG_ac71NtwBUbcUpXDsklWXRiTD=s2000?authuser=0" width="750" height="400" alt="guava-solanum-screenshot">

</details>

<details>
<summary><b>Guava Vaccinium Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1zmwL8Mx2405HC1BxZGlhlG5LzOOAXYdC=s2000?authuser=0" width="750" height="400" alt="guava-vaccinium-screenshot">

</details>

<details>
<summary><b>Guava Rubus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/17P1Z9HuLpGjDnqSfXLwk0Wyio46__rLL=s2000?authuser=0" width="750" height="400" alt="guava-rubus-screenshot">

</details>

<details>
<summary><b>Guava Pyrus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1E7pe9SFGGrb3DrVIr-cxyFw7TIVj3VJS=s2000?authuser=0" width="750" height="400" alt="guava-pyrus-screenshot">

</details>

<details>
<summary><b>Guava Petunia Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1G5uhCxk0NmjaUtlrdO5R70Xh3XH66hwK=s2000?authuser=0" width="750" height="400" alt="guava-petunia-screenshot">

</details>

<details>
<summary><b>Guava Malus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1RR4qUevqzlJ4rlz6Opl_-rxvrMWg4eUX=s2000?authuser=0" width="750" height="400" alt="guava-petunia-screenshot">

</details>

<details>
<summary><b>Guava Eucalyptus Theme</b></summary>

<img src="https://lh3.googleusercontent.com/d/1VXoJhfk2YEcW5VcyACC-S1y52g2cK08S=s2000?authuser=0" width="750" height="400" alt="guava-petunia-screenshot">

</details>

## TODO
- Add themes: Ficus.
- (Emacs 31) Add header-line-active and header-line-inactive faces
- (Emacs 31) Add tab-line-active and tab-line-inactive faces

## Contributions
Issues, pull requests, and forks are welcome.

Here is a tentative list of things to consider when contributing:


* When adding or modifying something that changes the visuals of Emacs (e.g. a face), make sure to include screenshots of the original and changed versions.
* When making a pull request, make sure the commits adhere to the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) specification.
* Make sure commits are modular; one feat/fix/doc/etc at a time.  

## Image Attributions
Unless otherwise stated, all images used, linked, displayed, and/or referenced in [this repository](https://github.com/bormoge/guava-themes) were created by me [(https://github.com/bormoge)](https://github.com/bormoge) under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en) license.

## License

SPDX-License-Identifier: GPL-3.0-or-later

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
