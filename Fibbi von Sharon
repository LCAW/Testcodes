#include<stdio.h>

int main () {

	/*
	* Dieses Programm gibt die n-te Fibonacci Zahl aus
	*/

	printf("\n ************************** ");
	printf("\n *   ^,,,,^   *           * ");
	printf("\n *  ( o x o)  * Fibonacci * ");
	printf("\n *  ( 7   7)  *           * ");
	printf("\n *   ´´´´´´   *   ©S.Buch * ");
	printf("\n ************************** \n\n");
	
	//Einlesen der n-ten Fibonacci Zahl
	int f0=0,f1=1,n,i;
	printf("\nBitte geben Sie für fn eine Zahl für n ein: ");
	scanf("%d",&n);

	//Berechnung
	if (n==0 || n==1) {
		return n;
	}

	for (i=2;i<=n;i++) {
		int tmp = f0+f1;
		f0 = f1;
		f1 = tmp;	
	}
	printf("Die %d.Fibonacci Zahl ist %d",n,f1);

	//Ende
	printf("\n\n");
	return 0;
}
