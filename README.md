import java.io.*;  
class square
{
int num;
square(int n)
{
num=n;
}
int sqr()
{
return (num*num);
}
}
class squares
{
public static void main(String[] args) throws IOException
{
BufferedReader br=new BufferedReader(new InputStreamReader(System.in)); 
int n;
System.out.println("enter the value:");
n=Integer.parseInt(br.readLine());
square s1=new square(n);
int s=s1.sqr();
System.out.println("the result is:"+s);
System.out.println("the square value of"+n+"is:"+s);
}
}
