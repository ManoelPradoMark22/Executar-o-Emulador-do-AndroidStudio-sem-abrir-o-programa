# Executar-o-Emulador-do-AndroidStudio-sem-abrir-o-programa
Passo a passo simples e rápido!

*Feito no Windows*

Artigo base:
<a href="https://medium.com/@lucasluizss/execute-seu-emulador-android-sem-abrir-o-android-studio-windows-94c826059552">

Corrigindo o artigo base - 

Nas versões mais recentes do AndroidStudio o emulador fica na pasta:
*C:\Users\Nome_Do_Usuário\AppData\Local\Android\Sdk\emulator*

Para ver a lista de emuladores, execute o comando nesse local (cmd):
*C:\Users\Nome_Do_Usuário\AppData\Local\Android\Sdk\emulator>emulator.exe -list-avds*
(Atenção! Exemplo: o nome do meu emulador é Nexus_5X_API_29 , mas, como recomendado no artigo base, deixemos com o x do modelo em minúsculo, assim Nexus_5x_API_29)
Copie o nome do emulador para usar a seguir!

# Opção 1.
Para executar o emulador basta executar esse comando nesse local (cmd):
*C:\Users\Nome_Do_Usuário\AppData\Local\Android\Sdk\emulator>emulator.exe -avd Nome_Do_Emulador*

********************************
# Opção 2. [Recomendado]
*Forma automatizada*
Copie as duas linhas de código a seguir, abra o bloco de notas e cole-as:

cd *"C:\Users\Nome_Do_Usuário\AppData\Local\Android\Sdk\emulator"*
start emulator.exe -avd Nome_Do_Emulador

Clique em Salvar Como, escolha o tipo como arquivo de texto e no nome do arquivo coloque a extensao .bat
ex: emulador.bat

Salve onde preferir e pronto, seu arquivo .bat está pronto.
Agora basta clicar duas vezes sobre ele para executar o emulador sem precisar abrir o AndroidStudio.

# Bônus - Ícone
Para adicionar um ícone ao seu arquivo .bat basta clicar com o botão direito sobre ele e ir em Enviar para Área de trabalho (criar atalho). 
Agora este atalho vai ser o que iremos utilizar!
Clique com o botão direito sobre ele, vá em propriedades. Na aba "atalho" clique em Alterar ícone.
Selecione um ícone de sua preferência ou, se quiser utilizar um ícone próprio, clique em "Procurar..." e selecione o ícone em questão.

# Baixei uma imagem de celular no google e a transformei em ícone para utilizar no meu arquivo .bat, caso queira é só baixar e utilizar no seu também (o ícone se encontra disponível para download neste repositório).
