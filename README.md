# Sprint1 java - Projeto MyTrend

![Programa](./Documentos/MyTrend.png)

- Acessar Link para vídeo do Projeto: https://youtu.be/bcxfzYwGMmM?si=ZPWaerNrTpIVxYxn

### Nome da Aplicação: MyTrend

### Descrição do projeto: 
<br>
- O MyTrend é um aplicativo voltado para o setor de Varejo, focado na venda de roupas, acessórios e sapatos. Desenvolvido em resposta ao desafio da Plusoft, "Desvendando o Potencial dos Dados", o MyTrend utiliza AI Generativa e Deep Analytics para oferecer uma experiência única aos clientes. Ele permite aos usuários encontrar combinações ideais de roupas de forma ágil e inovadora, utilizando dados gerados nas interações com clientes, leads e prospects. Com ênfase na compreensão e utilização eficaz dos dados, o MyTrend impulsiona o crescimento empresarial ao fornecer recomendações personalizadas e relevantes para cada usuário.

 
## Integrantes
- Guilherme Rocha Toledo dos Santos - RM99396
  <br>
 Responsável pela elaboração do CRUD do Pedido e exportação do GitHub.
  
- Gustavo Nunes Pereira - RM551496
  <br>
  Responsável pela elaboração do CRUD de Endereco.
  
- Isadora Tatajuba Moreira Pinto - RM552522
  <br>
  Responsável pela elaboração do CRUD de Cliente.
   
- Maria Eduarda Sousa de Oliveira - RM552477
  <br>
  Responsável pelo README e Documentação do Projeto.
  
- Matheus Wasserman Fernandes Silva - RM550712
  <br>
  Responsável pela elaboração de Diagramas MER e DER.


## Execução do código

1. Extrair arquivo da pasta zipada
2. Abrir o IntelliJ
3. Na opção (OpenFile) e acessar a pasta "sprint"
4. Com o código Java aberto no IntelliJ, rodar as dependências (build.graddle)
5. Rodar a aplicação
6. Para requisições utilizar os endpoints que estão disponíveis na documentação do projeto.


## Visão geral - Listagem de endpoints 
### Endpoints Cliente
- Criar Cliente <br>
  Método: POST  <br>
  Endpoint: /api/cliente  <br>
  Descrição: Cria um novo cliente com os dados fornecidos.  <br>
  
- Buscar Cliente  <br>
  Método: GET  <br>
  Endpoint: /api/cliente/buscar  <br>
  Descrição: Busca todos os clientes cadastrados.  <br>
  
- Atualizar Cliente
  Método: PUT  <br>
  Endpoint: /api/cliente/{id}  <br>
  Descrição: Atualiza os dados de um cliente específico identificado pelo ID.  <br>
  
- Excluir Cliente
  Método: DELETE  <br>
  Endpoint: /api/cliente/{id}  <br>
  Descrição: Exclui um cliente específico identificado pelo ID.  <br>

### Endpoints Endereço
- Criar Endereço  <br>
  Método: POST  <br>
  Endpoint: /api/endereco  <br>
  Descrição: Cria um novo endereço com os dados fornecidos. <br>
  
- Atualizar Endereço  <br>
 Método: PUT  <br>
 Endpoint: /api/endereco/{id}  <br>
 Descrição: Atualiza os dados de um endereço específico identificado pelo ID.  <br>
- Buscar Endereço  <br>
Método: GET  <br>
Endpoint: /api/endereco/buscar  <br>
Descrição: Busca todos os endereços cadastrados.  <br>
- Excluir Endereço  <br>
Método: DELETE  <br>
Endpoint: /api/endereco/{id}  <br> 
Descrição: Exclui um endereço específico identificado pelo ID.  <br>

### Endpoints Pedido
- Criar Pedido <br>
 Método: POST <br>
 Endpoint: /api/pedido <br>
 Descrição: Cria um novo pedido com os dados fornecidos. <br>
- Atualizar Pedido <br>
 Método: PUT <br>
 Endpoint: /api/pedido/{id} <br>
Descrição: Atualiza os dados de um pedido específico identificado pelo ID. <br>
- Buscar Pedido <br>
  Método: GET <br>
  Endpoint: /api/pedido/buscar <br>
  Descrição: Busca todos os pedidos cadastrados. <br>
- Excluir Pedido <br>
  Método: DELETE <br>
  Endpoint: /api/pedido/{id} <br>
  Descrição: Exclui um pedido específico identificado pelo ID. <br>

<br>

## Observações <br>
- Observação: Diagramas Relacionais e UML estão inseridos na documentação commitada. <br>
- Os endpoints listados estão disponíveis na pasta "Enpoints". <br>

  


