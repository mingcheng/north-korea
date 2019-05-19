# 《朝鲜行》的源文件

线上阅读地址 https://www.gracecode.com/north-korea/ ，这里只说明如何将 Markdown 转换为静态文件。

本站点使用 [Hugo](https://gohugo.io/) 静态生成，因此需要在使用前安装 Hugo，具体请参见 Hugo 的官方网站。同时，精简了下名为 Jane 的 Theme，这是套非常适合阅读的皮肤。

使用 `hugo server -D` 本地会启动个 HTTP Server，并 Watch 文件的更改适合本地的文档编写，直接使用 `hugo` 命令将会生成静态文件在 public 目录下。

部署方面，由于是静态文件部署就非常的方便，但考虑到由于发布上线以后，基本上不用做什么修改，同时为了性能方面的考虑，加大了 Cache 的配置，具体参看 `Caddyfile` 文件。

最后，源文件以及相关的资源使用协议，请参照 `LICENSE` 中的相关说明，非常感谢。

`- eof -`
