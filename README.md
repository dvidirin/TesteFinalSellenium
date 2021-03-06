# Tarefa Sellenium Webdriver + Java + Cucumber

Desenvolvido por: <br>
<ul>
  <li>Daniel Vidiri Neto - https://github.com/dvidirin</li>

# Descrição da Tarefa

Criar um projeto de teste Selenium WebDriver e Cucumber, usando Page objects.<br>
Preencher os campos das abas do site http://sampleapp.tricentis.com/101/app.php e receber mensagem de sucesso ao enviar o formulário.

## Caso de teste

<b>Funcionalidade:</b> Acessar o site Tricentis, preencher um formulario e ver uma mensagem de sucesso<br>

<b>Cenario:</b> Acessar o site da Trincentis<br>
Dado que o usuario esta no site tricentis<br>

<b>Cenario:</b> Preencher o formulario da aba enter vehicle data e pressione next<br>
Quando o usuario esta na aba um "Enter Vehicle Data"<br>
E o usuario preenche o campo make "Suzuki"<br>
E o usuario preenche o campo model "Motorcycle"<br>
E o usuario preenche o campo cylinder capacity "300"<br>
E o usuario preenche o campo engine performance "800"<br>
E o usuario preenche o campo date of manufacture "12/05/1999"<br>
E o usuario preenche o campo number of seats1 "2"<br>
E o usuario preenche o campo right hand drive "No"<br>
E o usuario preenche o campo number of seats2 "2"<br>
E o usuario preenche o campo fuel type "Electric Power"<br>
E o usuario preenche o campo payload "50"<br>
E o usuario preenche o campo total weight "200"<br>
E o usuario preenche o campo list price "80000"<br>
E o usuario preenche o campo license plate number "FQY0130"<br>
E o usuario preenche o campo annual mileage "2000"<br>
E clica no botao next aba um<br>

<b>Cenario:</b> Preencher o formulario da aba enter insurant e pressione next<br>
Quando o usuario esta na aba dois "Enter Insurant Data"<br>
E o usuario preenche o campo first name "Carmen"<br>
E o usuario preenche o campo last name "Sandiego"<br>
E o usuario preenche o campo date of birth "09/18/1979"<br>
E o usuario preenche o campo gender "Female"<br>
E o usuario preenche o campo street address "Avenida de Mayo"<br>
E o usuario preenche o campo country "Argentina"<br>
E o usuario preenche o campo zip code "88888888"<br>
E o usuario preenche o campo city "Buenos Aires"<br>
E o usuario preenche o campo occupation "Selfemployed"<br>
E o usuario preenche o campo hobbies " Cliff Diving"<br>
E o usuario preenche o campo website "https://en.wikipedia.org/wiki/Carmen_Sandiego_(character)"<br>
E clica no botao next aba dois<br>

<b>Cenario:</b> Preencher o formulario da aba enter product data e pressione next<br>
Quando o usuario esta na aba tres "Enter Product Data"<br>
E o usuario preenche o campo start date "03/28/2024"<br>
E o usuario preenche o campo insurance sum "30.000.000,00"<br>
E o usuario preenche o campo merit rating "Malus 13"<br>
E o usuario preenche o campo damage insurance "Full Coverage"<br>
E o usuario preenche o campo optional products "Legal Defense Insurance"<br>
E o usuario preenche o campo courtesy car "Yes"<br>
E clica no botao next aba tres<br>

<b>Cenario:</b> Selecionar a opcao de preco do seguro e pressione next<br>
Quando o usuario esta na aba quatro "Select Price Option"<br>
E escolhe o valor seguro "Platinum"<br>
E clica no botao next aba quatro<br>

<b>Cenario:</b> Preencher o formulario da aba send quote e pressione send<br>
Quando o usuario esta na aba cinco "Send Quote"<br>
E o usuario preenche o campo email "carmen@testando.com.ar"<br>
E o usuario preenche o campo phone "54777777777"<br>
E o usuario preenche o campo username "carmenvile"<br>
E o usuario preenche o campo password "Cv123456"<br>
E o usuario preenche o campo confirm password "Cv123456"<br>
E o usuario preenche o campo comments "Soy la reina de los ladrones kkkkkk"<br>
E clica no botao send<br>
Então verifica a mensagem "Sending e-mail success!"<br>

-------------------------------------------------------------------

## Ferramentas utilizadas 
:heavy_check_mark: <b>Java</b><br>
Linguagem de programação utilizada para programar os passos<br>

:heavy_check_mark: <b>Maven</b><br>
Gerenciador de dependências<br>

:heavy_check_mark: <b>Cucumber</b><br>
Framework responsável para usar a linguagem Gherkin<br>

:heavy_check_mark: <b>Selenium</b><br>
Framework responsável por fazer a integração do código Java com a linguagem Gherkin e automatização do navegadore<br>

--------------------------------------------------------------------

## Como utilizar
### Pré-requisitos
Instalar programas abaixo de acordo com seu sistema operacional.<br>
- Instalar o java:
https://www.java.com/pt-BR/download/ie_manual.jsp?locale=pt_BR
- Instalar jdk

- Instalar a IDE Eclipse

- Verificar se o JAVA_HOME está configurado em seu computador<br>

### Baixar a tarefa do GitHub
- Estando no repositório da tarefa, clicar no botão "Code" (botão verde) e selecionar "Download ZIP"

- O arquivo virá compactado, descompactar o arquivo<br>

### Para importar no Eclipse
- Com o Eclipse aberto, ir na opção de menu File e em seguida selecionar "Open Projects from File System..."

- Na nova janela que se abriu, clicar no botão "Directory..." e escolher onde está a pasta do projeto que foi descompactado

- Selecionar a "testFinalTricentis", que deverá estar dentro de outra pasta e clicar no botão "Selecionar pasta"

- O Eclipse irá importar o projeto<br>

### Para executar a tarefa no Eclipse
- Após importar o projeto, dar dois cliques em "src/test/resources"

- Dois cliquem em "com"

- Dois cliques em "tricentis"

- Dois cliquem em "sampleapp"

- Dois cliques em "user.feature"

- Abrindo o código na janela central do Eclipse, clicar em qualquer lugar desses códigos com o botão direito e selecionar "Run As" -> "1 Cucumber Feature"
  
- Caso seja aberto uma janela dizendo que há um erro no Workspace do Eclipse, clique no botão "Proceed" que o código será executado corretamente. Isso é um bug de importação do próprio Eclipse.  

- O código executará com sucesso.

-------------------------------------------------------------------

# Obrigado pela Oportunidade!

