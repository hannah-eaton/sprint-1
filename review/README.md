# Review

## HTML

Looks roughly correct, but style needs a lot of work. Clean, properly-indented and spaced code is very important for readability, and readability is vital for debugging and maintenance. Keep your code pristine, not only for the next developer, but for yourself.

Indent contents of elements two spaces. Use a single blank line between different sections.

Example. Instead of this:

```html
  <head>
    <style type="text/css" media="all">
  p {
    color: red;
  }
</style>
  </head>
```

This:

```html
<head>
  <style type="text/css" media="all">
    p {
      color: red;
    }
  </style>
</head>
```

Also, no need to space between tags and content (the browser strips those spaces out anyway):

Not this:

```html
<p> 2nd paragraph of the 1st article </p>
```

But this:

```html
<p>2nd paragraph of the 1st article</p>
```

Not this:

```html
<p>
1st paragraph of the article
</p>
```

But this:

```html
<p>
  1st paragraph of the article
</p>
```

Watch out for missing end tags, too. While not always required by the standard, they are good practice.

## Accessibility

Roles correct. Nice work.

Actually, with HTML5 these roles are a bit redundant (a `<nav>` is already a navigation element), but some experts recommend using the roles anyway for the moment until browsers catch up. If they ever do. Sigh...

## Usability

Glad you enjoyed the read!

## Empathy

Good feedback. Were you able to read the first chapter of *Search Inside Yourself*? If so, what did you think?

Overall, very nice. Keep up the good work. Please fix the style of your `index.html` file and commit your changes. Looking forward to seeing your work as you progress through the course.

P.S. Congratulations for being the only student in your class who caught on to the proper style for naming GitHub users: snake-case (lowercase separated by hyphens). Your classmates may be sorry later... or not. :-)
