# SUBLIME_NXC

Pacote feito para programar o Lego Mindstorm com o software de programação Sublime Text 3.

Antes de usar o pacote o usuário deve ter instalado em seu computador o compilador NBC. 

**Saiba como em Ubuntu e derivados:** 

  1. Abra um terminal e cole: sudo apt install nbc.
  
  2. Após a instalação siga as instruções deste site (não querendo roubar os créditos dos autores). : http://bricxcc.sourceforge.net/nbc/doc/nxtlinux.txt  OBS: As intruções anteriores configurarão as propriedades USB, apenas é necessário essa configuração, sendo o bluetooth opção do usuário.
  
  3. NBC instalado e conexão USB configurada, agora é possivel utilizar o pacote no Sublime Text 3.
  
  4. Para instalá-lo, você necessitará do Package Control, na parte superior vá em Tools > Install Package Control.
  
  5. Feito isto agora iremos adicionar o repositório do SUBLIME_NXC, ainda na parte superior vá em Prefrences > Package Control > Add Repository e cole o link https://github.com/Gabriel-o-Carvalho/SUBLIME_NXC.git
  
  6. Por fim, basta ir novamente por Preferences > Package Control e agora vá em Install Package. Digite o nome do pacote "SUBLIME_NXC"(sem as aspas) e dê um enter.
  
  7. Ao abrir um arquivo.nxc a syntax será alterada automaticamente, porém o build deve ser selecionado indo em Tools > Build system > NXC_Build.
  
  8. Após isso, com o NXT conectado ao PC, escreva o código e envie-o para o NXT pressionando Ctrl+ B.

*****************************************************************************************************************************

**Saiba como em Windows:** As instruções a seguir possuem embasamento neste site: https://www.java.com/pt_BR/download/help/path.xml

  1. Baixe o compilador nbc para windows do site oficial: http://downloads.sourceforge.net/bricxcc/nbc-1.2.1.r4.zip
  
  2. Extraia e coloque-o em uma pasta a seu gosto.
  
  3. Windows 10 e Windows 8
  
          3.1. Em Pesquisar, procure e selecione: Sistema (Painel de Controle).
          
          3.2. Clique no link Configurações avançadas do sistema.
          
          3.3. Clique em Variáveis de Ambiente. Na seção Variáveis do Sistema, localize a variável de ambiente PATH e selecione-a. Clique em Editar. Se a variável de ambiente PATH não existir, clique em Novo.
          
          3.4. Na janela Editar Variável de Sistema (ou Nova Variável de Sistema), adicione o caminho da pasta do NBC ao PATH e coloque-o como primeiro da lista. Clique em OK. Feche todas as janelas restantes clicando em OK.
          
          3.5. Abra o prompt de comando pressionando Bandeira + R, digitando "cmd"(sem aspas) e pressionando enter.
          
          3.6. Digite no prompt "nbc -help"(sem aspas).
          
          3.7. Caso apareça uma lista de opções de comandos, a operação foi realizada com sucesso.
   4. Windows 7
   
          4.1. Na área de trabalho, clique com o botão direito do mouse no ícone Computador.
          
          4.2. Escolha Propriedades no menu de contexto.
          
          4.3. Clique no link Configurações avançadas do sistema.
          
          4.4. Clique em Variáveis de Ambiente. Na seção Variáveis de Sistema, localize a variável de ambiente PATH e selecione-a. 
          
          4.5. Clique em Editar. Se a variável de ambiente PATH não existir, clique em Novo.
          
          4.6. Na janela Editar Variável de Sistema (ou Nova Variável de Sistema), adicione o caminho da pasta do NBC ao PATH e coloque-o como primeiro da lista. Clique em OK. Feche todas as janelas restantes clicando em OK.
          
          4.7. Abra o prompt de comando pressionando Bandeira + R, digitando "cmd"(sem aspas) e pressionando enter.
          
          4.8. Digite no prompt "nbc -help"(sem aspas).
          
          4.9. Caso apareça uma lista de opções de comandos, a operação foi realizada com sucesso.
          
   5. Agora baixe e instale o driver oficial da lego para comunicação USB com o dispositivo que será programado(EV3, NXT, etc): https://www.lego.com/en-us/mindstorms/downloads
   
   6. Após a instalação, vamos agora instalar o pacote SUBLIME_NXC.
   
   7. Para instalá-lo, você necessitará do Package Control, na parte superior vá em Tools > Install Package Control.
   
   8. Feito isto agora iremos adicionar o repositório do SUBLIME_NXC, ainda na parte superior vá em Prefrences > Package Control > Add Repository e cole o link https://github.com/Gabriel-o-Carvalho/SUBLIME_NXC.git
   
   9. Por fim, basta ir novamente por Preferences > Package Control e agora vá em Install Package. Digite o nome do pacote "SUBLIME_NXC"(sem as aspas) e dê um enter.
   
   10. Ao abrir um arquivo.nxc a syntax será alterada automaticamente, porém o build deve ser selecionado indo em Tools > Build system > NXC_Build.
   
   11. Após isso, com o NXT conectado ao PC, escreva o código e envie-o para o NXT pressionando Ctrl+ B.

          
  ...Estamos trabalhando nisso 😅.
 
  

