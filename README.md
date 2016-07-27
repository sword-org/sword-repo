
sword-org项目的maven库
===================
使用方法
====
1 在项目的pom文件中添加如下内容
```xml
	<repositories>
		<repository>
			<id>sword-maven-repository</id>
			<name>sword-maven-repository</name>
			<url>https://raw.github.com/sword-org/sword-repo/master/</url>
		</repository>
	</repositories>
```

2 添加sword的依赖项，以sword-ocean为例
```xml
		<dependency>
			<groupId>com.sword.ocean</groupId>
			<artifactId>sword-ocean</artifactId>
			<version>1.0.1</version>
		</dependency>
```


