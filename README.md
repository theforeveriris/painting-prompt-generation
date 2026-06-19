# Anime AI Prompt Generator

一个基于 GitHub Pages 部署的静态网站，用于生成动漫/二次元 AI 绘画提示词。

## 功能

- 从多个维度选择标签，一键生成专业级 AI 绘画提示词
- 支持正面提示词和负面提示词分别选择
- 标签按类别分组，支持 Tab 切换浏览
- 移动端友好的响应式设计
- 一键复制提示词到剪贴板

## 标签维度

| 维度 | 分组数 | 说明 |
|------|--------|------|
| 外貌特征 | 15 | 眼睛、发型、肤色、特殊特征等 |
| 服装搭配 | 9 | 上装、下装、外套、内衣、配饰等 |
| 姿势动作 | 11 | 基础姿势、动态动作、表情、运动等 |
| 场景环境 | 9 | 室内、室外、天气、光影、季节等 |
| 画风风格 | 6 | 主流画风、画师风格、质量标签、氛围、角色类型等 |
| 负面提示词 | 14 | 画质问题、人体结构、AI 生成痕迹等 |

总计约 3000+ 标签，覆盖 AI 绘画提示词的常见需求。

## 技术

纯静态网站，HTML + CSS + JavaScript，无构建步骤。

标签数据以 JSON 格式存储在 `data/` 目录下，便于维护和扩展。

## 使用

访问 [GitHub Pages 部署地址](https://theforeveriris.github.io/painting-prompt-generation/) 即可使用。

## 本地开发

```bash
git clone https://github.com/theforeveriris/painting-prompt-generation.git
cd painting-prompt-generation
# 使用任意静态文件服务器
python -m http.server 8000
```

## 贡献

欢迎提交 Issue 或 Pull Request 补充更多标签。

## License

MIT
