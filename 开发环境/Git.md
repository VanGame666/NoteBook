# Git


|                git命令                |           效果            |
| ------------------------------------ | ------------------------- |
| git push origin HEAD:refs/for/master | 代码提交                   |
| git rm -r --cached .                 | 清除.gitignor信息,重新加载 |
| git reset                            | 清除暂存区,工作区不变       |
| git reset --soft HEAD^               | 撤销上一次发布,工作区不变   |

![](vx_images/496154534353476.png =700x)

![](vx_images/306487408049241.png =700x)

---
- 新建文件--->Untracked
- 使用add命令将新建的文件加入到暂存区--->Staged
- 使用commit命令将暂存区的文件提交到本地仓库--->Unmodified
- 如果对Unmodified状态的文件进行修改---> modified
- 如果对Unmodified状态的文件进行remove操作--->Untracked
![](vx_images/100674696148268.png =700x)

