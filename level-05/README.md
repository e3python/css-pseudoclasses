# Combine Pseudo-class with Classes

Source URL: https://studio.code.org/courses/web-development-2025/units/1/lessons/18/levels/5

What if you have more than one hyperlink and you want to style them differently? Normally when we have several of the same element but we want to style one of them differently we would give that element a class attribute. Good news! We can do the same thing with pseudo-classes!
To do this, we would use our class attribute in our selector, instead of the anchor tag like this:
```
.special:visited {
color: purple;
}
```
Let's try it!
## Do This
**In the [HTML file](index.html):**
1. Give the first hyperlink a "highlight" class attribute.
**In the [CSS file](style.css):**
1. Add a rule for the "hover" state of the anchor tag using its "highlight" class attribute in the selector.
- `.highlight:hover`
2. Style this state with a different background-color and large font size.
3. Add any other different styles to each state of your choice.
**in the preview:**
1. Open [index.html](index.html) and start the live preview.
2. Refresh the preview to make sure your styles have been applied.
3. Hover over the first link to see your "hover" styling.
4. Hover over the second link to confirm it does not have any "hover" styling.
<br>
<details>
<summary>🔎 <strong>Show Me How To Get Started</strong> 🔍</summary>

<img src="https://images.code.org/e78d1254d55db0e3fc7c07d1d9fddc19-image-1708197128500.gif" style="width:500px">
</details>


---

## 💡 Copilot Tip

**Need help?** Try asking Copilot:
- "Can you explain what I need to do in this level?"
- "What does [technical term] mean?"
- "I'm stuck on step [number]. Can you give me a hint?"
- "Can you break this down into smaller steps?"

Remember: Copilot is here to guide you, not give you answers. Ask for hints and explanations!
