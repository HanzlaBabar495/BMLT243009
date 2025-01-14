C++ CODE (FOR ADDING TWO NUMBERS)

#include <iostream>

int main() {
    // Declare variables to hold the numbers
    float num1, num2, sum;

    // Ask the user for input
    std::cout << "Enter first number: ";
    std::cin >> num1;

    std::cout << "Enter second number: ";
    std::cin >> num2;

    // Calculate the sum
    sum = num1 + num2;

    // Display the result
    std::cout << "The sum of " << num1 << " and " << num2 << " is: " << sum << std::endl;

    return 0;
}


C++ CODE (FOR FINDING PERCENTAGE)



#include <iostream>
using namespace std;

int main() {
    float obtainedMarks, totalMarks, percentage;

    // Ask user for obtained marks and total marks
    cout << "Enter obtained marks: ";
    cin >> obtainedMarks;
    cout << "Enter total marks: ";
    cin >> totalMarks;

    // Check if total marks is not zero to avoid division by zero
    if (totalMarks > 0) {
        // Calculate percentage
        percentage = (obtainedMarks / totalMarks) * 100;

        // Display the percentage
        cout << "Percentage: " << percentage << "%" << endl;
    } else {
        cout << "Total marks cannot be zero." << endl;
    }

    return 0;
}




