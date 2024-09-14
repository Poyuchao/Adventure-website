# Adventure Website

## 概述

這個專案是一個基於 **React** 的網站，展示了世界各地的冒險目的地。

## 功能特色

- **React 基礎**：使用 React 建構可重複使用的元件並管理狀態。
- **切版 (Layout Cutting)**：設計適當的版面結構，非常適合練習 **CSS 佈局** 和響應式設計。
- **React Router**：使用 React Router 實現頁面之間的導航切換。
- **FontAwesome 圖示**：透過 FontAwesome 圖示來增強視覺效果。
- **響應式設計**：使用媒體查詢和響應式設計技術，適應各種裝置的螢幕尺寸。
- **GitHub Pages 部署**：此網站託管於 **GitHub Pages**，任何人皆可訪問。

## 線上展示

你可以透過以下連結查看部署的專案：[Adventure Website](https://poyuchao.github.io/Adventure-website)

## 安裝說明

如果你想在本地運行該專案，請按照以下步驟操作：

1. 克隆此倉庫：

    ```bash
    git clone https://github.com/Poyuchao/Adventure-website.git
    ```

2. 進入專案目錄：

    ```bash
    cd Adventure-website
    ```

3. 安裝依賴包：

    ```bash
    npm install
    ```

4. 啟動開發伺服器：

    ```bash
    npm start
    ```

完成後，可以打開瀏覽器並進入 `http://localhost:3000` 查看專案。

## 部署方式

此專案已經配置好，使用 **GitHub Pages** 進行部署。按照以下步驟進行部署：

1. 編譯專案：

    ```bash
    npm run build
    ```

2. 部署到 GitHub Pages：

    ```bash
    npm run deploy
    ```

請確保 `package.json` 文件中的 `homepage` 字段已正確設置：

```json
"homepage": "https://<你的-GitHub-使用者名稱>.github.io/Adventure-website"
