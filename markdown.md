---
title: A code tour content file
code: https://github.com/partyparrot/codetours-starter-kit/blob/ff549496a34638b7d940b915a68aae567bf2cce4/my-first-step.md
---

OK, now that we know how to configure a code tour, let's look at one of the content files. This tour is pretty meta, since we're now looking at the source code of the previous step's content.

<a href="https://github.com/partyparrot/codetours-starter-kit/blob/ff549496a34638b7d940b915a68aae567bf2cce4/my-first-step.md#L1-L4"><h4>YAML front matter</h4></a>

At the top of every step, there needs to be a bit of metadata. This is encoded in a standard format called "YAML front matter", used by a variety of different markdown-based site generators.

But you don't really need to know YAML for this - it's just a set of keys, followed by some values. There are only two used by code tours:

- `title` - as you may have guessed, this is the title of the tour step.
- `code` - this one is a bit more complicated. It represents the file that this step of the tour is about. It has to be in a specific format - a "blob" URL from GitHub.

You can get the URL that needs to go into the `code` property quite easily from the GitHub UI:

1. Go to the file you want
2. Hit `y` on your keyboard to get a URL for the specific commit hash
3. Click to select the starting line number
4. Shift-click to select the ending line number
5. Copy the URL from the address bar

That's it - the URL format is a bit complicated but you don't have to worry about it to use it.

<a href="https://github.com/partyparrot/codetours-starter-kit/blob/ff549496a34638b7d940b915a68aae567bf2cce4/my-first-step.md#L17"><h4>Code snippet links</h4></a>

Sometimes, a file or concept requires looking at several different parts of the code. In this case, you can add another section to the same step, that will highlight a specific set of lines when clicked. Just add an `<a>` tag in your markdown, with an `href` that has the same format as the `code` property in the YAML front matter.

The only restriction is, all sections of the same step have to reference the _same file_ of source code.

#### Starter kit

To get started with your own code tour, just fork the [starter kit](https://github.com/partyparrot/codetours-starter-kit) and get to editing. Then, type in the name of your code tour's repository in the "create a tour" box on the front page, and view it online!

The best part is, the formatting has been optimized to work almost as well in GitHub's native Markdown viewer. So you can look at your content directly on GitHub before you're ready to submit it to www.codetours.xyz.
