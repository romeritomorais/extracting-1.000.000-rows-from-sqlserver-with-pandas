![](https://github.com/romeritomorais/manipulando-dados-no-sqlserver-com-python/blob/master/resources/logo.jpeg)

## Instalação e configuração da base de dados

segue os passos:
- 0.baixe o Database: [click aqui!!:](https://www.microsoft.com/en-us/download/details.aspx?id=18279)
- 1.apos baixar, extrair o `ContosoRetailDW.bak` para uma pasta
- 2.abrir o `sqlserver` e fazer o `restore/restaurar`
- 3.mude o nome da base de dados para `DatabaseRetail`
- 4.abrir o Jupyter notebook e seguir os passos
![](https://github.com/romeritomorais/manipulando-dados-no-sqlserver-com-python/blob/master/resources/bd.PNG)
- 5.na imagem acima onde tem `yourStrong(!)Password` voce muda e coloca a senha do usuario do seu banco geralmente o SA, em `localhost` voce pode deixar como esta ou colocar o nome da sua maquina ou IP/host remoto, mas que seja o endereço de onde o banco `DatabaseRetail`
foi restaurado. após isso voce pode seguir os passos do `Extracting data from SQLServer with Python.ipynb`
