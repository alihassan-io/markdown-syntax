# Markdown Syntax

<!-- Headings -->

# Heading 1

    Markup :  # Heading 1 #

    -OR-

    Markup :  ============= (below H1 text)

## Heading 2

    Markup :  ## Heading 2 ##

    -OR-

    Markup: --------------- (below H2 text)

### Heading 3

    Markup :  ### Heading 3 ###

#### Heading 4

    Markup :  #### Heading 4 ####

##### Heading 5

    Markup :  ##### Heading 5 #####

###### Heading 6

    Markup :  ###### Heading 6 ######

## <!-- Common Text -->

Common text

    Markup :  Common text

<!-- Italic -->

_Italic_

    Markup : _Italic_

<!-- Strikethrough -->

~~Strikethrough~~

    Markup : ~~Strikethrough~~

<!-- Bold -->

**Bold**

    Markup : **Bold** or __Bold__

<!-- Bold & Italic -->

**_Bold & Italic_**

    Markup : ***Bold & Italic*** or ___Bold & Ilatic___

<!-- Horizontal Rule -->

_Horizontal line :_

---

    Markup : ----

<!-- Blockquote -->

> Blockquote

    Markup :  > Blockquote

> > Nested blockquote

    Markup :  >> Nested Blockquote

<!-- Links -->

[Simple Link](https://github.com/alihassan-io)

    Markup : [Simple Link](https://github.com/alihassan-io)

[Link With Title](https://github.com/alihassan-io "Ali Hassan")

    Markup : [Link With Title](https://github.com/alihassan-io "Ali Hassan")

<!-- UL -->

- Unordered List
  - Nested Unordered List

```
    Markup :    - Unordered List
                    - Nested Unordered List
                        - Sub-Nested Unordered List
                - Unordered List
```

<!-- OL -->

1. Ordered List 1
   1. Nested Ordered List 1
   2. Nested Ordered List 2
2. Ordered List 2

```
    Markup :    1. Ordered List 1
                    1. Nested Ordered List 1
                    2. Nested Ordered List 2
                2. Ordered List 2
```

<!-- Foldable text -->

Title With Dropdown Paragraph:

<details>
  <summary>Summary</summary>
  <p>This is paragraph.</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 ConteContent 1</p>
             </details>

<!-- Inline Code Block -->

`<p>This is HTML paragraph.</p>`

    Markup : `<p>This is HTML paragraph.</p>`

![GitHub](https://image.flaticon.com/icons/svg/25/25231.svg)

<!-- GitHub Markdown -->

<!-- Code Block -->

```bash
npm install

npm start
```

```c++
cout<<"Hello Web!";
```

```javascript
console.log("Hello Web!");
```

<!-- Table -->

| Name | Email        |
| ---- | ------------ |
| Tech | tech@web.com |
| Guy  | guy@web.com  |

<!-- Task List -->

- [x] Task 1
- [x] Task 2
- [ ] Task 3
- [ ] Task 4
