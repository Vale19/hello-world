//Librerie
#include <iostream>
using namespace std;

//Dichiarazione Variabili
float a; // primo lato 
float b; // secondo lato 
float c; // terzo lato 

int main ()
{
	cout<<"inserisci il primo lato: \n";
	cin>>a;
	cout<<"inserisci il secondo lato: \n";
	cin>>b;
	cout<<"inserisci il terzo lato: \n";
	cin>>c;
	if(a==b)
	{
		if(b==c)
		{
			cout<<"\n\n\n Triangolo equilatero\n";
		}
		else
		{
			cout<<"\n\n\n Triangolo isoscele\n";
		}
	}	
	else
	{
		if(a==c)
		{
			cout<<"\n\n\n Triangolo isoscele\n";
		}
		else
		{
			cout<<"\n\n\n Triangolo scaleno\n";
		}
		if(b==c)
		{
			cout<<"\n\n\n Triangolo isoscele\n";
		}	
		else
		{
			cout<<"\n\n\n Triangolo scaleno\n";
		}

	}
	("PAUSE");
}
	
