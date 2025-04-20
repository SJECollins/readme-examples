# Markdown Cheatsheet

This is a quick reference guide for some basic Markdown syntax commonly used in READMEs.

For more in-depth documentation:
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
- [GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

If using VSCode, there is also a handy extension that can help in writing your README quickly with helpful shortcuts (such as generating a Table of Contents):
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

---

## Headings

Use `#` for headings (up to six levels):

    # Heading 1
    ## Heading 2
    ### Heading 3

---

## Text Formatting

    **Bold text**
**Bold text**

    *Italic text*
*Italic text*

    ~~Strikethrough~~
~~Strikethrough~~

    `Inline code`
`Inline code`

---

## Lists

**Unordered List:**

    - Item 1
    - Item 2
      - Nested item
- Item 1
- Item 2
  - Nested Item

**Ordered List:**

    1. First item  
    2. Second item  
       1. Nested item
1. First item
2. Second item
   1. Nested item

---

## Links

    [Link text](https://www.example.com)
[Link text](https://google.com)

---

## Images

    ![Alt text](https://www.example.com/image.png)
![Alt text](https://)

---

## Code Blocks

Use triple backticks (```) for multiline code:

    ```python
    def hello():
        print("Hello, world!")
    ```
```
def hello():
  print("Hello, world!")
```

---

## Blockquotes

    > This is a blockquote.
> This is a blockquote

---

## Collapsible Sections (GitHub only)

    <details>
    <summary>Click to expand</summary>

    Hidden content goes here.

    </details>
<details>
  <summary>Click to expand</summary>

  Hidden content goes here.
  
</details>

---

## Tables

    | Column 1 | Column 2 |
    |----------|----------|
    | Row 1    | Data     |
    | Row 2    | More     |

| Column 1 | Column 2 |
|----------|----------|
| Row 1    | Data     |
| Row 2    | More     |

---

## Horizontal Rule

    ---
---

---

## Notes

- Markdown files use the `.md` extension.
- GitHub and most code editors preview Markdown automatically.
- You can combine formatting (e.g., **_bold italics_** or `code in *italics*`) for more control.
