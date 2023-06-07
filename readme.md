## disable select and right click
body {
    user-select: none;
}<br/>
document.addEventListener('contextmenu', event => event.preventDefault());
