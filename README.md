# IFCEbvd
## IFCE Biblioteca Virtual Downloader

Ferramenta de download de livros da biblioteca virtual do IFCE. Baixa página a página como imagem e depois converte para pdf.
<a href="http://macalogs.com.br/estudo-de-caso-baixando-livros-de-uma-biblioteca-virtual/">Veja esse estudo de caso para saber como ela foi desenvolvida.</a>

## Dependências
- Biblioteca do Python Selenium: `sudo pip3 install selenium`
- Biblioteca do Python fpdf: `sudo pip3 install fpdf`
- Biblioteca do Python Selenium: `sudo pip3 install selenium`
- PhantonJS: `sudo apt-get install phantomjs`

## Uso
**Windows**
1. Abra o CMD na pasta em que se localiza o script
2. Use o comando: `ifcevd.py <números, e somente os numeros, de sua matrícula> <endereco url do livro no bvu> [endereco url de outro livro] ..`.

**Linux**
1. Abra o terminal na pasta em que se localiza o script
2. Use o comando: `py3 ifcevd.py <números, e somente os numeros, de sua matrícula> <endereco url do livro no bvu> [endereco url de outro livro] ..`. 

***OBS:** O endereço a ser fornecido é o mesmo do navegador. Pode-se fornecer quantos livros quiser.*
