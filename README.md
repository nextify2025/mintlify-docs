# Mintlify 入门套件

使用入门套件快速部署并自定义你的文档。

点击本仓库顶部的绿色 **Use this template** 按钮，复制 Mintlify 入门套件。该套件包含以下示例：

- 指南页面  
- 导航  
- 自定义  
- API 参考页面  
- 常用组件的使用  

**[查看完整快速入门指南](https://starter.mintlify.com/quickstart)**

## 开发

安装 [Mintlify CLI](https://www.npmjs.com/package/mint) 以在本地预览文档更改。安装命令如下：

```

npm i -g mint

```

在 `docs.json` 所在的文档根目录运行：

```

mint dev

```

本地预览地址为 `http://localhost:3000`。

## 发布更改

从 [控制台](https://dashboard.mintlify.com/settings/organization/github-app) 安装我们的 GitHub 应用，即可将仓库的更改自动同步到部署环境。推送到默认分支后，更改将自动上线。

## 需要帮助？

### 故障排查

- 若开发环境无法运行：执行 `mint update` 确保 CLI 为最新版本。  
- 若页面返回 404：请确认当前目录存在有效的 `docs.json`。

### 资源

- [Mintlify 文档](https://mintlify.com/docs)