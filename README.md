牛客网联系地址：https://ac.nowcoder.com/acm/contest/320#question

主要为Java中Scanner类的应用

*Next,nextline,nextint*

Scanner 主要内涵scanner中的 hasnextline 为boolean类型，判断是否存在下一行.

比如前面用hasNextLine，那么后面要用 nextLine 来处理输入。

nextline 来读取整行数据（包括空格）,返回string。

next（）会自动消去有效字符前的空格，只返回输入的字符，不能得到带空格的字符串。

使用nextInt()方法时，与next()方法类似，只是它的返回值是int类型的，依旧将空格看作是两个输入的数据的间隔

当使用nexInt()方法时，只能输入int类型的数据，否则会跑出异常，必须全部整形。

Array中的sort方法，可按数字大小和字母表顺序，自行进行排序。

当字符串数组不能直接一次性输出时，可以借助for (String text : array) {System.out.print(" "+text+" ");}输出
