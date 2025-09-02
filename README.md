1.
#include <iostream>
using namespace std;

int main() {
    int i = 0;

    // Print numbers from 0 to 10
    while (i <= 10) {
        cout << i << " ";
        i++;
    }

    cout << endl;

    // Print numbers from 10 to 0
    int j = 10;
    while (j >= 0) {
        cout << j << " ";
        j--;
    }

    cout << endl;
    return 0;
}

