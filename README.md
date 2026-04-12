# Purpose of the `develop` Branch  

This is where all development happens before going to `main`.

You will:
- Work on your tasks
- Practice Git workflow
- Collaborate as a team

Do NOT push directly to `main`

---

## About This Challenge  

This project is based on the **Frontend Mentor – Stats Preview Card Component challenge**.
https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62

### Objective  

Build a stats preview card that matches the design as closely as possible.

---

### Challenge Files  

-Take time to understand these before coding.

---

### Commit : Best Practices
When to commit ?

-After a small task

-After a meaningful change

Commit format 
```
feat: add HTML structure  
style: add CSS styling  
fix: correct layout issue  
docs: update README  
setup: project setup 
```
### Pull Request (PR)
Open a Pull Request (PR)
Target: develop branch (never main), 
you will have the explanation of this image just below

<img width="1356" height="580" alt="image" src="https://github.com/user-attachments/assets/33d02ca0-e868-4ed8-9c09-b66815034f11" />


Add a clear description of what you did

Wait for review and apply corrections if needed

A PR is used to:


-Review your work

-Improve your code

-Collaborate

## Branching Strategy (Important)  
What if you need to start a second task before the first is merged?

Start from your previous branch, that is to say the new branch will be based on the previous.

exemple :
```
git checkout feature/salomon-html-structure
git checkout -b feature/salomon-css-style
```

Now you can build on your HTML.

Important: When you open your PR, still target develop, not the HTML branch.

<img width="1356" height="580" alt="image" src="https://github.com/user-attachments/assets/33d02ca0-e868-4ed8-9c09-b66815034f11" />

``Legend:`` As you can see in this image, when you make a Pull Request, your branch will appear where it is framed in orange. You will click on the small triangular button in the green box, then you will see the list of available branches, choose the develop branch as indicated by the blue arrow.

``IMPORTANT :`` Even if your branch is based on another, always merge into develop. This keeps the project clean and avoids chained dependencies.

## About "agent" and "Claude" Files
In this challenge, you may see references to tools like:

``agent``, ``Claude``

These are AI assistants that help generate ideas or code.

``Important:`` Do NOT copy blindly

Always understand what is generated
Use them as helpers, not replacements

## Learning Objective
This challenge is not only about building UI.

You are learning:

-How to work step by step
-How to use Git correctly
-How to think like a developer

### Final Note
You are allowed to make mistakes.
This is part of the process.
We are here to learn, not to be perfect.
