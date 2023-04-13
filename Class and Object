#include<iostream>
#include<cmath>
#include<cstring>
using namespace std;

class Persegi{
	private:
		float panjang;
		float lebar;
	public:
		Persegi(float panjang, float lebar){
			this->panjang=panjang;
			this->lebar=lebar;
		}
		void setPanjang(float panjang){
			this->panjang=panjang;
		}
		void setLebar(float lebar){
			this->lebar=lebar;
		}
		float getPanjang(){
			return panjang;
		}
		float getLebar(){
			return lebar;
		}
		float luas(){
			return panjang*lebar;
		}
};
int main(){

	Persegi kotak1(10, 15);
	Persegi kotak2(5, 20);

	cout<<"Panjang: "<<kotak1.getPanjang()<<endl;
	cout<<"Lebar: "<<kotak1.getLebar()<<endl;
	cout<<"Luas: "<<kotak1.luas()<<endl;

	cout<<"Panjang: "<<kotak2.getPanjang()<<endl;
	cout<<"Lebar: "<<kotak2.getLebar()<<endl;
	cout<<"Luas: "<<kotak2.luas()<<endl;
}
