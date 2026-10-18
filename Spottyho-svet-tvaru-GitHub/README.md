# Spottyho svět tvarů

Česká responzivní vzdělávací hra pro děti. Poznávání sedmi geometrických tvarů a hledání dvojic podle tvaru nebo barvy. Každá hra má deset úloh a závěrečné vyhodnocení.

## Spuštění na počítači
Rozbalte ZIP a otevřete soubor `index.html` v prohlížeči. Není potřeba instalace ani server. Soubor `spotty.png` a ostatní soubory ponechte vedle `index.html`.

## Vložení na GitHub a zveřejnění přes GitHub Pages
1. Na GitHubu vytvořte nový repozitář. Pro bezplatné zveřejnění přes Pages zvolte veřejný repozitář.
2. Rozbalte ZIP. Přes **Add file → Upload files** nahrajte všechny rozbalené soubory přímo do hlavní složky repozitáře. Nenahrávejte samotný ZIP. Soubor `index.html` musí být v hlavní složce.
3. Uložte nahrání přes **Commit changes**.
4. Otevřete **Settings → Pages**.
5. V části **Build and deployment** vyberte **Deploy from a branch**.
6. Vyberte větev **main** a složku **/ (root)** a klikněte na **Save**.
7. Po dokončení publikace se v části Pages objeví odkaz na hru.

## Soubory
- `index.html` – stránka hry
- `style.css` – responzivní vzhled
- `game.js` – herní logika
- `spotty.png` – dodaný obrázek králíčka Spottyho
- `.nojekyll` – přímé publikování statických souborů

Hra nemá závislosti, sestavení, reklamy ani analytiku. Ve stažené verzi používá systémové písmo, takže nepotřebuje stahovat písmo z internetu. Vlastní nahraný obrázek se ukládá pouze v prohlížeči daného zařízení. Pro sdílenou změnu výchozího obrázku nahraďte `spotty.png` v repozitáři.
