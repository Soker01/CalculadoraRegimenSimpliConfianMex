#include <stdio.h>
int main() {
	int n = 0;
	float Rete, IVA, total, res, Total;
	do {
	printf("\n Introduce Total: ");
	scanf("%f",&Total);
	        
			Rete = (Total)/(1.1475);
			res = Rete*(.0125);
			IVA = (Rete)*(0.16);
			total = IVA + Rete - res;
	        
	        printf("El Importe es de: %.2f",Rete);
	        printf("\nEl iva es de es de: %.2f",IVA);
	        printf("\nLa retencion es de es de: %.2f",res);
	        printf("\nEl total completo es: %.2f",total);
	printf("\n deseas continuar si = 1 no = 0: ");
	scanf("%d",&n);
	
	}while(n == 1);
	
	return 0;
}
