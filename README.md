# MOSES 更新源

本仓库只放更新清单，安装包用 GitHub Releases 发布。

## 客户检查更新地址

```
https://raw.githubusercontent.com/qaqqqe1123/moses-update/main/latest.json
```

## 发新版步骤

1. 打包得到 `MOSES_Setup_vX.Y.Z.exe`
2. 本仓库创建 Release：Tag 例如 `v1.0.1`，上传该 exe
3. 修改 `latest.json` 的 version / notes / download_url / download_url_cn（国内：https://4275.com/bqtgku）
4. 提交并 push `latest.json` 到 `main`
