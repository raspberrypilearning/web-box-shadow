Je kunt de `shadow` CSS class gebruiken om een slagschaduweffect toe te voegen aan HTML elementen, zoals `<section>`, `<div>`, `<img>`, en `<blockquote>`.

![De tekst 'Lorem ipsum dolor sit amet.' op een roze achtergrond met een slagschaduw.](images/box-shadow.png)

Dit voorbeeld voegt een schaduweffect toe aan een `<blockquote>` element.

--- code ---
---
language: html
filename: index.html
line_numbers: false
---

<main class="page">
  <section class="wrap">
    <blockquote class="secondary shadow"><p>Lorem ipsum dolor sit amet.</p></blockquote>
  </section>
</main>

--- /code ---

Je kunt de eigenschappen van de `shadow` class in `style.css` aanpassen om verschillende schaduw effecten te creëren.

--- code ---
---
language: css
filename: style.css
line_numbers: false
---

.shadow {
   box-shadow: 5px 5px 3px 0px #888888; /* schaduw grootte rechts en onderaan, vervaging, spreiding en kleur */
   /*box-shadow: 5px 5px 4px 2px var(--detail);*/
}

--- /code ---

![De tekst 'Lorem ipsum dolor sit amet.' op een roze achtergrond met een groene slagschaduw.](images/colour-shadow.png)

**Tip:** Try to add colour to your shadows. Use your detail colours `var(--detail)` or `var(--detail2)` to create coloured shadow effects.
