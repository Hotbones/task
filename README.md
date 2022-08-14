Primera parte:

Crear una función con tres parámetros que sean números que se suman entre sí.

Llamar a la función en el main y darle valores.

	public class Main {
    public static void main(String[] args) {
       suma(12,5,4);

    }

    public static int suma(int a, int b, int c) {
        int resultado;
        resultado = a + b + c;
        System.out.println("El resultado es: " + resultado);
        return resultado;
    }
	}

-----------------------------------

Segunda parte:

Crear una clase coche.

Dentro de la clase coche, una variable numérica que almacene el número de puertas que tiene.

Una función que incremente el número de puertas que tiene el coche.

Crear un objeto miCoche en el main y añadirle una puerta.

Mostrar el número de puertas que tiene el objeto.

	public class Main {
    public static void main(String[] args) {
        Coche micoche = new Coche();
        micoche.incrementar();
        System.out.println("El objeto Micoche, ahora tiene " + micoche.puertas + " puertas");
    }
	}

	class Coche {
    public int puertas = 4;

    public void incrementar(){
        this.puertas++ ;
    }
	}
