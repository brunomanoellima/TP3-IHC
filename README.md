<img width="120" src="https://cdn-icons-png.flaticon.com/512/1827/1827370.png" />

# 📘 TP3 – Imersão, Definição e Design de Interação  
### Sistema de Agendamento de Salas e Laboratórios – UFAM (ICET)

---

# 📌 Sumário  
- [Equipe](#-equipe)  
- [Visão Geral do Projeto](#-visão-geral-do-projeto)  
- [1. Imersão & Definição](#-1-imersão--definição)  
  - Briefing  
  - Matriz CSD  
  - Benchmarking  
  - Personas & Jornada  
  - MoSCoW  
- [2. Design de Interação](#-2-design-de-interação)  
  - Metamensagem  
  - Mapa de Objetivos  
  - HTA  
  - MoLIC  
  - Sketches  
- [3. Identidade Visual](#-3-identidade-visual)  
  - Paleta de Cores  
  - Tipografia  
  - Estilo de Ícones  
- [4. Protótipo Interativo](#-4-protótipo-interativo)  
- [5. Usabilidade, Heurísticas e Comunicabilidade](#-5-usabilidade-heurísticas-e-comunicabilidade)  
  - Telas de Acesso  
  - Telas de Busca e Solicitação  
  - Painel do Vigia  
- [Conclusão](#-conclusão)

---

# 👥 Equipe  
**Bruno — Carlos — Cíntia — Nélio**

---

# 📖 Visão Geral do Projeto  

Este repositório documenta **todo o processo** de criação do sistema *Reserva ICET*, desenvolvido para a disciplina de IHC.  

Inclui:  
✔ Pesquisa com usuários  
✔ Análise de tarefas  
✔ Modelagem conceitual  
✔ Fluxos de interação  
✔ Prototipação  
✔ Avaliação com heurísticas  
✔ Identidade visual e justificativas  

---

# 🧭 1. Imersão & Definição

---

## 🧩 Briefing  
O agendamento atual de salas e laboratórios depende de **vigilantes, cadernos físicos e comunicação informal**.

Problemas identificados:  
- Lento  
- Pouco transparente  
- Sem histórico  
- Dependente do turno do vigilante  
- Sem previsibilidade para docentes e discentes  

Perfis atendidos:  
- 👨‍🏫 **Docentes**
- 🎓 **Discentes autorizados**
- 👮 **Vigilantes**  

---

## 🧱 Matriz CSD  
![CSD](https://drive.google.com/uc?export=view&id=1xf81b8JiaalcVwjigrLoaAqx7Om2TE0a)

---

## 📊 Benchmarking  
Ferramentas analisadas:

| Sistema | Pontos Positivos | Limitações |
|--------|------------------|------------|
| Google Calendar | Intuitivo e visual | Sem controle de chaves |
| Bookings | Completo | Pago |
| Reserva USP | Acadêmico | Pouco flexível |
| MRBS IFAM | Similar à UFAM | Interface complexa |

**Conclusão:** UFAM precisa de um sistema digital **+ suporte ao controle físico de chaves**.

---

## 👤 Personas & Jornada
Perfis estudados:
- 👨‍🏫 Docente  
- 🎓 Discente Autorizado  
- 👮 Vigilante  

Jornada completa em: `5-jornada-do-usuario/jornada-do-usuario.md`

---

## 📌 MoSCoW  
![Moscow](https://drive.google.com/uc?export=view&id=1edBTi-89YX3K3a4ju0hVj4u9wR9eY3Lh)

---

# 🎨 2. Design de Interação

---

## 🧩 Metamensagem  
📁 `1_metamensagem/`

Define:
- contexto de uso  
- objetivos  
- necessidades  
- estilo da comunicação  

---

## 🎯 Mapa de Objetivos  
![Mapa](https://drive.google.com/uc?export=view&id=1wcXrqItdqwyCq7_D2vZZgTnUs18qkiYc)

---

## 🧠 HTA – Hierarchical Task Analysis  
📁 `3_HTAs/`

Contém 8 HTAs completos (Acesso → Reserva → Validação → Histórico).

---

## 💬 Diagramas MoLIC  
📁 `4_diagramas-MoLIC/`

Inclui:
- MoLIC Usuário  
- MoLIC Vigilante  
- MoLIC Acessível (Daltônicos)  

---

## ✏️ Sketches (Baixa Fidelidade)  
📁 `5_sketches/`

Inclui:
- Usuário v1 e v2  
- Vigilante v1 e v2  
- Versão final escolhida  
- Mapeamento MoLIC → Tela  

---

# 🎨 3. Identidade Visual

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso | Justificativa |
|----|------|------|---------------|
| 🔵 Azul Royal | **#0e34e8** | Cor principal | Tecnologia, confiança e profissionalismo |
| 🟤 Marrom Dourado | **#bf7908** | Cor de apoio | Equilíbrio, seriedade e estabilidade |
| 🟡 Amarelo Ouro | **#faa10b** | Destaque | Atenção, hierarquia visual e energia |
| ⚪ Branco | **#ffffff** | Fundo | Limpeza, respiro e contraste |
| ⚫ Cinza Médio | **#727272** | Textos secundários | Legibilidade sem agressividade |

---

## ✒️ Tipografia

### **1. Belanossimas (Títulos)**
- Elegante e marcante  
- Dá personalidade aos títulos  
- Boa para gerar identidade visual forte

### **2. Andika (Títulos e Corpo)**
- Extremamente legível  
- Ideal para acessibilidade  
- Confiável para mobile  

### **3. Amiri Quran Colored (Corpo de texto)**
- Serifada e formal  
- Boa para textos longos  
- Ajuda na hierarquia visual  

---

## 🖼️ Estilo de Ícones e Signos  
- Baseados em **Material Symbols** e **Phosphor Icons**  
- Traço linear, curvo e minimalista  
- Signos metalinguísticos claros:
  - ✔ Sucesso  
  - ❌ Erro  
  - 🟢 Disponível  
  - 🟠 Em uso  
  - 🔴 Indisponível  

**Consistência semântica:** o mesmo ícone representa sempre a mesma ação.

---

# 🎨 4. Protótipo Interativo

👉 **Acesse o protótipo navegável no Figma:**  
### 🔗 https://www.figma.com/proto/9457ZrZiUT5ts2XfAXC41d/TP3?node-id=144-802&p=f

---

# 📱 5. Usabilidade, Heurísticas e Comunicabilidade

A avaliação segue as **10 Heurísticas de Nielsen**, com foco em:
- visibilidade  
- consistência  
- correspondência ao mundo real  
- prevenção de erros  
- acessibilidade  

---

## 🟦 Telas de Acesso, Login e Cadastro  
![T1](https://drive.google.com/uc?export=view&id=1xEKjDEFx1FA6yqWYMVPxj5m-g3TRDJ3f)

### ✔ Heurísticas aplicadas
- **H1 – Visibilidade do estado do sistema:** perfil selecionado destacado  
- **H4 – Consistência e padrões:** campos sempre iguais  
- **H8 – Estética e minimalismo:** foco no essencial  

### ✔ Acessibilidade
- Alto contraste  
- Tipografia legível  
- Campos grandes  

---

## 🟦 Telas de Busca, Resultados e Solicitação  
![Tela 2](https://drive.google.com/uc?export=view&id=1sainHbak4oPfzC4OB434pigQryckUEUh)

### ✔ Heurísticas
- **H2 – Correspondência com o mundo real:** uso de cores universais  
- **H5 – Prevenção de erros:** datas e horários separados  
- **H6 – Reconhecimento, não memorização:** repetição de padrões  

### ✔ Comunicabilidade
- Signos por cor (verde/laranja/vermelho)  
- Etiquetas e ícones reforçam intenção  

---

## 🟦 Painel do Vigia  
![T3](https://drive.google.com/uc?export=view&id=1mJ3LzTh_3WO8GKpRLUxAslLABUSpOUgu)

### ✔ Heurísticas
- **H1 – Visibilidade do estado do sistema:** feedback imediato  
- **H3 – Controle e liberdade:** botão “Voltar ao início”  
- **H7 – Eficiência:** painel otimizado para decisões rápidas  
- **H9 – Recuperação de erros:** mensagens claras (✔ / ❌)

---

# ✔ Conclusão

Este projeto apresenta:

✔ Documentação completa (Imersão → Entrega Final)  
✔ Prototipação de alta qualidade  
✔ Análise sólida de usabilidade  
✔ Aplicação real das heurísticas de Nielsen  
✔ Identidade visual consistente e acessível  
✔ Fluxos claros para os três perfis do sistema  

O sistema *Reserva ICET* oferece uma solução moderna, intuitiva e funcional para o agendamento de salas, alinhado à realidade da UFAM.

---
