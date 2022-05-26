# Projekt zaliczeniowy WSB

Projekt zaliczeniowy - studia podyplomowe, kierunek "Tester Oprogramowania".

Testy napisane z użyciem RobotFramework oraz dedykowanej biblioteki Selenium. Projekt napisany dla serwisu e-commerce - automationpractice.com

# Wersja oprogramowania
```Chrome - Version  01.0.4951.67```

```Selenium - Version 4.1.5```

```Python - Version 3.8.10```

```Robotframework - Version 5.0.1```

```Robotframework-seleniumlibrary - Version 6.0.0```

# Instalacja i uruchomienie

Aby skonfigurować wirtualne środowisko należy użyć komend:

```sudo apt install git```

```sudo apt install python3```

```sudo apt install python3.8-venv```

```git init```

```git pull https://github.com/flopawc/Projekt```

```python3 -m venv env```

```source env/bin/activate```

```pip install -r requirements```

```robot robotWSB```

Pierwsze komendy oodpowiadają za instalację git i python, prawdopodobnie zbędne.

aby wyłączyć srodowisko wirtualne:

```source env/bin/deactivate```


Do poprawnego działania testu konieczna jest instalacja chromedriver/geckodriver w razie potrzeby podanie ścieżki do sterownika.
 
