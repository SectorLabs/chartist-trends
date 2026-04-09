# chartist-trends

Fork of [gionkunz/chartist-js](https://github.com/gionkunz/chartist-js). Stripped down for simple, responsive trend charts with a built-in tooltip plugin.

## Changes from upstream

* Reduced Chartist core by removing unneeded functionality
* Built-in tooltip plugin (`chartist-plugin-tooltip2`) with improvements
* Plugin system accepts objects with name and options
* `axisY` format function used as default value formatter in tooltips
* Tooltips positioned relative to the chart instead of the page
* Axis markers in tooltip plugin
* Custom autoscale via `getBounds` option on axis
* `ct-area` support
* `ct-point` drawing re-enabled
* Tooltip plugin updated for recent Node compatibility
* `value` accepted as an object, providing the `x` position
* Option to only render tooltips where required

## Install

```
npm install @sector-labs/chartist-trends
```

## License

MIT OR WTFPL
