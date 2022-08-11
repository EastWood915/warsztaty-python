# Materiały z zajęć

## Czwartek

### pierwszy.py
```python
print("Hello world!")

zmienna = 17

print(zmienna)

zmienna = 21
print(zmienna)
zmienna = zmienna + 4
print(zmienna)
```

### drugi.py
```python
liczba = 0
liczba = input("Podaj liczbę:") # Instrukcja input() zwraca tekst, a nie liczbę!
liczba = int(liczba) # Zamiana tekstu na liczbę
liczba = liczba*2
print(liczba)


# + - * / %
```

### instrukcje_warunkowe.py
```python
wiek = 0
wiek = input("Ile masz lat? ")
wiek = int(wiek)

if wiek >= 18:
    print("Możesz napić się piwka")
else:
    print("Nie możesz napić się piwka")
```

### listy.py
```python
lista = [3, 6, 9, 10]
print(lista[0]) # 3
print(lista[2]) # 9
print(lista) # [3, 6, 9, 10]

print(lista[1:]) # [6, 9, 10]
print(lista[1:3]) # [6, 9]
print(lista[:2]) # [3, 6]


lista.append(13) # [3, 6, 9, 10, 13]
print(lista)
```

### zadanie1.py
```python
# Stwórz zmienną o nazwie "postac" i wartości 0. 
# Zmienna ta określa pozycję postaci na mapie (w metrach od środka mapy).
postac = 0

# Poproś gracza o określenie, w którą stronę ma iść postać.
# Jeśli wpisze "w" - przesuń postać o 100m do przodu.
# Jeśli wpisze "s" - przesuń postać o 100m do tyłu.
klawisz = input("Podaj kierunek")
if klawisz == "w":
    postac = postac + 100
elif klawisz == "s":
    postac = postac - 100

# Wyświetl na ekranie aktualną pozycję postaci.
print(postac)
```
