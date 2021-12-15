# cplus2_study.a.bit.functions
practicing a bit of c++ functions


#include <iostream>
using namespace std;

void info(string name,string place,int age);

int main()
{
   info("Iren","CDOC",18);

    return 0;
}

void info(string name,string place,int age){
     cout<<" Hello "<<name<<" you live in "<<place<<" at the age of "<<age<<endl;
}
  
  output:
  
  Hello Iren you live in CDOC at the age of 18
