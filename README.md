# PRAKTICKÁ PŘÍRUČKA VLASTNÍKA KRYPTOMĚN

## HODL ZA ZIVOTA I PO NĚM

S laskavým svolením Pavla Urbaczku z advokátní kanceláře [Blockchain legal](https://www.blockchainlegal.cz/)


## OBSAH

[Obecná doporučení](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch01.md)

[Peňeženky a způsoby uložení - Jak uchovávat kryptoměny?](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch02.md)

[Zálohy peněženek - Jak pracovat se zálohami](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch03.md)

[Pokročilejší postupy - Jak dále zvýšit bezpečnost](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch04.md)

[K návodu - Pro sebe i ostatní](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch05.md)

[Jak na to - Z teorie a praxe](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch06.md)

[Pro případ smrti - Nežijeme věčně](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch07.md)

[Přílohy](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch08.md)


## Vygenerování ePub publikace

```
pandoc -o my-ebook.epub \
--metadata title="HODL ZA ŽIVOTA I PO NĚM" \
title.txt \
predmluva.md \
ch01.md \
ch02.md \
ch03.md \
ch04.md \
ch05.md \
ch06.md \
ch07.md \
ch08.md \
--epub-cover-image=images/cover.png \
--epub-metadata=metadata.xml \
--toc \
--toc-depth=2
```