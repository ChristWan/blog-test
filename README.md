# 自我介绍
我叫ChristWan，来自无锡，是一名Web前端的初学者
我的爱好是
* 吃饭
* 睡觉
* 玩游戏
* 敲代码（我自己反正信了）

对了，我还有一点点`Java`基础，下面是我写的一个小练习
```java
public class Demo {
    public static void main(String[] args) {
        long time1 = System.currentTimeMillis();
        char[] chs = new char[26];
        for (int i = 0; i <= 25; i++) {
            chs[i] = (char) (i + 'A');
        }
        for (int i = 0; i < 10; i++) {
            System.out.println(getStr(chs));
        }
        long time2 = System.currentTimeMillis();
        System.out.println(time2 - time1);
    }

    static String getStr(char[] chs) {
        Random random = new Random();
        char[] str = new char[5];
        int numCode = random.nextInt(5);
        str[numCode] = (char)('0' + random.nextInt(10));
        for (int i = 0; i < 5; i++) {
            if (numCode == i)
                continue;
            str[i] = (char)('A' + random.nextInt(26));
        }
        StringBuffer sb = new StringBuffer();
        String s = new String(str);
        return s;
    }
}
```

即将学习`html`，`JavaScript`，`CSS`的我
最后希望的未来是

1. 有房
2. 有车
3. 有一个幸福美满的家

![嘻嘻](xixi.jpg)