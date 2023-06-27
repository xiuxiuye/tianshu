# tianshu
## Description
## Git Commit Format
```
<type>(<scope>): <subject>
// 空一行
<body>
// 空一行
<footer>
```
### Header
```
<type>(<scope>): <summary>
```
#### type
- feat: 新增功能
- fix: bug修复
- docs: 文档更新
- style: 格式更新（不影响程序逻辑的代码修改，比如格式化缩进、分号补全等）
- refactor: 重构（即没有新增功能，也没有修复bug）
- perf: 优化相关，比如提升性能、体验
- test: 新增、更新、删除测试用例
- chore: 更新构建相关配置、工具、依赖库等
- revert: 版本回滚
#### scope
说明本次commit的影响范围，比如Controller、DAO、View等等，具体视项目决定。多个scope可以使用
#### summary
对本次commit的简短描述总结
### Body
对本次 commit 修改内容的具体描述, 可以分为多行。
```
# body: 72-character wrapped. This should answer:
# * Why was this change necessary?
# * How does it address the problem?
# * Are there any side effects?
# initial commit
```
### Footer
一些备注, 通常是 BREAKING CHANGE(当前代码与上一个版本不兼容) 或修复的 bug(关闭 Issue) 的链接。


