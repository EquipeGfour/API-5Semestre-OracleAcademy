<p align="center">
<h1 align="center"> Sprint 01 - 04/09 à 24/09 </h1>
<br id="topo">
<p align="center">
    <a href="#Objetivo">Objetivos da Sprint</a>  |  
    <a href="#entregas">Requisitos</a>  |
    <a href="#burndown">Burndown</a>  |
    <a href="#links">Links Úteis</a>  |     
</p>

<span id="Objetivo">
<h2> 🎯 Objetivo da Sprint</h2>
<h4> Para esta primeira entrega, foi decidido, após conversa com o cliente, que seria entregue uma aplicação que atendesse, mesmo que minimamente, o desafio proposto por ele - Criação de uma aplicação capaz de gerir as atividades de determinado indivíduo, separando-as por prioridade e com controle de tempo - para tanto, dividimos o time para definição das nomenclaturas que utilizariamos, criação de protótipos para validação com o cliente, modelagem dos dados...</h4>

<h2>📹 Video Sprint 1</h2>
<h3>https://www.youtube.com/watch?v=_wjq_ZkMMtc</h3>
    
<p>Requisitos Funcionais abrangidos nessa Sprint:</p>

- **RF 01:** Modelagem do banco;
- **RF 02:** CRUD de objetivos do usuário;
- **RF 03:** CRUD de Tarefas do usuário para alcançar determinado objetivo;
- **RF 04:** Implementação da Lógica de Priorização;
- **RF 05:** Implementação da estipulação de tempo de cada Objetivo.

<p>Requisitos Não Funcionais abrangidos nessa Sprint:</p>

- **RNF 12:** Documentação no GitHub;
- **RNF 13:** Versão Mobile Android;
- **RNF 14:** Utilização de React Native ;
- **RNF 15:** Utilização do NodeJS (Typescript);
- **RNF 16:** Utilização do Firebase.

<br>

<span id="entregas">
<h2> 📑 Requisitos</h2>

### RF 01: Modelagem do banco:
A modelagem de banco de dados é o processo de criar uma representação estruturada e organizada dos dados que a aplicação precisará armazenar e gerenciar. Ela envolveu a definição de tabelas, campos, relacionamentos e restrições tudo para garantir que os dados fossem armazenados de forma eficiente, consistente e acessível. Sendo fundamental para o desenvolvimento do sistema e desempenhando um papel crucial na garantia da integridade e eficiência dos dados.
<br>

### RF 02: CRUD de objetivos do usuário:
O desenvolvimento do CRUD de objetivos nada mais é do que a entrega da Criação, Listagem, Update e Delete de objetivos, que definimos como uma meta/plano/projeto macro que determinado usuário possuí e que para conclui-lo, ele precisa finalizar todas as tarefas relacionadas a esse objetivo, lembrando que o mesmo ainda possuí parametros de priorização e estipulação de tempo em dias.
Ex.: Objetivo: Construir uma casa de cachorro
     Tarefas:
        - Comprar material;
        - Construir a base;
        - ...
    
<br>

### RF 03: CRUD de Tarefas do usuário para alcançar determinado objetivo:
Assim como o objetivo, o CRUD de tarefas diz respeito a toda a parte de Criação, Listagem, Update e Delete de tarefas, e estas por sua vez são as responsáveis por são as responsáveis por compor determinado Objetivo, possuíndo agora nesta primeira entrega, parametros de priorização, titulo e descrição.
<br>

### RF 04: Implementação da Lógica de Priorização:
A lógica de priorização que foi implementada nesta sprint se trata de uma lógica que utiliza apenas os parametros de priorização, então o usuário passará se o objetivo é de prioridade baixa, media ou alta, e depois setará se as tarefas relacionadas são de prioridade baixa, media, alta ou urgente. Para as proximas entregas, pretendemos aprimorar ainda mais essa lógica, acrescentando o tempo esperado de conclusão da tarefa nessa lógica.
<br>

### RF 05: Implementação da estipulação de tempo de cada Objetivo:
Para esta primeira entrega, implementamos a estipulação de tempo em dias dos Objetivos, assim, por se tratarem de metas/planos/projetos macro, esse era a melhor unidade de medida para acompanhamento deles.
Para as proximas, pretendemos entregar estipulações de tempo mais precisas para tarefas, utilizando horas e até mesmo minutos, caso necessário, uma vez que são atividades em tese menores que serão realizadas.
<br>


<span id="burndown">
<h2>:chart_with_downwards_trend: Burndown da Sprint</h2>


<h1 align="center">
<img src="/img/burndown.png" alt="Burndown" /></h1>

<span id="links">
<h2>:card_file_box: Links Úteis</h2>

Link do Repositório do Front-End: https://github.com/EquipeGfour/API-5Semestre-OracleAcademy-FrontEnd

Link do Repositório do Back-End: https://github.com/EquipeGfour/API-5Semestre-OracleAcademy-BackEnd

<br>

 
 → [Voltar ao topo](#topo)
