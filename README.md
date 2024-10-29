function tradeColor(color) {
    const colorList = document.getElementById('colorList');
    const listItem = document.createElement('li');
    listItem.textContent = color;
    colorList.appendChild(listItem);
}

