#include <iostream>

using namespace std;

class Base1 {
public:
    int num1;

    Base1(int a) {
        num1 = a;
    }
};

class Base2 {
public:
    int num2;

    Base2(int b) {
        num2 = b;
    }
};

class Derived : public Base1, public Base2 {
public:
    Derived(int a, int b) : Base1(a), Base2(b) {}

    int sum() {
        return num1 + num2;
    }
};

int main() {
    Derived obj(10, 20);
    int result = obj.sum();
    cout << "Sum: " << result << endl;
    return 0;
}
