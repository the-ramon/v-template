## Python Template

# Instalar virtualenv

Digite:

pip install virtualenv

Execute:
No linux:
python3 -m virtualenv .env
source .env/bin/activate

No windows:

Habilite a execução de Scripts:(PowerShell Adm) Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Confira: (PowerShell) Get-ExecutionPolicy

python -m virtualenv .env
.env/Scripts/activate

No gitbash:

python -m virtualenv .env
source .env/Scripts/activate

# Faça o primeiro commit

git add .
git commit -F commit_comment.txt

# Crie a branch de desenvolvimento

git checkout -b develop

# Fast Commit(gitbash/linux)

no linux habilite o script: chmod +h cmt.sh

Execute: ./cmt.sh -h

atualiza o arquivo requirements.txt ,faz commit de todos os arquivos alterados com notas: commit_comment.txt, substitui commit_comment.txt por commit_comment_model.txt, acrescenta mais um ao número da versão na primeira linha.

Mantêm linhas após ::persist::

# Instalar requirements

Digite: pip install -r requirements.txt