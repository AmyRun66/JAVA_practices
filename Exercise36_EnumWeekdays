import java.util.Scanner;

public class Main{
    
    public static void main(String[] args){
        
        //Crea un enum con los días de la semana, pide un día de la semana e indica si es laboral o no.
        
        System.out.println("Introduce un día de la semana: ");
        
        Scanner teclado = new Scanner(System.in);
        
        String usertext = teclado.nextLine();
        
        DiasSemana dia = DiasSemana.valueOf(usertext.toUpperCase());
        
        switch(dia){
            
            case LUNES:
            case MARTES:
            case MIÉRCOLES:
            case JUEVES:
            case VIERNES:
                
                System.out.println("El día " + dia.name().toLowerCase() + " es laboral.");;
                break;
                
            case SÁBADO:
            case DOMINGO:
                
                System.out.println("El día " + dia.name().toLowerCase() + " es festivo.");;
                break;
        }
        
    }
    
}
