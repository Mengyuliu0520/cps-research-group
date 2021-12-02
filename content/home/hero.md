---
widget: hero
headless: true
weight: 5
title: Add a slide here
hero_media: book.svg
design:
  background:
    gradient_start: '#4bb4e3'
    gradient_end: '#2b94c3'
    text_color_light: true
cta:
  url: docs/
  label: Get Started
  icon_pack: fas
  icon: download
cta_alt:
  url: docs/
  label: View Documentation
cta_note:
  label: >-
    <span class="js-github-release" data-repo="wowchemy/wowchemy-hugo-modules">
      Show your product version here:<!-- Automatically filled based on data-repo value -->
    </span>
slides:
  # Choose a theme from https://github.com/hakimel/reveal.js#theming
  theme: black
  # Choose a code highlighting style (if highlighting enabled in `params.toml`)
  #   Light style: github. Dark style: dracula (default).
  highlight_style: dracula
---

# Create slides in Markdown with Wowchemy

[Wowchemy](https://wowchemy.com/) | [Documentation](https://owchemy.com/docs/managing-content/#create-slides)

---

## Features

- Efficiently write slides in Markdown
- 3-in-1: Create, Present, and Publish your slides
- Supports speaker notes
- Mobile friendly slides

---

## Controls

- Next: `Right Arrow` or `Space`
- Previous: `Left Arrow`
- Start: `Home`
- Finish: `End`
- Overview: `Esc`
- Speaker notes: `S`
- Fullscreen: `F`
- Zoom: `Alt + Click`
- [PDF Export](https://github.com/hakimel/reveal.js#pdf-export): `E`

---

## Code Highlighting

Inline code: `variable`

Code block:
```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}
- Only the speaker can read these notes
- Press `S` key to view
{{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}
- Only the speaker can read these notes
- Press `S` key to view
{{< /speaker_note >}}

---

## Themes

- black: Black background, white text, blue links (default)
- white: White background, black text, blue links
- league: Gray background, white text, blue links
- beige: Beige background, dark text, brown links
- sky: Blue background, thin dark text, blue links

---

- night: Black background, thick white text, orange links
- serif: Cappuccino background, gray text, brown links
- simple: White background, black text, blue links
- solarized: Cream-colored background, dark green text, blue links

---

{{< slide background-image="/media/boards.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.reveal section h1,
.reveal section h2,
.reveal section h3 {
  color: navy;
}
```

---
Published with the [Wowchemy Website Builder](https://wowchemy.com/) for Hugo.

Write something interesting about your project here.

<a class="github-button" href="https://github.com/wowchemy/wowchemy-hugo-modules" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star Wowchemy Website Builder for Hugo">Star Wowchemy Website Builder for Hugo</a><br><a class="github-button" href="https://github.com/wowchemy/starter-hugo-project-documentation" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star the Project Docs template">Star the Project Docs template</a><script async defer src="https://buttons.github.io/buttons.js"></script>
