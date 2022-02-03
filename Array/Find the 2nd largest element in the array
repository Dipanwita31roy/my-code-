#include <iostream>
using namespace std;
int main()
{
    int arr[] = {1, 2, 4, 6, 7, 5};
    int max = -100;
    int x;
    for (int i = 0; i < sizeof(arr) / sizeof(int); i++)
    {
        if (arr[i] > max)
        {
            max = arr[i];
            x = i;
        }
    }

    max = -100;
    for (int i = 0; i < sizeof(arr) / sizeof(int); i++)
    {
        if (x == i)
        {
            continue;
        }

        if (arr[i] > max)
        {
            max = arr[i];
        }
    }
    cout << "our 2nd max:" << max << endl;

    return 0;
}
