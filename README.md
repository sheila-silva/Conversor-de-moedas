# 💱 Conversor de Moedas
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=flat)](LICENSE)

Aplicação console em Java para conversão de moedas em tempo real utilizando a API ExchangeRate-API. O projeto implementa boas práticas de programação orientada a objetos, validação de entrada e histórico de conversões.

**Estruturas de Classes**

<br>

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/ad7836e7-c129-4391-91e3-b533df1f42d7" 
    alt="currencyconverterimage" 
    width="500"
  >
</p>

<br>
<br>

✨ Funcionalidades

1️⃣ Conversão de Moedas

-Conversão em tempo real entre mais de 160 moedas

-Tratamento de entrada numérica (aceita vírgula e ponto)

-Taxas de câmbio atualizadas via API externa

2️⃣ Histórico de Conversões

-Registro de todas as conversões realizadas na sessão

-Timestamp com data e hora de cada operação

-Visualização formatada do histórico

3️⃣ Validação de Dados

-Verificação de códigos de moeda válidos via API

-Validação de formato (3 letras maiúsculas)

-Tratamento de exceções e entradas inválidas

-Feedback claro ao usuário

<br>
<br>

## 🛠️ Technologias

-Java 17

-HttpClient

-Gson 

-ExchangeRate-API 

<br>
<br>

**Como utilizar a API**

1. Clone o repositório
bashgit clone https://github.com/seu-usuario/currency-converter.git

2. Configure a API Key

3.Inicie o prorama e veja o menu principal:

### **Menu Principal**
```
===== Conversor de Moedas =====
1. Converter moedas
2. Ver histórico de conversões
3. Sair
```

### **Fluxo de Conversão**

**1. Selecione a opção 1**

**2. Digite o código da moeda de origem:**
```
Digite o código da moeda de origem (ex: USD): USD
```

**3. Digite o código da moeda de destino:**
```
Digite o código da moeda de destino (ex: BRL): BRL
```

**4. Digite o valor:**
```
Digite o valor a converter: 100
Valor convertido: 493.50 BRL
```

**5. Visualize o histórico (opção 2):**
```
===== Histórico de Conversões =====
[10/01/2026 14:30:45] 100.00 USD -> 493.50 BRL
[10/01/2026 14:35:20] 50.00 EUR -> 267.80 BRL
```

---

## 🎯 Exemplos de Uso

### **Conversão USD para BRL**
```
Opção: 1
Origem: USD
Destino: BRL
Valor: 100
Resultado: 493.50 BRL
```

### **Conversão EUR para JPY**
```
Opção: 1
Origem: EUR
Destino: JPY
Valor: 50
Resultado: 8125.30 JPY
````

<br>
<br>

# Agradecimentos / Referências 

Alura - Cursos On Line de Tecnologia 

Oracle - Oracle Next Education - ONE


<br>


----------


# Autora:

Sheila M. M. L. Silva 

https://www.linkedin.com/in/sheilasheila/

