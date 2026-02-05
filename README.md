
````markdown
## STRING

### 1. Quyidagi kod natijasi nima?
```python
s = "Python"
print(s[-1])
````

A) P
B) n
C) o
D) Xato

---

### 2. `len("Salom")` natijasi?

A) 4
B) 5
C) 6
D) Xato

---

### 3. Qaysi metod stringni bo‘laklaydi?

A) split()
B) join()
C) replace()
D) strip()

---

### 4. Quyidagi kod natijasi?

```python
print("abc".replace("a", "z"))
```

A) abc
B) zbc
C) abz
D) Xato

---

### 5. Stringlar Python’da:

A) O‘zgaruvchan
B) O‘zgarmas
C) Indekssiz
D) Tartibsiz

---

## LIST

6. Quyidagi kod natijasi?

```python
lst = [1, 2, 3]
lst.insert(1, 9)
print(lst)
```

A) [1, 2, 9, 3]
B) [1, 9, 2, 3]
C) [9, 1, 2, 3]
D) Xato

7. `pop()` metodi nima qiladi?
   A) Qo‘shadi
   B) O‘chiradi va qaytaradi
   C) Faqat o‘chiradi
   D) Nusxa oladi

8. Quyidagi kod natijasi?

```python
a = [1, 2, 3]
b = a
b.append(4)
print(a)
```

A) [1,2,3]
B) [4]
C) [1,2,3,4]
D) Xato

9. List slicing natijasi?

```python
lst = [0,1,2,3,4]
print(lst[1:4])
```

A) [1,2,3]
B) [1,2,3,4]
C) [0,1,2]
D) [2,3,4]

10. Qaysi biri list metod EMAS?
    A) append
    B) add
    C) remove
    D) clear

---

## TUPLE

11. Tuple qanday yaratiladi?
    A) {}
    B) []
    C) ()
    D) <>

12. Quyidagi kod natijasi?

```python
t = (1, 2, 3)
print(t[1])
```

A) 1
B) 2
C) 3
D) Xato

13. Tuple xususiyati:
    A) O‘zgaruvchan
    B) O‘zgarmas
    C) Kalitli
    D) Tartibsiz

14. Quyidagi kod natijasi?

```python
t = (1)
print(type(t))
```

A) tuple
B) int
C) list
D) set

15. Tuple unpacking natijasi?

```python
a, b = (5, 10)
print(a)
```

A) 10
B) 5
C) (5,10)
D) Xato

---

## SET

16. Set qanday xususiyatga ega?
    A) Tartibli
    B) Takrorlanuvchi
    C) Takrorlanmas
    D) Indeksli

17. Quyidagi kod natijasi?

```python
s = {1, 2, 2, 3}
print(s)
```

A) {1,2,2,3}
B) {1,2,3}
C) [1,2,3]
D) Xato

18. `add()` qayerda ishlatiladi?
    A) list
    B) tuple
    C) set
    D) string

19. Setda indeks mavjudmi?
    A) Ha
    B) Yo‘q
    C) Ba’zan
    D) Faqat for bilan

20. Quyidagi kod natijasi?

```python
s = set()
s.add(5)
print(len(s))
```

A) 0
B) 1
C) 5
D) Xato

---

## DICTIONARY

21. Dictionary qanday tuzilma?
    A) Tartibli
    B) Indeksli
    C) Kalit-qiymatli
    D) Takrorlanuvchi

22. Quyidagi kod natijasi?

```python
d = {"a":1, "b":2}
print(d.get("c", 0))
```

A) None
B) Xato
C) 0
D) c

23. Dictionary kaliti bo‘la olmaydi:
    A) int
    B) str
    C) tuple
    D) list

24. `keys()` nima qaytaradi?
    A) Qiymatlar
    B) Kalitlar
    C) Juftliklar
    D) List

25. Quyidagi kod natijasi?

```python
d = {"x":1}
d["x"] = 5
print(d)
```

A) {"x":1}
B) {"x":5}
C) Xato
D) 5

---

## MATCH / CASE

26. `match` qachon ishlaydi?
    A) Python 3.7
    B) Python 3.8
    C) Python 3.9
    D) Python 3.10

27. Quyidagi kod natijasi?

```python
x = 3
match x:
    case 1:
        print("A")
    case 3:
        print("B")
```

A) A
B) B
C) Hech narsa
D) Xato

28. `case _:` nimani bildiradi?
    A) Xato
    B) O‘zgaruvchi
    C) Default
    D) Sikl

29. Quyidagi kod natijasi?

```python
x = 4
match x:
    case 1 | 3 | 5:
        print("Toq")
    case _:
        print("Juft")
```

A) Toq
B) Juft
C) 4
D) Xato

30. `match` nimaga o‘xshash?
    A) for
    B) while
    C) if/elif
    D) try

---

## TRY / EXCEPT

31. `try/except` nima uchun?
    A) Takrorlash
    B) Xatoni ushlash
    C) Funksiya
    D) Shart

32. Quyidagi kod natijasi?

```python
try:
    print(5 / 0)
except ZeroDivisionError:
    print("Xato")
```

A) 0
B) Infinity
C) Xato
D) Dastur to‘xtaydi

33. Qaysi xato `ValueError`?
    A) 10 / 0
    B) int("a")
    C) x + y
    D) index

34. `finally` qachon ishlaydi?
    A) Xato bo‘lsa
    B) Xato bo‘lmasa
    C) Har doim
    D) Hech qachon

35. Quyidagi kod natijasi?

```python
try:
    print("OK")
except:
    print("Xato")
```

A) OK
B) Xato
C) Hech narsa
D) Xato beradi

---


36. Quyidagi kod natijasi nima?
```python
s = "abcdef"
print(s[1:5:2])
````

A) bd
B) bdf
C) ace
D) bcde

37. Quyidagi kod natijasi?

```python
lst = [1, 2, 3, 4]
print(lst[::-1])
```

A) [1,2,3,4]
B) [4,3,2,1]
C) [2,3]
D) Xato

38. Qaysi biri **mutable**?
    A) string
    B) tuple
    C) list
    D) int

39. Quyidagi kod natijasi?

```python
a = [1, 2]
b = a.copy()
b.append(3)
print(a)
```

A) [1,2,3]
B) [3]
C) [1,2]
D) Xato

40. `clear()` metodi nima qiladi?
    A) Nusxa oladi
    B) O‘chiradi
    C) Tozalaydi
    D) Qo‘shadi

---

41. Quyidagi kod natijasi?

```python
t = (1, 2, 3)
print(len(t))
```

A) 2
B) 3
C) 1
D) Xato

42. Tuple ichida list bo‘lishi mumkinmi?
    A) Yo‘q
    B) Ha
    C) Faqat bo‘sh
    D) Faqat set

43. Quyidagi kod natijasi?

```python
t = (1, [2, 3])
t[1].append(4)
print(t)
```

A) Xato
B) (1, [2,3])
C) (1, [2,3,4])
D) [2,3,4]

44. Setdan element o‘chirish metodi?
    A) pop
    B) remove
    C) discard
    D) B va C

45. Quyidagi kod natijasi?

```python
s = {1, 2, 3}
s.remove(2)
print(s)
```

A) {1,2,3}
B) {1,3}
C) {2}
D) Xato

---

46. Dictionary uzunligini aniqlash?
    A) size()
    B) length()
    C) len()
    D) count()

47. Quyidagi kod natijasi?

```python
d = {"a":1, "b":2}
print("a" in d)
```

A) False
B) True
C) 1
D) Xato

48. `items()` nima qaytaradi?
    A) Kalitlar
    B) Qiymatlar
    C) Juftliklar
    D) List

49. Quyidagi kod natijasi?

```python
d = {"x":1}
d.update({"y":2})
print(d)
```

A) {"x":1}
B) {"y":2}
C) {"x":1,"y":2}
D) Xato

50. Dictionary tartibliligi (Python 3.7+):
    A) Tartibsiz
    B) Tartibli
    C) Set kabi
    D) Tuple kabi

---

51. Quyidagi kod natijasi?

```python
x = "hi"
match x:
    case "hi":
        print(1)
    case _:
        print(0)
```

A) 0
B) hi
C) 1
D) Xato

52. `case 1 | 2 | 3:` nimani bildiradi?
    A) Va
    B) Yoki
    C) Teng
    D) Xato

53. Quyidagi kod natijasi?

```python
x = 10
match x:
    case _ if x > 5:
        print("Katta")
    case _:
        print("Kichik")
```

A) Kichik
B) Katta
C) 10
D) Xato

54. `match` ichida `if` nima deyiladi?
    A) Guard
    B) Loop
    C) Exception
    D) Block

55. `match` qaysi tur bilan ishlaydi?
    A) Faqat int
    B) Faqat str
    C) Ko‘p turlar
    D) Faqat list

---

56. Quyidagi kod natijasi?

```python
try:
    x = int("5")
    print(x)
except:
    print("Xato")
```

A) Xato
B) 0
C) 5
D) int

57. Qaysi xato `IndexError`?
    A) lst[10]
    B) 10 / 0
    C) int("a")
    D) x

58. Quyidagi kod natijasi?

```python
try:
    print(1)
finally:
    print(2)
```

A) 1
B) 2
C) 1 2
D) Xato

59. `except Exception as e:` nimani anglatadi?
    A) Xatoni yashiradi
    B) Xatoni saqlaydi
    C) Xatoni chiqaradi
    D) Xatoni o‘chiradi

60. Quyidagi kod natijasi?

```python
try:
    a = 5 / 1
except:
    print("Xato")
else:
    print("OK")
```

A) Xato
B) OK
C) 5
D) Hech narsa

---

61. List comprehension natijasi?

```python
[x*2 for x in [1,2,3]]
```

A) [1,2,3]
B) [2,4,6]
C) [1,4,9]
D) Xato

62. Quyidagi kod natijasi?

```python
len({1,2,3,3,2})
```

A) 5
B) 4
C) 3
D) Xato

63. Qaysi biri xato?
    A) {}
    B) []
    C) ()
    D) set()

64. Bo‘sh dictionary qaysi?
    A) []
    B) ()
    C) {}
    D) set()

65. Quyidagi kod natijasi?

```python
bool([])
```

A) True
B) False
C) []
D) Xato

---

66. Quyidagi kod natijasi?

```python
print(type({}))
```

A) set
B) dict
C) list
D) tuple

67. Set bilan list farqi:
    A) Indeks
    B) Tartib
    C) Takrorlanish
    D) Tezlik

68. Quyidagi kod natijasi?

```python
s = {1,2}
s.add(2)
print(len(s))
```

A) 1
B) 2
C) 3
D) Xato

69. Tuple slicing natijasi?

```python
t = (0,1,2,3)
print(t[1:])
```

A) (0,1)
B) (1,2,3)
C) (0,1,2)
D) Xato

70. Dictionarydan element olish usuli:
    A) []
    B) get()
    C) items()
    D) A va B

---

71. Quyidagi kod natijasi?

```python
x = [1,2]
print(x * 2)
```

A) [1,2,1,2]
B) [2,4]
C) Xato
D) 4

72. `join()` qayerda ishlaydi?
    A) list
    B) string
    C) tuple
    D) set

73. Quyidagi kod natijasi?

```python
"-".join(["a","b","c"])
```

A) abc
B) a-b-c
C) a,b,c
D) Xato

74. `strip()` nima qiladi?
    A) Bo‘laklaydi
    B) Tozalaydi
    C) Qo‘shadi
    D) O‘chiradi

75. Quyidagi kod natijasi?

```python
"  hi  ".strip()
```

A) "hi"
B) "  hi"
C) "hi  "
D) Xato

---

76. Quyidagi kod natijasi?

```python
d = dict(a=1, b=2)
print(d)
```

A) Xato
B) {"a":1,"b":2}
C) [a,b]
D) (1,2)

77. `pop()` dictionaryda nima qiladi?
    A) Hammasini o‘chiradi
    B) Qiymat qo‘shadi
    C) Kalitni o‘chirib qaytaradi
    D) Nusxa oladi

78. Quyidagi kod natijasi?

```python
d = {"a":1}
print(d.pop("a"))
```

A) a
B) 1
C) {"a":1}
D) Xato

79. Set union operatori?
    A) &
    B) -
    C) |
    D) ^

80. Quyidagi kod natijasi?

```python
{1,2} | {2,3}
```

A) {1,2,3}
B) {2}
C) {1,3}
D) Xato

---

81. Listni tuplega aylantirish?
    A) tuple(list)
    B) list(tuple)
    C) set(list)
    D) dict(list)

82. Quyidagi kod natijasi?

```python
tuple([1,2,3])
```

A) [1,2,3]
B) (1,2,3)
C) {1,2,3}
D) Xato

83. Qaysi biri **immutable**?
    A) list
    B) set
    C) dict
    D) tuple

84. Quyidagi kod natijasi?

```python
print("abc" * 3)
```

A) abcabcabc
B) abc*3
C) Xato
D) abc abc abc

85. `count()` qayerda ishlaydi?
    A) string
    B) list
    C) tuple
    D) Barchasi

---

86. Quyidagi kod natijasi?

```python
[1,2,3].count(2)
```

A) 0
B) 1
C) 2
D) Xato

87. `index()` nima qaytaradi?
    A) Qiymat
    B) Indeks
    C) True/False
    D) List

88. Quyidagi kod natijasi?

```python
"hello".find("e")
```

A) 0
B) 1
C) -1
D) Xato

89. `find()` topilmasa nima qaytaradi?
    A) None
    B) False
    C) -1
    D) Xato

90. `index()` topilmasa?
    A) -1
    B) None
    C) Xato
    D) 0

---

91. Quyidagi kod natijasi?

```python
bool({})
```

A) True
B) False
C) {}
D) Xato

92. `len("")` natijasi?
    A) 1
    B) -1
    C) 0
    D) Xato

93. Quyidagi kod natijasi?

```python
set("aba")
```

A) {"a","b"}
B) ["a","b","a"]
C) ("a","b")
D) Xato

94. Dictionary qiymatlari qanday bo‘lishi mumkin?
    A) Faqat int
    B) Faqat str
    C) Har qanday
    D) Faqat list

95. Quyidagi kod natijasi?

```python
{"a":1}.values()
```

A) ["a"]
B) [1]
C) dict_values([1])
D) Xato

---

96. `try` ichida xato bo‘lmasa `except`?
    A) Ishlaydi
    B) Ishlamaydi
    C) Ba’zan
    D) Xato

97. Bir nechta `except` bo‘lishi mumkinmi?
    A) Yo‘q
    B) Ha
    C) Faqat 2 ta
    D) Faqat 1 ta

98. Quyidagi kod natijasi?

```python
try:
    x = 1
except:
    x = 2
print(x)
```

A) 2
B) 1
C) Xato
D) None

99. `raise` nima qiladi?
    A) Xatoni yashiradi
    B) Xatoni chiqaradi
    C) Xatoni o‘chiradi
    D) Dastur yopadi

100. Quyidagi kod natijasi?

```python
try:
    raise ValueError
except ValueError:
    print("Xato")
```

A) ValueError
B) Hech narsa
C) Xato
D) Dastur to‘xtaydi

```


