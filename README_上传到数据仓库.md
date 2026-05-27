# 仓库库存系统 - GitHub 数据仓库文件

把本文件夹里的文件上传到你的 `warehouse-query-data` 仓库根目录：

- `inventory_stock.json`：库存主数据，所有尺码库存默认 0。
- `admins.json`：子管理员数据，初始为空。
- `.nojekyll`：GitHub Pages 辅助文件。

上传后，数据地址应为：

```text
https://baihui-sudo.github.io/warehouse-query-data/inventory_stock.json
```

后续库存管理端会自动更新 `inventory_stock.json`，查看端会每隔几秒自动读取最新数据。

注意：这个方案基于 GitHub，属于准实时同步，不是数据库级毫秒同步。GitHub Pages 有时会有 1～数十秒缓存延迟。
