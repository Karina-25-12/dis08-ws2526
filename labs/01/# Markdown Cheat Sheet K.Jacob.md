# Markdown Cheat Sheet

> A personal Markdown reference with explanations and examples.

---

## Basic Formatting

### Headings

Use `#` for headings. More `#` = smaller heading.

```markdown
# H1
## H2
### H3
```

**Rendered:**

# H1  
## H2  
### H3

---

### Paragraphs & Line Breaks

Just write text as paragraphs. Use two spaces + Enter for a **line break**.

```markdown
This is a paragraph.  
This is a new line.
```

**Rendered:**

This is a paragraph.  
This is a new line.

---

### Bold

```markdown
**bold** or __bold__
```

**Rendered:** **bold**

---

### Italic

```markdown
*italic* or _italic_
```

**Rendered:** *italic*

---

### Bold + Italic

```markdown
***bold and italic***
```

**Rendered:** ***bold and italic***

---

### Strikethrough

```markdown
~~strikethrough~~
```

**Rendered:** ~~strikethrough~~

---

### Inline Code

```markdown
`code`
```

**Rendered:** `code`

---

## Lists

### Unordered Lists

```markdown
- Item A
* Item B
+ Item C
```

**Rendered:**

- Item A
- Item B
- Item C

---

### Ordered Lists

```markdown
1. First
2. Second
3. Third
```

**Rendered:**

1. First  
2. Second  
3. Third

---

### Nested Lists

```markdown
1. First
   - Subitem 1
   - Subitem 2
2. Second
```

**Rendered:**

1. First  
   - Subitem 1  
   - Subitem 2  
2. Second

---

## Links & Images

### Inline Links

```markdown
[Google](https://www.google.com)
```

**Rendered:** [Google](https://www.google.com)

---

### Reference-style Links

```markdown
[Google][1]

[1]: https://www.google.com
```

**Rendered:** [Google][1]

---

### Images

```markdown
![Alt text](https://via.placeholder.com/100)
```

**Rendered:**  
![Alt text](https://via.placeholder.com/100)

---

### Image + Link

```markdown
[![Alt text](https://via.placeholder.com/100)](https://www.google.com)
```

**Rendered:**  
[![Alt text](https://via.placeholder.com/100)](https://www.google.com)

---

## 💻 Code & Technical Content

### Inline Code

```markdown
Use `len()` to get the length.
```

**Rendered:** Use `len()` to get the length.

---

### Fenced Code Blocks

\`\`\`
function hello() {
  return "Hello!";
}
\`\`\`

### Syntax Highlighting

\`\`\`python
def greet(name):
    return f"Hello, {name}"
\`\`\`

**Rendered:**

```python
def greet(name):
    return f"Hello, {name}"
```

---

## Quotes & Notes

### Blockquotes

```markdown
> This is a quote.
```

**Rendered:**

> This is a quote.

---

### Nested Blockquotes

```markdown
> Outer quote
> > Nested quote
```

**Rendered:**

> Outer quote  
> > Nested quote

---

### Blockquotes with Formatting

```markdown
> **Note:** This is important.
```

**Rendered:**

> **Note:** This is important.

---

## Tables

### Basic Table

```markdown
| Name | Age |
|------|-----|
| Bob  | 25  |
| Ann  | 30  |
```

**Rendered:**

| Name | Age |
|------|-----|
| Bob  | 25  |
| Ann  | 30  |

---

### Alignment

```markdown
| Left | Center | Right |
|:-----|:------:|------:|
| A    |   B    |     C |
```

**Rendered:**

| Left | Center | Right |
|:-----|:------:|------:|
| A    |   B    |     C |

---

### Complex Table (merged manually)

Tables don't support real cell merging. Use formatting tricks instead.

```markdown
| Header | Description       |
|--------|-------------------|
| Row 1  | Line 1<br>Line 2  |
```

---

## Task Lists

```markdown
- [x] Write cheat sheet
- [ ] Upload to repo
- [ ] Share with peers
```

**Rendered:**

- [x] Write cheat sheet  
- [ ] Upload to repo  
- [ ] Share with peers

---

## Dividers & Layout

### Horizontal Rule

```markdown
---
```

**Rendered:**  
---

### Line Breaks

Use two spaces at the end of a line  
like this.

---

## Online & Collaborative Editors

- **HackMD** – https://hackmd.io  
- **Dillinger** – https://dillinger.io  
- **StackEdit** – https://stackedit.io  
- **Typora** – Desktop editor with live preview  
- **Obsidian** – Knowledge management app using Markdown

---

## GitHub Specific

### Task Lists in Issues/PRs

```markdown
- [x] Done
- [ ] To do
```

### Mention Users

```markdown
@octocat
```

### Automatic Linking of Issues/PRs

```markdown
Fixes #42
```

**GitHub renders it as a clickable link to issue 42.**

---

### Emoji Shortcodes

```markdown
:rocket: :smile: :tada:
```

**Rendered:** 🚀 😄 🎉

---
