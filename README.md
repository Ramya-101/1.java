# 1.java
Class program1
{
public static double calculator ()
{
While (a!=0 && b!=0)
{
double sum,sub,mul,div;
System.out.println("enter operator");
String opr=scn.nextString();
Switch()
{
case 1:opr="add";
System.out.println(a+b);
break;
case 2:opr="sub";
System.out.println(a-b);
break;
case 3:opr="mul";
System.out.println(a*b);
break;
case 4:opr="div";
System.out.println(a/b);
break;
default:
System.out.println("invalid")
break;
}
}
}
public static void main (String[]arts)
{
double a;
double b;
Scanner scn=new Scanner (System.in);
a=scn.nextDouble();
b=scn.nextDouble();
Calculator ();
}
}
