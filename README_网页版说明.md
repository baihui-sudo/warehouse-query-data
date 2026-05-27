仓库货架查询网页版使用说明

用途：
- 这是网页版查询工具，不是 APK。
- 页面会优先读取 GitHub Pages 上的最新 inventory.json：
  https://baihui-sudo.github.io/warehouse-query-data/inventory.json

推荐上传位置：
- 上传到 warehouse-query-data 仓库根目录。
- 也就是和 inventory.json 放在同一层。
- 上传后访问：
  https://baihui-sudo.github.io/warehouse-query-data/

以后怎么更新数据：
- 只需要更新 warehouse-query-data 仓库里的 inventory.json。
- 网页打开时会自动读取最新数据。
- 如果网络失败，页面会使用内置备用数据。

文件说明：
- index.html：网页主文件，直接上传到 GitHub 即可。
- README_网页版说明.md：本说明文件。
