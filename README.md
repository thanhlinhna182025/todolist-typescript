#1 npx create-react-app . --template typescript
#2 - npm i -D customize-cra react-app-rewired

- npm i sass
- npm i -D classnames

#3 Tạo file config-overrides.js cung cấp với file package.json. File này dùng để config webpack
#4 Tạo file .babelrc cùng cấp với package.json .File này dùng để config alias
#5 Tạo file .prettierrc dùng để config prettier dùng riêng cho dự án
#6 Tạo file Globals.d.ts dùng để tạo module css
declare module '_.module.css';
declare module '_.module.scss';
#7.Tạo thư mục components 
