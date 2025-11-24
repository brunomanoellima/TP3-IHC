# 📘 TP3 – Imersão, Definição & Design de Interação  
## Sistema de Agendamento de Salas e Laboratórios – UFAM (ICET)

Este repositório reúne todos os artefatos produzidos nas etapas de **Imersão**, **Definição** e **Design de Interação** do TP3 de IHC.  
Aqui estão incluídos: pesquisa com usuários, modelagem conceitual, análise de tarefas, fluxos de interação e protótipos de baixa fidelidade.

---

# 🧭 1. Imersão & Definição

---

## 🧩 Briefing

### 👥 Clientes Potenciais

**Docente:**  
Professor que precisa reservar salas para aulas, práticas e orientações. Hoje depende do vigilante e do caderno físico.

**Discente autorizado:**  
Aluno que usa salas para reuniões, estudos em grupo e atividades acadêmicas, também dependendo do sistema manual atual.

> ❗ O processo atual é **lento, burocrático, manual e sem transparência**.

### 🗣️ Roteiro de entrevista

> "Olá, somos estudantes de IHC e estamos desenvolvendo um sistema para facilitar o agendamento das salas do instituto..."

Foram coletadas informações sobre:
- necessidades reais  
- dores do sistema atual  
- funcionalidades essenciais  
- prioridades  
- integrações possíveis  

### 👩‍💻 Cliente C1 – Representante do Curso

Estudante de Engenharia de Software que atua como ponte entre coordenação, alunos e vigilância.  
Apresentou com clareza a demanda de **digitalizar o processo inteiro de reserva**.

---

## 🧱 Matriz CSD

Organiza as descobertas em:

- **Certezas**  
- **Suposições**  
- **Dúvidas**

### 📸 Matriz construída
![Matriz CSD](https://raw.githubusercontent.com/brunomanoellima/TP3-IHC/refs/heads/main/design-ihc/imersao-definicao/2-matriz-csd/imagens/Matriz%20CSD.png)

---

## 📊 Benchmarking

Sistemas analisados:

1. **Google Calendar** – excelente visual, mas sem controle de chaves.  
2. **Microsoft Bookings** – robusto, mas pago.  
3. **Reserva USP** – acadêmico, porém limitado.  
4. **MRBS – IFAM** – mais próximo da realidade UFAM.

### 🧠 Conclusão geral
A UFAM precisa de um sistema **híbrido**: digital + suporte ao controle físico de chaves feito pelo vigilante.

---

## 👤 Personas & 🧭 Jornada do Usuário

Três personas principais:

### 👮 Vigilante  
Dores: processos manuais, receio de erros, falta de organização.

### 🎓 Estudante Autorizado  
Dores: deslocamento até o vigilante, falta de previsibilidade e transparência.

### 👨‍🏫 Docente  
Dores: agenda cheia, dependência do vigilante, dificuldade para acompanhar salas.

As jornadas completas estão em:  
`5-jornada-do-usuario/jornada-do-usuario.md`

---

## 📌 Priorização MoSCoW

Classificação dos requisitos:

- **Must Have:** login institucional, visualização, reserva e validação do vigilante.  
- **Should Have:** filtros e histórico.  
- **Could Have:** mapa interativo, recorrência de reservas.  
- **Won’t Have:** integração com Google Calendar.

### 📸 Priorização
![MoSCoW](design-ihc/imersao-definicao/6-moscow/imagens/moscou.png)

---

## 📎 Arquivos úteis da Imersão & Definição

- **Briefing:** `1-briefing/briefing.md`  
- **Matriz CSD:** `2-matriz-csd/matriz-csd.md`  
- **Benchmarking:** `3-benchmarking/benchmarking.md`  
- **Personas:** `4-personas/`  
- **Jornada do usuário:** `5-jornada-do-usuario/jornada-do-usuario.md`  
- **MoSCoW:** `6-moscow/moscow.md`  

---

# 🎨 2. Design de Interação

Esta seção apresenta todo o processo de modelagem e prototipação do sistema, dividido em:

1. Metamensagem  
2. Mapa de Objetivos  
3. HTAs  
4. Diagramas MoLIC  
5. Protótipos de Baixa Fidelidade (Sketches)

---

## 🧩 2.1 Metamensagem  
📁 Pasta: [`1_metamensagem`](../1_metamensagem/README.md)

A metamensagem define:

- quem usa o sistema  
- o que busca  
- como o sistema ajuda  
- o que a interface deve transmitir  

---

## 🎯 2.2 Mapa de Objetivos  
📁 Pasta: [`2_mapas-objetivos`](../2_mapas-objetivos/README.md)

O mapa apresenta:

- objetivos finais  
- objetivos intermediários  
- relação entre papéis  
- caminhos de ação  

📸 **Mapa de Objetivos**  
![Mapa de Objetivos](../2_mapas-objetivos/objetivos.png)

---

## 🧠 2.3 HTA – Hierarchical Task Analysis  
📁 Pasta: [`3_HTAs`](../3_HTAs/README.md)

Inclui 8 HTAs completos, cada um com:

- imagem  
- explicação textual  
- relação com o Mapa de Objetivos  

### 📸 HTAs (1 a 8)

| HTA | Imagem |
|------|--------|
| **HTA 1 – Acessar o sistema** | ![HTA1](design-interacao/3_HTAs/imagens/hta1.png) |
| **HTA 2 – Visualizar disponibilidade** | ![HTA2](design-interacao/3_HTAs/imagens/hta2.png) |
| **HTA 3 – Selecionar e definir reserva** | ![HTA3](design-interacao/3_HTAs/imagens/hta3.png) |
| **HTA 4 – Confirmar reserva** | ![HTA4](design-interacao/3_HTAs/imagens/hta4.png) |
| **HTA 5 – Visualizar reservas (vigilante)** | ![HTA5](design-interacao/3_HTAs/imagens/hta5.png) |
| **HTA 6 – Validar retirada da chave** | ![HTA6](design-interacao/3_HTAs/imagens/hta6.png) |
| **HTA 7 – Registrar devolução** | ![HTA7](design-interacao/3_HTAs/imagens/hta7.png) |
| **HTA 8 – Consultar histórico** | ![HTA8](design-interacao/3_HTAs/imagens/hta8.png) |

---

## 💬 2.4 Diagramas MoLIC  
📁 Pasta: [`4_diagramas-MoLIC`](../4_diagramas-MoLIC/README.md)

Inclui:

- MoLIC do Usuário  
- MoLIC Adaptado para Daltônicos  
- MoLIC do Vigilante  

### 📸 Diagramas MoLIC

| Tipo | Imagem |
|------|--------|
| **MoLIC do Usuário** | ![MolicUsuario](design-interacao/4_diagramas-MoLIC/imagens/MolicUsuario.png) |
| **MoLIC Adaptado (Daltônicos)** | ![MolicDalt](design-interacao/4_diagramas-MoLIC/imagens/MolicUsuarioDaltonico.png) |
| **MoLIC do Vigilante** | ![MolicVigi](design-interacao/4_diagramas-MoLIC/imagens/MolicVigilante.jpeg) |

---

## 🎨 2.5 Protótipos de Baixa Fidelidade (Sketches)  
📁 Pasta: [`5_sketches`](../5_sketches/README.md)

Inclui:

- Telas do usuário (versão 1 e 2)  
- Tela adaptada para daltônicos  
- Telas do vigilante  
- Comparativo MoLIC → Tela  
- Explicações  
- Justificativa da escolha da Versão 2  

### 📸 Sketches do Usuário

| Tela | Imagem |
|------|--------|
| **Usuário – Versão 1** | ![TelaUsuario1](design-interacao/5_sketches/imagens/TelaUsuario1.png) |
| **Usuário – Versão 2 (Escolhida)** | ![TelaUsuario2](design-interacao/5_sketches/imagens/TelaUsuario2.png) |

### 📸 Sketches do Vigilante

| Tela | Imagem |
|------|--------|
| **Vigilante – Versão 1** | ![Vigi1](design-interacao/5_sketches/imagens/Tela_Vigi_1.PNG) |
| **Vigilante – Versão 2 (Escolhida)** | ![Vigi2](design-interacao/5_sketches/imagens/Tela_Vigi_2.PNG) |

---

---

# ✔️ Conclusão

Esta seção documenta de forma completa e organizada todo o processo de **Design de Interação**, mostrando claramente:

- a visão conceitual  
- os objetivos dos usuários  
- as tarefas essenciais  
- os fluxos de interação  
- e os primeiros protótipos desenhados  

Ela garante consistência, clareza e rastreabilidade entre todas as etapas do projeto.







