# Análise Estrutural e Dimensionamento: Pórtico Metálico Móvel (10t) 🏗️

Este projeto apresenta o memorial de cálculo e a validação estrutural de um pórtico metálico tubular destinado ao içamento de cargas de até **10 toneladas** em operações de poços de serviço com **20 metros de profundidade**.

O diferencial deste trabalho é a abordagem **End-to-End**: desde a concepção geométrica e escolha de materiais até a entrega do memorial de cálculo final validado por normas brasileiras.

---

## 🛠️ Especificações do Projeto
* **Capacidade Nominal:** 10.000 kg (100 kN).
* **Material:** Aço Estrutural **ASTM A572 Grau 50** (Tensão de escoamento: **345 MPa**).
* **Geometria:** Estrutura em perfis tubulares para otimização de peso e resistência à torção.
* **Aplicação:** Içamento de caçambas de $4,5 m^3$ em ambientes confinados.

## 📈 Etapas de Desenvolvimento

### 1. Concepção e Modelagem CAD
Desenvolvimento da geometria no **FreeCAD/Solid Edge**, focando na ergonomia de montagem e estabilidade global da estrutura.

### 2. Análise por Elementos Finitos (FEA)
Utilização do **ANSYS Mechanical** para simulação numérica, contemplando:
* **Estado Limite Último (ELU):** Verificação de tensões sob carga majorada (Fator de 1,82) para evitar falha catastrófica.
* **Estado Limite de Serviço (ELS):** Verificação de flechas e deformações para garantir a operabilidade.
* **Análise de Flambagem (Buckling):** Determinação do multiplicador de carga crítica para os pilares.

### 3. Análise de Fadiga
Cálculo da vida útil remanescente e acúmulo de dano utilizando a ferramenta **Fatigue Tool**, garantindo que a estrutura suporte os ciclos operacionais previstos sem falhas por fadiga.



## 📋 Conformidade Normativa
O projeto foi integralmente verificado segundo as normas:
* **NBR 8800:** Projeto de estruturas de aço.
* **NBR 16239:** Projeto de estruturas de aço com perfis tubulares.
* **NBR 8400:** Cálculo de equipamentos para levantamento e movimentação de cargas.

## 🚀 Resultados Principais
* **Segurança:** Coeficiente de segurança mínimo de **1,5** nas regiões críticas.
* **Otimização:** Atendimento aos requisitos de deflexão máxima ($L/600$).
* **Estabilidade:** Multiplicador de flambagem superior aos limites normativos, assegurando a rigidez do conjunto.

---

## 📂 Estrutura do Repositório
* `/docs`: Memorial de cálculo detalhado (PDF) e referências.
* `/media`: Mapas de tensão, deformação e fadiga extraídos do ANSYS.
* `/scripts`: (Opcional) Planilhas ou códigos Python usados na automação dos cálculos.

---
📧 **Contato:** Paulo Alberto Barros - www.linkedin.com/in/paulo-barros-365983380
