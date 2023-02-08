# 皮皮美食網

一個使用 Node.js + Express 打造的餐廳美食網站，可依照餐廳名稱與類別進行搜尋及預覽。

[Demo Website](http://localhost:3002/)


## 專案畫面

![image](https://github.com/pierceshih15/restaurantList/blob/master/public/img/homePage.png)

![image](https://github.com/pierceshih15/restaurantList/blob/master/public/img/restaurantInfo.png)

![image](https://github.com/pierceshih15/restaurantList/blob/master/public/img/addNewRestaurant.png)

![image](https://github.com/pierceshih15/restaurantList/blob/master/public/img/loginPage.png)

## Features - 產品功能

1. 使用者可以點擊任一餐廳，查看更多餐廳資訊，如地址、電話與簡介
2. 使用者可以依照中文名稱、英文名稱與餐廳類別進行搜尋

## Environment SetUp - 環境建置

1. [Node.js](https://nodejs.org/en/)
2. npm(https://www.npmjs.com/)
3. express 4.16.4版本
4. nodemon
5. express-handlebars 3.0.0

## Installing - 專案安裝流程

1. 打開你的 terminal，Clone 此專案至本機電腦

```
git clone https://github.com/WeiWayne1030/restaurantList.git
```

2. 開啟終端機(Terminal)，進入存放此專案的資料夾

```
cd restaurantList
```

3. 安裝 npm 套件

```
在 Terminal 輸入 npm install 指令
```
4.安裝express 套件

```
在 Terminal 輸入 npm install express@4.16.4 指令
```

5. 安裝 nodemon 套件

```
在 Terminal 輸入 nodemon app.js 指令
```

6. 啟動伺服器，執行 app.js 檔案

```
nodemon app.js
```

7. 當 terminal 出現以下字樣，表示伺服器與資料庫已啟動並成功連結

```
The Express server is running on http://localhost:3002
```

```
note: 若不需要更變，可利用 npm run dev 進行直接預覽
```

## Contributor - 專案開發人員

> [Wayne Sun]([https://github.com/WeiWayne1030])
