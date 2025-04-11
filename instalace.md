# Příprava před kurzem

<hr>

Nastavení vašeho vývojového prostředí.

## 1 Instalace nástrojů
Před tím, než začneme tvořit weby, je potřeba si počítač vybavit nástroji, které nám usnadní práci.
- Internetový prohlížeč
- Visual Studio Code

🧠 **Visual Studio Code** (**_VS Code_**) je chytrý editor na psaní kódu. Pomáhá programátorům díky užitečným nástrojům a rozšířením. Používá ho spousta profesionálů každý den.

<hr>

🛠️ **VS Code** si stáhni z [oficiálních stránek](https://code.visualstudio.com/) – funguje na **Windows**, **Mac** i **Linuxu**.
Pokud už ho máš, zkontroluj verzi v menu:
👉 **_Help → About (Windows/Linux) nebo Code → About VS Code (Mac)_**.

Měla by být aspoň *1.97.0* – jinak dej **_Help → Check for Updates…_**.

📌 **Pozor!** `VS Code` a `Visual Studio` jsou dva různé programy. My používáme jen **VS Code**.

```
{
  "window.zoomLevel": 0,
  "files.autoSave": "off",
  "files.eol": "\n",
  "files.insertFinalNewline": true,
  "editor.tabSize": 2,
  "editor.links": false,
  "editor.renderWhitespace": "boundary",
  "editor.wordWrap": "on",
  "editor.fontSize": 16,
  "editor.multiCursorModifier": "alt",
  "editor.formatOnSave": true,
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "vscode.css-language-features"
  },
  "prettier.singleQuote": true,
  "prettier.arrowParens": "always",
  "prettier.trailingComma": "all"
}
```


