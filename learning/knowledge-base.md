# 知识库构建

- 版本0.1 - **完成**
    - 为Jupyter安装C#核心
    - 使用Jupyter Book构建知识库
        - 安装Jupyter Book
            - `conda install -c conda-forge jupyter-book`
        - 发布HTML到Github Pages：
            - `pip install ghp-import`
            - `ghp-import -n -p -f _build/html`
- 通过目录和Parts构建知识库结构
- 版本0.2 - 未开始
    - 代码.gitignore文件增加_build目录
        - .gitignore文件中增加 `_build/`

参考：

- [Built with Jupyter Book](https://jupyterbook.org/en/stable/intro.html)