class Solution {
    public int[] searchRange(int[] nums, int target) {
     int s=-1;
	   int [] ans= {-1,-1};//create an array with the “default” values
		 if(nums.length==0){//if the array is blank then return [-1,-1]
		    return ans;
		 }
     for (int i=0;i<nums.length;i++){//looping through the array
          if(i>0&&(nums[i]==target&&nums[i-1]<target)){
				    s=i;//the starting position of the target
          }
			    if(nums[i]==target){
				    ans[1]=i;//it will eventually be the last position of the target
			    }
     }
		 if(nums[0]==target){//if the array started with the target
        s=0;
     }
		ans[0]=s;//assigning s to the start position
		return ans;
    }
}
