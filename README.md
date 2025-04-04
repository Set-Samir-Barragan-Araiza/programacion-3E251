# programacion-3E251
#include<iostream>
using namespace std;

int main()
{
   /* cout<<"Int :"<<sizeof(int)<<" bytes."<<endl;
    cout<<"float :"<<sizeof(float)<<" bytes."<<endl;
    cout<<"char :"<<sizeof(char)<<" bytes."<<endl;
    cout<<"bool :"<<sizeof(bool)<<" bytes."<<endl;
    cout<<"short :"<<sizeof(short)<<" bytes."<<endl;
    cout<<"long :"<<sizeof(long)<<" bytes."<<endl;
    cout<<"long long :"<<sizeof(long long)<<" bytes."<<endl;
    cout<<"unsigned long long :"<<sizeof(unsigned long long)<<" bytes."<<endl;*/
   // cout<<"Tipos de datos fundamentales \nint: 4 bytes, es la opción predeterminada para valores enteros\ndouble: 8 bytes, es la opción predeterminada para valores de punto flotante\nbool: 1 byte, representa valores que pueden ser true o false\nchar: 1 byte, se utiliza en los caracteres ASCII\nOtros tipos de datos \nunsigned int: 4 bytes, rango de 0 a 4294967295\nsigned int: 4 bytes, rango de -2147483648 a 2147483647\nsigned char: 1 byte, rango de –128 a 127\nunsigned char: 1 byte, rango de 0 a 255\nshort: 2 bytes, rango de –32,768 a 32,767\nunsigned short: 2 bytes, rango de 0 a 65,535";
   int a=74, b=185, *ptra;
   int *direccion=&a;
   ptra=&a;
   cout<<"\nOperador direccion : \n";
   cout<<"Direccion : "<<direccion;
   cout<<"\nValor de Direccion : "<<*direccion;
   cout<<"\nDireccion de Direccion : "<<&direccion<<"\nEspacio ocupado : "<<sizeof(direccion);
   cout<<"\n\nValor de a : "<<a<<"\nEspacio ocupado : "<<sizeof(a);
   cout<<"\nValor de b : "<<b<<"\nEspacio ocupado : "<<sizeof(b);
   cout<<"\nDireccion a : "<<&a<<"\nDireccion b : "<<&b;
   *ptra=120;
   cout<<"\nValor nuevo de a : "<<a<<"\nEspacio ocupado : "<<sizeof(a);
   return 0;
}