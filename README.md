## Jezyki-programowania-06.03, Zadania w c z wykładu.

####Podaj liczby cakowite od 0 do 23 za pomoca ptli for, while i do-while.

Petla for.   

```c
#include <stdio.h>
main()

{
	int x;
	
	for(x=0; x<=23; x++)
	
	printf("%d\n",x);
	 
	 getchar();
	 return(0);
}
```
Petla while.
```c
#include <stdio.h>
main()

{
	int x;
	x=0;
	while(x<=23){
	
	printf("%d\n",x);
	x=x+1;
}
	  getchar();
	 return(0);
}
```
Petla do-while.

```c
#include <stdio.h>
main()

{
	int x;
	x=0;
	
	do{
	   printf("%d\n",x);
	        x=x+1;
		}while (x<=23);
		
	getchar();
	return(0);
}
```

#### Wypisz liczby od -3.5 do 7.5 z krokiem co 0.5 za pomoc petli for w while.

Petla for
```c
#include <stdio.h>
main()

{
	double x;
	
	for(x=-3.5; x<=7.5; x=x+0.5){
	
	
	printf("%f\n",x); 

}
	 getchar();
	 return(0);
}
```
Petla while
```c
#include <stdio.h>
main()

{
	double x;
		x=-3.5;
	while(x<=7.5){
	
	printf("%f\n",x);
	x=x+0.5;
	
	

}
	 getchar();
	 return(0);
}
```
####Wypisz kwadraty i szeciany liczb naturalnych od 1 do liczby podanej przez użytkownika za pomoc petli for, while i do-while.

Petla for. 
```c
#include <stdio.h>
main()

{
	int x, y;
	printf("podaj liczbę:");
	scanf("%d", &y);
	for(x=1; x<=y; x++ ){
	
	
	
	printf("%d\t", x*x );
	printf("%d\n", x*x*x); 
}
	 getchar();
	 return(0);
}
```
Petla while.
```c
#include <stdio.h>
main()

{
	int x, y;
	printf("podaj liczbę:");
	scanf("%d", &y);
	while(x<=y){
	
	
	printf("%d\t", x*x );
	printf("%d\n", x*x*x);
	x=x+1; 
}
	 getchar();
	 return(0);
}
```
Petla do-while.
```c
#include <stdio.h>
main()

{
	int x, y;
	printf("podaj liczbę:");
	scanf("%d", &y);
	do{
	
	printf("%d\t", x*x );
	printf("%d\n", x*x*x);
	x=x+1; 
	}while (x<=y);
	
	 getchar();
	 return(0);
}
```
####Oblicz za pomoca petli for i while sume kwadratów liczb od 3 do 15.

Petla for.
```c
#include <stdio.h>
main()

{
	int x, y;
    y=0;
	for(x=3; x<=15; x++){
	
	printf("%d\t", x*x );
	y=y+x*x;
	
	printf("%d\n", y); 
}
	 getchar();
	 return(0);
}
```
Petla while.
```c
#include <stdio.h>
main()

{
	int x, y;
    y=0;
    x=3;

	while(x<=15){
		
	printf("%d\t", x*x );
	y=y+x*x;
	x=x+1;
	printf("%d\n", y); 
}
	 getchar();
	 return(0);
}
```

####Wypisz sinusy i cosinusy katów 0 - 180 stopni z krokiem co 30 stopni za pomoca petli for.

```c
#include <stdio.h>
#include <math.h>
main()

{
	double x;
    
    
	for(x=0; x<=180; x=x+30 ){

	printf("%f\t", sin(x*M_PI/180));	
    printf("%f\n", cos(x*M_PI/180));
}
	 getchar();
	 return(0);
}
```

#### Napisz program wczytujacy n liczb zmiennoprzecinkowych i wyswietl ich sume oraz srednia arytmetyczna. 

```c
#include <stdio.h>
main()
{
	double x, y, t; // y to suma, t średnia 
    int n, p;
    y=0;
    printf("podaj ilosc liczb:");
	scanf("%d", &n);
    for(p=1; p<=n; p++){
    
	printf("podaj liczbe:\t");
    scanf("%lf", &x); 
    y=y+x;
}
	printf("suma %lf\t\n", y);
  

     t=y/n;
     printf( "srednia %lf\n", t);
	 getchar();
	 return(0);
}
```
7

```c
#include <stdio.h>
main()

{
	char znak;
	for (znak='a'; znak<='k'; znak++){
		printf("dla %c w systemie dziesiętnym %d, w systemie szesnastkowym %x\n", znak, znak, znak);
	}
return(0);

}
```

8
```c
#include <stdio.h>
main()

{
char c;	
	while((c=getchar())!='x')
	putchar(c);
	
	return(0);

}

```
