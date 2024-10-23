#include <iostream>
using namespace std;

int main() {
    float cal1, cal2, cal3, promedio;
    cout << "Ingrese las tres calificaciones: ";
    cin >> cal1 >> cal2 >> cal3;
    promedio = (cal1 + cal2 + cal3) / 3;
    cout << "Promedio: " << promedio << endl;
    if (promedio >= 60) {
        cout << "Aprobatoria" << endl;
    } else {
        cout << "Reprobatoria" << endl;
    }
    return 0;
}
