# Github test playground

## Topics

* [Headlines](#headlines)
* [Text](#text)
* [Lists](#lists)
    + [Unordered list](#unordered-list)
    + [Ordered list](#ordered-list)
    + [Mixed list](#mixed-list)
* [Links](#tables)
* [Tables](#tables)

## Markdown Syntax

### Headlines

```markdown
# First level

## Second level

### Thrid level
```

### Text

```markdown
**bold**
_italic_
~~striked~~
```

**bold**  
_italtic_  
~~striked~~

### Lists

#### Unordered list

```markdown
* apple
* banana
* grapefruit
```

* apple
* banana
* grapefruit

#### Ordered list

```markdown
1. butter
2. flour
3. milk
```

1. butter
2. flour
3. milk

#### Mixed list

```markdown
1. create dough
    + add sugar
    + add egs
    + add flour
2. mix all incredients together
```

1. create dough
    + add sugar
    + add egs
    + add flour
2. mix all incredients together

### Links

```markdown
* simple link <https://github.com>
* link with different display text [Github](https://github.com)
* link with display text and tooltip [Link to Github with tooltip](https://github.com "Thats the tooltip")
* link to [Help Page](help.md)
```

* simple link <https://github.com>
* link with different display text [Github](https://github.com)
* link with display text and tooltip [Link to Github with tooltip](https://github.com "Thats the tooltip")
* link to [Help Page](help.md)
* link by reference key [Github][github-website]

### Tables

```markdown
Fruit | Color | Taste
------|-------|------
green apple | green | sour
banana | yellow | sweed
kiwi | green | sweed
```

Fruit | Color | Taste
------|-------|------
green apple | green | sour
banana | yellow | sweed
kiwi | green | sweed

## Comments

```markdown
<!-- this is a hidden comment -->
```

<!-- hidden links - use reference key to create a link in your text -->

[github-website]: https://github.com "Tooltip for github"
