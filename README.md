# Markdown Syntax<a name="Top"></a>

<!-- The List of Headings (H1 to H6) -->

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

## <!-- A Common Text -->

Common text

    Markup :  This is A Common text

<!-- Italic -->

_Italic_

    Markup : _Italic_

<!-- Strikethrough -->

~~Strikethrough~~

    Markup : ~~Strikethrough~~

<!-- Bold Text -->

**Bold**

    Markup : **Bold** or __Bold__

<!-- Bold & Italic -->

**_Bold & Italic_**

    Markup : ***Bold & Italic*** or ___Bold & Ilatic___

<!-- Monospaced -->

Monospaced

<samp>This is a monospaced text inside a samp tag.</samp>

    Markup: <samp>This is a monospaced text inside a samp tag.</samp>

<!-- Underlined -->

Underlined

<ins>This is a underlined text inside a ins tag.</ins>

    Markup: <ins>This is a underlined text inside a ins tag.</ins>

<!-- Horizontal Rule -->

_Horizontal line :_

---

---

---

    Markup :    -------- (hyphens)
                OR
                ******** (asterisks)
                OR
                ________ (underscores)

<!-- It's a comment. -->

Comments

    Markup  :   <!-- It's a comment. -->

<!-- Blockquote -->

> Blockquote

    Markup :  > Blockquote

> > Nested blockquote

    Markup :  >> Nested Blockquote

<!-- Box -->

Boxed

<table>
    <tr>
        <td>
        The quick brown fox jumps over the lazy dog.
        </td>
    </tr>
</table>

<!-- Subscript & Superscript -->

Subscript & Superscript

3 <sup>73-1</sup> & -2 <sup>30-1</sup>

    Markup:     3 <sup>73-1</sup> & -2 <sup>30-1</sup>

<!-- Footnote -->

A sentence with footnote. [^1]

[^1]: It's a footnote.

    Markup: [^1]: It's a footnote.

[^2]:
    It's a
    multiline footnote.

    Markup : [^2]: It's a
    multiline footnote.

<!-- Alignments -->

Alignments

<p align="left">
<img src="https://www.bettersrv.com/images/logo.png" />
</p>

    Markup:   <p align="left">
              <img src="https://www.bettersrv.com/images/logo.png" />
              </p>

<p align="center">
<img src="https://www.bettersrv.com/images/logo.png"/>
</p>

    Markup:   <p align="center">
              <img src="https://www.bettersrv.com/images/logo.png"/>
              </p>

<p align="right">
<img src="https://www.bettersrv.com/images/logo.png"/>
</p>

    Markup:   <p align="right">
              <img src="https://www.bettersrv.com/images/logo.png"/>
              </p>

<!-- Buttons -->

Button

<kbd>cmd + shift + p</kbd>

    Markup  :   <kbd>cmd + shift + p</kbd>

Button With Space

<kbd> <br> cmd + shift + p <br> </kbd>

    Markup  :   <kbd> <br> cmd + shift + p <br> </kbd>

Button with Link

<kbd>[BetterSrv](https://bettersrv.com/)</kbd>

    Markup  :   <kbd>[BetterSrv](https://bettersrv.com/)</kbd>

<!-- Math expressions -->

Math Expressions

Inline math expression $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$

    Markup  :   Inline math expression $x = {-b \pm \sqrt
                {b^2-4ac} \over 2a}$

Math Expression as a Block

$$
x = {-b \pm \sqrt{b^2-4ac} \over 2a}
$$

    Markup  :   $$
                x = {-b \pm \sqrt{b^2-4ac} \over 2a}
                $$

<!-- Links -->

[Simple Link](https://github.com/alihassan-io)

    Markup : [Simple Link](https://github.com/alihassan-io)

[Link With Title](https://github.com/alihassan-io "Ali Hassan")

    Markup : [Link With Title](https://github.com/alihassan-io "Ali Hassan")

<!-- Unorderd List -->

- Unordered List
  - Nested Unordered List

```
    Markup :    - Unordered List
                    - Nested Unordered List
                        - Sub-Nested Unordered List
                - Unordered List
```

<!-- Ordered List -->

1. Ordered List 1
   1. Nested Ordered List 1a
   2. Nested Ordered List 1b
2. Ordered List 2

```
    Markup :    1. Ordered List 1
                    1. Nested Ordered List 1a
                    2. Nested Ordered List 1b
                2. Ordered List 2
```

<!-- Foldable text -->

Title With Dropdown Paragraph:

<details>
  <summary>Summary</summary>
  <p>This is a paragraph.</p>
</details>

    Markup : <details>
               <summary>Summary</summary>
               <p>This is a paragraph.</p>
             </details>

<!-- Inline Code Block -->

`<p>HTML paragraph</p>`

    Markup : `<p>This is HTML paragraph.</p>`

<!-- Image with alt text -->

Image With Alt Text

![AliHassan.io](https://www.bettersrv.com/images/logo.png "AliHassan.io (Optional)")

    Markup : ![AliHassan.io](https://www.bettersrv.com/images/logo.png "AliHassan.io (Optional)")

<!-- Code Block -->

_Code Block:_

```bash
npm install

npm start
```

    Markup:     ```bash
                npm install
                npm start
                ```

C++ Code Block

```c++
cout<<"Hello Web!";
```

    Markup :    ```c++
                cout<<"Hello Web!";
                ```

HTML Code Block

```html
<h3>HTML</h3>
<p>This is a paragraph tag</p>
```

    Markup  :   ```html
                <h3>HTML</h3>
                <p> This is a paragraph tag </p>

JavaScript Code Block

```javascript
console.log("Hello Web!");
```

    Markup :    ```javascript
                console.log("Hello Web!");
                ```

<!-- Table -->

| Name       | Email               |
| ---------- | ------------------- |
| Ali Hassan | alihassan@gmail.com |

    Markup:     | Name | Email        |
                | ---- | ------------ |
                | Ali Hassan | alihassan@gmail.com |

<!-- Task List -->

**CheckList**

- [ ] Task (uncompleted)
- [x] Task (completed)

```
    Markup  :   - [ ] Task (uncompleted)
                - [x] Task (completed)
```

- [ ] Task (uncompleted)
  - [ ] Subtask (uncompleted)

```
    Markup  :   - [ ] Task (uncompleted)
                - [ ] Subtask (uncompleted)
```

<!-- Link to specific section within page -->

Link to a specific part of the page:

[Scroll To Top](#Top)

    Markup  :   [link text](#section_name)
                section_title<a name="section_name"></a>

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key       | Symbol |
| --------- | ------ |
| Option    | ⌥      |
| Control   | ⌃      |
| Command   | ⌘      |
| Shift     | ⇧      |
| Caps Lock | ⇪      |
| Tab       | ⇥      |
| Esc       | ⎋      |
| Power     | ⌽      |
| Return    | ↩      |
| Delete    | ⌫      |
| Up        | ↑      |
| Down      | ↓      |
| Left      | ←      |
| Right     | →      |
