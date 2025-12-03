# 🤝 Gestão de Voluntários - Frontend

![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

Uma interface moderna, limpa e responsiva desenvolvida para facilitar o cadastro e a gestão de voluntários da ONG **Grupo Amparo e Alívio**. Este projeto foca na experiência do usuário (UX), permitindo administração rápida de perfis, controle de status e gestão complexa de horários de disponibilidade.

> **Nota:** Este é o repositório do Frontend. O Backend (API) deve estar rodando para que o sistema funcione completamente.

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído sem dependência de frameworks pesados, focando no domínio da linguagem pura:

* ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) **HTML5 Semântico**
* ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) **CSS3 Moderno** (Flexbox, Grid, Variáveis CSS)
* ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) **Vanilla JS (ES6+)**
* ![Lucide](https://img.shields.io/badge/Icons-Lucide-pink?style=flat-square) **Lucide Icons** (Ícones leves e vetorizados)

---

## ✨ Funcionalidades

### 🖥️ Dashboard Interativo
* **Listagem Completa:** Visualização tabular dos voluntários cadastrados.
* **Filtros Dinâmicos:** Pesquisa em tempo real por nome, profissão ou CPF sem recarregar a página.
* **Filtro de Status:** Abas para alternar rapidamente entre voluntários "Todos", "Ativos" e "Inativos".

### 📝 Gestão de Cadastro (CRUD)
* **Adicionar Voluntário:** Formulário em Modal com validação de campos.
* **Edição Inteligente:** Carrega os dados existentes (incluindo horários) para atualização.
* **Exclusão Lógica (Soft Delete):** Inativa o voluntário sem perder o histórico.
* **Reativação:** Permite trazer voluntários inativos de volta à base ativa com um clique.

### 🕒 Gestão Avançada de Disponibilidade
* **Lista Dinâmica:** Adicione múltiplos períodos de disponibilidade (Dia + Hora Início + Hora Fim).
* **Cálculo Automático:** O sistema calcula automaticamente o total de horas semanais com base nos períodos inseridos.
* **Visualização:** Lista visual com opção de remover horários individuais antes de salvar.

---

## 📸 Screenshots

*(Espaço reservado para você colocar prints da tela. Sugestão: Tire prints do Dashboard e do Modal de Cadastro)*

---

## 🔧 Como Rodar o Projeto

Este é um projeto estático, mas depende da API.

### Pré-requisitos
1.  Certifique-se de que o **Backend Spring Boot** esteja rodando na porta `8080`.
2.  Banco de dados configurado no Backend.

### Passo a Passo

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/seu-repo-frontend.git](https://github.com/seu-usuario/seu-repo-frontend.git)
    ```

2.  **Abra o projeto:**
    Navegue até a pasta do projeto.

3.  **Execute:**
    * Você pode simplesmente abrir o arquivo `acesso.html` no seu navegador.
    * **Recomendado:** Use a extensão **"Live Server"** do VS Code para evitar problemas de cache ou bloqueios de CORS locais.

---

## 📂 Estrutura de Pastas
