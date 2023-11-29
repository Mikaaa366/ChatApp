## ChatApp
Projekt ChatApp to aplikacja służąca do szybkiej wymiany wiadomości w czasie rzeczywistym, oparta na technologii WebSocket. Jest to doskonały sposób na praktyczne zastosowanie WebSocketów, pozwalających na dwukierunkową, niezawodną i wydajną komunikację pomiędzy klientem a serwerem.

## Cel Projektu
Stworzenie prostego, ale funkcjonalnego czatu, który umożliwi użytkownikom wymianę wiadomości w czasie rzeczywistym.

## Funkcjonalności

**Klient**
1. **Podanie Nazwy Użytkownika:** Aplikacja na początku prosi o wpisanie nazwy użytkownika.
2. **Interfejs Czatu:** Po wpisaniu nazwy użytkownika, formularz znika, a na jego miejscu pojawia się interfejs czatu z listą wiadomości.
3. **Formularz Wysyłania Wiadomości:** Obok listy wiadomości znajduje się formularz z polem tekstowym i przyciskiem "Send" do wysyłania nowych wiadomości.

**Serwer**
1. **Przechowywanie Wiadomości:** Serwer przechowuje tablicę wiadomości.
2. **Zwracanie Aplikacji Klienta:** Pod adresem głównym (/) serwer zwraca aplikację klienta czatu.
3. **Aktualizacja Wiadomości:** Serwer aktualizuje tablicę wiadomości i informuje wszystkich użytkowników o nowych wiadomościach.

## Technologie 
- **WebSocket:** Do dwukierunkowej komunikacji w czasie rzeczywistym.
- **HTML/CSS/JavaScript:** Do stworzenia interfejsu użytkownika.
- **Node.js:** Serwer backendowy.

## Galeria: 
<img src="https://i.ibb.co/8D3Dy5D/1.png">
<img src="https://i.ibb.co/qJ8gkwx/2.png">
<img src="https://i.ibb.co/XksbmFY/3.png">
