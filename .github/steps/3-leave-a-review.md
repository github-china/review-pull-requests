<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  Historic note: this step combines the commend, approve, and needs changes steps from the previous version.
-->

## Step 3: 提交审查

_你已经成功把自己设为负责人啦! :tada:_

接下来，我们要学习如何对 Pull Request 进行**审查（Review）**。
代码审查的目的，是确保项目质量、保持一致性，并帮助团队成员更好地理解每一次改动。

#### 审查 Pull Request 时，你可以这样做:

1. **先读说明**：通过 Pull Request 的标题和描述（包括相关 issue），了解这次修改的目的。
2. **分析代码差异（diff）**：在项目整体的语境中理解这次改动。
3. **必要时试运行**：实际测试修改后的效果，看是否符合预期。
4. **参考贡献指南**：如果仓库里有 [贡献指南（Contributing Guide）](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)，可以查阅其中的审查规范。


#### 在评论中可以做的事:

* 发现潜在问题、风险或遗漏。
* 提出优化或改进建议。
* 提醒作者注意项目中即将发生的变动。
* 提问以确保彼此理解一致。
* 认可作者做得好的地方。
* 重点反馈最重要的部分。
* 简明清晰，同时提供有价值的信息。
* 以尊重和友善的态度交流。

当你认为修改暂时不需要合并时，可以使用 **comment（评论）**。
如果你觉得改动没问题，可以选择 **approve（批准）**。
若发现还需要修改，则可以选择 **request changes（请求更改）**。

不过因为这个 Pull Request 是你自己创建的，你暂时不能对自己的 PR 进行批准或请求修改。

### :keyboard: 实操环节

1. 在 Pull Request 页面中，点击 **Files changed** tab。
2. 点击右上角的 **Review changes** 按钮。
3. 在输入框中写下你对 Pull Request 的初步想法或反馈。
4. 选择 **Comment**（评论）选项。
5. 点击 **Submit review（提交审查）**。
6. 等待大约 20 秒，然后刷新此页面。
   [GitHub Actions](https://docs.github.com/en/actions) 会自动检测到操作并进入下一步。