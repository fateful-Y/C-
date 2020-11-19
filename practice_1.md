## 练习1

### 题目：字符转 ASCII 码

### 描述：输入一个字符，转换为ASCII码

### 思路：直接输出字符的%d格式输出其ASCII码

### 示例：

```c
#include "stdio.h"

int main()
{
	char c;
	printf("请输入一个字符:");
	scanf("%c",&c);
	printf("您输入的字符为:%c,它的ASCII码为：%d",c,c);
	return 0;
}
```

