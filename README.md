# -1---30.09
1 вариант
public class Control3 { 
    //I вариант, определить значен6ие у при данном значе6ние х 
    public static void main(String[] args) { 
        Scanner f = new Scanner(System.in); 
        System.out.print("Введите значе6ние х: "); 
        double x = f.nextDouble(); 
 
        if (x == 0) { 
            System.out.println("f(" + x + ") = "); 
        } else if (0 <= x & x <= 2) { 
            System.out.println("f(" + x + ") = " + Math.sin(x)); 
        } else if (x > 2) ; 
        { 
            System.out.println("f(" + x + ") = " + (x + 1 / x)); 
        } 
    } 
 
} 
 
