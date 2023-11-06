# Data Structure & Algorithm With C++
## Basic Input Output syntex:
```c++
#include <iostream>

using namespace std;

int main(){  
    #ifndef ONLINE_JUDGE
    freopen("input.txt" , "r" , stdin);
    freopen("output.txt" , "w" , stdout);
    #endif
    return 0;
}
```  
## Operator :
### Shift operator : 
    a << n --> a * 2^n
    a >> n --> a / 2^n

### Miscellaneous Operators :
    sizeof() --> Returns the size of variable
    condition? X : Y --> Return the vale of X if condition is true or else value of Y
## Array
```c++
#include <iostream>

using namespace std;

void updateArray(int arr[] ,int size){
    arr[0] = 120;
}

int main(){
    int arr[4] = {1 ,2 , 3, 4};

    // Updating the array
    updateArray(arr , 4);

    // Printing the array element
    for (int i = 0; i < 4; i++)
    {
        cout << arr[i] << " ";
    }
    cout << endl;
    
    return 0;
}
``` 
It will updae because:
* In the updateAarray function arr gives the address of arr[0] element
* Array give the address of it's 1st Element. so function will update value in it's address. 

## Linear Search
### Write a program to find a key is present or not in a array.
```c++
#include <iostream>

using namespace std;

bool search(int arr[], int size, int key)
{
    for(int i = 0; i < size; i++){
        if(arr[i] == key){
            return 1;
        }
    }
    return 0;
}

int main()
{
    int key;
    cout << "Enter the key you want to search : ";
    cin >> key;

    int arr[10] = {2, 4, 6, 4, 90, 45, 33, 44, 58, 11};
    bool fount = search(arr , 10 , key);

    if(fount){
        cout << "This key is Present." << endl;
    }
    else{
        cout << "This key is Absent." << endl;
    }
        return 0;
}
```

## Bitwise Operators
* bitwise AND (&&)
* bitwise OR (||)
* bitwise XOR (^)
### AND
    0 && 0 = 0
    0 && 1 = 0
    1 && 0 = 0
    1 && 1 = 1
### OR
    0 || 0 = 0
    0 || 1 = 1
    1 || 0 = 1
    1 || 1 = 1
### XOR
    0 ^ 0 = 0
    0 ^ 1 = 1
    1 ^ 0 = 1
    1 ^ 1 = 0


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


```c++

```


```c++

```


```c++

```