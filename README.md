# gl-compare-sidebar [![experimental](http://badges.github.io/stability-badges/dist/experimental.svg)](http://github.com/badges/stability-badges)

A sidebar UI for [gl-compare](http://github.com/hughsk/gl-compare), intended
for use in [glslify-workshopper](http://github.com/gl-modules/glslify-workshopper).

[![NPM](https://nodei.co/npm/gl-compare-sidebar.png)](https://nodei.co/npm/gl-compare-sidebar/)

## Usage

[<img src="http://imgur.com/N61zzfW.png" align="right"/>](http://hughsk.io/gl-compare-sidebar)

### sidebar = createSidebar(compare)

Given an instance of [gl-compare](http://github.com/hughsk/gl-compare), this
method creates a new sidebar.

### sidebar.el

The sidebar's DOM node. Will be automatically attached to `document.body` but
you can use this to apply your own styles too.

### sidebar.content

The otherwise empty content area in the middle of the sidebar. The styles
applied here are minimal, apart from a `monospace` font family and
`overflow: auto`, so you should be able to place whatever content you
like in here without many issues.

## License

MIT. See [LICENSE.md](http://github.com/hughsk/gl-compare-sidebar/blob/master/LICENSE.md) for details.
