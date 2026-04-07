#include <iostream>
using namespace std;

int main() {
    int n;

   
    cout << "Ingrese la cantidad de estudiantes: ";
    cin >> n;

   
    if (n <= 0) {
        cout << "Cantidad invalida." << endl;
        return 0;
    }

    
    double* notas = new double[n];

   
    for (int i = 0; i < n; i++) {
        cout << "Ingrese la nota del estudiante " << i + 1 << ": ";
        cin >> notas[i];
    }

   
    double suma = 0;
    double mayor = notas[0];
    double menor = notas[0];

    for (int i = 0; i < n; i++) {
        suma += notas[i];

        if (notas[i] > mayor) {
            mayor = notas[i];
        }

        if (notas[i] < menor) {
            menor = notas[i];
        }
    }

    double promedio = suma / n;

 
    cout << "\nPromedio: " << promedio << endl;
    cout << "Nota mayor: " << mayor << endl;
    cout << "Nota menor: " << menor << endl;

  
    delete[] notas;

    return 0;
}
