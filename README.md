# error-collections

the purpose for this repository is to collect errors met during working & study

##### npm/yarn

- engine error 

场景： 在初始化docz时， 使用yarn add  docz --dev 命令时， 出现本错误

```
like: 

info fsevents@1.2.4: The platform "win32" is incompatible with this module.

```

解决方法：忽略引擎检查

```

yarn add docz --dev --ignore-engine

```
