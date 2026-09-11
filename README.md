# EduPersona 配套网页 — GitHub Pages 部署

1. 在 GitHub 新建仓库（例如 EduPersona），把本目录下的 docs/ 文件夹整个上传到仓库根目录。
2. 仓库 Settings → Pages → Build and deployment：Source 选 "Deploy from a branch"，Branch 选 main，文件夹选 /docs，保存。
3. 一两分钟后页面地址为  https://<用户名>.github.io/EduPersona/
   （若仓库名不同，把 EduPersona 换成实际仓库名；若用组织账号，<用户名> 换成组织名）
4. 页面是单文件，图片全部内嵌，不依赖其他文件。
5. 页面顶部三个链接位（论文 PDF、arXiv、代码）在 index.html 里搜 lnk-paper / lnk-arxiv / lnk-code 填入。
