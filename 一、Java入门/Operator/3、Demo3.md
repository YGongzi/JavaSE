```Java
package com.itgongzi.operator;

public class OperatorDemo3 {
    public static void main(String[] args) {
        int m = 5;
        int n = 3;
        //m 5         6      5    4
        //n 3                           4     3
        //            6  -  5  +  5  -  4  +  4  + 3
        int result = ++m - --m + m-- - ++n + n-- + 3;
        System.out.println(result);
        System.out.println("-------------");

        //+=
        double a = 9.5;
        double b = 520;
        a += b;//a = a + b
        System.out.println(a);

        //-=
        double a1 = 1314;
        double b1 = 520;
        a1 -= b1;//a = a - b
        System.out.println(a1);

        byte x = 10;
        byte y = 20;
        //x = x + y;//编译报错
        x += y; //x = (byte) (x + y);
        System.out.println(x);
    }
}
```