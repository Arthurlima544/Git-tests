# Git-tests

- init e clone:

git clone https://github.com/NOME-USER/NOME-REPO

- add e commit:

    git add arq1 ou git add . // todos arquivos para Stage.

    git commit -m "Alterando o valor de x" // Repositorio local

    git commit -a -m "Alterando valor de x"

    O parâmetro -a no commit diz para adicionar todas as alterações dos arquivos rastreados e enviá-los. assim

    Para remover um arquivo, do repositorio local e do seu workspace:

    git rm arq1.txt
    git commit -m "Removendo arq1.txt"

- Status, DIff e log:

    - Status mostra:
        Arquivos do diretório de trabalho que foram alterados pelo desenvolvedor

        Arquivos do diretório de trabalho que não são rastreados pelo git(sem add)

        Arquivos que encontram-se no index, aguardando um commit.

    - Diff mostra: 
        As modificações realizados nos arquivos do diretório de trabalho e que ainda não foram movidas para o index (ou stage). usamos antes de um add/commit;
    - Log mostra: 
        Ultimos commits.

- Push & Pull:

    - Push :
        push copia os commits mais recentes do repositório local para o repositório remoto.

        git push origin master

        "origin" usado pelo git, para indicar o repositório remoto, por exemplo, o repositório GitHub, e "master" para branch principal.

    - Pull:
        Para atualizar seu repositório local.

        Primeiro, um pull copia os commits mais recentes do repositório central para o repositório local do desenvolvedor. Essa operação inicial é chamada de fetch.

        Em seguida, o comando pull atualiza os arquivos do diretório de trabalho. Essa operação é chamada de merge

- Conflitos de Merge
    Conflitos de merge acontecem quando dois desenvolvedores alteram o mesmo trecho de código ao mesmo tempo

alteração

continua em:
https://www.notion.so/Git-9fb79e3bdd4a4253b8a3d815c81819f6
# References

- https://engsoftmoderna.info/capAp.html