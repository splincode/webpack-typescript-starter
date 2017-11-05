Webpack + TypeScript starter
---

![example](drawing.jpg)

Это далеко не сложный и не полный starter kit. Цель этого репозитория состоит в том, чтобы получить простейшую возможную настройку, для работы с Webpack и TypeScript. Развернув себе этот репозиторий вы сможете дополнитель его своими необходимыми инструментами, которые вам нужны, например, SASS-компиляция, Gzip, Brotli-компрессия. Дополнить тестами свое окружение.

## Features

- [x] Webpack
- [x] TypeScript compilation
- [x] ts-lint
- [x] Webpack Development Server
- [ ] Karma and Jasmine test execution

## How to use

Просто склонируйте репозиторий, а дальше:

```
# change directory to your project
cd  <your-project-name>

# Maybe remove the `.git` directory and start with a fresh one.

# install all dependencies.
$ npm i

# Start developing and serve your app:
npm serve

# Build your app without minification: 
npm run build

# Build your app with minification: 
npm run build:prod
```
