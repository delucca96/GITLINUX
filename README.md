Comandos básicos GIT:


          Comandos para iniciar um repositório Git:

git init: Inicializa um novo repositório Git.

git clone <URL>: Clona um repositório remoto Git para o diretório local.
  

          Comandos para adicionar e commitar alterações:

git add <arquivo>: Adiciona um arquivo específico ao índice do Git para ser commitado.

git commit -m "<mensagem>": Realiza um commit das mudanças adicionadas ao índice com uma mensagem que descreve o que foi feito.

git commit -a -m "<mensagem>": Realiza um commit de todos os arquivos modificados e já rastreados do repositório, com uma mensagem que descreve o que foi feito.

git status: Exibe o estado atual do repositório Git, mostrando os arquivos modificados, adicionados e não rastreados.
  

          Comandos para visualizar e gerenciar o histórico de commits:

git log: Mostra o histórico de commits do repositório Git.

git log --oneline: Exibe o histórico de commits de forma resumida, em uma única linha.
  

          Comandos para trabalhar com branches:

git branch: Lista todas as branches existentes no repositório.

git branch <nome>: Cria uma nova branch.

git checkout <branch>: Alterna para a branch especificada.

git merge <branch>: Mescla uma branch específica à branch atual.
  

          Comandos para sincronizar com repositórios remotos:

git remote add <nome> <URL>: Adiciona um repositório remoto ao seu projeto Git.

git push <remote> <branch>: Envia as alterações locais para o repositório remoto.

git pull <remote> <branch>: Atualiza o seu repositório local com as alterações mais recentes do repositório remoto.
  

          Outros comandos úteis:

git diff: Mostra as diferenças entre o diretório de trabalho atual e o último commit.

git reset <arquivo>: Remove um arquivo do índice (staging area), mantendo as alterações locais.

git reset --hard: Descarta todas as alterações locais e retorna ao último commit.

git stash: Armazena temporariamente as alterações locais em um stash (esconderijo), permitindo que você as recupere posteriormente.

git remote -v: Lista todos os repositórios remotos configurados para o seu projeto.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

                                                                      ----------- EXEMPLO DE PASSO A PASSO ---------


    mkdir: Cria um novo diretório (pasta).
    Exemplo: mkdir my_folder

    cd: Navega para um diretório específico.
    Exemplo: cd my_folder

    ls: Lista os arquivos e diretórios no diretório atual.
    Exemplo: ls

    git init: Inicializa um novo repositório Git no diretório atual.
    Exemplo: git init

    git remote add: Adiciona um repositório remoto ao seu projeto Git.
    Exemplo: git remote add origin <URL>

    git clone: Clona um repositório remoto Git para o diretório local. Observação: Ao acessar um repositório que requer autenticação por token, você deve incluir o token no URL do repositório.
    Exemplo: git clone https://TOKEN@github.com/seu-usuario/seu-repositorio.git  
         *Dessa forma, ao utilizar o comando git clone, você deve substituir TOKEN pelo seu token de acesso ao repositório. Isso permitirá a autenticação correta durante o processo de clonagem.*

    git status: Exibe o estado atual do repositório Git, mostrando os arquivos modificados, adicionados e não rastreados.
    Exemplo: git status

    git add: Adiciona um arquivo específico ou todas as alterações ao índice do Git para serem commitadas.
    Exemplo: git add file.txt ou git add . (para adicionar todas as alterações)

    git commit: Realiza um commit das mudanças adicionadas ao índice com uma mensagem que descreve o que foi feito.
    Exemplo: git commit -m "Mensagem do commit"

    git push: Envia as alterações locais para o repositório remoto.
    Exemplo: git push origin master

    git pull: Atualiza o seu repositório local com as alterações mais recentes do repositório remoto.
    Exemplo: git pull origin master

          
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Comandos básicos LINUX:

          Comandos de listagem e navegação de diretórios:


 ls: Lista os arquivos e diretórios no diretório atual.
 Exemplo: ls

 cd: Navega para um diretório específico.
 Exemplo: cd Documents

 pwd: Mostra o diretório atual.
 Exemplo: pwd
  

          Comandos de criação e remoção de diretórios:

 mkdir: Cria um novo diretório.
 Exemplo: mkdir my_directory

 rm: Remove um arquivo.
 Exemplo: rm file.txt

 rmdir: Remove um diretório vazio.
 Exemplo: rmdir empty_directory
  

          Comandos de cópia e movimentação de arquivos:

 cp: Copia arquivos e diretórios.
 Exemplo: cp file.txt /path/to/destination

 mv: Move ou renomeia arquivos e diretórios.
 Exemplo: mv file.txt new_location/file_new.txt

  
          Comandos de visualização de arquivos:

 cat: Exibe o conteúdo de um arquivo.
 Exemplo: cat file.txt

 grep: Pesquisa por padrões em um arquivo.
 Exemplo: grep "keyword" file.txt

  
          Comandos de permissões e privilégios:

 chmod: Altera as permissões de um arquivo ou diretório.
 Exemplo: chmod +x script.sh

 sudo: Executa um comando com privilégios de superusuário.
 Exemplo: sudo apt-get update
  

          Comandos de gerenciamento de pacotes e servidores:

 apt-get: Gerenciador de pacotes do Ubuntu para instalar, atualizar ou remover programas.
 Exemplo: sudo apt-get install firefox

 ssh: Acessa um servidor remoto usando o protocolo SSH.
 Exemplo: ssh user@hostname
  

          Comandos de download de arquivos:

 wget: Baixa arquivos da web.
 Exemplo: wget https://example.com/file.txt

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
