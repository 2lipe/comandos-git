# 7. Trabalhando com Git e GitHub

**1 Gerando uma chave SSH de autenticação no Git bash**
```bash
// O git irá lhe perguntar: "nome de arquivo" e "senha", aplique 2 enters e ignore se for conveniente
ssh-keygen

// Normalmente o Git gera essa chave numa pasta dentre de Meus Documentos

Abra o arquivo ".ssh > id_rsa" e copie a chave
```

**2 Verificar se existe chave SSH configurada**
```bash
ls -al ~/.ssh
```

**2 Configurando a chave SSH no GitHub**
```bash
// Insira um nome para identificar a sua máquina no Github

// No Github vá em "Settings > SSH Keys" (Title + Key)
```

**3 Crie um repositorio no GitHub**
```bash
Acesse "Repositories" > New
```

**4 Clonando o repositório para a sua máquina**
```bash
No Github copie a URL SSH

No gitBash (git clone + insert nomeOpcional)
```

**5 Inserir caminho do repositorio remoto**
```bash
git remote add origin
```

**6 Verificar caminho do repositorio remoto que está setado**
```bash
git remote -v
```

**7 Altera a url do repositório remoto (Máquina local > Github)**
```bash
git remote set-url origin url-repositorio
```

**8 Enviando as modificações para o GitHub**
```bash
git push origin master
```

**9 Deletando branch remota**
```bash
git push origin nome-branch --delete
git push origin :nome-da-branch
```

**10 Baixando as modificações do GitHub para a sua máquina** (Se o repositório for de sua autoria)
```bash
git pull origin master
```

**11 Mantendo o Repositório Forkado atualizado com o original** (Para repositórios forkados)
```bash
// Nesse momento o nosso repositório chama-se origin;
// Vamos criar um novo chamado "upstream" que apontará para o original.

git remote add upstream insira-url-ssh-do-repositorio-original
```

**12 Sincronizando os dois repositórios** (upstream e original)
```bash
git fetch upstream
```

**13 Aplicando merge nas atualizações do fork para a branch master do nosso repositório**
```bash
git merge upstream/master
```

**14 Fechar issues através de commits**
```bash
git commit -m "Mensagem commit - fix ou resolve IDissue"
```
