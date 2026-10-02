# Comandos Git e Github

## Configuração

- `git config --global user.name "nomecorrespondente"` -> Usuário

- `git config --global user.email "emailcorrespondente"` -> Email

- `git config --global --list` -> Lista todas as informações do repositório

---

## Criando

- `git init` -> Cria um arquivo .git com a suas configurações

- `git clone (repositório a ser clonado ou abaixado)` -> Abaixa o repositório na web

## Fluxo de trablho

- Working Directory

Area de trabalho para produção

---

- Adicionando e remoção de arquivos:
    
  - `git add` -> Ele prepara o arquivo o *stage*

  - `git status` -> Verifica se foram adicionados ou que faltam a serem adicionados  

  - `git reset` -> Retiram eles do *stage*, mas, não altera o diretório de trabalho

  - `git restore` -> Ele restaura o diretório 

  - `git diff` -> Compara os arquivos que foram adicionados com os que faltam adicionar e com os removidos
---

- Confirmação de mudança

Envia um rastro de código(s) que podem ser **registrados** no projeto
        
- `git commit -m` -> Gera um rastro
          
  - `git commit --amend -m` -> Altera o commit anterior
        
- `git diff --staged` -> Verifica o novo commit 

---

- Logs e Histórico

Histórico de cada momento que foi registrado os códigos 

- `git log` -> Levanta todos os hashs de cada commit 

  - `git log --oneline` -> Traz os hashs reduzidos

  - `git log --graph` -> Mostra o histórico e formato de gráfico como se fosse uma linha do tempo de cada commit e branch

  - `git log --author= "Autor Correspondente"`-> Lista os commits do usuário
            
---

    - Branches
    
    Caminho **alternativo** do código sem alterar o projeto principal

        - `git branch` -> Lista a branch

            - `git branch *nome correspondente* -> Cria um nova branch
            
            - `git branch -D *nome da branch* -> Deleta a branch criada ou já existente
        
            - `git branch -m` -> Altera o nome da branch

        - `git checkout -b` -> Navega entre as branches
