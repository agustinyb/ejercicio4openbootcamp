# ejercicio4openbootcamp
ejercicio 4 de introduccion a la programacion 
                             
                             //EJERCICIO IF//

public class Main {

    public static void main(String[] args) {
        Integer numeroIf = 10 ;


        if (numeroIf < 0) {
            System.out.println("Es negativo");
            }
            if (numeroIf == 0) {
                System.out.println("Es 0");
            }
                if (numeroIf > 0) {
                    System.out.println("Es positivo");
                }
            }


    }


//EJERCICIO WHILE//

public class Main {


    public static void main(String[] args) {
        int numerowhile = 2;

        while (numerowhile > 0) {
            System.out.println(numerowhile);
            numerowhile = numerowhile + 1;
        }
    }

}
                  //EJERCICIO DOWHILE//

public class Main {
    public static void main(String[] args) {
        int numerowhile = 2;

        do {
            System.out.println(numerowhile);
            numerowhile = numerowhile - 1;
        } while (numerowhile > 1);
    }
}
public class Main {
            public static void main(String[] args) {
                for(int numerofor = 0; numerofor <=3; numerofor = numerofor +1)
                        System.out.println(numerofor);
            }
        }
        
        //EJERCICIO SWITCH//

public class Main {
    public static void main(String[] args) {
       var estacion = "jueves";

       switch (estacion) {
           case  "verano":
               System.out.println("es verano");
               break;
           case   "invierno":
               System.out.println("es invierno");
               break;
           case   "primavera":
               System.out.println("es primavera");
               break;
           case   "otoño":
               System.out.println("es otoño");
               break;
           default:
               System.out.println("no es una estacion");

       }
    }
}
