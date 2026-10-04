# Three-view sheets

角色三视图静态资产 ZIP 已按 8 MB 分片上传，分片文件名为 `角色三视图_静态资产包.zip.part01` 至 `.part09`。在仓库根目录执行：

```bash
cat 角色三视图_静态资产包.zip.part* > 角色三视图_静态资产包.zip
sha256sum -c 角色三视图_静态资产包.zip.sha256
unzip -t 角色三视图_静态资产包.zip
```

合并后的 ZIP 大小为 70,438,720 bytes，SHA256 为 `87fee8cee80401b5c55154915ddb65d6ed5e818bfaaa8f700e264a27b6c1a908`。
