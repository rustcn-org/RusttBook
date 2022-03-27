# 翻译成果放在哪？
可以说，整个翻译过程最需要注意的就是翻译文件的问题，因此请各位贡献者务必遵循下面的规则。

## 按照类型放入指定目录
选题的 issue 开头就是翻译内容的类型: 文章、资讯、书籍。它们需要分别放入到以下目录中(仓库的根目录下):

- 文章和系列文章: [`Posts`](https://github.com/studyrs/Rustt/tree/main/Posts)
- 书籍: [`Books`](https://github.com/studyrs/Rustt/tree/main/Books)
- 资讯: [`News`](https://github.com/studyrs/Rustt/tree/main/News)


## 图片存储

目前图片统一存储在 [rustt-assets](https://github.com/rustt-org/rustt-assets) 仓库中，对于翻译的文章、书籍，在里面创建同名的目录，然后将图片置入其中。

## 创建文件还是目录

- 文章、资讯: 文件
- 系列文章和书籍：目录

## 文件或目录名

翻译后的文件名规则如下：`[时间] 中文文章名(如果是有名的英文书籍需要附上英文书名).md`，例如 `[22-03-23] Rust程序设计(The Rust Book).md`

## 核心成员的特权
如果你是[核心以上的成员](../rank-points.md)，那么你将拥有将书籍作为一个单独的仓库放入 [StudyRust](https://github.com/studyrs) 组织下的权利。