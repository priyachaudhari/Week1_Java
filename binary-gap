class Solution {
    public int binaryGap(int N) {     
 
        while(N > 0){
            
            if((N & 1) == 1){
               flag = 1;
               max = Math.max(max,count);
               count = 0;  
            }
             
            if(flag == 1){
            count++;
            }
            
            N = N >>> 1;
        }      
        return max;      
    }
}
