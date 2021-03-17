Pomysł na budzik
================

### Zadania
1. Pobrać czas ze strony
2. Pobrać czas użytkownika przez port szeregowy
3. Sprawdzić czy czas użytkownika jest większy niż aktualny czas
4. obliczyć różnice w sekundach
5. przesłać dane na wyświetlacz
6. odliczać sekunda po sekundzie póki nie jest równa 0
7. włączyć sygnał dźwiękowy na kilka sekund
8. wyświetlić informacje o możliwości ponownego ustawienia budzika

Demo
----

### Funkcje

> ## setup
> 
> załącz port szeregowy Serial
> 
> poczekaj na wiadomość od użytkownika w formacie `T(czas w sekundach, system unix)`
> 
> wyświetl komunikat o możliwości podaniu czasu budzika
> 
> Zbierz informacje w formacie 'Y-m-d H:i:s'
> 
> Oblicz różnice
> 
> ustaw piny na przycisk, buzzer
> 
> zainicjalizuj wyświetlacz
> 

> ## loop
> 
> odliczanie różnicy póki jest większa od 0
> 
> odpalenie sygnału
> 

### Przydatne linki
+ [Podłączenie buzzera](https://www.youtube.com/watch?v=ZLonUt1S7qM)
+ [TimeLib](https://github.com/PaulStoffregen/Time)
+ [LiquidCrystal_I2C](https://github.com/johnrickman/LiquidCrystal_I2C)
+ [Unix time](https://www.unixtimestamp.com/index.php)



