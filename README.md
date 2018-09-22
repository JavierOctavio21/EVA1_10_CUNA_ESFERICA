import java.util.*;
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author Javier Octavio
 */
public class Principal {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner input = new Scanner(System.in);
        
        System.out.println("Introdusca el valor del Radio");
        double rRadio;
        rRadio = input.nextDouble();
        
        System.out.println("Introdusca el angulo de la Cuña");
        double rCuña;
        rCuña = input.nextDouble();
        
        double rVolumen;
        rVolumen = (double) 4 / 3 * (3.1416*Math.pow(rRadio, 3) / 360) * rCuña;
        System.out.print("El volumen de la Cuña Esferica es: ");
        System.out.println(rVolumen);
    }
    
}
