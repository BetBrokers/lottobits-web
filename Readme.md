![logo](https://avatars1.githubusercontent.com/u/44135538?s=460&v=4)

# Projeto em andamento

### Sistema de banca de jogo do bicho com pagamento em criptomoedas para  rede deep web, baseada em sorteio universal na blockchain.

A Lottobits foi iniciada com o intuito de desenvolvimento para sistemas de loterias e banca de jogo do bicho usando a anonimidade com distribui��o do c�digo do pod para outras redes e desenvolvedores da deep web seguindo o padr�o universal de sorteios e dos pr�mios, independente da banca
A Banca Lottobits n�o � respons�vel pelas bancas que usam software Lottobits, por�m, deve-se ressaltar que todos podem baixar, estudar, contribuir, distribuir e instalar seu pr�prio pod web Lottobits na rede TOR por sua pr�pria conta e risco sobre as responsabilidades vigentes das premia��es de cada banca para cada vencedor.

# 
# Softwares usados para o desenvolvimento da Lottobits

- Php 7.1
- Mysql 5.7
- Tor Project
- Apache 2.4
- Zend Framework 3.0.3-dev+
- Blockchain.com API

# Como funciona o sorteio por blockchain

H� um consenso sobre o protocolo com o qual n�o pode ser alterado sob interven��o humana, pois o sistema de criptomoedas processa atrav�s de dados criptogr�ficos, hashs que comp�em a ordem dos blocos que decidem o saldo de cada carteira, portanto, � indiscut�vel que os resultados dos sorteios sejam alterados. Para saber mais entre em <a link="https://pt.wikipedia.org/wiki/Bitcoin">Como funciona o bitcoin</a>.

Simplesmente a cada 10 ou 15 minutos um novo bloco � gerado, ent�o, a extra��o � feita da seguinte forma:
-  Todos os n�meros do bloco s�o separados das letras
-  Depois s�o invertidos de tr�s para frente
-  S�o cotados 20 n�meros uma milhar de 4 n�meros para cada pr�mio
   
Exemplo:
    
    000000004ebadb55ee9096c9a2f8880e09da59c0d68b1c228da88e48844a1485

Para saber o resultado dos pr�mios deste bloco, o sistema inverte os caracteres de tr�s para frente, como mostrado abaixo

    5841a44884e88ad822c1b86d0c95ad90e0888f2a9c6909ee55dbabe400000000
   
Depois tira todas as letras deixando apenas os n�meros
  
     5841448848882218609590088829690955400000000
   
Logo em seguida separa os 5 pr�mios com os primeiros n�meros, descartando o restante

     5841
     4488
     4888
     2218
     6095
     
     //90088829690955400000000
     
Esse � o padr�o seguido por todos, pois a cadeia de blocos n�o pode ser alterada.

# Como jogar

<p>Existem v&aacute;rios tipos e modalidades de jogos, Dentre eles est&atilde;o:</p>
   <p>Apostas Simples</p>
   
   <p>Grupos</p>
   <p>Voc� escolhe um grupo (bicho) e se um dos n�meros que fazem parte desse grupo sai na dezena do primeiro pr�mio dos resultados (chamado "cabe�a"), voc� ganha 18 vezes o valor que voc� apostou
   � a modalidade mais simples de aposta, com mais altas probabilidades de acerto e, por tanto, com ganhos menores.</p>
   
   <p>Dezena</p>
   <p>Pagamento da aposta: 60:1
   Voc� escolhe uma dezena qualquer (n�mero de dois d�gitos), e se ela cair na dezena do primeiro pr�mio, voc� ganha 60 vezes o valor da sua aposta!</p>

   <p>Centena Seca</p>
   <p>Pagamento da aposta: 600:1
   Voc� escolhe agora uma centena qualquer (n�mero de tr�s d�gitos), e se ela cair na centena do primeiro pr�mio, voc� ganha 600 vezes o valor da sua aposta.
    
   Ex: Quem apostou 0.0909 bitcoins na centena 209 no sorteio de 17/05, ganhou 54 bitcoins!</p>
    
   <p>Milhar Seca</p>
   <p>Pagamento da aposta: 4000:1.
   A mesma l�gica da Dezena e da Centena Seca. Voc� aposta em um n�mero de 4 d�gitos, um milhar, e se esse milhar cair no primeiro pr�mio do sorteio em que voc� apostou, voc� ganha 4000 vezes o valor da sua aposta!</p>

   <p>Cercados</p>
   
   <p>Do 1� ao 5�</p>
   <p>Pagamento da aposta: 1/5 do valor da aposta simples.
   Todas as apostas na Cabe�a podem ser �cercadas do 1� ao 5��, o que significa que voc� ganha se o seu bicho, dezena, centena ou milhar (dependendo do que voc� decidiu apostar), aparecem em um dos 5 primeiros pr�mios. Apesar de as chances de se ganhar assim s�o bem maiores, o pr�mio para essa op��o � menor: ser� igual ao pr�mio da aposta simples, mas dividido por 5.</p>

   <p>Duques</p>
   
   <p>Duques de Dezena</p>
   <p>Pagamento da Aposta: 300:1.
   Voc� aposta em duas dezenas, e se as duas sa�rem entre os cinco primeiros pr�mios, voc� ganha 300 vezes o valor da aposta.

   Exemplo

   Quem apostou 0.0002 bitcoins nas dezenas 53 e 59 no sorteio de 17/05, ganhou 0.06 bitcoins.</p>

   <p>Duque (ou dupla) de Grupo</p>
   <p>Pagamento da aposta: 18,75:1.
   Escolhe-se dois grupos (bichos) e voc� ganha se pelo menos um n�mero de cada grupo aparecer na dezena de um dos cinco primeiros pr�mios. Ou seja, de 5 bichos, voc� tem que acertar 2.</p>
   
   
   <p>Terno</p>
   Joga-se com 3 grupos/dezenas, aparecendo entre os 5 primeiros pr�mios.

   <p>Ternos de Grupo</p>
   <p>Pagamento da Aposta: 130:1.
   Voc� aposta em 3 grupos, e se os tr�s sa�rem nos cinco primeiros pr�mios (ou seja, de 5 grupos, voc� acerta 3), voc� ganha 130 vezes o valor apostado.

   Exemplo

   Quem apostou 40.000 satoshis no Terno de Grupo Vaca , Macaco e Jacar� , ganhou 0.52 bitcoins.

   N�meros 97 a 00: grupo Vaca N�meros 65 a 68: grupo Macaco N�meros 57a 60: grupo Jacar�</p>
   
   <p>Ternos de Dezena</p>
   <p>Pagamento da Aposta: 3000:1.
   Voc� aposta em 3 dezenas, e se as tr�s saem entre os cinco primeiros pr�mios (ou seja, de 5 dezenas, voc� acerta 3), voc� ganha 3000 vezes o valor apostado.

   Exemplo

   Quem apostou 5000 satoshis num Terno de Dezena, com o 68, 97 e 09 ganhou 0.15 bitcoins</p>
   
# Como eu recebo meu pr�mio?

Ap�s voc� ganhar, v� na se��o reinvindicar pr�mio, e la informe o seu id do jogo e hash tx da transa��o bitcoin do seu jogo, ap�s isso, seu pedido ser� registrado e o seu endere�o ser� mostrado para outros apostadores at� se completado os ganhos do seu pr�mio totalmente.

# Como instalar o pod no meu servidor 

A Lottobits foi desenvolvida para ser distribu�da e descentralizada por toda a deep web em muitos servidores espalhados.
Este website est� divulgando a plataforma para todos conhecerem, ent�o, voc� pode baixar e hospedar o seu pr�prio pod da plataforma Lottobits em seu computador.

# Contatos

Entre em contato com o grupo no telegram http://t.me/lottobits