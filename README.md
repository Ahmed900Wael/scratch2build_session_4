# Scratch2Build — Week 2 CSS Layout Lab

## What is this?

In Tuesday's offline workshop, you will style a simple Student Activity Portal using HTML and CSS. The goal is to practise page layout, Flexbox, CSS Grid, and making a page work on smaller screens.

## Files

- `index.html` — the portal's HTML structure.
- `styles.css` — add your CSS here. It is already linked from `index.html`.

## What to do

1. Create your own branch using the format below.
2. Add a simple CSS reset.
3. Arrange the sidebar and main content so the page layout is clear.
4. Use Flexbox to align the header and navigation items.
5. Use CSS Grid to arrange the dashboard cards.
6. Make the page work on smaller screens without horizontal scrolling.
7. Test your work in the browser and with Chrome DevTools.
8. Commit and push your work, then open a Pull Request targeting `main` before leaving the workshop, following the facilitator's instructions.

## Branch name

Use your name in the branch name:

```bash
git checkout main
git pull origin main
git checkout -b feature/yourname-responsive-ui
```

Replace `yourname` with your own name, using lowercase and hyphens if needed.

## Save and push your work

```bash
git add index.html styles.css
git commit -m "Style responsive activity portal"
git push -u origin feature/yourname-responsive-ui
```

Then open a Pull Request from your branch into `main` and briefly explain what you changed.

## Extra challenge (if you finish early)

Define a few CSS variables inside `:root` and use `var(--...)` to reuse colors in your design.

## Getting help

Try Chrome DevTools first, check the relevant MDN documentation, and then ask your Pod Lead. Mentors can guide you with questions, but they should not type code on your machine.

> Repository name: confirm the final name with the activity lead before publishing. This name is a suggested one because the Week 2 overview does not specify the lab repository's exact name.
