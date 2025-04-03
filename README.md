# To study and implement C++ decision making statements
# AIM
To study and implement C++ decision making statements.

## if Statement:
The if statement evaluates a condition. If the condition is true, the code block inside the if statement is executed.

## if-else Statement:
This extends the if statement by adding an else block. If the condition is false, the code inside the else block is executed.

## switch Statement:
Used for handling multiple possible values of a single variable. It selects a block of code to execute based on the variable’s value.

## Calculator Statement:
It is used for doing mathematical calculations among some given values.

## CODE:

### 1.
```
//Nalin Kumar Srivastava
//23070123157
#include <iostream>
using namespace std;
int main() 
{
    double n1, n2, n3;
    cout << "Enter three numbers: ";
    cin >> n1 >> n2 >> n3;
    if(n1 >= n2 && n1 >= n3)
        cout << "Largest number: " << n1;
    else if(n2 >= n1 && n2 >= n3)
        cout << "Largest number: " << n2;
    else 
        cout << "Largest number: " << n3;
        return 0;
}
```

### 2.
```
//Nalin Kumar Srivastava
//23070123157
//experiment 5
#include <iostream>
using namespace std;
int main() 
{
    double n1, n2, n3;
    cout << "Enter three numbers: ";
    cin >> n1 >> n2 >> n3;
    if (n1 >= n2) 
    {
        if (n1 >= n3)
            cout << "Largest number: " << n1;
        else
            cout << "Largest number: " << n3;
    }
    else {
        if (n2 >= n3)
            cout << "Largest number: " << n2;
        else
            cout << "Largest number: " << n3;
    }
    return 0;
}
```

### 3.
```
//Nalin Kumar Srivastava
//23070123157
//experiment 5
#include<iostream>
using namespace std;

int main() {
    char oper;
    float num1, num2;

    cout << "Enter an operator (+, -, *, /): ";
    cin >> oper;
    cout << "Enter two numbers: " << endl;
    cin >> num1 >> num2;

    switch (oper) {
        case '+':
            cout << num1 << " + " << num2 << " = " << num1 + num2 << endl;
            break;
        case '-':
            cout << num1 << " - " << num2 << " = " << num1 - num2 << endl;
            break;
        case '*':
            cout << num1 << " * " << num2 << " = " << num1 * num2 << endl;
            break;
        case '/':
            if (num2 != 0)
                cout << num1 << " / " << num2 << " = " << num1 / num2 << endl;
            else
                cout << "Error! Division by zero." << endl;
            break;
        default:
            cout << "Error! The operator is not correct" << endl;
            break;
    }

    return 0;
}
```

### 4.
```
//Nalin Kumar Srivastava
//23070123157
//experiment 5
#include<iostream>
using namespace std;

int main()
{
    int choice;
    cout << "1. Monday" << endl
         << "2. Tuesday" << endl
         << "3. Wednesday" << endl
         << "4. Thursday" << endl
         << "5. Friday" << endl
         << "6. Saturday" << endl
         << "7. Sunday" << endl;
    cout << "Enter your choice: ";
    cin >> choice;
    
    switch(choice) {
        case 1:
            cout << "Monday" << endl;
            break;
        case 2:
            cout << "Tuesday" << endl;
            break;
        case 3:
            cout << "Wednesday" << endl;
            break;
        case 4:
            cout << "Thursday" << endl;
            break;
        case 5:
            cout << "Friday" << endl;
            break;
        case 6:
            cout << "Saturday" << endl;
            break;
        case 7:
            cout << "Sunday" << endl;
            break;
        default:
            cout << "Wrong Input" << endl;
            break;
    }
    
    return 0;
}
```

## OUTPUT
### 1.
![cds 1](https://github.com/user-attachments/assets/3276cba9-638e-4b7c-b942-12b07813db93)
### 2.
![cds 4](https://github.com/user-attachments/assets/32ce732c-4cf8-4f64-919b-58f7d0ec20d3)
### 3.
![cds 3](https://github.com/user-attachments/assets/383ed45c-78f7-4a7a-97d0-5aa7144efa8f)
### 4.
![cds 2](https://github.com/user-attachments/assets/8132069c-8fb5-4820-a9fb-08f44496aac1)

## Conclusion:
Decision-making statements in programming control the flow of execution based on conditions. The if-else statement executes different code blocks depending on whether a condition is true or false, while the nested if else statement allows for multiple conditions to be checked in sequence. The switch statement provides a way to select one of many code blocks to execute based on the value of an expression, ideal for handling discrete values. calculator helps in doing mathematical operations.
