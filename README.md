<div align="center">

## the programme


</div>

### Description

it displays the sum of digits of any no.
 
### More Info
 
only put a no.

there is nothing special about my code??

any c language beginner can also do the same thing..

it returns the sum of digits.

no side effects??


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[ASHISH GOTHANIA](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ashish-gothania.md)
**Level**          |Beginner
**User Rating**    |5.0 (20 globes from 4 users)
**Compatibility**  |C
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ashish-gothania-the-programme__3-11680/archive/master.zip)





### Source Code

```
#include<stdio.h>
#include<conio.h>
#include<math.h>
void main()
{
clrscr();
long int n,c,a,e;
int sum=0,d,i;
printf("enter any no.and no.of digits");
scanf("%ld",&n);
scanf("%d",&d);
for(i=0;i<d;i++)
{
sum=sum+(n/10^i)%10;
}
printf("the sum of digits is %d",sum);
getch();
}
```

