你可以使用 `shadow` CSS 类为 HTML 元素添加阴影效果，例如 `<section>`、`<div>`、`<img>` 和 `<blockquote>`。

![文字“Lorem ipsum dolor sit amet。”在带有阴影的粉色背景上](images/box-shadow.png)

此示例为 `<blockquote>` 元素添加了阴影效果。

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

你可以调整 `style.css` 中 `shadow` 类的属性来创建不同的阴影效果。

--- code ---
---
language: css
filename: style.css
line_numbers: false
---

.shadow {
   box-shadow: 5px 5px 3px 0px #888888; /*右侧和底部阴影的大小、模糊、扩散和颜色 */
   /*box-shadow: 5px 5px 4px 2px var(--detail);*/
}

--- /code ---

![文字“Lorem ipsum dolor sit amet。”在带有绿色阴影的粉色背景上](images/colour-shadow.png)

**提示：**尝试为阴影添加颜色。 使用你的详细颜色 `var(--detail)` 或 `var(--detail2)` 来创建彩色阴影效果。

