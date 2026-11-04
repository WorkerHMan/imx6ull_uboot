# imx6ull/uboot

U-Boot v2026.10 + SPL，正点原子 ATh-DL6Y2C 适配

## 用途

这是 Gerrit 上的项目仓库，评审流程：

```bash
git clone ssh://guoqiangh@localhost:29418/imx6ull/uboot
cd uboot
curl -sS -o .git/hooks/commit-msg http://localhost:8080/tools/hooks/commit-msg
chmod +x .git/hooks/commit-msg

git commit -am "feat: xxx"
git push origin HEAD:refs/for/main
```

详见 `imx6ull/product` 里的 `01_docs/20-Gerrit评审服务器.md`。
