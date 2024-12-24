# gitdicas

Dicas truques e meus comandos preferidos no GitHub

No Git, um comando é uma instrução que você usa no terminal para interagir com o repositório. Ele serve para executar ações específicas, como criar um repositório, salvar alterações, visualizar o histórico ou colaborar com outros.
Por exemplo:
•	git init: inicializa um repositório.
•	git add: prepara arquivos para o commit.
•	git commit: salva as alterações no histórico.
•	git push: envia alterações para o repositório remoto.
Esses comandos são como ferramentas para gerenciar o código e o histórico do projeto.


Com vocês, as estrelas da festa:
git init

O comando git init é usado para inicializar um repositório Git em um diretório. Ele configura o local para começar a rastrear alterações nos arquivos.
Quando você executa git init, ele:
1.	Cria uma pasta oculta chamada .git no diretório atual.
2.	Prepara o ambiente para controle de versão.
Exemplo de uso:
bash

git init
Depois disso, você pode começar a usar comandos do Git, como git add e git commit, para gerenciar seu projeto.


git add

O comando git add é usado para adicionar arquivos ou alterações ao "staging area" (área de preparação) no Git. Essa etapa prepara os arquivos para serem incluídos no próximo commit.
Funcionalidade:
•	Marca os arquivos ou alterações que você deseja salvar no repositório.
•	Não realiza o commit, apenas prepara as mudanças.
Exemplos de uso:
1.	Adicionar um arquivo específico:
bash

git add arquivo.txt
2.	Adicionar todos os arquivos e mudanças no diretório atual:
bash

git add .
3.	Adicionar um diretório inteiro:
bash

git add pasta/
Após usar git add, você pode executar git commit para salvar as alterações no histórico do repositório.


git commit
Um commit é como salvar o progresso do seu trabalho no Git. Ele registra as alterações feitas nos arquivos do repositório e cria um ponto no histórico, permitindo que você volte a esse estado no futuro, se necessário.
Cada commit inclui:
•	Mensagem que descreve as mudanças.
•	Identificação do autor e data.
Pense nele como um "checkpoint" no seu projeto.

git push

O comando git push é usado para enviar os commits feitos localmente para um repositório remoto, como o GitHub, GitLab ou Bitbucket. Ele sincroniza as alterações do repositório local com o remoto.
Funcionalidade:
•	Atualiza o repositório remoto com as mudanças realizadas no repositório local.
•	Geralmente, é usado junto com branches (ramificações).
Sintaxe básica:
bash

git push REMOTO BRANCH
•	REMOTO: normalmente é chamado de origin (nome padrão do repositório remoto).
•	BRANCH: nome da branch que você está enviando (ex.: main ou master).
Exemplo:
1.	Enviar mudanças da branch atual para o repositório remoto:
bash

git push origin main
2.	Enviar todas as branches:
bash

git push --all
Observação: Antes de executar o git push, certifique-se de que o repositório remoto foi configurado usando o comando git remote add origin URL_DO_REPOSITORIO.

