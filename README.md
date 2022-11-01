# algoritmo-qp
Triangulos, isósceles, equilátero e escaleno 
//

#include <stdio.h>
float a,b,c;
int main (){
	printf ("digite o lado a :");
	scanf("%f",&a);
	printf("digite o lado b :");
	scanf ("%f",&b);
	printf ("digite o lado c:");
	scanf ("%f",&c);
if (c+a>b && a+b>c && b+c>a){
	
	if (a==b && b==c && a==c){
		printf("\nO triangulo e equilatero\n");
	}
	else if (a==b || c==a || b==c){
		printf ("\nO triangulo e isosceles\n");
	}
	else{
	printf("\nOtriangulo e escaleno");
	}
}
else {
	printf("nao e um triangulo");
}
	
	return 0;
}
