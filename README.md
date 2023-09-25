#include <stdio.h>
#include <stdlib.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
char choose;
	int N,i, datalist;
void ShowMenu() {
		printf("\n1. Hay nhap so nguyen N = ");
		printf("\n2. N! = ");
		printf("\n3. 1+2+...+N = ");
		printf("\n4. So sanh N! voi 1+2+..N");
		printf("\n5. THOAT!!!");
		printf("\n Xin hay chon mot trong 5 phuong an: ");
		scanf("%d", &choose);
}
void input() {
	

	printf("\nHay nhap vao so nguyen N: ");
scanf("%d", &N);
}
void Cacu1() {

	int Multiplication = 1;
			for(i = 1; i<=N;i++){
	Multiplication = Multiplication * i ;
}
printf("\nVay %d! = %d", N, Multiplication);}
void Cacu2() {
	int Sum = 0;
	for(i=0; i<=N;i++){
		Sum = Sum + i;
	}
	printf("\nVay 1+2+3+...+%d = %d", N, Sum);
}

void compare(){
	int Sum = 0;
	for(i=0; i<=N;i++){
		Sum = Sum + i;
	}
int Multiplication = 1;
			for(i = 1; i<=N;i++){
	Multiplication = Multiplication * i ;
}
	if(Sum > Multiplication){
		printf("\nVay 1+2+...+%d > %d!", N,N);
	}else if(Multiplication > Sum){
		printf("\nVay 1+2+...+%d < %d!", N,N);
	};
}
int main(int argc, char *argv[]) {

	do{
		
		ShowMenu();
		scanf("%d", &choose);
		switch(choose){
			case 1:{
			input();

				break;
			}
			case 2:{
					Cacu1()
;};

case 3:{
	Cacu2()
	
	;break;
}
case 4:{
compare()
	;break;
}
case 5:{
printf("\nTHOAT!!!");
	break;
}default:{
printf("\nNHAP SAI!!!");
break;
}

	

				
				
			};
			
		
	;}while(choose != 5);
	return 0;
}
