- JSX = JavaScript + HTML-like syntax, describes UI.
- Virtual DOM = lightweight copy of the UI in memory, used for efficient updates.
- Actual DOM = what is shown on the browser, updated efficiently by React.

#### Dom

- DOM = Document Object Model
- Represents HTML page as a tree of objects/nodes
- Enables dynamic interaction with web pages via JS
- React uses the Virtual DOM to efficiently update the actual DOM

### DOM Example

For HTML like `<h1 id="title">Hello, world!</h1>`, the DOM represents it as a tree:

- Document  
  └─ h1 (id="title")  
   └─ Text node: "Hello, world!"

JavaScript can access and modify this structure:

`js`
document.getElementById("title").textContent = "Hi there!";
