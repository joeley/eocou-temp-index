# Eocou Site

Eocou 的静态展示页，使用 Astro 构建。

## 本地运行

```bash
npm install
npm run dev
```

## 构建

```bash
npm run build
```

构建产物输出到 `dist/`。

## 阿里云 ESA Pages

仓库根目录已经包含 `esa.jsonc`，ESA Pages 会优先使用它：

```text
Install command: npm ci
Build command: npm run build
Output directory: dist
```

如果 ESA 的 Node 版本可选，选择 Node.js 22 或更新版本。
