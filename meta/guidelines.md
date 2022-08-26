# Guidelines

How to structure pages, and all the rules you should follow


## Files

### File formatting

Files are in [markdown](https://github.com/marketplace/actions/markdown-docs), a formatting language. It is fairly simple to learn, [read this](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github) to get started. Files *should* follow the [*Markdown Styleguide*](https://github.com/style-guides/Markdown), but we're not too strict about that.


### File names

All markdown files should be named according to the page's title (omitting "The", or any other [articles](https://www.grammarly.com/blog/articles/)), lowercased, and pages with multiple words in the title should be hyphenated. For example, a page titled "*The Shopping District*" would be in a file called "shopping-district.md"



### File Placement

ALL wiki pages should be placed at the "root" of the repository. The only exception is meta pages.

ALL files (photos) should be in the `src` directory. They should be linked to like so:

```markdown
![]


### Meta

Pages talking about the wiki itself should be in [`/wiki/meta/`](/wiki/meta/). 


## Writing


### Deficiencies

If a page needs more added to it, or needs to be reviewed by others, put one of the following snippets at the top, just underneath the title.

For incomplete pages:

```markdown
> THIS ARTICLE IS **INCOMPLETE!** YOU CAN HELP BY [CONTRIBUTING TO IT](meta/contributing).
```

and for pages that need review:

```markdown
> THIS ARTICLE **NEEDS REVIEWED!** YOU CAN HELP BY [CONTRIBUTING](meta/contributing).
```


### Tone

Try to sound like a wikipedia article, it makes it more fun. If you want, you can read the [Wikipedia Manual of Style](https://en.wikipedia.org/wiki/Wikipedia:Manual_of_Style) if you really want to.


### Bias and Prejudice

You should be as unbiased as you can in the way that you portray events, people, items, places, et cetera.


### Linking to other pages

Links from one wiki page to another should not include any slashes (`/`) or file extensions (like `.md`). Instead they should link to the page directly. For example:

```markdown
[Matt Rose](roseman)
```
If you are linking to a specific portion of a page, link to that specific heading:

```markdown
[Matt Rose](roseman#Youtube_Carrer)
```

Meta pages should be linked to with only **one slash**, like so:

```markdown
[Contribute!](meta/contributing)
```
Meta pages linking to each other should follow the rules for linking between wiki pages.
