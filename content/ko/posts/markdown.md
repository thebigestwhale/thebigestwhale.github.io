---
title: Markdown Syntax Guide
date: 2020-01-01
tags:
  - Markdown
  - Example
  - Guide
authors: iolite
excludeSearch: true
comments: true

---

This article offers a sample of basic Markdown syntax that can be used in Hugo content files.
<!--more-->

## Basic Syntax

### Headings

```
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

### Emphasis

```text
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```

*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

### Lists

#### Unordered

```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

* Item 1
* Item 2
  * Item 2a
  * Item 2b

#### Ordered

```
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b
```

### Images

```markdown
![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![GitHub Logo](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

### Links

```markdown
[Hugo](https://gohugo.io)
```

[Hugo](https://gohugo.io)

### Blockquotes

```markdown
As Newton said:

> If I have seen further it is by standing on the shoulders of Giants.
```

> If I have seen further it is by standing on the shoulders of Giants.

### Inline Code

```markdown
Inline `code` has `back-ticks around` it.
```

Inline `code` has `back-ticks around` it.

### Code Blocks

#### Syntax Highlighting

````markdown
```go
func main() {
    fmt.Println("Hello World")
}
```
````

```go
func main() {
    fmt.Println("Hello World")
}
```

### Tables

```markdown
| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |
```

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |


### callout
> [!NOTE] Title
> Contents

> [!INFO] Title
> Contents

---
>NOTE
>
>It works with almost all markdown flavours (the below blank line matters).



----------------------- ------------------------------------
![Tip](images/tip.png)\ Table multiline text bla bla bla bla
                        bla bla bla bla bla bla bla ... the
                        blank line below is important 

----------------------------------------------------------------

| | |
|-|-|
|`NOTE` | This is something I want you to notice. It has a lot of text, and I want that text to wrap within a cell to the right of the `NOTE`, instead of under it.|

## How to write warning in pandoc

::: warn
deprecated, do not use.
:::

::: tips
usefull tips for writing markdown
:::

| | | |
|-|-|-|
|`1위` | 가나다라마바사, 가격은 1원 | 바로가기|


## References

- [Markdown Syntax](https://www.markdownguide.org/basic-syntax/)
- [Hugo Markdown](https://gohugo.io/content-management/formats/#markdown)
