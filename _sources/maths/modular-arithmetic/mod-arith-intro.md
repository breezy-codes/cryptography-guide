# Modular Arithmetic

Welcome to the Modular Arithmetic section! Here, you will find detailed explanations and examples on various topics related to modular arithmetic, including modular addition, modular subtraction, modular multiplication, modular inverse, and modular exponentiation.

Access the handy maths symbol cheat sheet to help with covering these topics here: [Cheat Sheet](../cheat-sheet.md)

## Introduction to Modular Arithmetic

Modular arithmetic, sometimes referred to as "clock arithmetic," deals with integers and a specific number, the modulus, and involves performing operations and finding remainders when numbers are divided by the modulus.

### For Example:

- The expression $7 \mod 3$ evaluates to $1$ because when $7$ is divided by $3$, the remainder is $1$.
- The expression $10 \mod 4$ evaluates to $2$ because when $10$ is divided by $4$, the remainder is $2$.

### Properties of Modular Arithmetic

- **Modular addition:** $(a + b) \mod n = ((a \mod n) + (b \mod n)) \mod n$
- **Modular subtraction:** $(a - b) \mod n = ((a \mod n) - (b \mod n)) \mod n$
- **Modular multiplication:** $(a \times b) \mod n = ((a \mod n) \times (b \mod n)) \mod n$
- **Modular exponentiation:** $(a^b) \mod n = ((a \mod n)^b) \mod n$
- **Modular inverse:** Defined as $a \times b^{-1} \mod n$, where $b^{-1}$ is the modular multiplicative inverse of $b$ under modulus $n$.

## Topics Covered

1. **[Modular Addition:](modular-addition.ipynb)** Examples of performing addition under a modulus.
2. **[Modular Subtraction:](modular-subtraction.ipynb)** Examples of performing subtraction under a modulus.
3. **[Modular Multiplication:](modular-multiplication.ipynb)** Examples of performing multiplication under a modulus.
4. **[Modular Exponentiation:](modular-exponentiation.ipynb)** Examples of raising numbers to a power under a modulus.
5. **[Modular Inverse:](modular-inverse.ipynb)** Examples of finding the modular multiplicative inverse of a number.

## Why Study Modular Arithmetic?

Modular arithmetic is fundamental in various fields, including computer science, cryptography, and number theory. It is essential for understanding algorithms, encryption methods, and solving problems involving cyclic structures. Its also a very interesting topic to study!

```{admonition} Interesting Fact
:class: tip, dropdown

Did you know? Modular arithmetic has a rich history dating back to ancient China, where it was used in the Chinese Remainder Theorem. This theorem, first recorded by the mathematician Sunzi in the 3rd century AD, provides a way to solve systems of simultaneous congruences with different moduli. It laid the foundation for many modern applications in cryptography and computer science, illustrating the timeless relevance of modular arithmetic in solving complex problems.

```

```{tableofcontents}
```

