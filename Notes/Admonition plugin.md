2022-10-25 11:10
Links: [[Obsidian]]
Tags: #obsidian #cheatsheet #popup #icons

# Admonition plugin

## Custom ones

**Custom**
```ad-<type> # Admonition type. See below for a list of available types.
title:                  # Admonition title.
collapse:               # Create a collapsible admonition.
icon:                   # Override the icon.
color:                  # Override the color.
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.
```

```ad-important
title: Isaiah 43:2
icon: broadsword
color: 0, 255, 128
collapse:open

When you pass through the waters, I _will be_ with you; And through the rivers, they shall not overflow you. When you walk through the fire, you shall not be burned, Nor shall the flame scorch you.
```


## General template

```ad-note
title: Title
color: 14, 70, 200
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla.

~~~
title: Title | <nothing>
color: 200, 200, 200
collapse: close
~~~
```


## Quick overview


```ad-note
Name = ad-note

$\sum\frac{\pi}{\sigma}$
```


```ad-warning
Name = ad-warning
```

```ad-bug
Bug example

~~~javascript
throw new Error("Oops, I'm a bug.");
~~~
```

## All types

```ad-important
title: verse
icon: broadsword
color: 0, 255, 128
```

```ad-hint
title: practical
icon: wind
color: 134, 198, 244
```

```ad-seealso
title: note, seealso
```

```ad-abstract
title: abstract, summary, tldr
```

```ad-info
title: info, todo
```

```ad-tip
title: tip, hint, important
```

```ad-success
title: success, check, done
```

```ad-question:
title: question, help, faq
```

```ad-warning
title: warning, caution, attention
```

```ad-failure
title: failure, fail, missing
```

```ad-danger
title: danger, error
```

```ad-bug
title: bug
```

```ad-example
title: example
```

```ad-quote
title: quote, cite
```

```ad-quote
title: Anon
Test
```

---
# References

[Admonition Repo](https://github.com/valentine195/obsidian-admonition)

[Obsidian official callouts](https://help.obsidian.md/How+to/Use+callouts)

Fonts used:
- [Fontawesome](https://fontawesome.com/icons)
- [RPG Awesome](https://nagoshiashumari.github.io/Rpg-Awesome/)

