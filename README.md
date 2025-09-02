#include <iostream>
using namespace std;

int main() {
    int i = 0;

    // Print numbers 0 to 10
    while (i <= 10) {
        cout << i << " ";
        i++;
    }
    cout << endl;

    int j = 10;

    // Print numbers 10 to 0
    while (j >= 0) {
        cout << j << " ";
        j--;
    }
    cout << endl;

    return 0;
}


#include <iostream>
using namespace std;

int main() {
    int num;
    int sum = 0;

    cout << "Enter a number (0 to stop): ";
    cin >> num;

    while (num != 0) {  // loop runs until user enters 0
        if (num > 0) {
            sum += num;  // add only positive numbers
        }
        cout << "Enter a number (0 to stop): ";
        cin >> num;
    }

    cout << "Sum of positive numbers: " << sum << endl;

    return 0;
}


#include <iostream>
using namespace std;

int main() {
    int product = 1;
    int i = 1;

    while (i <= 5) {
        product *= i;  // multiply product by i
        i++;
    }

    cout << "Product of numbers from 1 to 5 is: " << product << endl;

    return 0;
}

