/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package baitap;

import java.util.Scanner;

/**
 *
 * @author DELL
 */
public class BaiTapc4 {
    public static void giaithua1(int n) {
        int giaithua = 1;
        int i = 1;                    
        System.out.print("Nhap so nguyen n: ");
        Scanner nhap = new Scanner(System.in);
        n = nhap.nextInt();
        while (i <= n) {            
            giaithua *= i;
            i++;
        }  
        System.out.println("Tinh giai thua: "+ "n"+ "*"+ "!"+ "= "+ giaithua);
                /* Tính giai thừa dạng while */
    }
    public static void giaithua2(int n) {
        int giaithua = 1;
        int i = 1; 
        System.out.print("Nhap so nguyen n: ");
        Scanner nhap = new Scanner(System.in);
        n = nhap.nextInt();
        do{
            giaithua *= i;
            i++;
        } while(i<= n);
        System.out.println("Tinh giai thua: "+ "n"+ "*"+ "!"+ "= "+ giaithua);
                /* Tính giai thừa dạng do_while */
    }
    public static void main(String[] args) {
        int nhap,n;
        int giaithua =1;
        int i = 1;     
        System.out.println("1. Tinh giai thua dang While ");
        System.out.println("2. Tinh giai thua dang do_while ");
        System.out.println("====*==========*==========*====");
        do {                
                System.out.print("Nhap phuong an: ");
                Scanner pa = new Scanner(System.in);
                nhap = pa.nextInt();
                
        switch (nhap) {
            case 1:
                giaithua1(giaithua);
                break;
            case 2:
                giaithua2(giaithua);
                break;
            default:
                throw new AssertionError();
        }  
            } while (true);
        
    }
}
