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

class Derived1 : public Base {
public:
    Derived1(int a, int b) : Base(a, b) {}

    void displayNum1() {
        cout << "First number: " << num1 << endl;
    }
};

class Derived2 : public Base {
public:
    Derived2(int a, int b) : Base(a, b) {}

    void displayNum2() {
        cout << "Second number: " << num2 << endl;
    }
};

int main() {
    Derived1 obj1(10, 20);
    Derived2 obj2(10, 20);

    obj1.displayNum1();
    obj2.displayNum2();

    return 0;
}
