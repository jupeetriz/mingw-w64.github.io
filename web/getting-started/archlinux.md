#include <iostream>
using namespace std;

void ubah(int *b);

int main() {
    int a = 12;
    cout << "isi nilai semula = " << a << endl;

    ubah(&a);

    cout << "isi nilai sekarang = " << a << endl;
    return 0;
}

void ubah(int *b) {
    *b = *b + 22;
}
