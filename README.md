# Решатель квадратных уравнений

Скрипт для поиска корней квадратного уравнения (`quadratic_equation.py`), а так же unittest для проверки (`test.py`).

# Как использовать

Для использования функции необходимо импортировать модуль `quadratic_equation.py`:

```python
from quadratic_equation import get_roots
```
Далее в своём приложении можно использовать функцию get_roots(a, b, c), где a, b, c - коэффициенты квадратного уравнения (ax^2 + bx + c).

## Пример:

```python
print(get_roots(1, -3, 2))
(1.0, 2.0)
```

При запуске модуля `tests.py` происходит проверка. Успешный запуск unittest возвращает:

```bash
....
----------------------------------------------------------------------
Ran 4 tests in 0.042s

OK
```

# Как запустить проверку

Скрипт требует для своей работы установленного интерпретатора Python версии 3.5

Запуск на Linux:

```bash
python tests.py # может понадобиться вызов python3 вместо python, зависит от настроек операционной системы
```

Запуск на Windows происходит аналогично.

# Цели проекта

Код создан в учебных целях. В рамках учебного курса по веб-разработке ― [DEVMAN.org](https://devman.org)
