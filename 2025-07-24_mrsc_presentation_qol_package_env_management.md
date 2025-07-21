---
title: "My favourite package **(?!)** managers, and why"
sub_title: "An (opinionated) account"
author: Stavrina Dimosthenous
event: MRSC
date: 2025-07-24
options:
  incremental_lists: true
---

Purpose
===

1. Quality-of-life
2. Try something new
3. Go forth and explore
4. Amusement (?)

<!-- end_slide -->

<!-- jump_to_middle -->


Quick Disclaimer
===

<!-- end_slide -->

<!-- jump_to_middle -->

A note
===

<!-- end_slide -->

Criteria
===
* Makes my life easier:
  * ACTUALLY fixes a problem I'm having
  * Command line interface (CLI)
  * One thing!
  * Shareable
  * No bloat **...?** ＼(º □ º l|l)/	

<!-- end_slide -->

`uv`
===

* What
  * Python version and environment management (+ a few more things)
* Why
  * Fed up with conda (miniconda)
  * Wanted to go back to `venv`
  * Still needed version management
  * `pyenv`, `virtualenv`, `pipenv`, `poetry`, `conda`, `mamba`...**?!** (⊙_☉)
    * And `poetry` just was not what I needed
  * I suck at docker ╥﹏╥
    * More on this soon...

**!! There's also `ruff` !!**

<!-- end_slide -->

`uv`, some commands
===
<!-- column_layout: [1, 1] -->
<!-- column: 0 -->

Basic usage

```shell
uv init
```

```shell
uv python install 
```

<!-- column: 1 -->

Same as

```shell
uv init --app --vsc git
```

<!-- end_slide -->

`uv`, opinionated reasons why I love it
===

* `.toml`!
* initialises `.git/` for me (with bells and whistles)
* **NOT** because it's written in Rust (￣ヘ￣)
<!-- end_slide -->

Some reasons why I'm keeping `conda`, for now "( – ⌓ – )
===

* "Interoperability"
* `IJulia` 
* I like having my hand held
* Need to look into `pixi`
<!-- end_slide -->

Still learning
===

* I still want to make okay environments with Docker/podman
* Still locked into *CodeOSS*\/*VSCodium* (˃̣̣̥⌓˂̣̣̥ )
* Trying new things is fun...
  * **Time**
  * **Reason**
    * A reason can be learning/self-teaching

<!-- end_slide -->

Other package/env managers to try
===

* Julia
  * `Pkg` in the REPL!
* `pacman` (for Arch)
  * `yay`\/`paru` (I prefer `yay`)
  * !!Disclosure, I use an Arch based distro, not Arch
    * Try CachyOS (I use this!), EndeavourOS or Garuda Linux!
    * Lots of Arch resources on <arcolinux.com>
* `cargo`\/`cargo-binstall` (I don't even know what Rust syntax looks like)
* `macports` (I also use `brew` but prefer `port`)
* Docker (use on macOS with `colima` and sort out your `.wslconfig` on Windows)
* `eget` (Full disclosure, not tested this out yet!)
