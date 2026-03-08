# 🖥️ Entregável Parcial 3 (EP3) – Prototipação do Wireframe e do Sitemap do MVP

## Plataforma web de doação e reaproveitamento de materiais escolares

Este entregável apresenta a prototipação do **wireframe** e do **sitemap** do MVP da plataforma **Material Solidário**, desenvolvida com foco na doação e reaproveitamento de materiais escolares.

O objetivo desta etapa foi estruturar visualmente as principais telas do sistema, organizando a navegação, os componentes da interface e o fluxo de interação do usuário, com atenção à consistência, usabilidade e acessibilidade.


## 📌 Sitemap do MVP

O sitemap foi elaborado para representar o fluxo de navegação entre as principais telas da plataforma.

A navegação inicia na **Home**, onde o usuário pode acessar as opções de **Login** ou **Cadastro**. Após a autenticação, o usuário é direcionado para o **Dashboard**, que funciona como tela central do sistema. A partir dele, é possível acessar as funcionalidades principais, como cadastro de doação, visualização de materiais disponíveis, acompanhamento das doações e solicitações realizadas.

## 🎨 Wireframes desenvolvidos

Nesta etapa, foram prototipadas as seguintes telas:

- Home
- Login
- Cadastro
- Dashboard

As demais telas do sistema foram desenvolvidas por outro integrante da equipe.

- Cadastrar Doação
- Cadastrar Solicitação
- Minhas Doações
- Minhas Solicitações

---

## 🏠 Tela Home

A tela inicial apresenta a proposta da plataforma e funciona como porta de entrada do sistema.

### Componentes principais:
- Logo do sistema
- Menu de navegação
- Botões de acesso para **Login** e **Cadastro**
- Seção introdutória explicando o objetivo da plataforma
- Área informativa sobre o serviço
- Rodapé com informações institucionais

### Objetivo:
Apresentar a plataforma ao usuário de forma clara e direcioná-lo para o acesso ou criação de conta.

---

## 🔐 Tela de Login

A tela de login foi projetada para permitir que usuários já cadastrados acessem o sistema.

### Componentes principais:
- Header com logo e menu
- Campo de e-mail
- Campo de senha
- Opção de visualizar senha
- Opção “lembrar senha”
- Link “esqueceu a senha?”
- Botão de entrar
- Link para cadastro
- Footer

### Objetivo:
Garantir um acesso simples e rápido à plataforma, com poucos campos e navegação intuitiva.

---

## 📝 Tela de Cadastro

A tela de cadastro permite que novos usuários criem uma conta na plataforma.

### Componentes principais:
- Header com navegação
- Campos de dados pessoais
- Campos de dados de acesso
- Seleção do tipo de usuário
- Campo de situação educacional
- Campos de localização
- Aceite de termos
- Botão de cadastro
- Botão de cancelar
- Opções de cadastro com redes
- Footer

### Objetivo:
Coletar as informações necessárias para o registro do usuário no sistema, de maneira organizada e acessível.

---

## 📊 Tela Dashboard

O dashboard foi pensado como a tela principal após o login, centralizando as funcionalidades do sistema.

### Componentes principais:
- Header com logo, menu e botão de sair
- Mensagem de boas-vindas ao usuário
- Resumo com indicadores do sistema
- Área de atividades recentes
- Cards de navegação para:
  - Cadastrar doação
  - Materiais disponíveis
  - Minhas doações
  - Minhas solicitações
- Footer

## 🎒 Cadastrar Doação

Nesta tela o usuário pode registrar materiais escolares que deseja disponibilizar para doação. O formulário permite informar detalhes do material, quantidade e outras informações relevantes.

### Campos da tela:
- Nome do material
- Descrição
- Estado do material (novo ou usado)
- Quantidade disponível

Botões da tela:
Adicionar Doação
- Registra o material no sistema e o torna disponível para solicitação por outros usuários.
Cancelar
- Cancela o cadastro da doação e retorna ao Dashboard.


## 📦 Cadastrar Solicitação

A tela de Cadastrar Solicitação permite que usuários solicitem materiais disponíveis no sistema. Dessa forma, pessoas que precisam de determinados itens podem registrar suas demandas.
Nesta tela o usuário pode registrar materiais escolares que deseja disponibilizar para doação.

### Campos da tela:

- Seleção do material desejado
- Quantidade solicitada
- Observações (opcional)

Botões da tela:
- Solicitar
Registra o pedido do material no sistema.
- Cancelar
Interrompe a solicitação e retorna ao Dashboard.

## 🤝 Minhas Doações

Nesta área o usuário pode visualizar e acompanhar todas as doações que cadastrou, permitindo acompanhar os materiais disponibilizados e sua situação dentro da plataforma.

### Cada item exibido mostra informações como:

- nome do material
- quantidade
- estado do material
- status da doação

Botões da tela:
- Editar
Permite alterar informações da doação cadastrada.
- Remover
Exclui a doação do sistema.

## 📥 Minhas Solicitações

A tela Minhas Solicitações permite que o usuário acompanhe os pedidos de materiais realizados, visualizando o status de cada solicitação feita no sistema.

### Cada solicitação apresenta informações como:

- material solicitado
- quantidade
- status da solicitação

Possíveis status:
- Em análise
- Aprovado
- Recusado

Botões da tela:
- Visualizar detalhes
Mostra informações mais detalhadas sobre a solicitação.
- Cancelar solicitação
Permite cancelar o pedido caso ele ainda não tenha sido aprovado.

### Objetivo:
Servir como painel principal de navegação, facilitando o acesso rápido às funcionalidades do sistema e apresentando informações resumidas ao usuário.

---

## 🧠 Consistência, usabilidade e acessibilidade

O desenvolvimento dos wireframes buscou seguir princípios de **design centrado no usuário**, priorizando clareza visual, simplicidade de navegação e organização das informações.

### Consistência
As telas foram desenvolvidas com estrutura visual padronizada, mantendo elementos como header, footer, tipografia, botões e organização de conteúdo de forma semelhante entre as páginas.

### Usabilidade
A navegação foi pensada para ser intuitiva, permitindo que o usuário localize rapidamente as principais funcionalidades do sistema. Foram priorizados fluxos simples, com poucos passos para ações importantes como entrar, cadastrar-se e acessar recursos do dashboard.

### Acessibilidade
A prototipação considerou aspectos como:
- organização clara dos elementos
- textos objetivos
- campos identificáveis
- navegação previsível
- contraste visual entre áreas e botões

Esses cuidados ajudam a tornar a interface mais compreensível e acessível para diferentes perfis de usuários.

---

## 🌍 Componente extensionista

A prototipação de wireframes é importante porque permite visualizar e organizar a interface de um sistema antes do desenvolvimento, ajudando a identificar problemas de navegação, excesso de informação ou ausência de elementos importantes, como foi encontrado aqui, ao iniciar o desenvolvimento deste wireframe, percebi que o gostaria de ter mas informações no cadastro do usuário, porém o Banco Mysql não possuia todos os elementos, deste modo, retorneamos à atividade anterior e realizados o ajuste na tabela Cadastro.

O **design centrado no usuário** contribui diretamente para a melhoria da qualidade dos sistemas utilizados no dia a dia, pois considera as necessidades reais das pessoas, sua forma de interação com a tecnologia e as dificuldades que podem surgir no uso da interface. Quando um sistema é projetado com foco no usuário, ele tende a ser mais intuitivo, acessível, eficiente e inclusivo, gerando impacto positivo na experiência das pessoas e na sociedade.

---

## 🛠️ Ferramentas utilizadas

- Miro
- GitHub
- MySQL Workbench (nas etapas anteriores de modelagem)

---

## 📷 Protótipos

As imagens dos wireframes e do sitemap foram adicionadas a este repositório para representar visualmente a estrutura do MVP.

## Documentação do Projeto Material Solidário
