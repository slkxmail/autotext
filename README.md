# Либа для автоматической генерации текста

Генерирует текст по заданному шаблону с переборами и перестановками.

## Правила генерации

### Выбрать один из перечисления (Xor)

```

Привет {дорогой|дорогая}

```

Выдаст два варианта:

**I вариант**

```

Привет дорогой

```

**II вариант**

```

Привет дорогая

```

### Перестановка вариантов (Or)

```

Привет [дорогой|дорогая]

```

Выдаст два варианта:

**I вариант**

```

Привет дорогой, дорогая

```

**II вариант**

```

Привет дорогая, дорогой

```
