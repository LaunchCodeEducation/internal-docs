---
title: "Aside Boxes"
---

This document shows how to use the `<aside>` tag within your markdown to generate little labeled boxes for your Couscous site. There are 4 built-in options, plus a "custom" option:

| Css Class | Resulting Label |
|-----------|-----------------|
`.aside-note` | ✶ Note
`.aside-warning` | ⚠️ Warning
`.aside-hint` | 🤔 Hint
`.aside-pro-tip` | 🎻 Pro Tip
`.aside-custom` | Whatever You Want

---

## Examples

### Note

Use `aside-note` when you want to acknowledge or call attention to something, but you don't want to break up the flow of your main thought(s). Finish the main flow of thought first, and then insert the note afterwards.

<aside class="aside-note" markdown="1">
If the image above fails to load, then [click here to see Daisy's mock-up](#).
</aside>

Markdown source:

```markdown
<aside class="aside-note" markdown="1">
If the image above fails to load, then [click here to see Daisy's mock-up](#).
</aside>
```

<aside class="aside-note" markdown="1">
Notice the `markdown="1"` attribute. This allows us to write arbitrary markdown inside the `<aside>` tag.

Yay!
</aside>


### Warning

Use `aside-warning` similarly to `aside-note`, but especially in situations where you want to prevent the reader from running into some trouble.

<aside class="aside-warning" markdown="1">
The `markdown="1"` attribute **is required**, even if you don't care about switching back to markdown.

If you leave it off, the alignment of elements in your `<aside>` box will look crappy.
</aside>

Markdown source:

```markdown
<aside class="aside-warning" markdown="1">
The `markdown="1"` attribute **is required**, even if you don't care about switching back to markdown.

If you leave it off, the alignment of elements in your `<aside>` box will look crappy.
</aside>
```


### Hint

Use `aside-hint` to give a hint about how the student might approach a problem.

<aside class="aside-hint" markdown="1">
You will probably need to build up the string as you go, using the [accumulator pattern](#).
</aside>

Markdown source:

```markdown
<aside class="aside-hint" markdown="1">
You will probably need to build up the string as you go, using the [accumulator pattern](#).
</aside>
```


### Pro Tip

Use `aside-pro-tip` to introduce concepts, skills, or cute tricks that are nice-to-have, but not fully necessary, and can be safely ignored without compromising the student's core understanding.

<aside class="aside-pro-tip" markdown="1">
You can write that in one line using the *ternary* operator. Learn more [here](#).
</aside>

Markdown source:

```markdown
<aside class="aside-pro-tip" markdown="1">
You can write that in one line using the *ternary* operator. Learn more [here](#).
</aside>
```


### Custom

If there is some specific label you need, then you can use the `aside-custom` class and set the `label` attribute accordingly.

<aside class="aside-custom" label="Announcement" markdown="1">
Party at Chris's place on Saturday!

(BYO accident insurance)
</aside>

```markdown
<aside class="aside-custom" label="Announcement" markdown="1">
Party at Chris's place on Saturday!

(BYO accident insurance)
</aside>
```
