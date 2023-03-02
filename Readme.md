Comandos do GITHUB (Desde o primeiro commit até o pull request)

1. O Readme.md é o arquivo de instruções que vai para o GITHUB por exemplo "ESSE PROJETO ENSINA VOCÊ A USAR O GIT"

2. Acessar a pasta que se encontra o seus arquivos que vão para o GITHUB. 

3. Comandos do git que utilizaremos para subir nosso primeiro arquivo são:

    3.1 git init -> Inicia a branch master (nesse momento a pasta .git é criada na pasta)

    3.2 git add -> Adiciona o arquivo que será commitado

    3.3 git status -> Ele mostra os arquivos a serem commitados neste caso o arquivo selecionado

    3.4 git commit -m "Meu primeiro projeto" -> -m é para adicionarmos o titulo do commit

    3.5 git status -> mostra que não há arquivos para comitar

    3.6 git branch -M main -> Para alterar o nome da branch principal de master para main

    3.7 git remote add origin https://github.com/felipesdevops/comandos-git.git -> Remote para conectar nosso repositorio com o do github, add para adicionar, origin o apelido ou nome do repositorio do github. 

    3.8 git push -u origin main -> Dá um empurrão nos commits para o repositorio remoto que foi criado no github

    3.9 Após isso fazer o login para que o push seja executado! Uma mensagem de erro ou sucesso é retornada.

4. git add . -> Para adicionar todos os arquivos da pasta para serem comitados ou manda somente add nome_do_arquivo a ser commitado.

    4.1 git status -> Caso tenha alterado um dos arquivos o git status vai mostrar que foi modificado

    4.2 git push origin main -> O comando remote é adcionado somente uma vez nesse caso só mandar o push na branch main

    















    

