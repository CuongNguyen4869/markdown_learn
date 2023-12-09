## Notice
This file provide some tips and tricks for working around Markdown's limitation.
These syntax will not guarantee to be supported by every Markdown processor.
I don't recommend to use these syntax if you don't have to.

## Underline

Some of these words <ins> will be underlined </ins>. Other will not be.

## Indent (Tab)

You can use tabs to create code blocks.
A space at beginning:
&nbsp;This is the first sentence.
A tab:
&nbsp;&nbsp;&nbsp;&nbsp;This is the second sentence.

## Center

<center> This sentence is centered. </center>

## Color

<font color="red">This text is red!</font>
<p style="color:blue">Make this text blue.</p>

## Comments

To write something that you don't want to render
[This is a comment that will be hidden.]: #
And here's another paragraph that's visible.

## Admonitions

==This can be useful.==

> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.

## Image Size

==This can be useful.==

<img src="examplePicture.jpg" width="200" height="100">

## Symbols

Markdown doesn’t provide special syntax for symbols. However, in most cases, you can copy and paste whatever symbol you want to use into your Markdown document. For example, if you need to display Pi (π), just find the symbol on a webpage and copy and paste it into your document. The symbol should appear as expected in the rendered output.

Alternatively, if your Markdown application supports HTML, you can use the HTML entity for whatever symbol you want to use. For example, if you want to display the copyright sign (©), you can copy and paste the HTML entity for copyright (&copy;) into your Markdown document.

Here’s a partial list of HTML entities for symbols:

Copyright (©) — &copy;
Registered trademark (®) — &reg;
Trademark (™) — &trade;
Euro (€) — &euro;
Left arrow (←) — &larr;
Up arrow (↑) — &uarr;
Right arrow (→) — &rarr;
Down arrow (↓) — &darr;
Degree (°) — &#176;
Pi (π) — &#960;
For a complete list of available HTML entities, refer to Wikipedia’s page on [HTML entities](https://en.wikipedia.org/wiki/List_of_XML_and_HTML_character_entity_references).

## Table Formatting

==This can be useful.==

### Line breaks within table cells

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |

### Lists Within Table Cells

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

## Table of contents

==This can be useful.==

#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)
