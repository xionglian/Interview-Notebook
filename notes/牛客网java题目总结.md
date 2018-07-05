# 对象
### 标识符
以字母开头的字母数字序列。字母：英文字母、_、$、unicode字符中字符（汉字）
### 面向对象五大原则

单一职责、开放封闭、里氏替换、依赖倒置、接口隔离

# 继承
### 覆盖原则

两同两小一大。同：方法名、形参列表；小：异常，返回；大：访问权限

# 多态
条件：继承+重写+父类引用指向子类对象

```
class Father{
	public static Integer i;
	public static void test(){};
	public static Integer j;
	public void test1(){};
}
class Son extends Father{
	public static Integer i;
	public static void test(){};
	public static Integer j;
	public void test1(){};
}
Father f = new Son(); 
```

### 多态绑定机制
f.test() f.test1() f.i f.j
深入理解JVM 第八章第二节
成员变量（实例+静态）、静态方法看左边，非静态方法：编译看左，运行看右


 

# 容器
### 避免ConcurrentModifyException

Iteartor it =..;it.remove();

# 多线程

# 内部类

# 异常

# jsp&servlet

## 九大内置对象

### Exception

<%@page language="java" import="java.util.*" errorPage="error.jsp" isErrorPage="false"/>

isErrorPage=true时才能使用Exception对象


# 判断

final可以用来声明属性和方法，分辨表示属性不可修改以及方法不可继承 错，方法不可覆盖


