# Markdown Syntax<a name="Top"></a>

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

    Markup :  This is A Common text

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

| Name | Email        |
| ---- | ------------ |
| Tech | tech@web.com |
| Guy  | guy@web.com  |

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
