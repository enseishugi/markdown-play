# Important remarks
1. [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
1. [Other references](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
1. Remember to name files with .md (Markdown) extension.
1. It's similar to org (it's a markup language, after all...).

# Header
## Sub(1)-header
### Sub(2)-header
#### Sub(3)-header
##### Sub(4)-header
###### Sub(5)-header
####### Sub(6)-header
 
# Emphasis
1. For emphasis, both *this* and _this_ work.
1. For bold, both **this** and __this__ work.
1. Both can be combined like __*this*__.

# Lists
## Unordered lists
Start every node with a * character:
* Like
* This
  * And
  * Subtrees
    * Are
    * Supported

## Ordered lists
Start every node with a 1. string:
1. Like
1. This
   1. And
   1. Subtrees
      1. Are
      1. Supported
      
# Hypertext
Both URLs and images can be inserted like [this](https://ncatlab.org/nlab/show/Yoneda+lemma) and ![this](https://ncatlab.org/nlab/files/YonedaObituary.jpg).

# Blockquotes
We can even insert blockquotes by starting lines with >:
> __Yoneda Lemma__
> Let C be a locally small category, and let Psh(C) be the category of presheaves on C.
> Let y : C -> Psh(C) be the Yoneda embedding, then Hom(y(-), X) is a presheaf on C, and...
> ...for any presheaf X in PSh(C) there is a natural isomorphism between Hom(y(-), X) and X.

# Inline code
Markdown supports inline code like `this`.

# Syntax highlighting
These are some very important functions I personally wrote in python3.

```python3
def sum(n):
    s = 0
    for i in range(1, n+1):
        s += i
    return s
    
def smartsum(n):
    return n * (n + 1) / 2
```

# Task Lists
It's recommended to
> include a task list in the first comment of an Issue, you will get a handy progress indicator in your issue list.
> It also works in Pull Requests!

- [ ] Read the Mastering Markdown tutorial. :)
- [x] Getting used to Markdown.

# Tables
Tables are very much like in Org, but here it doesn't fix its visuals automatically (unfortunately)

## Similarities Org/Markdown

Content            | Markdown | Org
-------------------|----------|----
Un/ordered Lists   | o        | o
Tables             | o        | o
Other stuff        | o        | o

...It wasn't meant to be a complete table. :D

# SHA References
> Any reference to a commit's SHA-1 hash will be automatically converted into a link that commit on GitHub

If you noticed, there's a SHA-1 string corresponding to every commit. This quote is refering to that string.

# Issue references within a repository
> Any number that refers to an Issue or Pull Request will be automatically converted into a link.

I don't quite get what this means. Maybe it'll soon be clearer as I get used to GitHub.

# Username @mentions
> Typing an `@` symbol, followed by a username, will notify that person to come and view the comment.

Kind of self-explanatory, ain't it?

# Automatic linking for URLs
Any URL will be automaticall converted into clickable link, exaclty as in Org. See: https://homotopytypetheory.org/2012/05/02/a-type-theoretical-yoneda-lemma/

# Strikethrough
Any word word rapped with two tildes will appear ~~crossed out~~.

# Emoji
GitHub supports emoji, and it's darn important.
1. 
1. [Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

# Conclusions
- [x] Read the Mastering Markodown tutorial. :slightly_smiling_face:
