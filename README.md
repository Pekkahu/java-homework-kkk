# Make a program that takes the radius of a circle as input, 
#calculates its radius and area and prints it as output to the user.

```java
import java.util.*;

class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.print("what is the radius of circle?");
    Double radius = sc.nextDouble();
    Double b = 3.14;
    Double c = b*(radius*radius);
    System.out.print("area of the circle is: ");
    System.out.print(c);
  }
}
```

# Make a program that prints the table of a number that is input by the user.

```java
import java.util.*;
class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    int g = sc.nextInt();
    System.out.println("your table is:");
    System.out.println(g*1);
    System.out.println(g*2);
    System.out.println(g*3);
    System.out.println(g*4);
    System.out.println(g*5);
    System.out.println(g*6);
    System.out.println(g*7);
    System.out.println(g*8);
    System.out.println(g*9);
    System.out.println(g*10);
  }
}
```

# check if adult or not adult

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int age = f.nextInt();
        if (age > 18) {
            System.out.println("your an adult");
        }
        else {
            System.out.print("your not an adult");
        }
    }
}
```

# check if the given number by user is odd or even

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int number = f.nextInt();
        if  (number % 2 == 0){
            System.out.println("even");
        }
        else {
            System.out.print("odd");
        }
    }
}
```

# check if the given number is equal or not 

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int a = f.nextInt();
        int b = f.nextInt();
        String c = String.format("no %o is greater then %o", a, b);
        String d = String.format("no %o is smaller then %o", a, b);
        if (a == b) {
            System.out.println("yes they are equal");
        } if (a > b) {
            System.out.print(c);
        } else {
            System.out.println(d);
        }
    }
}
```

# calcultaor

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        System.out.println("give two numbers");
        float a = f.nextFloat();
        float b = f.nextFloat();
        System.out.println("select the operation you want");
        System.out.println("A for addition");
        System.out.println("B for subtraction");
        System.out.println("C for muiltplication");
        System.out.println("D for division");
        System.out.println("E for remainder");
        String c = f.next();
        switch (c) {
            case "A" :
                System.out.println(a + b);
                break;
            case "B" :
                System.out.println(a - b);
                break;
            case "C" :
                System.out.println(a * b);
                break;
            case "D" : if(b == 0) {
                       System.out.println("Invalid Division");
                   } else {
                       System.out.println(a/b);
                   }
	    break;
           case "E" : if(b == 0) {
                       System.out.println("Invalid Division");
                   } else {
                       System.out.println(a%b);
                   }
	   break;
        }
    }
```

> (if denomentor get zero the result will be undefined for calculator)


# Ask the user to enter the number of the month & print the name of the month. 
> For eg - For ???1??? print ???January???, ???2??? print ???February??? & so on.

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int num = f.nextInt();
        switch (num) {
            case 1 :
                System.out.println("january");
                break;
            case 2 :
                System.out.println("february");
                break;
            case 3 :
                System.out.println("march");
                break;
            case 4 :
                System.out.println("aprill");
                break;
            case 5 :
                System.out.println("may");
                break;
            case 6 :
                System.out.println("june");
                break;
            case 7 :
                System.out.println("jully");
                break;
            case 8 :
                System.out.println("augest");
                break;
            case 9 :
                System.out.println("septamber");
                break;
            case 10 :
                System.out.println("october");
                break;
            case 11 :
                System.out.println("november");
                break;
            case 12 :
                System.out.println("december");
                break;
        }
    }
}
```

# for loop genrating 0 to 10 number

```java
public class Main {
    public static void main(String[] args) {
        for (int c = 0; c < 11; c = c + 1){
            System.out.println(c);
        }
    }
}
```

# print sum of n natural number

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int n = f.nextInt();
        int a = 0;
        for (int i = 1; i <= n ;i ++) {
            a = a + i;
            System.out.println(a);
        }
        System.out.println(a);
    }
}
```


# Make a program that prints the table of a number that is input by the user.

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int n = f.nextInt();
        for (int i = 1; i<11; i++) {
        System.out.println(n * i);
        }
    }
}
```

# Print all even numbers till n.

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int n = 2;
        int g = f.nextInt();
        for (int i = 1; i <=g; i++) {
            System.out.print(n*i);
        }
    }
}
```

# infinite loop example when there is no initialized object or condition or update

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        for(; ;) {
            System.out.println("bitch");
        }
    }
}
```
# Make a menu driven program. The user can enter 2 numbers, either 1 or 0. <br>If the user enters 1 then keep taking input from the user for a student???s marks(out of 100). <br>If they enter 0 then stop. <br>If he/ she scores : <br>Marks >=90 -> print ???This is Good??? <br>89 >= Marks >= 60 -> print ???This is also Good??? <br>59 >= Marks >= 0 -> print ???This is Good as well???

>(Hint : use do-while loop but think & understand why)

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        for( ; ; ) {
            int n = f.nextInt();
            if (n == 1) {
                int g = f.nextInt();
                if (g>=90) {
                    System.out.println("This is Good");
                } else if (g >= 60) {
                    if (g <= 89){
                        System.out.println("This is also Good");
                    }
                } else {
                    System.out.println("This is Good as well");
                }
            } else if (n == 0) {
                System.out.println("bye");
                break;
            } else {
                System.out.println("please enter valid number");
            }
        }
    }
}
```
# Print if a number is prime or not (Input n from the user). #
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int h = f.nextInt();
        int j = h % 2;
        if (j == 0) {
            System.out.println("yes it is a prime number");
        }else {
            System.out.println("no it is not a prime number");
        }
    }
}
```

# printing pattern #
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner q = new Scanner(System.in);
        int raws = q.nextInt();
        int columns = q.nextInt();
        for (int y = 1; y <= raws; y++) {
	// these decide number of raws 
            if ( y == 1) {
                for (int j = 1 ; j <= columns; j++) {
	// these decide number of column
                    System.out.print("*");
                };
                System.out.println();
	// first raw 
            } else if (y < raws) {
	// raws other then 1 
                for (int z = 1 ; z <= columns; z++) {
	// these decide number of column
                    if ( z == 1) {
	// first colomn
                        System.out.print("*");
                    } else if (z < columns) {
	// all other element are conisdered only first colomn and last colomn are excluded
                        System.out.print(" ");
                    } else {
	// last colomn
                        System.out.print("*");
                    }
                };
                System.out.println();
            }else {
	// last raw
                for (int a = 1 ; a <= columns; a++) {
                    System.out.print("*");
                }
                System.out.println();
            }
        }
    }
}
```

# output

```
"C:\Users\Admin\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.4.101-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\lib\idea_rt.jar=59023:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Admin\IdeaProjects\untitled\out\production\untitled Main
6
12
************
*          *
*          *
*          *
*          *
************

Process finished with exit code 0

```
# printing patern

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner q = new Scanner(System.in);
        int raws = q.nextInt();
        int columns = q.nextInt();
        for ( int i = 1 ; i <= raws ; i++ ) {
            for (int j = 1 ; j < ( i + 1 ) ; j++ ) {
                System.out.print("*");
            };
            System.out.println();
        }
    }
}
```

# output 

```
"C:\Users\Admin\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.4.101-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\lib\idea_rt.jar=62796:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Admin\IdeaProjects\untitled\out\production\untitled Main
4
5
*
**
***
****

Process finished with exit code 0
```

# pattern problem

```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner f = new Scanner(System.in);
        int raws = f.nextInt();
        int columns = f.nextInt();
        for (int i = 0 ; i < raws ; i++ ) {
            for ( int j = 1 ; j <= columns ; j++) {
                if ( j == columns || j == (columns - i ) ) {
                    System.out.print("*");
                } else if ( j < columns && j > (columns - i)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            };
        System.out.println();
        }
    }
}
```
# output

```
"C:\Users\Admin\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.4.101-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\lib\idea_rt.jar=58367:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Admin\IdeaProjects\untitled\out\production\untitled Main
4
5
    *
   **
  ***
 ****

Process finished with exit code 0
```
# pattern
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner q = new Scanner(System.in);
        int k = q. nextInt();
        for ( int i = 1 ; i <= k ; i++) {
            for (int j = 1 ; j <= i; j++) {
                if ( i % 2 != 0 && j % 2 != 0 || i % 2 == 0 && j % 2 == 0) {
                    System.out.print(1);
                } else {
                    System.out.print(0);
                };
            }
        System.out.println();
        }
    }
}
```
# output 
```
"C:\Users\Admin\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.4.101-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\lib\idea_rt.jar=62974:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Admin\IdeaProjects\untitled\out\production\untitled Main
5
1
01
101
0101
10101

Process finished with exit code 0
```
# Print a solid rhombus
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner q = new Scanner(System.in);
        int k = q. nextInt();
        for ( int i = 0 ; i < k ; i++) {
            for ( int j =1 ; j < 2*k; j++) {
                if ( j >= ((2*k)- 5 -i) && j<= ((2*k) - 1 -i)) {
                    System.out.print("*");
                } else {
                    System.out.print(" ");
                }
            };
        System.out.println();
        }
    }
}
```
# output
```
"C:\Users\Admin\AppData\Local\Programs\Eclipse Adoptium\jdk-17.0.4.101-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\lib\idea_rt.jar=63371:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Admin\IdeaProjects\untitled\out\production\untitled Main
5
    *****
   ***** 
  *****  
 *****   
*****    

Process finished with exit code 0
```
### roots of polynomail 2 degree 
```java
import java.util.*;

class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        double a = sc.nextDouble();
        double b = sc.nextDouble();
        double c = sc.nextDouble();
        double radical_value = ((b*b)-4*a*c);
        if (radical_value >= 0) {
            double squareing_radical_value = Math.pow(radical_value, 0.5);
            double root_1 = (((-b) + (squareing_radical_value))/(2*a));
            double root_2 = (((-b) - (squareing_radical_value))/(2*a));
            if (b < 0) {
                if (c < 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? "+b+"x "+c+"  are "+root_1+" and "+root_2);
                } else if (c > 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? "+b+"x +"+c+"  are "+root_1+" and "+root_2);
                }
            } else if (b > 0) {
                if (c < 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? +"+b+"x "+c+"  are "+root_1+" and "+root_2);
                }
            }
            if (b > 0) {
                if (c > 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? + "+b+"x + "+c+"  are "+root_1+" and "+root_2);
                }
            }
        } else if (radical_value < 0){
            double b1= b*-1;
            String g = b1+" + ???"+ radical_value ;
            String h = b1+" - ???"+ radical_value ;
            if (b < 0) {
                if (c < 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? "+b+"x "+c+"  are ("+g+")/(2*"+a +") and ("+h+")/(2*"+a+")");

                } else if (c > 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? "+b+"x +"+c+"  are ("+g+")/(2*"+a+") and ("+h+")/(2*"+a+")");
                }
            } else if (b > 0) {
                if (c < 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? +"+b+"x "+c+"  are ("+g+")/(2*"+a+") and ("+h+")/(2*"+a+")");
                }
            } if (b > 0) {
                if (c > 0) {
                    System.out.println("The roots of the polynomail "+a+"x?? + "+b+"x + "+c+"  are ("+g+")/(2*"+a+") and ("+h+")/(2*"+a+")");
                }
            }
        }
    }
}
```
### usefull way to abuse for loops for any pattern just use these code rather then if else statement.
> increaseing triangle
```java
public class Main{
   public static void main (String args[]){
      int n = 5;
      for (int i = 1; i<=n ; i++) 
      {
         for (int j = 1; j<=i; j++) {
            System.out.print("* ");
         }
         System.out.println();
      }
   }
}
```
> decreasing triangle 
```java
public class main {
   public static void main (String args[]) {
      int n = 5;
      for (int i = 1; i<=n ; i++) {
         for (int j = i; j<=n; j++) {
            System.out.print(???* ???);
         }
         System.out.println();
     }
  }
}
```
> increasing triangle spaces 
```java
public class Main {
     public static void main(String args[]) {
          int n = 8;
	  for (int i = 1; i<=n ; i++) {
             for (int j = i; j<=n; j++) {
             System.out.print(" ");
          }
          System.out.print("* ");
          System.out.println();
       }
    }
 }
```
> decreasing triangle spaces
```java
public class main {
     public static void main(String args[]) {
          int n= 5;
          for (int i = 1; i<=n ; i++) {
             for (int j = 1; j<=i; j++) {
               System.out.print(??? ???);
             }
             System.out.print(???* ???);
             System.out.println();
           }
        }
  }
```
>using it to form a pyraimid
```java
import java.util.Scanner;
public class Main {
    public static void main(String args[]) {
        Scanner scan = new Scanner(System.in);
       System.out.print("Enter Number of Rows : ");
       int n = scan.nextInt();

       for (int i = 1; i<=n ; i++) { 
          for (int j = i; j<=n; j++) {
             System.out.print(" ");
          }
          for (int j = 1; j< i; j++) { 
             System.out.print("* ");
          }
          for (int j = 1; j<=i; j++) {
             System.out.print("* ");
          }
          System.out.println();
       }

     }
 }
```
![Screenshot (79)](https://user-images.githubusercontent.com/96633728/200658854-d575e703-28a3-48a3-95bc-fb528a47e53a.png)
>these technic doesn't require if else statment and the battern can be formed 

### example code 
```java
import java.util.Scanner;
public class StarPattern4
{
  public static void main(String[] args)
    {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter the number of rows needed to print the pattern ");
        int rows = scanner.nextInt();
        System.out.println(" Printing the pattern ");
       
        for (int i=1; i<=rows; i++)
        {
            for (int j = 1; j <= i; j++)
            {
                System.out.print("*");
            }
            for (int k = i*2; k <= rows*2-1; k++)
            {
                System.out.print(" ");
            }
            for (int l = 1; l <= i; l++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
       
        for (int i=1; i<=rows-1; i++)         {             for (int j = rows-1; j >= i; j--)
            {
                System.out.print("*");
            }
            for (int k = 1; k <= i*2; k++)             {                 System.out.print(" ");             }             for (int l = rows-1; l >= i; l--)
            {
                System.out.print("*");
            }
           
            System.out.println();
        }
        scanner.close();
    }
}
```
### There are three type of variables in java. Local, Global(Instance) and static(both Local and Global)
### 1.Local variable 
> A variable that is declared inside the body of the method or constructor is called a local variable. It is called so because the extent of a local variable lies only within the method or constructor within which it is created and other methods in the class cannot access it. inside the method body, local variable is declared using the static keyword.

### Example: 
```java
public class Main {
    public static void main(String[] args) {
    	int number = 1; /** these is a local variable for main function only it can not be used out side these method. */
        System.out.print(number);
    }
}
```
### 2.Global(Instance) variable 
> An instance variable is declared inside the class but outside a method or a constructor. It is similar to a static variable except that it is declared without using the keyword static. These variables are accessible by all methods or constructors that are inside the class.

### Example:
```java
public class Main {
    int number = 1; /** these is a Global(Instance) variable it can be used by any method from these class but we have to creat a innstance of the object inside the method to use these variable. */ 
    public static void main(String[] args) {
    	Main b = new Main(); /** these is a Instance of the class */
        System.out.print(b.number);
    }
}
```
### 3. Static(both Local and Global) varaible
> An static variable is declared inside the class but outside a method or a constructor. It is similar to a instance variable except that it is declared using the keyword static. These variables are accessible by all methods or constructors that are inside the class.
### Example:
```java
public class Main {
    static int number = 1;
    public static void main(String[] args) {
        System.out.print(number);
    }
}
```
### In a program , input 3 numbers:A,B andC.You have to output the average of these 3 numbers.
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        int b = s.nextInt();
        int c = s.nextInt();
        System.out.print(((a + b + c)/3));
    }
}

```
### In a program , input the side of a square.You have to out put the area of the square.(Hint : area of a square is (side x side))
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int side = s.nextInt();
        System.out.print("area of square of side length "+side+" is equal to "+side*side);
    }
}
```
### Enter cost of 3 items from the user(using float datatype)- a pencil ,a pen and an eraser. You have to output the total cost of the items back to the user as their bill.(Add on : You can also try adding 18% gst tax to the items in the bill as an advanced problem)
```java
import java.util.*;
public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        float a = s.nextFloat();
        float b = s.nextFloat();
        float c = s.nextFloat();
        float gst = ((a + b + c) * (18f/100));
        System.out.print("total cost of the items you want to purchase is "+(gst+a+b+c));
    }
}
```
