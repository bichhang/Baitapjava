/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package sln;

import java.util.Scanner;

/**
 *
 * @author long
 */
public class SLN {

    /** @param args the command line arguments
     */
    public static void main(String[] args) {
        System.out.println("nhap a:");
        Scanner slna = new Scanner(System.in);
        int a=slna.nextInt();
        System.out.println("nhap b:");
        Scanner slnb = new Scanner(System.in);
        int b=slnb.nextInt();
        System.out.println("nhap c:");
        Scanner slnc = new Scanner(System.in);
        int c=slnc.nextInt();
        if(a>b)
        {
            if(a>c)
                System.out.println("SLN:"+a);
            else
                System.out.println("SLN:"+c);
        }
        else
        {
            if(b>c)
                System.out.println("SLN:"+b);
            else
                System.out.println("SLN:"+c);
        }
        
        
        
    }
    
}
