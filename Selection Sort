#include "stdio.h"


void main() {
    int n, arr[100], i, j;
    printf("Enter the size of array");
    scanf_s("%d", &n);
    printf("Enter the elements of the array");
    for (int i = 0; i < n; i++)
    {
        scanf_s("%d", &arr[i]);
    }
    int y;
    for (int i = 0; j < n; j++)
    {
        for (int i = j + 1; i < n; i++)
        {
            if (arr[i] < arr[j])
            {
                y = arr[i];
                arr[i] = arr[j];
                arr[j] = y;
            }
        }
    }
    printf("After sorting");
    for (i = 0; i < n; i++)
    {
        printf("%d,", arr[i]);
    }
}
