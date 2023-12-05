# workFlow
ATIVIDADE DE FIXAÇÃO

#OsPrincipaisComandos

**Configuração Inicial:**

git config --global user.name "Seu Nome": Configura o nome do usuário.
git config --global user.email "seu@email.com": Configura o email do usuário.

**Criar e Clonar Repositório:**
git init: Inicia um novo repositório local.
git clone <url_do_repositorio>: Clona um repositório remoto.

**Trabalhar com Alterações Locais:**
git status: Verifica o estado do repositório.
git add <nome_do_arquivo>: Adiciona alterações para o stage.
git commit -m "Mensagem de commit": Confirma as alterações.

**Branches:**
git branch <nome_da_branch>: Cria uma nova branch.
git checkout <nome_da_branch>: Troca para uma branch existente.
git checkout -b <nome_da_branch>: Cria e troca para uma nova branch.

**Sincronização com Repositório Remoto:**
git remote add origin <url_do_repositorio>: Adiciona um repositório remoto.
git push -u origin <nome_da_branch>: Envia alterações para o repositório remoto.
git pull: Atualiza o repositório local com as mudanças remotas.

**Merge e Rebase:**
git merge <nome_da_branch>: Realiza o merge de uma branch.
git rebase <nome_da_branch>: Realiza o rebase de uma branch.

**Desfazer Alterações Locais:**
git restore <nome_do_arquivo>: Desfaz alterações não cometidas.
git reset HEAD~1: Desfaz o último commit mantendo alterações locais.
git reset --hard HEAD~1: Desfaz o último commit descartando alterações locais.

