📅 Data: 03/09/2025

Conceitos principais
🔋 Sempre considerar pilha = 1,5V.

⚡ Tudo que for acima disso é considerado bateria.

Cores dos cabos e tensões

🟡 Amarelo → 12V Alimenta processador e placa de vídeo.

🔴 Vermelho → 5V Circuitos de apoio, alguns HDs e memória.

🟠 Laranja → 3,3V HD/SSD e outros componentes como a placa de vídeo.

Obs.: Fontes atuais não seguem mais padrão de cores nos cabos.

Instrumentação
🧰 Usar multímetro para descobrir as tensões corretamente.
<img width="945" height="525" alt="eletrica " src="https://github.com/user-attachments/assets/c42c9ae4-62d2-4526-bb2a-068315d45f95" />

# # ⚡ Eletricidade e Lei de Ohm 05/09/25

## 🔌 Corrente Alternada (CA / AC)

- **Tomada** → recebe o nome de **CA** (*Corrente Alternada*).  
- Tradução de **AC** → **127/CA220**.  
- **Entrada (Input):** `100–240V ~ 50/60Hz`.  
  - **100–127 V** | **200–240 V**.  
- Na corrente alternada existe a unidade **Hz (Hertz)** → indica a **frequência**.  
  - Exemplo: **50/60 Hz** → número de vezes que a polaridade muda por segundo.  

### Conversão de frequência
- **5 GHz = 5.000.000.000 Hz (5 bilhões de Hertz)** ✅  

---

## 🔋 Corrente Contínua (CC / DC)

- Tradução de **DC** → **CC (Corrente Contínua)**.  
- Não possui frequência.  
- Valores típicos: **12 V**, **5 V**, **3,3 V**.  
- Exemplo: **Saída de carregador (Output): 5.0V / 3.0A**.  
  - **5V** → padrão de **porta USB**.  

---


### Triângulo da Lei de Ohm
```text
        ▲
       / \
      / V \
     /-----\   ← linha horizontal = multiplicação
    /  I | R\
   /_________\ ← linha vertical = divisão
V = Tensão (Volts)

I = Corrente (Ampères)

R = Resistência (Ohms Ω)

🔑 Regras:

Vertical (cima ↔ baixo) → Divisão

Horizontal (lado ↔ lado) → Multiplicação

Na divisão: não alterar os números.

Na multiplicação: pode inverter sem problema.

🔠 Unidades e Símbolos

R = Resistor → Ω (Ohm)

I = Corrente → A (Ampère)

V = Tensão → V (Volt)

Ω = Resistência elétrica

U = Tensão

P = Potência (Watt)

⚠️ Se a corrente (I) for maior ou igual à tensão (U), ocorre curto-circuito.



	​


Representação
        ▲
       / \
      / P \
     /-----\   ← linha horizontal = multiplicação
    /  U | I\
   /_________\ ← linha vertical = divisão


P = Potência (Watt)

U = Tensão (Volt)

I = Corrente (Ampère)

📌 Observação

Quando não tiver 2 valores no primeiro triângulo (Lei de Ohm), usar o segundo triângulo da Potência para encontrar o que falta:



# 💡 Cálculo de Resistor para LED

## 🔦 Exemplo: LED Branco
- **Tensão do LED (Uled):** 3V  
- **Corrente do LED (Iled):** 0,02A (20mA)  
- **Potência (P):** 0,06W  

---



- **Valim** = Tensão da fonte  
- **Vled** = Tensão do LED  
- **Iled** = Corrente do LED  

---

## 🧮 Cálculos Práticos


R = \dfrac{5V - 3V}{0,02A} = 100 \, \Omega
\]

---

### 2. Fonte de 12V
\[
R = \dfrac{12V - 3V}{0,02A} = 450 \, \Omega
\]

---

### 3. Fonte de 127V
\[
R = \dfrac{127V - 3V}{0,02A} \approx 6.200 \, \Omega
\]

---

### 4. Fonte de 220V
\[
R = \dfrac{220V - 3V}{0,02A} \approx 10.850 \, \Omega
\]

---

## ⚠️ Observação Importante
- Sempre escolher um **resistor com valor maior ou igual** ao calculado.  
- Isso evita sobrecorrente e aumenta a vida útil do LED.  

