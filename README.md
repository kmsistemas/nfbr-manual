# Manual NFbr

Manual de uso do sistema NFbr.


## Setup inicial?

01. Clone o repositório;
02. Crie uma "virtualenv" com Python 3.6;
03. Ative a "virtualenv";
04. Atualize o "pip";
05. Instale as dependências;
06. Rode o projeto;
07. Faça deploy do projeto;

```console
git clone https://github.com/KmSistemas/nfbr-manual.git
cd nfbr-manual
python -m venv .venv

# OSX
source .venv/bin/activate

#windows
.venv\Scripts\activate.bat

pip install --upgrade pip
pip install -r requirements.txt
mkdocs serve
mkdocs gh-deploy
```


## Como desenvolver?

```console
# OSX
source .venv/bin/activate

#windows
.venv\Scripts\activate.bat

mkdocs serve
#Servidor na Rede
mkdocs serve -a 0.0.0.0:8000
mkdocs gh-deploy
```

## Links Úteis

Projeto criado com MkDocs
 - http://www.mkdocs.org/

Tema: Material
 - http://squidfunk.github.io/mkdocs-material/

Linguagem: Markdown
 - https://blog.ghost.org/markdown/
 - https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet
