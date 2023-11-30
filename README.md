Comandos Git e GitHub

### Configurando o Git

1. **git config --global user.name "Seu Nome"**
   - Define o nome associado aos seus commits.
2. **git config --global user.email "[seu@email.com](mailto:seu@email.com)"**
   - Define o email associado aos seus commits.

### Criando Repositórios

1. **git init**
   - Inicializa um novo repositório Git no diretório atual.
2. **git clone <url-do-repositório>**
   - Clona um repositório a partir de uma URL especificada.

### Fazendo Alterações

1. **git add <nome-do-arquivo>**
   - Adiciona alterações para o próximo commit.
2. **git add .**
   - Adiciona todas as alterações para o próximo commit.
3. **git commit -m "Sua mensagem de commit"**
   - Realiza o commit das alterações adicionadas com uma mensagem descritiva.

### Verificando Status e Diferenças

1. **git status**
   - Mostra o status das alterações como não rastreadas, modificadas ou adicionadas para commit.
2. **git diff**
   - Mostra as diferenças entre o diretório de trabalho e a área de staging.

### Branches e Mesclagem

1. **git branch**
   - Lista todas as branches locais.
2. **git branch <nome-da-branch>**
   - Cria uma nova branch.
3. **git checkout <nome-da-branch>**
   - Muda para uma branch específica.
4. **git merge <nome-da-branch>**
   - Mescla as alterações de uma branch para a branch atual.

### Repositórios Remotos (GitHub)

1. **git remote add origin <url-do-repositório-remoto>**
   - Adiciona um repositório remoto.
2. **git push -u origin <nome-da-branch>**
   - Envia as alterações para um repositório remoto.
3. **git pull origin <nome-da-branch>**
   - Puxa as alterações de um repositório remoto.
4. **git remote -v**
   - Mostra os repositórios remotos associados ao seu repositório local.

### Inspeção do Histórico

1. **git log**
   - Mostra o histórico de commits.
2. **git log --oneline**
   - Mostra um histórico simplificado com uma linha por commit.
3. **git blame <nome-do-arquivo>**
   - Mostra quem fez a última alteração em cada linha de um arquivo.
