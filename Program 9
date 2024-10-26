#include <iostream>

using namespace std;

class Base {
public:
    int num1, num2;

    Base(int a, int b) {
        num1 = a;
        num2 = b;
    }
};

class Derived : public Base {
public:
    Derived(int a, int b) : Base(a, b) {}

    int product() {
        return num1 * num2;
    }
};

int main() {
    Derived obj(5, 10);
    int result = obj.product();
    cout << "Product: " << result << endl;
    return 0;
}
