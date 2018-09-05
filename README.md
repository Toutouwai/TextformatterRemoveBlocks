# Remove Blocks

Textformatter module for ProcessWire that removes blocks of text/markup between configurable delimiters from output. This allows you to "comment out" blocks of text/markup so they remain present in the field but are not shown on the front-end.

This can be handy if content needs to be removed temporarily and will later be reinstated. Or you could use a commented block as a placeholder to indicate to an editor where some content should be added.

## Installation

[Install](http://modules.processwire.com/install-uninstall/) the Remove Blocks module.

Configure the open and close delimiters if needed. The default open delimiter is `{{` and the default close delimiter is `}}`. Tip: don't use delimiter characters that CKEditor will encode to HTML entities, e.g. `>`.

## Usage

Add the Remove Blocks textformatter to one or more fields.

Add the open and close delimiters around any content that you want to be removed from output.

![remove-blocks](https://user-images.githubusercontent.com/1538852/45066198-52696780-b111-11e8-859c-8dc8810633c8.png)