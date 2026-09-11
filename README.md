# AutoRefreshComicsList

建议直接用github.io制作这个项目

打开后直接就是卡片式目录

index.html文件会自动生成

pages文件夹需要自己创建，文件就放在这里面

此仓库的功能就是，自动索引你pages文件夹内的html文件，生成目录，并以每个html文件的标题（不是html文件名）和其内第一张图作为封面，生成一个实时的漫画网站首页

html用url/base64图片做成的类似telegraph的漫画阅读器，此处不包含漫画html的生成

为防止单调，卡片随机分列，每次刷新都不同

使用的github actions工作流

示例 BGGComics.github.io ，若要直达某个漫画html，链接则是 BGGComics.github.io/pages/7.html

不知道示例能坚持多久，毕竟github不是云盘，单个文件上限25mb

![首页](1.png)

![单独](2.png)
