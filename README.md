# Activity-2
#include <iostream>

using namespace std;
int main() {
    string fullname;
    string courseYearsection;
    string birthday;
    string motto;
    
    cout << "Enter your Full Name: ";
    getline (cin, fullname);
    
    cout << "Enter Course Year and Section: ";
    getline (cin, courseYearsection);
    
    cout << "Enter Your Birthday: ";
    getline (cin, birthday);
    
    cout << "Enter your Motto in life: ";
    getline (cin, motto);
    
    cout  << " Hi! I'm " << fullname << " of " << courseYearsection << ". Welcome to DataStructures and alorithm!" << endl;
    cout << "My Birthday is on " << birthday <<". And my Motto in life is " << motto << "." << endl;
    
    return 0;
}
