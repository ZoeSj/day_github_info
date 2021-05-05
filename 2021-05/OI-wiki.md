### 项目地址
[OI-wiki](https://github.com/OI-wiki/OI-wiki.git)
[官网](https://oi-wiki.org/)

### 项目简介
OI Wiki是一个免费开放且持续更新的知识整合站点，在这里能获取关于编程竞赛 (competitive programming)有趣又实用的知识，竞赛中的基础知识、常见题型、解题思路以及常用工具等内容，可以更快速深入地学习编程竞赛。

### 如何使用

```
git clone https://github.com/OI-wiki/OI-wiki.git --depth=1

cd OI-wiki

# 安装 mkdocs
pip3 install -U -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple/

# 使用我们的自定义主题
chmod +x ./scripts/install_theme.sh && ./scripts/install_theme.sh

# 两种方法（选其一即可）：
# 1. 运行一个本地服务器，访问 http://127.0.0.1:8000 可以查看效果
mkdocs serve -v

# 2. 在 site 文件夹下得到静态页面
mkdocs build -v

# 获取 mkdocs 的命令行工具的说明（解释了命令和参数的含义）
mkdocs --help
```