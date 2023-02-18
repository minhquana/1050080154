/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */
package baitap;
import java.util.Scanner;
import java.util.Arrays;

/**
 *
 * @author DELL
 */
public class BaiTapc5 {
    public static void main(String[] args) {  
        int a,x,vt,i;                    
        Scanner nhap = new Scanner(System.in);
        do {
        System.out.print("Nhap so phan tu mang: ");
         a = nhap.nextInt();
        } while (a <= 0);    
        
       int mang[] = new int[a];    
       
        for( i =0 ;i< a;i++){
            System.out.print("Nhap phan tu "+ i+ ": ");
            mang[i]= nhap.nextInt();
        }
        
        System.out.println("Xuat mang: "+ Arrays.toString(mang));
        
        Arrays.sort(mang);
        System.out.println("Sap xep tang dan: "+ Arrays.toString(mang));
        
        
        
        System.out.print("Nhap so nguyen x: ");
        x = nhap.nextInt();
         
    
    for (vt = i = 0; i < a; i++) {
        if (mang[i] != x) {
            mang[vt] = mang[i];
            vt++;
        }
    }
         
    a = vt; 
    System.out.println("Mang con lai sau khi xoa phan tu " + x + ": ");
    for (i = 0; i < a; i++) {
        System.out.println(mang[i] + "\t");
    }
  }
}       
