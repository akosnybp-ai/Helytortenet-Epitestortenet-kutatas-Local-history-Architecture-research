# Helytörténet és Építéstörténeti Tudományos Kutatás - Rákosmente

## Projekt áttekintés

Ez a digitális gyűjtemény a **Budapest XVII. kerületének (Rákosmente)** helytörténeti és építéstörténeti vonatkozású tudományos kutatási anyagainak, régi fotóinak és dokumentumainak a központi, verziókövetett tárolója.

Célunk, hogy strukturált formában őrizzük meg a kerület (Rákoscsaba, Rákoshegy, Rákosliget, Rákoskeresztúr, stb.) múltját, és hozzáférést biztosítsunk a kutatóknak és az érdeklődőknek a forrásokhoz.

---

## Célok

1.  **Digitális Archívum:** Rendszerezett és hosszú távon megőrzött digitális másolatokat biztosítani az eredeti forrásokról.
2.  **Kereshetőség:** A metaadatok (fájlnevek, leírások) segítségével maximalizálni a kereshetőséget.
3.  **Együttműködés:** Lehetővé tenni a közösségi tudásbázis bővítését (pl. képek azonosítása, hibák javítása).
4.  **Verziókövetés:** Nyomon követni minden változtatást, ezzel biztosítva a kutatás átláthatóságát.

---

## Gyűjtemény Struktúrája

A repozitórium tartalma tematikus mappákba van rendezve a könnyebb navigáció és adatgazdálkodás érdekében:

| Mappa | Tartalom | Példa almappák |
| :--- | :--- | :--- |
| **[Képek](Képek/)** | Régi fotók, térképek, képeslapok. | `Épületek/`, `Utcaképek/`, `Személyek/`, `Rákosliget/` |
| **[Dokumentumok](Dokumentumok/)** | Szkennelt levéltári anyagok, újságcikkek, hivatalos iratok (PDF, DOC). | `Újsagcikkek/`, `Anyakönyvek/` |
| **[Kutatasi-anyagok](Kutatasi-anyagok/)** | Kutatási jegyzetek, elemzések, forráslisták, feldolgozási jegyzőkönyvek. | `Feldolgozasi-jegyzokonyv/` |
| **[Adatbazis](Adatbazis/)** | Strukturált adatok (pl. CSV exportok, metaadat-táblázatok). | `kepek_metadata.csv` |

**Fájlnév Konvenció:** A fájlnevek minden esetben információs kulcsszavakat tartalmaznak a kereshetőség maximalizálása érdekében:
`[ÉV-HÓ-NAP]_[Helyszín]_[Leírás]_[Azonosító].kiterjesztés`
*Példa:* `1932-05-10_Rákoscsaba-Foter_Villas_ismeretlen-foto.jpg`

---

## Keresés és Azonosítás

Mivel a GitHub alapvetően kódtároló, a vizuális AI-keresés nem érhető el közvetlenül. A hatékony keresés a **szöveges metaadatok** használatán alapul:

1.  **GitHub Kereső:** Használd a repozitórium tetején található keresőmezőt. Ez átvizsgálja a **fájlneveket** és az **összes szöveges tartalom** (beleértve a `README.md` és a leírásokat tartalmazó `.md` fájlokat).
2.  **Leírás Fájlok (`.md`):** Minden fontos kép/dokumentum mellett található egy `.md` kiterjesztésű fájl, amely tartalmazza:
    * Azonosító adatokat (pl. rendszámok, utcanevek, évszámok).
    * **OCR-rel kinyert szövegeket** (manuálisan átírva).
    * Vizuális kulcsszavakat (pl. `vasútállomás`, `villamos`, `polgárház`, `szecesszió`).
3.  **Keresési példák:**
    * Keresd a rendszámot: `IR-00-29`
    * Keresd a helyszínt: `Rákosliget Iskola`
    * Keresd a vizuális tartalmat: `villamos sín`

---

## Hozzájárulás

A gyűjtemény a helyi közösség és a kutatók együttműködésével a legteljesebb. Kérjük, segíts a bővítésben és a pontatlanságok javításában!

* **Issue nyitása:** Használd az **Issues** fület hibák bejelentésére, hiányzó információk pótlására, vagy ötletek javaslására (pl. "Hibás dátum a Rákoskeresztúri térképen", "Új fotó forrása Rákoscsabáról").
* **Pull Request (PR):** Ha van hozzá technikai tudásod, közvetlenül is küldhetsz PR-t új fájlok (képek, leírások) hozzáadásával.

---

## Licenc

Ezt a gyűjteményt a **Creative Commons Nevezd meg! – Így add tovább! 4.0 Nemzetközi (CC BY-SA 4.0)** licenc alatt tesszük közzé.

Ez biztosítja, hogy az anyagokat szabadon felhasználhatod, másolhatod és adaptálhatod kutatási és oktatási célokra, feltéve, hogy:

1.  **Nevezd meg:** Megjelölöd az eredeti forrást (pl. "Forrás: Helytörténet és Építéstörténeti Tudományos Kutatás / GitHub").
2.  **Így add tovább:** Az általad módosított vagy felhasznált anyagokat azonos licenc alatt teszed közzé.

---
*Készült: 2023.11.19.*
