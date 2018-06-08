/*escribe un programa que lea de la entrada estandar 
los dos catetos de un triangulo rectangulo  y escriba en la 
salida estandar de su hipotenusa*/

#include <iostream>
#include <math.h>

using namespace std;

int main(){
	
	float base, altura, hipotenusa = 0, x = 0, c = 0, d = 0;
	
	cout<<"escribe la base : "; cin>>base;
	cout<<"escriba el altura:"; cin>>altura;
        
    c = base * base;
    d = altura * altura;
        
    x = c + d;
    
    hipotenusa = (sqrt(x)); //raiz cuadrada es (1/2)
    
     cout<<"\nla hipotenusa es:"<<hipotenusa<<endl;
    
		return 0;
}
