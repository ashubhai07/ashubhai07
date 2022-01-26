#include<time.h>
#include<iostream.h>
#include<conio.h>
int main()
{
time_t syst;
syst=time(NULL);
cout<<(ctime(&syst));
return 0;
}
