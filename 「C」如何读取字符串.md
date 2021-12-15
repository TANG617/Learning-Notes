# 字符串操作
### scanf()
注意是否存在取址符
```c
char str,string[100];
scanf("%c",&str);
scanf("%s",string);
```

1. 不能包含空格，否则只能读取空格前的第一个字符串
2. 存在返回值，可以读取完整的一个文件/为止个数的字符串 
### get()
```c
char str[100];
gets(str);
```
大多IDE与OJ提示不安全，会被禁用
遇到'\n'结束，可以读取空格
### getchar()
```c
char a;
a=getchar();
```
1. 一次只能读入一个character --> for循环读入
2. 可以读入空格、回车
3. 存在返回值，可以读入不确定个数的字符串
```c
 while((str[i]=getchar())!=EOF);
```
