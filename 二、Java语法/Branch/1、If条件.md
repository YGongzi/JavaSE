```Java
package com.itgongzi.branch;

//注意：if（条件）{}。（）后不能跟“；” 否则{}中的代码将不受if的控制
//注意：if（条件）{} else{}
public class IfDemo1 {
    public static void main(String[] args) {
        //if
        //测量用户体温，发现体温高于37度就报警
        double t = 38.5;
        if(t > 37){
            System.out.println("这个人的温度异常，请把带走~~~");
        }

        //发红包：你的钱包余额99元，现在要发出90元，如果未成功，则提示余额不足
        double money = 19;
        if(money > 90){
            System.out.println("红包发成功了~");
        }else{
            System.out.println("余额不足");
        }

        //某个公司有一个绩效系统，根据员工的打分输出对应的绩效级别。[0,60） D [60,80) C [80,90) B [90,100] A
        int score = 10;
        if(score >= 0 && score < 60){
            System.out.println("您的绩效级别是：D");
        } else if (score >= 60 && score < 80) {
            System.out.println("您的绩效级别是：C");
        }else if (score >= 80 && score < 90){
            System.out.println("您的绩效级别是：B");
        }else if(score >= 90 && score <= 100){
            System.out.println("您的绩效级别是：A");
        }else{
            System.out.println("您输入的分数错误~~");
        }
    }
}
```