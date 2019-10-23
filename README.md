# Atividadeavaliativa2pontos
#atividade avaliativa valendo 2 pontos.


 ///////////////////////Questão 01////////////////////////
 
1. Resposta  Opção (D).
////////////////////////////////////////////////
2. Resposta Letra a).

   void main(){
  int a = 2; 
  int b = 2;
  String c = 'numero'; 
  
 print('$a , $b , $c'); 
}
/////////////////////////////////////////
2.  Resposta Letra b).

main(){
  
n();
  
}
void n(){
  for(int a=1;a<11;a++){
    print('$a');
  }
}
//////////////////////////////////////
2.  Resposta Letra c).
 main() {
  n(50);
}

void n(int b) {
  for (int a = 1; a <= b; a++) {
    print('$a');
  }
}

////////////////////////////////////////
2.  Resposta Letra d).
void main() {
  n(5);
}
void n(int a) {
  int q = 0;
  for (int b = 1; b <= a; b++) {
    q = q + b;
  }
  print('quantidade = $q');
}
/////////////////////////////////////
2.  Resposta Letra e).

void main(){
  SmartTv Smart = SmartTv('HD2','Philco',3251,52);
  Smart.ligar();
  Smart.desligar();

  
}
class Aparelhos{
  String nome;
  String marca;
  int num_serie;
  int volume;
  
  void ligar(){
    print('Seu aparelho $nome ligou!');
  }
  
  void desligar(){
    print('Seu aparelho $nome desligou!');
  }
  

  
  
}

class SmartTv extends Aparelhos{
  SmartTv(String nome, String marca, int num_serie, int volume){
    this.nome = nome;
    this.marca=marca;
    this.num_serie=num_serie;
    this.volume=volume;  
  }  
}



////////////////////////////////////////////////////////////////////////////////////////
///////////////////////////////////////////////THE END////////////////////////////////////


///////////// atividade valendo 4 pontos////////////




