### 1、JDK和JRE

JRE：Java运行时环境，包含了Java虚拟机和基础类库。

JDK：Java开发工具包，包括JRE。

### 2、Java虚拟机的作用

解释运行字节码程序（转换为机器码）消除平台差异性。

### 3、数据类型

#### 八大基本数据类型：

boolean  1字节    byte  1字节    short  2字节    char  2字节

int  4字节    long  8字节    float  4字节    double  8字节   

#### 自动类型转换：

转换原则：从低精度向高精度转换 byte -&gt; short、char -&gt; int -&gt; long -&gt; float -&gt; double

两个char型运算时，自动转换为int型；与别的类型运算时，也会先转换成int型，再做其他类型的自动转换。

#### 装箱和拆箱：

装箱：int -&gt; Integer  拆箱：Integer -&gt; int

#### Java包装类的缓存：

在类中预先创建频繁使用的包装对象，当需要使用某个对象封装的值在缓存的范围内，就返回缓存的对象，否则才进行创建。

Float和Double没有缓存。

