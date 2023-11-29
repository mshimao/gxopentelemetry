# Atividade 2

### Criar KB Genexus

Vamos criar uma KB Genexus com as seguintes características:
...


### Configurar a observabilidade na aplicação GX

#### Passo 1
Configurar a propriedade Observability Provider com a opção "OpenTelemetry".
- [Como configurar a propriedade Observability Provider](https://wiki.genexus.com/commwiki/wiki?53408,Observability+Provider+property)


#### Passo 2
Para habilitar a geração do trace nas procedures, configurar a propriedade Generate Observability Span para Yes.
- [Configurar a geração do trace nas procedures](https://wiki.genexus.com/commwiki/wiki?55801,Generate+Observability+span+property)

#### Passo 3
Configurar o log do Genexus para gerar o log no arquivo client.log.

#### Passo 4
Gerar um deploy da aplicação para um container Docker.

#### Passo 5
Publicar a imagem no Docker Hub.

#### Passo 6
Ir para a pasta collector e editar o arquivo docker-compose-net.yml para informar o nome da imagem criada.

Próxima atividade: [Atividade 03](docs/03-atividade.md)


