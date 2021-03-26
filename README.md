# ejercicioAuto
ejercicio_2

public class Auto {
    
    public static void main(String arg[]){
    
       
    
        estadoAuto Funcion = new estadoAuto();
        Funcion.velocidad();
    }
    
}

public class estadoAuto {
    
   String Marca;
   Integer Modelo;
   Integer Kilometraje = 0;
    
    
     
    
    public void velocidad(){
        if(Kilometraje == 0){
        
            System.out.println("Esta Nuevo");
        
        }else if(Kilometraje < 10000){
        
            System.out.println("Poco usado");
        
        }else if(Kilometraje < 100000){
        
            System.out.println("Usado");
        
    
        }else if(Kilometraje > 10000){
        
            System.out.println("Bastante usado");
        
        }
    }
}
