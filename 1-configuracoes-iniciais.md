# 1. Configurações iniciais

**Obs1:** (Exemplo Windows) Acesse o menu iniciar, localize o ícone do Git Bash, clique com o direito do mouse e em propriedades altere para o local onde normalmente ficam os seus projetos. Exemplo: D:\xampp\htdocs

**Obs2:** No Git Bash a maioria dos comandos são inicializados com $, no entanto são inseridos automaticamente pela ferramenta. Por este motivo ocultei nos exemplos abaixo.

**Obs3:** Não seja tímido(a) peça um help pro Git
git help insira-verb

**1.1 Locomovendo-se pelas pastas do projeto**
```bash
cd nome-da-pasta

cd .. // Retorna 1 nível
```
**1.2 Cadastrando nome de usuário**
```bash
git config --global user.name nome-sobrenome
```
**1.3 Cadastrando email de usuário**
```bash
git config --global user.email email@email.com.br
```
**1.4 Visualiza as configurões de usuário**
```bash
git config -l
```
**1.5 Visualiza as configurões de usuário**
```bash
git config --list
```
**1.6 Verifica versão do git bash**
```bash
git --version
```
