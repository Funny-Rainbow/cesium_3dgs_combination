# lowalt_spark
基于 https://github.com/sparkjsdev/spark

## 安装方法
0. 克隆本仓库

1. 安装 Node.js  
   （全部默认安装，会自动包含 npm）

2. 安装 Spark、Three 包  
   ```bash
   npm install @sparkjsdev/spark
   npm install three
3. 安装并运行server
   ```bash
   npm install -g serve
   npx serve -p 8088 .

4. 运行示例
网页打开
   ```bash
   http://localhost:8088/combined_cesium_spark.html
(需要将学校3dgs文件放置在对应位置，const splatURL = "./assets/3dgs/JNUAerial-with_Park-y_up.sog";)

---
### 如需其他示例，运行以下步骤，但注意将示例文件及文件夹添加到.gitignore中
5. 前往官方网站安装 Rust
   ```bash
   https://rust-lang.org/tools/install/
6. 构建项目
   ```bash
   npm install
   npm run build
7. 下载必要 assets:
   ```bash
   npm run assets:download
8. 启动示例
   ```bash
   npm start
