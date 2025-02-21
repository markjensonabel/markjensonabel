#include <iostream>
#include <iomanip>

using namespace std;

double gramsToPounds(double grams) {
    return grams * 0.00220462; // Conversion factor
}

int main() {
    double grams;
    
    // User input
    cout << "Enter weight in grams: ";
    cin >> grams;

    // Convert and display result
    double pounds = gramsToPounds(grams);
    cout << fixed << setprecision(4); // Format output to 4 decimal places
    cout << grams << " grams is equal to " << pounds << " pounds." << endl;

    return 0;
}
