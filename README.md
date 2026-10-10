# publish

制品（Release）发布仓库。

- 发布方：内网制品分发中心 product-portal（ci-cd 流水线）
- 每个产品固定 tag：`publish-latest`，同名附件会在发布时先删后传（覆盖更新）
- 附件名规则：`<分类>__<产品标识>__<平台>__<指令集>__<文件名>`（路径分隔符 `/` 换成 `__`）

本仓库只承载 Release 附件，不需要源码；此 README 仅用于让仓库拥有首个提交
（GitHub 不允许在没有任何提交的空仓库上创建 tag / Release）。
