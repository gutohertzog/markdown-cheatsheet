Markdown Cheatsheet<a name="TOP"></a>
===================

<h3 align="center">Some dinamic data about this repository.</h3>
<p align="center">
<a href="https://github.com/gutohertzog/markdown-cheatsheet/fork" title="Forks">
<img src="https://img.shields.io/github/forks/gutohertzog/markdown-cheatsheet?label=Forks&logo=Github&style=flat-square" alt="Project Initiator Forks"/>
</a>
<a href="https://github.com/gutohertzog/markdown-cheatsheet/stargazers" title="Stars">
<img src="https://img.shields.io/github/stars/gutohertzog/markdown-cheatsheet?label=Stars&logo=Github&style=flat-square" alt="Project Initiator Stars"/>
</a>
<a href="https://github.com/gutohertzog/markdown-cheatsheet/issues" title="Issues">
<img src="https://img.shields.io/github/issues/gutohertzog/markdown-cheatsheet?label=Issues&logo=Github&style=flat-square" alt="Project Initiator Issues"/>
</a>
<a href="https://github.com/gutohertzog/markdown-cheatsheet/pulls" title="Pull Requests">
<img src="https://img.shields.io/github/issues-pr/gutohertzog/markdown-cheatsheet?label=Pull%20Requests&logo=Github&style=flat-square" alt="Project Initiator Pull Requests"/>
</a>
<a href="https://github.com/gutohertzog/markdown-cheatsheet" title="Repo Size">
<img src="https://img.shields.io/github/repo-size/gutohertzog/markdown-cheatsheet?label=Repo%20Size&logo=Github&style=flat-square" alt="Project Initiator Repo Size"/>
</a>
</p>

- - - -
# Heading 1 #

    Markup :  # Heading 1 #
     -OR-
    Markup :  ============= (below H1 text)
     -OR-
    Markup:   <h1>Heading 1</h1>

## Heading 2 ##

    Markup :  ## Heading 2 ##
     -OR-
    Markup: --------------- (below H2 text)
     -OR-
    Markup:   <h2>Heading 2</h2>

### Heading 3 ###

    Markup :  ### Heading 3 ###
     -OR-
    Markup:   <h3>Heading 3</h3>

#### Heading 4 ####

    Markup :  #### Heading 4 ####
     -OR-
    Markup:   <h4>Heading 4</h4>

##### Heading 5 #####

    Markup :  ##### Heading 5 #####
     -OR-
    Markup:   <h5>Heading 5</h5>

###### Heading 6 ######

    Markup :  ###### Heading 6 ######
     -OR-
    Markup:   <h6>Heading 6</h6>


Common text

    Markup :  Common text

_Emphasized / Italic text_

    Markup :  _Emphasized / Italic text_ or *Emphasized / Italic text*

~~Strikethrough text~~

    Markup :  ~~Strikethrough text~~

__Strong / Bold text__

    Markup :  __Strong / Bold text__ or **Strong / Bold text**

___Strong emphasized text___

    Markup :  ___Strong emphasized text___ or ***Strong emphasized text***

[Named Link](http://www.google.com/ "Named link title") and http://www.google.com/ or <http://example.com/>

    Markup :  [Named Link](http://www.google.com/ "Named link title") and http://www.google.com/ or <http://example.com/>

[heading-1](#heading-1 "Goto heading-1")

    Markup: [heading-1](#heading-1 "Goto heading-1")

Table, like this one :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
```

Adding a pipe `|` in a cell :

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | \|

```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \|
```

Left, right and center aligned table

Left aligned Header | Right aligned Header | Center aligned Header
| :--- | :---: | ---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell

```
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | :---: | ---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
```

`code()`

    Markup :  `code()`

```python
    def clear_screen() -> None:
        """Clear screen function of any OS."""
        os.system('cls' if os.name == 'nt' else 'clear')
```

    Markup : ```python
             ```

* Bullet list
    * Nested bullet
        * Sub-nested bullet etc
* Bullet list item 2

~~~
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2
~~~

1. A numbered list
    1. A nested numbered list
    2. Which is numbered
2. Which is numbered

~~~
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
~~~

- [ ] An uncompleted task
- [x] A completed task

~~~
 Markup : - [ ] An uncompleted task
          - [x] A completed task
~~~

- [ ] An uncompleted task
    - [ ] A subtask

~~~
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
~~~

> Blockquote
>> Nested blockquote

    Markup :  > Blockquote
              >> Nested Blockquote

_Horizontal line :_
- - - -

    Markup :  - - - -

_Image with alt :_

![picture alt](http://via.placeholder.com/200x150 "Title is optional")

    Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")

Foldable text:

<details>
  <summary>Title 1</summary>
  <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
</details>
<details>
  <summary>Title 2</summary>
  <p>Content 2 Content 2 Content 2 Content 2 Content 2</p>
</details>

    Markup : <details>
               <summary>Title 1</summary>
               <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
             </details>

```html
<h3>HTML</h3>
<p> Some HTML code here </p>
```

Link to a specific part of the page:

[Go To TOP](#TOP)

    Markup : [text goes here](#section_name)
              section_title<a name="section_name"></a>

Hotkey:

<kbd>⌘F</kbd>

<kbd>⇧⌘F</kbd>

    Markup : <kbd>⌘F</kbd>

Hotkey list:

| Key | Symbol |
| --- | --- |
| Option | ⌥ |
| Control | ⌃ |
| Command | ⌘ |
| Shift | ⇧ |
| Caps Lock | ⇪ |
| Tab | ⇥ |
| Esc | ⎋ |
| Power | ⌽ |
| Return | ↩ |
| Delete | ⌫ |
| Up | ↑ |
| Down | ↓ |
| Left | ← |
| Right | → |

Emoji:

:exclamation: Use emoji icons to enhance text. :+1:  Look up emoji codes at [emoji-cheat-sheet.com](http://emoji-cheat-sheet.com/)

    Markup : Code appears between colons :EMOJICODE:
