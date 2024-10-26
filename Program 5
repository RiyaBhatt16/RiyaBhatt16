#include <iostream>

using namespace std;

class A {
public:
    int num1, num2;

    A(int a, int b) {
        num1 = a;
        num2 = b;
    }
};

class B : public A {
public:
    B(int a, int b) : A(a, b) {}
};

class C : public A {
public:
    C(int a, int b) : A(a, b) {}
};

class D : public A {
public:
    D(int a, int b) : A(a, b) {}
};

class E : public B {
public:
    E(int a, int b) : B(a, b) {}

    void displayNum1() {
        cout << "First number: " << num1 << endl;
    }
};

int main() {
    E obj(10, 20);
    obj.displayNum1();
    return 0;
}
