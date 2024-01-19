# Rock, paper and scissor

#include <iostream>
#include <time.h>
#include <stdlib.h>
#include <string.h>
using namespace std;

int main(){
    srand(time(NULL));
    
    int userChoice;
    for (int i = 0; i=1; i++)
    {
    int computerChoice = (rand()%3);
    cout<<"Enter your choice(0 for paper, 1 for rock and 2 for scissors)"<<endl;
    cin>>userChoice;
    if (computerChoice==0)
    {
        cout<<"Computer choses paper"<<endl;
    }
    else if (computerChoice==1)
    {
        cout<<"Computer choses rock"<<endl;
    }
    else
    cout<<"Computer choses scissors"<<endl;
    
    if (userChoice==computerChoice)
    {
        cout<<"-->It's a tie!"<<endl;
    }
    else if ((userChoice==0 && computerChoice==1) || (userChoice==1 && computerChoice==2) || (userChoice==2 && computerChoice==0))
        {
            cout<<"-->Yippee!, You win"<<endl;
        }
        else
            cout<<"-->Computer wins"<<endl;

    int option;
    cout<<"Press 1 to play again and 2 to exit"<<endl;
    cin>>option;
    if (option==1)
    continue;
    else
    break;
    
    }
    return 0;
}
