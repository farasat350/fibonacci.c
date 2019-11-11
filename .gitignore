#include<stdio.h>
int main()
{
	int n;
    int i;
    int t1=0;
    int t2=1;
    int next_term=0;
    printf("enter number to print faibanocci series");
    scanf("%d",&n);
    for(i=1;i<=n;++i)
    {
    	if(i==1)
    	{
    		printf("%d\t",t1);
    	  continue;
		}
		if(i==2)
		{
			printf("%d\t",t2);
			continue;
		}
	    next_term=t1+t2;
	    t1=t2;
	    t2=next_term;
	printf("%d\t",next_term);
}
	return 0;
}
