# Aula – Análise de Circuitos por Proporção (com Voltímetro)

## 🎓 Disciplina: Termodinâmica, Eletricidade e Magnetismo  
## ⏰ Duração: 2 horas  

---

## 🔬 Objetivo da Aula
- Compreender a técnica de **análise proporcional de circuitos resistivos**, com foco no uso do **voltímetro**.  
- Aplicar passo a passo uma estratégia para encontrar a tensão em cada resistor de um circuito.

---

## ✅ Etapas da Análise por Proporção

### **1. Verificar se existe circuito série-paralelo**
- Identifique se o circuito possui resistores **em série, em paralelo ou mistos**.

### **2. Caso tenha parte em paralelo, verificar se é ímpar ou par**
- **Se ímpar**: Realizar **redução de dois em dois** até obter um par ou um equivalente.
- **Se par**: Aplicar a técnica da **proporção direta**:
  - Calcular:  
    \$$ V = \frac{R_{maior}}{R_1 + R_2} \times V_{total} \$$

### **3. Com todo o circuito em série, verificar a proporção entre os resistores**
- Para resistores em série:
  - Determine a **proporção entre os valores de resistência**:  
    Ex: R1 = 2Ω, R2 = 4Ω, R3 = 6Ω  ➔ Proporção: 2 : 4 : 6

### **4. Somar todas as proporções**
\$$ P_{total} = P_1 + P_2 + P_3 + … \$$

### **5. Dividir a tensão total do circuito pela soma das proporções**
\$$ V_{div} = \frac{V_{fonte}}{P_{total}} \$$

### **6. O valor obtido é a divisão de tensão**
- Essa será a "base" para multiplicar pelas proporções individuais.

### **7. Multiplicar a divisão de tensão por cada proporção**
\$$ V_{R_i} = P_i \times V_{div} \$$
- Resultado: tensão individual em cada resistor (ideal para leitura com **voltímetro**).

---

## 🔧 Exemplo Ilustrado
**Circuito com resistores em série:** R1 = 2Ω, R2 = 3Ω, R3 = 5Ω  
**Fonte de tensão:** 100V

**Passos:**
1. Proporção: 2 : 3 : 5
2. Soma: 2 + 3 + 5 = 10
3. Divisão de tensão: 100V / 10 = 10V
4. Tensão em cada resistor:
   - R1: 2 × 10 = 20V
   - R2: 3 × 10 = 30V
   - R3: 5 × 10 = 50V

---

## 📚 Aplicações Práticas
- Medida de tensão em resistores sem precisar calcular corrente.
- Agiliza a análise em circuitos série-paralelo.
- Permite prever leituras reais do **voltímetro**.

---

## 📈 Atividade Proposta (em sala)
**Dado:** Circuito com fonte de 120V e resistores R1 = 3Ω, R2 = 6Ω, R3 = 9Ω (em série).  
**Tarefa:** Calcular a tensão individual em cada resistor utilizando o método da proporção.

---

## 📚 Para Estudar
- Livro: Fundamentos de Física, vol. 3 (Halliday) – cap. 25 e 26
- Simulador: Tinkercad Circuits ou Falstad Circuit Simulator

---


