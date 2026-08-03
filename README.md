<div align="center">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&height=115&section=header&color=0:5C5C5C,50:6F6F6F,100:828282&animation=twinkling"
    alt="Cabeçalho"
  />  
</div>

<div align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=23&duration=2800&pause=1000&color=828282&center=true&vCenter=true&width=820&height=75&lines=Primeira+vers%C3%A3o+do+card%C3%A1pio+digital+do+Tobias+Lanches"
    alt="Cardápio Digital Tobias Lanches"/>
</div>


<div align="center">
  <p>
    Está versão foi muito usada e é a primeira versão do Cardápio Digital do Tobias lanches!
  </p>

  <p>
    <a href="https://vercel.app">
      <img src="https://img.shields.io/badge/Projeto_ao_vivo-0D1117?style=for-the-badge&logo=vercel&logoColor=828282" alt="Projeto ao vivo"/>
    </a>
    <a href="https://github.com">
      <img src="https://img.shields.io/badge/Vers%C3%A3o_2.0-0D1117?style=for-the-badge&logo=github&logoColor=828282" alt="Versão 2.0"/>
    </a>
  </p>
</div>


<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

## Sobre o Projeto

Criei este projeto com um objetivo bem claro: resolver a confusão dos pedidos por WhatsApp. Eu queria algo que fosse além de um PDF estático, uma ferramenta em que o cliente pudesse navegar com facilidade e que me desse a liberdade de alterar um preço ou trocar a descrição de um lanche sem precisar mexer em uma única linha de código.

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

## Por que construí isso?

Com o objetivo de testar os meus conhecimentos em HTML, CSS e JS que adquiri ao longo do tempo, pensei em realizar um projeto que sanasse uma dor muito comum na minha região. Notei que muitos **quiosques e lanchonetes** perdem vendas ou demoram a atender porque o processo é manual e demorado demais. 

Minha ideia foi centralizar tudo em uma interface web simples e rápida que já envia o pedido pronto para o atendente. O foco aqui é a experiência de quem está com fome: abrir o link, escolher o que quer e finalizar o pedido sem complicação.

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

## Recursos e Funcionalidades

### Área Pública (Catálogo)
A primeira versão já entrega a base central da experiência do usuário final:

* Navegação estruturada por categorias de produtos.
* Visualização detalhada de itens com nome, descrição e preço.
* Organização simples segregada entre lanches, bebidas e adicionais.
* Interface responsiva totalmente otimizada para leitura rápida no celular.

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

### Integração com WhatsApp
O fluxo principal da aplicação consiste em transformar a escolha do cliente em um payload pronto para envio.

* Seleção dinâmica dos itens diretamente pela interface.
* Revisão em tempo real do pedido antes da confirmação.
* Montagem automatizada da mensagem de texto de forma legível.
* Abertura direta do WhatsApp Web ou Aplicativo com o conteúdo formatado.

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

### Gestão Administrativa Local
Mesmo sendo um MVP de primeira iteração, o sistema conta com uma área de controle interna.

* Cadastro ágil de novos produtos no catálogo.
* Edição simplificada das informações existentes.
* Remoção de itens em tempo de execução.
* Atualização do conteúdo sem necessidade de alteração na estrutura do código.

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

## Arquitetura

### Matriz de Funcionalidades Técnicas

| Módulo | Escopo Operacional | Implementação Técnica |
| --- | --- | --- |
| **Catálogo Público** | Navegação, filtros e seleção de produtos | Renderização de nós DOM via JavaScript |
| **Integração WhatsApp** | Formatação de payload e redirecionamento | API Link (`wa.me`) com strings sanitizadas |
| **Painel Admin** | CRUD local de itens do cardápio | Manipulação de arrays de objetos e estado |
| **Persistência de Dados** | Armazenamento de informações da demo | Gravação direta na API de `localStorage` |

<br>

<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

### Estrutura de Arquivos Principais

| Arquivo / Área | Função Estrutural no Sistema |
| --- | --- |
| `index.html` | Ponto de entrada principal da interface do cardápio público. |
| Painel Admin | Tela dedicada ao gerenciamento local do catálogo de lanches. |
| Supabase Database (PostgreSQL) | Utilizado para armazenamento de dados. |

<br>
<div align="center">
  <img
    width="72%"
    height="1"
    src="https://capsule-render.vercel.app/api?type=rect&height=1&color=0:5C5C5C,50:828282,100:5C5C5C"
    alt=""
  />
</div>

<br>

## Como funciona esta demonstração

Esta versão foi totalmente preservada como a primeira iteração funcional do projeto para servir de portfólio de evolução técnica.

A arquitetura desta V1 **não depende** de:
* Banco de dados relacional externo.
* Mecanismos de autenticação online.
* Infraestrutura de servidores ou deploys complexos.

O objetivo aqui é manter a base original da solução totalmente navegável do lado do cliente (client-side), exibindo com clareza a evolução conceitual do sistema antes de sua migração na v2.0.

<br>

## Tecnologias Utilizadas

* **Frontend:** HTML5, CSS3, JavaScript.
* **Armazenamento de Dados:** `localStorage` API (Quando estava em uso, o **Supabase** era usado.)
* **Hospedagem:** Vercel

<br>

## Licença e Uso

Este projeto é disponibilizado exclusivamente para fins de visualização, consulta de código e portfólio.

Não são permitidos sob nenhuma hipótese:
* Distribuição de cópias sem prévia autorização.
* Modificação de arquivos com intuito de redistribuição comercial.
* Uso comercial direto ou indireto sem o consentimento do autor.

Todos os direitos são estritamente reservados.

<br>

<div align="center">
  <p>Desenvolvido por <b>Kayron Magalhães</b></p>
</div>
