# Conceptos Basicos de Markdown

---

### Titulos

```md
# title h1

## title h2

### title h3

#### title h4

##### title h5

###### title h6
```

---

### _Italic_

```md
Este es un texto en _italica_
```

Este es un texto en _italica_

---

### **Strong**

```md
Este es un texto en **Strong**
```

Este es un texto en **Strong**

---

### ~~Strikethroungh~~

```md
Este es un texto en ~~strikethroungh~~
La convinación de telclas para escribir la virgulilla(~) => Alt + 126
```

Este es un texto en ~~strikethroungh~~

---

### UL >> Listas Desordenadas

```md
- item 1
  - item 1.1
  - item 1.1
  - item 1.1
- item 2
  - item 1.2
  - item 1.1
- item 3
  - item 1.3
```

- item 1
  - item 1.1
  - item 1.1
  - item 1.1
- item 2
  - item 1.2
  - item 1.1
- item 3
  - item 1.3

---

### OL >> Listas Ordenadas

```
1. item 1
2. item 2
3. item 3
```

1. item 1
2. item 2
3. item 3

---

### Enlaces

```md
[YouTube](https://youtube.com)

<!-- Para cambiar el texto que sale al poner el cursor sobre el enlace -->

[YouTube](https://youtube.com "Enlace a Youtube")
```

[YouTube](https://youtube.com)

<!-- Para cambiar el texto que sale al poner el cursor sobre el enlace -->

[YouTube](https://youtube.com "Enlace a Youtube")

---

### Citas

```md
> Esta es una Cita
```

> Esta es una Cita

---

### Separadores

```md
---
---
```

---

### Código

````md
<!-- Con el acento grave es como podemos escribir código  -->

-> ``` <-

<!-- Si al final escribimos el lenguaje del código nos resaltara los colores de ese lenguaje -->

-> ```java <-

<!-- Tambien si queremos escribir solo una línea de código lo podemos hacer -->

-> `console.log("mensaje")` <-
````

```java
/*Código en Java*/
public class Persona{
    private String nombre;
    private String apellido;
}

if(1 = 1){
    System.out.println("Hola Mundo");
}
```

`console.log("mensaje")`

---

### Tablas

```
| Name      | Apellido  |
|-----------|:---------:|
| ronal     | mendoza   |
| texto     | texto     |
| texto     | texto     |
| texto     | texto     |

```

| Name  | Apellido |
| :---: | :------: |
| ronal | mendoza  |
| texto |  texto   |
| texto |  texto   |
| texto |  texto   |

---

### Imágenes

```
<!-- Remoto -->
![Visual Estudio Logo](https://cdn.worldvectorlogo.com/logos/visual-studio-code-1.svg)

<!-- Local -->
![Visual Estudio Logo](img/vscode.svg)

<!-- Al igual que los enlaces podemos mostrar un mensaje pasar el cursor sobre la imagen -->
```
![Visual Estudio Logo](img/vscode.svg)