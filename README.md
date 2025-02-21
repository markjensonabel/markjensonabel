#include <iostream>
using namespace std;

int main() {
  double grams, pounds;

  cout << "Enter weight in grams: ";
  cin >> grams;

  pounds = grams * 0.00220462;
  cout << grams << " grams is equal to " << pounds << " pounds." << endl;

  return 0;
}
