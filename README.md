
<table border="0" align="center">
    <tr>
        <td align="center"><a href="https://laravel.com/docs/10.x" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="320" alt="Laravel Logo"></a></td>
        <td align="center"><a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a></td>
        <td align="center"><a href="https://livewire.laravel.com/docs/quickstart" target="_blank"><img src="https://github.com/livewire/livewire/raw/main/art/readme_logo.png" width="270" alt="Livewire Logo"></a></td>
        <td align="center"><a href="https://packagist.org/packages/livewire/livewire"><img src="https://poser.pugx.org/livewire/livewire/d/total.svg" alt="Total Downloads">
    </a></td>
    </tr>
    <tr>
        <td align="center"><a href="https://github.com/axllent/mailpit" target="_blank"><img  src="https://d4.alternativeto.net/ZUFnPykA-p0m0qzlXm9w78cweEVee1d5J9inLyCwocU/rs:fit:280:280:0/g:ce:0:0/exar:1/YWJzOi8vZGlzdC9pY29ucy9tYWlscGl0XzIxODkzNS5wbmc.png" width="160" alt="Mailpit Logo"></a></td>
        <td align="center"><img src="https://camo.githubusercontent.com/8871e50211f7d38ea0cf996c78146e0c78b646b5f3c73e0119b2063cd0cfa269/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f61786c6c656e742f6d61696c7069742e737667" alt="Docker pulls" data-canonical-src="https://img.shields.io/docker/pulls/axllent/mailpit.svg" style="max-width: 100%;"></td>
        <td align="center"><a href="https://hub.docker.com/r/giovanegurgel/laravel_11" target="_blank"><img  src="https://geeksterminal.com/wp-content/uploads/2019/11/docker-logo-310x162.png" width="320" alt="Docker Logo"></a></td>
        <td align="center"><img src="https://img.shields.io/docker/pulls/giovanegurgel/laravel_11" alt="Docker Pulls"></td>
    </tr>
    <tr>        
        <td align="center"><a href="https://dbgate.org/" target="_blank"><img  src="https://avatars.githubusercontent.com/u/78292618?s=200&v=4" width="120" alt="DBGate Logo"></a></td>
        <td align="center"><img src="https://img.shields.io/github/stars/dbgate" alt="GitHub Stars"></td>
        <td align="center"><a href="https://www.mysql.com/" target="_blank"><img  src="https://vetores.org/d/mysql.svg" width="130" alt="MySQL Logo"></a></td>
        <td align="center"><img src="https://img.shields.io/github/stars/mysql" alt="GitHub Stars"></a></td>
    </tr>
</table>

# 🌟 Visão Geral
📦 Este repositório oferece um `Dev Container` pré-configurado para construir aplicações web com Laravel 11 e MySQL no VSCode.

🛠️ Ferramentas: Laravel, Mailpit, MySQL, DBGate

⚡ Início rápido: Elimine as complexidades de configuração e foque na codificação.


# 🛠️ Requisitos

📥 Crie um novo repositório baseado neste `template`.

🔗 Crie sua conta [`Docker Hub`](https://www.docker.com/products/docker-hub/).

🐧 **`Utilize alguma distribuição LINUX.`** 🐧

🐳 Verifique se instalou o [`Docker`](https://docs.docker.com/get-docker/).

💻 Verifique se instalou o [`Git`](https://git-scm.com/downloads).

💻📝 Verifique se instalou o [`VSCode`](https://code.visualstudio.com/download).

📦 Verifique se instalou a extensão [`Dev Containers`](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) no VSCode.

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/warning.svg">
>   <img alt="Warning" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/warning.svg">
> </picture><br>
>
> **ATENÇÃO: Para utilizar MySQL e DBGate, basta remover os comentários no arquivo `docker-compose.yml`**


# 🟢 Começando

1. Entre na sua conta [`Docker Hub`](https://www.docker.com/products/docker-hub/).

2. Clone o seu repositório (copie a URL HTTPS no GitHub)

```bash
git clone url_https_do_seu_repositório
```

3. Abra o projeto no `VSCode`. [instale a extensão Dev Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

```bash
cd pasta_do_projeto
code .
```
4. Clique no botão **`Reabrir no Contêiner`** que aparece no canto inferior direito. Nesse momento o VSCode será reaberto dentro do contexto do container Docker (conforme indicado em `docker-compose.yml`).

![Imagem da janela de reabrir Contêiner](https://raw.githubusercontent.com/giovanegurgel/devcont_laravel/main/img/reabrir_container.png)

5. Criando um novo projeto LARAVEL 11:
> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/warning.svg">
>   <img alt="Warning" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/warning.svg">
> </picture><br>
>
> **ATENÇÃO: Para criar um novo projeto, é necessário executar o comando `/var/www/create_laravel.sh` no  terminal do VSCode dentro do container. Após esse comando importar o Laravel e fazer o Build dos pacotes NodeJS, o projeto estará disponível na pasta `/var/www/html`.**

6. Algumas extensões VSCode serão instaladas automaticamente. Pode instalar outras normalmente ou obter as extensões já ativadas no seu VSCode. Para isso vá na aba de extensões, depois clique no ícone de nuvem, selecione as extensões que deseja instalar e clique em `Ok`.

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/info.svg">
>   <img alt="Info" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/info.svg">
> </picture><br>
>
> **É possível escolher extensões a serem instaladas automaticamente no arquivo `.devcontainer/devcontainer.json`**

# 🚀 Como acessar sua aplicação

🌐 Acesse seu projeto [**`Laravel ➡️ http://localhost:8080`**](http://localhost:8080) no navegador.

🌐 Acesse o [**`Mailpit ➡️ http://localhost:8025`**](http://localhost:8025) no navegador.

🌐 Acesse o [**`DBGate ➡️ http://localhost:8010`**](http://localhost:8010) no navegador.


# ✨ Dicas

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/warning.svg">
>   <img alt="Warning" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/warning.svg">
> </picture><br>
>
> **ATENÇÃO: Conforme indicado no arquivo `docker-compose.yml`, os serviços serão inicializados no modo HOST, logo, caso já exista algum programa instalado no Linux utilizando alguma das portas informadas no `docker-compose.yml`, será necessário modificar esse arquivo e inserir novos números de porta para os serviços.**

> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/warning.svg">
>   <img alt="Warning" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/warning.svg">
> </picture><br>
>
> **ATENÇÃO: Se houver algum conflito com nomes de Contêiners, utilize os seguintes comandos Docker para solucionar o problema. Também pode utilizar as interfaces gráficas `Docker Desktop` ou `Portainer` para excluir algum container já existente.**

```bash
docker ps # lista containers em execução

docker container ls -a # lista containers ocultos

docker container rm NOMECONTAINER # EXCLUI o container "NOMECONTAINER"
```
> <picture>
>   <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/light-theme/info.svg">
>   <img alt="Info" src="https://raw.githubusercontent.com/Mqxx/GitHub-Markdown/main/blockquotes/badge/dark-theme/info.svg">
> </picture><br>
>
> **ATENÇÃO: Os arquivos do `servidor MySQL` serão ignorados pelo Git. Portanto, sempre faça o DUMP (exportar) do banco de dados quando quiser executar seu projeto em outro computador.**
> **Para `EXPORTAR` algum banco de dados no `DBGate`, clique com o botão direito do mouse no título do banco de dados e depois clique em `Backup/export SQL Dump`. O arquivo `SQL` gerado ficará salvo na aba `Favoritos`. Basta salvar esse arquivo na raiz do projeto e versionar normalmente para o GitHub.**


# 🤝 Contribuições
Contribuições são muito bem-vindas! Mande pull request com melhorias, correções ou novas ideias.