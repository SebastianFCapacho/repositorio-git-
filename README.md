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

2 ejercicio 
#include <iostream>
#include <cmath> 
using namespace std;

int main() {
    double altura, tiempo;
    const double g = 9.81;  // Aceleración de la gravedad en m/s^2
    cout << "Ingresa la altura desde la que cae el objeto (en metros): ";
    cin >> altura; 
    while (altura <= 0) {
        cout << "La altura debe ser positiva. Ingresa una altura válida: ";
        cin >> altura;
    }
    tiempo = sqrt((2 * altura) / g);
    cout << "El tiempo de caída es: " << tiempo << " segundos." << endl;
    return 0;
}
3 ejercicio 
#include <iostream>
using namespace std;

int main() {
    double base, altura, area;
    cout << "Ingresa la base del rectángulo (en metros): ";
    cin >> base;
    cout << "Ingresa la altura del rectángulo (en metros): ";
    cin >> altura;
    area = base * altura;
    cout << "El área del rectángulo es: " << area << " metros cuadrados." << endl;
    return 0;
}
4 ejercicio 
#include <iostream>
using namespace std;

int main() {
    double base, altura, area;
    cout << "Ingresa la base del triángulo (en metros): ";
    cin >> base;
    cout << "Ingresa la altura del triángulo (en metros): ";
    cin >> altura;
    area = 0.5 * base * altura;
    cout << "El área del triángulo es: " << area << " metros cuadrados." << endl;
    return 0;
}


