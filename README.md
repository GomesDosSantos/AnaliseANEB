# AnaliseANEB

![python3](https://img.shields.io/badge/python-3.7-green)
![jupyter](https://img.shields.io/badge/jupyter-1.0-informational)
![pandas](https://img.shields.io/badge/pandas-0.24.2-informational)
![matplotlib](https://img.shields.io/badge/matplotlib-3.1.0-informational)


Este trabalho propõe uma breve análise sobre os indicadores do Sistema Nacional de Avaliação da Educação Básica (ANEB), aplicada sobre o 5º e 9º ano do ensino fundamental e 3º ano ensino médio.
#### Aneb
De acordo com o material pelos mesmos disponibilizado:
> A Aneb é uma avaliação bianual que abrange, de forma amostral e censitária, escolas e alunos das redes públicas e privadas do país, em áreas urbanas e rurais, matriculados no 5º ano (4ª série) e 9º ano (8ª série) do ensino  fundamental  (EF)  e  na  3ª  série  do  ensino  médio  (EM)  regulares.  Seu  objetivo  principal  é  **avaliar**  a **qualidade**, a **equidade** e a **eficiência da educação básica** brasileira. A  Aneb  apresenta  os  resultados  representativos  do  País,  das  regiões  e  dos  estados,  para  os  seguintes estratos  de  interesse:  dependência  administrativa  (pública -federal,  estadual  e  municipal -e  privada); localização (urbana e rural); e área (capital e interior). Apresenta, ainda, informações sobre o contexto e fatores extra e intraescolares associados ao desempenho escolar.



#### Dados
Os dados utilizados aqui podem ser adquiridos em http://portal.inep.gov.br/microdados e são organizados separadamente em acordância do semestre avaliado.
Pode-se notar que ao baixar o conjunto de dados referente ao ano de 2017, há dois arquivos cujo representam a avaliação aplicada na 3ª série do ensino médio:
 - `TS_ALUNO_3EM_AG` apresenta os dados para agregações superiores (estados, regiões e o país).
 - `TS_ALUNO_3EM_ESC` apresenta o resultado por escolas.    
Portanto, optou-se por ler apenas o `TS_ALUNO_3EM_ESC`.

#### Notas importantes
Se você quiser executar este livro em sua máquina, é aconselhável ter no mínimo 8GB de RAM instaladas.

#### Execução do Material
O trabalho por completo foi desenvolvido utilizando *Python 3.7, jupyter, pandas e matplotlib*. As dependências podem ser instaladas com o seguinte comando.   
`pip install  -r requirements.txt`
Para executar o código é necessário utilizar `jupyter notebook` e abrir o arquivo `Livro.ipynb`.

#### Referências Recomendados
Aneb: https://aneb.com.br/
INEP Microdados: http://portal.inep.gov.br/microdados

