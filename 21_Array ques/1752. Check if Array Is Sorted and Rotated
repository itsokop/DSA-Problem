class Solution {
public:
    bool check(vector<int>& nums) {
        
        // time complexity O(N)
        int count = 0;          
        for(int i=1; i<nums.size(); i++){
            if(nums[i] < nums[i-1]) count++;
        }
        if(count==0) return true;
        else if(count==1 && nums[nums.size()-1] <= nums[0]){    // = is imp
            return true;
        }
        return false;
    }
};
