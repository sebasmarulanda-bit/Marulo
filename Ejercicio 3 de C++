#include <iostream> 
using namespace std; 
int main()
{
	int N;
	int suma = 0;
	int i = 1;
	bool esPrimo = true;	
	cout << "Ingrese un numero N: ";
	cin >> N;	
	cout << "\nTabla de multiplicar del " << N << ":" << endl;
	for (int j = 1; j <= 10; j++)
	{
    	cout << N << " x " << j << " = " << N * j << endl;
	}	
	while (i <= N)
	{
    	suma = suma + i;
    	i++;
	}
	cout << "\nSuma acumulada desde 1 hasta " << N << ": " << suma << endl;
	if (N <= 1)
	{
    	esPrimo = false;
	} else {
    	for (int k = 2; k <= N / 2; k++)
    	{
        	if (N % k == 0) {
            	esPrimo = false;
            	break;
        	}
    	}
	}
 
	if (esPrimo)
	{
    	cout << "El numero " << N << " es primo." << endl;
	} else
	{
    	cout << "El numero " << N << " no es primo." << endl;
	}
 
	return 0;
}
