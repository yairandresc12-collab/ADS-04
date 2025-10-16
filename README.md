package com.mycompanysena.mavenproject1;
import java.util.Scanner;
public class Mavenproject1 {
static Scanner dato = new Scanner(System.in);
     
    public static void main(String[] args) {
        String sexo;
        int edad,general=0,urgencia=0,control=0;
        int citas,cont=0;
        System.out.println("ingrese numero de citas");
        citas=dato.nextInt();
        System.out.println("ingrese su edad");
        edad=dato.nextInt();
        System.out.println("ingrese su sexo");
        sexo=dato.nextLine();
         dato.nextLine();
        System.out.println("cuantas citas general fue la Â´persona");
        general=dato.nextInt();
        System.out.println("cuantas citas de urgencia fue la persona");
        urgencia=dato.nextInt();
        System.out.println("cuantas citas de control fue la persona");
        control=dato.nextInt();
        while (citas!=-1){
            cont++;
        System.out.println("ingrese numero de citas");
        citas=dato.nextInt();
        System.out.println("ingrese su edad");
        edad=dato.nextInt();
        
        System.out.println("ingrese su sexo");
        sexo=dato.nextLine();
        dato.nextLine();
        System.out.println("cuantas citas general fue la Â´persona");
        general=dato.nextInt();
        
        System.out.println("cuantas citas de urgencia fue la persona");
        urgencia=dato.nextInt();
        System.out.println("cuantas citas de control fue la persona");
        control=dato.nextInt();
        cont++;  
        
        }
        
        System.out.println("total de citas general son  "+general);
                System.out.println("total de citas de urgencia son  "+urgencia);
                        System.out.println("total de citas de control son  "+control);

    }                   
}   
      
