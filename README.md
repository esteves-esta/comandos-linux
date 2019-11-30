# Comandos 
Comandos utéis de linux listados aqui para ficarem mais acessiveis para uso pessoal.

- [Comandos](#comandos)
    - [Atalhos para interface gráfica do linux](#atalhos-para-interface-gr%c3%a1fica-do-linux)
        - [*Mostra arquivos ocultos no nautilus*](#mostra-arquivos-ocultos-no-nautilus)
        - [*Similar a window + r*](#similar-a-window--r)
        - [*Alternar telas*](#alternar-telas)
    - [Comandos terminal](#comandos-terminal)
        - [*Abrir arquivo .appImage*](#abrir-arquivo-appimage)
        - [*diz oque um comando faz*](#diz-oque-um-comando-faz)
        - [*ver histórico de comandos*](#ver-hist%c3%b3rico-de-comandos)
        - [*Criar atalhos para comandos*](#criar-atalhos-para-comandos)
        - [*Editar arquivos no terminal*](#editar-arquivos-no-terminal)
        - [*Mostrar ip da máquina*](#mostrar-ip-da-m%c3%a1quina)
        - [*comprime ou expande arquivo*](#comprime-ou-expande-arquivo)
        - [*Mostra arquivo comprimido*](#mostra-arquivo-comprimido)
        - [*Mostra processos suspensos*](#mostra-processos-suspensos)
        - [*Matar processos*](#matar-processos)
    - [APT-GET](#apt-get)
        - [*Atualiza indice do repositorio*](#atualiza-indice-do-repositorio)
        - [*Instalar pacote/aplicativo*](#instalar-pacoteaplicativo)
        - [*Atualiza pacotes com tratamento automatico de dependências*](#atualiza-pacotes-com-tratamento-automatico-de-depend%c3%aancias)
        - [*Limpar cache do apt-get*](#limpar-cache-do-apt-get)
        - [*Forçar arrumar pacotes quebrados*](#for%c3%a7ar-arrumar-pacotes-quebrados)
        - [*Procura pelo programa*](#procura-pelo-programa)
        - [*Mostra detalhes do pacote*](#mostra-detalhes-do-pacote)
        - [*Lista pacotes com críterios*](#lista-pacotes-com-cr%c3%adterios)
        - [*Remove pacote*](#remove-pacote)
        - [*Remove pacote com configuração*](#remove-pacote-com-configura%c3%a7%c3%a3o)
        - [*Remove pacotes indesejados*](#remove-pacotes-indesejados)
        - [*Desinstalar aplicativos*](#desinstalar-aplicativos)
    - [Arquivos .deb](#arquivos-deb)
        - [*Descompactar arquivo .deb*](#descompactar-arquivo-deb)
        - [*In case dpkg complains about missing dependencies, run:*](#in-case-dpkg-complains-about-missing-dependencies-run)
    - [Comandos gerais](#comandos-gerais)
        - [*Exibir arquivo no terminal*](#exibir-arquivo-no-terminal)
        - [*Criar arquivo vazio*](#criar-arquivo-vazio)
        - [*Novo diretorio*](#novo-diretorio)
        - [*Remover arquivo*](#remover-arquivo)
        - [*Copiar arquivo*](#copiar-arquivo)
        - [*Mover arquivo*](#mover-arquivo)
        - [*Comparar dois arquivos*](#comparar-dois-arquivos)
        - [*Encontrar arquivo*](#encontrar-arquivo)
        - [*Programas em execução e seu consumo de hardware*](#programas-em-execu%c3%a7%c3%a3o-e-seu-consumo-de-hardware)
        - [*Muda protecao de arquivo*](#muda-protecao-de-arquivo)
        - [*Muda dono ou grupo de um arquivo(change owner)*](#muda-dono-ou-grupo-de-um-arquivochange-owner)
        - [*Muda grupo de um arquivo*](#muda-grupo-de-um-arquivo)
        - [*Procura um arquivo por um padrão*](#procura-um-arquivo-por-um-padr%c3%a3o)
        - [*Exibe variáveis de ambiente*](#exibe-vari%c3%a1veis-de-ambiente)
        - [*Define variáveis da sessão do shell*](#define-vari%c3%a1veis-da-sess%c3%a3o-do-shell)
        - [*Total de palavras*](#total-de-palavras)
        - [*Calendario no terminal*](#calendario-no-terminal)
        - [*Mostra data atual*](#mostra-data-atual)
    - [React Native](#react-native)
        - [*Comandos usados para lidar com problemas no watchman*](#comandos-usados-para-lidar-com-problemas-no-watchman)

---

### Atalhos para interface gráfica do linux

##### *Mostra arquivos ocultos no nautilus*
    ctl + H

##### *Similar a window + r*
    alt + F2

##### *Alternar telas*
    alt + ESC

---

### Comandos terminal

##### *Abrir arquivo .appImage*
    chmod u+x arquivo.AppImage

##### *diz oque um comando faz*
    whatis comando
    
##### *ver histórico de comandos*
    history

##### *Criar atalhos para comandos*
    alias nomeAtalho="comando completo"

##### *Editar arquivos no terminal*

    nano caminho/nome-do-arquivo

##### *Mostrar ip da máquina*

    ip addr show

##### *comprime ou expande arquivo*
    gzip
    
##### *Mostra arquivo comprimido*
    zcat

##### *Mostra processos suspensos*
    jobs

##### *Matar processos*
    kill -9 100

---

### APT-GET

##### *Atualiza indice do repositorio*
    sudo apt update

##### *Instalar pacote/aplicativo*
    sudo apt-get install NOME

##### *Atualiza pacotes com tratamento automatico de dependências*
    sudo apt full-upgrade

##### *Limpar cache do apt-get*
    sudo apt-get autoclean

##### *Forçar arrumar pacotes quebrados*
    sudo apt-get install -f

##### *Procura pelo programa*
    apt search

##### *Mostra detalhes do pacote*
    apt show

##### *Lista pacotes com críterios*
    sudo apt list

##### *Remove pacote*
    sudo apt remove NOME

##### *Remove pacote com configuração*
    sudo apt purge NOME

##### *Remove pacotes indesejados*
    sudo apt autoremove

##### *Desinstalar aplicativos*
    sudo apt-get purge firefox

----

### Arquivos .deb

##### *Descompactar arquivo .deb*
    sudo dpkg -i ~/path/to/code_1.XXX.deb

##### *In case dpkg complains about missing dependencies, run:*
    sudo apt -f install

--------

### Comandos gerais


##### *Exibir arquivo no terminal*
    cat

##### *Criar arquivo vazio*
    touch nomearquivo

##### *Novo diretorio*
    mkdir novapasta

##### *Remover arquivo*
    rm nome

##### *Copiar arquivo*
    cp nome

##### *Mover arquivo*
    mv nome

##### *Comparar dois arquivos*
    cmp arquivo arquivo2

##### *Encontrar arquivo*
    locate nome

##### *Programas em execução e seu consumo de hardware*
    top

##### *Muda protecao de arquivo*
    chmod

##### *Muda dono ou grupo de um arquivo(change owner)*
    chown

##### *Muda grupo de um arquivo*
    chgrp

##### *Procura um arquivo por um padrão*
    grep

##### *Exibe variáveis de ambiente*
    env (ou printenv)

##### *Define variáveis da sessão do shell*
    set

##### *Total de palavras*
    wc nomearquivo.txt

##### *Calendario no terminal*
    cal

##### *Mostra data atual*
    date

---

### React Native

##### *Comandos usados para lidar com problemas no watchman*
    watchman watch-del-all

    watchman shutdown-server

    echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_user_watches && echo 999999 | sudo tee -a /proc/sys/fs/inotify/max_queued_events && echo 999999 | sudo tee -a /proc/sys/fs/inotify/  max_user_instances && watchman shutdown-server && sudo sysctl -p

---