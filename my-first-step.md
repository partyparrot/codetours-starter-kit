---
title: My first code tour step
code: https://github.com/partyparrot/codetours/blob/563179f4f67fd76ca2dc28be3d5cf4fae4132891/client/main.js#L10-L16
---

Welcome to CodeTours! As you can see, on the left is a code snippet of the route definitions in the CodeTours application itself. This code snippet was specified in the YAML front matter of this markdown file - the `code:` property above.

Note - you can get a link like the above by clicking in the line numbers of any file on GitHub, and then pressing `y` on your keyboard to get a "blob" URL.

If you want to refer to specific other sub-sections of the code, you can always do that by creating a link to a different set of lines, as you can see in the heading below:

<a href="https://github.com/partyparrot/codetours/blob/563179f4f67fd76ca2dc28be3d5cf4fae4132891/client/main.js#L75-L76" id="link-anchor"><h3>Linking to a different section</h3></a>

This heading has a few important aspects:

1. The `id` property is used as an anchor, so that you can link to this section directly.
2. The `href` is used to determine the line numbers.
3. The `<a>` tag is stripped entirely before displaying on the CodeTours website, since it has a special UI for navigating the code.
