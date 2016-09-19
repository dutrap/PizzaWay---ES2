
Alunos:   Daniel Melo 	        RA: 1840481513006
   	  Gabriel Hirakawa 	RA: 1840481513013
	  Karina Kaori Tanaka   RA: 1840481512020
	  Vin�cius Dutra	RA: 1840481513041


Projeto de Engenharia de Software II


PizzaWay Delivery 

Para o estudo de neg�cio buscamos analisar como � o ambiente em uma pizzaria que trabalha com o sistema de delivery e como � realizado o atendimento.
Atrav�s de nossa pesquisa constatamos que nesse tipo de atendimento existem constantes reclama��es dos clientes em rela��o � demora na entrega e falta de informa��es sobre o pedido.
Muitas vezes o tempo estimado pela pizzaria passa longe do tempo total real que o cliente precisa esperar at� que a entrega seja conclu�da, e nesse per�odo de espera o cliente se sente no escuro, n�o sabendo se sua pizza j� est� pronta, se j� saiu para entrega ou j� est� pr�xima ao destino, sendo necess�rio ligar novamente para a pizzaria, onde nem sempre o cliente consegue obter as respostas que deseja sobre o seu pedido. 

A PizzaWay Delivery � um sistema de gerenciamento de entregas de pizzas que possibilita que o cliente acompanhe o motoboy atrav�s de GPS.

O cliente ter� todas as informa��es e localiza��o do seu pedido em tempo real e o  tempo (estimativa) em que ele receber� a entrega do produto.


Trabalhadores de Neg�cio 
Pizzaiolo
Especializado em fazer pizzas. Pode utilizar o sistema.
Atendente
Profissional  informatizada. Utilizar� o sistema diretamente.
Entregador de Pizza
Habilitado para realizar as entregas de pizzas. 
Utilizar� diretamente o sistema.
Gerente do Neg�cio
Pessoa habilitada para comandar todo o neg�cio.
Entende do neg�cio e de todo seu funcionamento.
Conhece e utilizar� o sistema ocasionalmente.
Estoquista
Profissional organizada. N�o utilizar� o sistema de GPS, mas � habilitada para utilizar sistemas de controle de estoque.
Atores de Neg�cio 
 Jovens e Adultos. Fam�lias. Grupo de amigos. Fornecedores. 

Regras de Neg�cio:

RN � 01 Pedido: Somente poder�o fazer o pedido de entrega os clientes cadastrados. 

RN - 02 Valida��o de dados pessoais: para efetuar o cadastro, as pessoas devem possuir endere�o e telefone v�lido e atualizado.

RN � 03 Cancelamento de pedido: Os pedidos podem ser cancelados ou alterados ap�s 30 minutos, feito a encomenda do produto.

RN-04 Quantidade de Entrega por viagem: Cada motoboy poder� levar no m�ximo 5 pizzas por viagem e 2 bebidas.

RN � 05 Descontos: O cliente que comprar mais de 2 pizzas obter� um desconto.

RN � 06 Atualiza��o de dados: O cliente que n�o realizar um pedido durante 6 meses, quando solicitar um novo pedido,  deve informar  os dados de endere�o e telefone para uma  atualiza��o de dados.

RN � 07 Atraso: O cliente que n�o receber sua pizza at� 30min depois do tempo estimado de entrega, tem o direito ao cancelamento do pedido.


Requisitos
Requisitos Funcionais
RF-01 Cadastro de clientes: O sistema deve ser capaz de efetuar o cadastro, exclus�o, altera��o e consulta de clientes.
RF-02 Controle de pedidos: O sistema deve ser capaz de fazer o controle do fluxo de todos os pedidos.
RF-03 Listagem de pedidos: O sistema deve ser capaz de produzir uma listagem dos pedidos, indicando a ordem de prioridade de pedidos.
RF-04- c�lculo de rota(tempo estimado para chegar no local)- sistema deve ser capaz de calcular o tempo da rota desde a pizzaria at� o endere�o de entrega
RF-05 Cancelamento de pedidos e sabores mais procurados: O sistema deve ser capaz de identificar quais s�o os sabores mais procurados/vendidos, e fazer cancelamento de pedido, caso necess�rio.
RF-06 Disponibilidade de relat�rio do pedido:
O relat�rio de acompanhamento ser� disponibilizado assim que for solicitado o pedido(relat�rio da situa��o do pedido), a mesma din�mica se aplica ao relat�rio da rota.
RF-07 Relat�rio mensal e di�rio do fluxo de vendas: 
O sistema deve ser capaz de produzir relat�rios sobre o fluxo di�rio e mensal das vendas.



Requisitos N�o Funcionais
RNF-01 Interface Interativa: O sistema deve apresentar uma interface agrad�vel e intuitiva ao usu�rio;
RNF-02 F�cil de Usar:
O sistema dever� ser de f�cil utiliza��o.
RNF-03 O sistema dever� armazenar os dados de acesso: 
O aplicativo dever� armazenar os dados de acesso do usu�rio bem como seu hist�rico de compras.
RNF-04 Login de Usu�rio: O Login deve ser composto pelo nome completo do usu�rio e a senha composta por no m�nimo 6 caracteres (entre n�meros e letras apenas);
RNF-05 Sistema para rodar o aplicativo: O aplicativo dever� rodar nos seguintes sistemas:
- Android
-ios



