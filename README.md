# GitHub Profile Finder 🔍

Um buscador de perfis do GitHub que exibe informações do usuário e seus repositórios de forma elegante e responsiva.

## 📋 Sobre o Projeto

Esta aplicação permite buscar usuários do GitHub e visualizar suas informações públicas, incluindo:
- Foto de perfil
- Nome e bio
- Lista dos 5 repositórios mais recentes

## 🚀 Funcionalidades

- ✅ Busca por nome de usuário do GitHub
- ✅ Busca tanto por clique no botão quanto pressionando Enter
- ✅ Exibição de informações do perfil
- ✅ Lista de repositórios com links diretos
- ✅ Interface responsiva
- ✅ Tratamento de dados ausentes (nome e bio)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização e design responsivo
- **JavaScript ES6+** - Lógica da aplicação
- **GitHub API** - Consumo de dados
- **Módulos JavaScript** - Organização do código

## 🔧 Como Usar

1. **Busca por clique:**
   - Digite o nome de usuário do GitHub no campo de busca
   - Clique no botão "Buscar"

2. **Busca por tecla Enter:**
   - Digite o nome de usuário
   - Pressione Enter para realizar a busca

## ⚙️ Configuração da API

A aplicação utiliza a API pública do GitHub:
- **URL Base:** `https://api.github.com/users`
- **Quantidade de repositórios:** 5 (configurável)

## 🎯 Características Técnicas

### Arquitetura Modular
O código está organizado em módulos ES6 para melhor manutenibilidade:

- **Separação de concerns** (preocupações)
- **Reutilização de código**
- **Facilidade de testes**

### Tratamento de Erros
- Mensagens amigáveis para dados não encontrados
- Validação de campos vazios
- Feedback visual para o usuário

### Performance
- Requisições assíncronas com async/await
- Renderização eficiente da interface
- Cache de dados através do objeto user

## 🔄 Fluxo da Aplicação

1. Usuário insere nome de usuário
2. Requisição para API do GitHub (dados do usuário)
3. Requisição para API do GitHub (repositórios)
4. Processamento e formatação dos dados
5. Renderização na tela

## 🌟 Próximas Melhorias

- [ ] Adicionar loading durante as requisições
- [ ] Tratamento de erros de API
- [ ] Cache local para buscas recentes
- [ ] Paginação de repositórios
- [ ] Modo escuro/claro
- [ ] Exportação de dados do perfil

## 👨‍💻 Desenvolvimento

### Pré-requisitos
- Navegador moderno com suporte a módulos ES6
- Servidor local (devido ao CORS dos módulos)

