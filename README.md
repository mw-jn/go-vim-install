# go-vim-install
Easy environment setup for Vim addicts and go developers.

## Usage

This little installer for ubuntu make the life simpler for go development with Vim.
The idea here is to provide 3 commands to either :
- Download and install go from a tarball and set environment variables.
- Setup a fully working Vim environment with amazing plugins.
- Setup your go workspace with a few useful packages.

Examples :

- `./install.sh -go https://storage.googleapis.com/golang/go1.4.2.linux-amd64.tar.gz`
- `./install.sh -vim`
- `./install.sh -work ~/Workspace/go`

## Vim environment

The script will install pathogen and the following plugins :

- [vim-go](https://github.com/fatih/vim-go) (many great features like autoformat on save)
- [YouCompleteMe](https://github.com/Valloric/YouCompleteMe) (live completion based on types)
- [tagbar](https://github.com/majutsushi/tagbar) (display code metadata)

These two colorschemes will also be available :

- [molokai](https://github.com/fatih/molokai) (default)
- [monokai](https://github.com/sickill/vim-monokai)

## Workspace setup

The script will install in your workspace :
- [gocov](https://github.com/axw/gocov) (code coverage tools)
- [gotags](https://github.com/jstemmer/gotags) (required for vim tagbar)
