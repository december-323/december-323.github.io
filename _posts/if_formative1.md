---
layout: single
title: "조건문"
toc: true
toc_sticky: true
toc_label: "페이지 주요 목차"
---

### 01. 사주보기
![C_language_96](/assets/images/C_language_96.jpg)
~~~c
#include <stdio.h>
int main(void)
{ int year, month, day, result;
printf("당신의 사주를 봐드립니다.\n");
printf("연도 월 일을 차례대로 입력하세요 : ");
scanf("%d, %d, %d, &year, &month, &day");

result=(year-month+day)%10;
if(result==0)
printf("당신의 사주는 대박입니다.\n");
else 
printf("당신의 사주는 그럭저럭입니다.\n");
return 0;
}
~~~

### 02. 3개의 터널 통과
![C_language_98](/assets/images/C_language_98.jpg)
~~~c
#include <stdio.h>
int main(void)
{ int tunnul_1, tunnul_2, tunnul_3;
printf("세 터널의 높이를 차례대로 입력하세요 : ");
scanf("%d,%d,%d",&tunnul_1,&tunnul_2,&tunnul_3);
if(tunnul_1<=170)
printf("충돌 %d", tunnul_1);
else if(tunnul_2<=170)
printf("충돌 %d", tunnul_2);
else if(tunnul_3<=170)
printf("충돌 %d", tunnul_3);
else
printf("무사 통과");
return 0;
~~~
