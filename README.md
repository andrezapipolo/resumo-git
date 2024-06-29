
# Gitbash

## Terminologia do Git


<p align="justify">Árvore de trabalho: o conjunto de diretórios e arquivos aninhados que contém o projeto no qual está sendo feito o trabalho.

Repositório: o diretório, localizado no nível superior de uma árvore de trabalho, no qual o Git mantém todo o histórico e os metadados de um projeto. Os repositórios são quase sempre chamados de repositórios.

Hash: um número produzido por uma função de hash que representa o conteúdo de um arquivo ou de outro objeto como um número fixo de dígitos. O Git usa hashes que têm 160 bits de comprimento.

Objeto: um repositório Git contém quatro tipos de objetos, cada um exclusivamente identificado por um hash SHA-1. Um objeto de blob contém um arquivo comum. Um objeto de árvore representa um diretório; ele contém nomes, hashes e permissões. Um objeto de commit representa uma versão específica da árvore de trabalho. Uma marca é um nome anexado a um commit.

Commit: quando usado com o verbo fazer, commit significa fazer um objeto de commit. Essa ação recebe o nome dos commits feitos em um banco de dados. Isso significa que você está fazendo commit das alterações feitas, de modo que outras pessoas possam acabar vendo-as também.

Branch: um branch é uma série nomeada de commits vinculados. O commit mais recente em um branch é chamado de principal. A ramificação padrão, que é criada quando você inicializa um repositório, é chamada de main, em geral com o nome master no Git. O principal do branch atual é chamado de HEAD. Os branches são um recurso incrivelmente útil do Git, pois permitem que os desenvolvedores trabalhem de modo independente (ou em conjunto) nos branches e, posteriormente, mesclem as alterações no branch padrão.

Repositório remoto: um repositório remoto é uma referência nomeada a outro repositório Git. Quando você cria um repositório, o Git cria um repositório remoto chamado origin, que é o repositório remoto padrão das operações de push e pull.


Comandos, subcomandos e opções: as operações do Git são executadas por meio de comandos como git push e git pull. git é o comando e push ou pull é o subcomando. O subcomando especifica a operação que você deseja que o Git execute. Os comandos são frequentemente acompanhados por opções, que usam hifens (-) ou hifens duplos (--). Por exemplo, git reset --hard.</p>


## Comandos Gitbash

git --version = para verificar qual versão do Git está instalado

git config --global user.name "<USER_NAME>" = Substitua <USER_NAME> pelo nome de usuário que deseja usar.Para configurar o Git, é necessário definir algumas variáveis globais: user.name e user.email. As duas são necessárias para fazer commits.

git config --global user.email "<USER_EMAIL>" = Substitua <USER_EMAIL> pelo seu endereço de email

git config --list =  comando para verificar se as alterações funcionaram

mkdir <NOME DA PASTA> = Comando para criar uma pasta, Substitua <NOME DA PASTA> para o nome da pasta que você desejar

cd <NOME DA PASTA> = Comando para Alterar o diretório(pasta) do projeto

git init = Comando para iniciar o repositório 

ls - comando para mostrar o que tem dentro do diretório

ctrl + L = limpa o terminal

git clone <LINK REPOSITORIO> - para clonar um projeto

git clone <LINK REPOSITORIO> <NOME DA NOVA PASTA> -  clonar projeto dentro de outra pasta da sua escolha

git remote -v - para mostrar os repositorios que está veiculados 

cd .. - para voltar uma pasta no terminal 

git status - mostra o status da branch

touch README.md - cria o readme

git log - historico dos commits

git restore <nome do arquivo> - o git restaura o erro feito
	
git commit --amend -m"nome que vc desejar" - para alterar o nome do commit sem alterar o arquivo

