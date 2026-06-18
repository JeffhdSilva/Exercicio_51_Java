# ⚡ EletroCalc Pro - Dimensionamento Elétrico Inteligente

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Swing](https://img.shields.io/badge/Swing-GUI-blue?style=for-the-badge)
![FlatLaf](https://img.shields.io/badge/FlatLaf-UI%20Modern-purple?style=for-the-badge)
![Status](https://img.shields.io/badge/Projeto-Concluído-success?style=for-the-badge)

---

## 🚀 Sobre o projeto

O **EletroCalc Pro** é um sistema desenvolvido em Java com interface gráfica (Swing), voltado para o dimensionamento elétrico residencial.

O sistema calcula automaticamente a corrente elétrica e sugere o disjuntor e a bitola dos fios com base em regras técnicas simplificadas.

---

## ✨ Funcionalidades

- Entrada de potência (Watts)
- Seleção de tensão (110V ou 220V)
- Cálculo automático da corrente elétrica (Amperes)
- Aplicação de fator de segurança (1.25)
- Sugestão de disjuntor ideal
- Sugestão de bitola de fios
- Exibição de relatório completo
- Interface gráfica moderna com FlatLaf
- Validação de entrada numérica

---

## 🖥 Interface

O sistema possui uma interface gráfica desenvolvida em Java Swing (JFrame) com:

- Campos de entrada
- Radio buttons para voltagem
- Checkboxes para seleção de cálculo
- Área de resultado
- Tema moderno (FlatLaf Dark)

---

## 🧠 Regras de cálculo

Corrente elétrica:
I = P / V

Fator de segurança:
Disjuntor = Corrente × 1.25

---

## 📊 Tabela simplificada de dimensionamento

| Corrente / Disjuntor | Bitola do fio |
|----------------------|--------------|
| até 12A              | 1,0 mm²      |
| até 15A              | 1,5 mm²      |
| até 21A              | 2,5 mm²      |
| até 28A              | 4 mm²        |
| até 36A              | 6 mm²        |
| até 50A              | 10 mm²       |
| acima de 50A         | 16 mm²       |

---

## 🛠 Tecnologias utilizadas

- Java  
- Swing (JFrame, JButton, JTextField, JCheckBox, JRadioButton)  
- FlatLaf (tema moderno)  
- POO (Programação Orientada a Objetos)  
- DecimalFormat  

---

## 📂 Estrutura do projeto

NewJFrame.java → Interface principal do sistema

---

## ▶️ Como executar

1. Compile o projeto:
javac NewJFrame.java

2. Execute:
java NewJFrame

Ou abra diretamente em uma IDE como NetBeans.

---

## 💡 Conceitos aplicados

- Interface gráfica com Swing  
- Lógica de engenharia elétrica aplicada  
- Estruturas condicionais complexas  
- Manipulação de eventos  
- Reutilização de código  
- Formatação de dados  
- Experiência de usuário (UX básica)  

---

## 📈 Possíveis melhorias futuras

- Separação em arquitetura MVC  
- Exportação de relatório em PDF  
- Histórico de cálculos  
- Banco de dados local  
- Versão web (Spring Boot)  
- Versão mobile  

---

## 👨‍💻 Autor

Projeto desenvolvido como prática de Java, lógica de programação e sistemas interativos com interface gráfica.
