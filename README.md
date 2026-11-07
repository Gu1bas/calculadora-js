# Calculadora em JavaScript (POO)

Uma calculadora interativa e funcional desenvolvida em JavaScript Vanilla utilizando os princípios da **Programação Orientada a Objetos (POO)** com Classes ES6, HTML5 e CSS3.

> Projeto desenvolvido durante os estudos do curso de JavaScript do instrutor **Matheus Battisti (Hora de Codar)**.

---

## Funcionalidades

- [x] **Operações Básicas:** Adição (+), Subtração (-), Multiplicação (*) e Divisão (/).
- [x] **Visor Duplo:** Visualização em tempo real do valor atual e do histórico da operação anterior.
- [x] **Tratamento de Pontos Decimais:** Prevenção contra múltiplos pontos no mesmo número.
- [x] **Troca Dinâmica de Operador:** Possibilidade de alterar a operação matemática antes de digitar o próximo número.
- [x] **Funções de Limpeza e Correção:**
  - `DEL`: Apaga o último dígito inserido.
  - `CE` (Clear Entry): Limpa apenas a operação/dígito atual.
  - `C` (Clear All): Limpa todo o cálculo e reseta a calculadora.
- [x] **Cálculo de Resultado (`=`):** Processamento da conta e exibição imediata do resultado.

---

## Tecnologias Utilizadas

- **HTML5:** Estrutura da calculadora e mapeamento de botões.
- **CSS3:** Layout moderno simulando uma calculadora real.
- **JavaScript (ES6+):** Lógica da aplicação orientada a objetos (Classes, métodos e propriedades).

---

## Conceitos Praticados

- **Programação Orientada a Objetos (POO):** Criação da classe `Calculator`, encapsulamento de métodos (`addDigit`, `processOperation`, `updateScreen`, etc.) e controle de estado através do `this`.
- **Manipulação do DOM:** Seleção múltipla de botões (`querySelectorAll`), iteração com `forEach` e atualização de textos na tela (`innerText`).
- **Conversão de Tipos e Tratamento de Strings:** Uso do operador unário `+` para conversão de strings em números, métodos de array e string como `split()`, `slice()` e validações com `includes()`.
