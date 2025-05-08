
# App para monitorar BTC

Este projeto tem como objetivo monitorar e exibir o preço atual do Bitcoin (BTC) em tempo real, utilizando a linguagem Kotlin. Ele se conecta a uma API pública para obter o valor atual do BTC e exibe as informações de forma prática e intuitiva.

## Funcionalidades

- Monitoramento do preço do Bitcoin (BTC) em tempo real.
- Atualizações ao pressionar um botão.

## Tecnologias Utilizadas

- **Kotlin** - Linguagem de programação para implementação do projeto.
- **API de Preço de Criptomoedas** - API pública para obter dados de preços.
- **JSON** - Para processar as respostas da API.
- **Coroutines (Opcional)** - Para requisições assíncronas e otimização da performance.
- **Maven ou Gradle** - Para gerenciamento de dependências (escolha uma ferramenta de build).

## Estrutura do projeto

- AndroidManifest.xml: define o comportamento do app e define o tema que sera usado.
- MainActivity.kt: classe principal do app, contendo toda a lógica para definir o comportamento do botão que dispara a requisição para recuperar o preço do Bitcoin.
- TickerResponse.kt: o DTO que ira receber as informações retornadas pela API.
- Services: são as classes responsáveis pela comunicação com a API, guardando toda a lógica de url, disparo da requisição, aguardo e processamento da resposta.
- Resources: guardam os arquivos .xml que desenham a tela e os componentes do app, definindo tamanhos, cores e todo o design

