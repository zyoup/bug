# pom使用过程中的一些错误解决办法
>1.maven plugin的execution出错
![pom Bug1](https://github.com/zyoup/image/blob/master/pom.png)


```
在pom.xml中在报错的plugin的外面再包上一层<pluginManagement></pluginManagement>  如下：
1.	<build>
2.	    <pluginManagement>
3.	        <plugins>
4.	            <plugin> ... </plugin>
5.	            <plugin> ... </plugin>
6.	                  ....
7.	        </plugins>
8.	    </pluginManagement>
9.	</build>

```
