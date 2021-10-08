# :computer: NGINX - Micro Frontend

### Estudo de micro frontends utilizando `Docker` e `NGINX`

Este projeto consiste em 2 aplicações, uma feita em React, outra feita em Vue e os arquivos de configuração do Docker + nginx.

O intuito do exercicio é criar duas rotas de acesso no mesmo domínio para acessar as aplicações, de modo que elas sejam independentes na hora do build.

### Como rodar o projeto
> Para rodar o projeto, você necessita ter o Docker Desktop instalado em sua máquina.

#### 1º passo:
Clone o projeto em sua máquina.

```powershell
git clone https://github.com/smolskig/micro-frontend-nginx.git
```

#### 2º passo:
Abra um terminal dentro da pasta do projeto e rode o seguinte comando:

```powershell
docker-compose up --build
```

## :star: Pronto! :star:

### Agora é só abrir o navegador e acessar as seguintes rotas:

`localhost/vue` : para abrir a aplicação Vue

`localhost/react` : para abrir a aplicação React

## :page_facing_up: Fontes
Este exercício foi baseado no exemplo mostrado no canal do Matheus castiglioni:

https://www.youtube.com/watch?v=5_Ie7ykJ9Iw
