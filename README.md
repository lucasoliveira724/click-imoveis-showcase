# 🏠 Click Imóveis

### Plataforma Digital para o Mercado Imobiliário

A **Click Imóveis** é uma solução digital desenvolvida para modernizar a apresentação e o gerenciamento de imóveis, reunindo **plataforma web, painel administrativo e aplicativo mobile** em um mesmo ecossistema.

O projeto foi desenvolvido com foco em experiência do usuário, organização das informações dos imóveis e evolução contínua da operação digital.

> Este repositório apresenta o case, arquitetura e principais funcionalidades do projeto.  
> O código-fonte completo é mantido em repositórios privados.

---

## 📌 Sobre o projeto

A proposta da Click Imóveis é oferecer uma experiência digital moderna tanto para clientes que procuram imóveis quanto para a equipe responsável por administrar o catálogo.

A solução foi estruturada em diferentes frentes:

- 🌐 Plataforma web para apresentação dos imóveis;
- ⚙️ Painel administrativo para gerenciamento do catálogo;
- 📱 Aplicativo mobile para consulta de imóveis;
- ☁️ Serviços em nuvem para armazenamento e gerenciamento dos dados.

---

## 🎯 Desafio

O projeto precisava criar uma experiência digital capaz de centralizar as informações dos imóveis e facilitar sua apresentação aos clientes em diferentes dispositivos.

Além da experiência pública, também era necessário disponibilizar uma estrutura que permitisse administrar os imóveis sem depender de alterações diretamente no código da aplicação.

---

## 💡 Solução

A solução foi desenvolvida como um ecossistema composto por aplicações web e mobile conectadas aos serviços utilizados pela plataforma.

```text
                    CLICK IMÓVEIS
                         │
             ┌───────────┴───────────┐
             │                       │
        🌐 Plataforma Web        📱 Aplicativo
             │                       │
          Next.js               React Native
             │                       │
             └───────────┬───────────┘
                         │
                      Firebase
                         │
                 Dados dos imóveis
```

Essa arquitetura permite evoluir as diferentes experiências da plataforma mantendo uma base centralizada para os dados.

---

## 🌐 Plataforma Web

A plataforma web foi desenvolvida para apresentar os imóveis de forma organizada, visual e responsiva.

### Principais recursos

- Catálogo de imóveis;
- Visualização de informações e detalhes;
- Interface responsiva;
- Identidade visual da Click Imóveis;
- Integração com os dados dos imóveis;
- Estrutura preparada para evolução da captação de leads.

---

## ⚙️ Painel Administrativo

O projeto também possui uma área administrativa responsável pelo gerenciamento das informações exibidas na plataforma.

O objetivo é permitir que novos imóveis e suas informações sejam administrados sem necessidade de alterações diretamente no código da aplicação.

---

## 📱 Aplicativo Mobile

Como evolução do ecossistema digital, também foi desenvolvido um aplicativo mobile da Click Imóveis.

O aplicativo oferece uma experiência dedicada para dispositivos móveis e mantém a identidade visual utilizada na plataforma.

### Principais recursos

- Consulta de imóveis;
- Visualização de detalhes;
- Interface otimizada para dispositivos móveis;
- Sistema de favoritos;
- Integração com os dados da plataforma;
- Estrutura preparada para contato e geração de leads.

---

## 🛠️ Tecnologias utilizadas

### Web

`Next.js` `React` `JavaScript / TypeScript` `HTML` `CSS`

### Mobile

`React Native` `Expo`

### Backend e serviços

`Firebase`

### Desenvolvimento e versionamento

`Git` `GitHub` `VS Code`

---

## 👨‍💻 Minha participação

Minha atuação no projeto envolve diferentes etapas da construção e evolução da solução, incluindo:

- Desenvolvimento da plataforma web;
- Desenvolvimento e evolução do aplicativo mobile;
- Implementação de interfaces responsivas;
- Estruturação das informações dos imóveis;
- Integração com Firebase;
- Desenvolvimento de funcionalidades;
- Versionamento com Git e GitHub;
- Builds e testes do aplicativo;
- Planejamento de novas funcionalidades e integrações.

O projeto também é utilizado como ambiente para explorar novas formas de aplicar **automação e Inteligência Artificial** a processos do mercado imobiliário.

---

## 📸 Demonstração

### Plataforma Web

> Screenshots da plataforma serão adicionados nesta seção.

### Aplicativo Mobile

> Screenshots do aplicativo serão adicionados nesta seção.

---

## 🚀 Evolução do projeto

A Click Imóveis continua sendo evoluída com novas funcionalidades e possibilidades de automação.

Entre as evoluções estudadas está o **cadastro inteligente de imóveis através do WhatsApp com apoio de Inteligência Artificial**.

A proposta é permitir que o corretor envie as informações de um imóvel de maneira natural pelo WhatsApp e que a solução transforme esses dados em informações estruturadas para cadastro.

```text
Corretor
   │
   ▼
WhatsApp
   │
   ▼
Inteligência Artificial
   │
   ▼
Interpretação e estruturação
   │
   ▼
Cadastro do imóvel
   │
   ▼
Click Imóveis
```

> Essa funcionalidade representa uma evolução planejada do projeto e não faz parte da versão atualmente apresentada neste case.

---

## 🔒 Código-fonte

Por se tratar de um projeto real e em evolução, o **código-fonte completo é mantido em repositórios privados**.

Este repositório foi criado exclusivamente para apresentar o projeto, suas funcionalidades, arquitetura, tecnologias utilizadas e evolução.

---

## 👤 Desenvolvedor

**Lucas Oliveira**

Analista de Sistemas | Salesforce Marketing Cloud | Desenvolvimento Web | Automação & IA

[GitHub](https://github.com/lucasoliveira724)
