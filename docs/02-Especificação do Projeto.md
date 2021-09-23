# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

**Larissa Lima** tem 35 anos, é médica cardiologista e sócia em uma pequena clínica médica. Gosta de estar sempre em dia com a tecnologia e exige que a clínica onde atende ofereça o agendamento online. Deseja receber notificações de agendamento e cancelamento das consultas de seus pacientes e verificar seus históricos.

**Marcos Daniel** tem 37 anos, é analista de negócio e sócio-diretor de uma empresa. Gosta de explorar a tecnologia e apreciar vinhos. Procura um site que lhe permita realizar o agendamento de suas consultas de forma online pois possui tempo escasso para ficar em ligações. 

**Nelson Souza** tem 60 anos, é aposentado e pratica Pesca Esportiva. Busca facilidade em realizar o agendamento com os melhores médicos do mercado, sendo bem atendido substituir o agendamento telefônico. 

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                 |PARA ... `MOTIVO/VALOR`                                        |
|--------------------|--------------------------------------------------------------------|---------------------------------------------------------------|
|Larissa Lima        |Que meus pacientes realizem o próprio agendamento de forma online   |Digitalizar a empresa                                           |
|Larissa Lima        |Receber  notificação dos agendamentos                               |para obter total controle da minha agenda                      |
|Larissa Lima        |Receber notificação de cancelamentos                                |Para poder realizar possíveis encaixes                         |
|Marcos Daniel       |Localizar clínicas mais próximas com agenda livre para me atender   |Viajo muito pelo Brasil e preciso de agilidade                 |
|Marcos Daniel       |Receber lembretes com possibilidade de cancelar                     |Tenho agenda cheia e posso acabar esquecendo                   |
|Nelson Souza        |Consultar com os melhores médicos avaliados                         |Quero cuidar da minha saúde com os melhores médicos da clínica |
|Nelson Souza        |Receber notificação da última consulta após um período              |Fazer exames de rotinas                                        | 


> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|-----|------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----|
|RF-01| **Login** - O site deve permitir que o usuário realize login utilizando o email e a senha cadastrados.                                                               |Alta | 
|RF-02| **Cadastro Usuário e Senha** - O site deve gerenciar o usuário.                                                                                                     |Média|
|RF-03|**Tipos de Cadastro** - O site deve possuir 3 usuários diferentes, sendo: Médico, Clínica e Paciente. 
|RF-04| **Cadastro Médico** - O site deve permitir que o médico realize o seu cadastro preenchendo os requisitos: Nome, CRM, Data Nascimento, Senha, e-mail, Telefone, Especialidade, Agenda, valor das consultas e convênios aceitos.                                                                                                             |Alta |
|RF-05| **Cadastro Clínicas** -O site deve permitir que as clínicas se cadastrem vinculando seus médicos e preenchendo os requisitos: Endereço, CNPJ, Razão Social, telefone de contato, Senha e e-mail.                                                                                                                                         |Alta |                                                                              
|RF-06| **Cadastro Paciente** -O site deve permitir que os pacientes se cadastrem, preenchendo os requisitos: Nome, Data Nascimento, Endereço, CPF, Telefone.               |Alta |
|RF-07| **Agendamento de Consulta** - O site deve permitir que o paciente/médico/clínica agende consultas.                                                         |Alta |
|RF-08|**Cancelamento de consulta** - O site deve permitir que o paciente/médico/administrador cancele consultas. 
|RF-09| **Consultar Histórico** - O site deve permitir a visualização ou relatório com histórico do paciente/médico/clínica.                                                 |Alta |
|RF-10| **Consultar Médicos** - O site deve permitir a visualização ou relatório com informações de horário de atendimento, data e avaliações de pacientes referente a consulta.                                                                                                                                                                     .|Alta |
|RF-11| **Pesquisar/Consultar** -O site deve permitir que o paciente/administrador pesquise utilizando os filtros: Localidade, especialidade, clínicas, convênios e datas.                                                                                                                                                                       |Alta |
|RF-12| **Confirmação de agendamento** - O site deve notificar o usuário confirmando o agendamento informando o motivo.
      |Baixa| 
|RF-13|**Pós Consulta Paciente** -  O sistema deve permitir que o cliente faça um comentário a respeito da sua experiência e avalie o médicoe a clínica por estrelas, sendo uma para péssimo e cinco para excelente.                                                                                                                                         |Baixa|    
|RF-15|**Lembrete Periódico** - O site deve notificar o cliente de 6 em 6 meses informando que quando foi a ultima consulta.
      |Baixa|
|RF-16|**Pré consulta Médico/Clínica** - O site deve notificar ao médico/clínica quando efetuado um agendamento informando os dados do paciente. 
      |Baixa|
|RF-17|**Notificação de cancelamento Médico/Clínica** - O site deverá notificar ao médico/clínica quando ouver um cancelamento por parte do paciente informando o motivo.
      |Baixa|
|RF-18|**Notificação de cancelamento Paciente** - O site deve notificar ao cliente quando ouver um cancelamento por parte do médico informando o motivo.
      |Baixa|
     

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-01| O App ou site será publicado em um ambiente na Internet.                                                                                      |Alta | 
|RNF-02| O website poderá ser acessado por um telefone celular Android ou IOS com uma visualização adequada.                                           |Alta | 
|RNF-03| O website será compatível com os principais navegadores do mercado.                                                                           |Alta |
|RNF-04| O website deve ser confiável, deve atender às suas especificações.                                                                            |Alta |
|RNF-05| O website deve tratar acessos não autorizados, garantindo um alto grau de segurança.                                                          |Alta |
|RNF-06| A interface do website deve ser amigável, ou seja deve se sentir confortável ao utilizar o site, de forma que sua experiência torna-se fácil. |Média|

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo ultrapassar a data de 06/12/2021.  |
|02| O projeto não pode utilizar recursos externos ( contratar terceiros para o desenvolvimento).              |
|03| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend.                                |

Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
