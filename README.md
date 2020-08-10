# DesafioInMetrics
Desafio de Automacao Web

Teste Inmetrics 

Autor: Alex Santos
Desafio: Automação Web do site InMetrics

•	Features Automatizadas: 
1.	Cadastrar Usuário
2.	Login
3.	Funcionários (Cadastrar > Editar > Excluir)

REQUISITOS PARA EXECUTAR A AUTOMACAO:
•	Download do Eclipse 32 ou 64bit (do site Eclipse.org).

•	Download da JDK (site da Oracle).

•	Configurar JAVA_HOME no seu computador.

•	Após configurar sua maquina, abra o Eclipse e crie um projeto MAVEN.

•	Importe o projeto/desafio para o seu projeto criado no eclipse.

•	Certifique-se que os pluggins estão presentes no arquivo pom.xml para execução dos testes.
1.	Selenium Java
2.	Jbehave Gherkin
3.	Jbehave Spring
4.	Spring Tool

•	O projeto já vem com Chrome/Opera Driver, caso seja de sua opção usar outro driver. Basta ir no site “selenium.dev/downloads” baixar o drive se sua preferencia, em seguida crie uma pasta no path “src/test/resources” e importe o driver. E por fim, realizar as alterações necessárias na classe WebPage.java (do pacote br.com.desafioTest.steps). 

•	Instale JBehave Plug-In para utilizar dos arquivos .story do projeto, seguindo passo-a-passo abaixo:
1.	No Eclipse, vá em “Help > Install New Software”
2.	Clique no botao Add
3.	No “Add Repository dialog” digite: 
4.	Name: Jbehave
5.	Location: jBehave – http://jbehave.org/reference/eclipe/updates/
6.	Selecione a opcao jBehave e clique em “Next”
7.	Em seguida, reinicie seu Eclipse e plugin para os arquivos .story estará instalado com sucesso. 


EXECUTANDO OS TESTES
•	Clique com botão direito na classe “TestRunner.java” pertencente ao pacote “br.com.desafioTest.runner”

•	Em seguida, clique em “Run As”, e selecione a opção “JUnit Test”

•	Logo assim, todos os scenarios serão executados (de acordo com a ordem presente no arquivo Teste.story.) 

TESTE DE API:
• Abra o projeto no Eclipse e execute a classe APITest.java pelo Junit. 

