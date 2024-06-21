```Java
package com.itgongzi.varible;

public class ASCIIDemo1 {
    public static void main(String[] args) {
        //目标：ASCII编码的特点
        System.out.println('a' + 10);//97+10=107
        System.out.println('A' + 10);//65+10=75
        System.out.println('0' + 10);//48+10=58
        System.out.println('中' + 10);//

        //二进制 八进制 十六进制

        //二进制
        int a1 = 0B01101001;
        System.out.println(a1);

        //八进制
        int a2 = 0141;
        System.out.println(a2);

        //十六进制
        int a3 = 0XFA;
        System.out.println(a3);
    }
}
```