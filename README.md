# Numero-mayor
package numeromayor;

import java.util.*;

public class NumeroMayor {

   
    public static void main(String[] args) {
        Scanner lec=new Scanner(System.in);
        int A,B,C;
        
        System.out.println("Intruduzca tres numeros");
        System.out.println("");
        System.out.println("Introduzca el primer numero");
        A=lec.nextInt();
        System.out.println("Introduzca el segundo numero");
        B=lec.nextInt();
        System.out.println("Introduzca el tercer numero");
        C=lec.nextInt();
     
        if(A>B&&A>C){
            System.out.println(A+" es el numero mayor");   
        }
        if(B>A&&B>C){
            System.out.println(B+" es el numero mayor");
        }
        if(C>A&&C>B){
            System.out.println(C+" es el numero mayor");
        }
    }
    
}
