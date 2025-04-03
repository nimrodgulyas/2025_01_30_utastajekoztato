## MÁV utastájékoztató

Ez a projekt egy egyszerű webes felület, arra próbáltam törekedni, hogy a MÁV utastájékoztatóhoz hasonló legyen. A weboldal **HTML** és **CSS** használatával jött létre és egy táblázatos formátumban jeleníti meg az aktuális menetrendet.

![alt text](https://www.balatonmariafurdo.hu/wp-content/uploads/2019/11/post_m%C3%A1v.jpg)

### 🤖 Funkciók (Nem valós idejű)
- 🚉 Induló és érkező vonatok listázása táblázatban
- ⏰ Állomás, indulási és érkezési idők megjelenítése

### 💡 Használat
Egyszerűen nyisd meg a `https://github.com/nimrodgulyas/2025_01_30_utastajekoztato` weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.
#### 🍰 Élő demó

A projekt élőben megtekinthető az alábbi linken:  
[🔗 MÁV Utastájékoztató](https://github.com/nimrodgulyas/2025_01_30_utastajekoztato/)
###  Alap HTML szerkezet
```html
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
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
table, th, td {
    border: 1px solid;
    border-collapse: collapse;
  }

table {
    width: 80%; /* weboldal szélessége */
    background-color:rgb(26, 167, 68); /* háttérszín */
    color:rgb(255, 255, 255); /* betűszín */
    font-family: 'Courier New'; /* betűtípus */
    font-size: 25px; /* betűméret */
}
  

th {
    background-color: black;
}

#keses{
    background-color: red;
}
.paratlan_sor{
    background-color: green;
}: 10px 10px 10px black;
}
```