# Java_session_Assignment1.2
/*
Write a program to print the result of the following expressions provided the integer variable a is
20 and b is 10.
int b= a-- - --a;
int c=a--;
int d=a>>2;
int e=a&b
*/

import java.util.*;
class expr
{
  public static void main(String args[])
  {
    int a=20;
    int b=10;
    b=((a--) - (--a));
    System.out.println(b);
    int c=a--;
    System.out.println(c);
    int d=a>>2;
    System.out.println(d);
    int e=a&b;
    System.out.println(e);
  }
}
