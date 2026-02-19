# Part 3: Reflection

### 1. Summarize your understanding of `node_modules` and its relationship with `package.json`.
I think of `package.json` as the project's blueprint or manifest that lists exactly which tools and libraries are needed. The `node_modules` folder is where the actual code for those tools is stored locally. We don't upload the modules to GitHub because they are huge, but since we have the `package.json`, anyone can run `npm install` to get them back.

### 2. What does the ${} syntax do inside backticks? Why is it useful?
The `${}` syntax is used for string interpolation. It lets me put variables or logic directly inside a string without having to break the string apart with plus signs. It makes the code much cleaner and easier to read when I'm building sentences with data.

### 3. What happened when you saved your code in VS Code?
When I saved, my code automatically adjusted its spacing and indentation to look neater. It was helpful because it showed me that my extensions were working to keep the code consistent. I didn't see any new errors in the terminal, so I knew the syntax was okay.

### 4. How many commits did you make for this assignment? Why is it better to make multiple small commits instead of one large commit?
I made 4 commits for this assignment. It's better to do small commits because it’s like saving your progress in a game. If I make a huge mistake, I can just go back to the last small step that worked instead of losing everything I did. It also makes the history easier to follow.

### 5. When do we use `const` vs `let`? What about `var`?
I use `const` for everything by default if the value isn't going to change. I use `let` only when I know I need to reassign the variable later. I avoided `var` because I've learned it's the old way of doing things and can cause bugs with scoping that `const` and `let` fix.