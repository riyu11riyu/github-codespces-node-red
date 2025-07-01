# Node-RED Codespaces Environment

This repository provides a minimal setup for running Node-RED in GitHub Codespaces.
The `scripts/install.sh` script installs helpful Node-RED packages and starts the
editor.

## Example: Display "Hello!" Alert

To show a simple alert message when clicking a button, create an HTML file with
this content:

```html
<button id="helloBtn">Click me</button>

<script>
document.getElementById("helloBtn").addEventListener("click", function() {
    alert("Hello!");
});
</script>
```

Open the file in your browser and click the button to see the alert.
