<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dicas, Truques e Meus Comandos Preferidos no GitHub</title>
</head>
<body>
    <h1>Dicas, Truques e Meus Comandos Preferidos no GitHub</h1>
    
    <p>No Git, um comando é uma instrução que você usa no terminal para interagir com o repositório. Ele serve para executar ações específicas, como criar um repositório, salvar alterações, visualizar o histórico ou colaborar com outros.</p>
    
    <p><strong>Por exemplo:</strong></p>
    <ul>
        <li><code>git init</code>: inicializa um repositório.</li>
        <li><code>git add</code>: prepara arquivos para o commit.</li>
        <li><code>git commit</code>: salva as alterações no histórico.</li>
        <li><code>git push</code>: envia alterações para o repositório remoto.</li>
    </ul>
    <p>Esses comandos são como ferramentas para gerenciar o código e o histórico do projeto.</p>
    
    <h2>Com vocês as estrelas da festa:</h2>
    
    <h3><code>git init</code></h3>
    <p>O comando <code>git init</code> é usado para inicializar um repositório Git em um diretório. Ele configura o local para começar a rastrear alterações nos arquivos.</p>
    
    <p>Quando você executa <code>git init</code>, ele:</p>
    <ul>
        <li>Cria uma pasta oculta chamada <code>.git</code> no diretório atual.</li>
        <li>Prepara o ambiente para controle de versão.</li>
    </ul>
    
    <p><strong>Exemplo de uso:</strong></p>
    <pre><code>git init</code></pre>
    <p>Depois disso, você pode começar a usar comandos do Git, como <code>git add</code> e <code>git commit</code>, para gerenciar seu projeto.</p>
    
    <h3><code>git add</code></h3>
    <p>O comando <code>git add</code> é usado para adicionar arquivos ou alterações ao <em>"staging area"</em> (área de preparação) no Git. Essa etapa prepara os arquivos para serem incluídos no próximo commit.</p>
    
    <p><strong>Funcionalidade:</strong></p>
    <ul>
        <li>Marca os arquivos ou alterações que você deseja salvar no repositório.</li>
        <li>Não realiza o commit, apenas prepara as mudanças.</li>
    </ul>
    
    <p><strong>Exemplos de uso:</strong></p>
    <ul>
        <li><strong>Adicionar um arquivo específico:</strong></li>
        <pre><code>git add arquivo.txt</code></pre>
        
        <li><strong>Adicionar todos os arquivos e mudanças no diretório atual:</strong></li>
        <pre><code>git add .</code></pre>
        
        <li><strong>Adicionar um diretório inteiro:</strong></li>
        <pre><code>git add pasta/</code></pre>
    </ul>
    
    <p>Após usar <code>git add</code>, você pode executar <code>git commit</code> para salvar as alterações no histórico do repositório.</p>
    
    <h3><code>git commit</code></h3>
    <p>Um <strong>commit</strong> é como salvar o progresso do seu trabalho no Git. Ele registra as alterações feitas nos arquivos do repositório e cria um ponto no histórico, permitindo que você volte a esse estado no futuro, se necessário.</p>
    
    <p>Cada commit inclui:</p>
    <ul>
        <li><strong>Mensagem</strong> que descreve as mudanças.</li>
        <li><strong>Identificação</strong> do autor e data.</li>
    </ul>
    <p>Pense nele como um "checkpoint" no seu projeto.</p>
    
    <h3><code>git push</code></h3>
    <p>O comando <code>git push</code> é usado para enviar os commits feitos localmente para um repositório remoto, como o GitHub, GitLab ou Bitbucket. Ele sincroniza as alterações do repositório local com o remoto.</p>
    
    <p><strong>Funcionalidade:</strong></p>
    <ul>
        <li>Atualiza o repositório remoto com as mudanças realizadas no repositório local.</li>
        <li>Geralmente, é usado junto com branches (ramificações).</li>
    </ul>
    
    <p><strong>Sintaxe básica:</strong></p>
    <pre><code>git push REMOTO BRANCH</code></pre>
    
    <p><strong>REMOTO:</strong> normalmente é chamado de <code>origin</code> (nome padrão do repositório remoto).</p>
    <p><strong>BRANCH:</strong> nome da branch que você está enviando (ex.: <code>main</code> ou <code>master</code>).</p>
    
    <p><strong>Exemplo:</strong></p>
    <ul>
        <li><strong>Enviar mudanças da branch atual para o repositório remoto:</strong></li>
        <pre><code>git push origin main</code></pre>
        
        <li><strong>Enviar todas as branches:</strong></li>
        <pre><code>git push --all</code></pre>
    </ul>
    
    <p><strong>Observação:</strong> Antes de executar o <code>git push</code>, certifique-se de que o repositório remoto foi configurado usando o comando <code>git remote add origin URL_DO_REPOSITORIO</code>.</p>
</body>
</html>
