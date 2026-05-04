# 📊 Geração do Modelo Lógico

![Status](https://img.shields.io/badge/status-concluído-green)
![License](https://img.shields.io/badge/license-MIT-blue)

Projeto de modelagem de banco de dados contendo Diagrama Entidade-Relacionamento (DER) e script DDL para um sistema de gestão de eventos.

---

## 📌 Sobre o Projeto

Este projeto tem como objetivo desenvolver o modelo lógico de um banco de dados, garantindo integridade, consistência e organização das informações.

O sistema modelado é voltado para a gestão de eventos, permitindo o controle de usuários, pedidos, ingressos e setores.

---

## 🧱 Estrutura do Banco de Dados

O modelo é composto pelas seguintes entidades:

- **Usuário**: responsável pelo cadastro no sistema  
- **Evento**: representa os eventos disponíveis  
- **Local**: local onde os eventos acontecem  
- **Setor**: áreas dentro de um evento (VIP, pista, etc.)  
- **Pedido**: compras realizadas pelos usuários  
- **Ingresso**: tickets adquiridos nos pedidos  
- **Cupom**: descontos aplicáveis  
- **Pedido_Cupom**: relação entre pedidos e cupons  

---

## 🔗 Relacionamentos

- Um usuário pode realizar vários pedidos  
- Um pedido pertence a um único usuário  
- Um evento ocorre em um local  
- Um evento possui vários setores  
- Um setor pertence a um evento  
- Um pedido pode conter vários ingressos  
- Um ingresso está vinculado a um setor e a um pedido  
- Um pedido pode ter cupons associados  

---

## 📊 Diagrama Entidade-Relacionamento

![DER do sistema](./der-sistema-eventos.png)

---

## 🗄️ Script do Banco de Dados

O script DDL completo com a criação das tabelas e restrições está disponível em:

📄 `modelo-logico.sql`

---

## 📄 Documentação

Documento completo contendo o modelo lógico, DER e DDL:

📎 [Acessar documentação](./entrega-modelagem-dados.pdf)

---

## 🛠️ Tecnologias Utilizadas

- SQL (DDL)
- Modelagem de Dados
- Banco de Dados Relacional

---

## 🎯 Objetivos do Projeto

- Aplicar conceitos de modelagem de dados  
- Garantir integridade referencial  
- Utilizar boas práticas de normalização  
- Criar estrutura consistente para banco de dados  

---

## 📁 Estrutura do Repositório

```
📦 Geração-do-Modelo-Lógico
 ├── README.md
 ├── modelo-logico.sql
 ├── der-sistema-eventos.png
 └── entrega-modelagem-dados.pdf
```

---

## 📄 Licença

Este projeto é de caráter acadêmico e educacional.
