#include <iostream>
using namespace std;

double calcularAreaCirculo(double radio){
    const double PI= 3.1416;
    return PI * radio * radio;
}
    long long calcularFactorial (int numero){
         long long factorial =1;
         for ( int i=1; i <= numero; i++){
             factorial *=i;
             
         }
    return factorial;
        
    }
    
    void verificarParImpar(int numero){
        if (numero % 2 == 0 ){
            cout << "El numero es PAR." <<endl;
            
        }
    else{
        cout <<"El numero es IMPAR."<<endl;
     }
        
    }
    int main () {
        int opcion;
        
        do {
        cout << "\n===== MENU =====" << endl;
        cout << "1. Calcular area de un circulo" << endl;
        cout << "2. Calcular factorial" << endl;
        cout << "3. Verificar si un numero es par o impar" << endl;
        cout << "4. Salir" << endl;
        cout << "Seleccione una opcion: ";
        cin >> opcion;

        if (opcion == 1) {
            double radio;
            cout << "Ingrese el radio: ";
            cin >> radio;
            cout << "Area del circulo: " << calcularAreaCirculo(radio) << endl;
        }
        else if (opcion == 2) {
            int numero;
            cout << "Ingrese un numero: ";
            cin >> numero;

            if (numero < 0) {
                cout << "No existe factorial de numeros negativos." << endl;
            } else {
                cout << "Factorial: " << calcularFactorial(numero) << endl;
            }
        }
        else if (opcion == 3) {
            int numero;
            cout << "Ingrese un numero: ";
            cin >> numero;
            verificarParImpar(numero);
        }
        else if (opcion == 4) {
            cout << "Saliendo del programa..." << endl;
        }
        else {
            cout << "Opcion no valida." << endl;
        }

    } while (opcion != 4);

    return 0;
            
}
    
