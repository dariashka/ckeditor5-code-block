CKEditor 5 Code Blocks
========================================

This package implements basic up- and downcasting for pre-wrapped code blocks for CKEditor 5. This feature can be used with the CommonMark / GFM plugin for displaying enced code blocks.

Note that this is currently broken and since I did not overcome the issues reported in https://github.com/opf/ckeditor5-code-block/issues, [OpenProject](https://www.openproject.org/). instead currently uses a code block plugin in production that is edited with a modal window and a CodeMirror instance. https://github.com/opf/commonmark-ckeditor-build/tree/master/src/plugins/code-block

## Behavior

![peek 2018-07-10 11-18](https://user-images.githubusercontent.com/459462/42501039-1f7fd8d2-8433-11e8-8ed8-0ba56929c2c2.gif)

## Known issues

Code blocks rendered with this plugin cannot be edited currently. See [bug reports](https://github.com/opf/ckeditor5-code-block/issues) for more information.

## License

Licensed under the terms of [GNU General Public License Version 2 or later](http://www.gnu.org/licenses/gpl.html). For full details about the license, please check the `LICENSE.md` file.
