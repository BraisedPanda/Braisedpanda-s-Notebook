# Java8的新用法
## 1.Java8-Optional.ofNullable使用
&nbsp; Optional类是Java8为了解决null值判断问题，使用Optional类可以避免显式的null值判断（null的防御性检查），避免null导致的NPE（NullPointerException）。
```
// 如果不为null，输出A，否则输出B

int result = Optional.ofNullable(A).orElse(B);
```