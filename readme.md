# Atividade 01 - Dashboard de Monitoramento de Infraestrutura TI

**Disciplina:** Frameworks Front-end  
**Professor:** Prof. Me. Deivison S. Takatu  
**Instituição:** SENAI-SP  
**Aluno:** Enrico Emanuel  

---

## 📌 Descrição do Projeto
Aplicação web desenvolvida para a **Atividade 01** da disciplina de Frameworks Front-end[cite: 33]. O projeto consiste em um **Dashboard de Monitoramento de Infraestrutura de TI** em tempo real, simulação de um painel de controle de servidores, bancos de dados e serviços web[cite: 33].

A aplicação foi construída utilizando **CSS Externo** vinculado via tag `<link>`[cite: 6, 33], demonstrando a aplicação prática do **Box Model**[cite: 18, 20] e o uso de **20 propriedades de Flexbox** para garantir um layout moderno, organizado e responsivo[cite: 21, 33].

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica de 20 cards de serviços e métricas[cite: 33].
* **CSS3 (Externo):** Estilização customizada em arquivo `style.css`[cite: 6, 9], aplicando conceitos de Box Model[cite: 18, 20] e Flexbox[cite: 21].

---

## 📐 Estrutura do Box Model Aplicada
Cada um dos 20 cards aplica rigorosamente as 4 áreas do modelo de caixas (Box Model)[cite: 18, 20]:
1. **Content:** Largura (`width`), altura mínima (`min-height`) e conteúdo estruturado de cada serviço[cite: 20].
2. **Padding:** Preenchimento interno (`18px`) garantindo espaçamento entre o conteúdo e as bordas[cite: 20].
3. **Border:** Borda externa de `1px` com detalhe lateral em `5px` para indicação visual do status do serviço[cite: 20].
4. **Margin:** Espaçamento externo controlado e alinhado pelo container Flexbox[cite: 20].

---

## ⚙️ Tabela das 20 Propriedades Flexbox Utilizadas

| # | Propriedade CSS | Seletor / Alvo | Função / Descrição |
|---|---|---|---|
| 1 | `display: flex;` | `.container-flex` | Define o container principal como layout Flexbox[cite: 21, 23] |
| 2 | `flex-direction: row;` | `.container-flex` | Organiza os elementos no eixo principal em linha[cite: 21, 22] |
| 3 | `flex-wrap: wrap;` | `.container-flex` | Permite a quebra dos cards para novas linhas em telas menores[cite: 21, 22] |
| 4 | `justify-content: center;` | `.container-flex` | Centraliza os cards no eixo principal[cite: 21, 22] |
| 5 | `align-items: stretch;` | `.container-flex` | Estica os elementos para alinhamento na altura no eixo transversal[cite: 21, 30] |
| 6 | `align-content: flex-start;` | `.container-flex` | Alinha o bloco de linhas flex no topo do container[cite: 31] |
| 7 | `gap: 20px;` | `.container-flex` | Define o espaçamento uniforme entre os cards[cite: 22] |
| 8 | `row-gap: 20px;` | `.container-flex` | Define o espaçamento vertical entre as linhas flex[cite: 22] |
| 9 | `column-gap: 20px;` | `.container-flex` | Define o espaçamento horizontal entre as colunas flex[cite: 22] |
| 10 | `display: flex;` | `.card` | Transforma o interior do card em um container flexível[cite: 21] |
| 11 | `flex-direction: column;` | `.card` | Organiza o cabeçalho e as métricas do card em coluna
