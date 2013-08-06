# 基本类型

当使用+=、-=、*=、/=、%=等运算符对基本类型进行运算时，运算符右边的数值将首先被强制转换成与运算符左边数值相同的类型，然后再执行运算，且运算结果与运算符左边的数值类型相同。

Math类的round()方法的运算结果是一个<=(参数值+0.5)的最大整数。

### switch
1. byte、char、short、int四种基本类型以及它们的包装类（JDK5.0以上）都可以用于switch语句；
2. long、float、double、boolean四种基本类型以及它们的包装类都不能用于switch语句；
3. enum类，即枚举类型可以用于switch语句。（JDK5.0以上）
4. 所有类型的对象（包括String类型，在JDK5.0以上要排除byte、char、short、int四种基本类型对应的包装类）都不能用于switch语句。
