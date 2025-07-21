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

## Example: Simple Shooting Game

This repository includes `game.html`, a minimal shooting game using HTML5 canvas.
Open the file in your browser. Use the left and right arrow keys to move the
player and press the space bar to fire. Try to score 10 points within one
minute or the game will end.
