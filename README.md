# Extra-lesson

    #include <iostream>
    #include <math.h>
    using namespace std;
    /*
    int main()
    {
        cout << "The cube of 8 is " << pow(8, 3) << endl;

        cout << "The square-root of 8 is " << sqrt(8) << endl;
        cout << "The square-root of 8 is " << pow(8, 1 / 2) << endl;

        cout << "The cube-root of 8 is " << cbrt(8) << endl;
        cout << "The cube-root of 8 is " << pow(8, 1 / 3) << endl;
    }
     */

    int main()
    {
        int n;
        double sq = 1, cb = 1;

        cout << " \n\nEnter the number you want to find the Square root and Cube root of : ";
        cin >> n;

        sq = sqrt(n);
        cb = cbrt(n);

        cout << " \n\nThe Square Root of the number " << n << " is : " << sq;
        cout << " \n\nThe Cube Root of the number " << n << " is : " << cb;
        cout << "\n\n\n";

        return 0;
    }
