---
name: npm相关
date: 2022-06-07
---

# npm

## 命令

### 查看全局安装过的包

| 命令      | 解释             |
| --------- | ---------------- |
| npm list  | 显示安装过的包   |
| -g        | 指全局安装过的包 |
| --depth 0 | 限制输出模块层级 |

```
npm list -g --depth 0
```