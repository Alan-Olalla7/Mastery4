# Mastery4echo # Mastery4 >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/samanthariverac/Mastery4.git
git push -u origin master
#include <iostream>
using namespace std;
int x,y,s,d,p,dv,r;
int main () {
  cout<<"Enter a number:";
  cin>> x;
  cout<<"Enter another number:";
  cin>> y;
  s=x+y; cout<<"The sum of the numbers is:"<< s << endl;
  d=x-y; cout<<"The difference of the numbers is:"<< d << endl;
  p=x*y; cout<<"The product of the numbers is:"<< p << endl;
  dv=x/y; cout<<"The division of the numbers is:"<< dv << endl;
  r=x-(y*dv); cout<<"The remainder of the division of the numbers is:"<< r << endl;
  return 0;
}
