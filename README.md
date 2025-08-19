# projeto.m4
# 🌱 Projeto Final - Plantando

## 📌 Descrição
O projeto **Plantando** foi desenvolvido como parte do **Módulo 4** do curso, com o objetivo de aplicar os conceitos de **API em JavaScript**, **MVC** e **POO**, abordando temas ligados à **sustentabilidade e causas sociais**.

A proposta é criar uma **API RESTful** com dois temas principais, cada um contendo as operações de **CRUD (Create, Read, Update, Delete)**, permitindo praticar o desenvolvimento backend e preparar a base para o próximo módulo, onde será construído um sistema **fullstack**.

---

## ♻️ Temas da API
- **Recursos Hídricos** 💧  
  Cadastro e gestão de informações relacionadas à preservação e consumo consciente da água.

- **Economia Verde** 🌍  
  Fomento a práticas sustentáveis e registros de projetos que ajudam a reduzir o impacto ambiental.

Cada tema possui suas próprias rotas e modelos, organizados em **MVC**, utilizando **Classes** para representar as entidades.

---

## 🚀 Funcionalidades
- Criar novos registros em cada tema (**Create**).
- Listar registros existentes (**Read**).
- Atualizar informações (**Update**).
- Remover registros (**Delete**).

---

## 🛠️ Tecnologias Utilizadas
- **Node.js**
- **Express**
- **JavaScript (ES6+)**
- **MVC (Model-View-Controller)**
- **POO (Programação Orientada a Objetos)**

---

## 📂 Estrutura de Pastas
```bash
plantando/
│── app.js
│── package.json
│
├── controllers/
│   ├── recursosHidricosController.js
│   ├── economiaVerdeController.js
│
├── models/
│   ├── RecursosHidricos.js
│   ├── EconomiaVerde.js
│
├── routes/
│   ├── recursosHidricosRoutes.js
│   ├── economiaVerdeRoutes.js
│
└── README.md
