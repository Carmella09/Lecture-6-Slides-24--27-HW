# Lecture-6-Slides-24--27
//Odd or Even
using namespace std;
int main()
{
    int Number; 
    cout << "Enter any number: \n" << endl;
    cin >> Number; 
    if (Number % 2 == 0) {
        cout << Number << " is even ";
    }
    else {
        cout << Number << " is odd " << endl;
    }
    cin.get();
    return 0;
}

// Number Checker
using namespace std;
int main()
{
    double Number; 
    cout << "Enter any number: \n" << endl;
    cin >> Number; 
    if (Number > 0) {
        cout << Number << " is a positive number. ";
    }
    if (Number < 0) {
        cout << Number << " is a negative number. ";
    }
    else {
        cout << Number << " is a zero. " << endl;
    }
    cin.get();
    return 0;
}

// Profit or Loss (need help)
using namespace std;
int main()
{
    int Profit, Loss, Purchase, Sale;
    cout << "Enter the Purchase Price: \n" << endl;
    cin >> Purchase;
    cout << "Enter the Sale: \n" << endl;
    cin >> Sale;

    if (Profit = Purchase - Sale  ) {
        cout << " AED " << Profit << endl;
    }
    if (Loss = Sale - Purchase) {
        cout << " AED " << Loss << endl;
    }
    else {
        cout << " none " << endl;
    }
    cin.get();
    return 0;
}

// Name that Shape (need help)
using namespace std;
int main()
{
    int Shape;
    cout << "Enter any number: \n" << endl;
    cin >> Shape;
    if (Shape == 3) {
        cout << Shape << " is triangle " << endl;
    }
    if (Shape == 4) {
        cout << Shape << " is square" << endl;
    }
    if (Shape == 5) {
        cout << Shape << " is pentagon " << endl;
    }
    if (Shape == 6) {
        cout << Shape << " is a hexagon " << endl;
    }
    if (Shape == 7) {
        cout << Shape << " is a heptagon " << endl;
    }
    if (Shape == 8) {
        cout << Shape << " is a octagon " << endl;
    }
    if (Shape == 9) {
        cout << Shape << " is a nonagon " << endl;
    }
    if (Shape == 10) {
        cout << Shape << " is a star " << endl;
    }
    else {
        cout << Shape << " sides of shapes is not found " << endl;
    }
    cin.get();
    return 0;
}
