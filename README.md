# Joe's Neovim Config

Built from the [LazyVim](https://github.com/LazyVim/LazyVim) started template.
Refer to the LazyVim [documentation](https://lazyvim.github.io/installation) to get started.

Clone this repo in your `.config` folder.

## Installation

- Neovim >= 0.9.0 (needs to be built with LuaJIT)
- Git >= 2.19.0 (for partial clones support)

### Bob Install

I use [Bob](https://github.com/MordechaiHadad/bob) as my Neovim version manager.

To use [Bob](https://github.com/MordechaiHadad/bob), ensure [rustup](https://www.rust-lang.org/) is installed. You can install [here](https://www.rust-lang.org/tools/install), or if you're a Windows Subsystem for Linux user run the following in your terminal, then follow the on-screen instructions to install Rust.

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

#### You can now install bob

You can install from source or crates.io

```sh
# Install from source
cargo install --git https://github.com/MordechaiHadad/bob.git
```

or

```sh
# Install from crates.io
cargo install bob-nvim
```

You can install the most recent version of Neovim with the following bob usage.

> Note: If `0.9.5` is not the most recent version, replace it

```sh
bob install 0.9.5
```

```sh
bob use 0.9.5
```

A terminal restart may be required at this point.

#### Add Neovim to your path

Edit your `.bashrc` file. Add the following code.

```
export PATH="$PATH:/home/{Your-User}/.local/share/bob/nvim-bin"
```

You should now be met with a the new configuration when `nvim` is run.
