```Java
package com.itgongzi.branch;

public class SwitchDemo2 {
    public static void main(String[] args) {
        //周一:埋头苦干，解决bug             周二：请求大牛程序员帮忙
        //周三：今晚：啤酒，龙虾，小烧烤       周四：主动帮助新来的女程序员解决bug
        //周五：今晚吃鸡                    周六：与王婆介绍的小芳相亲
        // 周日：郁郁寡欢，准备上班

        String week = "周四";
        switch (week){
            case "周一":
                System.out.println("埋头苦干，解决bug");
                break;
            case "周二":
                System.out.println("请求大牛程序员帮忙");
                break;
            case "周三":
                System.out.println("今晚：啤酒，龙虾，小烧烤");
                break;
            case "周四":
                System.out.println("主动帮助新来的女程序员解决bug ");
                break;
            case "周五":
                System.out.println("今晚吃鸡");
                break;
            case "周六":
                System.out.println("与王婆介绍的小芳相亲");
                break;
            case "周日":
                System.out.println("郁郁寡欢，准备上班");
                break;
            default:
                System.out.println("输入的日期有误");
        }
    }
}
```