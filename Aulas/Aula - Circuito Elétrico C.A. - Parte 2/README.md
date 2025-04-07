# Aula – Filtros com Circuitos RC

## 🎓 Disciplina: Termodinâmica, Eletricidade e Magnetismo
## ⏰ Duração: 2 horas

---

## 🔬 Objetivos da Aula
- Entender o funcionamento dos circuitos RC como **filtros passa-baixa** e **passa-alta**.
- Analisar a resposta em frequência de um circuito RC.
- Calcular a **frequência de corte** e a **atenuação** do sinal.
- Aplicar os conceitos em situações reais de filtragem de sinais.
- Compreender o **diagrama de Bode** e a **função de transferência**.

---

## 🛠️ O que é um Filtro?
> Um **filtro** é um circuito que permite a passagem de determinados sinais com base em sua **frequência**, atenuando outros.

Tipos mais comuns:
- **Passa-baixa:** permite frequências baixas, atenua altas.
- **Passa-alta:** permite frequências altas, atenua baixas.

---

## 🔌 Circuito RC Passa-Baixa
### Configuração:
- Entrada conectada em série com resistor (R)
- Saída conectada em paralelo com capacitor (C)

### Comportamento:
- Baixas frequências: capacitor atua como circuito aberto → sinal passa.
- Altas frequências: capacitor atua como curto → sinal vai para o terra.

### Função de Transferência:
\$$ H(f) = \frac{1}{\sqrt{1 + (2\pi f RC)^2}}\$$

---

## 🔋 Circuito RC Passa-Alta
### Configuração:
- Entrada conectada ao capacitor (C)
- Resistor (R) ligado entre saída e terra

### Comportamento:
- Baixas frequências: capacitor bloqueia sinal → atenuado.
- Altas frequências: capacitor permite passagem do sinal.

### Função de Transferência:

\$$H(f) = \frac{(2\pi f RC)}{\sqrt{1 + (2\pi f RC)^2}}\$$

---

## 🔁 O que é Função de Transferência?
> A **função de transferência** representa matematicamente a relação entre a saída e a entrada de um sistema em função da frequência ou variável complexa \( s \).

### No domínio da frequência:

\$$H(f) = \frac{V_{\text{saída}}(f)}{V_{\text{entrada}}(f)}\$$

### Para que serve?
- Permite prever o comportamento do sistema para qualquer frequência.
- É base para construir o **diagrama de Bode**.
- Facilita a análise de estabilidade e resposta do sistema.

---

## 📊 O que é o Diagrama de Bode?
> O **Diagrama de Bode** é uma representação gráfica da função de transferência em duas partes:

1. **Magnitude (ganho)** vs. frequência (em escala logarítmica)
2. **Fase** vs. frequência (em escala logarítmica)

### Eixos:
- Eixo x: \$$\log_{10}(f)\$$ em Hz
- Eixo y (ganho): \$$20 \log_{10} |H(f)|\$$ em decibéis (dB)
- Eixo y (fase): em graus (°)

### Para que serve?
- Visualizar como o sistema **amplifica ou atenua** sinais em diferentes frequências.
- Estimar **frequência de corte** e comportamento assintótico.

---

## 🧭 Como Construir o Diagrama de Bode?
1. **Determine a função de transferência** \$$H(f)\$$ do circuito.
2. **Calcule a frequência de corte**:

   \$$f_c = \frac{1}{2\pi RC}\$$
   
4. **Monte uma tabela com valores de frequência** (ex: 0.1·fc, fc, 10·fc...)
5. **Calcule o ganho em dB** para cada frequência:
   
   \$$G(f) = 20 \cdot \log_{10} |H(f)|\$$
   
7. **Opcional**: calcule a **fase** para cada ponto (útil para sinais senoidais).
8. **Plote os dados** em dois gráficos separados (ganho e fase).

---

## 📈 Resposta em Frequência
- Abaixo de \$$(f_c)\$$: ganho próximo de 0 dB (passa)
- Acima de \$$(f_c)\$$: ganho decai → -20 dB por década

---

## 📍 Aplicações Típicas
- Filtragem de ruído em sensores
- Suavização de sinais analógicos
- Separador de faixas de frequência em sistemas de áudio
- Circuitos anti-aliasing para conversores AD

---

## 🧪 Exercício Guiado
**Dado:** R = 1 kΩ, C = 100 nF  
**Perguntas:**
- a) Qual a frequência de corte?
- b) Monte a função de transferência.
- c) Calcule os valores de ganho para 10 Hz, 100 Hz, 1 kHz, 10 kHz, 100 kHz
- d) Construa o diagrama de Bode (ganho)

---

## 🛠️ Atividades Práticas

### 🔧 Atividade 1: Simulação de Filtro RC Passa-Baixa

Monte o circuito em um simulador (PhET, Falstad, Tinkercad)

Altere a frequência da fonte de entrada

Meça a tensão na saída para várias frequências

Construa a curva experimental de resposta em frequência

### 🔧 Atividade 2: Simulação de Filtro RC Passa-Alta

Monte o circuito inverso da atividade anterior

Meça o comportamento da saída para frequências baixas, médias e altas

Compare com o gráfico teórico da função de transferência

### 🔧 Atividade 3: Análise de ruído

Simule um sinal misto (senoide + ruído de alta frequência)

Aplique filtro RC passa-baixa e observe a saída

Explique o resultado

### 🔧 Atividade 4: Escolha de componentes para uma aplicação

Escolha um valor de frequência de corte (ex: 1 kHz)

Determine valores possíveis para R e C que satisfaçam 

Monte e teste no simulador
  
---

## 📚 Referências
- Halliday, Resnick – Fundamentos de Física, Vol. 3, cap. 33 e 34
- Simuladores: Falstad, PhET, Tinkercad

---

📌 Na próxima aula: introdução aos **circuitos RLC** e **seleção de frequência!**

