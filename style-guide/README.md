---
title: Style Guide
---

This is a work-in-progress guide to writing and formatting content for LaunchCode education programs.

We identify three levels of current implementation for each category:

- *Strict*: Follow these guidelines at all times. If you find a violation of the guideline, fix it. Strict guidelines are generally widely-implemented.
- *Moderate*: Implemntation is more flexible -- more readily allowing for exceptions based on context -- and is generally less complete.
- *Aspirational*: Guidelines we aspire to implement more regularly. These are generally less impactful to the student, but are good for standardizing and maintaining a high level of quality.

## Headings

*Strict*

**Levels 1-2**: Use sentence case (all major words of the headline capitalized). For the definition of "major word" we defer to AP style: 

> Capitalize the first word of every letter except articles, coordinating conjunctions, and prepositions of three letters or fewer. There’s one exception: Any word that is the first word in the headline or the last word should be capitalized, regardless of its part of speech.

**Levels 3+**: Capitalie only the first word.

**Code snippets**: Any words or characters that would otherwise be formatted using inline code formatting (e.g. backtics in markdown) should *not* have such formatting applied when part of a heading. Furthermore, the case of such words or characters should not be modified to match the capitalization rules above; they should remain the same case that they would be when used.

## Inline Code Formatting

The following types of items should have inline code formatting applied (e.g. backtics in markdown, or `<code>` elements in HTML):

- Any literal piece of code, including all identifiers and operators
- File and directory names

<aside class="aside-note" markdown="1">
One exception to this rule is when any of these elements appears in a heading. See the [Headings](#headings) section for details.
</aside>

## Application and UI Labels

Format labels for applications menus and other UI components using italics.

<aside class="aside-example" markdown="1">
To open a file in Atom, use *File > Open*.
</aside> 