package Principal;

import Logica.ColaDinamica;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;


public class Principal {
     public static void main(String args[]){
        Scanner leer = new Scanner(System.in);
        List <String>lista= new ArrayList();
        ColaDinamica Pila= new ColaDinamica();
        
       boolean continuar = true;
               String respuesta;
       int  menu=0,num=0;
    
        while(continuar){
    
        System.out.println("BIENVENIDOS A  LA CONLA DINAMICA \n"
                   + "1: INSERTAR PALABRA A LA COLA\n"
                   + "2: MOSTRAR COLA DINAMICA \n"
                   + "3: ELIMINAR UN ELEMENTO \n"
                   + "4: SALIR");
        menu=leer.nextInt();
        
          switch(menu){
              case 1:
                  
                    System.out.println("Ingese la frase ");
               lista.add( respuesta=leer.next());
                
                
                Pila.Empujar(lista);
                
                break;
            case 2:
                 
               Pila.mostrarPila();
               break;
            case 3:
                Pila.SacrPila();
                break;
            case 4:
                System.out.println(" ELEGISTE SALIR...");
                continuar=false;
                break;
                 default:
                 System.out.println("opcion incorrecta");
                 break;
           
          }
     }
  }
}
