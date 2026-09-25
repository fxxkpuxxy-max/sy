## Chaoxing Ally v1.1.1

这是 Chaoxing Ally 的首个公开测试版本。

### 主要功能

- 提取学习通页面中的题干和选项
- 调用 DeepSeek 获取候选答案
- 用户明确确认后才填入答案
- 支持停止请求、超时重试和答案缓存
- 支持部分 iframe 页面
- 提供不联网的页面自检功能
- 不自动提交试卷

### 安装

1. 安装 Tampermonkey。
2. 下载本页面附件中的 `chaoxing-ally.user.js`。
3. 使用 Tampermonkey 打开并安装。
4. 在脚本菜单中设置自己的 DeepSeek API Key。

### 注意事项

- 当前版本处于早期测试阶段。
- 学习通页面更新可能导致部分功能失效。
- AI 候选答案可能出错，必须人工核对。
- 题干和选项会被发送至 DeepSeek API。
- 请遵守课程、考试和学校规定。