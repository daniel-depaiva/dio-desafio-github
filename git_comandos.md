# Lista de Comandos para uso do GIT

+ para ver a versão do   {git --version}

+ para iniciar o git em um projeto git init

+ ver status dos arquivos git status

+ para add um arquivo git add name do arquivo, ou para add todo o conteudo do diretorio git add .

+ para commit, git commit -m "mensagem para o commit"

+ configuração do git,  git config  --list

+ configurando seu user no git  git config --global user.name "joão teste"
  Configurando email  git config --global user.email "joao@teste.com"

+ conectado no projeto git remote add origin URL do Projeto

+ push apenas git push

## Git Logs

+ git reflog  = para ve os logs

+ para ver somente as mensagem do commit git log  --pretty=oneline

+ mostra ultima linha do log  git log  --pretty=oneline -1

+ mostra algumas informações do commits realizados git log  --stat  

+ retirando um arquivo da area de stage, git reset HEAD dante.txt
  voltando o arquivo para versão antes do commit, git checkout dante.txt

+ voltando versão no Git 

+ Git reset --hard ID da versão

### Links utéis para uso

[Documentação da Linguagem Markdown](https://www.markdownguide.org/)

[Documenta do GIt](https://comandosgit.github.io/)
