# Hospital ABC 

# Meu Front

Este pequeno projeto faz parte do material extra da Disciplina **Desenvolvimento Back End Avançado e Arquitetura de Software** 

---
## Como executar em modo de desenvolvimento

Basta fazer o download do projeto e abrir o arquivo index.html no seu browser.

## Como executar através do Docker

Certifique-se de ter o [Docker](https://docs.docker.com/engine/install/) instalado e em execução em sua máquina.

Navegue até o diretório que contém o Dockerfile no terminal e seus arquivos de aplicação e
Execute **como administrador** o seguinte comando para construir a imagem Docker:

```
$ docker build -t frontend .
```

Uma vez criada a imagem, para executar o container basta executar, **como administrador**, seguinte o comando:

```
$ docker run -d -p 8080:80 frontend
```

Uma vez executando, para acessar o front-end, basta abrir o [http://localhost:8000/#/](http://localhost:8000/#/) no navegador.




