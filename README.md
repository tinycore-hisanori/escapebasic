# EscapeGame Sample No.001 

## Step 1

まずは簡単なマップを用意します。

## Step 2

Instructions for step 2 here...

## Step 3 - Show the temperature

Get a ``||input:temperature||`` block and place it in the value slot of ``||basic:show number||``.

```blocks
forever(function() {
    basic.showNumber(input.temperature())
    basic.pause(1000)
})

## Step 4 - Show the temperature
ddddd

> Open this page at [https://tinycore-hisanori.github.io/escapebasic/](https://tinycore-hisanori.github.io/escapebasic/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/tinycore-hisanori/escapebasic** and import

## Edit this project ![Build status badge](https://github.com/tinycore-hisanori/escapebasic/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/tinycore-hisanori/escapebasic** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/tinycore-hisanori/escapebasic/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
