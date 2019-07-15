# Desafio de FrontEnd!

## Objetivo
Desenvolver uma página onde o usuário possa pesquisar disponibilidade de hotéis através de um critério e possa visualizar os resultados em uma lista **ordenada pelo hotel mais barato**, pelo desktop ou mobile. 

## API
Utilize a nossa API REST para efetuar a pesquisa por disponibilidade de hotel, segue abaixo a URL e a credencial de acesso.

URL de Pesquisa: https://pp.cangooroo.net/ws/rest/hotel.svc/Search

Usuário: **candidato_t4w**
Senha: **candit@!2019**

### Estrutura de campos da requisição:
|Nome do Campo| Descrição |
|--|--|
| Credential → Username | Usuário de acesso |
| Credential → Password	| Senha de acesso   |
| Criteria → DestinationId | Id da Cidade (Utilize os códigos **1003944** (MIAMI) ou **1010106** (ORLANDO) |
| Criteria → NumNights	| Quantidade de noites da estádia   |
| Criteria → CheckinDate | Data de Checkin no hotel (Formato: **YYYY-MM-DD**)  |
| Criteria → MainPaxCountryCodeNationality | Nacionalidade do passageiro (Deixar fixo **BR**) |
| Criteria → SearchRooms | Lista de Quartos a ser pesquisados |
| SearchRoom → NumAdults | Quantidade de adultos no quarto | 
| ChildAges | Lista de idades das crianças |
| Quantity | Quantidade de quartos |

Na **requisicao.json** o critério usado foi: 
 - Pesquisa em ORLANDO (1010106) - Duas noites - Data de checkin 10/01/2019 - 1 quarto com um adulto e uma criança de 5 anos.

## Arquivos de ajuda
Está disponível na pasta **Data** um exemplo de **requisicao.json** e **resposta.json** que deve ser utilizado para efetuar a comunicação com a API.


**IMPORTANTE**

Os arquivos abaixo, serão utéis para mostrar informações sobre o hotel, você conseguirá cruzar os dados através do ID do hotel que retorna na resposta da pesquisa e o ID do hotel contido no arquivo estático em cada nó de hotel.

Os aquivos são: 
 - **1003944_hotels_static_data.json** - Arquivo de conteúdo estático de detalhes de hotéis de MIAMI. 
 - **1010106_hotels_static_data.json** - Arquivo de conteúdo estático de detalhes de hotéis de Orlando.

Utilize os arquivos estáticos para complementar as informações retornadas pela API, mostrando dados como:
 - **Fotos**
 - **Categoria do Hotel**
 - **Coordenadas de Geolocalização**
 - E outras informações que desejar.


# Critério de Avaliação
Para desenvolvedores FrontEnd, vamos avaliar os seguintes critérios:
 - Reutilização, organização, padronização, legibilidade e documentação de código;
 - Performance no carregamento da página;
 - UI, UX e responsividade;
 - Animações, microinterações e loaders.
 
# Tecnologias utilizadas
Fica a critério do desenvolvedor escolher qual linguagem utilizará para desenvolver, desde que explique como executar e testar o projeto.

# Tempo de Desenvolvimento
O Desenvolvedor terá o tempo de **1 semana** para entregar o desafio, que contará a partir do momento em que o link foi enviado.

# Entrega
O Desenvolvedor poderá disponibilizar o código em seu próprio github ou enviar para o e-mail atila.santos@t4w.com.br o .zip do projeto.

**IMPORTANTE**: Não esquecer de enviar um arquivo explicando como executar/testar o projeto.

# Dúvidas
Entrar em contato através do e-mail: **atila.santos@t4w.com.br**.
