#  Corporate Background Check Skill

> 帮你背调公司。让你**投递更精准、面试有话说、更快获得offer。** 
> 数据可溯源，杜绝 AI 编造。
> 10 大模块报告，面试话术个性化。

🚫 无 AI 编造 · 🚫 无来源模糊 · 🚫 无被动跳过 

***
# 10 大模块预览

| 模块         | 内容                         | 亮点                                 |
| ---------- | -------------------------- | ---------------------------------- |
| 一、 公司基本信息  | 19字段工商表 + 股权结构 + 创始人 + 融资  | 每条标注可信度来源                          |
| 二、 求职者关注点  | JD拆解 + 薪资对比 + 加班文化         | **JD能力拆解：每个要求都匹配你的经历**             |
| 三、 业务健康度   | 市场地位 + 现金流推测 + 优劣势         | 不怕说实话                              |
| 四、 风险预警    | 司法/处罚/管理层/离职口碑             | **每个风险有 🔴🟡🟢 评级**                |
| 五、 行业深度分析  | 机遇挑战 + 上下游图 + 3年趋势         | ASCII树形图直观展示                       |
| 六、 账号矩阵分析  | 社媒布局 + 内容策略 + **平台AI工具推荐** | 按需展开，含（豆包、元宝、点点等）建议                |
| 七、 信息可信度总结 | 8维度 ★ 星级评定                 | 让你知道哪些可信、哪些存疑                      |
| 八、 整体评估与建议 | 适合/不适合人群 + 是否建议投递          | **一句话结论，不模棱两可**                    |
| 九、 面试话术整理  | 自我介绍6件套 + 5类Q&A + 12+反问    | **6组件自我介绍（钩子/1分钟版/速记卡/口诀/关键词/救场）** |
| 十、 深度思考    | 独特洞察 + 待确认清单               | 区别于模板的个性化分析                        |

***
# 工作原理

> 你提供公司名 + 岗位 → AI 搜索全网公开信息 → 生成带来源的报告 → AI 自检标注可疑项 → 你核实关键数据 → 输出干净终稿


## 安装

同时支持 Claude Code / Cursor / Trae / Codex，详见 `RULES.md`。

### 🤖 用 AI Agent 一键安装

把本仓库地址发给你的 AI 编程助手（Claude Code / Codex / Cursor），说"安装这个 skill"：

```
https://github.com/joce-zzz/PreInterview-Corporate-Analysis
```

Agent 会自动完成克隆、配置 profile、验证安装。**约需 1 分钟。**

### 🖥️ 手动安装

```bash
# 克隆到 Claude Code 的 skills 目录
git clone https://github.com/joce-zzz/PreInterview-Corporate-Analysis.git \
  ~/.claude/skills/PreInterview-Corporate-Analysis

# 创建你的个人信息文件
cp ~/.claude/skills/PreInterview-Corporate-Analysis/profile.template.md \
   ~/.claude/skills/PreInterview-Corporate-Analysis/profile.md

# 编辑 profile.md 填入你的真实信息
```

***
# 快速开始

## 前置条件

- **Claude Code** 支持 Skills 功能（将文件夹放入 `~/.claude/skills/` 即可）
- **联网搜索能力**（WebSearch 工具可用）
- ⚠️ **适用范围**：本 Skill 针对**中国企业**设计（依赖天眼查/企查查/Boss直聘等国内平台），其他国家企业请自行调整搜索来源

## 使用

在 Claude Code 中输入：

```
帮我背调一下"上海新炬网络信息技术股份有限公司"
岗位：文案策划，双休
薪资：5-7K·13薪
地点：广州
```

AI 会按 5 个 Phase 自动执行：
1. 检查 profile.md 和输入完整性
2. 搜索各平台公开信息，**输出搜索受阻清单**（哪些需要你登录/补充）
3. 生成 10 模块完整报告（含来源URL）
4. **AI 自检**，标注可疑数据 + URL可追溯性
5. 输出报告 + 验证清单，等待你核实

核实后告诉 AI 修正数据，AI 自动更新终稿。

## FAQ

<details>
<summary>必须填写 profile.md 吗？</summary>

不强制，但强烈建议。没有 profile 信息，二、九、十、模块无法个性化，面试话术会比较通用。填写后 AI 会根据你的经历定制匹配点和话术，质量差异巨大。

</details>

<details>
<summary>AI 生成的数据准确吗？</summary>

不一定。这就是为什么 Skill 内置了 **Phase 3 自检机制** 和 **Phase 4 人工复核**。AI 会主动标注可疑数据，你需要手动核实关键信息。核实后 AI 会更新报告。

</details>

<details>
<summary>生成的背调报告可以分享吗？</summary>

⚠️ **不建议**。报告包含目标公司的真实商业分析数据（股权结构、司法风险、业务健康度评估等），属于敏感信息，请勿上传至公开仓库。`.gitignore` 中已排除 `*_公司背调.md` 防止误提交。

</details>


# License

[MIT](LICENSE.txt) 

---

*Built by **jo_oz**. 愿你拿到心仪的 offer。*
