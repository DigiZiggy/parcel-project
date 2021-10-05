Parcel pakendustööriista peale ehitatud projekt
===============================

Parcel on ülikiire, null-konfiguratsiooniga veebirakenduste
komplekteerija. See pakub hämmastavalt kiiret jõudlust,
kasutades mitmetuumalist töötlemist. Parcel ei vaja selle
käivitamiseks ühtegi konfiguratsiooni, erinevalt teistest
pakendustööriistadest, mis vajavad palju seadistamist.
See on sisuliselt pistikprogramm.

## Projekti taust

Seoses KILP 2021 tehniliste töödega on vaja ressursside halduse
front-end arenduse stacki uuendada ja üle minna vanadelt
tehnoloogiatelt uutele.

Lisaks Reacti uuendamisele on vaja üle minna ka kaasaegsele
ehitus- ja pakendustööriistale.


- [Nõuded ehitus- ja pakendustööriistale](#nõuded-ehitus--ja-pakendustööriistale)
- [Kuidas kasutada](#kuidas-kasutada)


## Nõuded ehitus- ja pakendustööriistale

### 1. Kuidas mõjutab arenduse kiirust?
Ehitamise protsessi kiirus, Hot Module Replacement.

### 2. Peab toetama:

- React
- JSX
- TypeScript
- SCSS (ka CSS mooduleid)

### 3. Peab olema võimalikult lihtsalt konfigureeritav.

### 4. Lisavõimalused (tuleviku arendusi silmas pidades):

- Tree shaking
- Code splitting
- Automaatne formattimine (eslint, Prettier)


## Kuidas kasutada

Ehitamiseks 
```
npm run build
```

Jooksutamiseks

```
npm run start
```

Juurdepääs ```http://localhost:1234 ```
