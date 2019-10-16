#include <iostream>
using namespace std;
#define SCND_TO_HOUR 3600
#define SCND_TO_MINUTE 60
int main(){
    int sec1,sec,min=0,hour=0;
    cout<<"Input the total time in seconds: "<<endl;
    cin>>sec;
    sec1=sec;
    while (sec>3599){
        sec-=SCND_TO_HOUR;
        hour++;
    }
    while (sec>59){
        sec-=SCND_TO_MINUTE;
        min++;
    }
    cout<<sec1<<" seconds are equal to "<<hour<<" hours, "<<min<<" minutes and "<<sec<<" seconds.";
    return 0;
}
