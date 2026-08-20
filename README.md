# my-coding-notes
A collection of daily learning notes,practice projects,and git exercises.
## day 1- What I Learned Today (14-august-2026).
* Created my frist github repository("my-coding-notes").
* learned how to edit a "README.md" file using markdown.
* learned how to navigate github pages!

 ## day 2- basic program in c (16-august-2026)
  #include <stdio.h>
      int main (){
              printf("hello world");
   return 0;
}
### how to move in next line?
* example-
        printf("hello parul");
        printf("hello laddu");
* output will be:
             hello parulhello laddu
  ### use of escape sequence '\n'
  * example-
            printf("hello parul");
            printf("\n");
            printf("hello laddu");
  * output will be:
               hello parul
               hello laddu

## (20-august-2026) variables and their declaration
* let us focus on int data types as of now
* variables as containers :
   #include <stdio>
     int main()
     {
        printf("hello");
         int x;
         x=3;
         x=5;
        printf("%d",x);
       }

### printing variables in c & updation of variabels 
 int x=5;
printf("%d",x);
 x=7;
printf("%d",x);
x=x + 6;
printf("%d",x);
x=x - 20; 
printf("%d",x); 

   output will be:      
           5, 7, 13, -7
### airthmetic operations on int data types 
int x=5;
int y=2;
printf("%d",x+y);
printf("%d",x-y);
printf("%d",x*y);
printf("%d",x/y); 
   output will be:
     7, 3, 10 ,2
     
