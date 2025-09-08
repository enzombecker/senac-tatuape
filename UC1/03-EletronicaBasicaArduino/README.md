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
