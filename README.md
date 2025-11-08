# Welcome to my alx-frontend repository!
-------------
This repository contains various frontend development projects 
which explains the  web development practices in today's world.
These projects include `HTML/CSS`,`JavaScript/TypeScript`, and
`React`. Explained in detail here are the standards, scripts, and 
documentation that are to be used by the projects listed above.

## HTML basics — anatomy & semantics:
------------
Every HTML page follows a basic format:

```
<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>Page title</title>
  </head>
  <body>
    <!-- page content -->
  </body>
</html>

```

The __key elements__ of the HTML page include:
- `<!doctype html>` — This enables the standards mode.
- `<html lang="en">` — This sets the language for accessibility & search engines.
- `<meta charset="utf-8">` — This code is required for character encoding.
- `<meta name="viewport"...>` — This is required for the responsive layout on mobile.
- `Use semantic elements`: Such as `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`. 
__Semantic HTML__ is important because it improves accessibility and SEO.

__An example of a Semantic article:__

```
<article>
  <header><h2>Article title</h2></header>
  <p>Intro paragraph...</p>
  <footer><small>Published <time datetime="2025-10-06">Oct 6, 2025</time></small></footer>
</article>

```

__Accessible skip-link CSS (example):__

```
.skip-link { position: absolute; left: -9999px; top: auto; }
.skip-link:focus { left: 1rem; top: 1rem; }

```

## CSS basics —  Its syntax, selectors & specificity

__CSS rule:__

```
selector { property: value; property2: value2; }

```

Here are some examples of  selectors (brief) used in CSS and they include:
- Type: `p, h1`

- Class: `.btn`

- ID: `#header`

- Attribute: `a[rel="external"]

- Descendant: `.nav a`

- Child: `.nav > a`

- Pseudo-class: `a:hover`, `input:focus`

- Pseudo-element: `h2::after` 

Also, the specificity (ordering priority) used in CSS include:
- Inline style (`style="..."`) → __highest__