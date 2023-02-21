# TS-Starter

## How to Start

nvm version >= v16.19.0

```bash
npm install
npm start
```

## How to Test

```bash
npm run test
```

### 參數說明

**package**
typescript：TypeScript 編譯器  
ts-node：用於在 Node.js 中運行 TypeScript 的工具  
@types/node：Node.js 的類型定義文件  
nodemon：用於在代碼變更時重新啟動 Node.js 應用程序的開發工具  

**tsconfig**
target：編譯到的 ECMAScript 版本  
module：編譯成的模塊格式  
outDir：編譯生成的 JavaScript 文件的輸出目錄  
strict：開啟 TypeScript 的嚴格模式  
esModuleInterop：編譯器在處理 ES 模塊和 CommonJS 模塊時使用相同的導入/導出機制  
