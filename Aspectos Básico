1° Questão
#include <stdio.h>

int main() {
    int segundos, h, m, s, resto;

    printf("Digite uma quantidade de segundos: ");
    scanf("%d", &segundos);
    
    h = segundos / 3600;
    resto = segundos % 3600;
    m = resto / 60;
    s = resto % 60;
    printf("%d Hora(s) %d Minuto(s) %d Segundo(s)\n", h, m, s);

    return 0;
}

2° Questão
#include <stdio.h>


int main()

{

   float a,b,c,m;

   printf("Digite 3 valores \n");

   scanf("%2f",&a);

   scanf("%2f",&b);

   scanf("%2f",&c);

   m = (a+b+c)/3;

   printf("O valor da media eh:%0.2f", m);


   return 0;

}

3° Questão

#include <stdio.h>
#include <stdlib.h>
#include <math.h>


void main()
{
    float Altura,Vinicial, Angulo,Gravidade = 9.81, Seno, Ang_rad, Alcance;

    printf("Digite a Altura:");
    scanf("%f", &Altura);
    printf("Digite a Velocidade inicial:");
    scanf("%f", &Vinicial);
    printf("Digite o angulo:");
    scanf("%f", &Angulo);

    Ang_rad = (3.14*(Angulo*2))/180;
    Seno = sin(Ang_rad);

    Alcance = ((Vinicial*Vinicial)*(2*Seno))/Gravidade;

    printf("O Alcance foi de %.2f", Alcance);


}
