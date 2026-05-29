# TEMA1 - Apartado 1

# Sintaxis básica de Markdown

Este documento muestra **los elementos más usados de Markdown** con una breve explicación y un ejemplo de cada uno.

---

# 1. Cabeceras

Los encabezados en Markdown se crean utilizando el símbolo #. La cantidad de símbolos # antes del texto determinará el nivel del encabezado, con # siendo el más grande (equivalente a \<h1\> en HTML) y ###### el más pequeño (equivalente a \<h6\>). Aquí tienes un ejemplo de cómo se utilizan:

```markdown
# Cabecera nivel 1
## Cabecera nivel 2
### Cabecera nivel 3
#### Cabecera nivel 4
##### Cabecera nivel 5
###### Cabecera nivel 6
Cabecera nivel 1 (Usando =)
=====
Cabecera nivel 2 (Usando -)
-----
```

!!! note "Nota sobre Cabeceras nivel 1 y 2"

    Aunque se puede usar = para Cabeceras nivel 1 y - para Cabeceras nivel 2, es mejor usar # y ## respectivamente.

**Resultado**:

# Cabecera nivel 1

## Cabecera nivel 2

### Cabecera nivel 3

#### Cabecera nivel 4

##### Cabecera nivel 5

###### Cabecera nivel 6

Cabecera nivel 1 (Usando =)
===

Cabecera nivel 2 (Usando -)
---

---

# 2. Párrafos y saltos de línea

Para crear un párrafo, simplemente escribe texto separado por una línea en blanco.  
Si quiero que haya un salto entre frases, pero sin línea en blanco , debo poner **dos espacios** al final de la primera frase.

```markdown
Este es el primer párrafo.

Este es el segundo párrafo.

Esto es el tercer párrafo.
Pero ahora no salto de línea.

Esto es el cuarto párrafo.  
Pero ahora salto de línea.
```

```text
???+ note "Pregunta"

    ¿Cuantos espacios de debo poner al final de la línea anterior si quiero que haya salto, pero sin línea en blanco?

    ??? question "Ver la respuesta"

        2 espacios
```

**Resultado**:

Este es el primer párrafo.

Este es el segundo párrafo.

Esto es el tercer párrafo.
Pero ahora no hay salto de línea.

Esto es el cuarto párrafo.  
Pero ahora salto de línea.

---

# 3. Texto en negrita, cursiva y tachado

```markdown
**Texto en negrita**
__Texto en negrita__
*Texto en cursiva*
_Texto en cursiva_  
***Texto en negrita y cursiva***
~~Texto tachado~~
```

**Resultado**:

**Texto en negrita**

__Texto en negrita__

*Texto en cursiva*

_Texto en cursiva_

***Texto en negrita y cursiva***

~~Texto tachado~~

---

# 4. Listas no ordenadas

Se crean con `-`, `*` o `+`.

```markdown
- Elemento 1
* Elemento 2
+ Elemento 3

- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        - Elemento de lista 5
        - Elemento de lista 6
```

**Resultado**:

- Elemento 1
* Elemento 2
+ Elemento 3

**Resultado listas anidadas**:

- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        - Elemento de lista 5
        - Elemento de lista 6

---

# 5. Listas ordenadas

Se crean con números seguidos de punto.

```markdown
1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
```

**Resultado**:

1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
---

# 6. Listas anidadas

Permiten crear subniveles.

```markdown
- Lenguaje
  - Java
  - Python
  - C#
```

**Resultado**:

* Lenguajes

  * Java
  * Python
  * C#

---
