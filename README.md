# Github Introduction

## Issue finding:

go to the **issue** tab and filter the search using label for example:- **label: "good first issue"** or a language foe example **language: "javascript"**.

> If we found project we want to contribute to search the project for todo and if found todo in project try to fix it and try to make a pull request for this.

## Markdown basics:

**Heading:**

```markdown
# H1
## H2
### H3
Normal Text
**Bold test**
*Italic text*
~~striketrhough text~~
```
Output:

# H1
## H2
### H3
Normal Text
**Bold test**
*Italic text*
~~striketrhough text~~

---

**Horigonal line**
```markdown
---
```

Output:

---

**Unordered list:**

```markdown
- unordered list item 1
- unordered list item 2
```

Output:

- unordered list item 1
- unordered list item 2

---

**Ordered list:**
```markdown
1. ordered list item 1
2. ordered list item 2
2. ordered list item 3
```
Output:
1. ordered list item 1
2. ordered list item 2
2. ordered list item 3

Note: here above the item 2 and 3 has same numbet then also the github will fix it automatically

---

**Check box:**
```markdown
- [ ] item 1 incomplete
- [x] item 1 complete
```

Output:
- [ ] item 1 incomplete
- [x] item 1 complete

---

**Website link with text:**
```markdowm
[Ishan Joshi](https://github.com/Ishan25j)
```
Output:
[Ishan Joshi](https://github.com/Ishan25j)

---

**If there is a image to displayed having link:**
```markdown
![Ishan Joshi's contribution](https://camo.githubusercontent.com/4a423acdbf1225c3e3a7253098d0909dd8f7c887f97affbdc68c0c22f63b50c7/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170692f746f702d6c616e67733f757365726e616d653d497368616e32356a262673686f775f69636f6e733d74727565267469746c655f636f6c6f723d6666666666662669636f6e5f636f6c6f723d62623261636626746578745f636f6c6f723d6461663764632662675f636f6c6f723d313531353135)
```

Output:
![Ishan Joshi's contribution](https://camo.githubusercontent.com/4a423acdbf1225c3e3a7253098d0909dd8f7c887f97affbdc68c0c22f63b50c7/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170692f746f702d6c616e67733f757365726e616d653d497368616e32356a262673686f775f69636f6e733d74727565267469746c655f636f6c6f723d6666666666662669636f6e5f636f6c6f723d62623261636626746578745f636f6c6f723d6461663764632662675f636f6c6f723d313531353135)

---

**Creating a table:**
```markdown
| column1 | column 2 |
| :--- | ---: |
| row 1a | row1b |
```

Output:
| column1 | column 2 |
| :--- | ---: |
| row 1a | row1b |

---

**Creating a table which is centered:**

```markdown
| column1 | column 2 |
| :--- | :---: |
| row 1a | row1b |
```

Output:
| column1 | column 2 |
| :--- | :---: |
| row 1a | row1b |

---

**Using codeblock inline and a whole line:**

``` `console.log()` is using for printing.```


Output:
`console.log()` is using for printing.

codeblock:

```javascript
const a = 5;
const b = 10;
```

```diff

- const a = 5;
+ const a = 10;
```
Above is used to see the differnce before and after removing.

---

> I have idea 1

I agree with this

> also idea 2

I don't prefer this

---

**Closing the issue when the pull request get's close:**

`closes #<put the number here whose issue we want to close>`

and then add the description

---

**Link for github to learn how to contribute in open source:**

[open source docs link here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqa2M1N04xXzNDV0dXOXRNMEhzRk9ON0pORm1tZ3xBQ3Jtc0ttTXZvdThUbUtwTnA5SC1Sbnl6bTdJVDBKZzVVREN5XzZTVDloSVFnNXIzcHAtVkxaZkRuZVBpREJJMXdlWm5FUjRmb2JqNHN1Z1l5b0gxclRtUmZDdTFuX2RFaUJFZjY0NWdOMlVOMENGS3FvMnFGWQ&q=https%3A%2F%2Fgithub.com%2FfreeCodeCamp%2Fhow-to-contribute-to-open-source)

---

**Make a perfect Repo to develop open source community for your Repo:**

Go to **insight** section and go to **community** section and try to add the best thing possible to make your Repo perfect for contribution.

**Footnote:**

Reference the value in many places using the following method:


`markdown 1. this is text1 with [^1]`

`markdown[^1]: a footnote.`

Output:

1. this is text1 with [^1]

Go to the footer to see footer note.

[^1]: a footnote.
---

**Variable:**

A Variable is used to store a value which can be used in many place through variable.


`markdown[Example 1: Variable link to my gihub page][1]`
`markdown[Example 2: Link Google homepage][2]`

`markdown[1]: https://www.github.com/Ishan25j`
`markdown[2]: https://www.google.com`


Output:

[Example 1: Variable link to my gihub page][1]
[Example 2: Link Google homepage][2]

[1]: https://www.github.com/Ishan25j
[2]: https://www.google.com
