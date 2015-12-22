# Box

The Box object simply boxes off content.

## Dependencies

aleutcss’ Box object depends on three other aleutcss modules:

* [settings.defaults](https://github.com/aleutcss/settings.defaults)
* [tools.functions](https://github.com/aleutcss/tools.functions)
* [trumps.clearfix](https://github.com/aleutcss/trumps.clearfix)

If you install the Box object using NPM, you will get these dependencies at
the same time. If not using NPM, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

The recommended installation method is NPM, but you can install the Box
module via a Git Submodule, or copy and paste.

### 

Install using npm:

    $ npm install --save-dev aleut-box

Once installed, `@import` into your project in its Objects layer:

    @import "node_modules/inuit-box/objects.box";

### Install as a Git Submodule

    $ git submodule add git@github.com:aleutcss/objects.box.git

Once installed, `@import` into your project in its Objects layer:

    @import "objects.box/objects.box";

### Install via file download

The least recommended option for installation is to simply download
`_objects.box.scss` into your project and `@import` it into your project in
its Objects layer.

## Usage

Basic usage of the Box object uses the required classes:

    <div class="o-box">
        Foo Bar Baz
    </div>

## Options

Other, optional classes can supplement the required base classes:

* `.o-box--flush`: remove all padding from boxes.
* `.o-box--[tiny|small|large|huge]`: alter the padding on boxes.

For example:

    <div class="o-box  o-box--large">
        Foo Bar Baz
    </div>
