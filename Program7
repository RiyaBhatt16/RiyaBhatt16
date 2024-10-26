#include <iostream>

using namespace std;

class Base {
public:
    int num1;

    Base(int a) {
        num1 = a;
    }
};

class Derived1 : public Base {
public:
    int num2;

    Derived1(int a, int b) : Base(a) {
        num2 = b;
    }
};

class Derived2 : public Derived1 {
public:
    Derived2(int a, int b) : Derived1(a, b) {}

    int sum() {
        return num1 + num2;
    }
};

int main() {
    Derived2 obj(10, 20);
    int result = obj.sum();
    cout << "Sum: " << result << endl;
    return 0;
}
