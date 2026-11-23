# Leet-Code-
SOLVED QUESTIONS DAILY Consistency 

class Solution {
    public static int smallestSubWithSum(int x, int[] arr) {
       int i = 0;
       int j = 0;
       int ans = Integer.MAX_VALUE;
       int sum = 0;
       while(i<arr.length) {
           sum += arr[i];
           while(sum > x) {
               ans = Math.min(ans,i-j+1);
               sum -= arr[j];
               j++;
           }
           i++;
       }
         return ans == Integer.MAX_VALUE ? 0 : ans;
    }
}
