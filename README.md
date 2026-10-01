# SQL Injection Lab

一個可部署到 GitHub Pages 的 SQL Injection 資安教育網站。

## 功能

- SQL Injection 基礎原理
- 安全的瀏覽器互動模擬
- Vulnerable Query 概念展示
- Prepared Statement 防禦
- 常見情境
- 學習測驗
- 教師模式

## 部署到 GitHub Pages

1. 建立 GitHub Repository，例如 `SQL-Injection-Lab`
2. 將整個資料夾內容上傳到 `main` branch
3. GitHub Repository → Settings → Pages
4. Source 選擇 `Deploy from a branch`
5. Branch 選 `main`、資料夾選 `/ (root)`
6. 儲存並等待 GitHub Pages 發布

網站不需要後端，也不需要資料庫。

## 安全說明

本專案的互動實驗是前端模擬器，不會連接真實資料庫，也不應用於未授權的網站測試。教學與實驗請限定在自己擁有或明確獲得授權的環境。
