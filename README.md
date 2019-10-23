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


///////////// Atividade valendo 4 pontos////////////


void main() {
 MeuBanco clt = new MeuBanco(677,'thiago',500);
 clt.criarconta();
 clt.deposito(50);
 clt.saque(30);
 clt.transferencia(677, 231, 250);
  ////////////////
 double valorsaldo = clt.saldoatual();
 print('Saldo atual: $valorsaldo');
  
}

///////////////
class MeuBanco{
  
  int numeroconta;
  String nome;
  double saldoc;
  
  MeuBanco(this.numeroconta, this.nome, this.saldoc);
  //////////
   void criarconta () {
     print ('Nome:$nome');
     print ('Númerodaconta: $numeroconta');
   }
  /////////////
  void deposito (double valor) {
    print('Depositovalor: $valor');
    saldoc = saldoc + valor;
    print('Saldodaconta: $saldoc');
  }
  /////////////
  void saque (double valorsaq) {
    print ('Saquede: $valorsaq');
    saldoc = saldoc - valorsaq;
    print('Saldodaconta: $saldoc');
    
  }
  ///////////
  void transferencia (int x, int y, double rr) {
    print ('Conta$x ->$y para a conta $y');
    saldoc = saldoc - rr;
  }
  double saldoatual () => this.saldoc;
}


