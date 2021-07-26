#include <iostream>
#include <cmath>
#include <iomanip>

using namespace std;

struct point{
    int x;
    int y;
    int z;
};
double disp(point , point);
double disar(point arr[]);
point addar(point arr[]);
point add(point , point);
double mag(point pt);
int main()
{
    point pt1,pt2;
    cout<<"Enter The Coordinate of The First Point: \n";
    cin>>pt1.x>>pt1.y>>pt1.z;
    cout<<"Enter The Coordinate of The Second Point: \n";
    cin>>pt2.x>>pt2.y>>pt2.z;
    point arra[2];
   arra[0]=pt1;
   arra[1]=pt2;
cout<<"The Addition of The Two Points is " <<add(pt1,pt2).x<<"i"<<showpos<<add(pt1,pt2).y<<"j"<<add(pt1,pt2).z<<"k\n";
   cout<<"The Magnitude of The First Point is "<<noshowpos<<mag(pt1)<<endl;
   cout<<"The Magnitude of The Second Point is " <<mag(pt2)<<endl;
   cout<<"The Distance Between The Two Points is " <<disp(pt1,pt2)<<endl;
   cout<<"The Addition of The Two Points Using Array is " <<addar(arra).x<<"i"<<showpos<<addar(arra).y<<"j"<<addar(arra).z<<"k\n";
   cout<<"The Distance Between The Two Points Using Array is "<<noshowpos<<disar(arra);
 
    return 0;
}
double disp(point pt, point pt1)
{
    double disp;
    disp=sqrt((pt.x-pt1.x)*(pt.x-pt1.x) + (pt.y-pt1.y)*(pt.y-pt1.y) + (pt.z-pt1.z)*(pt.z-pt1.z) );
    return disp;
}



point add(point pt, point pt1)
{
   point sum;
   sum.x=pt.x + pt1.x;
   sum.y=pt.y + pt1.y;
   sum.z=pt.z + pt1.z;
   return sum; 
}
double mag(point pt)
{
   double mag;
   mag=sqrt((pt.x)*(pt.x) + (pt.y)*(pt.y) + (pt.z)*(pt.z));
   return mag;
}
double disar(point arr[])
{
    double disp;
   disp=sqrt((arr[0].x-arr[1].x)*(arr[0].x-arr[1].x) + (arr[0].y-arr[1].y)*(arr[0].y-arr[1].y) + (arr[0].z-arr[1].z)*(arr[0].z-arr[1].z) );
    return disp;
}
point addar(point arr[])
{
    point sum;
    sum.x=arr[0].x + arr[1].x;
    sum.y=arr[0].y + arr[1].y;
    sum.z=arr[0].z + arr[1].z;
    return sum;
}
