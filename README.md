#include<stdio.h>


/// @brief 
 int main(){

  //variaveis

  char nome[50];
  int num;
  char matri[20];
  char endereco[40];
  char curso[50];
  int periodo;
  char disciplina[100];
  float mensalidades;


  printf("Nome: \n");
  fgets(nome,50, stdin);


  printf("idade: \n");
  scanf("%d", &num);
  fflush(stdin);

  printf("Matricula: \n");
  fgets(matri,15,stdin);


  printf("Endereco: \n");
  fgets(endereco,40,stdin);

  printf("Curso: \n");
  fgets(curso,50,stdin);

  printf("Periodo: \n");
  scanf("%d", &periodo);
  fflush(stdin);

  printf("Disciplina: \n");
  fgets(disciplina,100,stdin);

  printf("Mensalidades: \n");
  scanf("%f", &mensalidades);


  //mostrar os dados
  
  printf("\n SEUS DADOS \n");
  printf("Nome: %s\n",nome);
  printf("Idade: %d\n", num);
  printf("Matricula: %s\n",matri);
  printf("Endereco:  %s\n", endereco);
  printf("Curso: %s\n", curso);
  printf("Periodo: %d\n", periodo);
  printf("Disciplina: %s\n", disciplina);
  printf("Mensalidade: %d\n", mensalidades);
 return  0;
}
