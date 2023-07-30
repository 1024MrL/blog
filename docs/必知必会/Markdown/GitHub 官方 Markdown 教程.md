> 本文由 [简悦 SimpRead](http://ksria.com/simpread/) 转码，原文地址 [docs.github.com](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

Create sophisticated formatting for your prose and code on GitHub with simple syntax.

[Headings](#headings)
---------------------

To create a heading, add one to six # symbols before your heading text. The number of # you use will determine the hierarchy level and typeface size of the heading.

```
# A first-level heading
## A second-level heading
### A third-level heading
```

![](https://docs.github.com/assets/cb-11432/images/help/writing/headings-rendered.png)

When you use two or more headings, GitHub automatically generates a table of contents that you can access by clicking within the file header. Each heading title is listed in the table of contents and you can click a title to navigate to the selected section.

![](https://docs.github.com/assets/cb-82878/images/help/repository/headings-toc.png)

[Styling text](#styling-text)
-----------------------------

You can indicate emphasis with bold, italic, strikethrough, subscript, or superscript text in comment fields and `.md` files.

<table><thead><tr><th scope="col">Style</th><th scope="col">Syntax</th><th scope="col">Keyboard shortcut</th><th scope="col">Example</th><th scope="col">Output</th></tr></thead><tbody><tr><td>Bold</td><td><code>** **</code> or <code>__ __</code></td><td><kbd>Command</kbd>+<kbd>B</kbd> (Mac) or <kbd>Ctrl</kbd>+<kbd>B</kbd> (Windows/Linux)</td><td><code>**This is bold text**</code></td><td><strong>This is bold text</strong></td></tr><tr><td>Italic</td><td><code>* *</code> or <code>_ _</code>     </td><td><kbd>Command</kbd>+<kbd>I</kbd> (Mac) or <kbd>Ctrl</kbd>+<kbd>I</kbd> (Windows/Linux)</td><td><code>_This text is italicized_</code></td><td><em>This text is italicized</em></td></tr><tr><td>Strikethrough</td><td><code>~~ ~~</code></td><td>None</td><td><code>~~This was mistaken text~~</code></td><td><del>This was mistaken text</del></td></tr><tr><td>Bold and nested italic</td><td><code>** **</code> and <code>_ _</code></td><td>None</td><td><code>**This text is _extremely_ important**</code></td><td><strong>This text is <em>extremely</em> important</strong></td></tr><tr><td>All bold and italic</td><td><code>*** ***</code></td><td>None</td><td><code>***All this text is important***</code></td><td><strong><em>All this text is important</em></strong></td></tr><tr><td>Subscript</td><td><code>&lt;sub&gt; &lt;/sub&gt;</code></td><td>None</td><td><code>&lt;sub&gt;This is a subscript text&lt;/sub&gt;</code></td><td><sub>This is a subscript text</sub></td></tr><tr><td>Superscript</td><td><code>&lt;sup&gt; &lt;/sup&gt;</code></td><td>None</td><td><code>&lt;sup&gt;This is a superscript text&lt;/sup&gt;</code></td><td><sup>This is a superscript text</sup></td></tr></tbody></table>

[Quoting text](#quoting-text)
-----------------------------

You can quote text with a >.

```
Text that is not a quote

> Text that is a quote
```

Quoted text is indented, with a different type color.

![](https://docs.github.com/assets/cb-13462/images/help/writing/quoted-text-rendered.png)

**Tip:** When viewing a conversation, you can automatically quote text in a comment by highlighting the text, then typing R. You can quote an entire comment by clicking , then **Quote reply**. For more information about keyboard shortcuts, see "[Keyboard shortcuts](https://docs.github.com/en/get-started/using-github/keyboard-shortcuts)."

[Quoting code](#quoting-code)
-----------------------------

You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted. You can also press the Command+E (Mac) or Ctrl+E (Windows/Linux) keyboard shortcut to insert the backticks for a code block within a line of Markdown.

```
Use `git status` to list all new or modified files that haven't yet been committed.
```

![](https://docs.github.com/assets/cb-24556/images/help/writing/inline-code-rendered.png)

To format code or text into its own distinct block, use triple backticks.

```
Some basic Git commands are:
```
git status
git add
git commit
```


```

![](https://docs.github.com/assets/cb-34231/images/help/writing/code-block-rendered.png)

For more information, see "[Creating and highlighting code blocks](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks)."

If you are frequently editing code snippets and tables, you may benefit from enabling a fixed-width font in all comment fields on GitHub. For more information, see "[About writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github#enabling-fixed-width-fonts-in-the-editor)."

[Supported color models](#supported-color-models)
-------------------------------------------------

In issues, pull requests, and discussions, you can call out colors within a sentence by using backticks. A supported color model within backticks will display a visualization of the color.

```
The background color is `#ffffff` for light mode and `#000000` for dark mode.


```

![](https://docs.github.com/assets/cb-11648/images/help/writing/supported-color-models-rendered.png)

Here are the currently supported color models.

<table><thead><tr><th scope="col">Color</th><th scope="col">Syntax</th><th scope="col">Example</th><th scope="col">Output</th></tr></thead><tbody><tr><td>HEX</td><td><code>` #RRGGBB `</code></td><td><code>` #0969DA `</code></td><td><picture><source srcset="/assets/cb-1558/mw-1440/images/help/writing/supported-color-models-hex-rendered.webp" type="image/webp"><img class="" src="https://docs.github.com/assets/cb-1558/images/help/writing/supported-color-models-hex-rendered.png"></picture></td></tr><tr><td>RGB</td><td><code>`rgb(R,G,B)`</code></td><td><code>`rgb(9, 105, 218)`</code></td><td><picture><source srcset="/assets/cb-1962/mw-1440/images/help/writing/supported-color-models-rgb-rendered.webp" type="image/webp"><img class="" src="https://docs.github.com/assets/cb-1962/images/help/writing/supported-color-models-rgb-rendered.png"></picture></td></tr><tr><td>HSL</td><td><code>`hsl(H,S,L)`</code></td><td><code>`hsl(212, 92%, 45%)`</code></td><td><picture><source srcset="/assets/cb-2066/mw-1440/images/help/writing/supported-color-models-hsl-rendered.webp" type="image/webp"><img class="" src="https://docs.github.com/assets/cb-2066/images/help/writing/supported-color-models-hsl-rendered.png"></picture></td></tr></tbody></table>

**Notes:**

*   A supported color model cannot have any leading or trailing spaces within the backticks.
*   The visualization of the color is only supported in issues, pull requests, and discussions.

[Links](#links)
---------------

You can create an inline link by wrapping link text in brackets `[ ]`, and then wrapping the URL in parentheses `( )`. You can also use the keyboard shortcut Command+K to create a link. When you have text selected, you can paste a URL from your clipboard to automatically create a link from the selection.

You can also create a Markdown hyperlink by highlighting the text and using the keyboard shortcut Command+V. If you'd like to replace the text with the link, use the keyboard shortcut Command+Shift+V.

`This site was built using [GitHub Pages](https://pages.github.com/).`

![](https://docs.github.com/assets/cb-8313/images/help/writing/link-rendered.png)

**Tip:** GitHub automatically creates links when valid URLs are written in a comment. For more information, see "[Autolinked references and URLs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls)."

[Section links](#section-links)
-------------------------------

You can link directly to a section in a rendered file by hovering over the section heading to expose .

![](https://docs.github.com/assets/cb-55935/images/help/repository/readme-links.png)

[Relative links](#relative-links)
---------------------------------

You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in _docs/CONTRIBUTING.md_, the relative link to _CONTRIBUTING.md_ in your README might look like this:

```
[Contribution guidelines for this project](docs/CONTRIBUTING.md)


```

GitHub will automatically transform your relative link or image path based on whatever branch you're currently on, so that the link or path always works. The path of the link will be relative to the current file. Links starting with `/` will be relative to the repository root. You can use all relative link operands, such as `./` and `../`.

Relative links are easier for users who clone your repository. Absolute links may not work in clones of your repository - we recommend using relative links to refer to other files within your repository.

[Images](#images)
-----------------

You can display an image by adding ! and wrapping the alt text in `[ ]`. Alt text is a short text equivalent of the information in the image. Then, wrap the link for the image in parentheses `()`.

` ![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg) `

![](https://docs.github.com/assets/cb-39745/images/help/writing/image-rendered.png)

GitHub supports embedding images into your issues, pull requests, discussions, comments and `.md` files. You can display an image from your repository, add a link to an online image, or upload an image. For more information, see "[Uploading assets](#uploading-assets)."

**Tip:** When you want to display an image that is in your repository, use relative links instead of absolute links.

Here are some examples for using relative links to display an image.

<table><thead><tr><th scope="col">Context</th><th scope="col">Relative Link</th></tr></thead><tbody><tr><td>In a <code>.md</code> file on the same branch</td><td><code>/<wbr>assets/<wbr>images/<wbr>electrocat.png</code></td></tr><tr><td>In a <code>.md</code> file on another branch</td><td><code>/<wbr>../<wbr>main/<wbr>assets/<wbr>images/<wbr>electrocat.png</code></td></tr><tr><td>In issues, pull requests and comments of the repository</td><td><code>../<wbr>blob/<wbr>main/<wbr>assets/<wbr>images/<wbr>electrocat.png?raw=true</code></td></tr><tr><td>In a <code>.md</code> file in another repository</td><td><code>/<wbr>../<wbr>../<wbr>../<wbr>../<wbr>github/<wbr>docs/<wbr>blob/<wbr>main/<wbr>assets/<wbr>images/<wbr>electrocat.png</code></td></tr><tr><td>In issues, pull requests and comments of another repository</td><td><code>../<wbr>../<wbr>../<wbr>github/<wbr>docs/<wbr>blob/<wbr>main/<wbr>assets/<wbr>images/<wbr>electrocat.png?raw=true</code></td></tr></tbody></table>

**Note**: The last two relative links in the table above will work for images in a private repository only if the viewer has at least read access to the private repository that contains these images.

For more information, see "[Relative Links](#relative-links)."

### [Specifying the theme an image is shown to](#specifying-the-theme-an-image-is-shown-to)

You can specify the theme an image is displayed for in Markdown by using the HTML `<picture>` element in combination with the `prefers-color-scheme` media feature. We distinguish between light and dark color modes, so there are two options available. You can use these options to display images optimized for dark or light backgrounds. This is particularly helpful for transparent PNG images.

For example, the following code displays a sun image for light themes and a moon for dark themes:

```
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>


```

The old method of specifying images based on the theme, by using a fragment appended to the URL (` #gh -dark-mode-only` or ` #gh -light-mode-only`), is deprecated and will be removed in favor of the new method described above.

[Lists](#lists)
---------------

You can make an unordered list by preceding one or more lines of text with -, *, or +.

```
- George Washington
* John Adams
+ Thomas Jefferson


```

![](https://docs.github.com/assets/cb-7927/images/help/writing/unordered-list-rendered.png)

To order your list, precede each line with a number.

```
1. James Madison
1. James Monroe
1. John Quincy Adams


```

![](https://docs.github.com/assets/cb-8162/images/help/writing/ordered-list-rendered.png)

### [Nested Lists](#nested-lists)

You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like [Visual Studio Code](https://code.visualstudio.com/), you can align your list visually. Type space characters in front of your nested list item until the list marker character (- or *) lies directly below the first character of the text in the item above it.

```
1. First list item
   - First nested list item
     - Second nested list item


```

**Note**: In the web-based editor, you can indent or dedent one or more lines of text by first highlighting the desired lines and then using Tab or Shift+Tab respectively.

![](https://docs.github.com/assets/cb-7202/images/help/writing/nested-list-alignment.png)

![](https://docs.github.com/assets/cb-7206/images/help/writing/nested-list-example-1.png)

To create a nested list in the comment editor on GitHub, which doesn't use a monospaced font, you can look at the list item immediately above the nested list and count the number of characters that appear before the content of the item. Then type that number of space characters in front of the nested list item.

In this example, you could add a nested list item under the list item `100. First list item` by indenting the nested list item a minimum of five spaces, since there are five characters (`100 .`) before `First list item`.

```
100. First list item
     - First nested list item


```

![](https://docs.github.com/assets/cb-4906/images/help/writing/nested-list-example-3.png)

You can create multiple levels of nested lists using the same method. For example, because the first nested list item has seven characters (`␣␣␣␣␣-␣`) before the nested list content `First nested list item`, you would need to indent the second nested list item by at least two more characters (nine spaces minimum).

```
100. First list item
       - First nested list item
         - Second nested list item


```

![](https://docs.github.com/assets/cb-7734/images/help/writing/nested-list-example-2.png)

For more examples, see the [GitHub Flavored Markdown Spec](https://github.github.com/gfm/#example-265).

[Task lists](#task-lists)
-------------------------

To create a task list, preface list items with a hyphen and space followed by `[ ]`. To mark a task as complete, use `[x]`.

```
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:


```

![](https://docs.github.com/assets/cb-64626/images/help/writing/task-list-rendered-simple.png)

If a task list item description begins with a parenthesis, you'll need to escape it with \:

`- [ ] \(Optional) Open a followup issue`

For more information, see "[About task lists](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists)."

[Mentioning people and teams](#mentioning-people-and-teams)
-----------------------------------------------------------

You can mention a person or [team](https://docs.github.com/en/organizations/organizing-members-into-teams) on GitHub by typing @ plus their username or team name. This will trigger a notification and bring their attention to the conversation. People will also receive a notification if you edit a comment to mention their username or team name. For more information about notifications, see "[About notifications](https://docs.github.com/en/account-and-profile/managing-subscriptions-and-notifications-on-github/setting-up-notifications/about-notifications)."

**Note:** A person will only be notified about a mention if the person has read access to the repository and, if the repository is owned by an organization, the person is a member of the organization.

`@github/support What do you think about these updates?`

![](https://docs.github.com/assets/cb-6949/images/help/writing/mention-rendered.png)

When you mention a parent team, members of its child teams also receive notifications, simplifying communication with multiple groups of people. For more information, see "[About teams](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams)."

Typing an @ symbol will bring up a list of people or teams on a project. The list filters as you type, so once you find the name of the person or team you are looking for, you can use the arrow keys to select it and press either tab or enter to complete the name. For teams, enter the @organization/team-name and all members of that team will get subscribed to the conversation.

The autocomplete results are restricted to repository collaborators and any other participants on the thread.

[Referencing issues and pull requests](#referencing-issues-and-pull-requests)
-----------------------------------------------------------------------------

You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

For more information, see "[Autolinked references and URLs](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/autolinked-references-and-urls)."

[Referencing external resources](#referencing-external-resources)
-----------------------------------------------------------------

If custom autolink references are configured for a repository, then references to external resources, like a JIRA issue or Zendesk ticket, convert into shortened links. To know which autolinks are available in your repository, contact someone with admin permissions to the repository. For more information, see "[Configuring autolinks to reference external resources](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/configuring-autolinks-to-reference-external-resources)."

[Uploading assets](#uploading-assets)
-------------------------------------

You can upload assets like images by dragging and dropping, selecting from a file browser, or pasting. You can upload assets to issues, pull requests, comments, and `.md` files in your repository.

[Using emoji](#using-emoji)
---------------------------

You can add emoji to your writing by typing `:EMOJICODE:`, a colon followed by the name of the emoji.

`@octocat :+1: This PR looks great - it's ready to merge! :shipit:`

![](https://docs.github.com/assets/cb-17229/images/help/writing/emoji-rendered.png)

Typing : will bring up a list of suggested emoji. The list will filter as you type, so once you find the emoji you're looking for, press **Tab** or **Enter** to complete the highlighted result.

For a full list of available emoji and codes, see [the Emoji-Cheat-Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md).

[Paragraphs](#paragraphs)
-------------------------

You can create a new paragraph by leaving a blank line between lines of text.

You can add footnotes to your content by using this bracket syntax:

```
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].

[^1]: My reference.
[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.
  This is a second line.


```

The footnote will render like this:

![](https://docs.github.com/assets/cb-27019/images/help/writing/footnote-rendered.png)

**Note**: The position of a footnote in your Markdown does not influence where the footnote will be rendered. You can write a footnote right after your reference to the footnote, and the footnote will still render at the bottom of the Markdown.

Footnotes are not supported in wikis.

You can tell GitHub to hide content from the rendered Markdown by placing the content in an HTML comment.

```
<!-- This content will not appear in the rendered Markdown -->


```

[Ignoring Markdown formatting](#ignoring-markdown-formatting)
-------------------------------------------------------------

You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

`Let's rename \*our-new-project\* to \*our-old-project\*.`

![](https://docs.github.com/assets/cb-5440/images/help/writing/escaped-character-rendered.png)

For more information on backslashes, see Daring Fireball's"[Markdown Syntax](https://daringfireball.net/projects/markdown/syntax#backslash)."

**Note**: The Markdown formatting will not be ignored in the title of an issue or a pull request.

[Disabling Markdown rendering](#disabling-markdown-rendering)
-------------------------------------------------------------

When viewing a Markdown file, you can click at the top of the file to disable Markdown rendering and view the file's source instead.

![](https://docs.github.com/assets/cb-24194/images/help/writing/display-markdown-as-source.png)

Disabling Markdown rendering enables you to use source view features, such as line linking, which is not possible when viewing rendered Markdown files.

[Further reading](#further-reading)
-----------------------------------

*   [GitHub Flavored Markdown Spec](https://github.github.com/gfm/)
*   "[About writing and formatting on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/about-writing-and-formatting-on-github)"
*   "[Working with advanced formatting](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting)"
*   "[Quickstart for writing on GitHub](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github)"