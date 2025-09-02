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

2.
#include <iostream>
using namespace std;

int main() {
    int number, sum = 0;

    while (true) {
        cout << "Enter an integer (0 to stop): ";
        cin >> number;

        if (number == 0)
            break;

        if (number > 0)
            sum += number;
    }

    cout << "Sum of positive integers: " << sum << endl;
    return 0;
}

3.
#include <iostream>
using namespace std;

int main() {
    int product = 1;
    int i = 1;

    while (i <= 5) {
        product *= i;
        i++;
    }

    cout << "Product of numbers from 1 to 5 is: " << product << endl;
    return 0;
}
