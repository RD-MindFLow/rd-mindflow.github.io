# fe-mindflow.github.io
曼孚科技

# 撰写文章

## 创建文章

发表一篇新文章，你所需要做的就是在 */_posts* 文件夹中创建一个新的文件。文件名的命名非常重要。文章的文件名遵循下面的格式：

    年-月-日-标题.md

下面是一些合法的文件名的例子：

    2011-12-31-new-years-eve-is-awesome.md
    2012-09-12-how-to-write-a-blog.markdown

## 内容相关

所有博客文章顶部必须有一段 YAML 头信息(YAML front-matter)。

### YAML 头信息

    ---
    title: 技术爱好者周刊（第1期）
    tags: 周刊
    key: 10001
    author: 崔鹏程
    ---

在 `---` 之间你可以设置属性的值，key 手动递增即可，tags 为标签，author 为作者。

# 开发

## 安装依赖

前置依赖：
- Ruby
- Bundler
- Jekyll

```bash
bundle install
```

## 本地开发

```bash
bundle exec jekyll serve
```



