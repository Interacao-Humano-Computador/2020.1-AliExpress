### Metodologia
A Análise Hierárquica de Tarefas ( HTA  – Hierarchical Task Analysis) foi desenvolvida na década de 1960 para entender as competências e habilidades exibidas em tarefas complexas e não repetitivas, bem como para auxiliar na identifi cação de problemas de desempenho (Annett, 2003; Annett e Duncan, 1967). Ela ajuda a relacionar o queas pessoas fazem (ou se recomenda que façam), por que o fazem, e quais as consequ-ências caso não o façam corretamente. 

Uma tarefa é qualquer parte do trabalho que precisa ser realizada. Toda tarefa pode ser defi nida em termo de seu(s) objetivo(s). Tarefas complexas são defi nidas em termos de objetivos e subobjetivos, num desdobramento hierárquico. Uma análise funcional de tarefas começa pela definição dos objetivos das pessoas, antes de considerarmos as ações através das quais a tarefa pode ser realizada e o objetivo ser atingido.

### Análise Hierárquica de Tarefas(HTA)
Esse tipo de análise funciona separando as operações em objetivos e subobjetivos a serem cumpridos pelo usuário, é feito uma tabela relatando o passo a passo de cada objetivo ou operação assim como a descrição dos problemas e recomendações.
<br>
<br>
Para uma compreensão mais clara da tabela deve-se entender o significado das operações 1+2, 1/2 e 1>2.
|Símbolo|Descrição|
|:-:|:-:|
|1+2| Expressa que as tarefas são feitas de forma paralela|
|1/2| Expressa que há escolha em relação das tarefas|
|1>2| Expressa que as tarefas são feitas de forma sequencial  |

### Fluxo de Login

![Fluxo de Login](./images/v0.3HTA/HTA-FluxodeLogin.png ':size=50%')

## Fluxo de Login
|Operações/Objetivos|Problemas e Recomendações|
|:-:|:-:|
|0- Fluxo de Login 1/2|Problemas e Recomendações|
|1- Usar o site sem logar||
|1.1- Fluxo de compra/venda||
|1.1.1- Preencher o formulario de login 1>2|Input: Todos os dados necessarios para poder entrar na conta no aliexpress|
|1.1.1.1- Inserir dados para o login 1+2|Ação: Informar nome, preço.<br>Plano: Deverá ser inserido o email e a senha para que seja possivel efetuar o login|
|1.1.1.2- Finalizar o login|Ação: Clicar no botão de fazer o login|
|2- Fazer o login 1>2|Ação: Clicar no botão de fazer o login|
|2.1- Inserir dados para o login 1+2|Ação: Informar nome, preço.<br>Plano: Deverá ser inserido o email e a senha para que seja possivel efetuar o login|
|3- Criar uma conta 1/2|Ação: Clicar no botão de criar uma conta no aliexpress|
|3.1- Preencher formulário|Input: Todos os dados necessarios para poder criar uma conta no aliexpress|
|3.1.1- Finalizar Cadastro 1>2|Ação: Clicar no botão de concluir a criação de conta|
|3.1.1.1- Inserir dados para o login 1+2|Ação: Informar nome, preço<br>Plano: Deverá ser inserido o email e a senha para que seja possivel efetuar o login|
|3.1.1.2- Finalizar o login|Ação: Clicar no botão para poder fazer o login|

<br>

## Inserir dados para o login
|Operações/Objetivos|Problemas e Recomendações|
|:-:|:-:|
|1 - Informar senha|Input: Informar a senha cadastrada no aliexpress|
|2 - Informar email|Input: Informar o email cadastrado no aliexpress|
|3 - Verificar dados inseridos|Ação: Fazer uma verificação de que a senha e o email estão corretos |

<br>

### Fluxo de Compra

![Fluxo de compra](./images/v0.3HTA/HTA-Comprar.png ':size=50%')

|Operações/Objetivos|Problemas e Recomendações|
|:-:|:-:|
|0- Comprar|Input: Compra realizada pelo usuário com o login já efetuado.<br>Plano: realizar o login ou se cadastrar e depois efetuar os procedimentos de compra do produto|
|1- Fluxo de Login 1/2||
|1.1- Propaganda de um certo produto||
|1.2- Link de produto| |
|1.3- Pesquisar algum produto pela barra de pesquisa|Input: Dado para pesquisar o produto que o usuairo quer.<br>Plano: Fazer a pesquisa de um determinado produto.|
|2- Pagina do produto 1/2||
|2.1- Adicionar ao carrinho 1/2|Ação: Clicar no botão de adicionar ao carrinho|
|2.1.1- Adicionar novos produtos ao carrinho||
|2.2- Comprar agora|Ação: Clicar no botão de comprar|
|3- Continuar para pagamento 1/2||
|3.1- Adicionar um cupom de desconto|Ação: Adicionar o código do cupom de desconto<br>Problema: Cupom pode não ser válido|
|3.2- Confirmar método de pagamento|Input: Adicionar dados da forma de pagamento escolhida<br>Plano: Escolher a forma de pagamento e depois informar os dados|
|3.2.1- Confirmar endereço de entrega|Input: Informar cidade, e endereço, bem como o CEP<br>Ação: Escolher cidade, e digitar endereço, CEP e outros dados referentes ao endereço de entrega|
|3.2.1.1- Finalizar comprar|Ação: apertar o botão finalizar compra|
|3.2.1.1.1- Aviso sobre a data de entrega||

### Fluxo de Venda

![Fluxo de venda](./images/v0.3HTA/HTA-Vender.png ':size=50%')

|Operações/Objetivos|Problemas e Recomendações|
|:-:|:-:|
|0- Vender|Input: Venda realizada pelo usuário login já efetuado.<br>Plano: realizar o login ou se cadastrar e depois efetuar os procedimentos de venda do produto|
|1- Fluxo de Login||
|1.1- Criar venda 1>2|Input: Adicionar produto a ser vendido|
|1.1.1- Inserir dados do produto 1+2| |
|1.1.1.1- Inserir o nome, preço, descrição do produto|Ação: Informar nome, preço.<br>Plano: Deverá ser efetuado uma escolha do preço do produto bem como uma descrição|
|1.1.1.2- Selecionar categoria do produto|Ação: Selecionar que tipo de categorias aquele produto faz parte|
|1.1.1.3- Selecionar locais que o produto pode ser entregue|Ação: Informar para quais países o produto poderá ser enviado|
|1.1.1.4- Selecionar categoria do produto|Ação: Selecionar que tipo de categorias aquele produto faz parte|
|1.2- Visualizar vendas|Ação: Clicar no botão de comprar|
|1.2.1- Atender comprador||

### Versionamento

|Data|Versão|Descrição|Autor|
|:-:|:-:|:-:|:-:|
|22/10/2020|0.1|Criação do documento| Pedro Vítor de Salles Cella e Paulo Gonçalves Lima|
|22/10/2020|0.2|Adicionando a versão 0.3 da análise de tarefas| Pedro Vítor de Salles Cella e Paulo Gonçalves Lima|
|23/10/2020|0.3|Adicionando a avaliação da análise de tarefas| Pedro Vítor de Salles Cella e Paulo Gonçalves Lima|

<br>

### Referências

- BARBOSA, Simone; SILVA, Bruno. "Interação Humano-Computador". Elsevier Editora Ltda, 2010.