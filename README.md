<div align="center">
  <h1>Cardápio Digital - Tobias Lanches</h1>
  <p><b>Solução para gestão de produtos e integração de pedidos via WhatsApp</b></p>
  <a href="https://democardapio-digital-tobias-lanches.vercel.app/"><b>Ver projeto</b></a>
  <br><br>
  <p>Esta foi a primeira versão do projeto. A evolução dessa solução continuou no <a href="https://github.com/kayronmagl/Cardapio-Digital-v2.0"><b>Cardápio Digital v2.0</b></a>.</p>
</div>

## Sobre o Projeto

Criei este projeto com um objetivo bem claro: resolver a confusão dos pedidos por WhatsApp. Eu queria algo que fosse além de um PDF estático, uma ferramenta em que o cliente pudesse navegar com facilidade e que me desse a liberdade de alterar um preço ou trocar a descrição de um lanche sem precisar mexer em uma única linha de código.

## Por que construí isso?

Em razão de testar meus conhecimentos em HTML, CSS E JS que adquiri ao longo do tempo, pensei em realizar um projeto que sanasse uma dor relativamente comum localmente, e notei que muitos **quiosques e lanchonetes** perdem vendas ou demoram a atender porque o processo é manual demais. Minha ideia foi centralizar tudo em uma interface web simples e rápida que já envia o pedido pronto para o atendente. O foco aqui é a experiência de quem está com fome: abrir o link, escolher o que quer e finalizar o pedido sem complicação.

## Funcionalidades Principais

### Catálogo público
A primeira versão já entrega a base central da experiência:

- navegação por categorias
- visualização de produtos com nome, descrição e preço
- organização simples entre lanches, bebidas e adicionais
- interface pensada para leitura rápida no celular

### Pedido direto pelo WhatsApp
O fluxo principal do projeto é transformar a escolha do cliente em um pedido pronto para envio.

- seleção dos itens na própria interface
- revisão do pedido antes do envio
- montagem automática da mensagem
- abertura direta do WhatsApp com o conteúdo formatado para atendimento

### Gestão administrativa
Mesmo sendo a primeira versão, o projeto já conta com um painel para manutenção do cardápio.

- cadastro de produtos
- edição de informações do catálogo
- remoção de itens
- atualização do conteúdo sem precisar alterar manualmente a estrutura principal da página

### Persistência local da demonstração
Nesta versão, a demonstração funciona de forma local no navegador.

- os dados ficam armazenados em `localStorage`
- a edição pode ser mantida no próprio navegador
- o projeto continua funcional sem depender de banco de dados ou integração online

### Foco em mobile
Desde a primeira versão, a experiência foi pensada para uso prático em smartphones.

- navegação simples
- leitura rápida
- interação direta com o catálogo
- fluxo de pedido adaptado ao uso no celular

## Tecnologias Utilizadas

### Frontend
- HTML5
- CSS3
- JavaScript Vanilla

### Persistência da demonstração
- `localStorage`

### Execução
- demonstração local da primeira versão do sistema

## Estrutura principal

| Arquivo / área | Função |
| --- | --- |
| `index.html` | entrada principal do cardápio |
| painel Admin | gerenciamento local do catálogo |
| armazenamento local | persistência dos dados da demonstração no navegador |

## Como funciona esta demonstração

Esta versão foi preservada como a primeira iteração funcional do projeto.

Ela não depende de:
- banco de dados
- autenticação online
- deploy obrigatório
- infraestrutura externa para funcionar

O objetivo aqui é manter a base original da solução como demonstração navegável, mostrando como o projeto começou antes da evolução para a v2.0.

## Licença e Uso

Este projeto é disponibilizado para visualização e consulta da solução.

Não é permitida:
- distribuição sem autorização
- modificação para redistribuição
- uso comercial sem autorização prévia do autor

Todos os direitos são reservados.

<br>
<div align="center">
  <p>Desenvolvido por <b>Kayron Magalhães</b></p>
</div>
