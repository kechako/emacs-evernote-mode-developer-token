emacs-evernote-mode-developer-token
===================================

This patch adds the authentication function by the developer token to [emacs-evernote-mode][].

[emacs-evernote-mode]: <https://code.google.com/p/emacs-evernote-mode/> "emacs-evernote-mode"

Quick Start
-----------
1. Apply a patch to emacs-evernote-mode (r198).
2. Add the following line to your `init.el` to set your developer token.

        (setq evernote-developer-token "Your developer token.")
