# phyblog

极简静态博客生成器。特点是代码少，依赖少，简单，支持 markdown 及 org-mode 两种格式。缺点是简陋。

A very simple static blog generator. Only about 100 lines using python. All details can be found in `s.py` .

# 基本框架 (Frame)

- 使用 Python 语言作为主要语言

- markdown 渲染使用 [https://python-markdown.github.io/](Python-Markdown)

- org-mode 渲染使用 emacs 自带的 org-html-export-to-html: `emacs 'to_be_render.org' --batch --eval '(org-html-export-to-html)'`

# Documention

- 生成所有博客，并生成首页： `python s.py -a`

- 生成单篇博客： `python s.py -p post.org`

- 生成首页： `python s.py -i`

- 生成本地预览： `python s.py -s`

- 其他直接参考 `s.py` 源码


