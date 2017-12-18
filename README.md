# entornos01
Repositorio de ejemplo para Entornos

## Encabezado 2

- Item de la lista
- Otro item
- Y otro más

## Otras cosas

Puedo dar formato en *cursiva* y en **negrita**

Y poner [enlaces](https://gregoriofer.com).

## Probando código

Tienes que hacer System.out.println("Hello") en tu primer código de Java.

## Ejemplo de cálculo del factorial de un número.
public class Factorial
{
	public static void main(String[] args)
	{	final int NUM_FACTS = 100;
		for(int i = 0; i < NUM_FACTS; i++)
			System.out.println( i + "! is " + factorial(i));
	}
	
	public static int factorial(int n)
	{	int result = 1;
		for(int i = 2; i <= n; i++)
			result *= i;
		return result;
	}
}
