Levia Zeng — 本地可编辑网站

1. 解压 ZIP，保留整个文件夹结构。
2. 双击 index.html，可直接在浏览器打开主页。
3. 用 VS Code 或其他纯文本编辑器打开 index.html。文字、导航、项目卡片、配色与手机布局均在此文件中，已加分区注释。
4. 图片在 assets/，论文和演示材料在 documents/，NYC 互动页面在 nyc/。不要随意更改文件名，否则需要同步修改 href 或 src。
5. 保存文件后刷新浏览器查看修改。无需 npm、安装依赖或登录。

如果某个互动页面受 file:// 限制，可在此文件夹打开终端，运行：
python3 -m http.server 8000
然后在浏览器打开 http://localhost:8000
按 Ctrl+C 停止服务器。

Google Fonts、期刊、YouTube、LinkedIn 等外部链接需要网络；离线时主页会使用系统备用字体。
修改本地代码不会自动更新线上网站。

内容说明：已去掉 Professional Experience 与挑战杯，Research 仅保留《社会治理》的 DOI 链接，不含 manuscript 或接受信。Baja 图使用硬盘“24赛季巴哈工作/合照”中的原图，U15 和 E7 同框，中间还有一辆 Formula 赛车。
Deep Sky 原始模型的 70%/80% 债务情景存在折现率引用不一致，原文件未修改。
