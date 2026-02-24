# 📦 Material Stock Manager

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## 🌟 Visão Geral do Projeto

O **Material Stock Manager** é um sistema robusto de gerenciamento de estoque e materiais, desenvolvido com **Django**. Este projeto visa otimizar o controle de equipamentos, peças, movimentações, manutenções e certificações, proporcionando uma ferramenta eficiente para a gestão de recursos materiais. Ideal para pequenas e médias empresas ou para uso pessoal, o sistema oferece uma interface intuitiva para acompanhar o ciclo de vida dos itens em estoque, desde a aquisição até a baixa ou manutenção.

## ✨ Funcionalidades Principais

O sistema foi projetado para oferecer um controle abrangente, incluindo as seguintes funcionalidades:

*   **Gestão de Equipamentos**: Cadastro detalhado de equipamentos, incluindo informações como tipo, status, localização e histórico.
*   **Controle de Peças**: Gerenciamento de peças de reposição, associando-as a equipamentos e registrando seu uso.
*   **Movimentação de Materiais**: Registro de entradas e saídas de materiais, com rastreamento de tipo de movimentação, status e colaborador responsável.
*   **Manutenção de Equipamentos**: Agendamento e acompanhamento de manutenções, com registro de status e histórico.
*   **Notificações**: Sistema de notificações para alertar sobre eventos importantes, como baixos níveis de estoque ou manutenções pendentes.
*   **Certificações**: Gerenciamento de certificações de equipamentos e colaboradores, com controle de validade.
*   **Gestão de Fornecedores**: Cadastro e controle de informações de fornecedores.
*   **Localização de Estoque**: Organização de materiais por localização física.
*   **Relatórios em PDF**: Geração de relatórios em formato PDF para análise e auditoria.
*   **QR Code para Equipamentos**: Implementação de QR Codes para identificação rápida e fácil de equipamentos.

## 🛠️ Pilha Tecnológica

Este projeto demonstra o uso de tecnologias web consolidadas para um sistema de gerenciamento eficiente:

*   **Backend**: Desenvolvido com **Python** e o framework **Django**, garantindo segurança, escalabilidade e um desenvolvimento rápido.
*   **Banco de Dados**: Utiliza **SQLite** para desenvolvimento e pode ser facilmente configurado para **PostgreSQL** em ambientes de produção.
*   **Frontend**: Construído com **HTML** e **CSS**, com foco em uma interface funcional e responsiva.
*   **Geração de Relatórios**: Implementação de funcionalidades para exportação de dados em **PDF**.
*   **Identificação**: Geração e leitura de **QR Codes** para otimização do controle de equipamentos.

## 🚀 Como Começar

Para configurar e executar o projeto em seu ambiente local, siga as instruções abaixo:

### Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas:

*   Python (versão 3.x)
*   pip (gerenciador de pacotes Python)

### Instalação

1.  **Clone o repositório**:

    ```bash
    git clone https://github.com/Dalmocabral/controle_de_estoque_material.git
    cd controle_de_estoque_material
    ```

2.  **Crie e ative um ambiente virtual**:

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: .\venv\Scripts\activate
    ```

3.  **Instale as dependências**:

    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute as migrações do banco de dados**:

    ```bash
    python manage.py migrate
    ```

5.  **Crie um superusuário (opcional, para acesso ao painel administrativo do Django)**:

    ```bash
    python manage.py createsuperuser
    ```

6.  **Inicie o servidor de desenvolvimento do Django**:

    ```bash
    python manage.py runserver
    ```

    O sistema estará acessível em `http://127.0.0.1:8000/`.

## 📂 Estrutura do Projeto

*   `estoque/`: Aplicação principal do Django, contendo modelos, views, templates, etc.
*   `estoque_project/`: Configurações do projeto Django.
*   `media/`: Diretório para arquivos de mídia (imagens, documentos, etc.) enviados pelo usuário.
*   `static/`: Diretório para arquivos estáticos (CSS, JavaScript, imagens) do projeto.
*   `requirements.txt`: Lista de dependências do projeto Python.

## 📌 Melhorias Futuras

*   Implementação de um dashboard interativo para visualização de métricas de estoque.
*   Integração com sistemas de código de barras para entrada e saída de materiais.
*   Módulo de relatórios personalizáveis com filtros avançados.
*   Otimização da interface do usuário para dispositivos móveis.

## 📧 Contato

Para dúvidas, sugestões ou colaborações, sinta-se à vontade para entrar em contato através do meu perfil no GitHub ou outras redes sociais. Estou sempre aberto a novas ideias e aprendizados!

---

*Desenvolvido com paixão por Dalmo dos Santos Cabral.*
