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

# # ⚡ Eletricidade e Lei de Ohm

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

## 📐 Lei de Ohm

### Fórmulas
- \( V = I \times R \)  
- \( I = \dfrac{V}{R} \)  
- \( R = \dfrac{V}{I} \)  

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

🧮 Exemplos de Cálculo
Exemplo 1

𝑈
=
5
𝑉
U=5V

𝐼
=
3
𝐴
I=3A

𝑅
=
?
R=?

𝑅
=
𝑈
𝐼
=
5
3
≈
1
,
66
 
Ω
R=
I
U
	​

=
3
5
	​

≈1,66Ω

⚠️ Se a corrente (I) for maior ou igual à tensão (U), ocorre curto-circuito.

Exemplo 2

Potência 
𝑃
=
5500
𝑊
P=5500W

Tensão 
𝑈
=
220
𝑉
U=220V

Corrente 
𝐼
=
25
𝐴
I=25A

𝑃
=
𝑈
×
𝐼
=
220
×
25
=
5500
𝑊
P=U×I=220×25=5500W

✅ Equação confirmada!

🔺 Triângulo da Potência
Fórmula

𝑃
=
𝑈
×
𝐼
P=U×I

𝑈
=
𝑃
𝐼
U=
I
P
	​


𝐼
=
𝑃
𝑈
I=
U
P
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

𝑃
=
𝑈
×
𝐼
P=U×I
