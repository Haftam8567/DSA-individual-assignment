# DSA-individual-assignment
algorthim of smallest num in array
Initialize a variable `smallest` with the first element of the  array.
  2. Iterate through the array starting from the second element.
    3. Compare each element with `smallest`.
      4. If the current element is greater than `smallest`, update  `smallest` with the current element.  5. After the loop ends, `smallest' will contain the smallest number in the array.  
        ## How to Run the Code 
         1. Clone the repository to your local machine.
           2. Open the terminal and navigate to the repository directory. 
            3. Compile the C++ code using:     ```bash     g++ main.cpp -o main    Run the compiled 
        program:  ./main  Output  The program will output:  The smallest number in the array is: 2
        smallest-number-in-arry 
        include <iostream>
using namespace std;

int findsmallest(int arr[], int size) { 
    int smallest = arr[0]; 
    for (int i = 1; i < size; i++) { 
        if (arr[i] < smallest) {  
            smallest = arr[i]; 
        } 
    } 
    return smallest; 
} 

int main() { 
    int arr[] = {10, 2, 30, 40, 5}; 
    int size = sizeof(arr) / sizeof(arr[0]); 
    int smallest = findsmallest(arr, size); 
    cout << "The smallest number in the array is: " << smallest << endl; 
    return 0; 
}algorthim of smallest num in array
Initialize a variable `smallest` with the first element of the  array.
  2. Iterate through the array starting from the second element.
    3. Compare each element with `smallest`.
      4. If the current element is greater than `smallest`, update  `smallest` with the current element.  5. After the loop ends, `smallest' will contain the smallest number in the array.  
        ## How to Run the Code 
         1. Clone the repository to your local machine.
           2. Open the terminal and navigate to the repository directory. 
            3. Compile the C++ code using:     ```bash     g++ main.cpp -o main    Run the compiled 
        program:  ./main  Output  The program will output:  The smallest number in the array is: 2
        smallest-number-in-arry 
        include <iostream>
using namespace std;

int findsmallest(int arr[], int size) { 
    int smallest = arr[0]; 
    for (int i = 1; i < size; i++) { 
        if (arr[i] < smallest) {  
            smallest = arr[i]; 
        } 
    } 
    return smallest; 
} 

int main() { 
    int arr[] = {10, 2, 30, 40, 5}; 
    int size = sizeof(arr) / sizeof(arr[0]); 
    int smallest = findsmallest(arr, size); 
    cout << "The smallest number in the array is: " << smallest << endl; 
    return 0; 
}