# gtl.github.com
Share my life and moving moments.
The page is undone and keeps updated...

目录结构
_config.yml 配置文件
_layouts/default.html 默认布局，被index.html引用，Every time you commit a file that specifies layout: default at the top, Jekyll will magically generate the full HTML 
_posts 存储帖子
document by replacing {{ content }} in _layouts/default.html with the contents of the committed file. 
css/main.css
index.html
index.md
.gitigore 不参与Jekyll构建的文件
