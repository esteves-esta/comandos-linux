# comandos-linux
Comandos utéis de linux que uso diariamente

## React Native

### watchman
- `watchman watch-del-all`
- 
- `watchman shutdown-server`

- `echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_watches && echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_queued_events && echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_instances && watchman shutdown-server && sudo sysctl -p`

---

## Comandos + usados

### abrir arquivo .appImage

`chmod u+x arquivo.AppImage`

#### criar atalhos indo no arquivo .bashrc na pasta pessoal e adicionando uma nova linha como:

`alias atalho="comando completo"`

`source .bashrc`

### editar arquivos no terminal

`nano caminho/nome-do-arquivo`

### ip

`ip addr show`

## Instala pacote/aplicativo

`sudo apt-get install NOME`

## Remove pacote

`sudo apt remove NOME`

## Remove pacote com configuração

`sudo apt purge NOME`

## Atualiza indice do repositorio

`sudo apt update`

## Remove pacotes indesejados

`sudo apt autoremove`

## Atualiza pacotes com tratamento automatico de dependências

`sudo apt full-upgrade`

### limpar cache do apt-get

`sudo apt-get autoclean`

### para consertar pacotes quebrados

`sudo apt-get install -f`


## Procura pelo programa

`apt search`

## Mostra detalhes do pacote

`apt show`

## Lista pacotes com críterios

`sudo apt list`

## Desinstalar aplicativos

`sudo apt-get purge firefox`

## Descompactar arquivo .deb

`sudo dpkg -i ~/path/to/code_1.XXX.deb`

### In case dpkg complains about missing dependencies, run:

`sudo apt -f install`

## Ferramentas de tranferencia de dados curl (client URL ) and wget 
`wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash``



--------

## Comandos gerais


### diz oque um comando faz

`whatis comando`

### manual

`man nome-do-comando`

## Mostra espaço disponivel em cada partição do sitema 

`df-h`

### exibir arquivo no terminal

`cat`

### criar arquivo vazio

`touch nome`

### ver histórico de comandos

`history`

### novo diretorio

`mkdir novapasta`

### remover arquivo

`rm nome`

## copiar arquivo

`cp nome`

### mover arquivo

`mv nome`

### comparar dois arquivos

`cmp arquivo arquivo2`

### ver uso da memoria

`free`

### encontrar arquivo

`locate nome`

### calendario no terminal

`cal`

### mostra data atual date

`date`

### programas em execução e seu consumo de hardware

`top`

### muda protecao de arquivo

`chmod`

### muda dono ou grupo de um arquivo(change owner)

`chown`

### muda grupo de um arquivo

`chgrp`

### procura um arquivo por um paddrão

`grep`

### comprime ou expande arquivo

`gzip`

### list open files

`lsof`

### word count

`wc`

### mostra arquivo comprimido

`zcat`

### mostra estado da rede

`netstat`

### ver jobs em execução

`jobs`

### matar processos/jobs

`kill -9 100`

### exebe variáveis de ambiente

`env (ou printenv)`

### define variáveis da sessão do shell

`set`

### similar a window + r

`alt + F2`

### alternar telas 

`alt + ESC`

### mostra arquivos ocultos

`ctl + H`

