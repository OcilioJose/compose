## Docker 

- **docker-compose.yml**: Arquivo de configuração do Docker Compose.
- **html/**: Diretório que contém os arquivos HTML.
  - **index.html**: Página inicial servida pelo Apache.

## Pré-requisitos

Antes de começar, você precisa ter o Docker e o Docker Compose instalados em sua máquina. Você pode seguir as instruções de instalação no [site oficial do Docker](https://docs.docker.com/get-docker/).

## Como Executar

1. Clone este repositório:

   ```bash
   git clone https://github.com/OcilioJose/compose.git
   cd compose

   docker-compose up
   
 Acesse http://localhost:8080 no seu navegador. Você deverá ver a página HTML que você criou.
