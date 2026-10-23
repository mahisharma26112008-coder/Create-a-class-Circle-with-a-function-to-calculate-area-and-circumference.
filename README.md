# Create-a-class-Circle-with-a-function-to-calculate-area-and-circumference.

#include<iostream>
  using namespace std;
 class circle{
     public:
     int radius;

     void area(){
     cout<<"area "<<3.14*radius*radius<<"\n";
 }
     void circumstance(){
         cout<<"perameter "<<2*3.14*radius;
     }
 };
int main(){
   circle c1;
    cout<<"enter  the value of radius";
    cin>>c1.radius;
    c1.area();
    c1.circumstance();

    return 0;
}
