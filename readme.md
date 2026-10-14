# 🕯️ E-commerce de Velas Artesanais

Projeto de e-commerce minimalista para venda de velas artesanais e aromáticas. Este repositório foi desenvolvido como um **estudo prático e experimento de engenharia de prompts**, testando as capacidades de modelos de IA generativa para a construção de uma aplicação web funcional de ponta a ponta.

---

## 🚀 Tecnologias Utilizadas

* **PHP:** Processamento no lado do servidor e rotas de produtos.
* **JavaScript (`script.js`):** Interatividade de interface e manipulação dinâmica.
* **MySQL (`db.php`):** Persistência de dados (catálogo e upload de arquivos).
* **HTML5 & CSS3 (`style.css`):** Estilização responsiva e layouts.

---

## ✨ Destaques e Funcionalidades

* **Painel Administrativo (`/admin`):** Área restrita para gerenciamento do catálogo e upload de novos produtos.
* **Upload Helper (`upload_helper.php`):** Script utilitário para tratamento e upload de imagens dos produtos.
* **Catálogo Dinâmico:** Exibição de produtos com detalhes e preços consumidos do banco de dados.
* **Reescrita de URLs (`.htaccess`):** Configuração de rotas para navegação amigável.

---

## 📁 Estrutura do Repositório

```text
├── admin/               # Painel e rotas administrativas
├── .gitignore           # Arquivos ignorados pelo controle de versão
├── .htaccess            # Regras de reescrita de URL do Apache
├── db.php               # Conexão centralizada com o banco MySQL
├── index.php            # Página inicial e catálogo de velas
├── produto.php          # Visualização detalhada de produto
├── script.js            # Comportamentos em JavaScript
├── style.css            # Estilização visual da loja
└── upload_helper.php    # Função auxiliar para gerenciamento de uploads
