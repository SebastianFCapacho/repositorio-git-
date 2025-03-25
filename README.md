#include <iostream>
using namespace std;

int main() {
    float nota1, nota2, nota3, promedio;


    cout << "Ingresa la primera nota (0-100): ";
    cin >> nota1;
    while (nota1 < 0 || nota1 > 100) {
        cout << "Nota inválida. Ingresa una nota entre 0 y 100: ";
        cin >> nota1;
    }

    cout << "Ingresa la segunda nota (0-100): ";
    cin >> nota2;
    while (nota2 < 0 || nota2 > 100) {
        cout << "Nota inválida. Ingresa una nota entre 0 y 100: ";
        cin >> nota2;
    }

    cout << "Ingresa la tercera nota (0-100): ";
    cin >> nota3;
    while (nota3 < 0 || nota3 > 100) {
        cout << "Nota inválida. Ingresa una nota entre 0 y 100: ";
        cin >> nota3;
    }

 
    promedio = (nota1 + nota2 + nota3) / 3;

    // Mostrar el promedio
    cout << "El promedio de las tres notas es: " << promedio << endl;

    return 0;
}
