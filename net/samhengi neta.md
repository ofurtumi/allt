# samhengi, hlutnet og samhengisþættir
eru hlutir sem gott er að kunna um [[net]]

## samhengi
óstefnt net er kallað **samanhangandi**, *e. connected*, ef það er vegur á milli allra tveggja aðskildra hnúta í netinu, *ath. ekki allir tengdir saman, bara allir með ehv tenginu*, einfalt net sem er ekki **samanhangandi** er þá einfaldlega **ósamanhangandi**, *e. disconnected*

## hlutnet
*e. subgraph*, nets $A$ er net $B$ þar sem **hnútamengi** $B$, *mengi allra hnúta í $B$*, er **hlutmengi** í **hnútamengi** $A$, og **leggjamengi** $B$ er líka hlutmengi **leggjamengis** $A$

## samhengisþáttur
*e. connected components*, nets $A$ er hlutnet $A$ sem er **samanhangandi** og **óstækkanlegt**, ósamanhangandi net hafa alltaf meiri en einn samhengisþátt, þe. samhengisþáttur táknar fjölda hlutneta í neti

## brú
*e. bridge*, er leggur sem hefur þann eiginleika að ef maður **tekur hann í burtu** eykst samhengisþáttur netsins, þe. leggur $e$ í neti $G$ væri brú, ef og aðeins ef hlutnetið sem myndast með því að fjarlægja $e$ úr $G$ hefur fleiri samhengisþætti en $G$

## slithnútur
Hnútur $v$ í $G$ kallast **slithnútur**, *(e. cut vertex)*, ef hlutnetið sem myndað er með því  
að fjarlægja $v$ úr $G$ hefur fleiri samhengisþætti en $G$

## hnúta- og leggjasamhengi
talan $\lambda(G)$ táknar **leggjasamhengi**, *e. edge connectivity*, netsins $G$, það þýðir að $\lambda(G)$ táknar hversu marga leggi þarf að fjarlægja úr $G$ til þess mynda net sem er **ósamanhangandi**
**hnútasamhengi** er það sama nema fyrir hnúta en það stendur ekki í glósunum hvernig það er táknað 