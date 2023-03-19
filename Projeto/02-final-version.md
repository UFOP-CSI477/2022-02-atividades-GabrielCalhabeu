# **CSI606-2021-02 - Remoto - Trabalho Final - Resultados**

## *Aluna(o): Gabriel Augusto Rocha Calhabeu - 20.1.8039*

--------------

<!-- Este documento tem como objetivo apresentar o projeto desenvolvido, considerando o que foi definido na proposta e o produto final. -->

### Resumo


  O objetivo do aplicativo, é permitir que DMs em RPGs de mesa consigam controlar NPCs durante combate, em plataformas online.
Com vários NPCs em um confronto, acaba ficando difícil gerenciar todos os inimigos
e suas Iniciativas, HPs, Status, Turnos, etc. O usuário pode logar ou não para poder usar. E para salvar/carregar é preciso criar uma conta.

### 1. Funcionalidades implementadas
<!-- Descrever as funcionalidades que eram previstas e foram implementas. -->
As implementadas previstas que foram implementadas:
Criar conta;</br>
Entrar na conta;</br>
Criar instâncias de inimigos;</br>
Gerenciar as instâncias (HP, Status, etc);</br>
Salvar as instâncias com um arquivo em sua conta, apagar e carregar o aqruivo.</br>

  
### 2. Funcionalidades previstas e não implementadas
<!-- Descrever as funcionalidades que eram previstas e não foram implementas, apresentando uma breve justificativa do porquê elas não foram incluídas -->
Algumas funcionalidades não implementandas, que não necessariamente foram previstas, foram:
Editar perfil, foto, etc;</br>
Um mesmo usuário poder salvar múltiplas sessões diferentes.</br>

### 3. Outras funcionalidades implementadas
<!-- Descrever as funcionalidades implementas além daquelas que foram previstas, caso se aplique.  -->
Não houveram funções implementadas, além daquelas que foram previstas.

### 4. Principais desafios e dificuldades
<!-- Descrever os principais desafios encontrados no desenvolvimento do trabalho, quais foram as dificuldades e como elas foram superadas e resolvidas. -->
Os principais desafios consistiram em criar os controladores, e averiguar que os dados sendo recebidos são válidos, assim como os dados passados.
Em relação ao que mais foi trabalhoso, foi o frontend.

Para os controladores e banco de dados, um método de tentativa e erro foi implementado, até que foi possível verificar os possíveis erros.
  
### 5. Instruções para instalação e execução
<!-- Descrever o que deve ser feito para instalar (ou baixar) a aplicação, o que precisa ser configurando (parâmetros, banco de dados e afins) e como executá-la. -->
É necessario baixar o repositório, e garantir que  as suas dependências (Mongoose, express, axios, etc) estão funcionando. 
Para executar é necessário utilizar nas pastas:</br> 
 <ul><li>mobmanager/src:  
  
  ```npm start```  
  
  </li><li>  server:
  
  ```npm run dev ```
  
  
  </li>
  </ul>
  

 
 
Em relação ao banco de dados, em teoria, não é necessário fazer nenhuma configuração, pois a senha e usuário já estão inclusos.
O banco é o MongoDb, e em nuvem, e o acesso foi permitido para qualquer rede.

Caso não seja possível conectar ao banco, contate-me, ou crie o seu banco em nuvem no MongoDB e configure o arquivo server/src/config/dbConfig.js

### 6. Referências
<!-- Referências podem ser incluídas, caso necessário. Utilize o padrão ABNT. -->
