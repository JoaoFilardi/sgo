# SGO - Sistema de Gestão das Olimpíadas

Este projeto tem como objetivo gerenciar competições esportivas das Olimpíadas, permitindo o cadastro de competições, inscrição de atletas, alocação de locais, registro de resultados e geração de relatórios de medalhas por país.

---

## ✅ Histórias de Usuário

### **US01 - Cadastrar Competição**
Como **Administrador**, quero cadastrar uma competição (modalidade, data, horário, local, limite de vagas), para disponibilizá-la para inscrições.

### **US02 - Inscrever Atleta**
Como **Atleta**, quero me inscrever em uma competição, informando meus dados e país, para participar do evento.

### **US03 - Alocar Local**
Como **Gerente de Logística**, quero alocar um local para uma competição evitando conflitos de horário, para garantir a organização do evento.

### **US04 - Registrar Resultados**
Como **Árbitro**, quero registrar os resultados da competição (1º, 2º, 3º), para atualizar o ranking de medalhas dos países.

### **US05 - Gerar Relatório de Medalhas**
Como **Usuário do sistema**, quero visualizar o total de medalhas por país (ouro, prata, bronze), para acompanhar o desempenho das nações.

---

## ✅ Diagramas do Sistema

Abaixo estão os diagramas solicitados no trabalho:

---

### 📌 Diagrama de Caso de Uso

<img width="500px" src="https://github.com/JoaoFilardi/sgo/imagens/Caso%20de%20Uso%20SGO.png"/>

---

### 📌 Diagrama de Pacotes

<img width="500px" src="https://github.com/JoaoFilardi/SEU_REPOSITORIO/blob/main/sgo/imagens/Diagrama%20Pacotes%20SGO.png"/>

---

### 📌 Diagrama de Classes

<img width="500px" src="https://github.com/JoaoFilardi/SEU_REPOSITORIO/blob/main/sgo/imagens/Diagrama%20de%20Classes%20-%20SGO.png"/>

---

### 📌 Diagrama de Componentes

<img width="500px" src="https://github.com/JoaoFilardi/SEU_REPOSITORIO/blob/main/sgo/imagens/Diagrama%20Componentes%20SGO.png"/>

---

### 📌 Diagrama de Implantação

<img width="500px" src="https://github.com/JoaoFilardi/SEU_REPOSITORIO/blob/main/sgo/imagens/Diagrama%20de%20Implantacao%20SGO.png"/>

---

## ✅ Regras de Negócio Importantes

- Um local **não pode** ter duas competições no mesmo horário.
- Um atleta **pode participar de várias competições**, mas **representa apenas 1 país por modalidade**.
- Para cada competição, o árbitro registra apenas **1º, 2º e 3º lugar**.
- Cada medalha atribuída aumenta o total do país (ouro, prata, bronze, total).
- O relatório de medalhas exibe os países **ordenados pelo número de ouros**.

---

## ✅ Tecnologias (sugestão futura)
- Java / Spring Boot (opcional)
- MVC + Service + DAO + DTO + Domain
- Banco de dados relacional (PostgreSQL/MySQL)
- Front-end Web / API REST

---

## ✅ Autores / Equipe
Projeto desenvolvido para a disciplina **Projeto de Software**.

---

✅ Pronto! Todas as exigências do trabalho foram atendidas:
✔ Histórias de usuário  
✔ Exibição das imagens do repositório  
✔ Estrutura organizada  
✔ Linguagem clara e objetiva (sem enrolação)

Se quiser, posso **colocar o link real do repositório (substituindo SEU_REPOSITORIO)** para já ficar 100% funcional. Me diga seu repositório completo (ex: `JoaoFilardi/projeto-sgo`) e atualizo pra você!


