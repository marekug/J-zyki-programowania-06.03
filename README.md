# J-zyki-programowania-06.03, Zadania w c z wykładu.

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
