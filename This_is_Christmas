(function () {
    const encryptedCode = "I1RURFRUVGNocmlzdG1hczIwMjQ=";
    function decryptBase64(encodedText) {
        return atob(encodedText);
    }
    function drawChristmasTree() {
        const treeHeight = 10; // Hauteur de l'arbre
        for (let i = 0; i < treeHeight; i++) {
            const spaces = ' '.repeat(treeHeight - i - 1);
            const stars = '*'.repeat(i * 2 + 1);
            console.log(`%c${spaces + stars}`, 'color: green');
        }
        const trunkWidth = 3;
        const trunkHeight = 2;
        const trunkPadding = ' '.repeat(treeHeight - Math.floor(trunkWidth / 2) - 1);
        for (let i = 0; i < trunkHeight; i++) {
            console.log(`%c${trunkPadding + '|'.repeat(trunkWidth)}`, 'color: green');
        }
        console.log('%c\nMerry Christmas!\n the code is :', 'color: red; font-size: 16px; font-weight: bold');
        const decryptedCode = decryptBase64(encryptedCode);
        console.log(`%c${decryptedCode}`, 'color: red; font-style: italic');
    }
    drawChristmasTree();
})();
