[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=7842432&assignment_repo_type=AssignmentRepo)
# Vlastní webová stránka

Vytvořte vlastní malý tématický web pomocí HTML a CSS. Toto zadání slouží jako závěrečná práce a finální rekapitulace probraného učiva webové větve předmětu ALGoritmizace.

Web může a musí být na libovolné přijatelné téma. Pokud Vás žádné téma nenapadá, použijte téma referátu na IKT. Text ani obrázky nemusí být nutně Vaše.

Pro pojmenování tříd je doporučená metodika [BEM](http://getbem.com/introduction/).

Editací tohoto souboru a náhradou ``[ ]`` za ``[x]`` můžete evidovat, které body zadání už máte splněné.

## Body zadání

### HTML, struktura souborů

* [x] Web má alespoň dvě stránky provázané společnými styly
* [ ] HTML kód je validní bez chyb ve [validátoru](https://validator.w3.org/)
* [x] HTML značky dávají smysl, kód obsahuje ``<article>``, ``<section>``, ``<header>``, ``<nav>``.
* [x] Navigace mezi stránkami je tvořená přes ``<nav><ul><li><a>`` a je funkční i po zkopírování na lokální disk
* [x] Soubory webu jsou členěny do složek (např. ``/styles``, ``/images``, ``/fonts``)
* [x] Soubory webu se nacházejí v GitHubovém repozitáři
* [x] V repozitáři se soubory ocitly pomocí commitů a pushů a těch je více než 3, rozprostřených do celé doby vypracovávání zadání
* [x] Web je dostupný přes Github Pages (do README.md přidejte [odkaz](https://pslib-cz.github.io/2021-p1a-web-vlastni-web-MartinRostejnsky/news.html))
* [ ] Celková načítaná velikost jednotlivých stránek nepřesahuje jednotky MiB
* [x] Stránka obsahuje formátovaný seznam zdrojů textu a obrázků

### CSS, vzhled

* [x] Stránky používají několik souborů stylů, jeden z nich je [normalize](https://necolas.github.io/normalize.css/)
* [x] Ke stránkám jsou připojeny externí fonty (např. přes [Google Fonts](https://fonts.google.com/))
* [x] Stránka obsahuje horizontální nebo vertikální menu s odkazy na celou plochu nabídky
* [x] Vzhled stránek je zamýšlen na mobilní telefon pro rozměr od cca 360px do 960px. Content-wrapper má omezení na ``max-width: 960px; margin: 0 auto;``
* [x] Obrázky mají rozumnou velikost pro mobilní telefon
* [x] Velikosti písem jsou odvozeny od kořenového elementu
* [x] Velikosti mezer kolem prvku jsou odvozeny od velikosti písma elementu
* [x] Web používá omezenou paletu barev a mezer (lze zajistit přes [proměnné v CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties))
* [x] Barevné schéma je vkusné a odpovídá tématu. Inspiraci můžete čerpat z [editoru palet](https://coolors.co/palettes/trending)
* [x] Šířka hlavního bloku stránky je omezená (tedy používá například ``width``, ``margin``, ``max-width``)
* [x] Web obsahuje obrázek v záhlaví zobrazovaný na celou velikost/výšku obrazovky
````    
.main-header {
    background-image: url(img_bg.jpg);
    min-height: 100vh;
}
````
* [x] Styly definují vzhled prvků podle typografických zvyklosti (velikosti nadpisů, formát odstavců)
* [x] Odkazy (například menu) využívají efekt ``hover``
* [x] Za nebo před odkazy v textu je přidána ikonka (např. šipka) (využití ``::before`` nebo ``::after``)

### Vyzkoušejte nad rámec probrané látky

Po splnění předchozích bodů

* [x] Na webu je použitý jednoduchý efekt [paralaxního obrázku](https://www.w3schools.com/howto/howto_css_parallax.asp)
* [x] Pro layout stránky je použit [flex](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [x] Jsou použity ikonky přes Font Awesome nebo [IcoMoon](https://icomoon.io/)
* [x] vytvořte galerii obrázků tvořenou náhledy vedle sebe (``display: flex`` nebo ``inline-block``)
* [ ] Použijte pozadí přes lineární nebo radiální gradient
* [x] + jakékoli další vylepšení, kterým chcete zanechat přetrvávající dojem

## Kde hledat řešení a inspiraci?

* [CSS Tricks Guides](https://css-tricks.com/guides/)
* [Metodika BEM](http://getbem.com/introduction/)
