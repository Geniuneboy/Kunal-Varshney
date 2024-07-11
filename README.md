#include <stdio.h>

int main() {
    int arr[5] = {10, 20, 30, 40, 50};
    
    // Verify the size of the array
    printf("Size of the array: %lu bytes\n", sizeof(arr));
    
    // Verify the size of an integer
    printf("Size of an integer: %lu bytes\n", sizeof(int));
    
    // Print the address of each element in the array
    for(int i = 0; i < 5; i++) {
        printf("Address of arr[%d]: %p\n", i, (void*)&arr[i]);
    }
    
    return 0;
}
