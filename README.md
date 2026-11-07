# Sistema de Autenticação - Expresso Login

Aplicação front-end desenvolvida para simulação e gerenciamento do fluxo de autenticação de usuários, contendo layout personalizado, animações CSS nativas e manipulação de tokens no armazenamento local do navegador.

---

## Visão Geral do Projeto

Este projeto foi construído para demonstrar a implementação de uma interface de login moderna e responsiva. Além da camada visual, a aplicação simula o comportamento de integração com APIs de autenticação através do processamento de credenciais, exibição de estados de carregamento e persistência de dados de sessão.

---

## Funcionalidades e Arquitetura

* **Layout Split Screen:** Estrutura dividida entre área visual temática e formulário de acesso estilizado na cor principal (#78004f).
* **Tratamento de Erros:** Exibição de mensagens de alerta integradas ao layout e alinhadas dinamicamente via CSS Flexbox.
* **Componente de Carregamento:** Overlay animado em CSS puro que simula uma caneca com fumaça em movimento durante a transição de autenticação.
* **Simulação de Token JWT:** Processamento e codificação em Base64 de dados de acesso simulados (access_token) com tempo de expiração.
* **Persistência Local:** Gravação automática do token de acesso no LocalStorage para controle do estado da sessão.

---

## Tecnologias Utilizadas

* **HTML5:** Estruturação semântica dos elementos de formulário, áreas de feedback e contêineres de animação.
* **CSS3:** Estilização responsiva, alinhamentos com Flexbox e uso de regras @keyframes para a animação da fumaça.
* **JavaScript (ES6+):** Controle de eventos da DOM, validação de entradas de usuário e gerenciamento da API de Storage.

---

## Credenciais de Teste

| Campo | Valor de Teste |
| :--- | :--- |
| **Usuário** | `admin` |
| **Senha** | `1234` |

---

## Instruções de Execução

1. Clone este repositório para o seu ambiente local:
   ```bash
   git clone [https://github.com/vitoriakarolinaS/login-expresso.git](https://github.com/vitoriakarolinaS/login-expresso.git)