
### [Sobre a base de dados](#)
<p align="justify">
Esse conjunto de dados corresponde à informações dos nascimentos ocorridos na cidade de Lavras (cod: 313820), Minas Gerais, no ano de 2021. Os dados brutos estão disponíveis <a href="https://datasus.saude.gov.br/transferencia-de-arquivos" target="_blank">neste link</a>, foram extraídos em 03 de janeiro de 2024 e já passaram por um processo de estruturação e limpeza. 
</p> 

#### [Descrição das variáveis](#)
A base de dados contém informações sobre os 2056 nascimentos ocorridos no ano de 2021, incluindo 10 variáveis relacionadas às características da mãe e do bebê. Sendo:

- *idade_da_mae*: Idade da mãe, em anos completos.
  
- *estado_civil_mae*: Estado civil da mãe, contendo seis níveis (<b>1:</b> solteira; <b>2:</b> casada; <b>3:</b> viúva; <b>4:</b> separado judicialmente/divorciado; <b>5:</b> união consensual; <b>9:</b> ignorado).

- *escolaridade_da_mae*: Escolaridade da mãe, em anos de estudo concluídos, sendo: <b>1:</b> nenhuma; <b>2:</b> 1 a 3 anos; <b>3:</b> 4 a 7 anos; <b>4:</b> 8 a 11 anos; <b>5:</b> 12 e mais; <b>9:</b> ignorado.

- *gestacao*: Semanas de gestação, sendo: <b>1:</b> menos de 22 semanas; <b>2:</b> 22 a 27 semanas; <b>3:</b> 28 a 31 semanas; <b>4:</b> 32 a 36 semanas; <b>5:</b> 37 a 41 semanas; <b>6:</b> 42 semanas e mais; <b>9:</b> ignorado.

- *parto*: Tipo de parto, conforme os níveis: <b>1:</b> vaginal; <b>2:</b> cesáreo; <b>9:</b> ignorado.

- *consultas*: Número de consultas de pré-natal: <b>1:</b> nenhuma; <b>2:</b> de 1 a 3; <b>3:</b> de 4 a 6; <b>4:</b> 7 e mais; <b>9:</b> ignorado.

- *data_nascimento*: Data do nascimento, no formato aaaa-mm-dd.

- *sexo*: Sexo, conforme os níveis: <b>0:</b> ignorado ou não informado; <b>1:</b> masculino; <b>2:</b> feminino.

- *raca_cor*: Raça/Cor: <b>1:</b> branca; <b>2:</b> preta; <b>3:</b> amarela; <b>4:</b> parda; <b>5:</b> indígena.

- *peso*: Peso ao nascer, em gramas.

Em caso de dúvidas, veja a <a href="https://luizpala1.github.io/GES109/bases_de_dados/sus_nascimentos/Estrutura_SINASC_para_CD.pdf" target="_blank">descrição completa</a>
 da base de dados disponibilizada pelo Sistema Único de Saúde. 

#### [Download da base](#)
A base está dispoível para download <a href="https://luizpala1.github.io/GES109/bases_de_dados/sus_nascimentos/base.csv" target="_blank">neste link</a> no formato CSV (Comma-Separated Values).


