include <stdio.h>

// Function to find the single number
int findSingleDigit(int* nums, int numsSize) {
    int result = 0;
    for (int i = 0; i < numsSize; i++) {
        result ^= nums[i]; // XOR each element with the result
    }
    return result;
}

int main() {
    int nums[] = {6, 5, 6, 2, 5};
    int numsSize = sizeof(nums) / sizeof(nums[0]);

    int singleNumber = findSingleDigit(nums, numsSize);
    printf("The single number is: %d\n", singleNumber);

    return 0;
}
