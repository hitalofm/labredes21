# labredes21
## Projeto final labredes2021 monitor

## Docker básico
Construir uma aplicação com 3 serviços: Monitor, servidor tcp e servidor apache.

Monitor: está presente neste repositório e gera testes de ping, DNS e Getrequest.
server: Salva os testes em um arquivo html. [Presente em outro repositório](https://github.com/hitalofm/labredes21host).
Apache: cria um http server e mostrar os testes.

## Executando o container monitor:

- sudo docker run --rm --network=host --name=monitor labredes21/labredes21 python3 monitor.py 127.0.0.1 8081
