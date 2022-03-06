# Demonstration JavaWeb Project

一个示范性的Javaweb项目，没有采用特殊的框架但是代码结构非常合理，供参考
项目结构如下：

1. Dao类：负责数据库操作，里面是所有数据库操作函数，包括取数、计算、写数，所有需要数据库支持的功能都能且只能调用这个文件夹中的函数
2. entity类：包括所有主要类，比如学生类、教师类、管理员类等
3. filter类：负责设置全局过滤器，一个过滤器就可以使所有网页都支持中文
4. service类：具体的功能实现类，里面的函数负责实现各项功能（关于数据库的功能实现就是在这里调用dao函数）
5. servlet类：在这里实现servlet的功能，一般也是根据条件判断service中的函数
6. util类：工具类，做测试时需要

## 注意：不要尝试运行它，因为配置的原因，肯定跑不动，只看看代码结构就ok，所有类文件都分为函数名文件和impl文件，函数名文件里只写函数名称（表示函数用途），impl文件夹里才写具体代码
