#include <iostream>

using namespace std;

class SumPositive {
public:
    int sum;

    SumPositive(int arr[], int n) {
        sum = 0;
        for (int i = 0; i < n; i++) {
            if (arr[i] > 0) {
                sum += arr[i];
            }
        }
    }

    SumPositive(const SumPositive& other) {
        sum = other.sum;
    }

    void displaySum() {
        cout << "Sum of positive numbers: " << sum << endl;
    }
};

int main() {
    int arr[] = {1, -2, 3, 4, -5};
    int n = sizeof(arr) / sizeof(arr[0]);

    SumPositive obj1(arr, n);
    SumPositive obj2(obj1); // Copy constructor called

    obj2.displaySum();

    return 0;
}
