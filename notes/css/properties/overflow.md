# `overflow`

Sets behavior when element's content bigger than block formatting context, in both directions. Shorthand for `overflow-x` and `overflow-y`.

Specified as one or two keywords. If two keywords, first applies to `overflow-x` and second to `overflow-y`. Otherwise applies to both.

## Values

### `visible`

Content not clipped and may be rendered outside padding box.

### `hidden`

Content clipped if necessary. No scroll bars and no user scroll interaction support. Can be scrolled programmatically.

### `clip`

Similar to `hidden`, but forbids all scrolling, including programmatic.

### `scroll`

Content clipped. Scroll bars always displayed.

### `auto`

Depends on user agent. If content fits, looks same as `visible`, but still establishes new block formatting context. Scroll bars provided if content overflows.

### `overlay`

Same as `auto`, but scroll bars drawn on top of content instead of taking up space.
