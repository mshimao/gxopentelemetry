# Hands-On Genexus Opentelemetry

Hands-On para observabilidade no Genexus.

### Requisitos

Inicialmente é necessário configurar os requisitos para trabalharmos com Genexus e Opentelemetry. 

Os requisitos são:
- Genexus 18 Upgrade 6
- Conta do Grafana Cloud
- Docker Desktop for Windows

Software opcionais:
- [VS Code](https://code.visualstudio.com/download) - Editor de código open source.
- [Extensão para o VSCode - REST Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client) - Extensão que permite realizar chamadas a APIs REST.
- [DevToys](https://devtoys.app/) - DevToys é um aplicativo para Windows que oferece uma coleção de ferramentas úteis para desenvolvedores. Ele inclui recursos como um comparador de texto, um verificador de JSON, um codificador/decodificador de URL, entre outros. É uma ferramenta útil para tarefas rápidas de desenvolvimento e depuração.

### Instalar o Genexus 18 Upgrade 6

Os recursos de observabilidade que iremos utilizar estão disponíveis no Genexus 18 Upgrade 6.
A aplicação que será criada é será em .NET Core, será necessário instalar os requisitos para gerar a aplicação em .NET Core.

- [Requisitos Gerador .NET](https://wiki.genexus.com/commwiki/wiki?38605,.NET+Generator+Requirements)

### Criar uma conta no Grafana Cloud

Vamos utilizar o Grafana para exibir os dados coletados, o Grafana Cloud disponibiliza uma conta gratuita com vários recursos já configurados que permite rapidamente visualizar os dados que iremos coletar da aplicação.

Acessar o link abaixo e clicar no botão "Create free account" para criar a conta gratuíta:
- [Grafana Cloud](https://grafana.com/products/cloud/)

### Instalação do Docker Desktop for Windows

O primeiro passo é ler a documentação do Docker que explica os requisitos para a instalação do Docker Desktop for Windows:

- [Requisitos para o Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/#system-requirements)

Após a leitura e configuração dos requisitos, agora é fazer o download do Docker Desktop for Windows e a instalação.

- [Instalar o Docker Desktop for Windows](https://docs.docker.com/desktop/install/windows-install/#install-docker-desktop-on-windows)

Com isso temos o ambiente preparado para executar os contêineres Docker.

Próximo: [Atividade 01](docs/01-atividade.md)