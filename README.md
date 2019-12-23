# sum-and-average
class SumAvg
{
public static void main(String args[])
{
int a[]={1,2,3};
int sum=0,avg=0,i;
int n=a.length;
for(i=0;i<a.length;i++)
{sum=sum+a[i];
}
System.out.println(sum);
avg=sum/n;
System.out.println(avg);
}
}
