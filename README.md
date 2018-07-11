# error-collections

the purpose for this repository is to collect errors met during working & study

- [hexo部署github报错HTTP request failed，提示403](https://blog.csdn.net/u013181595/article/details/75206929)

- docz 在windows环境下安装时platform错误

```

engine error 

场景： 在初始化docz时， 使用yarn add  docz --dev 命令时， 出现本错误



info fsevents@1.2.4: The platform "win32" is incompatible with this module.

```

 解决方法：忽略引擎检查

```

yarn add docz --dev --ignore-engine

```
