## MÁV utastájékoztató

Ez a projekt egy egyszerű webes felület, a MÁV Utastájékoztató másolata. A weboldal **HTML** és **CSS** segítségével készült, és egy táblázatos formátumban jeleníti meg az aktuális menetrendet.

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTENgTB9awH7gVkBdPfobi765VMPjRs7Xofmg&s)

### 📌 Funkciók (Nem valós idejű)
- 🚉 Induló és érkező vonatok listázása táblázatban
- ⏰ Állomás, indulási és érkezési idők megjelenítése
- 🎨 Felhasználóbarát, letisztult dizájn

### 🚀 Használat
Egyszerűen nyisd meg a `https://milan0419.github.io/2025_01_30_MAV_utastajekoztato/` weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.
#### 🌍 Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[🔗 MÁV Utastájékoztató](https://milan0419.github.io/2025_01_30_MAV_utastajekoztato/)

### 🏗️ Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>MÁV Utastájékoztató</h1>
    <table>
        <tr>
            <th>Vonatszám</th>
            <th>Indulás</th>
            <th>Érkezés</th>
            <th>Állomás</th>
        </tr>
        <tr>
            <td>1234</td>
            <td>12:30</td>
            <td>14:00</td>
            <td>Budapest</td>
        </tr>
    </table>
</body>
</html>
```

## 🎨 CSS Stílusok
```css
body{
    background-color: gray;
    background-image: url("image.png");
    background-repeat: no-repeat;
    background-size: 100%;
}

table {
    background-color: green;
    color: white;
    font-family:'Gill Sans MT';
    font-size: 25px;
    width: 70%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 7%;
    margin-bottom: auto;
    border-collapse: collapse;
    padding: 0%;
    box-shadow: 10px 10px 10px black;
}
```

### 🔧 Fejlesztési lehetőségek
- [ ] 🔄 Dinamikus adatbetöltés API-n keresztül
- [ ] 🔍 Keresési és szűrési lehetőségek
- [x] 📱 Reszponzív megjelenítés mobileszközökre