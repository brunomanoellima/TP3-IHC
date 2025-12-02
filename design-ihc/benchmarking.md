# 📊 Benchmarking

O *benchmarking* tem como objetivo analisar sistemas semelhantes já existentes, identificando como outras plataformas resolvem o problema de **agendamento e controle de uso de espaços compartilhados**.  
A partir dessa análise, é possível compreender **boas práticas, limitações e oportunidades de melhoria** para o sistema proposto.

---

## 🧩 a) Avaliação dos Itens a Serem Comparados

Os principais itens definidos para comparação entre os sistemas foram:

- Funcionalidades principais (agendamento, cancelamento, visualização de disponibilidade)  
- Acessibilidade e usabilidade  
- Níveis de acesso (usuário e administrador)  
- Controle de conflito  

---

## 🧠 b) Definição dos Similares-Alvo

Foram selecionados quatro sistemas ou serviços que possuem finalidades próximas ou que podem servir como referência:

- **Sistema 1 — Google Calendar (Google Agenda):**  
  Plataforma amplamente utilizada para gerenciamento de compromissos, com visualização de horários e compartilhamento de agendas.

- **Sistema 2 — Microsoft Bookings:**  
  Ferramenta corporativa que permite agendamento de salas e recursos, com controle de disponibilidade e confirmação automática.

- **Sistema 3 — Sistema de Reserva de Salas da USP:**  
  Sistema acadêmico interno voltado à reserva de salas e laboratórios da Universidade de São Paulo.

- **Sistema 4 — Sistema de Agendamento de Laboratórios do IFAM (MRBS):**  
  Sistema institucional voltado ao controle de uso de laboratórios, administrado por técnicos e vigilantes locais.

---

## 📈 c) Estabelecimento de Indicadores e Obtenção de Dados

Para cada sistema, foram observadas as respostas às seguintes perguntas:

1. Quais problemas o produto resolve?  
2. Como os problemas são resolvidos?  
3. Quais os pontos fortes e fracos dessas soluções?

---

### **Sistema 1 — Google Calendar**

**1. Problemas que resolve:**  
Permite organizar e compartilhar horários de uso de espaços e compromissos.  

**2. Como resolve:**  
Oferece calendários compartilhados e notificações automáticas de eventos.  

**3. Pontos fortes e fracos:**  
- ✅ **Forte:** Interface intuitiva, sincronização entre dispositivos, envio de alertas automáticos.  
- ❌ **Fraco:** Não há controle físico (ex.: chaves) e não possui autenticação institucional.  

---

### **Sistema 2 — Microsoft Bookings**

**1. Problemas que resolve:**  
Gerencia reservas de salas e serviços internos em tempo real.  

**2. Como resolve:**  
Agenda automatizada integrada ao Microsoft 365 com confirmação e cancelamento automáticos.  

**3. Pontos fortes e fracos:**  
- ✅ **Forte:** Integração com e-mail institucional e autenticação corporativa.  
- ❌ **Fraco:** Plataforma paga, dependente de licença Microsoft.  

---

### **Sistema 3 — Sistema de Reserva de Salas da USP**

**1. Problemas que resolve:**  
Centraliza o agendamento de salas de aula e laboratórios na universidade.  

**2. Como resolve:**  
Oferece login institucional, painel administrativo e histórico de uso.  

**3. Pontos fortes e fracos:**  
- ✅ **Forte:** Foco no contexto acadêmico, relatórios automáticos de uso.  
- ❌ **Fraco:** Interface pouco responsiva.  

---

### **Sistema 4 — Sistema de Agendamento de Laboratórios do IFAM (MRBS)**

**1. Quais problemas resolve:**  
Centraliza o agendamento de laboratórios e evita conflitos de horários entre diferentes turmas ou professores.  

**2. Como resolve:**  
Funciona via plataforma web (**MRBS – Meeting Room Booking System**), onde o usuário pode visualizar as datas e horários disponíveis, cadastrar uma reserva e aguardar a **autorização de um técnico de laboratório**.  
O sistema exige **cadastro de usuário e senha**, feito junto ao técnico responsável, e bloqueia automaticamente horários já ocupados.  

**3. Pontos fortes e fracos:**  
- ✅ **Forte:** Sistema totalmente online; evita conflitos de reserva; possui controle de autorização e relatórios de uso.  
- ❌ **Fraco:** Interface pouco responsiva e dependente da rede interna do campus; o processo de criação de login precisa ser feito presencialmente com o técnico, o que limita a autonomia do usuário.  

---

## 📊 d) Comparação das Informações Coletadas

| **Similar** | **Visualiza disponibilidade** | **Reserva online** | **Notificações automáticas** | **Login institucional** | **Controle físico (chave)** | **Integração com sistemas** | **Relatórios de uso** |
|--------------|-------------------------------|--------------------|------------------------------|--------------------------|-----------------------------|-----------------------------|----------------------|
| **Google Calendar** | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ (Gmail) | ✅ |
| **Microsoft Bookings** | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ (Microsoft 365) | ✅ |
| **USP (Sistema Interno)** | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ (Sistema interno) | ✅ |
| **IFAM (MRBS)** | ✅ | ✅ | ⚠️ Parcial (confirmação via técnico) | ⚠️ Parcial (login com técnico) | ✅ | ❌ | ✅ |

---

## 🧩 Conclusão do Benchmarking

Com base na análise, percebe-se que **nenhum dos sistemas atuais atende totalmente às necessidades específicas da UFAM**, que envolvem **gestão física de chaves, autenticação institucional e controle centralizado de reservas**.  

O sistema proposto visa **combinar a praticidade das plataformas digitais com o controle local dos vigilantes**, oferecendo um **modelo híbrido e acessível** para a comunidade acadêmica.

---

