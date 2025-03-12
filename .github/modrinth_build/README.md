# 构建 Modrinth 格式整合包

## 如何使用？

`.github\modrinth_build\modrinth_build.yml` 替换 `.github\workflows\curseforge_build.yml`

## 注意事项

由于 `actions/upload-artifact` 目前仅支持上传 .zip 格式的 Artifact，因此构建的 Modrinth 格式整合包需要下载 Artifact 后解压得到 xxxx.mrpack 后再进行常规安装操作