用法：git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]



以下是在各种情况下常用的 Git 命令：

**开始一个工作区**（另见：`git help tutorial`）  
- `clone`    将仓库克隆到一个新目录  
- `init`     创建一个空的 Git 仓库或重新初始化一个已有仓库  

**在当前更改上工作**（另见：`git help everyday`）  
- `add`      将文件内容添加到暂存区  
- `mv`       移动或重命名文件、目录或符号链接  
- `restore`  恢复工作区文件  
- `rm`       从工作区和暂存区中移除文件  

**查看历史和状态**（另见：`git help revisions`）  
- `bisect`   使用二分查找找出引入 bug 的提交  
- `diff`     显示提交之间、提交与工作区之间等的差异  
- `grep`     打印匹配模式的行  
- `log`      显示提交日志  
- `show`     显示各种类型的对象  
- `status`   显示工作区状态  

**扩展、标记并调整历史记录**  
- `branch`   列出、创建或删除分支  
- `commit`   将更改提交到仓库  
- `merge`    将两个或多个开发分支合并  
- `rebase`   将提交重新应用到另一个分支的基础上  
- `reset`    将当前 HEAD 重置到指定状态  
- `switch`   切换分支  
- `tag`      创建、列出、删除或验证由 GPG 签名的标签对象  

**协作**（另见：`git help workflows`）  
- `fetch`    从其他仓库下载对象和引用  
- `pull`     从其他仓库或本地分支获取并合并更新  
- `push`     更新远程引用及相关对象  

`git help -a` 和 `git help -g` 列出可用的子命令和一些概念指南。使用 `git help <command>` 或 `git help <concept>` 查看有关特定子命令或概念的说明。使用 `git help git` 查看 Git 系统的概览。