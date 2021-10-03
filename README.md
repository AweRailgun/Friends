# [神龙章轩的永远的好朋友](https://blog.sku.moe/friends/)


## 如何交换友链

- 将神龙章轩的网站添加到自己的友链中：

  - Name：`神龙章轩的博客` 或 `DargonXuan's Blog`
  - URL：`https://sku.moe` 或 `https://blog.sku.moe`
  - Slogan：`真实就在于永远醒不来`
  - Image: `https://cdn.jsdelivr.net/npm/skn/avatar.webp`

- 将你的网站添加到神龙章轩的友链中：

  - 在 GitHub 上 Fork 这个仓库

  - 修改 `src/links.yml` 文件。
    - 按照如下格式将你的网站信息添加到 `links.yml` 文件中：
      ```yaml
      "站点名称": # 请使用双引号包裹
        url: https://example.com # 你的网站的 URL
        img: example.com.png # Logo 的文件名
        text: "Hello, World" # Slogan，请使用双引号包裹

  - 完成上述步骤后，请新建一个 Pull Request。
  
  - 当 Pull Request 被 Review 并被通过、合并后，等待 Github Actions 完成、CDN 更新，你的网站就会出现在我的友链里啦。
