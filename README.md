# Npm Tutorial

# Перевірка версій Node.js та npm

```
node --version — Перевіряє встановлену версію Node.js;
npm --version — Перевіряє встановлену версію npm.
```

# Ініціалізація проекту

```
npm init — Запускає майстер створення package.json;
npm init -y — Створює package.json з налаштуваннями за замовчуванням.
```

# Налаштування конфігурації npm

```
npm config set init-author-name "YOUR_NAME" — Встановлює ім'я автора;
npm config set init-author-email "YOUR_EMAIL" — Встановлює email автора;
npm config list — Показує поточну конфігурацію npm;
npm config get <key> — Отримує значення конкретного налаштування.
```

# Встановлення пакетів

```
npm install <package-name> — Встановлює пакет локально;
npm i <package-name> — Скорочена версія команди;
npm install -g <package-name> — Встановлює пакет глобально;
npm install <package-name> --save-dev — Встановлює пакет як dev-залежність;
npm install <package-name> --save-prod — Встановлює пакет як основну залежність.
```

# Видалення пакетів

```
npm uninstall <package-name> — Видаляє пакет;
npm r <package-name> — Скорочена версія команди;
npm uninstall -g <package-name> — Видаляє глобально встановлений пакет.
```

# Оновлення пакетів

```
npm update — Оновлює всі пакети до minor/patch версій;
npm update <package-name> — Оновлює конкретний пакет;
npm outdated — Показує застарілі пакети;
npm install <package-name>@latest — Встановлює найновішу версію пакета.
```

# Очищення кешу

```
npm cache clean --force — Очищає кеш npm;
npm cache verify — Перевіряє цілісність кешу.
```

# Робота з директоріями

```
cd ~/projects — Перехід до папки "projects" у домашній директорії.
```

# Запуск скриптів

```
npm start — Запускає скрипт start з package.json;
npm run <script-name> — Запускає користувацький скрипт з package.json;
npm run dev — Запускає dev-сервер.
```

# Зупинка сервера або процесу

```
Ctrl + C — Для користувачів Windows;
Control + C — Для користувачів MacOS і Linux.
```

# Управління залежностями

```
npm list — Показує встановлені пакети;
npm list -g --depth=0 — Показує глобально встановлені пакети;
npm ls <package-name> — Показує інформацію про конкретний пакет.
```

# Повторна установка залежностей

```
rm -rf node_modules package-lock.json && npm install — Видаляє папку node_modules і package-lock.json, а потім перевстановлює всі залежності;
npm ci — Встановлює залежності строго за package-lock.json.
```
