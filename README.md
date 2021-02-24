#// Area-of-rectangle-by-func
//this will show that how to find area of rectangle by using OOP`s concepr of c++

#include<iostream>
using namespace std;
class rectangle
{
private:
int length;
int breadth;
public:
int area()
{
   return length*breadth;
}
};
int main()
rectangle r;//here we are creating an object r1 of the class rectangle 
r.length=10;
r.breadth=5;
cout<<"The area of the rectangle is"<<r.area()<<endl;
return 0;
}
