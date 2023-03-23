# Lab_Assignment_7

#include <time.h>
#include <stdlib.h>
#include <stdio.h>

void bubbleSort (int array[], int n){
    int i, l, num;

    for(i = 0; i < n - 1; i++){
        for(l = 0; l < n - i - 1; l++){
            if(array[l] > array [l + 1]){

                num = array[l];
                array[l] = array[l + 1];
                array[l + 1] = num;
                
            }
        }
    }

}
