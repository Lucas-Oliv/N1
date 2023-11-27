<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Projeto DeliveryX&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Lucas de Oliveira Bertelini


# Descrição do projeto


*&lt;
O "Projeto DeliveryX" representa uma iniciativa de engenharia de software com foco na aprimoração do serviço de entrega da Pizza-Express, uma renomada cadeia de 40 lojas de fast-food e entrega domiciliar. Em resposta ao contexto competitivo atual e às crescentes demandas dos consumidores por entregas mais céleres, este projeto busca desenvolver e implementar um sistema de software de vanguarda. O propósito central é possibilitar à Pizza-Express efetuar a entrega de pizzas aos seus clientes no prazo de 30 minutos ou menos, solidificando assim sua posição de liderança na indústria de fast-food.

A abrangência deste projeto envolve a concepção e implementação de um sistema de pedidos online, permitindo aos clientes efetuar pedidos por meio de uma plataforma digital, com opções de personalização dos itens do menu e processamento seguro de pagamentos. Além disso, o projeto contempla a integração de um sistema de rastreamento em tempo real, que viabiliza a localização das lojas de pizza Pizza-Express mais próximas dos clientes no momento da realização do pedido.

O gerenciamento eficaz dos pedidos é uma peça fundamental deste projeto, com uma abordagem inteligente para a alocação de pedidos às lojas de maneira a otimizar a eficiência das entregas. Uma roteirização inteligente é empregada para determinar as rotas mais eficientes e reduzir o tempo de entrega, almejando alcançar um prazo de 10 a 15 minutos após o pedido.

No que concerne à segurança e confiabilidade, serão implementadas medidas rigorosas para garantir a proteção dos dados dos clientes e a continuidade das operações de entrega. Além disso, a usabilidade do sistema será aprimorada por meio de uma interface de usuário intuitiva e de alto desempenho.

O Projeto DeliveryX também se compromete com a disponibilidade contínua do sistema, assegurando sua operação 24 horas por dia, 7 dias por semana. Adicionalmente, o projeto visa à integração harmônica com os processos operacionais da Pizza-Express e à aderência aos requisitos regulatórios pertinentes.

A equipe de engenheiros de software encarregada deste projeto buscará profissionalismo e colaboração mútua para cumprir com êxito o objetivo de elevar a Pizza-Express ao posto de líder incontestável na entrega de pizzas rápidas e eficientes por meio do "Projeto DeliveryX".
&gt;*

# Análise de requisitos funcionais e não-funcionais

| Funcionais | Description |
| --- | --- |
| Sistema de Pedidos Online | Desenvolver um sistema que permita aos clientes fazer pedidos de pizza online, incluindo seleção de itens do menu, especificações de pedido e informações de pagamento. |
| Rastreamento de Localização | Criar uma funcionalidade que permita rastrear a localização das lojas de pizza Pizza-Express mais próximas do cliente no momento do pedido. |
| Gestão de Pedidos | Desenvolver uma função para gerenciar e processar pedidos, atribuindo-os à loja de pizza mais adequada com base na proximidade. |
| Eficiência de Entrega | Implementar um sistema que otimize as rotas de entrega para garantir entregas rápidas (em 10 a 15 minutos) após o pedido. |
| Integração de Pagamento | Integrar opções de pagamento online para processar pagamentos de pedidos com eficiência. |
| Sistema de Notificação | Incluir um sistema de notificação que informa os clientes sobre o status de seus pedidos e horário estimado de entrega. |

| Não Funcionais | Description |
| --- | --- |
| Tempo de Resposta | Garantir que o sistema tenha tempos de resposta rápidos para permitir um serviço de entrega ágil.|
| Escalabilidade | Certificar-se de que o sistema seja escalável para lidar com um grande volume de pedidos e lojas. |
| Segurança | Implementar medidas de segurança robustas para proteger os dados dos clientes e os processos de pagamento.|
| Confiabilidade | Assegurar que o sistema seja altamente confiável, minimizando interrupções ou falhas. |
| Usabilidade | Projetar uma interface de usuário intuitiva para clientes e funcionários das lojas, visando facilitar o processo de pedidos e entregas.|
| Desempenho | Garantir que o sistema possa lidar com o processamento simultâneo de pedidos sem degradação significativa do desempenho.|
| Disponibilidade | Assegurar que o sistema esteja disponível 24 horas por dia, 7 dias por semana, para atender às necessidades dos clientes.|
| Integração | Integrar o sistema de software com os processos operacionais das lojas de pizza, garantindo uma operação suave.|
| Compliance | Cumprir regulamentos e padrões de segurança de pagamento, caso seja aplicável.|


# Diagrama de casos de uso

*&lt;
![D1 drawio](https://github.com/Lucas-Oliv/N1/assets/71336527/43107eec-85ba-4f8f-9636-6979507ba86e)
&gt;*
# Descrição dos casos de uso

*&lt;
| Caso de Uso         | Realizar Pedido                                    |
|---------------------|---------------------------------------------------|
| Descrição           | Permite que os clientes façam pedidos de pizza.   |
| Ator Principal      | Cliente                                           |
| Fluxo Principal     | 1.1 O Cliente inicia o aplicativo ou acessa o site da Pizza-Express.|
|                     | 1.2 O Cliente navega pelo menu de itens disponíveis.|
|                     | 1.3 O Cliente seleciona itens do menu (pizzas, bebidas, acompanhamentos, etc.).|
|                     | 1.4 O Cliente personaliza os itens selecionados, se necessário (por exemplo, escolhendo ingredientes adicionais para uma pizza).|
|                     | 1.5 O Cliente adiciona os itens ao carrinho de compras.|
|                     | 1.6 O Cliente revisa o carrinho e faz alterações, se necessário.|
|                     | 1.7 O Cliente confirma o pedido.|
|                     | 1.8 O sistema registra o pedido e processa o pagamento de forma segura.|
|                     | 1.9 O sistema atribui o pedido à loja de pizza mais próxima.|
|                     | 1.10 O Funcionário da Pizzaria recebe o pedido e o inicia.|
|                     | 1.11 O Funcionário da Pizzaria prepara os itens do pedido, embala-os e encaminha-os para entrega.|
|                     | 1.12 O Funcionário da Pizzaria entrega os itens ao Cliente.|
|---------------------|---------------------------------------------------|
| Fluxo Alternativos  |                                                   |
| 3a. Pedido Personalizado | Se o Cliente desejar, ele pode criar uma pizza personalizada, especificando os ingredientes desejados. |
| 3b. Pedido em Grupo | O Cliente pode fazer um pedido em nome de um grupo, especificando várias pizzas e bebidas. |
| 3c. Pedido Especial | O Cliente pode incluir instruções especiais no pedido, como "sem queijo" ou "molho extra" |
| 7a. Cancelar Pedido | O Cliente pode cancelar o pedido a qualquer momento antes da confirmação. |
| 8a. Falha no Pagamento | Se ocorrer uma falha no pagamento, o sistema notificará o Cliente e fornecerá opções de pagamento alternativas. |

| Caso de Uso         | Rastrear Entrega                                  |
|---------------------|--------------------------------------------------|
| Descrição           | Permite que os clientes rastreiem o status e a localização de suas entregas em tempo real. |
| Ator Principal      | Cliente                                          |
| Fluxo Principal     | 1. O Cliente inicia o aplicativo ou acessa o site da Pizza-Express. |
|                     | 2. O Cliente acessa a seção "Rastrear Entrega".  |
|                     | 3. O sistema exibe o status atual do pedido (por exemplo, "Preparando", "Em Rota"). |
|                     | 4. O sistema exibe a localização atual do entregador no mapa. |



&gt;*

# Diagrama de sequencia

*&lt;![D1 1 drawio](https://github.com/Lucas-Oliv/N1/assets/71336527/b27216fc-9245-4ed1-985d-449b82a4a3bd)&gt;*


# Diagrama de classes

*&lt;![Screenshot_3](https://github.com/Lucas-Oliv/N1/assets/71336527/284ff41d-2695-455e-8825-2cdea7817e56)&gt;*

# Diagrama de Componentes

*&lt;![Screenshot_1](https://github.com/Lucas-Oliv/N1/assets/71336527/37fc102e-ed93-4b33-83d7-baff4661bad6)&lt;*


# Decisões de arquitetura

*&lt;Arquitetura de Microserviços:

Optamos por uma arquitetura de microserviços para promover modularidade e escalabilidade. Essa abordagem divide o sistema em componentes independentes, facilitando o desenvolvimento e a manutenção.
Banco de Dados Distribuído:

Escolhemos um banco de dados distribuído para garantir alta disponibilidade e desempenho, especialmente em situações de carga elevada. Isso permite o armazenamento eficiente de dados críticos, como informações de clientes e pedidos.
Arquitetura de Camadas:

Adotamos uma arquitetura de camadas para organizar o sistema de maneira clara, separando a interface do usuário, a lógica de negócios e os dados. Isso simplifica a manutenção e promove uma estrutura coesa.
API RESTful:

Implementamos uma arquitetura baseada em APIs RESTful para facilitar a comunicação entre os diferentes serviços do sistema. Isso promove a interoperabilidade e simplifica integrações com aplicativos externos.
Segurança (OAuth, HTTPS):

Para garantir a segurança dos dados e transações, adotamos protocolos como OAuth para autenticação e autorização, junto com o uso do HTTPS para comunicação segura entre os componentes do sistema.
Mensageria Assíncrona (Kafka, RabbitMQ):

A introdução de sistemas de mensageria assíncrona, como Kafka ou RabbitMQ, fortalece a resiliência do sistema, permitindo o processamento em segundo plano e melhorando a eficiência operacional.
Cache (Redis, Memcached):

Implementamos estratégias de caching utilizando ferramentas como Redis ou Memcached para otimizar o desempenho do sistema. Isso reduz a carga no banco de dados, acelerando o acesso a dados frequentemente requisitados.
Contêineres e Orquestração (Docker, Kubernetes):

Utilizamos contêineres, como Docker, e orquestração, por meio de Kubernetes, para simplificar a implantação consistente e a escalabilidade dos serviços em diferentes ambientes, garantindo eficiência operacional.
Monitoramento e Logs (Prometheus, ELK Stack):

Implementamos ferramentas de monitoramento, como Prometheus, e registro, como ELK Stack, para rastrear o desempenho do sistema, identificar problemas e assegurar uma operação eficiente.
Testes Automatizados (JUnit, Selenium):

A integração de testes automatizados, incluindo testes de unidade, integração e aceitação do usuário, no ciclo de desenvolvimento visa garantir a qualidade do código e facilitar atualizações contínuas.
Escalabilidade Horizontal:

Projetamos o sistema para permitir a escalabilidade horizontal, adicionando instâncias de serviços conforme necessário. Isso assegura a capacidade de lidar com aumentos de carga de maneira eficiente.
Usabilidade da Interface do Usuário:

Priorizamos uma interface de usuário intuitiva e amigável para melhorar a experiência do cliente ao fazer pedidos e rastrear entregas, contribuindo para a satisfação do usuário.&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
