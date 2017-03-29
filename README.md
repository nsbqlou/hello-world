# hello-world
based on the guide
#include <stdio.h>
int main()
{
char c;
c=getchar();
if(c>='a'&&c<='z')
c=c-32;
else if(c>='A'&&c<='Z')
c=c+32;
putchar(c);
return 0;
}
