# Rejtett képek – háttérbeállítás

Ez a tároló kizárólag a weboldal nyilvános háttérszínét és a hozzá tartozó szerkesztő konfigurációját tartalmazza. A weboldal forráskódja külön, privát tárolóban marad. Ide nem kerülhet jelszó vagy személyes adat.

## Egyszeri beállítás

1. A tulajdonos a https://app.pagescms.org/ oldalon belép GitHubbal, és elfogadja a szolgáltatás feltételeit.
2. A Pages CMS GitHub App számára **csak ezt a tárolót** választja ki.
3. Megnyitja a `rejtett-kepek-beallitasok` tároló `main` ágát a szerkesztőben.
4. A Collaborators résznél meghívja Ildikót a saját e-mail-címével. E-mailes szerkesztőként Ildikónak nem kell GitHub-fiók.

A felhasználó kérésére egyelőre csak az új világoskék háttér kerül ki. A bekötés és a meghívás még nincs elvégezve, a weboldal jelenleg nem olvassa ezt a beállítást.

## Háttércsere

A szerkesztőben: **Megjelenés → Háttér színe → szín kiválasztása → Save**.

Az oldalhoz kapcsolás után nyisd meg vagy frissítsd a weboldalt. A háttér minden látogatónál változik, nem csak a szerkesztő saját böngészőjében. A már nyitott lap frissítéséig a korábbi szín marad. A GitHub gyorsítótára miatt a mentés megjelenése néhány percet is igénybe vehet. Nincs külön weboldal-feltöltés.

A későbbi integráció csak színneveket fogadhat el, anonim kérésben, titkos kulcs nélkül; ne késleltesse az oldalváltást. Az `appearance.json` megengedett értékei: `blue`, `cream`, `sage`, `rose`, `white`. Hibás vagy elérhetetlen beállítás esetén a beépített világoskék legyen a tartalék. Ez a betöltő még nincs bekötve a demóba.

Demó: https://pritz-ildiko-prototipus.andras-vidor.chatgpt.site/

Hivatalos útmutatók: https://pagescms.org/docs/quick-start/ és https://pagescms.org/docs/configuration/collaborators/
