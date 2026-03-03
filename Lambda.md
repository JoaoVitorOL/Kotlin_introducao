# 👅 Funções Lambda na Programação


## 1. O que são funções Lambda

Funções **lambda** são funções **anônimas**, ou seja, não possuem um nome explícito e normalmente são definidas **no local onde são usadas**.

Características principais:
- Não possuem nome.
- Geralmente são curtas (Uma linha).
- Expressam uma única operação ou expressão.
- Podem ser atribuídas a variáveis, passadas como parâmetro ou usadas imediatamente.

Forma conceitual: <br>
entrada(s) → expressão → saída <br>

---

## 2. Por que funções Lambda existem
Funções lambda surgiram para **resolver problemas específicos** de clareza, concisão e expressividade do código. <br>
Motivações principais: <br>

* Evitar a criação de funções auxiliares triviais.
* Tornar operações simples mais legíveis.
* Facilitar programação funcional (map, filter, reduce).
* Permitir passar comportamento como dado.
* 
Em outras palavras:
> quando o comportamento é pequeno e local, a lambda evita burocracia.

---

## 3. ✔️ Quando funções Lambda são usadas
Funções lambda são usadas quando:

* A função é curta
* tem lógica simples
* não será reutilizada em vários pontos
* O foco é o que fazer, não como a função se chama
* A função é passada como argumento

Casos típicos:
* Iterações sobre coleções
*  Filtros
* Transformações de dados
* Callbacks
* Comparadores
* Eventos

---

## ❎  4. Quando NÃO usar funções Lambda

Funções lambda  **não são** ideais quando:
* A lógica é complexa.
* Há múltiplas etapas internas.
* É necessário reaproveitamento.
* É importante nomear a intenção da regra.
* Há necessidade de testes unitários isolados.

 > Se você precisa comentar uma lambda para explicá-la, ela já deveria ser uma função normal.
