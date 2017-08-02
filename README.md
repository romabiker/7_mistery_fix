# Решатель квадратных уравнений

Решает квадратные уравнения  a\*x\*\*2 + b\*x + c = 0

# Как использовать

Предназначен для использования в командной консоли.

a\*x\*\*2 + b\*x + c = 0
```python
>>> roots = get_roots(a, b, c)
>>> print(roots)
(root1, root2)
```

Example
```python
$  python3
>>> from quadratic_equation import get_roots
>>> roots = get_roots(1, 2, 3)
>>> print(roots)
(None, None)
>>> roots = get_roots(2, -2, -1)
>>> print(roots)
(-0.3660254037844386, 1.3660254037844386)
```


# Как запустить

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
