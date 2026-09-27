# Biblioteca Escolar (Front-End)

Interface de usuário para o MVP do sistema de biblioteca escolar. Construída com HTML, CSS e Vanilla JavaScript (agora com tema escuro), a aplicação faz chamadas assíncronas para as quatro rotas HTTP obrigatórias (GET, POST, PUT, DELETE) da API principal sem recarregar a página.

## Instalação e Execução (Docker)

Este repositório contém o `Dockerfile` na raiz com as instruções de implementação para execução via contêineres utilizando Nginx.

1. Clone este repositório:

```bash
git clone https://github.com/lucianacoda/bookedu-frontend.git
cd bookedu-frontend
```

2. Construa a imagem Docker:

```bash
docker build -t app-biblioteca .
```

3. Execute o contêiner (mapeando a porta 8080 para a porta 80 do Nginx):

```bash
docker run -p 8080:80 app-biblioteca
```

Após iniciar o contêiner, acesse a interface abrindo o navegador no endereço: `http://localhost:8080`
