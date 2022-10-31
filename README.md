# Markdown
INDICE
1.- Listas ordenadas
2.- Listas desordenadas
3.- Código
4.- Enlaces
5.- Imagenes
6.- Tablas
7.- Listas con check
# **indice**

##__Listas ordenadas__
1 alimentos solidos
2 alimentos liquidos

##__ Listas desordenadas__
*alimentos solidos 
    *almendras
    *pollo
    *salmon
    *pistachos
*alimentos liquidos
    *aceite
    *agua
    *cerveza

## __Código__
import java.util.Scanner;

public class Inicio {
    public static void ejercicio1() {

			int num;
			int res = 0;
			
					
			Scanner entrada=new Scanner(System.in);
			System.out.print("dame un numero entero: ");
			num = entrada.nextInt();
			res = num+3;
			
			System.out.println("El numero " + num +  " + 3 es: " + res );	

	}
}
 
##__Enlaces__

  [pagina de google] (www,google.es)
  [la arboleda] (www.laarboleda.es)
  [bbva] (www.bbva.es)
  [listas ordenadas] (#indice)


##__imagenes__
|[imagen de un pollo](http://c.files.bbci.co.uk/12C50/production/_103908867_pollo.jpg)
|[imagen de un salmon](https://www.gastronomiavasca.net/uploads/image/file/3268/salmon.jpg)
|[imagen de botella aceite](data:image/jpeg;base64,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)
|[foto de otro repositorio](/../main/assets/images/electrocat.png)


##__Tablas__

  
