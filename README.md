# DEMO_Vue_Flask_Electron_APP 整合應用程式

主要用於驗證微服務應用程式的開發，當該程式啟動時，同時啟動API服務器，通訊方式主要採用API。此專案旨在演示如何使用Electron整合Vue.js和Flask，以創建一個互動式應用程式。在此應用程式中，Flask充當後端伺服器，會在應用程式啟動時運行，這使得在Electron框架下運行的Vue.js前端能夠進行API請求和執行其他操作。

![應用程式示意圖](./doc/demo1.png)

## 專案開發

### 服務器

請閱讀 `./backend/Readme.md` 進行安裝

### 主程式

首先，安裝專案所需的依賴項目：

```bash
npm install
```

### 開發時編譯和熱重載

要在開發環境下啟動專案，請運行以下命令，它會啟用熱重載功能，讓你在開發時能即時看到變更效果：

```bash
npm run dev
```

### 生產環境編譯和壓縮

為了準備生產環境的發佈，運行以下命令來編譯和壓縮專案文件：

```bash
npm run publish
```

### Lints 和文件修正

運行下面的命令來檢查和修復檔案中的語法錯誤或格式問題：

```bash
npm run lint
```

---

請注意，若有特定於專案的配置或命令，建議在 README.md 中詳細說明，以便於新使用者理解和運行專案。若有附加的配置文件或需要預先設置的環境變量，也應在文檔中提供相應的說明。
