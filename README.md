# Poblaci-n-on-resultado-
Código 
/* Carlos Torres , MT42M*/
#include<iostream>
#include<stdlib.h>
#include"conio.h"
#include<math.h>
#include<stdio.h>

using namespace std;
int main () {
	do
	{
	int poblacion, periodo, poblacionfn;
	 cout <<"\nIntroduzca una población inicial: ";
	 cin >> poblacion;
	 cout << "\nInjtroduzca una poblacion final: ";
	 cin << poblacionfn
	}

		 while ((poblacion >9) && (poblacion < poblacionfn));
	 {
		 int Resultado;
		 Resultado = log(poblacionfn / poblacion);
		 printf("Años",Resultado);
		 printf("Población inicial:", poblacion);
		 printf("Población final:", poblacionfn);
}
	 EXIT_SUCCESS;
}
