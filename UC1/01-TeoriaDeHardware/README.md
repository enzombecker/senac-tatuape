# 🖥️ Peças para PC

## 🔧 Principais componentes

- **Processador (CPU)**
- **Placa-mãe**
- **Memória RAM (DDR)**
- **Armazenamento** (SSD ou HD)
- **Placa de vídeo (GPU)**
- **Fonte (PSU)**
- **Gabinete**
- **Air cooler**
- **Fan / Ventoinha**
- **Monitor, teclado e mouse**
- **Sistema operacional**

---

## ⚡ Processador

### Tipos
- **i3 / Ryzen 3** → entrada  
- **i5 / Ryzen 5** → intermediário  
- **i7 / Ryzen 7** → desempenho  
- **i9 / Ryzen 9** → trabalho pesado  

### Marcas
- **Intel** → i1 ao i14 / Ultra  
- **AMD** → Ryzen 1000, 2000, 3000 / 4000, 5000, 7000, 8000, 9000  

### Como saber qual é melhor?
- **Intel Core i5 14400** é inferior ao **i5 14600**  
- **AMD Ryzen 5 7500F** é inferior ao **Ryzen 5 7600**

---

## 🔤 Sufixos dos Processadores

### AMD
- **G** → gráficos integrados *(ex: Ryzen 5 8600G)*  
- **X** → maior frequência *(ex: Ryzen 5 5600X)*  
- **F** → sem gráficos integrados *(ex: Ryzen 5 7600F)*  
- **3D** → maior cache *(ex: Ryzen 7 7800X3D)*  

### Intel
- **F** → sem gráficos integrados  
- **K** → desbloqueado para overclock  

---

## 🧮 Núcleos e Threads

- **Cores (núcleos):** parte física do processador  
- **Threads:** processadores lógicos (tarefas virtuais por núcleo)  

Exemplo:  
- **2/4** → melhor que **2/2** (dobro de threads melhora o desempenho)  

### Caso especial da Intel
Alguns modelos usam **Performance Cores (P-Cores)** e **Efficient Cores (E-Cores):**

- **10 núcleos (10C/16T)**  
  - 6 P-Cores  
  - 4 E-Cores  
  - 16 Threads  

---

## 🔌 Sockets

- **Intel** → LGA  
- **AMD** → AM4 / AM5  


# 🖥️ Gerações de Soquetes e Exemplos

## 🔹 Intel
- **LGA 1200 (10ª e 11ª geração)**  
  - Exemplo: **Core i5 10400** + Placa-mãe **H510**  

- **LGA 1700 (12ª até 14ª geração)**  
  - Exemplo: **Core i9 14900F** + Placa-mãe **B760**  

- **LGA 1851 (nova geração Ultra série 200)**  
  - Exemplo: **Core Ultra 9 285** + Placa-mãe **B860**  

## 🔹 AMD
- **AM4 (Ryzen 1000 até 5000)**  
  - Exemplo: **Ryzen 5 5600** + Placa-mãe **B550**  

- **AM5 (Ryzen 7000 até 9000)**  
  - Exemplo: **Ryzen 9 9900X** + Placa-mãe **X870**  

---

# ⚡ Cache x Memória RAM

## 🔸 Cache (dentro do processador)
- É uma memória **muito rápida e próxima da CPU**.  
- **Quanto maior o cache → menor a latência → mais desempenho**, principalmente em jogos e tarefas que acessam dados repetidamente.  

## 🔸 Memória RAM
- **Latência menor → responde mais rápido aos pedidos do processador**.  
- **Frequência maior (MHz) → mais velocidade na transferência de dados**.  
- O ideal é **equilíbrio entre frequência e baixa latência**.  

---
✅ Resumindo: **cache ajuda o processador a pensar mais rápido**, enquanto **RAM com baixa latência e alta frequência ajuda a alimentar a CPU com dados sem atrasos**.


 Relatório Comparativo de Processadores AMD  
### Ryzen 9 9950X vs Ryzen 7 9800X3D em Jogos 🎮

---

## 📌 Resumo Executivo
Apesar de o **Ryzen 9 9950X** (16c/32t) ter mais núcleos e ser mais caro, o **Ryzen 7 9800X3D** (8c/16t) vence em **desempenho em jogos**.  
O motivo principal é a tecnologia **3D V-Cache**, que aumenta drasticamente o cache L3 disponível e reduz a latência — fator decisivo para games.  

---

## 🔑 Principais Motivos

### 1) 3D V-Cache como “turbo” para jogos
- O **9800X3D** possui **96 MB de L3 empilhado em 3D**, ideal para engines de jogos sensíveis a latência.  
- Reduz acessos à RAM → melhora **FPS médio** e **1% lows**.  

### 2) Topologia de Chiplets (CCD)
- O **9950X** usa **dois CCDs** → maior latência ao alternar threads.  
- O **9800X3D** tem **um único CCD com V-Cache**, evitando penalidades.  

### 3) Escalabilidade em Jogos
- Jogos modernos raramente usam **mais de 8 núcleos de forma eficiente**.  
- Mais núcleos ≠ mais FPS → cache e latência importam mais.  

### 4) Clocks vs. Cache
- **9950X**: 4,3 GHz base / 5,7 GHz turbo.  
- **9800X3D**: 4,7 GHz base / 5,2 GHz turbo **+ V-Cache**.  
- O equilíbrio de **clock + cache gigante** dá vantagem ao 9800X3D.  

### 5) Otimizações de Software
- Drivers e Windows estão **otimizados para CPUs X3D**.  
- Isso garante consistência e estabilidade no uso em jogos.  

---

## 🎯 Quando o Ryzen 9 9950X é melhor
- **Produtividade pesada**: renderização, edição de vídeo, compilação, simulação, IA local.  
- Tarefas altamente **multi-threaded** aproveitam os **16c/32t**.  
- Mas em jogos, fica **atrás do 9800X3D**.  

---

## 📊 Considerações Práticas
- **Resolução importa**:
  - Em **1080p/1440p com GPUs topo de linha** → 9800X3D abre vantagem.  
  - Em **4K** → diferenças diminuem, pois a GPU vira gargalo.  
- **BIOS e drivers atualizados** são essenciais para extrair o máximo dos Ryzen 9000.  

---

## 💰 Comparativo de Preço (Brasil)
- Ryzen 9 9950X — **R$ 3.999,90**  
- Ryzen 7 9800X3D — **R$ 3.099,90**  

➡️ Em jogos, o **9800X3D entrega mais performance por real investido**. 


# 🔎 Especificações do AMD Ryzen 9 9950X3D

- **4.3GHz (5.7GHz Turbo)** → Frequência de operação do processador.  
  - *4.3GHz*: velocidade base.  
  - *5.7GHz Turbo*: velocidade máxima em modo de aumento automático (boost).

- **16-Cores** → Quantidade de núcleos físicos.  
  - Cada núcleo é capaz de executar tarefas de forma independente.

- **32-Threads** → Número de processos simultâneos que podem ser executados.  
  - Graças ao *SMT (Simultaneous Multithreading)*, cada núcleo pode lidar com 2 threads.

- **AM5** → Tipo de soquete da placa-mãe compatível.  
  - Necessário para encaixar fisicamente o processador.

- **Sem Cooler** → O processador **não acompanha sistema de resfriamento**.  
  - É preciso comprar separadamente um **air cooler** ou **water cooler** adequado.

### Intel
# 📌 Intel Ultra 9 285 — Explicação Simples

## 🧩 CPU (processador)
- **24 núcleos:** 8 rápidos (P-cores) + 16 econômicos (E-cores).  
- **24 threads:** tarefas simultâneas que ele consegue fazer.  
- **Velocidade máx.:** até 5,6 GHz (quando precisa de mais desempenho).  
- **Cache L3 (36 MB):** memória super rápida dentro do processador.  
- **Consumo:** 65W normal, até 182W no máximo.  
- **Tecnologia 3 nm:** mais moderno e eficiente.

## 💾 Memória (RAM)
- **Até 192 GB DDR5:** suporta muita memória, bem rápida (6400 MHz).  
- **2 canais:** caminhos para trocar dados com a RAM.  
- **ECC:** memória com correção de erros (mais segurança).  

## 🎮 Gráficos (GPU integrada)
- **Frequência:** de 300 MHz até 2 GHz.  
- **Resolução:** até 8K a 60 Hz.  
- **Suporta DirectX 12, OpenGL, OpenCL:** compatível com jogos e softwares.  
- **Quick Sync:** acelera vídeos (edição, streaming).  
- **Até 4 monitores conectados.**

## 🤖 NPU (para IA)
- **13 TOPS:** poder dedicado a inteligência artificial.  
- **Suporta frameworks de IA:** como OpenVINO, ONNX, WindowsML etc.  

## ⚡ Expansões
- **Thunderbolt 4:** conexões rápidas (dados, vídeo e energia).  
- **PCIe 5.0/4.0:** entrada para placas de vídeo e SSDs.  
- **24 linhas PCIe:** número de dispositivos que pode conectar.  

## 🔥 Encapsulamento
- **Soquete FCLGA1851:** onde encaixa na placa-mãe.  
- **Temperatura máx.:** 105 °C.  

## 🔐 Tecnologias extras
- **Thread Director:** distribui tarefas entre núcleos rápidos e econômicos.  
- **vPro:** recursos de segurança e gerenciamento remoto.  
- **Virtualização:** rodar vários sistemas no mesmo PC.  
- **AES / Boot Guard:** mais proteção e criptografia.  
- **TDT:** detecta ameaças em tempo real.  

---
✅ Em resumo: o **Intel Ultra 9 285** é um processador super moderno, rápido, eficiente, com **gráficos, inteligência artificial, segurança e suporte a muitas tecnologias avançadas**.



<img width="1200" height="1200" alt="VRM" src="https://github.com/user-attachments/assets/98255393-7ee0-4731-b683-4323770fccbd" />

<img width="702" height="700" alt="placa mae" src="https://github.com/user-attachments/assets/52c62952-daab-4d91-88a6-ac7e04cfaa44" />

![Placa-Branca-VRM](https://github.com/user-attachments/assets/053ac35f-2035-44cf-86f6-fa6855a1014c)[README.md](https://github.com/user-attachments/files/22242399/README.md)

![placa-mae-asus-tuf-gaming-x670e-plus-aula](https://github.com/user-attachments/assets/5dc68823-c72d-474c-94a4-8779e44c36be)

![Placa-Mãe MSI Pro A620M-E-Aula](https://github.com/user-attachments/assets/3eaafb1c-a9c3-4cb4-834c-e5394c2a70cb)

![placa A](https://github.com/user-attachments/assets/9877193d-52e6-458e-936a-901564865845)

# 📜 Componentes da PLACA-A

1. **Socket**  
2. **VRM**  
3. **PWM-Fans / Fan do cooler**  
4. **RAM DDR5**  
5. **Conector CPU (8 pinos)**  
6. **Debug LED**  
7. **ATX Conector da Fonte (16 pinos)**  
8. **Conector SATA**  
9. **Painel Frontal**  
10. **USB**  
11. **Conector USB 2.0**  
12. **Conector Áudio**  
13. **PCI x1 / Rede**  
14. **Bateria**  
15. **PCI 16x / Placa de Vídeo**  
16. **SSD**  
17. **SYS Fan 


