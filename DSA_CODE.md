# DSA Problem Solving

## 1. Write a C++ program to find the maximum and minimum values in an array of 10 integers entered by the user.
```c++
#include <iostream>
#include <climits>
using namespace std;

// Finding Max Value function
int arrMax(int number[] , int size)
{

    int max = INT_MIN;

    for (int i = 0; i < size; i++)
    {
        if (number[i] > max)
        {
            max = number[i];
        }
    }
    return max;
}

// Finding Max Value function
int arrMin(int number[] , int size)
{

    int min = INT_MAX;

    for (int i = 0; i < size; i++)
    {
        if (number[i] < min)
        {
            min = number[i];
        }
    }
    return min;
}

int main()
{
    int number[10];
    // Reciving array input
    for (int i = 0; i < 10; i++)
    {
        cout << "Enter this array Value " << i + 1 << " : ";
        cin >> number[i];
    }

    cout << "The Max value of this array : " << arrMax(number , 10) << endl;
    cout << "The Min value of this array : " << arrMin(number , 10) << endl;
    return 0;
}
```


## 2. Write a program to reverse an Array.
```c++
#include <iostream>

using namespace std;

void printArray(int arr[] , int size){
    cout << "The array is : ";
    for (int i = 0; i < size; i++)
    {
       cout << arr[i] << " "; 
    }
    cout << endl;
}

void reverseArray(int arr[] , int size){
    int count = 0;
    int new_arr[size];
    for (int i = 0; i < size; i++)
    {
        new_arr[i] = arr[(size -1) -count];
        count++;
    }
    for (int i = 0; i < size; i++)
    {
        arr[i] = new_arr[i]; 
    }
}

int main(){
    int arr[10] = {1,2,3,4,5,6,7,8,9,10};
    printArray(arr , 10);

    // Reverse the array
    reverseArray(arr , 10);
    printArray(arr , 10);
    return 0;
}
```


## 3. Write a program to swap altarnate of an array element.
```c++
#include <iostream>

using namespace std;
void printArray(int arr[] , int size){
    cout << "The Array is : { ";
    for (int i = 0; i < size; i++)
    {
        cout << arr[i] << " ";
    }
    cout << "}" << endl;
    
}

void altarnateArray(int arr[] , int size){
    for (int i = 0; i < size; i+=2)
    {
        if(size % 2 != 0){
            if(i == size - 1){
                break;
            }
        }
        int temp;
        temp = arr[i];
        arr[i] = arr[i+1];
        arr[i+1] = temp;
    }
    
}

int main(){
    // Event Array :
    int arr[6] = {1, 2 , 7, 8, 6 , 9};
    printArray(arr , 6);

    altarnateArray(arr , 6);
    printArray(arr , 6);

    // Odd Array
    int arr2[5] = {1, 2 , 7, 8, 6 };
    printArray(arr2 , 5);

    altarnateArray(arr2 , 5);
    printArray(arr2 , 5);
    return 0;
}
```


## 4. 
```c++

```



```c++

```



```c++

```



```c++

```



```c++

```



```c++

```



```c++

```



```c++

```



```c++

```



