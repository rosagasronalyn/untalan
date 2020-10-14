//Compiler version g++ 6.3.0

# include <iostream>
using namespace std;

int main()
{
    char op;
    float num1, num2;

    cout<<"Enter First Number:";
    cin>>num1;
    cout << "Enter operator either + or - or * or /: ";
    cin >> op;

    cout << "Enter second number: ";
    cin>> num2;

    switch(op)
    {
        case '+':
            cout << num1+num2;
            break;

        case '-':
            cout << num1-num2;
            break;

        case '*':
            cout << num1*num2;
            break;

        case '/':
            cout << num1/num2;
            break;

        default:
            // If the operator is other than +, -, * or /, error message is shown
            cout << "Error! operator is not correct";
            break;
    }

    return 0;
}
