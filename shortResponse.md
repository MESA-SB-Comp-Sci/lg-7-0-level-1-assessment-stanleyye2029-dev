# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`?

Describe what makes a unit responsive and why that matters when building a website.

A static unit stays the same, like px, and therefore does not change, a responsive unit like % or vh changes and adapts, responding to changes to things like window size. A responsive unit is a unit that has to change as conditions, like window size, change, and that matters when building a website for accessability, so that computer and phone users can use your site. For example, a working site using static units on computer may work fine, however, on a phone, it may break.

---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?

The first rule, the one that uses width: 400px, will sort of overflow off the screen, because regardless of screen size, the image has to and will be exactly 400px wide no matter the screen size or device. However, the second rule that uses width 50% will be 50% of the small screen, and no matter the screen size, the image width will forever be 50% of the screen. This rule behaves better because it is *responsive*, meaning it can change accordingly when the screen size changes, which is better because now you can see the image on a screen with any size. The first rule was *static*, which meant it did not change, and like I said before, it would be bad for the small screen because you cannot see the whole image.



