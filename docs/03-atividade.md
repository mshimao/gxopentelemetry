# Atividade 3

### Configurar o coletor OpenTelemetry

#### Passo 1
Abrir um linha de comando e ir até a pasta collector, e editar o arquivo collector.yaml

![collector.yaml](images/collectoryaml.png)

#### Passo 2
Acessar o Grafana Cloud para pegar as chaves de autenticação, e configurar o coletor para acessar os serviços do Grafana Cloud.

- [https://grafana.com/](https://grafana.com/)

Clicar no botão "My Account".

![grafanacloud](images/grafanacom.png)

Após o login serão apresentados os componentes do Grafana Cloud disponíveis na conta.

![grafanacloudcomponent](images/grafanadatasources.png)

#### Passo 3
Clicar na opção "Send Metrics" do Prometheus.

![prometheus](images/prometheus.png)

Copiar o endpoint "Remote Write Endpoint" e colar no endpoint do Prometheus no arquivo collector.yaml.

![Remote Write Endpoint](images/prometheusendpoint.png)

![prometheusendpointcollector](images/prometheusendpointcollector.png)

Clicar em "Generate Token" para gerar o token de acesso ao Prometheus.

![prometheustoken](images/prometheustoken.png)

No popup informar o nome do token e clicar em "Create token".

![prometheustoken2](images/prometheustoken2.png)

Copiar o token gerado e guardar num arquivo texto.

![prometheustoken3](images/prometheustoken3.png)

Copiar o Username e usando um encoder base64, encodar a string "username:token".

![prometheustoken4](images/prometheustoken4.png)

![prometheustoken5](images/prometheustoken5.png)

Copiar a string resultante do encoding e substituir a tag {base64 encoded username:password} da configuração do Prometheus no arquivo collector.yaml.

![prometheustokencollector](images/prometheustokencollector.png)

Próxima atividade: [Atividade 04](docs/04-atividade.md)


