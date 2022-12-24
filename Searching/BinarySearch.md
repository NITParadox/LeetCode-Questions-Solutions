# Binary Search

## Approch:

- First we will get the mid.
- After we check the element and compare with the arr[mid] and do the further computation
- return mid;

## JAVA code:

```JAVA
class Solution {
    public int binarySearch(int[] arr, int target){
        int start =0;
        int end = arr.length-1;
        while(start<=end){
            int mid = start + (end -start)/2;
            if(target<arr[mid]){
                end = mid-1;
            }else if(target>arr[mid]){
                start=mid+1;
            }
            else{
                return mid;
            }
        }
        return -1;
    }
}
```
