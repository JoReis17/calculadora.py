# calculadora.java

# OBJETIVO GERAL

Desenvolvimento de um sistema de gerenciamento de anúncios para uma agência que permite o cadastro e o rastreio dos resultados de uma campanha.


# Situação Problema (cenário)

A agência Divulga Tudo precisa de um programa para gerenciar os seus anúncios online. O objetivo dos anúncios faz parte de uma campanha nas redes sociais. O sistema de gerenciamento permitirá a gestão do anúncio e o rastreio dos resultados da campanha.

# Funções do Negócio

O programa é composto de duas partes:

1ª Parte – Uma calculadora de alcance de anúncio online baseada em dados de análise de anúncios anteriores. A agência tem os seguintes dados:

   *	A cada 100 pessoas que visualizam o anúncio 12 clicam nele.
   *	A cada 20 pessoas que clicam no anúncio 3 compartilham nas redes sociais. 
   *	Cada compartilhamento nas redes sociais gera 40 novas visualizações. 
   *	30 pessoas visualizam o anúncio original (não compartilhado) a cada R$ 1,00 investido. 
   *	O mesmo anúncio é compartilhado no máximo 4 vezes em sequência: (1ª pessoa --> compartilha --> 2ª pessoa --> compartilha --> 3ª pessoa --> compartilha --> 4ª pessoa)

2ª Parte – Um sistema de cadastro de anúncios que fornece os relatórios de cada anúncio, podendo ser filtrados por intervalo de tempo e cliente e que atende os seguintes requisitos:

   *	Nome do anúncio.
   *	Cliente.
   *	Data de início.
   *	Data de término.
   *	Investimento por dia.
   *	Gerar Relatório com os seguintes dados: valor total investido, quantidade máxima de visualizações, de cliques e de compartilhamentos.

# SISTEMA

Para a utilização do sistema será necessário realizar a instalação dos programas abaixo listados. Para tanto o(a) usuário(a) deverá pesquisar na internet e realizar o download dos arquivos correspondentes ao seu sistema operacional. Ao finalizar o download, executar cada arquivo seguindo a ordem abaixo.

1. JDK 8. 
2. IDE Apache Netbeans versão 12LTS.
3. Gerenciador do Servidor: XAMPP (banco de dados).
4. Servidor do Sistema: Apache Tomcat versão 8.5.59.


# Instalando o sistema de gerenciamento

  1. Abra a IDE Netbeans e aguarde o carregamento.
  2. Clique no x para fechar a start page para aparecer as abas padrão da IDE.
  3. Primeiro adicionar o servidor Tomcat ao Netbeans e rode o sistema de gerenciamento.
  4. Clique na guia “Services” para adicionar o servidor.
  5. Clique com o botão direito do mouse e em seguida clique em Add Server.
  6. Selecione o servidor Apache Tomcat e clique em next.
  7. Clique em download and activate.
  8. Clique em next.
  9. Aceite os termos e clique em install.
  10. Clique em finish.
  11. Será ativado o JAVA WEB e o EE.
  12. Agora o servidor poderá ser adicionado. Em Server Location procure a pasta   descompactada do apache Tomcat.
  13. Crie usuário e senha. Escolha um de sua preferência pois ele será usado quando para startar o servidor.

# Adicionando e Executando o projeto do sistema de gerenciamento na IDE Apache Netbeans 12LTS

  1. Após os passos anteriores ir em adicionar o projeto que foi disponibilizando.
  2. Clique em open project.
  3. Localize a pasta do projeto descompactada “NetbeansProjects”. Selecione e clique em Open Project.
  4. Espere o Netbeans adicionar o projeto e fazer as validações.
  5. Após a IDE adicionar o projeto, clique com o botão direito em cima do mesmo e em seguida clique em Clean and Build.
  6. Será realizado o clean and build. Para visualizar o status do processo pressione as teclas Ctrl + 4.
  7.  Irá retornar a mensagem de BUILD SUCCESSFUL.
  
  # Banco de Dados
  
   1. Abra o Xampp.
   2. Em seguida dê um start nos serviços do Apachee do MySQL.
   3. Clique em admim no service do MySQL, para abrir o gerenciador do banco de dados, para que seja inserido o script de banco de dados do projeto.
   4. Após isso irá abrir o navegador com a seguinte tela.
   5. Vá até a aba importar e escolha o arquivo .sql que foi disponibilizado para download.
   6. Após adicioná-lo, vá em executar.
   7. Após o término ele irá mostrar essa mensagem: Importação terminou com sucesso.
 
 # Executando o Projeto
 
  1. Após fazer a inserção do banco de dados, volte no Netbeans e execute o projeto.
  2. Ele irá iniciar o servidor e caso peça a senha será aquela que foi configurada.
  3. Após isso ele abrirá o navegador com o sistema web funcionando.
  
  

    
    
  



