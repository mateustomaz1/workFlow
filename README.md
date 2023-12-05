# workFlow
ATIVIDADE DE FIXAÇÃO

# Inicialização de um Repositório Git

Aqui estão as etapas para inicializar um repositório Git:

## Instalação do Git
Antes de tudo, você precisa ter o Git instalado em seu computador. Se ainda não o fez, você pode baixá-lo do site oficial do Git.

## Criação de um novo repositório
1. Abra o terminal.
2. Navegue até o diretório onde você deseja criar o repositório. Por exemplo, se você deseja criar um repositório em um diretório chamado `meu-projeto`, você pode fazer isso com o comando `cd caminho/para/o/diretório/meu-projeto`.
3. Digite `git init`. Isso criará um novo repositório Git no diretório atual.

## Adição de arquivos ao repositório
1. Para adicionar arquivos ao repositório, você pode usar o comando `git add`. Por exemplo, `git add README.md` adicionará o arquivo README.md ao repositório. Se você deseja adicionar todos os arquivos do diretório, você pode usar `git add .`.
2. Depois de adicionar os arquivos, você precisa confirmar as alterações com `git commit`. Por exemplo, `git commit -m "mensagem de commit"`.

## Conexão do repositório local a um repositório remoto
1. No GitHub (ou qualquer outro serviço de hospedagem de Git), crie um novo repositório.
2. No terminal, adicione o URL do repositório remoto com `git remote add origin url-do-repositório-remoto`.
3. Agora você pode enviar suas alterações para o repositório remoto com `git push -u origin master`.

E é isso! Você criou e inicializou com sucesso um repositório Git. Lembre-se de que o Git é uma ferramenta poderosa com muitos outros recursos, então sinta-se à vontade para explorar mais!