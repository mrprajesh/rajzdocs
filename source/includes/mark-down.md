# Markdown Syntax


## Heading

```
# Heading 1
## Heading 2 ##
and so on till H6.

A short form for H1 and H2 is
Heading 1
=========
Heading 2
----------
```

## Quoting text

Syntax                  |  Output
------------------------|-------------------------
![](images/quotes0.png)|  ![](images/quotes1.png)


## Source code

```
This is inline `code` and
e.g. Use `git log` to see the commits.
```

- This is inline `code` and
- e.g Use `git log` to see the commits.


***

> This is called code block or fenced code. You may specify the language.

```cpp

  #include <iostream>
  int main(int argc, char* argv[]){
    std::cout << "Hello There!"<< std::endl;
    return EXIT_SUCCESS;
  }
```

<aside class="notice"> Use the below syntax to acquire effect on the right! </aside>
![cpp code block](images/codeblock1.png)

You may mention language from [this list](https://github.com/rouge-ruby/rouge/wiki/List-of-supported-languages-and-lexers ) to enable syntax hightlighting at `line 1`.

## Hyperlinks/Attachments


```
This is [Google](www.google.com) as a link.
```

This is [Google](www.google.com) as a link.

---

```
![Alt text rajzdocs logo](images/logo.png)
![Some logo](http://example.com/logo.png)
```
![Alt text rajzdocs logo](images/logo.png)


## Text formatting
```
*This text will be italic* and _This will also be italic_

**This text will be bold** and __This will also be bold__

_We **can** combine both_

~~This text will be stricked-out~~
```

*This text will be italic* and _This will also be italic_

**This text will be bold** and __This will also be bold__

_We **can** combine both_

~~This text will be stricked-out~~


## List


```
* one // Unordered
* two
* three

1. One // Ordered
2. Two
3. Three

- This is also
- Unordered
- An another way
```
> Multi-level or nesting

```
- Can be nested
  * One.One
  * One.Two
- Can also be nested this way
  1. Two.One
  1. Two.Two. What?
  1. You see this? auto-increment.
- Three
  - Thread.One
```

* one // Unordered
* two
* three

1. One // Ordered
2. Two
3. Three


- This is also
- Unordered
- An another way

__Multi-level or nesting__

- Can be nested
  * One.One
  * One.Two
- Can also be nested this way
  1. Two.One
  1. Two.Two. What?
  1. You see this? auto-increment.
- Three
  - Thread.One

## Horizontal rule

```
If you need horizontal rule then, use three
asterisks,

***

hyphens or underscores like the below.

---

Also, have a blank line before and after!

___
```

If you need horizontal rule then, use three
asterisks,

***

hyphens or underscores like the below.

---

Also, have a blank line before and after!

___


## Table
```
Header 1 | Header 2
-------- | -----------
cell 1x1 | cell 1x2
cell 2x1 | cell 2x2

```
Header 1 | Header 2
-------- | -----------
cell 1x1 | cell 1x2
cell 2x1 | cell 2x2


you may use handy table [generator website](https://www.tablesgenerator.com/markdown_tables) to generate large tables.



## References

- From [the author of Markdown](https://daringfireball.net/projects/markdown/basics)
- Github [Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- [Markdownguide](https://www.markdownguide.org/cheat-sheet/) Cheat-sheet
- [Markdownguide](https://www.markdownguide.org/basic-syntax/) DOs and DONTs


## Not part of markdown

```
This search engine [1] is lot better than [2] and [3]

[1] - www.google.com
[2] - www.yahoo.com
[3] - www.bing.com
```

This search engine [1] is lot better than [2] and [3]
Here's a sentence with a footnote. [^4].

[1] - www.google.com
[2] - www.yahoo.com
[3] - www.bing.com
[^4]: This is the footnote.
