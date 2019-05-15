### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
"JS library"
a tool from FB to code...easier...with HTML, CSS, and JS

2.  What is create-react-app?
The command to download a new react project

3.  What is Component Based Architecture?
code storage/organization. easier to delegate tasks. readability. reusability

4.  What is JSX?
JSX is JS that can hold HTML and CSS elements within the "return" element
"syntax extension to JS"

5.  What is the virtual DOM?
A glorious thing that checks your changes to see if it needs to update the file or not.
lightweight DOM to check 

6.  What is unidirectional (one-way) data flow?
code can only read in 1 direction (down)

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

8.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

9.  Explain how data is passed from a parent component to a child component.

### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

14. Compare and contrast one-way data flow with two-way data binding.
