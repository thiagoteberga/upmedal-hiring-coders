# Desafio#3 - E-commerce para o cliente UPMedal.com - VTEX.IO
Desenvolvido durante o Hiring Coders (Em parceria com a Gama Academy)

### Enunciado:
Você foi contratado para desenvolver o ecommerce do seu novo cliente, a UPMedal.com.

### Template de criação
Criar a solução a partir de um [boiler template padrão da Vtex IO](https://github.com/vtex-apps/minimum-boilerplate-theme).

### Layout
- Veja o Layout [clicando aqui](https://www.upmedal.com/desafios). Observação - A réplica não precisa ser uma cópia fiel deste layout mas tentar se aproximar o máximo que conseguir.
- Utilizar o [Markdown](https://pt.wikipedia.org/wiki/Markdown) + o css para formatação.

## To Do List:
- [x] [Flex Layout](https://vtex.io/docs/components/all/vtex.flex-layout@0.17.0/) para criar as cores em css.
- [x] Dar prioridade as páginas criada nos arquivos.jsonc colocando comentários dos blocos criados
- [x] Utilizar o [Slider layout](https://vtex.io/docs/app/vtex.slider-layout) para mostrar os produtos em destaque.
- [x] Criar um componente [Tab Layout](https://vtex.io/docs/components/all/vtex.tab-layout@0.4.3/) para separar os produtos por categoria.
- [x] Criar um [bloco de lista de produtos](https://vtex.io/docs/app/vtex.product-list@0.31.0/) (Sugestão paginado por 8 itens da categoria).
- [x] Criar [Minicard](https://vtex.io/docs/components/content-blocks/vtex.minicart@2.60.0/) para lista dos produtos no carrinho.
- [x] Ao clicar no produto ir para tela com [Product Summary](https://vtex.io/docs/components/all/vtex.product-summary@2.53.0/).
- [x] Responsivo - Layout Mobile
- [x] Criar um componente customizado para falar com suporte no whatsapp, no rodapé [Utilizar o Vtex Componentes com React para criar o componente](https://vtex.io/docs/components/all/vtex.store-components@3.150.0/) - [API whatsapp](https://www.convertte.com.br/gerador-link-whatsapp/).
- [ ] Criar um componente customizado para cadastrar leads (possíveis clientes prospectos), pegar o Nome, Email e Telefone. Este componente pode servir de isca digital, dando uma bonificação para o prospecto que preencher as informações da lead. [Utilizar o Vtex Componentes com React para criar o componente](https://vtex.io/docs/components/all/vtex.store-components@3.150.0/). Mais sugestões para ajudar no layout: [Um](https://vtex.io/docs/getting-started/desenvolva-componentes-usando-vtex-io-e-react/5) e [Dois](https://vtex.io/docs/components/all/vtex.stack-layout@0.1.0/).
- [ ] AWS API Gateway - Com o objetivo de armazenar as leads que o Vtex componente irá utilizar no React, [criar uma API Gateway na AWS para colocar as informações](https://aws.amazon.com/pt/api-gateway/). Um exemplo de arquivo API Gateway para estudo: [Um](https://github.com/awslabs/aws-api-gateway-developer-portal/blob/master/cloudformation/template.yaml), [Dois](https://github.com/mattpodolak/email-api-lambda) e [Tres](https://github.com/amazon-archives/realworld-serverless-application/blob/master/backend/sam/app/api.template.yaml).



# Links Úteis:
## Meu Workspace:
https://upmedalthiagoteberga--hiringcoders2021.myvtex.com

## Exemplo de Manifest:
https://github.com/vtex-apps/store-theme/blob/master/manifest.json

## Página dos Cursos:
https://learn.vtex.com/page/learning-path-lang-pt

## Developers - VTEX - Explicação dos Componentes:
https://developers.vtex.com/vtex-developer-docs/docs/

## Sintaxes Básicas de Markdown - para Git:
https://docs.github.com/pt/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax



# Comandos utilizados:

``` bash
# NPM Install Dependencies:
npm i -g vtex

# Login na conta para o desenvolvimento:
vtex login hiringcoders2021

# Comando para confirmar a conta e a área de trabalho:
vtex whoami

# Listar os Links da conta:
vtex list

# Se existir algum Link, remover:
vtex unlink --all

# Listar os Workspaces criados:
vtex workspace list

# Criar a workspace para desenvolvimento:
vtex use upmedalthiagoteberga

# Linkar o workspace com a máquina local
vtex link

# Instalar algumas dependências
vtex install vtex.store-sitemap vtex.store -f

```
