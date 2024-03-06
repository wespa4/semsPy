# semsPy

## pract2
### 2.3. (уровень сложности: средний)
В следующем фрагменте по индексу i выбирается одна из трех строк. Сократите код во второй строке до 19 символов без использования функций и методов.
```
  i = 0
  ['much','code','wow'][i] # 24 символа
```
**Решение**
```
  i = 0
  print("mcwuoocdwhe"[i::3])
```
### 3.1. (уровень сложности: низкий)
Преобразовать элементы списка s из строковой в числовую форму.

**Решение**
```
  print(list(map(int, ["1", "2"])))
```
### 3.2. (уровень сложности: низкий)
Подсчитать количество различных элементов в последовательности s.

**Решение**
```
  print(len(set(["1", "2", "3", "1"])))
```
### 3.3. (уровень сложности: простейший)
Обратить последовательность s без использования функций.

**Решение**
```
  print(["1", "2", "3", "4"][::-1])
```
### 3.4. (уровень сложности: низкий)
Выдать список индексов, на которых найден элемент x в последовательности s.

**Решение**
```
  print([i for i, x in enumerate([1, 1, 2, 3]) if x == 2])
```
### 3.5. (уровень сложности: низкий)
Сложить элементы списка s с четными индексами.

**Решение**
```
  print([sum([1, 2, 3, 4, 5][i] for i in range(len([1, 2, 3, 4, 5])) if i % 2 == 0)])
```
### 3.6. (уровень сложности: низкий)
Найти строку максимальной длины в списке строк s.

**Решение**
```
  print(max(["a", "aa", "aba"]))
  print(max(["uha", "aajh", "abasjkahd"], key = len))
```
### 3.8. (уровень сложности: низкий)
Сгенерировать случайную текстовую строку с заданным максимальным размером.

**Решение**
```
  import random
  import string
  print(''.join(random.sample(string.ascii_letters + string.digits, 30)))
```
