# proyecto-poo
GitHub Desktop tutorial repository

#include <iostream>
#include <cstdlib>
#include <stdio.h>
#include <conio.h>
 
using namespace std;
 
class matriculas
{
      public:
             	  char nombre[50];
                  char apellido[50];
                  int cuenta;
 
             void menu(){
                  int seleccion=0, repetir=1;
 
                  while(repetir==1)
                  {
                  system("cls");
                  cout<<" \n\n\n*************SISTEMA DE MATRICULA----- UNAH-----\n\n\n     "<<endl;
                  cout<<"1. MATRICULAR  " << endl;
                  cout<<"2.AGREGAR PROFESOR "<<endl;
                  cout<<"3.VER ALUMNOS MATRICULADOS"<<endl;

                  cout<<"5. SALIR "<<endl;
                  cout<<"Ingrese la opcion-> ";
                  cin>>seleccion;
                  cout<<endl;
 
                  switch(seleccion){
                      case 1:matricula(); getch();break;
                      case 2:agregar_profesor(); getch();break;
                      case 3:ver_alumnos_matriculados(); getch;break;
                      
                 
                      
                      case 5:repetir=0; break;
                      default: cout <<"Error. Dato Invalido!! "<<endl; getch();break;
                      }
                  }
                  }
                  
                  
                  
                  
                  int main()
{
    sistema matricular;
 
    cout << "Sistema matricula" << endl;
    cout<<endl;
 
 
    matricular.menu();
 
 
 
 
    system ("pause");
    return 0;
}
           
