# FLL_Cargo_Connect_Capitech 
Análise dos Códigos utilizados para realizar o Desafio da Mesa da temporada Cargo Connect

# My Blocks

* Mover Direção:
 
  Este my block foi feito para que os trajetos retilíneos fossem realizados com máxima precisão. Isso pois, em algumas missões, precisamos que o robô esteja exatamente em determinado local, assim aumentando as chances de realizar a tarefa.
  
  O bloco: 
  
  A interface dele conta com dois parâmetros, a velocidade e a distância, ambos muitos intuitivos, onde um idica a velocidade e a distância que o robô deve alcançar para realizar a tearefa.
  
  No começo do "my block", temos um bloco que define a posição "grau 0", que será tomada como referência pelo sensor de giro.
  
  Logo após, pelo Principio da Tricotomia, vemos 3 situações em que o robô pode estar em relação a posição referêncial:
  
  I) Maior que Zero - nessa situação o robô está indo, curvilinemente, para o sentido horário. Assim fazemos a diminuição da velocidade do motor esquerdo; 
  
  II) Igual que Zero - nessa situação o robô esta em seu caminho certo, então sua velocidade é a mesma em ambos motores, essa é a velocidade principal quje foi definida em um dos parâmetros;
  
  III) Menor que Zero - nessa situação o robô está indo, curvilinemente, para o sentido anti-horário. Assim fazemos a diminuição da velocidade do motor direito.
  
  Isso ira se repetir até o robô ompletar o percurso programado.

* Alinha na Linha:

 Este my block nos proporciona á realizar um alinhamento nas linhas guias por meio dos sensores de cor.


# Runs
