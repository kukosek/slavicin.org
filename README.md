# Slavicin.org

Rozcestník Slavičína - přehled webů od místního lidu.

---

## Vývoj

Tato stránka je staticky generována pomocí programu Hugo. Pokud
chcete přidávat nebo měnit obsah, stáhněte si ho.

Pokud chcete dělat nějaké změny, tak nejlepší bude
když tady na githubu kliknete na "fork" a naklonujete
si do počítače ten váš fork přes GIT.

Takže pokud ve vašem forku uděláte nějaké commity,
dejte pull request a já vám ho příjmu.

Pro spuštění vývojového serveru hugo spusťte ve složce s tímhle
repem příkaz `hugo server`

## Úpravy obsahu

Funguje to tak, že ten program vezme vstupní soubory ze složky content,
vloží to do templatů ze složky themes/signpost a vyplivne
výstupné HTMLka, které už se dají lehce dát na jakýkoli web server
či CDN.

### Nový příspěvek v novinkách

Ve složce s tímhle repem spusťte příkaz

```bash
hugo new posts/novinky moje-novinka.md
```

Ten vytvoří základní soubor `content/novinky/moje-novinka.md`, který můžete upravovat,
napsat nějaký článek a tak.

Samozřejmě to jde udělat i bez toho příkazu `hugo new` - stačí vám
duplikovat nějaký z předchozích souborů.

Obsah příspěvku se píše ve formátu [markdown](https://www.markdownguide.org/basic-syntax)

### Přidání stránky

Podobně to funguje se stránkama, takže stačí dát

```bash
hugo new sites/dalsi-stranka.md
```

a pak to upravit.
