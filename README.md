# KazumiRulesR18

自用 Kazumi 自定义规则仓库（兼容 Kazumi API Level 9，规则仓库结构参考 [Predidit/KazumiRules](https://github.com/Predidit/KazumiRules)）。

## 使用方法

在 Kazumi 客户端中进入 **规则仓库** 页面，点击右上角 **链接图标（规则仓库地址）**，填入以下任一地址：

- **直连地址**：
  `https://raw.githubusercontent.com/misaka0721/KazumiRulesR18/main/`
- **代理镜像示例（大陆网络备用）**：
  `https://gh-proxy.org/https://raw.githubusercontent.com/misaka0721/KazumiRulesR18/main/`

## 维护说明

- 规则文件命名为 `<name>.json`，且文件名必须与 JSON 内的 `"name"` 字段严格一致。
- 推送新的或修改后的 `*.json` 规则文件到 `main` 分支后，GitHub Actions 会自动运行 `script/update_index.dart` 更新 `index.json` 与下方列表。

## Available Rules

| Name | Version | Last Update |
|------|---------|-------------|
| hanime1 | 1.0 | 2026-11-15 |
| hanimeone | 1.0 | 2026-11-15 |
| hstream | 1.0 | 2026-11-15 |
| kanav | 1.0 | 2026-11-15 |
| oppaistream | 1.0 | 2026-11-15 |