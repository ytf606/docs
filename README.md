# BaishanCloud ATD Document Center

## 安装
文档中心是基于[jekyll](http://jekyllcn.com/)进行开发

```
$ yum install rubygems ruby
$ gem install jekyll
```

## 开发

在根目录下执行如下命令

```bash
$ jekyll serve         # 访问 http://127.0.0.1:4000/
$ jekyll serve --host xxx --port xx
```

## 部署

首次本地开发部署，需保证本地有release分支，并且已更新到最新版本
当在master分支开发测试完毕后执行如下命令

```bash
$ sh build-release.sh
```

服务器每5分钟自动检测代码并更新.
