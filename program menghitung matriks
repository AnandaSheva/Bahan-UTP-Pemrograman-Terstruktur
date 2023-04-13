#include<iostream>
using namespace std;

int main(){
    int baris1, kolom1;
    cin>>baris1>>kolom1;
    int matriks1[baris1][kolom1];
    for (int i=0; i<baris1; i++){
        for(int j=0; j<kolom1; j++){
            cin>>matriks1[i][j];
        }
    }
    int baris2, kolom2;
    cin>>baris2>>kolom2;
    int matriks2[baris2][kolom2];
    for (int i=0; i<baris2; i++){
        for(int j=0; j<kolom2; j++){
            cin>>matriks2[i][j];
        }
    }
    if(kolom1!=baris2){
        cout<<"Perhitungan tidak dapat dilakukan ";
    }else{
        int hasil[baris1][kolom2];
        for(int i=0; i<baris1; i++){
            for(int j=0; j<kolom2; j++){
            hasil[i][j]=0;
                for(int k=0; k<baris2; k++){
                    hasil[i][j]+=matriks1[i][k]*matriks2[k][j];
                }
            }
        }
        for (int i=0; i<baris1; i++){
            for(int j=0; j<kolom2; j++){
                cout<<hasil[i][j]<<" ";
            }
            cout<<endl;
            }
        }
}
