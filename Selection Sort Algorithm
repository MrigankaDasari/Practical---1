#include <iostream>
using namespace std;

int main() 
{
    int arr[] = {34, 92, 52, 22, 75};
    int n = 5;

    for (int i = 0; i < n - 1; i++) 
{
        int min = i;

        for (int j = i + 1; j < n; j++) 
{
            if (arr[j] < arr[min]) 
{
                min = j;
            }
        }

        swap(arr[i], arr[min]);
    }

    cout << "Sorted Array: ";
    for (int i = 0; i < n; i++)
        cout << arr[i] << " ";

    return 0;
}
