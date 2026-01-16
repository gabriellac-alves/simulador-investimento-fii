# 📊 Simulador de Investimentos em Fundos Imobiliários (FIIs) 

## 📌 Desafio DIO – Excel Aplicado a Finanças

Este projeto foi desenvolvido como parte de um **desafio prático da DIO**, com o objetivo de aplicar conceitos de **Excel**, **cálculos financeiros** e **documentação técnica**, por meio da criação de uma ferramenta de simulação de investimentos em **Fundos Imobiliários (FIIs)**.

A planilha permite que o usuário simule investimentos de forma simples e automatizada, visualizando o crescimento do patrimônio e a geração de renda passiva ao longo do tempo.

---

## 🎯 Objetivo do Projeto

Desenvolver uma planilha em Excel capaz de:

* Simular investimentos em FIIs;
* Calcular patrimônio acumulado com base em aportes mensais;
* Estimar dividendos mensais;
* Auxiliar o investidor na tomada de decisão, considerando diferentes perfis de risco.

---

## 🧠 Conceitos Aplicados

Durante o desenvolvimento do projeto, foram aplicados os seguintes conceitos:

* Juros compostos
* Valor Futuro (VF)
* Renda passiva
* Perfis de investidor
* Organização de dados no Excel
* Automação de cálculos financeiros

---

## 🗂️ Estrutura da Planilha

### 🔹 Aba APP

Área de interação com o usuário, onde são informados:

* Salário mensal
* Valor de investimento mensal
* Perfil de investidor

A partir desses dados, a planilha calcula automaticamente:

* Patrimônio acumulado
* Renda passiva mensal
* Projeções para **2, 5, 10, 20 e 30 anos**

### 🔹 Aba DATABASE

Contém as regras de investimento para cada perfil:

* Conservador
* Moderado
* Agressivo

Cada perfil possui taxas de rendimento específicas, utilizadas nos cálculos da simulação.

---

## 🛠️ Fórmulas Utilizadas

### ✔ Valor Futuro (Patrimônio Acumulado)

```excel
=VF(taxa; período; -aporte_mensal; -aporte_inicial)
```

Utilizada para projetar o crescimento do capital ao longo do tempo, considerando juros compostos.

### ✔ Dividendos Mensais

```excel
=Patrimônio_Acumulado * Rendimento_da_Carteira
```

Calcula a renda passiva mensal gerada pelos investimentos.

### ✔ Regra dos 30% (Sugestão de Investimento)

```excel
=Salário * 0,30
```

Define um valor recomendado de investimento mensal com base no salário informado.

---

## 🚀 Aprendizados

Com este desafio, foi possível:

* Aplicar fórmulas financeiras reais no Excel;
* Criar cenários de investimento de longo prazo;
* Organizar bases de dados para diferentes perfis de investidor;
* Documentar um projeto técnico de forma clara e estruturada;

---


## 📬 Considerações Finais

Este projeto reforça a importância do Excel como ferramenta poderosa para análise financeira e apoio à tomada de decisão. A simulação de investimentos em FIIs proporciona uma visão clara do impacto do tempo, dos aportes e dos rendimentos no crescimento patrimonial.

Projeto desenvolvido para fins educacionais no programa da **Digital Innovation One (DIO)**.

---

📈 *Bons investimentos e bons estudos!*
