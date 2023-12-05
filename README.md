# O que é WorkFlow git
ATIVIDADE DE FIXAÇÃO

 Tomaz
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

O termo "workflow Git" se refere aos processos e fluxos de trabalho envolvidos no gerenciamento de código usando o sistema de controle de versão Git. O Git é uma ferramenta amplamente utilizada no desenvolvimento de software para controlar as alterações no código-fonte ao longo do tempo.

Um workflow Git descreve como as pessoas e equipes colaboram no desenvolvimento de um projeto, como as ramificações (branches) são criadas e gerenciadas, como as alterações são integradas (merge) e como as versões finais são distribuídas. Existem vários modelos de workflow Git, cada um com suas próprias práticas e convenções:

**Git Flow:** Este é um dos workflows mais populares, com uma estrutura clara para criar branches dedicadas para recursos, desenvolvimento, correções e versões.

**GitHub Flow:** Mais simples que o Git Flow, este workflow incentiva atualizações frequentes no repositório principal, usando principalmente uma branch principal (geralmente 'main') e branches temporárias para features ou correções.

**GitLab Flow:** Similar ao GitHub Flow, este modelo incorpora etapas adicionais para testes automatizados e integração contínua antes de mesclar as alterações na branch principal.

**GitLab Workflow:** Especificamente projetado para o GitLab, este modelo inclui elementos do GitLab CI/CD (Continuous Integration/Continuous Deployment), focando na automação de testes e implantação.

Cada workflow Git tem suas vantagens e é mais adequado para diferentes contextos e equipes. A escolha do workflow depende das necessidades do projeto, da estrutura da equipe e das preferências de desenvolvimento.
