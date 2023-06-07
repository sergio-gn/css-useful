## disable select and right click
body {
    user-select: none;
}
document.addEventListener('contextmenu', event => event.preventDefault());
