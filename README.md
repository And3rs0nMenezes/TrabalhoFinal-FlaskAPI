# Supermarket API
Este projeto representa o trabalho final para o curso de Programação Web I. Consiste em uma API desenvolvida com o framework Flask, destinada à gestão de estoque em um ambiente de supermercado.

## 🛒 Visão Geral
A API do Sistema de Estoque de Supermercado foi projetada para fornecer operações completas de CRUD (Criar, Ler, Atualizar, Excluir) relacionadas à administração de estoques em supermercados. Ao aderir aos princípios RESTful, nossa API oferece uma interface limpa, precisa e altamente interativa para lidar com todos os aspectos dos recursos de estoque. Você pode ler o escopo inicial do projeto [aqui](https://docs.google.com/document/d/1X4wjatlVUa80E7u3VwwE6aVIaxxLmiBwUOya_DKId7M/edit?usp=sharing).

## 🔀 Rotas
<details>
<summary><strong>Products</strong></summary>
<br><p>Essa rota tem como objetivo a administração da entidade produtos</p>
<table>
    <thead>
        <tr>
            <th>Requisição</th>
            <th>Rota</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>GET</td>
            <td>/products</td>
            <td>Buscar todos os produtos</td>
        </tr>
        <tr>
            <td>POST</td>
            <td>/products</td>
            <td>Cadastrar um novo produto</td>
        </tr>
        <tr>
            <td>PUT</td>
            <td>/products/&#123;id&#125;</td>
            <td>Editar um produto já existente</td>
        </tr>
         <tr>
            <td>DELETE</td>
            <td>/products/&#123;id&#125;</td>
            <td>Deletar um produto já existente</td>
        </tr>
    </tbody>
</table>     
</details>

<details>
<summary><strong>Category</strong></summary>
<br><p>Essa rota tem como objetivo a administração da entidade categorias</p>
<table>
    <thead>
        <tr>
            <th>Requisição</th>
            <th>Rota</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>GET</td>
            <td>/categories</td>
            <td>Buscar todas as categorias</td>
        </tr>
        <tr>
            <td>POST</td>
            <td>/categories</td>
            <td>Cadastrar uma nova categoria</td>
        </tr>
        <tr>
            <td>PUT</td>
            <td>/categories/&#123;id&#125;</td>
            <td>Editar uma categoria já existente</td>
        </tr>
         <tr>
            <td>DELETE</td>
            <td>/categories/&#123;id&#125;</td>
            <td>Deletar uma categoria já existente</td>
        </tr>
    </tbody>
</table>
</details>

<details>
<summary><strong>Manufacturers</strong></summary>
<br><p>Essa rota tem como objetivo a administração da entidade fabricantes</p>
<table>
    <thead>
        <tr>
            <th>Requisição</th>
            <th>Rota</th>
            <th>Descrição</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>GET</td>
            <td>/categories</td>
            <td>Buscar todos os fabricantes</td>
        </tr>
        <tr>
            <td>POST</td>
            <td>/categories</td>
            <td>Cadastrar um novo fabricante</td>
        </tr>
        <tr>
            <td>PUT</td>
            <td>/categories/&#123;id&#125;</td>
            <td>Editar um fabricante já existente</td>
        </tr>
         <tr>
            <td>DELETE</td>
            <td>/categories/&#123;id&#125;</td>
            <td>Deletar um fabricante já existente</td>
        </tr>
    </tbody>
</table>     
</details>

## 💻 Instalação

Para rodar esse projeto localmente, siga os seguintes passos:
1. Clone esse repositório:
```bash
git clone <repository-url>
```

2. Navegue até o diretório desse projeto:
```bash
cd <project-directory>
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Inicie o servidor:
```bash
python app.py
```

## 📄 Documentação

A documentação completa da API pode ser acessada através do Swagger. Para explorar a documentação, basta abrir a [rota /api-docs](http://127.0.0.1:5000/api/docs/) em seu navegador web. Na documentação, você pode visualizar os esquemas de solicitação e resposta e até mesmo executar operações diretamente. Isso oferece uma maneira conveniente de entender e interagir com a API sem a necessidade de ferramentas ou clientes adicionais.

## 🌙 Insomnia
Para simplificar ainda mais a integração e teste da nossa API, incluí um arquivo do aplicativo Insomnia na pasta base deste projeto. Este arquivo contém uma coleção de rotas prontas para uso, permitindo que você teste rapidamente as funcionalidades da API sem a necessidade de configurar manualmente cada solicitação.

## 👨‍💻 Desenvolvedores

<!--
- [Anderson Menezes](https://github.com/And3rs0nMenezes)
-->

<table align="center">
  <tr align="center">
      <a href="https://github.com/And3rs0nMenezes">
        <img src="https://avatars.githubusercontent.com/And3rs0nMenezes" width=100 />
        <p>Anderson <br/>Menezes</p>
      </a>
    </td>
  </tr>
</table>
