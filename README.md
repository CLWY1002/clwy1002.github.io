# clwy1002.github.io
基于Hexo的个人博客


##SAVE分支--保存源码文件
```
hexo/
  |- node_modules/  # hexo需要的模块，不需要上传GitHub
  |- themes/        # 主题文件，需要上传GitHub的dev分支
  |- sources/       # 博文md文件，需要上传GitHub的dev分支
  |- scaffolds/     # 模版文件夹。当您新建文章时，Hexo 会根据 scaffold 来建立文件，需要上传GitHub的dev分支
  |- public/        # 生成的静态页面，由hexo deploy自动上传到master分支
  |- package.json   # 记录hexo需要的包信息，不需要上传GitHub
  |- _config.yml    # 全局配置文件，需要上传GitHub的dev分支
  |- .gitignore     # hexo生成默认的.gitignore，它已经配置好了不需要上传的hexo文件
```
