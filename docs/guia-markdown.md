# Guía Básica de Markdown.md

Esta guía te ayudará a comprender los elementos básicos para escribir en **Markdown**.

---

## Títulos

Usa el símbolo `#` para crear títulos:

```markdown
# Título 1
## Título 2
### Título 3
```

Resultado:

# Título 1
## Título 2
### Título 3

---

## Listas

### Listas con viñetas

```markdown
- Elemento 1
- Elemento 2
  - Sub-elemento
- Elemento 3
```

- Elemento 1
- Elemento 2
  - Sub-elemento
- Elemento 3

### Listas numeradas

```markdown
1. Primer paso
2. Segundo paso
3. Tercer paso
```

1. Primer paso
2. Segundo paso
3. Tercer paso

---

## Enlaces e Imágenes

### Enlace

```markdown
[Ir a GitHub](https://github.com)
```

[Ir a GitHub](https://github.com)

### Imagen

```markdown
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)

---

## Tablas

```markdown
| Nombre  | Rol       | GitHub        |
|---------|-----------|---------------|
| Camilo  | Desarrollador | @JBHanck |
| Daniela | Tester    | @Danielaparra121 |
| Jader   | Líder     | @Jader Suárez     |
```

| Nombre  | Rol            | GitHub   |
|---------|----------------|----------|
| Camilo  | Desarrollador | @JBHanck  |
| Ivanna  | Tester         | @ivanna008 |
|  Jader  | Líder          | @Jader Suárez|

---

## Bloques de código

```markdown
```python
def saludar(nombre):
    print(f"Hola, {nombre}!")
```
```

Resultado:

```python
def saludar(nombre):
    print(f"Hola, {nombre}!")
```

