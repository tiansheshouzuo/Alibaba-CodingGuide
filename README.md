# Alibaba-CodingGuide
阿里巴巴Java开发手册、编程规范

## 1、命名规范
1、类名采用UpperCamelCase风格，遵循驼峰形式，如Merge
2、方法名、参数名、局部变量名、成员变量名一律采用lowerCamelCase风格，遵循驼峰形式，如give、add
3、常量全部大写，单词之间用下划线隔开，如MAX_VALUE
4、包名统一小写，点与点之间有且只有一个单词，如com.alibaba.ai
5、接口类中的方法和属性不要加任何修饰符，尽量保持简洁，如void commit();
6、接口对应的实现类，命令以Impl后缀结尾


## 2、常量定义
1、常量要按照类分别存放在不同的常量类中，如缓存类存放在CacheConsts下，系统配置相关的类存放在ConfigConsts下
2、变量在一定范围内变化，则用enum类定义