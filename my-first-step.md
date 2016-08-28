---
title: A code tour configuration file
code: https://github.com/partyparrot/codetours-starter-kit/blob/ded59179edb6bd892ccffcb0c5a8a4f3868826d5/.codetour.json
---

You might have read some code tours already, but this one is special - it's designed to teach you how to make a tour yourself. You can make a code tour of any open source project, even one you don't have commit access to.

The content for a code tour is pulled from your repository on GitHub. To be able to be imported as a code tour, your repository needs to contain:

1. A `.codetour.json` configuration file in the root of the repository
2. One or more markdown files, referenced by the configuration file

On the left, you can see an example of a very simple `.codetour.json` file. You can see that it needs to include at least three properties.

<a href="https://github.com/partyparrot/codetours-starter-kit/blob/ded59179edb6bd892ccffcb0c5a8a4f3868826d5/.codetour.json#L2" id="targetRepository"><h4>targetRepository</h4></a>

This property represents the repository that you are writing a tour about. For example, your code tour might live at `github.com/mynamehere/best-react-tour`, and the `targetRepository` would be `facebook/react`. This will help people find your tour when browsing this website.

<a href="https://github.com/partyparrot/codetours-starter-kit/blob/ded59179edb6bd892ccffcb0c5a8a4f3868826d5/.codetour.json#L3" id="description"><h4>description</h4></a>

This property is a description that should tell people what to expect when they get into your tour. It's your chance to hook people in when they are browsing the catalog.

<a href="https://github.com/partyparrot/codetours-starter-kit/blob/ded59179edb6bd892ccffcb0c5a8a4f3868826d5/.codetour.json#L4-L6" id="steps"><h4>steps</h4></a>

This property represents the actual content of your tour - it's an array of steps, each of which is the path to a Markdown-formatted file inside the same repository.

That's all for the configuration file - go to the next step to learn how to write the content of the steps themselves.
