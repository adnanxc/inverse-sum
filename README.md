# inverse-sum

#include <iostream>
using namespace std;


int main(){
    int n;
    cout << "Enter the value of N: ";
    cin >> n;
    cout << 1 << " +";
    for(int i=2; i<=n; i++){
        cout << " ("<< 1 << "/" << i << ") + ";
    }

    cout << "\b\b= ";

    float sum = 0;

    for(float i=1; i<=n; i++){

        sum = sum + (1/i);
    }
    cout << sum;
    return 0;
}
