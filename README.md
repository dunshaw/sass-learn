# sass-learn


## Basics 1 (project1)
``` bash
# 命令行指令
$ compass create <project>

# 编译Sass
$ sass <sass file> <css file> --style
  -- 4种输出风格
     -- nested  
     -- expanded
     -- compact
     -- compressed

# 监视效果
$ sass --watch <sass file>:<css file>

$ compass compile

# 监视文件夹
$ sass --watch <sass folder>:<css folder>

$ compass watch  --force(强制编译)  -(输出风格)

```

## Basics 2 (project2)
``` bash
1.变量 $
2.变量中横线和下划线是一样的  

# 部分文件
_xxx.scss(下划线开头，不会生成css文件，只为了导入)

# 导入
@import()


# work1/sass/index2  
**嵌套**
& -- 引用父选择器

@at-root 跳出嵌套

@at-root (without:all media rule) 4个参数  

@at-root + & 使用

**继承**
@extend  (多继承，链式继承，hover也会被继承。)！包含选择器和兄弟选择器无法被继承

**占位选择器 % **


```
