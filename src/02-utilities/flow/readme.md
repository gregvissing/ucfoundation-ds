# Flow

The flow utility provides flow and rhythm between direct sibling elements. Where `--flow-space` is not defined: the default value is `500` on the [size scale](/components/detail/size-scale).

This means that direct siblings inside of the `.flow` utility will have a `margin-top` of `get-size('500')`, which is `20px`.

By defining `--flow-space` in the CSS of either a child element of `.flow`, or on `.flow` itself: that value will be honoured in line with the cascade and specificity.
