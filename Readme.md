# Github
- Comandos para git
- Testes de versionamento

$ git init 
> Iniciliza o repositório na sua máquina.

$ git status
> Exibe informações sobre os estados dos arquivos.

$ git add 
> Adiciona os arquivos e/ou alterações realizadas nos arquivos.

$ git commit -m
> Envia o commit. 
> A flag -m indica que sera passado uma msg.

$ git commit -am
> Possibilita que vc adcione e commit ao msm tempo.

$ git log
> Exibe as informaçõe sobre todas os commits enviados, como autor, hora, hash do commit e etc...

$ git log --graph
> Exibe um grafico dos de alteraçõe.

$ git shortlog
> Mostra o nome dos autores seus respectivos commits.

$ git shortlog -sn
> Mostra quantos commits cada autor realizou.

$ git show *HASH*
> Exibe as informações sobre um determinado commit, exibindo o que foi adcionado.

$ git diff
> Exibe as alterações realizadas nos arquivos antes de serem versionadas.

$ git checkout "Nome do arquivo"
> Desfaz as alterações antes que o arquivo seja adicionado.

$ git reset HEAD "Name do arquivo"
> Esse comando serve para remover um arquivo da fila de staged... ou seja, ele volta para o estado em que o arquivo ainda nao foi adcionado.

$ git reset --soft
> Mata o commit e volta para a fila de staged... ou seja, o commit vai ser apagado, mas o arquivo ira continiar pronto para ser commitado com as alteraçõe feitas. Obs: Nessa parte o aquivo ja foi adicionado mas não commitado.

$ git reset --mixed
> Deleta o commit r volta para a estado antes do staged... entao nesse caso o arquico ainda materá as alterações, mas sera preciso realizar os comando git add e git commit -m.

$ git reset --hard
> Este é o reset mais hardcore, pois ele exclui o commit e as alterações realizadas no arquivo por esse commit.

>>>> OBS: Para cada um dos commando reset é necessário informar o HASH da versão que vc deseja voltar, lembrando que as alteraçõe e exclusões serão realizadas em todos os commits feitos depois do commit informado.
