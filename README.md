# 💙 ONG Grupo Amparo e Alívio - Frontend

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Version](https://img.shields.io/badge/Version-1.0.0-orange)

Bem-vindo ao repositório Front-end do ecossistema digital da ONG **Grupo Amparo e Alívio (GAA)**. 

Este projeto foi desenhado para conectar profissionais de saúde voluntários à comunidade. Ele é dividido em duas partes essenciais: uma **Landing Page Institucional** para captação de voluntários/doações e um **Painel Administrativo** para gestão completa desses cadastros.

> **Nota:** Este projeto consome uma API Backend em Java Spring Boot. Para funcionalidade completa do Dashboard, o backend deve estar rodando localmente ou na nuvem.

---

## 🎨 Visão Geral do Projeto

O projeto é composto por dois módulos principais:

### 1. 🌐 Landing Page (Institucional)
A porta de entrada da ONG. Desenvolvida com foco em UX/UI para transmitir confiança e acolhimento.
* **Design Responsivo:** Adapta-se perfeitamente a celulares, tablets e desktops.
* **Navegação Fluida:** Menu com scroll suave (smooth scroll).
* **Seções Informativas:** História, Serviços, Galeria de Fotos e Depoimentos.
* **Call-to-Action (CTA):** Botões estratégicos para "Seja um Voluntário" e "Faça uma Doação".

### 2. ⚙️ Sistema de Gestão (Dashboard)
A área restrita para administração dos voluntários cadastrados.
* **CRUD Completo:** Criar, Ler, Atualizar e Inativar voluntários via Fetch API.
* **Filtros Dinâmicos:** Busca em tempo real por nome, profissão ou CPF.
* **Gestão de Disponibilidade:** Lógica complexa para adicionar múltiplos períodos de horários e cálculo automático de horas semanais.
* **Feedback Visual:** Modais interativos, toasts de alerta e indicadores de status (Ativo/Inativo).

---

## 🚀 Tecnologias Utilizadas

O foco deste projeto foi o domínio da base da web, sem dependência de frameworks pesados (como React ou Angular), garantindo leveza e performance.

* ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) **HTML5 Semântico**
* ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) **CSS3 Moderno** (Flexbox, Grid, Variáveis CSS, Gradientes)
* ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **Vanilla JS (ES6+)**
* ![Lucide](https://img.shields.io/badge/Icons-Lucide-pink?style=flat-square) **Lucide Icons** (Ícones vetoriais leves)

---

## 📂 Estrutura do Projeto

A organização de pastas separa claramente o conteúdo público do administrativo:

Frontend/ │ ├── Imagens/ # Logos, fotos da ONG e ícones │ ├── LP/ # MÓDULO PÚBLICO │ ├── LP.html # Página Principal (Landing Page) │ └── styleLP.css # Estilização da Landing Page │ ├── Formulario/ 
# MÓDULO ADMINISTRATIVO │ ├── cadastro.html # Formulário de cadastro externo │ └── ... │ ├── Acesso/ # SISTEMA DE GESTÃO │ ├── acesso.html # Dashboard Principal (Tabela e Modais) │ └── acesso.css # Estilos do Dashboard │ └── README.md # Documentação


---

## 🔧 Como Rodar Localmente
Este é um projeto estático, mas depende da API.

### Pré-requisitos
1.  Certifique-se de que o **Backend Spring Boot** esteja rodando na porta `8080`.
2.  Banco de dados configurado no Backend.

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/GabrieldePaulaDev/Frontend_ONG.git](https://github.com/GabrieldePaulaDev/Frontend_ONG.git)
    ```

2.  **Acesse a Landing Page:**
    * Navegue até a pasta `LP`.
    * Abra o arquivo `LP.html` no seu navegador.

3.  **Acesse o Sistema de Gestão:**
    * Navegue até a pasta `Acesso` (ou onde salvou o `acesso.html` final).
    * Abra o arquivo `acesso.html`.
    * *Dica:* Se os dados não carregarem, verifique no console do navegador (`F12`) se a conexão com `http://localhost:8080` foi estabelecida.

---

## 📸 Screenshots

### Landing Page
*(Espaço para colocar um print da LP)*

### Dashboard de Gestão
*(Espaço para colocar um print da Tabela de Voluntários)*

### Modal de Edição
*(Espaço para colocar um print do Modal com a gestão de horários)*

---

## 👨‍💻 Autor

Desenvolvido pelo grupo **Techcare** como parte do Projeto Interdisciplinar Fatec.
