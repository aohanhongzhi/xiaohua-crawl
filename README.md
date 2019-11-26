# xiaohua-crawl

这个程序里里面有一段代码
```java
    LinkFilter filter = new LinkFilter() {
            public boolean accept(String url) {
                if (url.startsWith("http://www.baidu.com/"))
                    return true;
                else
                    return false;
            }
        };
```

LinkFilter是一个接口
```java
public interface LinkFilter {
    public boolean accept(String url);
}
```

接口不能实例化，上面算什么操作？匿名？
