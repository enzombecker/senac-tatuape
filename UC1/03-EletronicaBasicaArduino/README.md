<img width="543" height="137" alt="leds" src="https://github.com/user-attachments/assets/1a5c4da7-cd00-42e2-a239-dbcbdfe178db" />

<img width="464" height="215" alt="protoboard" src="https://github.com/user-attachments/assets/533f4452-17c6-4bd5-80eb-9b5b626298da" />

<img width="512" height="363" alt="unoR3-esquema" src="https://github.com/user-attachments/assets/e717c222-665c-40bd-956a-7905dbd920d3" />

[aula 1 piscar LED .pdf](https://github.com/user-attachments/files/22216669/aula.1.piscar.LED.pdf)


<img width="671" height="506" alt="arduino" src="https://github.com/user-attachments/assets/d904c6ad-c5ff-45d5-9576-4ac05378baea" />

📌 O que é Arduino?

Arduino é uma plataforma de prototipagem eletrônica de código aberto baseada em hardware e software fáceis de usar. Ela permite a criação de projetos interativos que envolvem sensores, atuadores e programação.

A placa Arduino possui um microcontrolador (como o ATmega328) que pode ser programado via USB usando a linguagem de programação C/C++ com a IDE do Arduino.

Muito utilizada em projetos de automação, robótica, IoT (Internet das Coisas), sistemas embarcados e educação.

🧾 Tipos de Comentários no Código Arduino

No Arduino, os comentários são escritos para explicar o código, mas não são lidos nem executados pelo microcontrolador. Eles ajudam os programadores a entenderem melhor o que cada parte do código faz.

/**
 * Documentação de Cabeçalho
 * Este tipo de comentário é usado para descrever o propósito do código,
 * autor, data, licenças, etc.
 */

/*
 * Comentários em bloco
 * São usados para comentar várias linhas de uma vez.
 * Úteis para desativar partes do código temporariamente.
 */

// Comentário em linha
// São usados para explicar uma linha específica do código.

⚠️ Boas Práticas com Comentários

✅ Use comentários para explicar o "porquê" do código, não apenas o "como".

✅ Seja claro e objetivo.

✅ Mantenha os comentários atualizados com o código.

❌ Evite excesso de comentários óbvios (ex: x = 1; // x é igual a 1).

❌ Comentários confusos ou desatualizados atrapalham mais do que ajudam.

💡 Projeto: Pisca LED com Arduino
/**
 * Pisca LED
 * @author Enzo Mesquita
 */


Este é um exemplo básico de um programa que acende um LED no pino digital 13 da placa Arduino. Ideal para iniciantes aprenderem como usar saídas digitais.

🔧 Comando pinMode
pinMode(13, OUTPUT);


Função: Configura o pino 13 como saída digital.

Uso: Tudo que você quiser controlar (LEDs, motores, relés) deve estar em um pino configurado como OUTPUT.

⚡ Comando digitalWrite
digitalWrite(13, HIGH);


Função: Envia nível alto (5V) ao pino 13, fazendo o LED acender.

Parâmetros:

13: Número do pino

HIGH: Nível lógico alto (5V ou 1 binário)

✅ Código Corrigido e Explicado
/**
 * Pisca LED
 * @author Enzo Mesquita
 */

void setup() {
  pinMode(13, OUTPUT); // configurar o pino 13 como saída
  digitalWrite(13, HIGH); // acender o LED (HIGH = 5V ou 1 binário)
}

void loop() {
  // put your main code here, to run repeatedly:
}

ℹ️ Dicas Importantes

Sempre termine comandos com ponto e vírgula (;).

Tudo que for programar antes do ponto e vírgula faz parte da instrução.

O comando setup() é executado uma única vez ao iniciar.

O comando loop() roda continuamente enquanto o Arduino estiver ligado

⚠️ PARA DESLIGAR O LED
digitalWrite(13,LOW)


troque HIGH por LOW

HIGHT está errado, o correto é HIGH

LOW faz o pino receber 0V, apagando o LED

🔁 PARA FAZER PISCAR

apague a linha que só acende:

// digitalWrite(13, LOW);  // acender o LED (HIGH = 5V ou 1 binario)


e coloque:

void loop() {
  digitalWrite(13, HIGH);  // acender led
  
  delay(1000);             // esperar um segundo 1000 milissegundos
  
  digitalWrite(13, LOW);   // apagar led
  
  delay(1000);             // esperar um segundo 1000 milissegundos
  
}

⏱️ SOBRE O DELAY

1000ms igual a um segundo

para piscar mais rapido diminua numero do delay

exemplo: delay(500) iguala mei 0 segundo

exemplo: delay(100) iguala 0 ponto 1 segundo

*** desafio do semaforo

void setup() {
  // semaforo 1
  pinMode(13, OUTPUT);  // vermelho A
  pinMode(12, OUTPUT);  // amarelo A
  pinMode(11, OUTPUT);  // verde A

  // semaforo 2
  pinMode(10, OUTPUT);  // vermelho B
  pinMode(9, OUTPUT);   // amarelo B
  pinMode(8, OUTPUT);   // verde B 
}

void loop() {
  // ciclo 1
  digitalWrite(11, HIGH); // acender verde A
  digitalWrite(10, HIGH); // acender vermelho B
  delay(3000);

  // ciclo 2
  digitalWrite(11, LOW);  // apagar verde A
  digitalWrite(10, HIGH); // manter vermelho B
  digitalWrite(12, HIGH); // acender amarelo A
  delay(3000);

  // ciclo 3
  digitalWrite(10, LOW);  // apagar vermelho B
  digitalWrite(12, LOW);  // apagar amarelo A
  digitalWrite(8, HIGH);  // acender verde B
  digitalWrite(13, HIGH); // acender vermelho A
  delay(3000);

  // ciclo 4
  digitalWrite(8, LOW);   // apagar verde B
  digitalWrite(13, HIGH); // manter vermelho A
  digitalWrite(9, HIGH);  // acender amarelo B
  delay(3000);

  // ciclo 5
  digitalWrite(13, LOW);  // apagar vermelho A
  digitalWrite(9, LOW);   // apagar amarelo B
  digitalWrite(11, HIGH); // acender verde A
  digitalWrite(10, HIGH); // acender vermelho B
  delay(3000);

  // ciclo 6
  digitalWrite(11, HIGH); // acender verde A
  digitalWrite(10, HIGH); // acender vermelho B

  oo 📟 Relatório: Uso do Multímetro 

O **multímetro** é uma ferramenta eletrônica versátil, utilizada para medir diferentes grandezas elétricas em circuitos, como **tensão (V)**, **corrente (A)** e **resistência (Ω)**.  

---

## 🔌 Principais Entradas

- **COM** → borne de referência/terra (fio preto).  
- **V/mA/Ω** → entrada para medir tensão, corrente baixa e resistência (fio vermelho).  
- **10A/20A** → entrada exclusiva para correntes mais altas (dependendo do modelo).  

---

## 🧾 Símbolos Mais Usados

| Símbolo | Função |
|---------|--------|
| **V⎓ (DCV)** | Tensão contínua (pilhas e baterias) |
| **V∿ (ACV)** | Tensão alternada (tomadas/rede elétrica) |
| **A⎓ (DCA)** | Corrente contínua |
| **A∿ (ACA)** | Corrente alternada |
| **Ω** | Resistência elétrica |
| **🔔 (bip)** | Teste de continuidade |
| **→|– (diodo)** | Teste de diodos e semicondutores |

---

## ⚡ Medindo Tomadas (Tensão AC)

- Utilize a escala de **200V ou 600V** (nunca abaixo disso).  
- Em rede de **127V**, a leitura típica varia entre **121V e 123V**.  
- Em rede de **220V**, use a escala de **600V**.  
- ⚠️ **Atenção:** nunca encostar as pontas de prova entre si quando estiverem na tomada.  

---

## 🔋 Tipos de Tensão

- **Tensão Contínua (DC):**  
  - Tem lado positivo (+) e negativo (–).  
  - Usada em **baterias e pilhas**.  

- **Tensão Alternada (AC):**  
  - Não possui polaridade fixa.  
  - Usada em **tomadas e rede elétrica**.  

---

## 📊 Exemplos de Medição

- **Bateria 9V:** leitura típica próxima a **9V** (ex.: 9,69V).  
- **Pilha AA/AAA:** valor nominal de **1,5V**.  
- **Bateria da placa-mãe (CR2032):** especificação de **3V**.  
  - Sempre instalar com o **lado negativo para baixo**.  
  - Colocar invertida pode **danificar o slot**.  

---

## 🌀 Medindo Resistência (Ω)

- Usado para resistores e continuidade de cabos.  
- “1” ou “OL” = **não há continuidade**.  
- Se apitar no modo **🔔**, significa que há passagem de corrente (fio bom).  

---

## 🔍 Medindo Corrente (A)

- Corrente deve ser medida **em série** (o multímetro entra no circuito).  
- Verifique se vai usar a entrada **mA** ou **10A**.  
- ⚠️ **Nunca medir corrente direto na tomada!** Risco de queimar o multímetro.  

---

## 🛡️ Cuidados de Segurança

- Ponta **preta sempre no COM**.  
- Escolha a escala **acima do valor esperado**.  
- Não medir resistência em componentes energizados.  
- Não deixar o multímetro no modo **corrente** ao medir tensão.  
- Guardar em local seco, longe de umidade.  

---

## 📌 Guia Rápido de Escalas

| O que medir | Escala no multímetro |
|-------------|-----------------------|
| Tomada 127V | **200V AC** |
| Tomada 220V | **600V AC** |
| Pilha AA/AAA | **20V DC** |
| Bateria 9V | **20V DC** |
| Bateria placa-mãe 3V | **20V DC** |
| Resistores | **Ω (faixa adequada)** |
| Continuidade de cabos | **🔔 (bip)** |

---

## 📝 Observação Final

- Quando a **voltagem de pilhas/baterias começar a cair**, significa que estão descarregando.  
- Valores muito abaixo da especificação indicam que é hora de **trocar ou recarregar**
}
