include <map>
#include <iostream>
#include <iterator>
using namespace std; 
int main () 
{
    map <int,int> squarenumbers ; // creating a map  
    int i = 12; //initializing i as 12 
    while(i!= 0)// it is not going to stop until i be 0 
        {   i--; // decreasing one by one
            squarenumbers.insert(pair<int, int>(i,i*i)); //inserting keys and values for squarenumbers map that we created in line 7
        }
    // or
    /*for (int i = 2; i< 11; i++)
        {
            squarenumbers.insert(pair<int, int>(i,i*i));
        }
    *//
    //you can use either of those loops to create the keys and values      
    cout<<"\t \t The map is here"<< endl; // A simple cout line with the title 
    map <int, int>:: iterator itr; //creating an iterator, which gives us handy tools like the line below this one(22) 
    for (itr = squarenumbers.begin(); itr != squarenumbers.end(); itr++)//for loop, it is not going to end until it goes from the begining of the map until the end 
        {
            cout<<"\t the key is: "<<itr->first<<"\t the value: "<<itr -> second << endl; //itr - first means key and itr -> second means value
        }
    
    
    return 0; // the driver main function was declared as an int, and we return and integer. It shows that it went trhough the end successfully 
}
