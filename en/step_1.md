You can use the `shadow` CSS class to add a drop shadow effect to HTML elements including `<section>`, `<div>`, `<img>` and `<blockquote>`.

![Lorem ipsum text on a pink background with a drop shadow.](images/box-shadow.png)

This example adds a shadow effect to a `<blockquote>` element. 

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

You can adjust the properties of the `shadow` class in `style.css` to create different shadow effects. 

--- code ---
---
language: css
filename: style.css
line_numbers: false
---

.shadow {
   box-shadow: 5px 5px 3px 0px #888888; /* right and bottom shadow size, blur, spread and colour */
   /*box-shadow: 5px 5px 4px 2px var(--detail);*/
}

--- /code ---

![Lorem ipsum text on a pink background with a green drop shadow.](images/colour-shadow.png)

**Tip:** Try creating coloured shadows using your detail colours `var(--detail)` or `var(--detail2)` to create coloured shadow effects. 

