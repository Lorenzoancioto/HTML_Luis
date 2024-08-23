Explicação dos comandos usados para subir o código no Github.
'Git-init': Inicializa um repositório vazio quando você está começando um novo projeto e quer usar o controle de versão do Git.
'Git add README.md': Adiciona o arquivo 'README.md' ao índice do Git para que quando quiser incluir alterações no commit usa este comando
'Git commit -m "first commit"':  Cria um novo commit com uma mensagem descritiva, para usa-lo precisa anteriormente ter adicionado ao "git-add".
'Git branch -M main': Renomeia a branch atual para main, o -M força a renomeação, mesmo que já exista uma branch com o nome main, após inicializar o repositório, se você quiser usar main como o nome da branch principal em vez de master use este comando.
'Git remote add origin https://github.com/Lorenzoancioto/teste.git': Adiciona um repositório remoto chamado origin com a URL especificada, você configura o repositório remoto no seu repositório local com este comando.
'Git push -u origin main': Envia os commits da branch main do seu repositório local para o repositório remoto chamado origin. A opção -u define a branch main do repositório remoto como a branch de rastreamento padrão para a branch local main. Depois de fazer commits e querer compartilhar essas alterações com o repositório remoto, você usa este comando para enviar suas alterações para o GitHub (ou outro serviço de hospedagem de código).

Falando sobre a criação de branchs:
Como esta atividade foi muito simples não houve a necessidade de cirar branchs, no caso desta atividade só houve um único commit.
