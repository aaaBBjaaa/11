授权培训笔试刷题网页（静态版）

文件：
- index.html：网页页面和答题逻辑
- questions.json：从 Excel 的“单选题-1分每题-40分”工作表提取的 80 道单选题

本地预览：
由于浏览器可能限制 file:// 页面读取 JSON，请不要只双击 index.html 作为最终验证方式。推荐上传到静态网站托管平台后通过网址访问。

部署（以 GitHub Pages 为例）：
1. 登录 GitHub，新建一个仓库。
2. 上传 index.html 和 questions.json（放在同一目录）。
3. 打开仓库 Settings → Pages。
4. 在 Build and deployment 中选择 Deploy from a branch，分支选 main，目录选 /(root)，保存。
5. 等待生成网址，打开网址验证手机和电脑端均可正常刷题。

注意：
- 这是纯静态网页，无账号、无数据库、无后端。
- 题库文件随网页公开发布，知道网址的人可能查看/下载题库；请勿上传保密内容。
- 第一版仅纳入单选题工作表；简答题和论述题未纳入。
