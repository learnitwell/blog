## Learn IT Well

- 官网：learnitwell.net
- 公众号：Learn IT Well
- 知乎专栏：https://zhuanlan.zhihu.com/learnitwell
- github组织：https://github.com/learnitwell

## 项目安装

1. 下载源码到本地

```
cd ~
git clone https://github.com/learnitwell/blog.git learnitwell
```

2. 初始化

```
cd learnitwell
git submodule init
git submodule update
npm install
```

3. 创建自己的分支

```
git checkout -b author
```

4. 预览

```
hexo s
```

5. 写文章

```
hexo new post
```

6. 投稿

```
git add
git commit -a "comment"
git push origin author
```

7. 申请合并

在github发送pull request到learnitwell/blog项目的master分支