#include<iostream>
using namespace std;
  
  struct node{
	int data;
	node *selanjutnya;
};
node *palingdepan = NULL;

bool isempty(){
	if (palingdepan == NULL){
		return 1;
	}
	else {
		return 0;
	}
}
