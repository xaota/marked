# javascript-markdown

## Установка
```shell
$ npm install javascript-markdown
```

### Настройка браузера
Надо настроить в вашем сервере резолв с `/javascript-markdown` в `node_modules/javascript-markdown`.

```html
  <script type="importmap">
  {
    "imports": {
      "javascript-markdown": "/javascript-markdown/index.js"
    }
  }
  </script>
```

## Использование
```javascript
import markdown from 'javascript-markdown';


```

### Дополнительно
Если вы используете vscode, можно настроить резолв для корректной работы самого редактора с помощью файла `jsconfig.json`
```json
{
  "compilerOptions": {
    "baseUrl": "../node_modules/",
    "paths": {
      "javascript-markdown/*": ["./javascript-markdown/library/*"]
    }
  }
}
```
