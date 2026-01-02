## 1. FUNDAMENTY I SKŁADNIA
* **Typy danych:** `int`, `float`, `str`, `bool`, `None`, rzutowanie (`type casting`).
* **Operatory:** Arytmetyczne (`//`, `%`, `**`), logiczne (`and`, `or`, `not`, *short-circuit*), porównania.
* **Semantyka zmiennych:** Obiekty mutowalne vs niemutowalne, referencje, pułapki aliasowania.
* **Stringi:** *Slicing*, metody (`strip`, `split`, `replace`, `casefold`), *f-strings*.

## 2. STRUKTURY DANYCH
* **Listy i Krotki:** Indeksowanie, *slicing*, metody (`append`, `extend`, `pop`), rozpakowywanie (*unpacking*).
* **Słowniki:** Operacje na kluczach, metody `get`, `setdefault`, `popitem`, liczniki częstotliwości.
* **Zbiory (Sets):** Operacje teoriomnogościowe, hashowalność.
* **Comprehensions:** List/dict/set comprehensions, wyrażenia generatorowe.

## 3. STEROWANIE PRZEPŁYWEM
* **Warunki:** `if/elif/else`, operator trójargumentowy.
* **Pętle:** `for`, `while`, `break`, `continue`, `pass`, klauzula `else`.
* **Iteratory:** `range`, `enumerate`, `zip`, obsługa `iter`/`next`.

## 4. PROGRAMOWANIE FUNKCYJNE
* **Definicje:** Argumenty pozycyjne/nazwane/domyślne, wymuszanie typów (`/`, `*`).
* **Zasięg:** LEGB, `global`, `nonlocal`.
* **Funkcje wyższego rzędu:** `lambda`, `map`, `filter`, `sorted`.
* **Zaawansowane:** `functools.partial`, domknięcia (*closures*), fabryki funkcji.
* **Type Hinting:** Adnotacje typów.

## 5. PROGRAMOWANIE OBIEKTOWE (OOP)
* **Klasy:** Konstruktor `__init__`, atrybuty instancji/klasowe.
* **Metody:** Instancyjne, klasowe (`@classmethod`), statyczne (`@staticmethod`).
* **Enkapsulacja:** `@property`, settery/gettery, zmienne prywatne (`_var`).
* **Dziedziczenie:** Klasy abstrakcyjne (`ABC`), wielokrotne dziedziczenie, `super()`, MRO.
* **Kompozycja:** Budowanie obiektów z obiektów.
* **Magic Methods:** `__str__`, `__repr__`, `__eq__`.
* **Dataclasses:** Użycie `@dataclass`.

## 6. I/O ORAZ OBSŁUGA PLIKÓW
* **Biblioteki:** `pathlib.Path`, `open()`.
* **Context Managers:** `with`.
* **Formaty:** JSON (`load/dump`).

## 7. OBSŁUGA BŁĘDÓW I JAKOŚĆ KODU
* **Wyjątki:** `try/except/else/finally`, `raise`, własne wyjątki.
* **Paradygmaty:** EAFP vs LBYL.
* **Walidacja:** `assert`, `isinstance`, kontrakty funkcji.

## WERDYKT
Solidne fundamenty backendowe. Zrozumienie mechanizmów wewnętrznych (iteratory, MRO) i nowoczesnych idiomów. Rekomendowane kolejne kroki: asynchroniczność, `pytest`, frameworki.
