# include <iostream>
 using namespace std;
 int main ()  
 {
     int marks ;
     float income,  percentage;
     cout <<"Enter marks (out of 100) ";
     cin >>marks;
     cout <<"Enter the family income";
     cin >> income;
     cout <<"Enter attendece percentage";
     cin >> percentage;
     if (marks >=85 )
     if (percentage >=80)
    { 
     cout <<"Full scholarship";
    }
     else if (marks >= 70)
     {
         cout <<"partial scholarship";
     }
     else 
     {
              cout <<" Not scholarship";
     }
 }