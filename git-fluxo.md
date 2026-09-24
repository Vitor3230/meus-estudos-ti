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
    - Adicionando e remoção de arquivos: 
        - `git add` -> Ele prepara o arquivo o *stage* 
        - `git status` -> Verifica se foram adicionados ou que faltam a serem adicionados  
        - `git reset` -> Retiram eles do *stage*, mas, não altera o diretório de trabalho
        - `git restore` -> Ele restaura o diretório 
        - `git diff` -> Compara os arquivos que foram adicionados com os que faltam adicionar e com os removidos
    
