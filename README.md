//
#include <iostream>
using namespace std;

int main()
{
    float temp;

    cout << "===== Form of Water =====" << endl;
    cout << "Temperature Less than 0                = ICE" << endl;
    cout << "Temperature Greater than 0 & Less than 100 = Water" << endl;
    cout << "Temperature Greater than 100           = STEAM" << endl;
    cout << "=========================" << endl;

    cout << "Enter temperature (C): ";
    cin >> temp;

    if (temp < 0)
        cout << "ICE";
    else if (temp > 0 && temp < 100)
        cout << "Water";
    else if (temp > 100)
        cout << "STEAM";
    else
        cout << "Boundary value (0 or 100): two forms exist together";

    return 0;
}
