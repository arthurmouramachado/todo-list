# 📋 Lista de Tarefas - Aplicação Full Stack

## 🎯 Objetivo
O objetivo deste projeto é desenvolver uma **aplicação WEB completa** para gerenciar uma lista de tarefas (**Todo List**).  

A aplicação foi projetada com arquitetura **Full Stack**, utilizando:  
- **Backend:** Spring Boot (API REST)  
- **Frontend:** Angular (consumindo a API via HTTP)  

O sistema foi publicado e está disponível em:  
👉 [Lista de Tarefas - Deploy](https://ricardotecpro.github.io/ads_proj_aplicacao_full_stack/projetos/listadetarefas_03)  

---

## 📌 Escopo Mínimo Obrigatório (MVP)
- ✅ API REST desenvolvida em **Spring Boot**  
- ✅ Interface Web em **Angular**  
- ✅ Comunicação **Frontend ↔ Backend** via **REST API**  

---

## ⭐ Extras (opcional - bônus)
- 🚀 Aplicação **Desktop** em **JavaFX** consumindo a mesma API  
- 📱 Aplicação **Mobile** em **Android (Kotlin + Jetpack Compose)** consumindo a mesma API  

---

## 🛠️ Tecnologias Utilizadas

### Backend (API)
- **Java 17+**  
- **Spring Boot**  
  - Spring Web (REST)  
  - Spring Data JPA  
  - H2 Database (para ambiente de desenvolvimento)  
- **Maven** (gerenciador de dependências)  

### Frontend (Web)
- **Angular 17+**  
- **TypeScript**  
- **Bootstrap / CSS**  

### Extras (opcionais)
- **JavaFX** (Desktop)  
- **Kotlin + Jetpack Compose** (Mobile Android)  

---

## ⚙️ Como Executar o Projeto

### 1. Clonar o Repositório
```bash
git clone https://github.com/SEU_USUARIO/listadetarefas.git
cd listadetarefas
```

---

### 2. Backend (Spring Boot)
1. Acesse a pasta do backend:  
   ```bash
   cd backend
   ```
2. Compile e execute o projeto:  
   ```bash
   ./mvnw spring-boot:run
   ```
3. A API estará disponível em:  
   👉 `http://localhost:8080/api/tarefas`  

---

### 3. Frontend (Angular)
1. Acesse a pasta do frontend:  
   ```bash
   cd frontend
   ```
2. Instale as dependências:  
   ```bash
   npm install
   ```
3. Execute o servidor de desenvolvimento:  
   ```bash
   ng serve
   ```
4. A aplicação estará disponível em:  
   👉 `http://localhost:4200`  

---

### 4. Extras (opcionais)
- **JavaFX:** Executar projeto desktop apontando para a API.  
- **Android (Kotlin + Jetpack Compose):** Rodar em emulador ou dispositivo físico, consumindo a mesma API.  

---

## 🌗 Funcionalidades
- Criar, listar, atualizar e remover tarefas.  
- API REST documentada e reutilizável para outros clientes (Web, Desktop, Mobile).  

---

## 👨‍💻 Desenvolvedor
**Nome:** Ricardo TecPro  
🔗 [GitHub](https://github.com/ricardotecpro)  

---

## 📅 Prazo e Entrega
- O repositório deve ser **público**  
- Enviar no **Moodle** o link do GitHub dentro do prazo estabelecido  
