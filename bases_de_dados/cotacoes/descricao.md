
### [Sobre a base de dados](#)
<p align="justify">
A base se refere às cotações da Magazine Luiza (código MGLU3.SA) na bolsa de valores do Brasil. Os dados são diários e englobam o período entre 03 de janeiro de 2022 e 03 de janeiro de 2024.
</p> 

#### [Descrição das variáveis](#)
A base de dados contém 500 linhas e seis variáveis, que estão descritas abaixo:

- *data*: Data da cotação, no formato aaaa-mm-dd.

- *abertura*: Valor de abertura da cotação na correspondente data, em reais.

- *maxima*: Valor máximo da cotação na correspondente data, em reais.

  *minima*: Valor mínimo da cotação na correspondente data, em reais.

- *fechamento*: Valor de fechamento da ação na correspondente data, em reais.

- *volume*: Volume de ações negociadas na correspondente data.

#### [Download da base](#)
A base está dispoível para download <a href="https://luizpala1.github.io/GES109/bases_de_dados/cotacoes/mglu" target="_blank">neste link</a>, no formato texto.

#### [Leitura da base no RStudio](#)
Para carregar a base de dados em seu RStudio, iremos utilizar a seguinte linha de código:

```{r}
# leitura da base no RStudio
df <- read.table("C:/Users/DESICET/Desktop/mglu", h = T)
```

<p align="justify">
Observe que o path *C:/Users/DESICET/Desktop/* requer modificação para o diretório onde o conjunto de dados foi armazenado em seu computador. Lembrem-se que para alguns sistemas é necessário substituir as barras invertidas (\) por barras inclinadas (/) como separadores de diretório.
</p> 

```{r}
# visualizar a base de dados
View(df)
```
