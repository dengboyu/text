# JAVA SE源码范畴

0.Unsafe:提供硬件级别原子操作，使其像C语言一样拥有操作内存空间能力，但是也会带来指针问题，提供了82种native方法

```

> park()/unpark()：线程挂起与恢复

```

1.Integer/Long/Character/Number

2.String

```

1).底层final char[] ，toCharArray() --> char[]

```

3.Array

4.Collection

```

> ArrayList
  
  1).底层Object[]  toObject() --> Object[]

```

5.Map

6.Object

7.Thread

```

> JUC(AtmoicInteger)

```

8.IO

9.Reflect

10.Date

```

> Date
  
> Calendar

```

11.Math

12.Network

13.Servlet

14.Filter

15.Interceptor

16.Listener

