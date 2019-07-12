# Projeto do Curso de Big Data
### Descrição:
Este projeto trás a estrutura básica de um data lake contendo dados dos gastos dos parlamentares da Câmara dos Deputados.<br>
__Fonte:__ https://www2.camara.leg.br/transparencia/cota-para-exercicio-da-atividade-parlamentar/dados-abertos-cota-parlamentar

### Estrutura do Lago
* __Landed__: Arquivos brutos, extraídos do Porta da Transparência da Câmara dos Deputados;
* __Raw__ : Arquivos otimizados, já em formato mais estruturado (Parquet);
* __Modeled__ : Arquivo com agregações, conversões e etc;
* __Self__ : Arquivos pronto para uso em insights
