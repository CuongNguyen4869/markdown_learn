[Source](https://www.markdownguide.org/cheat-sheet/)

# Basic syntax

## 1. Heading

# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
maximum heading level is 6
Alternate syntax for Heading level 1 and 2

Heading level 1
=

Heading level 2
-


## 2. Bold

**bold text**

## 3. Italic

*italicized text*

## 4. Bold and Italic
This is really ***important***

## 5. Blockquote

> This is a blockquote
> This is the first line
> This is the second line
> This is the third line

## 6. Ordered List

1. First item
2. Second item
3. Third item
   
## 7. Unordered List

- First item
- Second item
- Third item
  
## 8. Code

`code`

## 9. Horizontal Rule

---

## 10. Link

https://www.google.com/
[Link to Google](https://www.google.com/)

Disabling automatic URL Linking: 
`https://www.google.com/`

## 11. Image

![example_picture](examplePicture.jpg)

# Extended syntax

## 1. Table

| Category 1 | Category 2 |
| - | - |
| Item 1.1 | Item 2.1 |
| Item 1.2 | Item 2.2 |

### Alignment in table

| Category 1 | Category 2 | Category 3|
| :- | :-: | -: |
| Item 1.1 | Item 2.1 | Item 3.1 |
| Item 1.2 | Item 2.2 | Item 3.2 |

## 2. Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### Syntax highlighting

```cpp
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

[list of language supported](https://docs.readme.com/rdmd/docs/code-blocks)

## 3. Footnote

Here is a sentence with a footnote. [^2]
[^2]: This is the footnote.
Here is another sentence with a footnote. [^another]
[^another]: This is also a footnote. Look at the number.

## 4. Heading ID

### My Great Heading {#custom_id}

## 5. Definition List

API
: application programming interface

www
: World wide web

## 6. Strikethrough

~~The world is flat~~

## 7. Task list

- [ ] Wipe the floor
- [x] Clean the dishes

## 8. Emoji

There is 2 ways to add emoji to Markdown files: copy and paste the emoji into your Markdown-formatted text or type emoji shortcodes.

Example of emoji shortcodes:
:tent: :eggplant:
[List of emoji for markdown](https://gist.github.com/rxaviers/7360908)

## 9. Highlight

I need to hight light these ==very important words==

## 10. Subscript

H~2~O

## 11. Superscript

x^2^ + x^3^y
