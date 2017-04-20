/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package so.le;

import java.util.Scanner;

/**
 *
 * @author long
 */
public class SoLe {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
       int i;
       System.out.println("N= ");
       Scanner Sc = new Scanner(System.in);
       int N=Sc.nextInt();
       for(i=1; i<N; i+=2)
           System.out.print(i+" ");
       
    }
    
}
