# -39.1.-React-Stateful-Stateless
ДЗ 39.1. Компоненти React: Stateful проти Stateless


node -v
npm -v

nvm ls-remote
nvm install 23.5.0 
nvm use 23.5.0 
node -v

npm install -g npm@latest

node -v
npm -v


створення проекту
npx create-react-app my-app

перехід в директорію
cd my-app

запуск сервера 
npm start

додатково встановлення пакетів 
npm install my-app

ігнорування конфліктів між
npx create-react-app my-app --legacy-peer-deps


перехід до директорії
cd my-app

встановлення залежностей
npm install react@18.18.0 react-dom@18.18.0
npm install @testing-library/react@13.4.0

помилки...
npm install --legacy-peer-deps
npm install react@18.2.0 react-dom@18.2.0
npm install @testing-library/react@13.4.0

видалення та повторна ініціалізація
rm -rf node_modules
rm package-lock.json

оновити до останньої
npm install -g npm@latest
встановити залежність
npm install --legacy-peer-deps

виправлення помилок автоматично
npm audit fix
npm audit fix --force



rm -rf package-lock.json node_modules
npm install
npm ls webpack
npm start
SKIP_PREFLIGHT_CHECK=true



////
"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build",
  "test": "react-scripts test",
  "eject": "react-scripts eject"
}
...видалити кеш за запуск проекта
npx create-react-app my-new-app
cd my-new-app
npm start

npm ls -g webpack
npm uninstall -g webpack

SKIP_PREFLIGHT_CHECK=true
npm start
npm install react-scripts@latest

npm ls webpack


npm install --save-dev @babel/plugin-proposal-private-property-in-object
npm start
