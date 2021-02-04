# PRAKTICKÁ PŘÍRUČKA VLASTNÍKA KRYPTOMĚN

## Hodl za života i po něm

[ePub ke stažení zde](https://github.com/pavoltravnik/prirucka-hodlera/raw/master/HODL.epub)

[PDF ke stažení zde](https://www.blockchainlegal.cz/cs/ebook/)

S laskavým svolením Pavla Urbaczky z advokátní kanceláře [Blockchain legal](https://www.blockchainlegal.cz/)


## OBSAH

1. [Obecná doporučení](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch01.md)
2. [Peněženky a způsoby uložení - Jak uchovávat kryptoměny?](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch02.md)
3. [Zálohy peněženek - Jak pracovat se zálohami](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch03.md)
4. [Pokročilejší postupy - Jak dále zvýšit bezpečnost](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch04.md)
5. [K návodu - Pro sebe i ostatní](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch05.md)
6. [Jak na to - Z teorie a praxe](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch06.md)
7. [Pro případ smrti - Nežijeme věčně](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch07.md)
8. [Přílohy](https://github.com/pavoltravnik/prirucka-hodlera/blob/master/ch08.md)



## Vygenerování ePub publikace

```
pandoc -o HODL.epub \
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
