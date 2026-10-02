# Comandos que aprendi sobre Linux

## Navegação

- `pwd` -> Verifica onde está o caminho 

- `cd` -> Navega pelos diretórios

- `rm` -> Remove os arquivos ou diretórios

- `ls` ->  Lista todos os arquivos ou diretórios

- `rm` -> Remove os arquivos ou diretórios 

- `nvim` -> Executa dentro do *neovim*

- `cat` -> Imprime o texto via terminal

--- 

## Permissões

- `chmod` -> Altera o formato do diretório e dos arquivos, correspondendo aos número octais de acordo com a somatória deles: 
    - `r` -> read/leitura -> 4
    - `w` -> write/escrita -> 2
    - `x` -> execute/executar -> 1

- `chown` -> Altera a permissão de acesso de grupos ou usuários:
    - `user` -> O próprio usuário
    - `group` -> Grupos que podem acessar
    - `other` -> Outro usuários

---

## Gerenciadores de pacotes

- `sudo apt` -> Instala as dependencias pelos repositorios oficiais do linux
  - `sudo apt install` -> Instala as dependencias e os pacotes  
  - `sudo apt update` -> Atualiza as informções de software
  - `sudo apt upgrade` -> Atualiza todos os softwares
    - `apt-cache` 


- `sudo dpkg` -> Não instala as dependencias, transformando somente o arquivo _*.deb*_
  - `sudo dpkg -r` -> Remove
    - `sudo dpkg --purge` -> Remove de forma total
  - `sudo dpkg -i` -> Instala
  - `sudo dpkg -l` -> Lista
