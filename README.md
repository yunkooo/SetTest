# SetTest

## React-basic-template 설치

## Eslint Prettier 설치

`npm i -D eslint prettier`

### npx eslint --init을 하지않고 직접 파일을 생성하고 설정하겠습니다.

## Eslint, Prettier 기본 파일 생성

`.eslintrc.js`, `.eslintignore`, `.prettierrc.js`,`.prettierignore`

## eslint-config-prettier, eslint-plugin-prettier 설치

`npm install -D eslint-config-prettier eslint-plugin-prettier`

## eslint-config-airbnb-base 설치

`npx install-peerdeps --dev eslint-config-airbnb-base`

## eslint-plugin-react, eslint-plugin-react-hooks 설치

`npm i -D eslint-plugin-react eslint-plugin-react-hooks`

## eslint, prettier 저장시 자동 수정 설정

setting.json

```
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }

  // 저장시 자동 변경
  "editor.formatOnSave": true

  // eslint 자동 수정
    "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
```
