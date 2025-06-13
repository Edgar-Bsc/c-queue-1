#include<iostream>
#include <queue>
using namespace std;

int main(){
queue<string>cars;
cars.push("VOLVO");
cars.push("BMW");
cars.push("FORD");
cars.push("MAZDA");

cout<<cars.front()<<"\n";
cout<<cars.back()<<"\n";
return0;
}

