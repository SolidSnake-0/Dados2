# Juego de Dados - Modelado y Solución

## Problema

Se desea modelar un juego de dados utilizando los principios de programación orientada a objetos. El juego debe cumplir con las siguientes características y reglas:

1. **Dado:** 
   - Un dado tiene una característica principal: la cara superior que queda visible después de lanzarlo.
   - Cada lanzamiento debe simular un número aleatorio entre 1 y 6.

2. **Juego de Dados:**
   - El juego utiliza **dos dados**.
   - Ambos dados se lanzan y se calcula la **suma de las caras superiores**.
   - Reglas del juego:
     - Si la suma de las caras superiores es **7**, ganas.
     - Si no, pierdes.

3. **Restricciones:**
   - Un dado **no debe saber cómo se suman valores**. Para ello, se requiere una clase separada (`Calculadora`) que se encargue de realizar las operaciones matemáticas.

4. **Objetivo Final:**
   - Implementar una solución que modele este juego, utilizando relaciones entre clases (`Dado`, `Calculadora` y `JuegoDeDados`).

---

## Solución Propuesta

### Clases Identificadas
1. **Dado:** Representa el objeto "dado" y permite simular su lanzamiento.
2. **Calculadora:** Provee métodos para realizar operaciones matemáticas básicas, como sumar dos números.
3. **JuegoDeDados:** Coordina los lanzamientos de los dados y calcula el resultado según las reglas del juego.


