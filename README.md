# Scratch2Build — Week 2 CSS Layout Lab

## What is this?

In Tuesday's offline workshop, you will style a simple Student Activity Portal using HTML and CSS. The goal is to practise page layout, Flexbox, CSS Grid, and making a page work on smaller screens.

## Files

* `index.html` — the portal's HTML structure.
* `styles.css` — add your CSS here. It is already linked from `index.html`.

## What to do

1. Create your own branch using the format below.
2. Add a simple CSS reset.
3. Arrange the sidebar and main content so the page layout is clear.
4. Use Flexbox to align the header and navigation items.
5. Use CSS Grid to arrange the dashboard cards.
6. Make the page work on smaller screens without horizontal scrolling.
7. Test your work in the browser and with Chrome DevTools.
8. Commit and push your work, then open a Pull Request targeting `main` before leaving the workshop, following the facilitator's instructions.

## How to submit your work

### 1. Fork the repository

Click the **Fork** button on GitHub to create your own copy of this repository.

### 2. Clone your fork

Copy the URL of your fork, then run:

```bash
git clone <YOUR_FORK_URL>
cd scratch2build-css-layout-lab
```

Replace `<YOUR_FORK_URL>` with the URL of your own fork.

### 3. Create your branch

Create a branch using your name:

```bash
git checkout main
git pull origin main
git checkout -b feature/yourname-responsive-ui
```

Replace `yourname` with your own name, using lowercase letters and hyphens if needed.

### 4. Complete the task

Edit `index.html` and `styles.css`.

Use Flexbox and CSS Grid to arrange the page elements. Check your work in the browser and make sure the page works on smaller screens without horizontal scrolling.

### 5. Commit and push your changes

```bash
git add index.html styles.css
git commit -m "Style responsive activity portal"
git push -u origin feature/yourname-responsive-ui
```

### 6. Open a Pull Request

On GitHub, open a Pull Request from your fork's `feature/yourname-responsive-ui` branch to the original repository's `main` branch.

Make sure the base repository is:

`FCAI-E-Club-Tech-Committee/scratch2build-css-layout-lab`

Use the Pull Request template and briefly explain what you changed.

### 7. Review feedback

If a reviewer requests changes, update your code and push the changes to the same branch. Your existing Pull Request will include the new commits.

## Extra challenge (if you finish early)

Define a few CSS variables inside `:root` and use `var(--...)` to reuse colors in your design.

## Getting help

Try Chrome DevTools first, check the relevant MDN documentation, and then ask your Pod Lead. Mentors can guide you with questions, but they should not type code on your machine.
