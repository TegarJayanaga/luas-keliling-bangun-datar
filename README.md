// luas-keliling-bangun-datar
// implementasi pointer array dan fungsi 
#include <iostream>
#include <cmath>
using namespace std;
  
  
  double luas_persegi(double sisi){
  	double luas;
	  luas = 0;
	  luas = sisi * sisi;
	  return luas;
  }
  
  double keliling_persegi(double sisi){
  	double keliling ;
	  keliling = 0;
	  keliling = sisi * 4;
	  return keliling;
  }
  
  void cetak_luas(double s){
  	
  	  cout<<"luas persegi adalah : "<<luas_persegi(s)<<endl;
     }
  
  void cetak_keliling(double s){
  	
	  cout<<"keliling persegi adalah : "<<keliling_persegi(s)<<endl;
  }
  
  int main(){
  	double sisi[2];
  	
  	for(int i=1 ; i<=2; i++){
  			sisi[2]=0;
  			
	  cout<<" masukkan sisi persegi ke "<<i<<" : ";
	  cin>>sisi[i];
	  }
	  cout<<endl;
	  for(int i=1 ; i<=2 ; i++){
	  
	  cetak_luas(sisi[i]);
	  }
	  cout<<endl;
	  for (int i=1 ; i<=2 ; i++){
    	
    	cetak_keliling(sisi[i]);
    }
    return 0;
    }
  
  
  
  
  
  
   
  
