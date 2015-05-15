##### 1. Configurações iniciais

Obs1: (Exemplo Windows) Acesse o menu iniciar, localize o ícone do Git Bash, clique com o direito do mouse e em propriedades altere para o local onde normalmente ficam os seus projetos. 
Exemplo: D:\xampp\htdocs 

Obs2: No Git Bash a maioria dos comandos são inicializados com $, no entanto são inseridos automaticamente pela ferramenta. Por este motivo ocultei nos exemplos abaixo.

Obs3: Não seja tímido(a) peça um help pro Git
git help <verb>
// _exemplos_
git help commit
git help branch

##### 1.1 Locomovendo-se pelas pastas do projeto
// _Acessa uma pasta especifica_

cd nome-da-pasta
cd nome-da-pasta/nome-da-pasta

// _Retorna 1 nível_
cd ..

##### 1.2 Cadastrando nome de usuário
git config --global user.name nome-sobrenome

##### 1.3 Cadastrando email de usuário
git config --global user.email email@email.com.br

##### 1.4 Visualizar as configurões de usuário
git config --list