#include <stdio.h>
int main() {
 int a, b=0,g=10, ch;
 int e[]={1,2,3,4,5};
do{
    int i=0, ch;

    printf("looking for hotel price (bath): ");
    scanf("%d",&a);

if(a <700 ) {
        b==0;
    printf("You can't get any hotel room in this price\n");
    i = 700-a;
    printf("If you add %d ,you can get hotel %d star room \n", i, e[b]);
 }
else if(a>=700 && a<2000){
        b==0;
        e[b]=(b+1);
    printf("You can get %d star hotel\n", e[b]);
    i=2000-a;
    printf("If you add %d ,you can get hotel %d star room\n", i, e[b+1]);
}
else if(a>=2000 && a<3500){
        e[b]=(b+2);
    printf("You can get %d star hotel\n", e[b] );
    i=3500-a;
    printf("If you add %d ,you can get hotel %d star room\n", i, e[+2]);
}
else if(a>=3500 && a<5000){
        b==2;
        e[b]=(b+3);
    printf("You can get %d star hotel\n", e[b]);
    i=5000-a;
    printf("If you add %d ,you can get hotel %d star room\n", i, e[b+3]);
}
else if(a>=5000 && a<9000){
        b==3;
        e[b]=(b+4);

    printf("You can get %d star hotel\n", e[b]);
    i=9000-a;
    printf("If you add %d ,you can get hotel %d star room\n", i, e[b+4]);
}
else if(a>=9000){
        b==4;
        e[b]=(b+5);

    printf("You can get %d star hotel\n", e[b]);
    printf("This is the best thing we can find for u\n");
}
else{
    printf("ERROR\n");
    continue;
}
printf("Press '0' to end this program");
    scanf("%d",&ch);
    if(ch==0){
        break;
    }
}while(1);
}