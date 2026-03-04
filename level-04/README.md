# Anchor Pseudo-class Order

Source URL: https://studio.code.org/courses/web-development-2025/units/1/lessons/18/levels/4

It is recommended that if you are going to use all four states for an anchor tag, you create your rule sets in CSS in the following order:
1. link
2. visited
3. hover
4. active
Setting these out of order on your CSS can create unforeseen actions as the cascading style of CSS can have one property overriding another. In short, if there are competing rule sets, styles declared later typically override those declared earlier.
**One way to remember the right order is with the phrase "LOVE, HATE" - LV, HA (Link, Visited, Hover, Active).**
## Do This
**In the [CSS file](style.css):**
1. Add a rule for each of the states for the `<a>` element in the right order.
- `a:link`
- `a:visited`
- `a:hover`
- `a:active`
2. Style each state with a different color and font size.
3. Add any other different styles to each state of your choice.
**in the preview:**
1. Open [index.html](index.html) and start the live preview.
2. Refresh the preview to make sure your styles have been applied.
3. Test each state to make sure they work
- Hover over the link to see your "hover" styling.
- _Slowly_ click on the link to see your "active" styling.
- Click on the link and come back to Visual Studio Code to see if the link changed to your "visited" style.
<br>
<details>
<summary>🔎 <strong>Show Me How To Get Started</strong> 🔍</summary>

<img src="https://images.code.org/2f5beba5755add94ceae9df3522428f8-image-1708196980711.gif" style="width:500px">
</details>


---

## 💡 Copilot Tip

**Need help?** Try asking Copilot:
- "Can you explain what I need to do in this level?"
- "What does [technical term] mean?"
- "I'm stuck on step [number]. Can you give me a hint?"
- "Can you break this down into smaller steps?"

Remember: Copilot is here to guide you, not give you answers. Ask for hints and explanations!
