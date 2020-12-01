package Logica;

import Nodocola.Nodocola;
import java.util.ArrayList;
import java.util.List;

public class ColaDinamica {
    List <String>lista= new ArrayList();
  private   Nodocola cimaI,cimaf;
 int tamaño, num;
 String frase;
   

 public ColaDinamica(){
 cimaI=null;
 cimaf=null;
 tamaño=0;

 }
    public boolean estaVacia(){
        if(cimaI==null){
        return true;
        }else{
      return false;
     }
    }
    
    public void Empujar(List lista){ 
       
            for(int i=0;i<lista.size();i++){
                frase=(String) lista.get(i);
                 num=(int)(Math.random()*(1-10)+1);
            }

           Nodocola nodo = new  Nodocola (frase,num);
            nodo.elemento=frase;
            nodo.siguiente=null;
              if(estaVacia()){
             cimaI=nodo;
              cimaf=nodo;
              }else{
    cimaf.siguiente=nodo;
    cimaf=nodo;

  }
}
 
    public String SacrPila(){
        if(estaVacia()){
            System.out.println("LLA NO PUEDES ELIMINAR POR QUE LA PILA ESTA VACIA");
        }
         String aux=cimaI.elemento;
         if(cimaI==cimaf){
         cimaI=null;
         cimaf=null;
         }else{
    cimaI=cimaI.siguiente;
    tamaño--;
        }
        return aux;
    }
    
    
    public void mostrarPila(){
        if(estaVacia()){
            System.out.println("LA PILA ESTA VACIA INGRESE DATOS");
              }else{
    Nodocola recorre = cimaI;
    while(recorre!=null){
        
        System.out.println(recorre.elemento);
        recorre=recorre.siguiente;
        }
       }
    }
}
