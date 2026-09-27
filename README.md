# 🔢 Conjectura de Collatz

Programa em **C** que calcula a sequência da Conjectura de Collatz para um número inteiro positivo informado pelo usuário.

---

## 📖 Sobre

A Conjectura de Collatz afirma que, partindo de qualquer número natural `n`, aplicando repetidamente as regras abaixo, sempre se chega ao número 1:

- Se `n` for **par** → `n = n / 2`
- Se `n` for **ímpar** → `n = 3n + 1`

O programa lê um número do usuário e imprime toda a sequência gerada até chegar em 1.

---

## 📂 Estrutura do Projeto

```
📦 collatz
 ┣ 📄 index.c
 ┗ 📄 README.md
```

| Arquivo | Função |
|---|---|
| `index.c` | Código-fonte principal do programa |
| `README.md` | Documentação do projeto |

---

## ▶️ Como executar

### 1. Compilar

```
gcc -o collatz index.c
```

### 2. Executar

```
./collatz
```

### 3. Exemplo de uso

```
Digite um numero maior que 1: 6
6 -> 3 -> 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1
```

---

## 🎯 Objetivo

Praticar estruturas de repetição (`while`), condicionais (`if/else`) e entrada/saída em C, aplicando um problema matemático clássico.

---

⭐ Sinta-se à vontade para testar com outros números!
