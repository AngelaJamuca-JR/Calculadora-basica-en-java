# Calculadora-basica-en-java
Calculadora básica escrita en lenguaje Java, con operaciones basicas.

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package calculadorabasica;

import javax.swing.JOptionPane;


/**
 *
 * @author Tatiana Jamauca
 * 
 */
public class CalculadoraBasica 
{

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) 
    {
        
     calculadora ventana = new calculadora();
     
     ventana.leerOpcion();
     ventana.menu();
     ventana.operaciones();
     
     
     
     
     
     
     
     
    
        
        
    }
    
    
    
}
