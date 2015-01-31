# mastery-15-and-16
Here's the code


    #include <iostream> // llama a la librería iostream, para así poder utilizar comandos como cout, etc.
    // Luis Angel Aguilar Carrillo A01225421    
    
    using namespace std;
    
    int main(){
    	
    	int x;
    
    	cout << "Introduce tu edad" << endl; 
    	cin >> x;
    
    	if (x<=12){ 								// Esta es la primera condición, si la condición es verdadera,
    		cout << "Eres muy joven" << endl;		// se correrá lo que esté dentro de ella
    	}
    		else if (x>12 && x<18){					// Esta es la segunda condición, si la primera condición no se cumple,
    												// pasa a la siguiente,y correrá si se cumple 
    			cout << "Eres adolecente" << endl;
    		}
    			else {								// Es la ultima condición, en la que, si no se cumplen ninguna de las anteriores, 
    												// todas las demás opciones que pueden haber, lo correran en esta sección
    				cout << "Eres señor" << endl;
    			}

	return 0;
	}
