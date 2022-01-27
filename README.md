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


# References

- https://engsoftmoderna.info/capAp.html