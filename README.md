#include<stdio.h>
int main(){

    int n,t,i,temp;float rs;char name[12],movie;
    
    char id,date;
    printf("~WELCOME IN OUR OFFICIAL PAGE~\n\n\n");
    printf("Printing the name of the movies:\n");
    printf("1.Animal \n2.Hi Nanna\n3.MAD\n\n\n");
    printf("Choose the movie:\n");
    
    scanf("%d",&id);
    temp=id;
    
    if(id==1)
    
    {
        printf("Entering into the Animal...........\n");}
    else if(id==2){
        printf("Entering into the Hi Nanna...........\n");     
    
    }
    else if(id==3){
        printf("Entering into the MAD...........\n");}
        else{
            printf("Database error.....\n Please Enter write Digits");
            return 0;
            
        }
        printf("You Entering into the Movie Ticket Booking Section\n\n\n");
        printf("The amount of movie is 150 Rs.per audience\n");
        printf("Number of Audience\n");
        scanf("%d",&n);
        n=n-1;
        if (n==1){
            printf("Enter the name of the Audience\n");
            scanf("%s",&name[n]);
            
        }
        else
        {
            printf("Enter the names of the Audiences\n");
      for(i=0;i<=n;i++){
    
      scanf("%s",&name[n]);}
            
        }
        printf("In which date you want to see the movie_:12:2023\n");
        scanf("%d",&date);
        printf("Choose the time\n 1.10:30\n 2.1:30\n 3.3:30\n 4.7:00\n\n\n");
        scanf("%d",&t);
        if(t==1){
            printf("Your time is:10:30\n");
            
        }
        else if(t==2){
            printf("Your time is:1:30\n");
            
        }
        else if(t==3){
            printf("Your time is:3:30\n");
            
        }
        else{
            printf("Your time is:7:00\n");
            
        }
        printf("Printing all the details of the tickets....\n");
        puts(name);
        if(temp==1){
            printf("Movie name : Animal\n");
            
        }
        else if(temp==2){
            printf("Movie name : Hi Nanna\n");
            
        }
        else if(temp==3){
            printf("Movie name : MAD\n");
            
        }
        else{
            printf("Database problem\n");

 }
  printf("Date:%d:12:2023\n",date);
 rs=(1 + n)*150;
 printf("Amount of Rs:%f\n",rs);
 if(t==1){
     printf("Time is:10:30\n");
     
 }
 
 else if(t==2){
     printf("Time is:1:30\n");
     
 }
 else if(t==3){
     printf("Time is:3:30\n");
     
 }
 else{
     printf("Time is:7:00\n\n\n");
     
 }
 printf("~Thanking you for entering into the server\n");
 return 0;
    
}
