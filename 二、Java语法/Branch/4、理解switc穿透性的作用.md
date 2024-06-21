```Java
package com.itgongzi.branch;

public class SwitchDemo4 {
    public static void main(String[] args) {
        //理解switc穿透性的作用
        //周一:埋头苦干，解决bug               周二：主动帮助新来的女程序员解决bug
        //周三：主动帮助新来的女程序员解决bug     周四：主动帮助新来的女程序员解决bug
        //周五：今晚吃鸡                    周六：与王婆介绍的小芳相亲
        // 周日：郁郁寡欢，准备上班

        //存在多个case分支的代码是一样的，可以把代码写到一个case块，其他case块通过穿透性能，穿透到case块即可，这样可以简化代码。
        String week = "周二";
        switch (week){
            case "周一":
                System.out.println("埋头苦干，解决bug");
                break;
            case "周二":
            case "周三":
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