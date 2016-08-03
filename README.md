#include<iostream>
#include<conio.h>
using namespace std;

int count = 0;
char co;

int main(){
  cout << "Please enter the paragraph:\n";
  cin >> co;
  
  while(co != '.')
  {
            if(co == 'a'){ 
            count = count + 1;
              cin >> co;
  }
 
 cout << "The 'a' in the paragraph is " << count << "." << endl;
 return 0;


