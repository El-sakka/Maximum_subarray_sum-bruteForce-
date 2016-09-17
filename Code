#include <bits/stdc++.h>
//#include called preprocessor directive
using namespace std;

//Ready or not here i  come
int Maximum_subarray_Sum(int arr[],int size){
	int ans = INT_MIN;// represent the minimum value of an integer value
	//here to check the size of sub array start from what ! as you want 
	for(int sub_array_size=2;sub_array_size<=size;sub_array_size++){

		for(int start_indx=0;start_indx<size;start_indx++){

			if(start_indx+sub_array_size > size )	//here to bound the exceeds of the array
				break;

			int sum = 0;

			for(int indx = start_indx;indx < (start_indx + sub_array_size);indx++)
				sum+=arr[indx];

			ans = max(ans,sum);
		}
	}
	return ans;
}

int main() {

	int arr[]={1,-2,5,-1};
	int max;
	max=Maximum_subarray_Sum(arr,4);
	cout<<max;

}
