![logo](https://avatars1.githubusercontent.com/u/44135538?s=460&v=4)

# Projeto em andamento

### Sistema de banca de jogo do bicho com pagamento em criptomoedas para  rede deep web, baseada em sorteio universal na blockchain.

A Lottobits foi iniciada com o intuito de desenvolvimento para sistemas de loterias e banca de jogo do bicho usando a anonimidade com distribuição do código do pod para outras redes e desenvolvedores da deep web seguindo o padrão universal de sorteios e dos prêmios, independente da banca
A Banca Lottobits não é responsável pelas bancas que usam software Lottobits, porém, deve-se ressaltar que todos podem baixar, estudar, contribuir, distribuir e instalar seu próprio pod web Lottobits na rede TOR por sua própria conta e risco sobre as responsabilidades vigentes das premiações de cada banca para cada vencedor.

# 
# Softwares usados para o desenvolvimento da Lottobits

- Php 7.1
- Mysql 5.7
- Tor Project
- Apache 2.4
- Zend Framework 3.0.3-dev+
- Blockchain.com API

# Como funciona o sorteio por blockchain

Há um consenso sobre o protocolo com o qual não pode ser alterado sob intervenção humana, pois o sistema de criptomoedas processa através de dados criptográficos, hashs que compôem a ordem dos blocos que decidem o saldo de cada carteira, portanto, é indiscutível que os resultados dos sorteios sejam alterados. Para saber mais entre em <a link="https://pt.wikipedia.org/wiki/Bitcoin">Como funciona o bitcoin</a>.

Simplesmente a cada 10 ou 15 minutos um novo bloco é gerado, então, a extração é feita da seguinte forma:
-  Todos os números do bloco são separados das letras
-  Depois são invertidos de trás para frente
-  São cotados 20 números uma milhar de 4 números para cada prêmio
   
Exemplo:
    
    000000004ebadb55ee9096c9a2f8880e09da59c0d68b1c228da88e48844a1485

Para saber o resultado dos prêmios deste bloco, o sistema inverte os caracteres de trás para frente, como mostrado abaixo

    5841a44884e88ad822c1b86d0c95ad90e0888f2a9c6909ee55dbabe400000000
   
Depois tira todas as letras deixando apenas os números
  
     5841448848882218609590088829690955400000000
   
Logo em seguida separa os 5 prêmios com os primeiros números, descartando o restante

     5841
     4488
     4888
     2218
     6095
     
     //90088829690955400000000
     
Esse é o padrão seguido por todos, pois a cadeia de blocos não pode ser alterada.

# Como jogar

<p>Existem v&aacute;rios tipos e modalidades de jogos, Dentre eles est&atilde;o:</p>
   <p>Apostas Simples</p>
   
   <p>Grupos</p>
   <p>Você escolhe um grupo (bicho) e se um dos números que fazem parte desse grupo sai na dezena do primeiro prêmio dos resultados (chamado "cabeça"), você ganha 18 vezes o valor que você apostou
   É a modalidade mais simples de aposta, com mais altas probabilidades de acerto e, por tanto, com ganhos menores.</p>
   
   <p>Dezena</p>
   <p>Pagamento da aposta: 60:1
   Você escolhe uma dezena qualquer (número de dois dígitos), e se ela cair na dezena do primeiro prêmio, você ganha 60 vezes o valor da sua aposta!</p>

   <p>Centena Seca</p>
   <p>Pagamento da aposta: 600:1
   Você escolhe agora uma centena qualquer (número de três dígitos), e se ela cair na centena do primeiro prêmio, você ganha 600 vezes o valor da sua aposta.
    
   Ex: Quem apostou 0.0909 bitcoins na centena 209 no sorteio de 17/05, ganhou 54 bitcoins!</p>
    
   <p>Milhar Seca</p>
   <p>Pagamento da aposta: 4000:1.
   A mesma lógica da Dezena e da Centena Seca. Você aposta em um número de 4 dígitos, um milhar, e se esse milhar cair no primeiro prêmio do sorteio em que você apostou, você ganha 4000 vezes o valor da sua aposta!</p>

   <p>Cercados</p>
   
   <p>Do 1º ao 5º</p>
   <p>Pagamento da aposta: 1/5 do valor da aposta simples.
   Todas as apostas na Cabeça podem ser “cercadas do 1º ao 5º”, o que significa que você ganha se o seu bicho, dezena, centena ou milhar (dependendo do que você decidiu apostar), aparecem em um dos 5 primeiros prêmios. Apesar de as chances de se ganhar assim são bem maiores, o prêmio para essa opção é menor: será igual ao prêmio da aposta simples, mas dividido por 5.</p>

   <p>Duques</p>
   
   <p>Duques de Dezena</p>
   <p>Pagamento da Aposta: 300:1.
   Você aposta em duas dezenas, e se as duas saírem entre os cinco primeiros prêmios, você ganha 300 vezes o valor da aposta.

   Exemplo

   Quem apostou 0.0002 bitcoins nas dezenas 53 e 59 no sorteio de 17/05, ganhou 0.06 bitcoins.</p>

   <p>Duque (ou dupla) de Grupo</p>
   <p>Pagamento da aposta: 18,75:1.
   Escolhe-se dois grupos (bichos) e você ganha se pelo menos um número de cada grupo aparecer na dezena de um dos cinco primeiros prêmios. Ou seja, de 5 bichos, você tem que acertar 2.</p>
   
   
   <p>Terno</p>
   Joga-se com 3 grupos/dezenas, aparecendo entre os 5 primeiros prêmios.

   <p>Ternos de Grupo</p>
   <p>Pagamento da Aposta: 130:1.
   Você aposta em 3 grupos, e se os três saírem nos cinco primeiros prêmios (ou seja, de 5 grupos, você acerta 3), você ganha 130 vezes o valor apostado.

   Exemplo

   Quem apostou 40.000 satoshis no Terno de Grupo Vaca , Macaco e Jacaré , ganhou 0.52 bitcoins.

   Números 97 a 00: grupo Vaca Números 65 a 68: grupo Macaco Números 57a 60: grupo Jacaré</p>
   
   <p>Ternos de Dezena</p>
   <p>Pagamento da Aposta: 3000:1.
   Você aposta em 3 dezenas, e se as três saem entre os cinco primeiros prêmios (ou seja, de 5 dezenas, você acerta 3), você ganha 3000 vezes o valor apostado.

   Exemplo

   Quem apostou 5000 satoshis num Terno de Dezena, com o 68, 97 e 09 ganhou 0.15 bitcoins</p>
   
# Como eu recebo meu prêmio?

Após você ganhar, vá na seção reinvindicar prêmio, e la informe o seu id do jogo e hash tx da transação bitcoin do seu jogo, após isso, seu pedido será registrado e o seu endereço será mostrado para outros apostadores até se completado os ganhos do seu prêmio totalmente.

# Como instalar o pod no meu servidor 

A Lottobits foi desenvolvida para ser distribuída e descentralizada por toda a deep web em muitos servidores espalhados.
Este website está divulgando a plataforma para todos conhecerem, então, você pode baixar e hospedar o seu próprio pod da plataforma Lottobits em seu computador.

# Contatos

Entre em contato com o grupo no telegram http://t.me/lottobits