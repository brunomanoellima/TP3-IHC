# 🧩 Diagramas MoLIC – Agendamento de Salas e Laboratórios (UFAM)

A seguir estão os diagramas MoLIC desenvolvidos para o sistema, acompanhados de explicações claras para facilitar a compreensão, mesmo por quem não conhece a notação.

---

# 📘 1. MoLIC – Usuário Padrão

Este diagrama representa o **fluxo de interação do usuário comum (docente ou discente autorizado)** ao realizar uma reserva no sistema.

![MoLIC Usuário](https://drive.google.com/uc?id=1LNBWe1ZdsLRqOsEywFGjvb_6Mww3hKHt)

### **O que acontece no diagrama:**

1. **Entrada no sistema** – o usuário acessa a plataforma e faz login com e-mail e senha institucionais.  
2. **Validação** – caso digite credenciais incorretas, o sistema exibe uma mensagem de erro.  
3. **Calendário Geral** – após login bem-sucedido, o sistema mostra:
   - grade de horários  
   - salas disponíveis e indisponíveis  
4. **Seleção da sala** – o usuário escolhe uma sala na lista.  
5. **Formulário de reserva** – o sistema exibe campos para:
   - data  
   - horário inicial e final  
   - motivo da reserva  
6. **Confirmação** – o usuário revisa o resumo e confirma.  
7. **Registro no sistema** – a reserva é salva e finalizada.

Este diagrama mostra **todo o caminho do usuário até concluir uma reserva**.

---

# 📘 2. MoLIC – Usuário Daltônico

Este diagrama representa o mesmo fluxo de reserva do usuário comum, porém **adaptado para acessibilidade**, garantindo que pessoas com daltonismo possam usar o sistema sem dificuldades.

![MoLIC Usuário Daltônico](https://drive.google.com/uc?id=1KX8EztG9P22jXXkhar4jv5GnOxoiGqju)

### **O que muda neste diagrama:**

- Elementos visuais são substituídos por:
  - **descrições textuais**  
  - **formas**, em vez de cores  
- Estados das salas (disponível/indisponível) apresentados **por texto**.  
- Botões e campos com **identificação clara**, independente de cor.  

Este diagrama demonstra o compromisso com **acessibilidade e design inclusivo** no sistema.

---

# 📘 3. MoLIC – Vigilante

Este diagrama representa o fluxo do **vigilante**, responsável por validar retirada de chave, acompanhar reservas e registrar devoluções.

![MoLIC Vigilante](https://drive.google.com/uc?id=1QZZcQV2IPWICTKlCWHQdKa8GbXwWPmVG)

### **O que acontece no diagrama:**

### 🔹 **1. Acesso ao Painel de Reservas**
- O vigilante entra na área administrativa.  
- O sistema exibe todas as reservas do dia.

### 🔹 **2. Validação da Retirada da Chave**
- O sistema mostra foto, nome e detalhes da reserva.  
- O vigilante confere a identidade.  
- Se correto → entrega a chave.  
- Se incorreto → sistema exibe alerta.

### 🔹 **3. Uso da Sala**
- Sistema muda o status da sala para **“em uso”**.

### 🔹 **4. Devolução da Chave**
- O vigilante registra a devolução.  
- Verifica integridade da sala.  
- Sistema confirma o registro.

### 🔹 **5. Finalização**
- Status da sala muda para **“liberada”**.

---

# ✔️ Conclusão

Os três diagramas representam:

- o fluxo do **usuário comum**  
- uma versão **acessível** para daltônicos  
- o fluxo administrativo do **vigilante**  

Eles garantem clareza, acessibilidade e consistência no sistema.
