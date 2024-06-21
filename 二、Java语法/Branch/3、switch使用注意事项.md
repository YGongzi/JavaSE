```Java
package com.itgongzi.branch;

public class SwitchDemo3 {
    public static void main(String[] args) {
        //switch使用注意事项
        //1、表达式类型只能是byte\shourt\int\char\,jdk7开始支持枚举String、不支持double、float、long
        //这是因为：switch在底层是通过二进制进行比较的，而double\float\long都是64位，而char是16位，所以不支持
        //通俗的来说就是他们的值太大了，不精确。不会有那摩多分支。

        //2、case给出的值不允许重复，且只能是字面量，不能是变量。
        //意思是：case里面的值只能是10,20类似的不重复的字面量，也不能是变量，因为变量的值会发生变化。


        //3、default可以省略，但是不建议省略。

        //4、break可以省略，但是不建议省略。否则会出现穿透现象
        //会一直执行下去
        String a = "10";
        switch(a){
            case "10":
                System.out.println();
                break;
        }
    }
}
```