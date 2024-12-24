Dicas truques e meus comandos preferidos no GitHub
==================================================

No **Git**, um comando é uma instrução que você usa no terminal para interagir com o repositório. Ele serve para executar ações específicas, como criar um repositório, salvar alterações, visualizar o histórico ou colaborar com outros.

Por exemplo:

*   git init: inicializa um repositório.
*   git add: prepara arquivos para o commit.
*   git commit: salva as alterações no histórico.
*   git push: envia alterações para o repositório remoto.

Esses comandos são como ferramentas para gerenciar o código e o histórico do projeto.

Com vocês as estrelas da festa:

git init
--------

O comando **git init** é usado para inicializar um repositório Git em um diretório. Ele configura o local para começar a rastrear alterações nos arquivos.

Quando você executa **git init**, ele:

1.  Cria uma pasta oculta chamada **.git** no diretório atual.
2.  Prepara o ambiente para controle de versão.

**Exemplo de uso:**

bash

git init

Depois disso, você pode começar a usar comandos do Git, como **git add** e **git commit**, para gerenciar seu projeto.

git add
=======

O comando **git add** é usado para adicionar arquivos ou alterações ao **"staging area"** (área de preparação) no Git. Essa etapa prepara os arquivos para serem incluídos no próximo **commit**.

**Funcionalidade:**

*   Marca os arquivos ou alterações que você deseja salvar no repositório.
*   Não realiza o commit, apenas prepara as mudanças.

**Exemplos de uso:**

1.  **Adicionar um arquivo específico**:

bash

git add arquivo.txt

2.  **Adicionar todos os arquivos e mudanças no diretório atual**:

bash

git add .

3.  **Adicionar um diretório inteiro**:

bash

git add pasta/

Após usar **git add**, você pode executar **git commit** para salvar as alterações no histórico do repositório.

git commit

Um **commit** é como salvar o progresso do seu trabalho no Git. Ele registra as alterações feitas nos arquivos do repositório e cria um ponto no histórico, permitindo que você volte a esse estado no futuro, se necessário.

Cada commit inclui:

*   **Mensagem** que descreve as mudanças.
*   **Identificação** do autor e data.

Pense nele como um "checkpoint" no seu projeto.

git push
========

O comando **git push** é usado para enviar os commits feitos localmente para um repositório remoto, como o GitHub, GitLab ou Bitbucket. Ele sincroniza as alterações do repositório local com o remoto.

**Funcionalidade:**

*   Atualiza o repositório remoto com as mudanças realizadas no repositório local.
*   Geralmente, é usado junto com branches (ramificações).

**Sintaxe básica:**

bash

git push REMOTO BRANCH

*   **REMOTO**: normalmente é chamado de origin (nome padrão do repositório remoto).
*   **BRANCH**: nome da branch que você está enviando (ex.: main ou master).

**Exemplo:**

1.  **Enviar mudanças da branch atual para o repositório remoto**:

bash

git push origin main

2.  **Enviar todas as branches**:

bash

git push --all

**Observação**: Antes de executar o git push, certifique-se de que o repositório remoto foi configurado usando o comando **git remote add origin URL\_DO\_REPOSITORIO**.

1\. Configuração Inicial e importane
====================================

*   **Devemos Configurar um nome de usuário**:

Observação importante:

ü depois de aberto o git-bash, todos os comandos a seguir será digitado ou copiado\\colado

Abrir o git-bash

git config --global user.name "Insira seu Nome de usuário do github"

*   **Configurar e-mail**:

Digite no terminal

git config --global user.email "seuemailqueusanogithub@dominiodeexemplo.com"

*   **Para Ver as configurações atuais**:

comando

git config --list

2\. Inicialização e Configuração do Repositório
===============================================

*   **Inicializar um repositório Git através do git-bash**:

comando

git init

*   **Clonar um repositório remoto**:

comando

git clone URL\_DO\_REPOSITORIO

3\. Verificação do Status e Alterações
======================================

*   **Verificar o status do repositório**:

comando

git status

*   **Exibir as diferenças entre versões**:

comando

git diff

4\. Controle de Arquivos
========================

*   **Adicionar arquivos ao índice (staging area)**:

comando

git add ARQUIVO

(Ou adicionar todos os arquivos:)

comando

git add .

*   **Remover arquivos do índice e repositório**:

comando

git rm ARQUIVO

5\. Commits
===========

*   **Fazer um commit com mensagem**:

comando

git commit -m "Mensagem descritiva"

*   **Fazer commit incluindo arquivos não adicionados**:

comando

git commit -am "Mensagem"

6\. Histórico
=============

*   **Exibir histórico de commits**:

comando

git log

*   **Exibir histórico compacto**:

comando

git log --oneline

7\. Branches (Ramificações)
===========================

*   **Criar uma nova branch**:

comando

git branch NOME\_DA\_BRANCH

*   **Mudar para outra branch**:

comando

git checkout NOME\_DA\_BRANCH

*   **Criar e mudar para nova branch ao mesmo tempo**:

comando

git checkout -b NOME\_DA\_BRANCH

*   **Listar branches existentes**:

comando

git branch

*   **Excluir uma branch**:

comando

git branch -d NOME\_DA\_BRANCH

8\. Mesclagem (Merge)
=====================

*   **Mesclar uma branch à branch atual**:

comando

git merge NOME\_DA\_BRANCH

9\. Repositórios Remotos
========================

*   **Adicionar repositório remoto**:

comando

git remote add origin URL\_DO\_REPOSITORIO

*   **Ver repositórios remotos configurados**:

comando

git remote -v

*   **Enviar mudanças para o repositório remoto**:

comando

git push origin NOME\_DA\_BRANCH

*   **Baixar alterações do repositório remoto**:

comando

git pull origin NOME\_DA\_BRANCH

*   **Clonar repositório remoto**:

comando

git clone URL\_DO\_REPOSITORIO

10\. Revertendo Alterações
==========================

*   **Reverter mudanças locais não adicionadas ao índice**:

comando

git checkout -- ARQUIVO

*   **Remover arquivos do índice mas mantê-los localmente**:

comando

git reset ARQUIVO

*   **Desfazer último commit (mantendo alterações)**:

comando

git reset --soft HEAD~1

*   **Desfazer último commit (removendo alterações)**:

comando

git reset --hard HEAD~1

11\. Outros Comandos Úteis
==========================

*   **Salvar alterações temporariamente (stashing)**:

comando

git stash

*   **Listar stashes salvos**:

comando

git stash list

*   **Aplicar stash salvo**:

comando

git stash apply

*   **Renomear branch atual**:

comando

git branch -m NOVO\_NOME