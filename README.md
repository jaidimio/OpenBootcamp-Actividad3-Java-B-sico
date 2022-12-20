# OpenBootcamp-Actividad3-Java-B-sico

//Actividad 3: crear un bucle que permita concatenar textos e imprima el resultado final por consola.//

package com.ListaLibros;

public class Libros {
    public static void main(String[] args) {

        String [] frase = {"Estos son", "los libros preferidos", "que yo tengo en mi biblioteca", "Lo que el Viento se Llevó", "Crimen y Castigo", "Guerra y Paz",
                    "Cien Años de Soledad", "Donde Duerme el Agua"};

        StringBuilder frases = new StringBuilder();

        for(String texto : frase) frases.append(" " + texto + " ");
        System.out.println(frases);
    }
}



