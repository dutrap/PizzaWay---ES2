
Alunos:   Daniel Melo 	        RA: 1840481513006
   	  Gabriel Hirakawa 	RA: 1840481513013
	  Karina Kaori Tanaka   RA: 1840481512020
	  Vinícius Dutra	RA: 1840481513041


Projeto de Engenharia de Software II


PizzaWay Delivery 

Para o estudo de negócio buscamos analisar como é o ambiente em uma pizzaria que trabalha com o sistema de delivery e como é realizado o atendimento.
Através de nossa pesquisa constatamos que nesse tipo de atendimento existem constantes reclamações dos clientes em relação à demora na entrega e falta de informações sobre o pedido.
Muitas vezes o tempo estimado pela pizzaria passa longe do tempo total real que o cliente precisa esperar até que a entrega seja concluída, e nesse período de espera o cliente se sente no escuro, não sabendo se sua pizza já está pronta, se já saiu para entrega ou já está próxima ao destino, sendo necessário ligar novamente para a pizzaria, onde nem sempre o cliente consegue obter as respostas que deseja sobre o seu pedido. 

A PizzaWay Delivery é um sistema de gerenciamento de entregas de pizzas que possibilita que o cliente acompanhe o motoboy através de GPS.

O cliente terá todas as informações e localização do seu pedido em tempo real e o  tempo (estimativa) em que ele receberá a entrega do produto.


Trabalhadores de Negócio 
Pizzaiolo
Especializado em fazer pizzas. Pode utilizar o sistema.
Atendente
Profissional  informatizada. Utilizará o sistema diretamente.
Entregador de Pizza
Habilitado para realizar as entregas de pizzas. 
Utilizará diretamente o sistema.
Gerente do Negócio
Pessoa habilitada para comandar todo o negócio.
Entende do negócio e de todo seu funcionamento.
Conhece e utilizará o sistema ocasionalmente.
Estoquista
Profissional organizada. Não utilizará o sistema de GPS, mas é habilitada para utilizar sistemas de controle de estoque.
Atores de Negócio 
 Jovens e Adultos. Famílias. Grupo de amigos. Fornecedores. 

Regras de Negócio:

RN – 01 Pedido: Somente poderão fazer o pedido de entrega os clientes cadastrados. 

RN - 02 Validação de dados pessoais: para efetuar o cadastro, as pessoas devem possuir endereço e telefone válido e atualizado.

RN – 03 Cancelamento de pedido: Os pedidos podem ser cancelados ou alterados após 30 minutos, feito a encomenda do produto.

RN-04 Quantidade de Entrega por viagem: Cada motoboy poderá levar no máximo 5 pizzas por viagem e 2 bebidas.

RN – 05 Descontos: O cliente que comprar mais de 2 pizzas obterá um desconto.

RN – 06 Atualização de dados: O cliente que não realizar um pedido durante 6 meses, quando solicitar um novo pedido,  deve informar  os dados de endereço e telefone para uma  atualização de dados.

RN – 07 Atraso: O cliente que não receber sua pizza até 30min depois do tempo estimado de entrega, tem o direito ao cancelamento do pedido.


Requisitos
Requisitos Funcionais
RF-01 Cadastro de clientes: O sistema deve ser capaz de efetuar o cadastro, exclusão, alteração e consulta de clientes.
RF-02 Controle de pedidos: O sistema deve ser capaz de fazer o controle do fluxo de todos os pedidos.
RF-03 Listagem de pedidos: O sistema deve ser capaz de produzir uma listagem dos pedidos, indicando a ordem de prioridade de pedidos.
RF-04- cálculo de rota(tempo estimado para chegar no local)- sistema deve ser capaz de calcular o tempo da rota desde a pizzaria até o endereço de entrega
RF-05 Cancelamento de pedidos e sabores mais procurados: O sistema deve ser capaz de identificar quais são os sabores mais procurados/vendidos, e fazer cancelamento de pedido, caso necessário.
RF-06 Disponibilidade de relatório do pedido:
O relatório de acompanhamento será disponibilizado assim que for solicitado o pedido(relatório da situação do pedido), a mesma dinâmica se aplica ao relatório da rota.
RF-07 Relatório mensal e diário do fluxo de vendas: 
O sistema deve ser capaz de produzir relatórios sobre o fluxo diário e mensal das vendas.



Requisitos Não Funcionais
RNF-01 Interface Interativa: O sistema deve apresentar uma interface agradável e intuitiva ao usuário;
RNF-02 Fácil de Usar:
O sistema deverá ser de fácil utilização.
RNF-03 O sistema deverá armazenar os dados de acesso: 
O aplicativo deverá armazenar os dados de acesso do usuário bem como seu histórico de compras.
RNF-04 Login de Usuário: O Login deve ser composto pelo nome completo do usuário e a senha composta por no mínimo 6 caracteres (entre números e letras apenas);
RNF-05 Sistema para rodar o aplicativo: O aplicativo deverá rodar nos seguintes sistemas:
- Android
-ios



