#include <iostream>
using namespace std;
int main() {
    int input;
    cout << "Which console do you prefer?\n";
     cout << "Playstation, Xbox, Nintendo, or pc?\n";
    cout << endl;

    int p, x, n, pc;//declare variables

    cout << "Playstation: ";
    cin >> p; 
    cout << "Xbox: ";
    cin >> x;
    cout << "Nintendo: ";
    cin >> n;
    cout << "Pc: ";
    cin >> pc;

    for (int i = 0; i < p; i++)
        cout << "*";
    cout << endl << endl;

    for (int i = 0; i < n; i++)
        cout << "*";
    cout << endl << endl;

    for (int i = 0; i < x; i++)
        cout << "*";
    cout << endl << endl;

    for (int i = 0; i < pc; i++)
        cout << "*";
    
return 0;
}
