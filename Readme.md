---

# CSS Styling Challenge

In this challenge, you will practice your CSS styling skills by applying styles to different elements in an HTML document. Your goal is to complete the provided CSS code based on the pseudocode provided.

## Getting Started

1. Fork this repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. Open the `index.html` file in a web browser to see the current state of the webpage. You will notice that the page has some structure but lacks proper styling.

## Challenge Tasks

Your task is to complete the CSS styling based on the pseudocode provided in the `styles.css` file. The pseudocode outlines the desired styles for various elements in the HTML document.

Open the `styles.css` file and locate the comments labeled with "target" and "skill" to apply the appropriate styles.

For example, the pseudocode for styling the header element is as follows:
```css
header {
    background-color: #333;
    color: white;
    padding: 1em;
}
```
You need to complete the CSS rules for other elements following a similar pattern.

## Media Query

The pseudocode also includes a media query for responsiveness. Make sure to implement the specified changes to the navigation when the screen width is 600px or less.

## Testing

After completing the CSS styling, refresh the `index.html` page in your web browser to see the updated styling. Ensure that the elements match the desired styles outlined in the pseudocode.

## Submitting Your Solution

Once you're satisfied with your CSS styling, push your changes to your GitHub repository. You can also provide a brief explanation of the changes you made and any challenges you encountered in the README file.

## Solution

If you get stuck or want to compare your solution, you can find the completed CSS code in the `solution.css` file.

---

**Solution:**

```css
/* Reset some default styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Basic styling */
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

/* Header styling */
header {
  background-color: #333;
  color: white;
  padding: 1em;
}

/* Navigation styling */
nav {
  list-style: none;
  display: flex;
}

/* Navigation list item styling */
nav li {
  margin-right: 20px;
}

/* Navigation anchor tag styling */
nav a {
  text-decoration: none;
  color: white;
}

/* Section styling */
section {
  margin: 2em;
}

/* Section heading styling */
h2 {
  margin-bottom: 1em;
}

/* Footer styling */
footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 1em;
}

/* Skills list styling */
.skills-list {
  list-style: none;
  padding: 0;
}

/* Skill list item styling */
.skills-list li {
  margin-bottom: 1em;
}

/* Skill name styling */
.skill-name {
  font-weight: bold;
  margin-bottom: 0.5em;
  display: block;
}

/* Skill bar styling */
.skill-bar {
  width: 100%;
  height: 10px;
  background-color: #ddd;
  border-radius: 5px;
  overflow: hidden;
}

/* Skill level styling */
.skill-level {
  height: 100%;
  background-color: #4caf50;
}

/* Media queries for responsiveness */
@media (max-width: 600px) {
  nav ul {
    flex-direction: column;
  }

  nav li {
    margin-right: 0;
    margin-bottom: 10px;
  }
}
```

---
