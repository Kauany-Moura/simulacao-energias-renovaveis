# 🌱 Simulação de Uso de Energias Renováveis  
### *Modelagem dos efeitos da adoção de fontes renováveis no consumo, emissões e custos energéticos*

Este projeto apresenta uma simulação em Python que analisa como a adoção progressiva de energias renováveis impacta o consumo total de energia, as emissões de CO₂ e os custos ao longo do tempo.  
O objetivo é fornecer um modelo simples, didático e facilmente expansível para estudos relacionados à transição energética.

---

## 📘 Descrição do Projeto

O código realiza uma simulação de 10 anos considerando:

- Crescimento anual do consumo total de energia  
- Aumento gradual da participação de fontes renováveis  
- Diferenças de custo e emissão entre energia fóssil e renovável  

A simulação calcula:

- Energia renovável e fóssil (GWh)  
- Participação renovável (%)  
- Emissões totais (t CO₂)  
- Custo total da matriz energética  
- Visualizações da evolução da matriz e emissões  

---

## 📊 Resultados Esperados

- Redução contínua de emissões de CO₂  
- Aumento significativo da energia renovável na matriz  
- Redução de custos devido à menor dependência de combustíveis fósseis  
- Crescimento controlado do consumo energético  

---

## 🧠 Metodologia

O modelo usa:

- Progressão exponencial para crescimento de consumo  
- Adoção linear de renováveis de 10% → 60%  
- Custos e emissões diferentes para fósseis e renováveis  
- Visualização com matplotlib

---

## 🚀 Como Executar
1. Instale as dependências:
   `pip install numpy pandas matplotlib`
2. Execute o script:
   `python main.py`

---

## 📈 Visualizações

O script gera dois gráficos:

- Evolução das energias renovável x fóssil
- Evolução das emissões totais de CO₂

Essas visualizações facilitam a interpretação das tendências da matriz energética.
