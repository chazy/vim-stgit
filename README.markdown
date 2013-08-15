stgit.vim
=========

Provides syntax highlighting for common stgit commands, including:
 - stg new
 - stg edit
 - stg squash
 - stg mail

These files are taken from https://github.com/pitkali/vim-config and modified
to work with my remaining plugings (the .txt autocommand or vim built-in file
type detection overwrote the stgit ones).

This is also packaged as a plugin rather than individual files as part
of another repository and therefore I have added a check to avoid
loading the autocommands twice and put the autocommands into an
appropriate group that gets cleared on reload.
