# CPU Completa de 8 Bits — Projeto de CPU Simples com Memória, Registrador Acumulador e ALU Integrada

## 🎥 Assista ao vídeo:
- A imagem abaixo te redireciona para o vídeo explicativo do projeto:
<div align="center">
  <a href="https://youtu.be/NCPiJ1pQdhU">
    <img src="https://i.ytimg.com/vi/9WJBmMQ8DsE/maxresdefault.jpg" alt="Vídeo do Projeto CPU Completa">
  </a>
</div>

- Você também pode assistir diretamente pelo [Google Drive](https://drive.google.com/file/d/1nM7PtPJ9TRLKO7bn5Ql6Oy4oWu6ovuEc/view?usp=sharing)

---

## 🟢 CPU Simples de 8 Bits com Memória, Acumulador e ALU Completa

## 📌 Descrição
Este projeto consiste na construção de uma **CPU simplificada de 8 bits**, projetada para funcionar em ciclo único, ou seja, realizando **leitura da instrução** e **execução** em um único passo.

A CPU conta com:
- **Memória de instruções** para armazenar as palavras de comando e operando.
- **Registrador acumulador**, responsável por armazenar os resultados das operações.
- **ALU completa**, com operações aritméticas, lógicas e de deslocamento.
- **Display de 7 segmentos** para visualização do resultado das operações.
- **Clock** para sincronização de todo o sistema.

---

## 🎯 Objetivos

✅ Construir uma **ALU de 8 bits**, com operações de:
- Soma
- Subtração
- Multiplicação
- Shift Right
- Shift Left
- AND
- OR
- XOR

✅ Implementar uma **memória EEPROM** para armazenar as instruções.

✅ Criar uma **palavra de instrução** com 4 bits para operação e 8 bits para operando.

✅ Desenvolver um **registrador acumulador** para armazenar operandos e resultados das operações.

✅ Integrar todos os componentes para execução automática das instruções armazenadas na memória.

✅ Utilizar **display de 7 segmentos** para exibição dos resultados.

✅ Sincronizar todas as operações utilizando **clock**.

---

## 📜 Especificações Técnicas

- **Entradas**:
  - **Memória de instruções**: palavras com 4 bits de operação e 8 bits de operando.
  - **Clock**: sinal para sincronização das operações.

- **Palavra de instrução (12 bits totais)**:
  - **Bits 11 a 8**: Código da operação.
  - **Bits 7 a 0**: Operando (valor de entrada para as operações).

- **Operações suportadas**:
  - `0000` = A

  - `0001` = OR

  - `0010` = AND

  - `0011` = XOR

  - `0100` = SHIFT LEFT

  - `0101` = SUBTRATOR

  - `0110` = SOMADOR

  - `0111` = SHIFT RIGHT

  - `1000` = MULTIPLICADOR

- **Saídas**:
  - **Display de 7 segmentos**: mostra o resultado das operações.
  - **Acumulador**: mantém o valor intermediário das operações.

---

## 🚀 Conclusão

Este projeto de **CPU de 8 bits** consolida conhecimentos essenciais de **arquitetura de computadores**, **lógica digital** e **integração de componentes básicos** como memória, registradores e ALU.

Ao implementar uma palavra de instrução simples e automatizar a execução por meio de memória EEPROM e clock, conseguimos criar um sistema funcional que lê e executa comandos sequencialmente, armazenando resultados no acumulador e exibindo-os no display.

A experiência fortaleceu nossa compreensão de **circuitos sequenciais**, **controle por clock**, e da importância da correta integração de **memória, registradores e ALU** para a construção de uma CPU básica.

---
