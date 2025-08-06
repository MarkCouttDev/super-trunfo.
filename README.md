# 🌆 Super Trunfo de Cidades — Projeto em C

Projeto desenvolvido por **Marcos Augusto do Couto** como parte dos desafios de nível *novato*, *aventureiro* e *avançado* na plataforma **SAVA**.

---

## 🎯 Objetivo

Criar um programa em linguagem C que simule cartas no estilo Super Trunfo, comparando cidades brasileiras por atributos como população, área, PIB, entre outros. Cada carta representa uma cidade, com indicadores calculados automaticamente.

---

## 🃏 Atributos por Carta

Cada carta contém os seguintes dados:

- **Estado** (`char`) — letra de A a H  
- **Código da carta** (`char[4]`) — ex: A01  
- **Nome da cidade** (`char[50]`)  
- **População** (`unsigned long int`)  
- **Área** (`float`) — km²  
- **PIB** (`float`) — bilhões de reais  
- **Pontos turísticos** (`int`)  
- **Densidade populacional** (`float`) — habitantes/km²  
- **PIB per capita** (`float`) — reais  
- **Super Poder** (`float`) — soma ponderada com inverso da densidade  

---

## ⚙️ Funcionalidades

- ✅ Cadastro completo das duas cartas
- ✅ Cálculo automático de:
  - Densidade populacional
  - PIB per capita
  - Super Poder
- ✅ Comparação entre atributos:
  - Atributos comuns: vence o **maior valor**
  - Densidade populacional: vence o **menor valor**
- ✅ Exibição clara do resultado, mostrando qual carta venceu

---

## 🧪 Tecnologias Utilizadas

- **Linguagem:** C  
- **Compilador:** Dev-C++ / GCC  
- **Estilo:** sem estruturas de repetição ou decisão complexas  
- **Sistema Operacional:** Windows / Linux / macOS  

---

## 🚀 Como Compilar e Executar

### Linux/macOS com GCC

```bash
gcc super_trunfo.c -o super_trunfo
./super_trunfo
