## Exercicios:
<br>
0. O que são APIs.  Para que servem ?<br>
    As APIs são como interfaces que servem para fazer a comunicação entre um cliente e um servidor, possibilitando o transporte de dados entre eles. Sem duvidas diversos aplicativos e sites que usamos utlizam API, entretanto isso não fica explícito.
<br>
<br>
1. O que são Verbos HTTP ? Quais são eles e o que cada um faz ?<br>
    Os verbos HTTP são um conjunto de métodos de requisição utilizados para indicar a ação que esta sendo requisitada pelo consumidor do serviço.<br>
    Alguns dos verbos são:<br>
    POST   > Utilizado para criar novos recursos, não e um método seguro por conta de que ele altera o estado do recurso no servidor.<br>
    GET    > Utilizado para a leitura ou recuperação de alguma nota, portanto é considerado seguro quanto utilizado dessa forma.<br>
    PUT    > Utilizado para editar recursos, substituindo as suas representações de destino por dados da requisição.<br>
    PATCH  > Utilizado normalmente para fazer uma modificação parcial dos recursos, também não é seguro.<br>
    DELETE > Utilizado para remover algum recurso específico.
<br>
<br>
1.2. Para que o POSTMAN é utilizado? <br>
    O Postman é uma ferramenta que da suporte à documentação das requisição feitas pela API, facilitando criar, compartilhar e testar APIs.
<br>
<br> 
2. O que acontece se voce enviar uma requisição GET pelo POSTMAN a sua githubpage ?<br>
    Quando a requisiçao GET foi feita, basicamente me retornou a leitura do codigo da minha página, semelhante a utilizar o recurso de 'inspecionar' nos navegadores.
<br>
<br>
3. Quando voce acessa uma pagina web pelo navegador, qual é o verbo utilizado ? <br>
    Ao acessar qualquer página web em um navegador, o verbo utilizado é o GET, entretanto o navegador conta com interpretadores, que fazem a leitura dos códigos.
<br>
<br>
4. O que são os códigos de status de resposta HTTP ?  <br>
    Os códigos de status basicamente servem como notas de um servidor, são mensagens para informar como as coisas correram quando o navegador interagiu com o servidor.
<br>
<br>
4.1 Quais as classes de agrupamento dos status HTTP ?  <br>
    100 a 199 - Códigos de resposta de informação;<br>
    200 a 299 - Respostas de sucesso;<br>
    300 a 399 - Redirecionamentos;<br>
    400 a 499 - Erros do cliente;<br>
    500 a 599 - Erros do servidor.
<br>
<br>
4.2 Quando a requisição HTTP é bem sucedida, qual o código ? <br>
    Quando a requisição é bem sucedida o código retornado é o 200.
<br>
<br>
4.3 Qual o status HTTP quando você não é autorizado a acessar um recurso ?  <br>
    Quando você não é autorizado a acessar o código exibido é o 401.
<br>
<br>
4.4 Listar e descrever a utilização os seguintes códigos de cada agrupamento: 100, 200, 201, 202, 301, 400, 401, 403, 404, 405, 500, 501, 502. <br>
    100 - Continaur - Este código basicamente indica o "continuar", ou seja, indica que o servidor já recebeu os requisitos do seu navegador e está pronto para o restante da solicitação; <br>
    200 - Tudo Bem - Código que indica que a página ou algum recurso da mesma está agindo da maneira esperada; <br>
    201 - Criado - Indica que a requisição foi bem sucedida e um ou mais recursos foram criados com sucesso; <br>
    202 - Aceite - Este código indica que o servidor aceitou o pedido do seu navegador; <br>
    301 - Recurso movido permanentemente - Este código indica que uma página ou um recurso foi permanentemente substituído por outro; <br>
    400 - Mal Pedido - O servidor não entendeu a requisição devido a um erro do lado do cliente; <br>
    401 - Não Autorizado - Código que indica que você não tem autorização de credenciais válidas; <br>
    403 - Acesso Proibido - Este código indica que o usuário tentou acessar algo que não tem a permissão devida; <br>
    404 - Recurso não encontrado - Indica que o servidor não encontrou o recurso solicitado; <br>
    405 -  

5. O que é Node.js ?  
5.1 Instale-o em sua máquina, versão LTS v14.17.3  | Listar os comandos que utilizou.
5.2 Para checar se você possui o node:   
```
$ node -v
v14.17.3
```
6. O que são gerenciadores de pacotes (software)?  
6.1 Instale os principais gerenciadores de pacote para a linguagem JavaScript em sua máquina. | Listar os comandos que utilizou.  
6.2 Para checar se você possui os gerenciadores:  
```
$ npm -v
7.24.1

$ yarn -v
1.22.11
```
7. Java e JavaScript são a mesma linguagem ? Descreva as diferenças entre essas linguagens e pesquise do porque do nome ser parecido.
  
8. Você possui o gerenciador de pacotes da linguagem Python em sua máquina?  
8.1  Caso não tenha, instale o principal gerenciador de pacote para a linguagem python. | Listar os comandos que utilizou.  
8.2 Para checar se você possui o gerenciador de pacote do python (V maisusculo):  
```
$ pip -V
pip 21.3.1
```
9. O que é linguagem interpretada ? O que é linguagem compilada ? E hibidria ?  
9.1 Escreva exemplos de linguagens compiladas, interpretadas e hibidrias.  
9.2 Qual o nome do compilador da linguagem C ?  
9.3 Qual o nome do compilador da linguagem Java ?
9.4 Qual o nome do interpretador do bytecode da linguagem java ?  
9.5 Qual o nome do interpretador da linguagem JavaScript ?
9.6 Qual o nome interpretador da linguagem Python?
9.7 Python é ou não compilado ? Pesquise e descreva o que encontrar.

10. O que é POO  em programação?  
10.1 Java é totalmente POO. O que é uma classe e o que é um objeto ?  
10.2 O que é a JVM, JRE e a JDK ? Descreva.  
10.3 Quais os principais gerenciadores de pacote da linguagem java ?
10.4 Instale o Open JDK 11 em sua máquina. | Listar os comandos que utilizou.  

```
$ java --version
java 11.0.12 2021-07-20 LTS
```     

11. O que é uma IDE, o que é um editor de texto ?    
11.1 Vs Code é uma IDE ou um editor de Texto ?  
11.2  Instale o Vs Code em sua máquina.  
11.3 IntelliJ é uma IDE ou editor de texto ?  
11.4 Instale o IntelliJ em sua máquina

12. O que é docker ?    
12.1 Quais suas vantagens ?  
12.1 Instale o Docker em sua máquina. | Listar os comandos que utilizou.  

* Estudaremos containers Docker, a linguagem Java entre outras com calma futuramente, por enquanto é somente importante se familiarizar com os conceitos apresentados nesse exercicio e com os processos de instalação e configuração do ambiente de desenvolvimento. 
---