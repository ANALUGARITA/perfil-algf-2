---
authors: []
categories: []
date: "2021-09-05T00:00:00Z"
slides:
  highlight_style: github
  theme: white
summary: Fotografías del procesado del café en Costa Rica.
tags: []
title: Presentación
---

# Create slides in Markdown with Wowchemy

[Wowchemy](https://wowchemy.com/) | [Documentation](https://wowchemy.com/docs/managing-content/#create-slides)

---

## Tipos de procesado del café

- Natural
- Honey
- Semi-lavado/Lavado

---

{{< slide background-image="/media/cafe/Natural1.png" >}}

## Café Natural

La cereza madura con su piel es secada en camas africanas al sol, manteniendo gran cantidad de sacarosa y ácidos, lo cual crea un sabor exótico y distinguible.

```markdown
{{</* slide background-image="/media/cafe/Natural1.png" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

{{< slide background-image="/media/cafe/cafe-honey.jpg" >}}

## Café Honey

Este café es secado bajo el sol sin su cáscara, manteniendo el mucílago que contiene una gran cantidad de sacarosa y ácidos, lo cual da origen al nombre del proceso Honey y su sabor inigualable.

```markdown
{{</* slide background-image="/media/cafe/cafe-honey.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

{{< slide background-image="/media/cafe/cafe-lavado.jpg" >}}

## Café Semi-Lavado / Lavado

Se separa el grano de café de su cáscara (se despulpa) y, posteriormente, se fermenta en tanques de agua durante horas o incluso días hasta que el mucílago, la capa más fina que recubre el grano, desaparece completamente.

```markdown
{{</* slide background-image="/media/cafe/cafe-lavado.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

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

# Questions?

[Ask](https://github.com/wowchemy/wowchemy-hugo-modules/discussions)

[Documentation](https://wowchemy.com/docs/managing-content/#create-slides)
