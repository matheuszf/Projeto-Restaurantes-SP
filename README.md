<p align="center">
  <img src="https://thumbs.dreamstime.com/b/projeto-isolado-pino-do-%C3%ADcone-do-lugar-do-restaurante-74197494.jpg" width="180">
</p>

<div align="center">
  Restaurantes-SP
</div>

# Dados
Web scrapping com selenium foi utilizado para extrair informações do site https://www.zomato.com/pt/sao-paulo-sp que oferece os restaurantes mais conceituados de São Paulo - SP.

## Documentação do dataset

- name - Nome do restaurante
- price - Média de preço para duas pessoas
- type - Tipo de cozinha do restaurante
- bairro - Bairro onde o restaurante está localizado
- address - Endereço onde o restaurante está localizado
- url - Url do restaurante no site https://www.zomato.com/pt/sao-paulo-sp
- latitude - Latitude do restaurante
- longitude - Longitude do restaurante
- tipo_novo - Tipo de cozinha filtrado

# Pré-requisitos

- Python
- Selenium Webdriver - ChromeDriver
- Algumas bibliotecas do Python
- Tableau

### Bibliotecas

- Pandas
- Selenium

# Introdução

Esse projeto visa analisar os dados de 11.053 restaurantes da cidade de São Paulo capital para obter informações relevantes e abordar algumas questões.

## Questões

- Quais são os bairros com maior e menor número de restaurantes na cidade?
- Qual a média de preço por bairro?
- Qual a média de preço por tipo de cozinha em cada bairro?
- Qual é a quantidade de restaurantes por tipo de cozinha em São Paulo?
- Quais são os 4 tipos predominantes de cozinha na cidade?
- Qual o tipo de cozinha predonominante em cada bairro?
- Qual o preço médio para duas pessoas dos restaurantes analisados?

# Público alvo

Os dados obtidos podem ser úteis tanto para novos empreendedores, donos de restaurantes, quanto para clientes.
Empreendedores podem buscar por informações sobre, por exemplo, qual tipo de cozinha é a mais frequente em cada bairro e a média de preço.
Assim como os clientes poderiam fazer a busca de um tipo de cozinha baseado na média de preço dos restaurante de um bairro específico. 

# Ferramenta de visualização

O Tableau tem sido usado como ferramenta de visualização de dados, pois é uma plataforma de análise muito poderosa, segura e flexível, onde podemos visualizar nossos dados de forma rápida.Também é possível criar painéis interativos e uma história geral usando o storyboard.

<img src="https://github.com/matheuszf/Projeto-Restaurantes-SP/blob/main/Untitled-4-Trim.gif" width="1000">


## Tableau story link

https://public.tableau.com/profile/matheus.zavagli#!/vizhome/ProjetoFinalRestairantesSP/Story1?publish=yes

# Conclusão

- Itaim Bibi é o bairro com maior números de restaurantes em São Paulo - SP, com um número de 1.055 restaurantes de diversos tipos de cozinha, seguido por Pinheiros (642) e Jardim Paulista (639). 
- Vila Formosa é o bairro com menor quantidade de restaurantes, com 21 restaurantes, seguido por Carrão (22) e Rio Pequeno (22).
- Jardim Paulista é o bairro mais caro para uma reifeição, com valor médio de R$88,74 para cada 2 pessoas, seguido da Vila Madalena (R$83,13) e Moema (R$ 78,72).
- Braz é o bairro mais barato para uma reifeição a dois, com valor de R$ 37,83 para cada 2 pessoas, seguido de Casa Verde (R$38,37) e Vila Prudente (R$ 38,50).
- A cozinha predominante é a brasileira, com 5.243 restaurantes espalhados por São Paulo - SP, seguido por comidas de bar (913) e pizzarias (898) e padaria (607).
- Na grande maioria os tipos de cozinhas predominantes nos bairros  são:  brasileira, comida de bar, pizzaria e padaria.
- Os preços médios dos restaurantes variam de R$ 10,00 a R$ 600,00.

