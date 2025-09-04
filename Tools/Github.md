整体
- Repositories（代码仓库）：用于托管和管理项目代码，开发一个开源库或应用。
- Projects（项目管理看板）：跟踪任务进度。
- Packages（软件包托管）：用于存储和分发软件包（如 npm、Docker、Maven 等）。

> 比较  
> 开发者A想参与项目：访问 Repository → 克隆代码 → 创建分支 → 提交 PR  
> 开发者B只想查看某个文件：点击 Code 标签 → 浏览文件 → 复制片段  
  
单个 repository 下 
- **Code（代码标签页）**：存储和管理项目代码。是仓库内的一个 功能标签页（Tab），仅展示仓库中的 代码文件部分，相当于仓库的“代码浏览器”。
- **Issues（问题追踪）**：项目管理与问题跟踪。 
- **Pull Requests（合并请求）**：开发者将代码变更从分支合并到主分支的请求，触发代码审查（Code Review）流程  
- **Actions（自动化工作流）**：自动化构建、测试和部署，基于YAML配置文件（.github/workflows/），预置多种模板（Node.js, Python等），可定时执行任务（cron语法）。
- **Projects（项目管理）**：项目看板，可关联Issues和PRs。 
- **Wiki（文档系统）**：知识管理，适合存放API文档、教程等。
  
> 迭代流程：Code分支开发 → 创建Issue → 提交PR → Actions自动测试 → 代码审查 → 合并到主分支 → 更新Wiki文档 

  
  
  
### git 快捷键 
Wiki文档中 write 和 preview 切换：Ctrl + Shift + P 

### 资源 
- Git 极简使用指南：https://cloud.tencent.com/developer/article/2531006
- 小白够用教程：https://zhuanlan.zhihu.com/p/372512096
- 官方文档：https://docs.github.com/zh 


