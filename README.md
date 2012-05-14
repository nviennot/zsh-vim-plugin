Vim Plugin for zsh
===================

Introduction
-------------

Sometimes, we want to open a file at a specific line number. Following the
cucumber syntax `features/story.feature:123`, this plugin allows you to do so
in an easy way.

This plugin allows you to type:

    vi file:123

This will open the `file` at line `123`.

Installation
------------

Clone the repository:

    cd ~/.oh-my-zsh
    git submodule add git://github.com/nviennot/zsh-vim-plugin.git plugins/vim

Then edit your `.zshrc` and add vim to the plugin list.
