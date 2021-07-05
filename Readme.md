# Desafio 1 - Webserver com Docker e Golang

No projeto **Imersão Full Cycle 3.0** foi feito o seguinte desafio:
```
Desenvolva uma aplicação utilizando Golang que disponibilizará um servidor web na porta 8000.

Ao acessar deveremos ver uma página com o seguinte conteúdo:

- Background com um tema de um filme, quadrinhos, seriado a sua escolha
- De forma centralizada escreva: Imersão Full Cycle entre h1
- Fique na liberdade para estilizar a página a seu gosto
- Gere o arquivo executável da aplicação rodado: GOOS=linux go build main.go

Gere uma imagem Docker que ao ser executada rode a aplicação. Faça o push da imagem no Docker Hub.
```

Como resultado deste desafio, a imagem [***wdot456/fc3-desafio-01***](https://hub.docker.com/r/wdot456/fc3-desafio-01) foi gerada.
Para testar, com o docker instalado em sua máquina, execute o seguinte comando no terminal: 

``docker run -p 8000:8000 wdot456/fc3-desafio-01``

Agora basta acessar em seu navegador [http://localhost:8000](http://localhost:8000)

