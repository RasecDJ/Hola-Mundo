#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main( ) {
	int n=0;
	printf("ESCRIBIR EL VALOR FACTORIAL");
	//DE ESTA FORMA N=N*(N-1)
	scanf("%d",&n);//n NUMERO ELEGIDO POR EL USUARIO
	int nfac=n-1;//nfac NUMERO FACTORIAL DECRECIENTE DE n-1
	int fact=n;//fact RESULTADO DEL FACTORIAL
	while (nfac>=1){
		fact=fact*nfac;nfac--;//FORMULA
}
printf("RESULTADO FACTORIAL DE %d es: %d",n,fact);
}
