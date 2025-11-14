# JogoSuperTriunfo.C

#include <stdio.h>

int main() {

    // Aqui estou declarando as variaveis das duas cartas
    
    char Estado1[30], Estado2[30], cidade1[30], cidade2[30], codigo1[5], codigo2[5];
    int populacao1, populacao2, turismo1, turismo2;
    float area1, area2, pib1, pib2;

    // Interação e armazenamento da prmeira carta 

    printf("Ola, iremos primeiro cadastrar os dados da primeira carta, certo?\n");
    printf("Digite primeiro o nome do estado da carta1: ");
    scanf(" %29s",Estado1);

     printf("\n"); // espaço no terminal 

    printf("Agora digite o codigo da primeira carta: ");
    scanf("%4s", codigo1);

     printf("\n"); // espaço no terminal 

    printf("Qual e o nome da cidade desse estado?:");
    scanf(" %29s", cidade1);

     printf("\n"); // espaço no terminal 
    
    printf("Agora digite qual e a populacao desse primeiro estado: ");
    scanf("%i", &populacao1);

     printf("\n"); // espaço no terminal 

    printf("Agora digite qual e a area em Km2 desse estado: ");
    scanf("%f", &area1);

     printf("\n"); // espaço no terminal 

    printf("qual e o PIB desse estado?: ");
    scanf("%f", &pib1);
    getchar(); // limpa o buffer do teclado

     printf("\n"); // espaço no terminal 

    printf("E quantos pontos turisticos tem nesse estado?: ");
    scanf("%i", &turismo1);

    // instruindo o usuario para a segunda carta

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 
       printf("\n"); // espaço no terminal 

    printf("Tudo certo, agora que temos os dados da primeira carta vamos para a segunda carta, ok?\n");
    printf("Vamos la!\n");

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 
       printf("\n"); // espaço no terminal 


    // Interação e armazenamento da segunda carta

    printf("Digite agora o nome do estado da carta2: ");
    scanf(" %29s", Estado2);

     printf("\n"); // espaço no terminal 

    printf("Agora digite o codigo da segunda carta: ");
    scanf ("%4s", codigo2);

     printf("\n"); // espaço no terminal 

    printf("Qual e o nome da cidade desse segundo estado?:");
    scanf(" %29s", cidade2);
    
     printf("\n"); // espaço no terminal 

    printf("Agora digite qual e a populacao do segundo estado: ");
    scanf("%i", &populacao2);

     printf("\n"); // espaço no terminal 

    printf("Agora digite qual e a area em Km2 desse segundo estado: ");
    scanf("%f", &area2);

     printf("\n"); // espaço no terminal 

    printf("qual e o PIB desse segundo estado?: ");
    scanf("%f", &pib2);
    getchar(); // limpa o buffer do teclado

     printf("\n"); // espaço no terminal 

    printf("e quantos pontos turisticos tem nesse segundo estado?: ");
    scanf("%i", &turismo2);

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 
       printf("\n"); // espaço no terminal 
    

    //Apresentação das duas cartas para o usuario

    printf("Perfeito, agora vamos ver os dados das duas cartas que voce cadastrou:\n");

    printf("Carta 1: %s \n", Estado1);
    printf("Codigo: %s \n", codigo1);
    printf("cidade: %s \n", cidade1);
    printf("Populacao: %i \n", populacao1);
    printf("Area em Km2: %.2f Km² \n", area1);
    printf("PIB: %.2f bilhoes de reais \n", pib1);
    printf("Pontos Turisticos: %i \n", turismo1);

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 
       printf("\n"); // espaço no terminal 

    printf("Carta 2: %s \n", Estado2);
    printf("Codigo: %s \n", codigo2);
    printf("cidade: %s \n", cidade2);
    printf("Populacao: %i \n", populacao2);
    printf("Area em Km2: %.2f Km² \n", area2);
    printf("PIB: %.2f bilhoes de reais \n", pib2);
    printf("Pontos turisticos: %i \n", turismo2);

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 
       printf("\n"); // espaço no terminal 

    printf ("Agora comeca a guerra entre as cartas, Vamos la!\n");

     printf("\n"); // espaço no terminal 
      printf("\n"); // espaço no terminal 

   printf("====Iniciando guerra====\n");

   //Aqui estou iniando a guerra entre as carta1 e carta2

   printf("%s VS %s !\n", Estado1, Estado2);
 
       printf("\n"); // espaço no terminal
       printf("\n"); // espaço no terminal
       
   printf(" ROUND 1: populacao\n");

       printf("\n"); // espaço no terminal 

   printf("A poulacao de %s e %i e a de %s e %i \n", Estado1, populacao1, Estado2, populacao2);

       if ( populacao1 > populacao2){
         printf("O %s e o ganhador da rodada! \n", Estado1);
       } else {
         printf("O %s e o ganhador da rodada! \n", Estado2 );
       }
       
       printf("\n"); //Espaço no terminal
       printf("\n"); //Espaço no terminal
       printf("\n"); //Espaço no terminal

   printf(" ROUND 2: Area Km2 \n");

      printf("\n"); // espaço no terminal 

   printf("A area km2 de %s e %.2f e a de %s e de %.2f \n", Estado1, area1, Estado2, area2);

   if(area1 > area2){
      printf("O %s e o ganhador da rodada! \n", Estado1);
   } else {
      printf("O %s e o ganhador da rodada! \n", Estado2);
   }

   printf("\n"); // espaço no terminal 
   printf("\n"); //Espaço no terminal

   printf(" ROUND 2: PIB \n");

   printf("\n"); // espaço no terminal 

   printf(" O PIB do estado de %s e de %.2f e o do estado %s e de %.2f sendo asim", Estado1, pib1, Estado2, pib2);

   if(pib1 > pib2) {
      printf("O %s e o ganhador da rodada! \n", Estado1);
   } else {
      printf("O %s e o ganhador da rodada! \n",Estado2);
   }

   printf("\n"); // espaço no terminal 
   printf("\n"); //Espaço no terminal

   printf(" ROUND 3: Pontos Turristicos \n");

   printf("\n"); // espaço no terminal 

   printf("O estado de %s tem %i de pontos turristicos, em quando %s tem %i de pontos turristicos, sendo asim \n", Estado1, turismo1, Estado2, turismo2);

   if( turismo1 > turismo2 ) {
      printf("O estado %s e o vencedor da rodada!", Estado1);
   } else {
      printf("O estado %s e o ganhador da rodada", Estado2);
   }
    return 0;
}
