Zoom
====

This minor mode takes care of managing the window sizes by enforcing a fixed and
automatic balanced layout where the currently selected window is resized
according to `zoom-size` which can be either an absolute value in rows/columns
or a ratio between the selected window and frame size.

TODO screencast

Installation
------------

### Manual

Add the following to your init file:

```el
(require 'zoom-mode "/path/to/zoom-mode.el")
```

### TODO melpa or such

Usage
-----

Enable this minor mode with `M-x zoom-mode` otherwise use `M-x zoom` to manually
rearrange windows just once.

Example configuration
---------------------

Add the following to your init file to load `zoom-mode` at startup and to set
the focused window size to 90 columns and 30 rows:

```el
(custom-set-variables
 '(zoom-mode t)
 '(zoom-size '(90 30)))
```

### TODO what about golden ratio?
