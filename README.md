# ConverteDolarEmReal
Conversor De Moeda Para o Real

import java.util.Scanner;


public class ConverteDolarEmReal {

	public static void main(String[] args) {
		Scanner entrada = new Scanner(System.in);
		double cotDolar, valDolar, valReal;
		
		System.out.print("Conversor de dólar em real.\n\n");
		
		System.out.print("Digite o valor do dólar:\n");
		cotDolar = entrada.nextDouble();
		
		System.out.print("Digite o valor em real:\n");
		valDolar = entrada.nextDouble();
		
		valReal = cotDolar * valDolar;
		
		System.out.println("O valor convertido para o real é: "+valReal+"\n");
		
		entrada.close();
	}

}
