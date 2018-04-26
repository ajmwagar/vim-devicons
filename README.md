<h1 align="center">
 Vim emoticons - Add EMOJI to (n)vim 🔥 💯 🎊
</h1>
## DO NOT USE WITH VIM-DEVICONS ❗ ❗


<div align="center">

![version](https://img.shields.io/github/release/ajmwagar/vim-emoticons.svg?style=for-the-badge)
![chat on gitter](https://img.shields.io/gitter/room/nwjs/nw.js.svg?style=for-the-badge)
![issue count](https://img.shields.io/codeclimate/issues/github/ajmwagar/vim-emoticons.svg?style=for-the-badge) ![code of conduct](https://img.shields.io/badge/code%20of-conduct-ff69b4.svg?style=for-the-badge)
![prs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAMAAABEpIrGAAACWFBMVEXXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWkrXWko2FeWCAAAAAXRSTlMAQObYZgAAAAFiS0dEAIgFHUgAAAAJcEhZcwAAI28AACNvATX8B%2FsAAAAHdElNRQfhBQMBMCLAfV85AAAAi0lEQVQ4y2NgIBYszkPmJc5ORZE9DgEJqNxmmPS%2B43AA4h5B5TIwbD5%2BHFnoKCoXYSBMBIW7CF0eAxChoPM4ARXHB4GCZEIKKA8H%2FCoWE1LAwIBfBVp6wQA1DPhVzMJMcyggCVuqxGI%2FLhWY6Z6QPKoK7HmHkDwDwxYC8gwMdSDprXiz6PHjpQxUBgCLDfI7GXNh5gAAAABJRU5ErkJggg%3D%3D)

</div>

> Supports plugins such as [NERDTree](https://github.com/scrooloose/nerdtree), [vim-airline](https://github.com/vim-airline/vim-airline), [CtrlP](https://github.com/ctrlpvim/ctrlp.vim), [powerline](https://github.com/powerline/powerline), [denite](https://github.com/Shougo/denite.nvim), [unite](https://github.com/Shougo/unite.vim), [lightline.vim](https://github.com/itchyny/lightline.vim), [vim-startify](https://github.com/mhinz/vim-startify), [vimfiler](https://github.com/Shougo/vimfiler.vim), [vim-workspace](https://github.com/bagrat/vim-workspace) and [flagship](https://github.com/tpope/vim-flagship).


> See [Screenshots](https://github.com/ajmwagar/vim-emoticons/wiki/screenshots) for more.

Features
--------

- Adds filetype __EMOJI__ 📖 🔥 💯 (icons) to various vim plugins.
- Supports byte order marker (BOM).
- Customizable and extendable emoji settings.
- Supports a wide range of file type extensions.
- Supports popular full filenames, like `.gitignore`, `node_modules`, `.vimrc`.

> See [Detailed Features](https://github.com/ajmwagar/vim-emoticons/wiki/Detailed-Features) for more.

> See [Configuration](https://github.com/ajmwagar/vim-emoticons/wiki/Extra-Configuration) for a list of configuration and customization options.

Installation
------------

#### Linux 

1. Install `emojione` from your package manager
  - Arch/Manjaro
    `sudo yaourt -S ttf-emojione --noconfirm`

1. Using your system package manager update/download the lastest version of cairo
  - Arch/Manjaro
    `sudo pacman -S cairo`


1. Make sure your terminal emulator supports cairo AND normal unicode emojis


1. Install the Vim plugin with your favorite plugin manager, e.g. [vim-plug](https://github.com/junegunn/vim-plug):

    ```vim
    Plug 'ajmwagar/vim-emoticons'
    ```

    > Always load the vim-emoticons as the very last one.

1. Configure Vim

    ```vim
    set encoding=UTF-8
    ```

	> No need to set explicitly under Neovim: always uses UTF-8 as the default encoding.


> See [Installation](https://github.com/ajmwagar/vim-emoticons/wiki/Installation) for detailed setup instructions

Use `:help devicons` for further configuration.

Developers
----------

See [DEVELOPER](DEVELOPER.md) for how to use the API.

Troubleshooting
---------------

See [FAQ](https://github.com/ajmwagar/vim-emoticons/wiki/FAQ-&-Troubleshooting).

Contributing
------------

### [Code of Conduct](CODE_OF_CONDUCT.md)

This project has adopted a Code of Conduct that we expect project participants to adhere to. Check out [code of conduct](CODE_OF_CONDUCT.md) for further details.

### [Contributing Guide](CONTRIBUTING.md)

Read our [contributing](CONTRIBUTING.md) guide to learn about how to send pull requests, creating issues properly.

### Promotion

You can help us by simply giving a star. It will ensure continued development going forward.

- Star this repository [on GitHub](https://github.com/ajmwagar/vim-emoticons).

Credits
-------

Thanks goes to:

- [ryanoasis](https://github/ryanoasis)
    Creater of vim-devicons (the base for vim-emoticons)

License
-------

[MIT](LICENSE)
