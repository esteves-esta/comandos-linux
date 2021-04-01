# Comandos 
Comandos utéis de linux listados aqui para ficarem mais acessiveis para uso pessoal.

- [Comandos](#comandos)
    - [Atalhos para interface gráfica do linux](#atalhos-para-interface-gr%c3%a1fica-do-linux)
        - [*Mostra arquivos ocultos no nautilus*](#mostra-arquivos-ocultos-no-nautilus)
        - [*Similar a window + r*](#similar-a-window--r)
        - [*Alternar telas*](#alternar-telas)
    - [Comandos terminal](#comandos-terminal)
        - [*Mostra caminho do diretorio atual*](#mostra-caminho-do-diretorio-atual)
        - [*Abrir arquivo .appImage*](#abrir-arquivo-appimage)
        - [*Abrir arquivo executável*](#abrir-arquivo-execut%c3%a1vel)
        - [*Diz oque um comando faz*](#diz-oque-um-comando-faz)
        - [*Ver histórico de comandos*](#ver-hist%c3%b3rico-de-comandos)
        - [*Criar atalhos para comandos*](#criar-atalhos-para-comandos)
        - [*Editar arquivos no terminal*](#editar-arquivos-no-terminal)
        - [*Mostrar ip da máquina*](#mostrar-ip-da-m%c3%a1quina)
        - [*Comprime ou expande arquivo*](#comprime-ou-expande-arquivo)
        - [*Mostra arquivo comprimido*](#mostra-arquivo-comprimido)
        - [*Mostra processos suspensos*](#mostra-processos-suspensos)
        - [*Matar processos*](#matar-processos)
        - [*Procura arquivo*](#procura-arquivo)
    - [Comandos gerais](#comandos-gerais)
        - [*Exibir arquivo no terminal*](#exibir-arquivo-no-terminal)
        - [*Criar arquivo vazio*](#criar-arquivo-vazio)
        - [*Novo diretorio*](#novo-diretorio)
        - [*Remove diretorios vazios*](#remove-diretorios-vazios)
        - [*Remover arquivo*](#remover-arquivo)
        - [*Copiar arquivo*](#copiar-arquivo)
        - [*Mover arquivo*](#mover-arquivo)
        - [*Comparar dois arquivos*](#comparar-dois-arquivos)
        - [*Encontrar arquivo*](#encontrar-arquivo)
        - [*Programas em execução e seu consumo de hardware*](#programas-em-execu%c3%a7%c3%a3o-e-seu-consumo-de-hardware)
        - [*Muda protecao de arquivo*](#muda-protecao-de-arquivo)
        - [*Muda dono ou grupo de um arquivo*](#muda-dono-ou-grupo-de-um-arquivo)
        - [*Muda grupo de um arquivo*](#muda-grupo-de-um-arquivo)
        - [*Procura um arquivo por um padrão*](#procura-um-arquivo-por-um-padr%c3%a3o)
        - [*Links/atalhos para arquivos/diretório*](#linksatalhos-para-arquivosdiret%c3%b3rio)
        - [*Exibe variáveis de ambiente*](#exibe-vari%c3%a1veis-de-ambiente)
        - [*Define variáveis da sessão do shell*](#define-vari%c3%a1veis-da-sess%c3%a3o-do-shell)
        - [*Total de palavras*](#total-de-palavras)
        - [*Calendario no terminal*](#calendario-no-terminal)
        - [*Mostra data atual*](#mostra-data-atual)
        - [*maquina usuário logado*](#maquina-usu%c3%a1rio-logado)
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
    - [Atualizar node](#atualizar-node)
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

##### *Mostra caminho do diretorio atual*
    pwd

##### *Abrir arquivo .appImage*
    chmod u+x arquivo.AppImage
    
##### *Abrir arquivo executável*
    ./nomeDoArquivo

##### *Diz oque um comando faz*
    whatis comando
    
##### *Ver histórico de comandos*
    history

##### *Criar atalhos para comandos*
    alias nomeAtalho="comando completo"

##### *Editar arquivos no terminal*
    nano caminho/nome-do-arquivo

##### *Mostrar ip da máquina*
    ip addr show

##### *Comprime ou expande arquivo*
    gzip
    
##### *Mostra arquivo comprimido*
    zcat

##### *Mostra processos suspensos*
    jobs

##### *Matar processos*
    kill -9 100

##### *Procura arquivo*
    find /pasta -name Arq* (procura arquivos na /pasta que comecam com nome Arq)
---

### Comandos gerais

##### *Exibir arquivo no terminal*
    cat -b

##### *Criar arquivo vazio*
    touch nomearquivo

##### *Novo diretorio*
    mkdir -p pasta/pastaDentroDePasta

##### *Remove diretorios vazios*
    rmdir pastaVazia

##### *Remover arquivo*
    rm -i nome (pede confirmação para remover)

##### *Copiar arquivo*
    cp nome /pastaDestino

##### *Mover arquivo*
    mv nome novoNome
    mv nome novoDestino/

##### *Comparar dois arquivos*
    cmp arquivo arquivo2

##### *Encontrar arquivo*
    locate nome

##### *Programas em execução e seu consumo de hardware*
    top

##### *Muda protecao de arquivo*
    > chmod 750 arquivo
    > chmod u+x arquivo 
    > chmod a-x arquivo

##### *Muda dono ou grupo de um arquivo*
    chown

##### *Muda grupo de um arquivo*
    chgrp

##### *Procura um arquivo por um padrão*
    grep

##### *Links/atalhos para arquivos/diretório*
    ln arquivo diretorioDestino

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

##### *maquina usuário logado*
    hostname
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

### Atualizar node

1. Verifica versão atual
    `nvm ls`

2. Ver todas as versões
    `nvm ls-remote`

3. Instalar versão desejada    
    `nvm install [VERSION]`
    
4. Usar versão desejada
    `nvm use [VESSION]`

5. Alterar versão padrão para versão desejada [esse é o comando de muda a versão global padrão do pc]
    `nvm alias default [VERSION]`
    
