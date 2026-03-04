# Anchor Tag States

Source URL: https://studio.code.org/courses/web-development-2025/units/1/lessons/18/levels/2

An anchor (`<a>`) tag has four states:
1. **link**: when the link has not yet been clicked
2. **visited**: when the link has been clicked (clicking a link "visits" that linked page, hence the name "visited")
3. **hover**: when the mouse is hovered over, but not clicked, the link
4. **active**: the moment the mouse is actively clicking down on the link
We style these states using pseudo-classes. In the example below, we specify the anchor element selector, a colon, and the name of the anchor state:
```
a:hover {
color: yellow;
}
```
Let's give the first two states a try!
## Do This
**In the [CSS file](style.css):**
1. Add a rule to style the "link" state of the `<a>` element.
- The selector of your rule should look like this: `a:link`
- Add the `color` property with a value of your choice.
- This will define what your link looks like when it has not been clicked - Add any other properties of your choice.
<br>
2. Add a rule to style the "visited" state of the `<a>` element.
- The selector of your rule should look like this: `a:visited`
- Add the `color` property with a different color than the "link" state.
- This will define what your link looks like when it has been clicked - Add any other properties of your choice.
**in the preview:**
1. Open [index.html](index.html) and start the live preview.
2. Click on the link. A new tab with "google.com" should open. Come back to Visual Studio Code to see the changes to the look of your link.
- *You may need to Refresh the preview to see the "visited" style applied to your hyperlink*
<br>
<details>
<summary>🔎 <strong>Show Me How To Get Started</strong> 🔍</summary>

<img src="https://images.code.org/c4c850b4e8f10814b57afae9a9ee141f-image-1708196522992.gif" style="width:500px">
</details>

---

## 💡 Copilot Tip

**Need help?** Try asking Copilot:
- "Can you explain what I need to do in this level?"
- "What does [technical term] mean?"
- "I'm stuck on step [number]. Can you give me a hint?"
- "Can you break this down into smaller steps?"

Remember: Copilot is here to guide you, not give you answers. Ask for hints and explanations!
