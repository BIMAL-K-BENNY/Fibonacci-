# Fibonacci-
// Online C compiler to run C program online #include &lt;stdio.h>  void fibo(int);  void main() { int n;  printf("enter your number "); scanf("%d",&amp;n);  printf(" Fibonacci series is\n"); fibo(n); }  void fibo(int n) {     int a=0,b=1,c,i;     for(i=0;i&lt;n;i++)     {         if (i&lt;=1)         c=i;         else         {             c=a+b;             a=b;             b=c;         }         printf("%d",c);      }  }
