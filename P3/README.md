# P3: Feature-branch Git workflow

## Aim
For this practical I practise making a separate branch for a change instead of editing the main branch directly. After checking the changes, the branch can be merged back into main.

## What I did
- Went through the practical topic and tried the example.
- Kept the HTML and CSS in separate files.
- Made a few notes so I can revise the steps later.

## Files
- `index.html` – the page for this practical.
- `style.css` – the external stylesheet.

## Commands / points to remember
```text
git switch -c feature/about-section
# make the changes
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
```

## Result
The practical page is ready. Open `index.html` in a browser to check the layout. For the Git tasks, the commands above are the steps to practise the workflow.

## What I learned
I got a little more comfortable with this topic and understood where it fits into a normal web project.
